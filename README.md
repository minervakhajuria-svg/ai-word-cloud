# AI Word Cloud

An animated word cloud of the AI terms that appear in the most AI news articles published 1-31 October 2026 (72 articles: 36 TechCrunch, 26 VentureBeat, 10 MIT Technology Review). Hover or tap a word for a plain-language definition, its article count, and two articles to read.

**Live page:** https://minervakhajuria-svg.github.io/ai-word-cloud/

## Method and limits
- Each term is counted once per article, however many times it appears.
- Variants are merged, so "token", "input tokens" and "cached tokens" all count as tokens.
- A model pulled the terms out of each article's full text, so counts are approximate.
- Sources are TechCrunch, VentureBeat and MIT Technology Review. MIT Technology Review's feed blocks automated reads, so its 10 articles were found by search and read individually, and it is thinner than the other two. The Verge, Wired, Ars Technica, CNET and ZDNet were not read, so none are in the counts.
- Articles are a sample, not every story: the last full read was 30 October, so 31 October is not covered, and early October (1-6) is thinly covered, especially VentureBeat.
- Last refreshed 1 November 2026.
- Definitions were written for this page and have not been editorially reviewed.

## Updating
Replace `WORDS`, `LINKS`, `TOTAL`, the date range and the source note in `index.html`. Keep `WORDS` sorted from highest count to lowest.
