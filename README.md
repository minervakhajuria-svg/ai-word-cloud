# AI Word Cloud

An animated word cloud of the AI terms that appear in the most AI news articles published 12-25 October 2026 (39 articles). Hover or tap a word for a plain-language definition, its article count, and two articles to read.

**Live page:** https://minervakhajuria-svg.github.io/ai-word-cloud/

## Method and limits
- Each term is counted once per article, however many times it appears.
- Variants are merged, so "token", "input tokens" and "cached tokens" all count as tokens.
- A model pulled the terms out of each article's full text, so counts are approximate.
- The Verge, Wired, Ars Technica, CNET and ZDNet could not be read, so none are in the counts.
- Four TechCrunch links use short numeric addresses (`techcrunch.com/?p=...`) that should redirect to the article.
- For "evals", one link goes to an AI Chief summary of a TechCrunch story.
- Definitions were written for this page and have not been editorially reviewed.

## Updating
Replace `WORDS`, `LINKS`, `TOTAL`, the date range and the source note in `index.html`. Keep `WORDS` sorted from highest count to lowest.
