# Research: Social security number (Sozialversicherungsnummer) (cluster)

Date: 2026-08-21
Target keyword: "wie sieht eine sozialversicherungsnummer aus" (what does a social security number look like) (1900/month DE) + cluster variants (see roadmap/competitor-a-gap.md, 18 keywords, total ≈ 6,120/month)
Format: wiki article (informational intent, no purchase intent — standard format fits)

## DataForSEO
- SERP depth-20 "wie sieht eine sozialversicherungsnummer aus" (2276/de, 2026-08-21):
  - #4 deutsche-rentenversicherung.de, #7 aok.de, #9 tk.de, #19 dak.de, #20 de.wikipedia.org
  - **help.competitor-a.example at #15** (competitor Competitor A)
  - **premote.de: not in top 20**
- Search volume (google_ads/search_volume/live, DE):
  - "wie sieht eine sozialversicherungsnummer aus" = 1900
  - "wie sieht die sozialversicherungsnummer aus" = 1900
  - "sozialversicherungsnummer" (head) = 74000
  - "zusammensetzung sozialversicherungsnummer" = 260
  - "sozialversicherungsnummer aufbau" = 1000

## Sources (all fetched directly in this session)

### 1. Deutsche Rentenversicherung (German pension insurance, DRV) – proof of insurance number (Versicherungsnummernachweis)
https://www.deutsche-rentenversicherung.de/DRV/DE/Rente/Allgemeine-Informationen/Sozialversicherungsausweis
> Quote (translated from German): "When you take up your first employment, we issue you a proof of insurance number (social insurance card). It contains your insurance number, your first name and surname."
> Obligation to carry it abolished since 2023; passport photo no longer required. A sector-specific obligation to carry/present identity documents (no longer the social insurance card, Sozialversicherungsausweis) remains (construction, meat industry, hospitality, building cleaning, passenger transport, prostitution, guarding/security services, showmen, freight forwarding/transport/logistics, forestry, trade fair set-up/dismantling).

### 2. Deutsche Rentenversicherung – press release 11.01.2023
https://www.deutsche-rentenversicherung.de/DRV/DE/Ueber-uns-und-Presse/Presse/Meldungen/2023/230111_vsnr_nachweis
> Quote (translated from German): "Since 01 January 2023, the proof of insurance number replaces the social insurance card. The new document contains – as the social insurance card did before – the insurance number, first name(s), surname, birth name and the date of issue."
> Loss/recovery no longer has to be reported; no general obligation to present it to the employer any more, only if the automated retrieval (DSRV) does not return a unique number. Old social insurance cards remain valid.

### 3. TK (Techniker Krankenkasse) – SVA and SV number (business customer FAQ)
https://www.tk.de/firmenkunden/versicherung/meldeverfahren-faq/renten--und-sozialversicherungsnummer/sva-und-sv-nummer-2035900
> Quote (translated from German): "Every German citizen receives a twelve-digit pension insurance number (RV number) for life, at the latest when taking up employment subject to social insurance contributions. […] Since 2005, the RV number has been assigned from birth."
> Employers are required to retrieve the number via the Data Centre of the German Pension Insurance (Datenstelle der Rentenversicherung, DSRV); only if this fails must the employee present the proof, or a new number is initiated via the notification procedure.

### 4. AOK – Providing the social security number (business customers)
https://www.aok.de/fk/sozialversicherung/meldung-zur-sozialversicherung/angabe-der-sozialversicherungsnummer/
> Structure, using the example "50220479M123":
> - Positions 1–2: pension insurance institution (encoded)
> - Positions 3–8: date of birth (DDMMYY, unencoded)
> - Position 9: first letter of the birth name
> - Positions 10–11: two-digit serial number — previously 00–49 men, 50–99 women/"undetermined"/"diverse"; **gender-neutral assignment since 1 January 2026**
> - Position 12: check digit
> Page as of: 01.01.2026. Procedure when no number exists: the employer submits a DSVV query to the DRV; three possible responses (no result / unique result / no unique result); the number is then assigned with the registration for social insurance.

### 5. DAK-Gesundheit – What is the social security number?
https://www.dak.de/dak/ihr-anliegen/mitgliedschaft-und-beitraege/versicherungsnummernachweis/was-ist-die-sozialversicherungsnummer-_142544
> Quote (translated from German): "The social security number is also called the pension insurance number, SV number or insurance number of the pension insurance. It is a twelve-digit number that you receive when you take up employment subject to social insurance contributions. It stays the same for your whole life."

### 6. Wikipedia – Sozialversicherungsnummer (international comparison, context)
https://de.wikipedia.org/wiki/Sozialversicherungsnummer
> Germany has NO uniform social security number across all branches (data protection reasons) — to a limited extent, the pension insurance number is used like a social security number. Example format in the article: "15 070649 C 103". Abbreviations in the DACH region are inconsistent; Austria/Switzerland have their own, different formats.

### 7. Perplexity leads (context only, not a source — facts above verified independently)
Confirms in substance: for A1 applications and postings, the insurance number is an identifier used by the DRV; when foreign employees take up their first employment in Germany, the number is newly assigned via the notification procedure (DSRV) if needed, not "brought along". This premote-relevant link (A1/posting/first registration of foreign employees) is used as a focus section in the article; all facts on it come from Sources 1–4.

## premote relevance (why this article fits premote)
Foreign employees, posted workers and workation employees constantly run into the question "what does my German SV number look like / where do I get it". The article links into the A1 certificate (A1-Bescheinigung) and posting wiki content and positions premote as the point of contact when the number is missing or the DSRV query does not return a unique result (typical case for international new hires).

## Verify points for the PR
- Twelve digits, valid for life, assigned from birth since 2005 → TK, DAK
- Structure (institution/date of birth/name letter/serial number/check digit), example 50220479M123 → AOK
- Gender-neutral assignment since 1.1.2026 → AOK (as of 01.01.2026)
- Proof of insurance number has replaced the social insurance card since 1.1.2023, no general obligation to present it any more → DRV (x2), TK
- Germany has no uniform social security number across all branches → Wikipedia
- Competitor A (help.competitor-a.example) ranks #15 for the main keyword, premote not in top 20 → DataForSEO SERP 2026-08-21
