# Sales/

This folder tracks every human conversation that could turn into revenue. It holds outreach lists with contact details and status, DM and cold-email templates that have been tested and refined, notes from every sales call or discovery conversation, and the pipeline tracker that gives you a live view of where each deal stands. The discipline is: every prospect interaction gets logged the same day it happens. A folder full of call notes is not busywork — it is the data set you hand Claude when you need to know who to follow up with and what to say.

## How to use

1. **Keep `pipeline-tracker.md`** as a Markdown table: Name, Company, Stage, Last Contact, Next Action, Value. Update it after every interaction.
2. **Log each call or DM thread** in its own file the same day — what they said, what you said, open questions, agreed next step.
3. **Store DM/email templates** in `templates/` subfolder, one file per use case (cold intro, follow-up, proposal send, win/loss close).
4. **When building an outreach list**, create one file per campaign with the list as a table — Name, Handle/Email, Why Now, Sent date, Reply.
5. **After closing or losing a deal**, add a two-sentence win/loss note to the bottom of that prospect's call-note file.

## File-naming convention

```
2026-MM-DD-sal-{type}-{slug}.md
```
Examples:
- `2026-05-21-sal-call-jane-acme.md`
- `2026-05-21-sal-outreach-list-solopreneurs-batch1.md`
- `pipeline-tracker.md` (evergreen)
- `templates/sal-template-cold-intro.md`

## Ask Claude

- *"Read Sales/pipeline-tracker.md and all call notes from the last 14 days — which 3 prospects should I follow up with this week and what should I say?"*
- *"Read Sales/ and write a follow-up message for each prospect who has gone quiet for more than 7 days, using context from their call notes."*
- *"Read Sales/templates/ and the last 5 call notes — identify the objection that comes up most and write a new rebuttal to add to the cold-intro template."*
