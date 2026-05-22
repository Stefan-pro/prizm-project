# Project/

This folder is the live workspace for whatever you are building right now. It is the one folder that changes the most: specs get drafted here before moving to Development/, campaign briefs get started here before moving to Marketing/, and raw outputs from this Builder Kit session land here first. Think of Project/ as your current desk — everything actively in progress sits here. When a project ships or is shelved, the folder gets archived to `_archive-YYYY-MM-{project-name}/` at the vault root.

## How to use

1. **Start every new project** with a `project-brief.md` — one paragraph on the problem, the solution, the target user, and the definition of done.
2. **Use Project/ as a staging area**: draft specs, copy, and outreach here, then move or link them to the relevant department folder once they are solid.
3. **Keep a `project-log.md`** — a running append-only log of daily progress, blockers, and decisions. Date each entry.
4. **Track the launch checklist** in `launch-checklist.md` — a Markdown checkbox list of every task required to ship.
5. **When the project closes**, move all mature outputs to their department homes, then archive this folder.

## File-naming convention

```
2026-MM-DD-prj-{slug}.md
```
Examples:
- `project-brief.md` (evergreen for this project)
- `launch-checklist.md` (evergreen for this project)
- `project-log.md` (evergreen, append-only)
- `2026-05-21-prj-spec-waitlist-page.md`
- `2026-05-21-prj-copy-hero-draft.md`

## Ask Claude

- *"Read Project/ and give me a one-paragraph status update: what is done, what is in progress, and what is blocked."*
- *"Read Project/launch-checklist.md and project-log.md — what are the 3 highest-priority remaining tasks to hit the launch date?"*
- *"Read Project/project-brief.md and Development/roadmap.md — does the current roadmap align with the project brief, and what is missing?"*
