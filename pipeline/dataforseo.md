# DataForSEO — how the engine picks and justifies topics

Credentials: env `DATAFORSEO_LOGIN` + `DATAFORSEO_PASSWORD` (HTTP Basic). Base: `https://api.dataforseo.com`.
All POST bodies are JSON **arrays** of task objects. Germany = `"location_code": 2276`, `"language_code": "de"`.
**Always use real umlauts in keywords** ("grenzüberschreitende", not "grenzueberschreitende") — ASCII variants return no volume.

## The two calls every article run makes (BEFORE writing anything)

1. **Search volume** for 10–20 candidate keywords (~$0.09/call):
```
POST /v3/keywords_data/google_ads/search_volume/live
[{"keywords": ["a1 bescheinigung", "workation", ...], "location_code": 2276, "language_code": "de"}]
```
→ `tasks[0].result[].search_volume`

2. **SERP check** for the chosen main keyword (~$0.004/call, depth 20):
```
POST /v3/serp/google/organic/live/regular
[{"keyword": "…", "location_code": 2276, "language_code": "de", "depth": 20}]
```
→ organic items: note the rank of `premote.de` (usually absent) and of competitors
(`competitor-a-legacy.example`/`competitor-a-us.example`, `competitor-b.example`, `competitor-c.example`, `competitor-d.example`, `competitor-e.example`) plus who holds top 3.

Optional (weekly/roadmap, ~$0.11/call): `POST /v3/dataforseo_labs/google/ranked_keywords/live`
`[{"target": "premote.de", "location_code": 2276, "language_code": "de", "limit": 100}]` — all keywords a domain ranks for; run for premote and one competitor to find gap keywords.

## Decision rules for topic selection
- Prefer topics whose keyword cluster has **combined volume ≥ 100/month** (DE). Below that, the topic needs an explicit strategic reason (authority piece, regulatory change, sales enablement) stated in the "Why this topic" line.
- Prefer keywords where a **competitor ranks top 10 and premote does not** — name the competitor and their position.
- Head keywords owned by authorities (DVKA, EU) are fine for authority pieces; commercial keywords (workation, A1-Antrag) are where premote should fight for positions.

## The "Why this topic" line (goes into the final Slack message)
`Why this topic: "<keyword>" has <X> searches/month (DE); premote ranks <not in top 20 | #N>, <Competitor> ranks #M — the article targets this gap. (DataForSEO, <date>)`

## Budget
Balance check: `GET /v3/appendix/user_data`. Typical cost per article run: **$0.10–0.20**. Log the per-run cost in the run log.

## Reference numbers (measured 2026-08-21, DE)
a1 bescheinigung 12100 · workation 8100 · a1 bescheinigung beantragen 1600 · homeoffice im ausland 260 · homeoffice ausland 50 · grenzüberschreitende telearbeit 10 · telearbeit ausland 10
