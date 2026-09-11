=== Snapshot: competitor-d ===
Date: 2026-09-07T06:00Z
Domain: competitor-d.example → 200 OK (note: www.competitor-d.example/sitemap.xml redirected to bare competitor-d.example/ homepage HTML, not the sitemap — canonical sitemap only resolves at bare-domain /sitemap_index.xml)
Watch-paths: blog

** Domain verification / correction needed: **
- https://www.competitor-d.example/sitemap.xml → 200 but finalUrl=https://competitor-d.example/ (redirected to homepage HTML, NOT the sitemap — likely a www→non-www redirect misconfigured for the /sitemap.xml path, or the www host simply serves the homepage for any unmatched path). FLAGGED.
- Correct sitemap entrypoint confirmed: https://competitor-d.example/sitemap_index.xml (200, application/xml, Yoast SEO sitemap index) — recommend updating watchlist/competitors.yaml domain reference to the bare non-www form or noting the working sitemap path explicitly.
- Sub-sitemaps in index: post-sitemap.xml, page-sitemap.xml, lead_scanner-sitemap.xml, testimonials-sitemap.xml, academy-post-sitemap.xml, countries-sitemap.xml, testimonials-2-sitemap.xml, wm-event-sitemap.xml, wm-webinar-sitemap.xml, category-sitemap.xml, author-sitemap.xml

** Crawl (post-sitemap.xml, truncated at ~200,000 chars by fetch limit — partial but representative): **
Total <loc> entries captured: 239 blog post URLs (bilingual EN/DE, e.g. /blog/... and /de/blog/...)
- Content themes: EOR onboarding, global hiring guides, payroll/tax by country, employee benefits, talent retention, recession/career content, company culture case studies (five named customer case studies)
- Oldest visible lastmod in this partial crawl: 2023-05 · newest: 2024-11 (crawl was truncated before reaching the most recent 2026 posts — full post count and latest additions not fully captured this run)
- No Workation/A1/business-travel-compliance content detected in the sampled set — EOR/global-hiring focus confirmed.

** Status vs previous run (2026-08-31): **
- Previous snapshot was qualitative only ("kein detaillierter Blog-Auszug verfügbar") — this run is the first to actually reach and parse the sitemap successfully (previous run likely hit the same www→homepage redirect issue without following up to the working bare-domain sitemap).
- Domain correction applied this run: use competitor-d.example (no www) for sitemap crawls going forward.

** Summary: **
Competitor D's canonical sitemap only resolves correctly at the bare (non-www) domain — competitors.yaml domain entry should be corrected/annotated to competitor-d.example. Content remains EOR/global-hiring/payroll focused with no workation or short-term-travel-compliance angle. Low priority for the Competitor-A-gap cluster; blog post inventory (239+ sampled, full count likely higher) not fully diffable yet since this is the first successful full crawl.
