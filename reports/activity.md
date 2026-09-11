engine activity log

## 2026-09-06 — Digital Nomad Visa Deutschland (PR #21)
- Cluster: "digital nomad visa germany" (US 110/mo, UK 40/mo) + variants (germany digital nomad visa, does germany have a digital nomad visa, german digital nomad visa) ≈ 440/mo total (US+UK)
- Roadmap base table had been fully worked through; cluster newly uncovered by a repeat DataForSEO Labs pull (US location 2840) — see competitor-a-gap.md refresh 2026-09-06
- SERP verify: Competitor A/competitor-a-us.example ranks #20-22 (competitor-a-us.example/visa/digital-nomad-visa-germany/), premote not in top 20-22 (DataForSEO SERP depth-20/22, location US 2840 + UK 2826, 2026-09-06)
- Sources (4, all retrieved and read): Residence Act (AufenthG) section 21 full text (gesetze-im-internet.de, Wayback snapshot), Make it in Germany – EU Blue Card (BMWK portal, Wayback snapshot, 2026 salary thresholds), Make it in Germany – Self-Employment (BMWK portal, Wayback snapshot), Your Europe / EU citizens' portal (Schengen 90/180-day rule, retrieved live)
- Content: Germany has no dedicated digital nomad visa; comparison of the freelancer visa (Residence Act (AufenthG) section 21(5)) vs. EU Blue Card vs. Schengen 90/180-day short stay, comparison table, FAQ
- DE+EN wiki article "digital-nomad-visa-deutschland", backlinks added in digital-nomad-visa, digital-nomad-visa-kanada, digital-nomad-visa-neuseeland, digital-nomad-visa-malaysia; term registered in wiki.ts
- Branch content/digital-nomad-visa-deutschland, PR: https://github.com/premote-de/website/pull/21
- Build + link audit green (0 orphans, 0 stale links). Preview deployed (Vercel Ready): https://website-git-content-digital-nomad-visa-deutschland-premote.vercel.app
- Waiting for approval by Philipp/Johannes in #website-content.

## 2026-08-30 — Posted Worker Explained (PR #14)
- Cluster: "posted worker" (EN, ~480/mo UK) + variants (posted worker definition, posted employee, posted worker notification, among others) ≈ 550/mo total
- SERP verify: Competitor A ranks #14 (competitor-a.example/en-uk/hr-glossary/posted-worker-compliance-guide), premote not in top 20 (DataForSEO SERP depth-20, location UK 2826, 2026-08-30)
- Roadmap: comprehensive refresh 2026-08-30 (DE+EN DataForSEO Labs, 87 candidates checked, all except "posted worker" already covered/out of scope) — see content-ops/roadmap/competitor-a-gap.md
- Sources (3, all retrieved and read): European Commission (Employment/Social Affairs, PWD legal basis, core terms and conditions of employment, 12/18-month rule), European Labour Authority (sectors, enforcement, third-country nationals), German Customs (Zoll) EN page (minimum wage notification portal (Meldeportal Mindestlohn), Minimum Wage Notification Ordinance (MiLoMeldV), IMI for drivers)
- Content: English-language definition article, clear distinction between posted worker and business trip, comparison table PWD vs. A1 certificate (A1-Bescheinigung), FAQ
- DE+EN wiki article "posted-worker-explained", backlinks added in eu-entsenderichtlinie-posted-workers-directive, posted-workers-directive-und-equal-pay, a1-certificate-explained
- Branch content/posted-worker-explained, PR: https://github.com/premote-de/website/pull/14
- Build + link audit green. Preview deployed (Vercel Ready): https://website-git-content-posted-worker-explained-premote.vercel.app
- Waiting for approval by Philipp/Johannes in #website-content.

## 2026-08-25 — A1-Bescheinigung Schweiz (PR #9)
- Cluster: a1 bescheinigung für schweiz (390/mo, Competitor A rank 20; German for "A1 certificate for Switzerland") + variants (a1 bescheinigung schweiz, a1-formular schweiz, a1 schweiz, a1 bescheinigung schweiz beantragen) ≈ 1,090/mo total
- SERP verify: Competitor A HR glossary page ranks organically at #20, premote not in top 20 (DataForSEO Labs, 2026-08-25)
- Sources (4, all retrieved and read): Deutsche Rentenversicherung (German pension insurance, DRV) A1 FAQ, EAK Switzerland (Swiss Federal Compensation Office; A1 certificate/CoC), Basel-Stadt compensation office (Ausgleichskasse Basel-Stadt), BSV (Swiss Federal Social Insurance Office) forms page
- Content: supplements the generic A1 articles with Switzerland specifics — two posting (Entsendung) directions with different competent bodies/portals (DE→CH via health insurer/DRV/SV-Meldeportal, CH→EU via compensation office/ALPS), personal scope (EU/EEA/CH nationals only, DRV examples Norway/Turkey rejected), short-trip exemption despite tightened Swiss checks
- DE+EN wiki article, branch content/a1-bescheinigung-schweiz, PR: https://github.com/premote-de/website/pull/9
- Build + link audit green. Preview deployed (Vercel Ready).
- Backlink from a1-bescheinigung-basics added.
- Waiting for approval by Philipp/Johannes in #website-content.

## 2026-08-20 — New wiki article: EU framework agreement on cross-border telework
- Reason: content gap — no coverage of the multilateral EU framework agreement under Regulation (EC) No 883/2004 Art. 16(1) (cross-border telework), in force since 1 July 2023.
- Research: content-ops/research/grenzueberschreitende-telearbeit.md (DVKA translation, EUR-Lex Decision H14/2023, European Commission Guidance Note AC 137/23, Belgian Federal Public Service Social Security (FÖD Soziale Sicherheit)).
- Article: DE + EN, slug `grenzueberschreitende-telearbeit`, 7 H2 sections, comparison table (25/50% rule), FAQ (5 Q&As), 3 internal links (added bidirectionally in sozialversicherungsabkommen, elektronische-a1-bescheinigung-fuer-grenzgaenger, 183-tage-regel).
- Fixed along the way: hardcoded absolute path in scripts/link-audit.mjs (previously only ran on one specific developer machine).
- Build (`yarn build`) + link audit green. PR: https://github.com/premote-de/website/pull/1
- Status: waiting for approval by Philipp/Johannes in Slack #website-content.

## 2026-08-22 — Sozialversicherungsnachweis (PR #3)
- Cluster: sozialversicherungsnachweis (1,600/mo, Competitor A rank 29; German for "proof of social insurance"), sozialversicherungsnachweis arbeitgeber (170/mo, Competitor A rank 18)
- SERP verify: premote not in top 20; Competitor A minimally present; DRV/Wikipedia/lexware/AOK/DAK dominate
- Sources: DRV (x2), AOK, Minijob-Zentrale, DAK, Social Code Book IV (SGB IV) sections 4/5 (dejure.org) — all retrieved
- DE+EN wiki article, branch content/sozialversicherungsnachweis, PR: https://github.com/premote-de/website/pull/3
- Build + link audit green. Preview deployed (Vercel Ready).
- Waiting for approval by Philipp/Johannes in #website-content.

## 2026-08-23 — No new Competitor A gap topic
- Competitor A gap list was fully [x]/[skip] at the start of the turn. Fresh DataForSEO Labs pull (ranked_keywords, competitor-a-legacy.example, vol>=30, 269 KW paginated) + additional check of competitor-a-us.example, competitor-d.example, competitor-e.example, competitor-b.example.
- Result: no new qualifying gap (Competitor A rank<=20, premote absent/weakly represented, within compliance scope). Remaining candidates with Competitor A rank<=20 belong to the social insurance number/proof (Sozialversicherungsnummer/-nachweis) family (already covered by articles) or are job-title/brand searches with no compliance relevance.
- DataForSEO cost today: ~$0.15 (several ranked_keywords calls + 2 SERP checks).
- roadmap/competitor-a-gap.md updated (refresh block 2026-08-23) and committed.
- No PR today — next candidate will come from the weekly competitor sitemap/blog diff.

## 2026-08-25 — A1-Bescheinigung Schweiz (PR #9)
- Cluster: a1 bescheinigung für schweiz (390/mo, Competitor A HR glossary ranks organically at #20), a1 bescheinigung schweiz (390/mo), a1-formular schweiz (140/mo), a1 schweiz (140/mo), a1 bescheinigung schweiz beantragen (30/mo) = 1090/mo total.
- SERP verify (depth20, DE): premote not in top 20; Competitor A #20 organic confirmed.
- Beforehand, the e-visa/e-visum cluster (5400/mo) was checked and discarded: Labs rank #16/#10 did not hold up in the live SERP check (Competitor A not in top 20) and the topic is outside compliance scope (pure tourist visa topic). mobiles-arbeiten-im-ausland, sv-meldeportal-a1-bescheinigung, business-visa-us also checked and discarded (see roadmap comments).
- Sources (4, retrieved and read): DRV A1 FAQ, EAK Switzerland (ALPS portal), ak-bs.ch, BSV forms page.
- Article: DE+EN, slug `a1-bescheinigung-schweiz`, 4 H2 + FAQ, comparison table (posting direction DE↔CH), 3 internal links (a1-bescheinigung-basics [+backlink added], work-permit, sozialversicherungsabkommen).
- Branch content/a1-bescheinigung-schweiz, Build + link audit green, Vercel preview Ready.
- PR: https://github.com/premote-de/website/pull/9 — waiting for approval by Philipp/Johannes in #website-content.


## 2026-08-26 — thailand-aufenthaltsdauer
- Pipeline: Competitor A gap refresh (2026-08-26), cluster "thailand aufenthaltsdauer" (Competitor A #14-#19 live, premote absent; German for "Thailand length of stay"), 540 searches/month total.
- New wiki article DE+EN: 60-day visa exemption, Destination Thailand Visa (DTV), 180-day tax threshold.
- Sources: Thai Consulate Munich, Thai Consulate LA, BDO Thailand (3 independently retrieved sources).
- PR: https://github.com/premote-de/website/pull/10 (branch content/thailand-aufenthaltsdauer)
- Preview: https://website-git-content-thailand-aufenthaltsdauer-premote.vercel.app/{de,en}/wiki/thailand-aufenthaltsdauer
- Build ✅ link audit ✅ premote check ✅
- Status: waiting for approval (Philipp/Johannes) in Slack.

## 2026-08-27 — A1 Certificate Explained (PR #11)
- Pipeline: Competitor A gap refresh (2026-08-27, new Labs pull competitor-a.example 192 KW). Roadmap was previously fully x/skip; new candidate found and verified.
- Cluster: a1 certificate (390/mo DE), a1 form (6600/mo DE, same search intent), what is a1 certificate (30/mo) = 7020/mo total.
- SERP verify (depth20, DE): Competitor A ranks organically at #4 (competitor-a.example/en-uk/hr-glossary/a1-certificate), premote not among the top 17 visible results.
- Target audience: international/English-speaking HR teams, US/UK group subsidiaries, expats — gap relative to the existing German A1 article family.
- Sources (5, retrieved and read): DRV FAQ, European Labour Authority glossary, European Commission (incl. note on the EU reform of April 2026), EUR-Lex Recommendation No A1, UK HMRC National Insurance Manual NIM33115.
- Article: DE+EN, slug `a1-certificate-explained`, 7 H2 + FAQ, 2 comparison tables (scope, terminology DE/EN/EU), 4 internal links (bidirectional: a1-bescheinigung-basics now links back as well).
- Branch content/a1-certificate-explained, Build + link audit green (84/84 reachable, 0 orphans), premote casing check 0 hits.
- PR: https://github.com/premote-de/website/pull/11
- Preview: https://website-git-content-a1-certificate-explained-premote.vercel.app/{de,en}/wiki/a1-certificate-explained (verified, HTTP 200, correct titles)
- Status: waiting for approval (Philipp/Johannes) in Slack; auto-merge after 6h if no objection.

## 2026-08-28 — No new Competitor A gap topic
- Previous session aborted at step 2 ("LLM request failed"), Slack status message was left stuck on "Article in progress" — picked up and completed in this session.
- Fresh DataForSEO Labs pull (ranked_keywords, competitor-a.example, DE, vol>=30, rank<=20, 192 KW total, 69 qualifying candidates) — identical list to 2026-08-27, all already [x]/[skip] except 2 rows without a live SERP check.
- Live SERP depth-20 check on the 2 open candidates: "dauerhaftes homeoffice im ausland" (90/mo; German for "permanent home office abroad") and "visum verlängern thailand" (70/mo; German for "extend visa Thailand") — both negative, Competitor A not among the top 19 visible results (Labs ranks outdated); the second is also outside compliance scope (pure extension procedure).
- Result: no new qualifying gap (Competitor A rank<=20 confirmed live, premote absent/weakly represented, within compliance scope).
- DataForSEO cost today: ~$0.04 (1x ranked_keywords + 2x SERP check).
- roadmap/competitor-a-gap.md updated (refresh block 2026-08-28) and committed.
- No PR today. Four PRs still open and waiting for approval by Philipp/Johannes: #4 (entsendebescheinigung), #6 (TOC sidebar fix), #8 (Global Mobility), #10 (Thailand-Aufenthaltsdauer). PR #11 (A1 Certificate Explained) has since been merged.
- Slack status message (#website-content) updated from "Article in progress" to the end-of-day summary.
- Next candidate will come from the weekly competitor sitemap/blog diff.

## 2026-08-28 — A1-Bescheinigung USA (PR #12)
- Pipeline: Competitor A gap refresh 2026-08-28b (after the initial "no gap" in 2026-08-28a; second attempt with a Perplexity lead + Competitor A sitemap cross-check + a second independent live SERP call for a1-bescheinigung-usa, since the first call failed in the previous session).
- Cluster: a1-bescheinigung usa (110/mo DE; German for "A1 certificate USA"), a1 bescheinigung für usa (30/mo) = 140/mo total.
- SERP verify (depth19, DE, DataForSEO): Competitor A ranks organically at #17 (competitor-a.example/de/loesungen/a1-bescheinigung), premote.de not among the 19 visible results.
- 5 further candidates from Perplexity + Competitor A sitemap checked and discarded (mobiles-arbeiten-im-ausland-recheck, entsandter-arbeitnehmer, entsendebescheinigung, iso-31030/travel-risk-management, remote-onboarding) — all Labs-outdated or out of scope.
- Topic: the A1 certificate applies only within the EU/EEA/Switzerland; for the USA the German-American social security agreement (Sozialversicherungsabkommen, 1976) applies, with form D/USA 101 (Certificate of Coverage) — previously covered only in general terms via sozialversicherungsabkommen, no USA-focused article.
- Sources (4, retrieved and read): SSA.gov Totalization Agreement Germany (via Wayback, since ssa.gov blocks live access), DRV official USA page, DRV rvRecht legal portal, touring-artists.info (independent specialist portal).
- Article: DE+EN, slug `a1-bescheinigung-usa`, 8 H2 + FAQ, 1 comparison table (A1 vs. D/USA 101), 4 internal links.
- Branch content/a1-bescheinigung-usa, Build + link audit green (84/84 reachable, 0 orphans), premote casing check 0 hits.
- PR: https://github.com/premote-de/website/pull/12
- Preview: https://website-git-content-a1-bescheinigung-usa-premote.vercel.app/{de,en}/wiki/a1-bescheinigung-usa (verified, HTTP 200, correct titles)
- Status: waiting for approval (Philipp/Johannes) in Slack.

## 2026-08-29 — Company Offsite Compliance (PR #13)
- Pipeline: Competitor A gap refresh 2026-08-29 (competitor-a-gap.md gone through exhaustively, roadmap refresh block extended with skip/dedupe rows, A1 reform 2026 whitepaper flagged as a watch item — no search volume signals).
- Cluster: "company offsite" (70/mo UK), "company off-site" (70/mo UK), "corporate offsite" (20/mo UK) = 160/mo UK total. English-language cluster with no DE volume (analogous to the A1 certificate cluster: UK as reference market, since Competitor A ranks there; the US market showed Competitor A not listed at all).
- SERP verify (depth20, UK/en, DataForSEO, Live-Regular): Competitor A ranks #15 ("company offsite") and #19 ("company off-site") via an HR glossary entry; premote.de not visible in the top 20-22 for any of the three keywords.
- Topic: company offsites abroad trigger the same compliance questions as classic business trips (A1 obligation, permanent establishment (Betriebsstätte) risk, accident insurance, entry requirements) — not previously bundled anywhere in the wiki as a topic of its own (grep-checked, 0 hits before this PR).
- Sources (3, retrieved and read): Deutsche Rentenversicherung A1 certificate FAQ, DGUV foreign coverage insurance/sections 140 et seq. Social Code Book VII (SGB VII), JUHN Partner on permanent establishment, section 12 Fiscal Code (AO)/Art. 5 OECD Model Tax Convention. Research note: content-ops/research/company-offsite-compliance.md.
- Article: DE+EN, slug `company-offsite-compliance`, cat dienstreise (cats: dienstreise/compliance/workation), 6 H2 + FAQ, 1 compliance checklist table, 4 internal links + 3 reciprocal links added from betriebsstaettenrisiko/reise-und-gesundheitsschutz-bei-auslandsreisen/business-visa-arbeitserlaubnis/a1-bescheinigung-basics.
- Format: wiki article (informational/guide intent, no comparison/purchase intent — fits the existing WikiArticleData structure).
- Branch content/company-offsite-compliance, Build + link audit green (86/86 reachable, 0 orphans, 0 stale links), premote casing check 0 hits, registered in wiki.ts (confirmed via git diff).
- PR: https://github.com/premote-de/website/pull/13
- Preview: https://website-git-content-company-offsite-compliance-premote.vercel.app/{de,en}/wiki/company-offsite-compliance (verified, HTTP 200, correct titles)
- Status: waiting for approval (Philipp/Johannes) in Slack.

## 2026-08-31 — No new Competitor A gap topic
- Pipeline: Competitor A gap refresh 2026-08-31. Two fresh DataForSEO Labs pulls (ranked_keywords, competitor-a.example): DE 67 candidates (vol>=30, rank<=20) and EN/UK 41 candidates — both lists identical to the pulls of 2026-08-29/08-30, all already [x]/[skip] in the roadmap.
- Additionally, a Competitor A sitemap diff (sitemap-0.xml + sitemap-pages.xml retrieved directly) for new HR glossary/country guide pages since the last check: one new glossary page found — `public-holidays-on-workation`. DataForSEO search_volume for 9 DE/EN variants ("public holidays workation", "feiertage bei workation" (German for "public holidays during workation"), among others): consistently None/0 — no demand signal, no gap.
- A Perplexity lead on Competitor A August 2026 updates additionally yielded "permanent establishment" (Competitor A glossary page) as a candidate. Live SERP check (EN/UK, depth20, DataForSEO): Competitor A NOT visible in the top 19 (gov.uk, Bloomberg Tax, RSM UK, PwC, EY dominate this highly competitive tax term) — no Competitor A gap under the rule, and content-wise already covered via betriebsstaettenrisiko/betriebsstaette-lohnsteuer.
- Repeat EN/UK live check for "bleisure"/"bleisure travel" (after the DE skip of 2026-08-30): Competitor A not organically visible in the top 19/20 in the English-language market either, in any case — skip confirmed and now verified bilingually.
- "workation" (plain, EN/UK) technically meets the Competitor A gap rule (Competitor A ranks #6, premote not visible in the top 18, live SERP check DataForSEO), but is an intent duplicate of the already bilingual article workation-basics (analogous to the "workation meaning" skip of 2026-08-27) — not a new cluster; earmarked as a later EN extension of workation-basics rather than a standalone article.
- Result: no new qualifying gap found that meets the format rules (volume ≥100/mo or a clear strategic rationale, genuine content gap, no duplicate). No PR today.
- DataForSEO cost today: ~$1.10 (2× ranked_keywords Labs at ~$0.017–0.02 each, 8× SERP checks depth20 at $0.004 each, 6× search_volume batches at $0.09 each).
- roadmap/competitor-a-gap.md updated (refresh block 2026-08-31), committed + pushed (content-ops main).
- Open PRs still waiting for approval by Philipp/Johannes: #4, #6, #8, #10, #12, #13, #14 (status unchanged since the last check — no merge check today, as the focus was on the gap search).
- Next candidate will come from the weekly competitor sitemap/blog diff or the 6-week roadmap refresh.

## 2026-08-31 — Digital Nomad Visa Malaysia (DE Rantau) (PR #15)
- Pipeline: Competitor A gap refresh (2026-08-31). DE/EN Labs pull for competitor-a.example identical to previous days (no new candidate) — second Competitor A brand competitor-a-us.example (tracked per competitors.yaml, never before included in a Labs pull) pulled for the first time and delivered the hit.
- Cluster: "malaysia digital nomad visa" (110/mo, EN/UK) + "digital nomad visa malaysia" (20/mo, DE) + variants ≈ 180/mo total.
- SERP verify (depth20, UK 2826): competitor-a-us.example ranks organically at #11 (competitor-a-us.example/visa/digital-nomad-visa-malaysia/), premote.de not visible in the top 19.
- Gap: premote only had the generic `digital-nomad-visa` article (Estonia/Barbados/Croatia/Bermuda/Georgia, no details) — no Malaysia, no compliance specifics. New country-specific article following the a1-bescheinigung-usa/-schweiz pattern.
- Sources (3, all retrieved and read): MDEC (official programme operator, DE Rantau page read via Wayback snapshot 2026-08-04, since the live page renders JS-only), Ministry of Digital Malaysia press release (digital.gov.my, June 2024 non-tech expansion), PwC Malaysia Tax Booklet (summarises LHDN/Income Tax Act 1967 §7(1)).
- Content: DE Rantau Pass mechanics (tech/non-tech categories, income thresholds USD 24k/60k, fees MYR 1000/500, 3–12 month validity) plus the central compliance point: the pass governs only residence, NOT German social insurance liability (section 4 SGB IV) or the Malaysian 182-day tax residency threshold. Comparison table against the USA Certificate of Coverage model.
- DE+EN wiki article, slug `digital-nomad-visa-malaysia` (27 characters), 9 H2 sections + FAQ, 2 comparison tables, 3 bidirectional internal links (digital-nomad-visa, a1-bescheinigung-usa, 183-tage-regel ↔ new article).
- Branch content/digital-nomad-visa-malaysia (35 characters, at the limit), Build (`yarn build`) + `node scripts/link-audit.mjs` green (92/92 reachable, 0 orphans, 0 broken links), `tsc --noEmit` green, premote casing check 0 hits.
- PR: https://github.com/premote-de/website/pull/15
- Preview: https://website-git-content-digital-nomad-visa-malaysia-premote.vercel.app/{de,en}/wiki/digital-nomad-visa-malaysia — both locales verified 200 OK.
- Research note: content-ops/research/digital-nomad-visa-malaysia.md (committed).
- roadmap/competitor-a-gap.md updated (pick row 2026-08-31b), committed+pushed.
- Status: waiting for approval by Philipp/Johannes in #website-content.

## 2026-08-31 — PR #15 Slack status message posted
- Build (`yarn build`) + `link-audit.mjs` re-verified locally (green, 0 orphans, 0 broken links).
- Both preview locales (DE/EN) confirmed via HTTP fetch (200, correct titles "Digital Nomad Visa Malaysia (DE Rantau)" / "Malaysia Digital Nomad Visa (DE Rantau)").
- Final status message posted in #website-content (PR link, the "Why this topic" line, summary, verify checklist, preview DE+EN).
- Status: waiting for approval by Philipp/Johannes.


## 2026-09-01 — Arbeiten aus Indien (PR #16)
- Continuation of a context-split run: article/research/roadmap entry had already been committed+pushed on branch `content/arbeiten-aus-indien`; in this continuation the PR was opened, the preview verified, and duplicate roadmap/research entries (from a parallel session summary) cleaned up.
- Pipeline: Competitor A gap refresh 2026-09-01. DE/EN gap table fully worked through; fresh DataForSEO Labs pull for competitor-a-us.example (sister brand of competitor-a-legacy.example, included for the first time) delivered the hit.
- Cluster: "working from india" (140/mo DE market SERP + 70/mo UK) + "arbeiten in indien" (50/mo DE; German for "working in India") + "a1 bescheinigung indien" (20/mo DE; German for "A1 certificate India") ≈ 280/mo total. competitor-a-us.example rank #7 (DE market)/#8 (UK), premote.de not in top 20 (live SERP check).
- Build (`yarn build`) + `node scripts/link-audit.mjs` green (92/92 reachable, 0 orphans, 0 broken links), premote casing check 0 hits.
- PR: https://github.com/premote-de/website/pull/16
- Preview: https://website-git-content-arbeiten-aus-indien-premote.vercel.app/wiki/arbeiten-aus-indien (DE) and /en/wiki/arbeiten-aus-indien (EN) — both 200 OK, titles verified.
- Research note: content-ops/research/arbeiten-aus-indien.md (already committed).
- Status: waiting for approval by Philipp/Johannes.

## 2026-09-02 — Digital Nomad Visa Kanada (PR #17)
- Pipeline: continuation of a context-split run — article/research/roadmap already committed+pushed on branch `content/digital-nomad-visa-kanada`; in this continuation the branch was rebased onto current main (India PR merged in the meantime), PR opened, Build+link audit re-verified green, preview confirmed.
- Cluster: "canada digital nomad visa" (50/mo UK) + "digital nomad visa canada" (40/mo UK) + variants ≈ 110/mo. competitor-a-us.example #18 (competitor-a-us.example/visa/digital-nomad-visa-canada/), premote.de not in top 20/22 (2x live SERP check, both word orders, DataForSEO 2026-09-02).
- Gap: premote only had the generic `digital-nomad-visa` article (Estonia/Barbados/Croatia/Bermuda/Georgia) with no reference to Canada — format analogous to a1-bescheinigung-usa/digital-nomad-visa-malaysia.
- Sources (6, all retrieved and read): IRCC Business Visitors [R186(a)], IRCC eTA page, CRA Income Tax Folio S5-F1-C1 (183-day sojourner rule), DVKA agreement Canada, Deutsche Rentenversicherung social security agreements overview, rvRecht SVA Canada Art. 1. Research note: content-ops/research/digital-nomad-visa-kanada.md (already committed).
- Article: DE+EN, slug `digital-nomad-visa-kanada`, 6 H2 + FAQ, 1 comparison table against the USA, wiki.ts entry added, internal links to digital-nomad-visa/a1-bescheinigung-usa/digital-nomad-visa-malaysia/183-tage-regel.
- Branch content/digital-nomad-visa-kanada recreated from origin/main (after the India merge), patch reapplied. Build (`yarn build`) + `node scripts/link-audit.mjs` against the running server green (94/94 reachable, 0 orphans, 0 stale links), premote casing check 0 hits.
- PR: https://github.com/premote-de/website/pull/17
- Preview: https://website-git-content-digital-nomad-visa-kanada-premote.vercel.app/{de,en}/wiki/digital-nomad-visa-kanada — both locales 200 OK, titles verified.
- Status: waiting for approval by Philipp/Johannes.

## 2026-09-03 — Digital Nomad Visa Brasilien (VITEM XIV) (PR #18)
- Pipeline: Competitor A gap refresh 2026-09-03. DE/EN competitor-a-legacy.example pull identical to previous pulls; fresh
  competitor-a-us.example pull (DE 1, EN/UK 23 qualifying) delivered the hit ("brazil digital nomad visa").
- Cluster: "brazil digital nomad visa" (70/mo UK) + "digital nomad visa brazil" (70/mo UK) + the same
  EN keywords in the DE market (10/mo each) ≈ 160/mo total. competitor-a-us.example rank #16 ("digital nomad visa brazil"
  word order, UK SERP, DataForSEO live 2026-09-03), premote.de not in top 19/20 (2x SERP check, both
  word orders).
- Gap: premote only had the generic `digital-nomad-visa` article (Estonia/Barbados/Croatia/
  Bermuda/Georgia) with no reference to Brazil. Distinctive feature vs. Canada/Malaysia: Brazil has both a
  dedicated visa (VITEM XIV) and a bilateral social security agreement with Germany — and a 184-day rather than
  183-day tax threshold.
- Sources (4, all retrieved and read): MRE Consulado-Geral Lisboa VITEM XIV page (via Wayback, live version
  CAPTCHA-protected), CNIg Resolução MJSP Nº 45/2021 (Diário Oficial, via Wayback), Receita Federal
  "Residente e Não Residente" (live, 184-day threshold), Deutsche Rentenversicherung Bund
  posting certificate (Entsendebescheinigung) competence table (live, form BR/DE 101).
- Article: DE+EN, slug `digital-nomad-visa-brasilien` (27 characters), 6 H2 + FAQ, 1 comparison table
  against Malaysia/Canada, wiki.ts entry added, internal links to digital-nomad-visa/
  digital-nomad-visa-kanada/digital-nomad-visa-malaysia/sozialversicherungsabkommen/183-tage-regel
  (bidirectional: all three existing articles now also link to the new one).
- Branch content/digital-nomad-visa-brasilien (37 characters) newly created from origin/main. Build
  (`yarn build`) + `node scripts/link-audit.mjs` against the running server green (95/95 reachable, 0
  orphans, 0 broken links), premote casing check 0 hits.
- PR: https://github.com/premote-de/website/pull/18
- Preview: https://website-git-content-digital-nomad-visa-brasilien-premote.vercel.app/wiki/digital-nomad-visa-brasilien
  (DE) and /en/wiki/digital-nomad-visa-brasilien (EN) — both 200 OK, titles verified.
- Research note: content-ops/research/digital-nomad-visa-brasilien.md (already committed).
- DataForSEO cost today: ~$0.17 (4× ranked_keywords Labs at ~$0.014-0.044 each, 3× SERP checks depth20 at
  $0.004 each, 2× search_volume batches at $0.09 each).
- Status: waiting for approval by Philipp/Johannes.

## 2026-09-04 — Digital Nomad Visa Neuseeland (PR #19)
- Pipeline: Competitor A gap refresh 2026-09-04. competitor-a-legacy.example DE/EN identical to all previous pulls (all already [x]/[skip]). Fresh competitor-a-us.example pull (EN/UK 20 qualifying) identical to 09-02/09-03; the only still unused+relevant row was "new zealand digital nomad visa"/"digital nomad visa new zealand", previously skipped because <100/mo (09-02). Picked today with an explicit strategic reason: continuation of the country DNV series (Malaysia/Canada/Brazil).
- Cluster: "new zealand digital nomad visa" (40/mo UK) + "digital nomad visa new zealand" (20/mo UK) + the same EN keywords in the DE market (10/mo each) ≈ 80/mo total. competitor-a-us.example rank #9 ("new zealand digital nomad visa" word order) / #8 ("digital nomad visa new zealand" word order), premote.de not in top 22 (2x live SERP check, both word orders, DataForSEO 2026-09-04).
- Gap: premote only had the generic digital-nomad-visa article with no reference to New Zealand. Distinctive feature vs. Canada/Malaysia/Brazil: since 27.01.2025 New Zealand explicitly permits remote work on the visitor visa/NZeTA (no dedicated DNV category, but the most liberal rule in the series), yet as the only one of the four countries it has NO bilateral social security agreement with Germany.
- Sources (4, all retrieved and read, 2026-09-04): Immigration New Zealand news release "Working remotely from New Zealand" (27.01.2025, official), Immigration New Zealand guidance page "Working remotely in New Zealand on a visitor visa" (official), Inland Revenue NZ "Tax residency status for individuals" (183-day rule, official), Deutsche Rentenversicherung complete country list of social security agreements (NZ missing, official).
- Article: DE+EN, slug digital-nomad-visa-neuseeland (29 characters), 6 H2 + FAQ, 1 comparison table against Canada/Brazil, wiki.ts entry added, internal links to digital-nomad-visa/digital-nomad-visa-kanada/digital-nomad-visa-malaysia/183-tage-regel (bidirectional: existing articles now also link to the new one).
- Branch content/digital-nomad-visa-neuseeland (37 characters) created from current main. tsc --noEmit + Build (yarn build) + node scripts/link-audit.mjs against the running server green (95/95 reachable, 0 orphans, 0 broken links), premote casing check 0 hits.
- PR: https://github.com/premote-de/website/pull/19
- Preview: https://website-git-content-digital-nomad-visa-neuseeland-premote.vercel.app/wiki/digital-nomad-visa-neuseeland (DE) and /en/wiki/digital-nomad-visa-neuseeland (EN) — both 200 OK, titles verified.
- Research note: content-ops/research/digital-nomad-visa-neuseeland.md (already committed).
- Note: the GitHub token has no access to the commit status/checks/deployments API (403 Resource not accessible) — preview verification was done via direct HTTP fetch of the known Vercel branch URL instead of API polling.
- Status: waiting for approval by Philipp/Johannes.

## 2026-09-05 — Ständige Wohnstätte / Permanent Home DBA-Tie-Breaker (PR #20)
- Pipeline: continuation of a context-split run — topic pick, roadmap update, research note, article content and articles.ts entry had already been prepared/committed; in this continuation a body-string bug in articles.ts was found and fixed (template literal had double quotes around the HTML string), term registered in wiki.ts, Build+TypeScript+link audit verified green, PR opened, preview confirmed.
- Pipeline: Competitor A gap refresh 2026-09-05. Fresh DataForSEO Labs pull for competitor-a-legacy.example + competitor-a-us.example delivered "permanent house"/"residency home" as new top-20 hits; SERP qualifier ("permanent home tax") confirmed genuine tax residency intent rather than real estate noise.
- Cluster: "permanent house" (480/mo UK) + "residency home" (70/mo UK) + "permanent legal residence" (40/mo UK) + "permanent home" (30/mo UK) ≈ 650/mo total. Competitor A ranks #8 with a dedicated glossary page (help.competitor-a.example/en/articles/permanent-home), premote.de not in the top 17 of 131 SERP results (DataForSEO depth-20 check, 2026-09-05).
- Gap: premote so far covers the permanent home (ständige Wohnstätte) only as a sub-aspect within the existing article `steuerliche-ansassigkeit` (tie-breaker cascade as a list without depth) — no standalone, high-search-volume technical term article.
- Sources (3, all retrieved and read): OECD Model Tax Convention Art. 4(2) (legalinstruments.oecd.org, original wording), Federal Ministry of Finance (BMF) circular of 12.12.2023 paras. 12-24 (via Wayback Machine PDF snapshot + clawpdf text extraction, since lsth.bundesfinanzministerium.de is bot-blocked; definition + 6 Federal Fiscal Court (BFH) references + 1-/5-year presumption rule for postings (Entsendungen)), Haufe.de practical workation example (3-month case, residence remains in Germany).
- Article: DE+EN, slug `staendige-wohnstaette-dba` (25 characters), 7 sections (definition, 5-step cascade table, qualification criteria table, 1-year rule of thumb + workation example, centre of vital interests, distinction from the A1 certificate, FAQ), cats: workation/dienstreise/social, wiki.ts entry added, bidirectional internal links to/from `steuerliche-ansassigkeit` and `a1-certificate-explained`.
- Branch `content/staendige-wohnstaette-dba` (33 characters). `yarn build` + `node scripts/link-audit.mjs` against the running server green (96/96 reachable, 0 orphans, 0 broken links), premote casing check 0 hits.
- PR: https://github.com/premote-de/website/pull/20
- Preview: https://website-git-content-staendige-wohnstaette-dba-premote.vercel.app/wiki/staendige-wohnstaette-dba (DE) and /en/wiki/staendige-wohnstaette-dba (EN) — both 200 OK, titles verified.
- Research note: content-ops/research/staendige-wohnstaette-dba.md (already committed).
- Note: the GitHub token still has no access to the commit status/checks/deployments API (403) — preview verification via direct HTTP fetch of the Vercel branch URL.
- Status: waiting for approval by Philipp/Johannes.

## 2026-09-10 — Workation Griechenland (PR #25)
- Pipeline: Competitor A gap refresh 2026-09-10. Base table had been fully worked through (0 unused entries); fresh DataForSEO Labs pull for competitor-a-legacy.example (271 items) + competitor-a-us.example (12 items) uncovered a new qualifying candidate: "work from greece" (competitor-a-us.example, rank #17 per Labs snapshot, 50 searches/month DE).
- Cluster: "work from greece" + "working from greece" ≈ 100/mo, "workation griechenland" (German for "workation Greece") 20/mo, "homeoffice griechenland" (German for "home office Greece") 10/mo — total cluster ≈130/mo. 10 further new competitor-a-us.example candidates marked as [skip] (rank too low / own brand / EOR out of scope / generic without relevance — rationale in competitor-a-gap.md).
- SERP: DataForSEO Labs snapshot (2026-07-30/last updated 2026-08-18) confirms competitor-a-us.example/remote-work/greece/ at rank #17 for "work from greece"; premote not in top 20. Live depth-20 recheck (2026-09-10) showed SERP volatility (competitor-a-us.example not visible) — both states documented transparently in the roadmap entry.
- Sources (4, all retrieved live and read): Deutsche Rentenversicherung A1 FAQ (scope EU incl. Greece), BMF double taxation agreement (DBA) Greece overview + full-text PDF Art. XI(2)+(3) (183-day rule, original wording, extracted via pdf-parse), EU "Your Europe" free movement page (3-month rule + registration requirement from day 91, original quotes), European Commission posted workers definition (original quote on distinguishing workation vs. posting (Entsendung)).
- Article: DE+EN, slug `workation-griechenland` (22 characters), 8 sections (legal overview, A1 certificate EU standard, entry rules/registration from day 91, 183-day rule/DBA Art. XI, workation vs. posting/PWD notification obligation, comparison table, employer checklist, FAQ), cats: workation/dienstreise/social, bidirectional internal links to/from entsendung-meldung-griechenland, workation-basics, 183-tage-regel.
- Branch `content/workation-griechenland` (30 characters). `npx tsc --noEmit` + `yarn build` + `node scripts/link-audit.mjs` against the running server green (100/100 reachable, 0 orphans, 0 broken links), premote casing check 0 hits.
- PR: https://github.com/premote-de/website/pull/25
- Preview: https://website-git-content-workation-griechenland-premote.vercel.app/de/wiki/workation-griechenland (DE) and /en/wiki/workation-griechenland (EN) — both 200 OK.
- Research note: content-ops/research/workation-griechenland.md (already committed).
- Note: the GitHub token still has no access to the commit status/checks/deployments API (403) — preview verification via direct HTTP fetch of the Vercel branch URL.
- Status: waiting for approval by Philipp/Johannes.

## 2026-09-07 — Digital Nomad Visa Australien (PR #22)
- Pipeline: Competitor A gap refresh 2026-09-07. Base table had been fully worked through (0 unused entries); fresh DataForSEO Labs pull for competitor-a-legacy.example + competitor-a-us.example (US location 2840) uncovered new country DNV candidates (Albania, Australia, Taiwan, Norway, Korea, Montenegro, Turkey, Costa Rica).
- Cluster: "australia digital nomad visa" + "digital nomad visa australia" ≈ 300/mo total (US+UK+DE) — largest/most relevant cluster among the candidates, with a dedicated competitor-a-us.example page. Norway/Taiwan/Albania/Korea/Montenegro/Turkey/Costa Rica as well as the Apple/RTO brand and EOR/remote-vs-hybrid clusters marked as [skip] (rationale in competitor-a-gap.md).
- SERP: live depth-20 check (US 2840, 2026-09-07) confirms competitor-a-us.example rank #14 for "digital nomad visa australia" and "australia digital nomad visa"; premote.de not in top 22.
- Sources (3, all retrieved live and read): immi.homeaffairs.gov.au ETA 601 page (original quote "not a work visa"/business visitor restrictions), DVKA posting (Entsendung) Australia page (AU/DE 101, 48-month rule original quote), BMF DBA Australia PDF Art. 14(2) (183-day rule original wording, extracted via pdf-parse since no poppler-utils available).
- Article: DE+EN, slug `digital-nomad-visa-australien` (29 characters), 8 sections (no dedicated DNV, short stay ETA/eVisitor/Visitor 600, Working Holiday 417 age limit, AU/DE 101 social security agreement, DBA 183-day rule, comparison table AU/NZ/Canada, employer implications, FAQ), cats: workation/dienstreise/social, wiki.ts entry added, bidirectional internal links to/from digital-nomad-visa, digital-nomad-visa-neuseeland, digital-nomad-visa-kanada, digital-nomad-visa-deutschland.
- Branch `content/digital-nomad-visa-australien` (37 characters). `npx tsc --noEmit` + `yarn build` + `node scripts/link-audit.mjs` against the running server green (97/97 reachable, 0 orphans, 0 broken links), premote casing check 0 hits.
- PR: https://github.com/premote-de/website/pull/22
- Preview: https://website-git-content-digital-nomad-visa-australien-premote.vercel.app/de/wiki/digital-nomad-visa-australien (DE) and /en/wiki/digital-nomad-visa-australien (EN) — both 200 OK, titles verified.
- Research note: content-ops/research/digital-nomad-visa-australien.md (already committed).
- Note: the GitHub token still has no access to the commit status/checks/deployments API (403) — preview verification via direct HTTP fetch of the Vercel branch URL.
- Status: waiting for approval by Philipp/Johannes.
