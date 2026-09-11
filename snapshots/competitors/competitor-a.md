=== Snapshot: competitor-a ===
Date: 2026-09-07T06:00Z
Domain: www.competitor-a-legacy.example → 200 OK, redirects to www.competitor-a.example (canonical host change confirmed 2026-08-31, persists)
Secondary domain: competitor-a-us.example → 200 OK, own WordPress site (US-market "Work From Anywhere" content, distinct from competitor-a.example)
Watch-paths: sitemap.xml, blog, glossary, country pages

** Domain verification: **
- www.competitor-a-legacy.example/sitemap.xml → 200, finalUrl www.competitor-a.example/sitemap.xml (redirect confirmed, working as intended)
- competitor-a-us.example/sitemap.xml → 200 (WordPress/AIOSEO, own sitemap index with post/page/remote-work/visa/faq sub-sitemaps)

** www.competitor-a.example — crawl (sitemap-0.xml + sitemap-pages.xml): **
Total URLs (sitemap-pages.xml, DE locale base): 484
- hr-lexikon (glossary) entries: 24 (a1-bescheinigung, arbeitsrecht, betriebsstaette, bleisure, certificate-of-coverage, compliance-mobiles-arbeiten, datenschutz, dienstreise, digital-nomad-visum, dsgvo, entsandter-arbeitnehmer, feiertagsregelung-auf-workation, firmen-offsite, g35, iso-31030-travel-risk-management-standard, krankenversicherung, lohnsteuer, remote-onboarding, schweizer-arbeitsbewilligungen, sozialversicherung, sozialversicherungsabkommen, travel-risk-management, workation, workations-ohne-risiko)
- country-guides: 60 countries (DE locale)
- newsroom/insights posts: 74 (across en-uk + de, press/PR content)
- /post/ (blog-style long-form, case studies, guides): 74 per locale (de + en-uk)
- industries pages: 13

** Status vs previous run (2026-08-31): **
- Previous snapshot only recorded the sitemap INDEX (2 sub-sitemap URLs), not the actual page listing — no true URL-level baseline existed before this run.
- This run establishes the first full URL-level baseline (484 URLs from sitemap-pages.xml + case-study posts from sitemap-0.xml) for future diffing.
- hr-lexikon glossary count stable at ~24-25 terms (consistent with prior week's qualitative note).
- No new hr-lexikon terms detected vs. last week's list.

** competitor-a-us.example — crawl (post-sitemap.xml + page-sitemap.xml + remote-work-sitemap.xml): **
- Blog posts (post-sitemap.xml): 247 URLs ("Work From Anywhere" US-focused blog: corporate work-from-anywhere policy deep-dives e.g. Apple, OpenAI, Accenture, Google, NVIDIA, Meta, Netflix, Revolut, Atlassian, Shopify, IBM, Cisco, Salesforce, Microsoft — company remote-work policy content, not compliance/A1 focus)
- Pages (page-sitemap.xml): 79 URLs (product pages: remote-work-compliance-software, partner pages, how-to-approve-international-remote-work)
- Remote-work country pages (remote-work-sitemap.xml): 88 country landing pages (South Africa, Turkey, Saudi Arabia, Qatar, Egypt, Singapore, Malaysia, Greece, Vietnam, Jordan, Morocco, Nigeria, Israel, UAE, India, Japan, Indonesia, and ~70 more)
- New Sept 2026: two new partner landing pages (insurance/mobility partnership expansion)

** Summary: **
Competitor A (www.competitor-a.example) remains the core direct competitor — 484 pages incl. 60 country guides + 24 glossary terms + 74 case-study/blog posts, all bilingual DE/EN. competitor-a-us.example is a related but distinct US-market work-from-anywhere-policy content play (247 blog posts, 88 country pages) not overlapping with the DE/EU A1-compliance angle — track separately if relevant to Track 2 (Global Mobility).
