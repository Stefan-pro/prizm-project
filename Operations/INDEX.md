# Operations/

This folder runs the business behind the business. It holds transcripts or notes from every meeting (client calls, advisor chats, co-working sessions), weekly review files that capture what shipped, what stalled, and what you learned, financial records (revenue, expenses, MRR tracking), and OKR documents that keep the quarter on track. Operations/ is the folder you read on Monday morning to orient yourself and on Friday afternoon to close the week cleanly. Keeping it current takes five minutes a day and saves hours of reconstructing context later.

## How to use

1. **Every Friday**, write a weekly review (`2026-05-21-ops-weekly-review.md`) — what shipped, what stalled, top learning, plan for next week.
2. **After every meeting**, create a note the same day — attendees, agenda, key decisions, action items with owners and due dates.
3. **Track financials** in `finance/mrr-tracker.md` — a simple table updated monthly: month, new MRR, churned MRR, net MRR, total MRR.
4. **Set OKRs each quarter** in `okr-2026-q2.md` — 2–3 objectives, 2–3 key results each, reviewed weekly.
5. **Write a one-paragraph `annual-plan.md`** at the start of each year so quarterly OKRs have a north star to align to.

## File-naming convention

```
2026-MM-DD-ops-{type}-{slug}.md
```
Examples:
- `2026-05-21-ops-weekly-review.md`
- `2026-05-21-ops-meeting-advisor-john.md`
- `2026-05-21-ops-daily.md`
- `okr-2026-q2.md` (evergreen per quarter)
- `finance/mrr-tracker.md` (evergreen)

## Ask Claude

- *"Read Operations/ weekly reviews from the last 4 weeks — what patterns keep appearing in the 'stalled' section and what should I do about them?"*
- *"Read Operations/okr-2026-q2.md and the last 3 weekly reviews — score my progress on each key result and flag which ones are at risk."*
- *"Read Operations/finance/mrr-tracker.md and write a 3-sentence financial summary I can include in my next investor update."*
