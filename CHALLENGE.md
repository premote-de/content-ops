# Challenge: plan the engine's next article

**Time box: 2 hours.** Stop when the time is up, even if you are not finished, and note where you stopped. We value good prioritisation more than completeness.

## Context

This repository is the memory of premote's autonomous content engine. An agent writes wiki articles for [premote.de](https://www.premote.de) following the operating manual in `agent/AGENTS.md`: it picks a topic from the roadmap, researches it, drafts the article in German and English, opens a pull request on the website repository and asks a human for approval in Slack. Everything it decides is written down here: the sources it watches, the competitors it tracks, the topic gaps it found, the research behind every article, and a log of what it did.

The notes are in English. The search keywords are the original German queries, because premote.de serves the German market first.

For this challenge you act as the human who owns this system. Your job is to do one run of the pipeline by hand, up to the point where the article would be written, and to present the result in our meeting.

## Your task

**Plan the next article and present your plan in the interview.**

### 1. Understand the system (about 30 minutes)

Read, in this order:

- `agent/AGENTS.md` (the operating manual, especially "Content pipeline", "SEO data requirement" and "Focus")
- `pipeline/content-style.md` and `pipeline/dataforseo.md` (what a good article is, and how topics are chosen and justified)
- `roadmap/competitor-a-gap.md` (the topic backlog and how picks are recorded)
- `briefings/premote-content-briefing.md`, sections 1 and 2 plus one cluster of your choice (positioning and scope)
- one research note, for example `research/workation-griechenland.md`, and one entry in `reports/activity.md`

### 2. Pick the next topic (about 20 minutes)

Choose one topic cluster for the next article. Candidates can come from the gap roadmap (including rows marked `[skip]`, if you disagree with the skip), from the numbered topics in the briefing, or from your own research. The topic must be inside the scope defined in briefing section 1 and must be justified with the decision rules in `pipeline/dataforseo.md`.

You do not have API access. Use any free keyword tool or the numbers already in this repository, and label estimates as estimates.

### 3. Prepare your plan (about 60 minutes)

Prepare the following in whatever format suits you: a document, slides, or markdown files. No fork and no pull request are needed.

**a) The roadmap entry.** How you would record your pick in `roadmap/competitor-a-gap.md` (or in `roadmap/global-mobility.md` if the topic comes from the briefing), marked `[x] <date>` with the justification, in the format the file already uses.

**b) The research note**, following the pattern of the existing notes in `research/`:

- the keyword cluster with volumes and your data source
- the "Why this topic" line in the exact format given in `pipeline/dataforseo.md`
- at least three sources you actually opened: URL, access date, one quote each (official sources first, then professional bodies, then media)
- the article outline: H2 sections, which comparison table the article gets, 3 to 5 FAQ questions phrased as real user questions
- at least three internal links to existing articles on premote.de (wiki slugs)
- a writing sample in English: the answer-first lead (2 to 4 sentences), a meta title (max. 60 characters) and a meta description (max. 155 characters). If you write German, a German version of the lead is welcome in addition.

**c) A short presentation** for the meeting (about 10 minutes, then discussion): your topic choice and why, the numbers and sources you relied on, the outline, and what you would do next on this topic if you had a full day. Tell us what is verified and what is estimated, and which tools you used (AI tools are fine).

### 4. Optional, only if time remains

`brand-voice.md` is still a placeholder. Draft version 1: five do/don't rules and five example sentences quoted from live premote.de articles, following the instructions at the top of that file.

## Rules

- Every factual claim needs a source you opened yourself (hard rule 3 in the manual). Never cite a URL you did not read.
- `premote` is always lowercase, also at the start of a sentence.
- You need no access to Slack, the server or any API for this task, and you should not try to obtain any.
- Bring your material to the meeting. You can share your screen or send it to us beforehand; nothing needs to be committed to this repository.

## What we look at

- Judgment: is the topic a real gap, in scope, and worth the effort? Is the reasoning traceable?
- Data literacy: are numbers sourced, dated and honestly labelled?
- Source quality: official and primary sources, actually read.
- Structure: does the outline follow `pipeline/content-style.md`?
- Writing: precise, practical, compliance-literate English without filler.
- Pragmatism: did you respect the time box and say what you left out?

We will discuss your plan together in the interview.
