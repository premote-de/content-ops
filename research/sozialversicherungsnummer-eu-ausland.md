# Research: EU social security number (EU-Sozialversicherungsnummer) / eu sozialversicherungsnummer

**Date:** 2026-09-09
**Target article:** website/src/content/wiki/articles.ts, slug: `sozialversicherungsnummer-eu-ausland`
**Keyword cluster (Competitor A gap):**
- eu sozialversicherungsnummer (70 searches/month DE, DataForSEO 2026-09-09)
- europäische sozialversicherungsnummer (10 searches/month DE, DataForSEO 2026-09-09)
- Cluster total: 80/month
- Competitor A help article ranks #15 for "sozialversicherungsnummer" in the SERP check (help.competitor-a.example/de/articles/sozialversicherungsnummer); premote.de not in top 20/22.

## Core question of the article
Is there a uniform EU-wide social security number? How do national social security numbers relate to the A1 certificate (A1-Bescheinigung) for EU postings?

## Facts + sources (all retrieved and read directly, 2026-09-09)

### 1. There is NO uniform EU social security number
Source: European Commission, Employment, Social Affairs and Inclusion – "European Social Security Pass (ESSPASS)" Q&A
URL: https://employment-social-affairs.ec.europa.eu/policies-and-activities/moving-working-europe/eu-social-security-coordination/digitalisation-social-security-coordination/european-social-security-pass/questions-answers_en
Retrieved: 2026-09-09

Quote (excerpt, translated/paraphrased from the official text): With ESSPASS, the Commission is not pursuing a common EU identifier but a digital solution that facilitates the cross-border verification of social security entitlements – building on the existing Portable Document A1 and the electronic data exchange infrastructure EESSI. Verbatim on EESSI: "EESSI is a message exchange system that allows for secure and fast exchange of information between institutions... Only social security institutions have access to the EESSI system."
→ So there is no uniform EU numbering system; instead, national institutions exchange data via EESSI, referenced by the respective national numbers.

### 2. Official EU forms overview confirms: national institutions, no EU form with its own number
Source: European Commission, "Your Europe" – Social security entitlements: forms
URL: https://europa.eu/youreurope/citizens/work/social-security-and-benefits/social-security-forms/index_de.htm
Retrieved: 2026-09-09

Quote (translated from German): "A1 (formerly: E101, E103) – Certificate concerning the applicable legislation... Issued by: the social security institution of the country in which you are insured. If you are posted, this is the institution in the sending country."
→ The A1 certificate is issued by the national institution of the home country – there is no central EU form with its own number. The A1 refers to the national insurance number of the posted person.

### 3. Deutsche Rentenversicherung (German pension insurance, DRV): insurance number is a prerequisite for the A1 application
Source: Deutsche Rentenversicherung, FAQ "A1-Bescheinigung – Arbeiten im EU-Ausland" (A1 certificate – working in other EU countries)
URL: https://www.deutsche-rentenversicherung.de/SharedDocs/FAQ/a1_bescheinigung/a1_bescheinigung_faq_liste
Retrieved: 2026-09-09

Quotes (translated from the German original):
- "From 1 January 2025, the A1 certificate must always be applied for electronically. Applying for an A1 certificate with a paper form is not permitted..."
- "Where the Deutsche Rentenversicherung is responsible, the insurance number of the person to be posted must be provided as part of the electronic application."
- Territorial scope: all EU states, Iceland, Liechtenstein, Norway, Switzerland, United Kingdom.
→ For postings from Germany, the German (national) social security number is a mandatory part of the A1 application. No separate "EU number" is required or assigned.

### 4. DSRV (Datenstelle der Rentenversicherung, Data Centre of the German Pension Insurance): insurance number as a basic prerequisite
Source: Datenstelle der Rentenversicherung (DSRV), "Entsendebescheinigung" (posting certificate)
URL: https://www.dsrv.info/de/Navigation/20_Unsere_Verfahren/01_Nationaler_Datenaustausch/03_Arbeitgeber/03_A1/A1_node
Retrieved: 2026-09-09

Quote (translated from German): "What prerequisite must be met? The person who is to receive an A1 certificate must have an insurance number. If no insurance number exists, the employer must apply for one."
→ Confirms independently of Source 3: no A1 without a (national) insurance number. Responsibility depends on the group of persons: health insurance fund, pension insurance institution, ABV, GKV-SV/DVKA (flight/cabin crew, multiple employment).

### 5. Every EU state assigns its own national social security numbers (example: Austria)
Source: oesterreich.gv.at, "Checkliste Sozialversicherung ... für EU-Bürger und Schweizer" (social insurance checklist for EU citizens and Swiss nationals)
URL: https://www.oesterreich.gv.at/de/themen/bauen_und_wohnen/umzug/2/2/Seite.180621
Retrieved: 2026-09-09

Quote (translated from German): "...[certain groups of persons] should register with the competent social insurance institution in order to obtain a social security number and an e-card."
→ On moving in/taking up employment, Austria assigns its own national social security number (independent of the German one). Confirms the pattern: each country has its own system, no EU-wide porting of the number.

## Existing article (context, NOT a source for new facts, only for delineation)
- website/src/content/wiki/articles.ts → slug "sozialversicherungsnummer": describes the structure/format of the GERMAN social security number (12 digits). The new article builds on it but answers the other search intent: "is there an EU number / how does this work for EU postings".
- Slug "sozialversicherungsnachweis": document level (proof of insurance number, Versicherungsnummernachweis), also linked.
- Slug "a1-certificate-explained": A1 basics EN.

## Implications for the article
Key messages for the DE/EN article:
1. There is no uniform EU social security number (Sources 1, 2).
2. Every EU/EEA/CH state assigns its own national number (Sources 2, 5, plus the existing article on the DE number as an internal cross-link).
3. Coordination for postings runs via the A1 certificate, issued by the institution of the country of origin, stating the national (e.g. German) insurance number (Sources 2, 3, 4).
4. No A1 without an insurance number – the employer may have to apply for it first (Source 4).
5. The EU is working on a digital solution (ESSPASS/EESSI), NOT on a new EU number (Source 1).

## Verify checklist for the final Slack message
- "No uniform EU social security number" → EU Commission ESSPASS Q&A (Source 1)
- "A1 is issued by the institution of the country of insurance" → Your Europe forms overview (Source 2)
- "Electronic A1 mandatory since 1.1.2025, insurance number must be provided" → DRV FAQ (Source 3)
- "Insurance number is a prerequisite for A1, otherwise the employer must apply for it" → DSRV (Source 4)
- "Each country has its own national number, example Austria" → oesterreich.gv.at (Source 5)
