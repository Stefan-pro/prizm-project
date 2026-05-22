# Vault Conventions

## File-naming standard

```
YYYY-MM-DD-{department-prefix}-{slug}.md
```

| Department | Prefix | Example |
|---|---|---|
| Development | `dev` | `2026-05-21-dev-auth-spec.md` |
| Marketing | `mkt` | `2026-05-21-mkt-launch-campaign.md` |
| Audience | `aud` | `2026-05-21-aud-newsletter-issue-12.md` |
| Sales | `sal` | `2026-05-21-sal-call-jane-acme.md` |
| Research | `res` | `2026-05-21-res-competitor-notion.md` |
| Operations | `ops` | `2026-05-21-ops-weekly-review.md` |
| Project | `prj` | `2026-05-21-prj-feature-waitlist.md` |

**Evergreen files** (not date-scoped) omit the date prefix:
- `pipeline-tracker.md`
- `okr-2026-q2.md`
- `icp-profile-v2.md`

Slugs are lowercase, hyphen-separated, no spaces or special characters.

---

## Daily note template

Create as `Operations/YYYY-MM-DD-ops-daily.md`:

```markdown
# YYYY-MM-DD

## Top 3 today
- [ ] 
- [ ] 
- [ ] 

## Decisions made
- 

## Captures (links to files created today)
- 

## Tomorrow
- 
```

---

## Tagging rules

Use YAML frontmatter at the top of every file:

```yaml
---
date: YYYY-MM-DD
tags: [department, type, status]
status: draft | active | done | archived
project: slug-of-current-project
---
```

### Standard tag vocabulary

**Department tags** (always include one):
`development` `marketing` `audience` `sales` `research` `operations` `project`

**Type tags** (always include one):
`spec` `campaign` `newsletter` `outreach` `analysis` `transcript` `review` `template` `tracker`

**Status tags** (optional but useful):
`draft` `active` `done` `archived` `blocked`

---

## Linking conventions

- Link related files with `[[filename]]` syntax.
- Every spec in Development/ should link to its Research/ source file.
- Every campaign in Marketing/ should link to its Research/ pain-point file.
- Pipeline entries in Sales/ should link to their call-note files.

---

## Archiving

When a project is complete, prefix its folder or file with `_archive-YYYY-MM-`:
```
_archive-2026-05-project-builder-kit/
```
This keeps the vault root clean while preserving history.
