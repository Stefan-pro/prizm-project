# Research/

This folder is the evidence base for every decision in the business. It holds market-size data and trend reports, competitor teardowns (pricing, positioning, features, weaknesses), raw pain-point quotes gathered from interviews, surveys, Reddit threads, and reviews, and Ideal Customer Profile (ICP) documents that describe exactly who you are building for and why. Research/ is the folder you read before writing a spec, before writing a landing page, and before opening a cold-outreach campaign — it keeps your work grounded in what is real rather than what you assume.

## How to use

1. **When you discover a pain-point quote** (from a call, a tweet, a review), paste it verbatim into a running `pain-points.md` file with source and date.
2. **For each competitor**, maintain one file with: overview, pricing, positioning, strengths, weaknesses, and a "gaps we can exploit" section.
3. **After every customer interview**, write a one-page summary in a dated file — quotes, job-to-be-done, biggest frustration, how they currently solve it.
4. **Update `icp-profile.md`** whenever you learn something new about who your best customers are — demographics, psychographics, triggers, watering holes.
5. **Capture market data** (TAM, trends, stats) in dated files with a source link so you can cite them later.

## File-naming convention

```
2026-MM-DD-res-{slug}.md
```
Examples:
- `2026-05-21-res-competitor-notion.md`
- `2026-05-21-res-interview-freelancer-designer.md`
- `2026-05-21-res-market-pkm-tools-2026.md`
- `pain-points.md` (evergreen, append-only)
- `icp-profile.md` (evergreen, versioned with frontmatter)

## Ask Claude

- *"Read Research/pain-points.md and group the quotes into the top 3 themes, then rank them by frequency."*
- *"Read Research/ and write a competitive positioning table: us vs. the top 3 competitors on price, target user, and key differentiator."*
- *"Read Research/icp-profile.md and Research/pain-points.md — write a 200-word 'who this is for' section for the landing page."*
