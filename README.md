# ai-news-from-x

Daily AI news roundup pulled from X (Twitter) — OpenAI, Anthropic, and inspiring research.

Each day a new file lands in [`news/`](news/) named `YYYY-MM-DD.md`. Newest entries are the highest-numbered date.

## How it runs

- A local scheduled Claude task fires at 7:00pm America/Los_Angeles daily.
- A remote routine on claude.ai fires at the same time as a backup when the local app is closed.
- Both pull fresh posts from `site:x.com` searches, write a short roundup, and push a new file to this repo.

## Sections in each daily file

1. **OpenAI** — model releases, product launches, business moves
2. **Anthropic** — model releases, deals, valuation/revenue
3. **Inspiring research** — papers, benchmarks, open-source breakthroughs

Under 400 words. Bullets, no hype. Sources are X post URLs at the bottom.
