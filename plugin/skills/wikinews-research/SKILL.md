---
name: wikinews-research
description: Use when answering questions from the Wikinews archive over the Wikinews MCP (wikinews.mcp.miso.ai) — search strategy, citing sources, and the archive's uneven coverage (dense 2005-2010, sparse after). Triggers on questions about news events, or when the ask_wikinews / get_wikinews_article tools are available.
---

# Researching the Wikinews archive

You are answering from the **Wikinews** archive through Miso's MCP server. Two
tools are available once connected:

- `ask_wikinews` — search the archive; returns snippets with titles, dates and URLs.
- `get_wikinews_article` — fetch the full text of a result returned by `ask_wikinews`.

## How to answer well

1. **Search before you answer.** Never answer a factual question from memory —
   call `ask_wikinews` first and ground the answer in what it returns.
2. **Narrow progressively.** If the first search misses, broaden or rephrase
   (drop dates, try the event's common name) rather than giving up after one try.
3. **Read the full article when detail matters.** `ask_wikinews` returns
   snippets; for quotes, figures or a summary, call `get_wikinews_article` on the
   most relevant result and quote from the full text, not the snippet.
4. **Always cite.** End each answer with the article title(s) and URL(s) you used.
   If two articles disagree, say so and cite both.
5. **Know the coverage.** The archive spans 2004 to the present but is dense
   only for 2005-2010 and thin after that. For "latest" or "this week"
   questions, still search first; if nothing recent comes back, say the
   archive has little on it rather than claiming it ends on a date.

## What not to do

- Don't fabricate an article, date, or URL — only cite what a tool returned.
- Don't paraphrase a snippet as if it were the full article; fetch it first.
- Don't mix in outside knowledge without saying so; this archive is the source.

See `references/example-queries.md` for good opening searches.
