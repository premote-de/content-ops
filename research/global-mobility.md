# Research note: global-mobility (solution page, pillar/positioning)

Date: 2026-08-24
Author: premote content engine
Purpose: new solution page `/global-mobility` (DE+EN) — position premote as the all-in-one global mobility platform.
Authoritative source for positioning/scope: `content-ops/briefings/premote-content-briefing.md`, section 1.

## Scope boundaries (taken verbatim from the briefing)
- In scope: business travel, postings (Entsendungen), workation, travel risk management, assignment management (cost projections, permanent establishment (Betriebsstätte) reporting, risk & compliance assessments), tax and permanent establishment data as evidence/reporting.
- Out of scope: EOR, payroll processing, relocation/moving logistics, immigration as legal advice.
- Positioning: premote is the all-in-one global mobility platform for every form of mobility, compliance automated from the HR/travel system, no consulting-project logic.

## Existing content checked (no duplication)
- `src/content/solutions/{workation,dienstreise-compliance,entsendungen-neu,travel-risk,agentic-workflows}.ts` — each covers a single solution; no overarching category/positioning page "Global Mobility Software/Platform".
- `src/content/site.ts` already uses "Global Mobility" as the brand header claim (hero H1, meta), but no dedicated page/route exists for it.
- No wiki article and no route under `src/app/[lang]/` with slug `global-mobility` exists (grep negative). → Topic is free, no collision.

## DataForSEO (fetched 2026-08-24, DE, location_code 2276)
Search volume (`google_ads/search_volume/live`):
- "global mobility software": 10/month
- "global mobility plattform": no volume (0/none)
- "global mobility management": 20/month
- "global mobility tool": 10/month
- "global mobility system": 10/month
- "global mobility platform": 10/month
- "assignment management software": 10/month

Chosen primary keyword: **"global mobility software"** (10/month DE, but a strategic category term with high competitive density, HIGH competition_index 79 according to DataForSEO).

SERP check (`serp/google/organic/live/regular`, depth 20, DE) for "global mobility software":
- premote.de: **not in the top 20**.
- Rank 2: Deloitte (deloitte.com) — Big Four provider, old consulting model.
- Rank 4: [provider, name removed] — relocation/immigration, not the same business.
- Rank 6: [competitor, name removed] — direct competitor (per briefing section 1).
- Rank 10: Competitor B (competitor-b.example) — EOR, not the same business.
- Rank 15: Competitor A (competitor-a-us.example) — direct competitor, ranks #15 for this keyword.
- None of the top 3 results is a compliance automation platform like premote; the page is occupied by Big Four PDF/law-firm-style explainer articles and comparison blogs (a number of larger competing players in comparison-blog format); no category landing page of a direct competitor clearly dominates.

"Why this topic" line (format per `content-ops/pipeline/dataforseo.md`):
"global mobility software" has 10 searches/month (DE); premote does not rank in the top 20, Competitor A (competitor-a-us.example) ranks #15 — the article targets this gap before Big Four PDF content (Deloitte #2) and comparison blogs ([provider] #4, Competitor B #10) occupy the category further. (DataForSEO, 2026-08-24)

## Research leads (Perplexity, sonar-pro) — used as leads only; all sources below fetched & read first-hand
Prompt: definition/feature set of global mobility management software, delimitation from EOR/payroll/relocation, market size, consolidation drivers, EU/DE compliance context.

## Verified external sources (fetched & read personally, 2026-08-24)

### 1) Aragon Research — Global Mobility Management (GMM) glossary
URL: https://aragonresearch.com/glossary-gmm/
Quote (fetched): "Global mobility management (GMM) is a business application that manages the complete set of processes and data required to identify, justify, and manage the movement of an existing employee or the hiring of an employee who requires relocation. GMM is designed to automate domestic and international employee mobility decisions, operations, and benefits."
Use: category definition "What is global mobility management" in the FAQ/intro. Neutral, analyst-grade, no vendor bias in the definition itself.

### 2) Mordor Intelligence — Mobility And Relocation Management Software Market
URL: https://www.mordorintelligence.com/industry-reports/mobility-and-relocation-management-software-market
Quote (fetched): "The mobility and relocation management software market size is projected to expand from USD 4.50 billion in 2025 and USD 5.11 billion in 2026 to USD 10.09 billion by 2031, registering a CAGR of 14.58% between 2026 and 2031. […] enterprises move away from manual tracking toward platforms that combine immigration workflows, assignment administration, and compliance reporting in a single operating system."
Use: market/consolidation evidence for the "one platform instead of point solutions" argument. The figure (USD 4.50 bn → 10.09 bn, 14.58 % CAGR) is cited in the article with date + source, not adopted without comment.
Note: the market definition ("mobility and relocation management") is broader than premote's scope (it includes e.g. relocation logistics) — labelled in the text as market context, not as a 1:1 premote figure.

### 3) European Commission — Posted workers (Employment, Social Affairs and Inclusion)
URL: https://employment-social-affairs.ec.europa.eu/policies-and-activities/moving-working-europe/working-another-eu-country/posted-workers_en
(Originally linked as ec.europa.eu/social/main.jsp?catId=471 — redirects to the URL above; final URL cited.)
Quote (fetched): "A 'posted worker' is an employee who is sent by his employer to carry out a service in another EU Member State on a temporary basis […] These rules are set out in the Posting of Workers Directive (PWD) which was adopted in 1996 and revised in 2018."
Use: evidence for the EU-law obligations (PWD) as one of the compliance drivers for why mobility is now managed with software rather than manually. Only the official EU definition is quoted; no figures that would require verification are taken from this source.

## Unused/rejected leads
- europa.eu/youreurope A1 portal subpage (suggested by Perplexity): 404/redirect to the generic Your Europe start page, no stable deep-link URL found — not cited.
- DVKA (dvka.de) posting subpages: on fetch "Regretfully the service is not available at the moment." — unreachable, not cited.
- BMAS (Federal Ministry of Labour and Social Affairs) subpage on A1/posting: 404 — not cited.
- Perk.com, XPath Global (vendor blogs): only named as Perplexity leads, not fetched/verified first-hand → not used as sources (Hard Rule 3).

## Conclusion for the article
- Claim "the market is consolidating towards a single platform" → Mordor Intelligence, with date and the wording "according to Mordor Intelligence (as of: 2026 market report)".
- Claim "What is global mobility management" → Aragon Research definition, paraphrased in German/English, with link.
- Claim "EU-law obligations (PWD) drive software demand" → European Commission page, with link.
- All three sources are independent of each other (analyst, research market report, EU authority) and official/professional as preferred, as required by Hard Rule 3.
- The scope delimitation (no EOR/payroll/relocation/immigration advice) is named explicitly in the article, not just implicitly — briefing section 1 is mirrored verbatim in the FAQ.
