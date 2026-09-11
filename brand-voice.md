# premote brand voice (v0 — to be extracted)

Phase-2 task for the engine: read 15 representative wiki articles + 5 country pages
+ the solution pages from website/src/content, and distill:
- sentence length & rhythm, formal "Sie" address conventions, terminology (Dienstreise, Entsendung,
  Workation, A1-Bescheinigung, Meldepflicht, ... — i.e. business trip, posting, workation, A1 certificate,
  notification duty), what premote never says,
  how legal references are cited, how CTAs are phrased per audience (HR vs traveler).
Write the result here as concrete do/don't rules with 10+ real example sentences
from the corpus, then keep it updated when reviewers correct drafts.

## Fixed brand rule (Johannes, 2026-08-23)
**premote is ALWAYS lowercase** — also at the start of a sentence, in headings, meta titles and meta descriptions. Never "Premote". Before every PR: `grep -c "Premote"` on all changed content files must return 0.
