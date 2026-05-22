# Marketing/

This folder holds every outward-facing message about the product. Campaigns from first draft to live, landing-page copy with version history, ad creative briefs and copy variants, a content calendar that maps what goes out and when, and positioning documents that anchor the voice and message. Having all copy in one place means you never rewrite the same headline twice — you pull from what already worked, iterate on what did not, and ask Claude to remix rather than invent from scratch.

## How to use

1. **Start each campaign** with a brief (`2026-05-21-mkt-campaign-{slug}.md`) — goal, audience segment, channels, timeline, KPIs.
2. **Draft landing-page copy** in its own file; keep versions by appending `-v2`, `-v3` rather than overwriting.
3. **Log ad creative** with the copy, targeting notes, and result (CTR, spend, outcome) in a single file per ad set.
4. **Maintain `content-calendar.md`** as an evergreen tracker: date, channel, topic, status, link to draft.
5. **Keep a `positioning.md`** at the folder root — one-liner, value prop, ICP, key differentiators — so every piece of copy can reference it.

## File-naming convention

```
2026-MM-DD-mkt-{slug}.md
```
Examples:
- `2026-05-21-mkt-campaign-launch-week.md`
- `2026-05-21-mkt-lp-hero-copy-v1.md`
- `2026-05-21-mkt-ad-twitter-pain-point.md`
- `content-calendar.md` (evergreen)
- `positioning.md` (evergreen)

## Ask Claude

- *"Read Marketing/positioning.md and the three most recent campaign files — write five headline variants for the next campaign that match the voice."*
- *"Read Marketing/content-calendar.md and tell me what content is due this week and flag anything with no draft yet."*
- *"Read Marketing/2026-05-21-mkt-lp-hero-copy-v1.md and rewrite it to lead with the top pain point from Research/pain-points.md."*
