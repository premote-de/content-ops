# Content style & GEO format (what "really good content" means here)

Format rules distilled from the webentity pitch (Mar 5 + Apr 20 recordings) and premote's own corpus. AI answer engines currently prefer and cite content that follows this shape.

## Structure of every article
1. **Answer first**: the opening 2–4 sentences directly answer the implied query (the existing `summary`/`lead` fields carry this). No warm-up prose.
2. **Heading hierarchy**: one H1 (title), H2 sections with anchor ids, H3 sparingly.
3. **Comparison table** wherever the topic allows (country vs country, option vs option, deadlines, thresholds). Answer engines love tables.
4. **FAQ block**: 3–5 short Q&As at the end, phrased as real user questions (feeds FAQPage JSON-LD).
5. **Sources section**: named sources with dates. Official > professional org > media.
6. **Internal links**: ≥3 links to related wiki articles / country pages / solution pages. When a new article goes live, also add links FROM the most related existing articles TO it (separate small edits in the same PR).
7. **Freshness**: dateModified must reflect real content changes; visible "last updated" stamp.

## Quality bar
- ≥3 independent, fetched-and-read sources; every number/threshold/date traced to one.
- No AI filler phrases, no generic intros, no "in today's fast-paced world"-style openers.
- Surgical updates: when a law changes, update the affected section, not the whole page.
- DE is the primary text (formal "Sie" address), EN is an adaptation for international readers.
- Legal disclaimer block stays.

## Distribution
- After merge: ping IndexNow (Bing) with new/changed URLs; Google picks up via sitemap lastmod.
- JSON-LD: Article (+ FAQPage when FAQ present) per article — via the site's JsonLd component.

## Later (backlog, from the pitch)
- Event/campaign landing pages on request via Slack.
- Lead-magnet calculators (e.g. A1 processing-time checker).
- Country landing pages triggered by ranking gaps (bot proposes, human approves).
- Compliance-changelog feed as subscribable page.
- HubSpot forms/sequences via API (premote has Sales Enterprise).
