# Development/

This folder is the technical memory of the product. It holds everything that explains *what you are building and why*: feature specs before you write a line of code, architecture decision records (ADRs) that capture why you chose one approach over another, code-review notes that track what changed and what broke, and post-mortems that close the loop after incidents. Keeping this folder current means you can onboard a contractor, revisit a decision six months later, or hand a spec to Claude for implementation help without re-explaining context from scratch.

## How to use

1. **Before coding**, write a spec (`2026-05-21-dev-{feature}.md`) — problem, proposed solution, acceptance criteria, open questions.
2. **When choosing a tech approach**, create an ADR (`2026-05-21-dev-adr-{decision}.md`) — options considered, decision made, trade-offs accepted.
3. **After a PR merges**, add a brief code-review note — what changed, what edge cases were caught, what tech debt was introduced.
4. **After a bug or outage**, write a post-mortem (`2026-05-21-dev-postmortem-{slug}.md`) — timeline, root cause, fix, prevention.
5. **Maintain a running `roadmap.md`** at the folder root that lists features by status: backlog / in-progress / shipped.

## File-naming convention

```
2026-MM-DD-dev-{slug}.md
```
Examples:
- `2026-05-21-dev-spec-onboarding-flow.md`
- `2026-05-21-dev-adr-database-choice.md`
- `2026-05-21-dev-postmortem-payment-timeout.md`
- `roadmap.md` (evergreen, no date)

## Ask Claude

- *"Read Development/ and summarize all open technical decisions and unresolved questions."*
- *"Read Development/roadmap.md and the three most recent specs — what should I build next based on dependencies and impact?"*
- *"Read Development/2026-05-21-dev-spec-{feature}.md and write the acceptance-criteria test cases as a checklist."*
