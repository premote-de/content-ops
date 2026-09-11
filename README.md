# content-ops

Memory and ops for the premote content engine (OpenClaw on Lightsail, eu-central-1).

**Applicants:** your take-home task is in [`CHALLENGE.md`](CHALLENGE.md) (time box: 2 hours).

- `agent/AGENTS.md` — operating manual (source of truth; sync to workspace root on change)
- `watchlist.yaml` — compliance sources the engine crawls (add via Slack: "add this page as a source")
- `competitors.yaml` — competitor properties diffed weekly
- `brand-voice.md` — tone-of-voice guide (extracted from the live corpus)
- `pipeline/content-style.md` — article structure & GEO format rules
- `research/` — per-article research notes (facts + quotes + source URLs)
- `roadmap/` — rolling 6-week content plans with per-article justification
- `reports/` — activity log, monthly performance + spend reports
- `snapshots/` — crawl snapshots for change detection
- `slack/app-manifest.yaml` — Slack app definition for the bot

Infra: Lightsail `content-engine` (<static-ip>, Frankfurt), OpenClaw pinned to 2026.7.1 (image digest in ~/openclaw/.env on the box), models via Amazon Bedrock EU profiles (Sonnet 5 primary, Haiku 4.5 fallback).

> **Note on this copy:** third-party companies are anonymized in this repository. The main competitor tracked by the engine is **Competitor A** (`competitor-a.example`; `competitor-a-legacy.example` for its former domain; `competitor-a-us.example` for its US sister site). The other tracked competitors are **Competitor B to E** (`competitor-b.example` to `competitor-e.example`). Further competitor names appear as `[competitor]` or `[competitor-brand]`, brand keywords as `[competitor-a brand]`. The server IP, Slack user IDs and customer names are replaced with placeholders. The engine's working notes were written in German; this copy is translated into English. Search keywords are kept as the original German queries, because they are the actual search terms with their volumes. Apart from the placeholders and the translation, the content is unchanged.
