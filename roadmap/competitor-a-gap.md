# Competitor A keyword gap (DataForSEO Labs, 2026-09-07, DE; refreshed 2026-09-10, 2026-09-11)
# Competitor A domain: competitor-a-legacy.example | rule: volume>=30, Competitor A in top 20, premote absent or >5 behind
# The daily article picks the TOPMOST unused entry (mark used with [x] + date + PR link).

| used | volume | Competitor A rank | premote rank | keyword |
|------|--------|---------|--------------|---------|
| [x] | 1900 | 13 | — | wie sieht eine sozialversicherungsnummer aus |
| [skip] | 1600 | 10 | — | [competitor-a brand] |
| [skip] | 1000 | 20 | — | senior manager |
| [x] 2026-09-08 | 880 | 14 | 69 | was bedeutet eta |
| [x] 2026-09-08 | 590 | 11 | 62 | was heißt eta |
| [skip] | 390 | 6 | — | senior management |
| [x] | 320 | 18 | — | wie sieht sozialversicherungsnummer aus |
| [skip] | 260 | 11 | — | x automatische übersetzung deaktivieren |
| [x] | 260 | 16 | — | zusammensetzung sozialversicherungsnummer |
| [x] | 210 | 18 | — | sozialversicherungsnummer wie sieht die aus |
| [skip] | 170 | 6 | — | was ist ein senior manager |
| [x] | 170 | 13 | — | versicherungsnummer sv |
| [x] | 170 | 18 | — | wie ist die sozialversicherungsnummer aufgebaut |
| [skip] | 140 | 3 | — | [competitor-a brand] login |
| [skip] | 140 | 16 | — | automatische übersetzung ausschalten |
| [skip] | 140 | 17 | — | senior executives |
| [x] | 140 | 17 | — | was ist die sv-nummer auf der lohnabrechnung |
| [x] | 140 | 20 | — | sozialversicherungsnummer was ist das |
| [x] | 140 | 20 | — | welches ist die sozialversicherungsnummer |
| [skip] | 110 | 15 | — | google automatische übersetzung aktivieren |
| [x] | 110 | 16 | — | sozialversicherungsnummer abkürzung |
| [x] | 110 | 20 | — | sozialversicherungsnummer wie viele stellen |
| [skip] | 90 | 5 | — | google automatische übersetzung deaktivieren |
| [skip] | 90 | 10 | — | google translate deaktivieren |
| [skip] | 90 | 11 | — | google übersetzer ausschalten | -- irrelevant, no premote topic relevance (Google Translate setting)
| [x] | 90 | 20 | — | wie sieht die sv nummer aus |
| [skip] | 70 | 14 | — | senior leaders |
| [x] 2026-09-09 | 70 | 15 | 61 | eu sozialversicherungsnummer |  -- Cluster: eu sozialversicherungsnummer (70), europäische sozialversicherungsnummer (10). Article: sozialversicherungsnummer-eu-ausland. DataForSEO SERP 2026-09-09: Competitor A #15, premote not in top 20.
| [x] | 70 | 20 | — | abkürzung sozialversicherungsnummer |
| [skip] | 50 | 6 | — | was bedeutet senior manager |
| [skip] | 50 | 15 | — | jobflexx |
| [x] | 50 | 18 | — | sozialversicherungsnummer länge |
| [skip] | 40 | 11 | — | senior manager bedeutung |

# Refresh 2026-09-10 — base table fully worked through (0 unused). competitor-a-legacy.example pull (DE) returned
# no new rows with rank<=20 (all qualifying hits already captured above). competitor-a-us.example pull (DE)
# yielded 12 new hits, of which only 1 with rank<=20 + vol>=30 (criterion met):
| [x] 2026-09-10 | 50 | 17 | not in top 20 | work from greece | -- Cluster: work from greece (50) + working from greece (50) ≈ 100/mo in total (workation griechenland 20, homeoffice griechenland 10 too small for the cluster). Article: workation-griechenland. Rank source: DataForSEO Labs ranked_keywords for competitor-a-us.example (snapshot 2026-07-30) — competitor-a-us.example/remote-work/greece/ rank #17 for "work from greece". Live SERP recheck 2026-09-10 (depth20) shows a volatile top 20 without competitor-a-us.example/Competitor A (SERP fluctuation), premote.de not in top 20 in either check. Competitor A has a dedicated Greece remote work page, premote does not yet.
| [skip] | 8100 | 69 | — | global mobility solutions | -- rank too low (>20), no gap
| [skip] | 720 | 26 | — | [competitor-a-us brand] | -- competitor's own brand term, no content gap
| [skip] | 260 | 49 | — | google job home office | -- rank too low, no premote topic relevance
| [skip] | 260 | 53 | — | google jobs homeoffice | -- rank too low, no premote topic relevance
| [skip] | 170 | 44 | — | mobility solutions | -- rank too low, too generic
| [skip] | 110 | 109 | — | workation meaning | -- rank too low, no gap
| [skip] | 90 | 105 | — | eor meaning | -- rank too low; EOR is not in premote's scope according to the briefing
| [skip] | 70 | 40 | — | google jobs remote | -- rank too low, no premote topic relevance
| [skip] | 50 | 43 | — | nomad germany | -- rank too low, too generic for a dedicated article
| [skip] | 50 | 82 | — | unterschied remote und hybrid | -- rank too low, HR jargon without compliance relevance

# Refresh 2026-09-11 — dataforseo_labs ranked_keywords (rank<=20, DE) for competitor-a.example (58 hits) +
# competitor-a-legacy.example (48, legacy domain) + competitor-a-us.example (1, unchanged). All rows already captured (Sozialversicherungsnummer
# cluster, senior*, eta*, competitor-a-brand, google-übersetzer, work from greece) are already [x]/[skip] above. New,
# relevant candidates checked below via live SERP recheck (depth20, 2026-09-11):
| [x] 2026-09-11 | 90 | 2 | not in top 20 | certificate of coverage | -- Cluster: certificate of coverage (90/mo) + certificate of coverage usa (10) + certificate of coverage deutschland (10) + certificate of coverage a1 (10) + d usa 101 (70) ≈ 190/mo in total. Article: certificate-of-coverage (new glossary wiki article, complements a1-bescheinigung-usa/-kanada/-australien with the generic CoC system). Live SERP recheck 2026-09-11 (depth20, DE): competitor-a.example rank #2 (https://www.competitor-a.example/en-uk/hr-glossary/certificate-of-coverage), premote.de not in top 20. Rank source competitor-a: DataForSEO Labs ranked_keywords competitor-a.example (snapshot 2026-09-11).
| [skip] | 320 | 20 | #11 | posted workers | -- premote already ranks #11 (eu-entsenderichtlinie-posted-workers-directive), better than competitor-a #13/#20 in various snapshots — no clear gap, cluster already covered.
| [skip] | 480 | 8 | — | digital nomad visa | -- premote already ranks #6 (digital-nomad-visa), better than competitor-a #8 — no gap, topic already covered.
| [skip] | 110 | 12 | #5 | swiss work permit | -- premote already ranks #5 (arbeitsbewilligung-schweiz), better than competitor-a #14 — no gap.
| [skip] | 320 | 19 | — | mobiles arbeiten im ausland | -- Live SERP check 2026-09-11: top 19 entirely associations/law firms/HR portals (IHK, TK, Haufe, Personio etc.), neither competitor-a.example nor premote.de in top 20 — no Competitor A gap within the meaning of the rule (Competitor A must be in top 20).
| [skip] | 140 | 13/15 | — | us business visa / business visa usa | -- Live SERP check 2026-09-11 ("us business visa"): top 19 exclusively US embassy/law firms/visa service providers, neither competitor-a.example nor competitor-a-legacy.example in top 20 (ranked keywords snapshot was outdated) — no current gap.
| [skip] | 110 | 1 | — | a1-formular schweiz | -- Live SERP check 2026-09-11: DRV, EAK, DVKA, chambers dominate the top 10; premote itself already #11 (a1-bescheinigung-schweiz), competitor-a not in top 20 — no gap.
| [skip] | 50 | 12 | — | workation a1-bescheinigung | -- Volume too low (50) for a standalone article, topic already covered by a1-bescheinigungen-fuer-workations + a1-bescheinigung-usa/-schweiz.
