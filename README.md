# Builders — Second Brain

This vault is the operating system for a one-person product company. Every decision, draft, contact, and idea lives here so nothing exists only in your head or scattered across apps. The second-brain concept means you capture once, tag consistently, and retrieve by asking Claude to read a folder rather than scrolling through memory. Each department folder is a dedicated context window: when you sit down to do sales work, you open Sales/ and ask Claude to brief you; when you ship a feature, Development/ holds the spec and the post-mortem. The vault grows alongside your business — what starts as a few files becomes a searchable, referenceable history of every product decision you have ever made.

## Departments

| Folder | Purpose |
|---|---|
| [Development/](Development/INDEX.md) | Product specs, technical decisions, code review notes |
| [Marketing/](Marketing/INDEX.md) | Campaigns, landing-page copy, ad creative, content calendar |
| [Audience/](Audience/INDEX.md) | Newsletter drafts, social posts, podcast episodes |
| [Sales/](Sales/INDEX.md) | Outreach lists, DM templates, call notes, pipeline tracker |
| [Research/](Research/INDEX.md) | Market data, competitor analysis, pain-point quotes, ICP profiles |
| [Operations/](Operations/INDEX.md) | Meeting transcripts, weekly reviews, finance, OKRs |
| [Project/](Project/INDEX.md) | Current active project — live outputs from this Builder Kit |
| [_System/](\_System/conventions.md) | Naming standards, templates, tagging rules |

## Example Workflows

### Product launch
1. Drop competitor research into `Research/2026-05-21-competitor-audit.md`.
2. Write a spec in `Development/2026-05-21-spec-feature-name.md`.
3. Ask Claude: *"Read Research/ and Development/ and write a one-page positioning brief for this feature."*
4. Paste the brief into `Marketing/2026-05-21-positioning-feature-name.md`.

### Marketing campaign
1. Capture audience pain-point quotes in `Research/2026-05-21-pain-points-icp.md`.
2. Draft the campaign in `Marketing/2026-05-21-campaign-slug.md`.
3. Ask Claude: *"Read Research/pain-points and Marketing/campaign — rewrite the headline and subhead to lead with the top pain point."*

### Sales sprint
1. Update your pipeline in `Sales/pipeline-tracker.md`.
2. Log each call in `Sales/2026-05-21-call-{name}.md`.
3. Ask Claude: *"Read Sales/ and tell me which 3 prospects are warmest and what the next action is for each."*
