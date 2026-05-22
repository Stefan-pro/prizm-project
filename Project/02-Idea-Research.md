---
date: 2026-05-21
tags: [project, research, idea-validation, proposal-app, ai]
status: active
project: proposal-generator
---

# Project Brief — AI Proposal Generator

## The idea in one sentence
An AI-powered web app that turns a 2-minute project brief into a complete, polished client proposal — including scope, pricing suggestions, timeline, deliverables, and a presentation-ready layout.

---

## Who it's for
**Primary:** Freelance web designers, developers, and graphic designers aged 21–40  
**Secondary:** Small agencies (2–10 people), copywriters, video editors, social media managers, brand consultants  
**They earn:** $2,000–$15,000/month from client work  
**Their pain:** Writing proposals takes 2–5 hours, pricing feels like guessing, and a weak proposal loses the deal before the conversation starts

---

## The core problem
Most freelancers lose deals not because of skill — but because their proposal looks amateur, undercharges, or takes so long to write that the client moves on. Existing tools (Proposify, PandaDoc, Bonsai) give you blank templates. They don't help you think. An AI that actually drafts the content, suggests pricing based on project type, and outputs something polished in minutes is a different product entirely.

---

## Competition

| Tool | Price/mo | What it does | What it lacks |
|---|---|---|---|
| Proposify | $49–$99 | Proposal templates + e-sign | No AI, expensive, bloated |
| Better Proposals | $19–$49 | Templates + analytics | No AI, generic |
| PandaDoc | $19–$49 | Document automation | Not freelancer-focused |
| Bonsai | $17–$32 | Freelancer all-in-one | Proposals are secondary feature |
| Qwilr | $35–$59 | Web-based proposals | No AI, design-heavy learning curve |

**The gap:** Every competitor is template-based. You fill in the blank. Nobody uses AI to *generate* the proposal content, suggest pricing, and scope the project. That's the opening.

---

## Differentiator
- AI writes the first draft — you just answer 6 questions
- Pricing suggestions based on project type, scope, and market rates
- Built specifically for freelancers and creatives (not enterprise)
- Output looks like it was designed by a senior designer, not filled in on a form
- Fast: proposal ready in under 3 minutes

---

## MVP — build this first, nothing else

### User flow
1. User answers 6 intake questions:
   - What type of project? (website, branding, social media, video, etc.)
   - What does the client do / what's their industry?
   - What are the main deliverables?
   - What's the rough budget range?
   - What's the timeline?
   - Any special requirements or notes?
2. AI generates a complete proposal draft:
   - Project overview paragraph
   - Scope of work (bulleted deliverables)
   - Suggested pricing breakdown (line items)
   - Timeline with phases
   - What's included / what's not included
   - Next steps / call to action
3. User edits inline — text is editable before export
4. Export as PDF or shareable link

### MVP screens (5 total)
- Landing page (what it does, sign up)
- Intake form (6 questions)
- Proposal preview (editable)
- Export / share screen
- Dashboard (list of saved proposals)

### What is NOT in the MVP
- Team/agency features
- Client e-signature
- CRM or pipeline tracking
- Custom branding / white-label
- Template library
- Payment integration

---

## Build stack (realistic for your skill level)

| Layer | Tool | Why |
|---|---|---|
| Frontend / UI | Webflow or Framer | Visual, modern, no-code — matches your skills |
| App logic + database | Bubble.io | No-code app builder, handles user accounts, data, API calls |
| AI generation | Claude API (Anthropic) or OpenAI GPT-4o | Claude produces cleaner long-form professional writing |
| PDF export | Bubble PDF Conjurer plugin or html2pdf | Converts the proposal view to a downloadable PDF |
| Payments | Stripe (via Bubble plugin) | Simple subscription billing |

**Learning path:** Bubble.io is the core skill to learn. It handles the database, user accounts, and API connections. The AI call is just sending the 6 answers to Claude/GPT and displaying what comes back. This is beginner-friendly in Bubble.

**Estimated build time (learning as you go):** 6–10 weeks for MVP

---

## Monetization

| Plan | Price | What you get |
|---|---|---|
| Free | $0 | 3 proposals/month, watermarked PDF |
| Pro | $19/month | Unlimited proposals, clean PDF export, shareable link |
| Agency | $49/month | 5 team seats, client portal, custom branding |

**Target:** 100 Pro users = $1,900/month. Achievable within 6 months with focused distribution.

---

## Go-to-market (where your first 100 users come from)

1. **You are the target user** — post your own story: "I built this because writing proposals was killing my time as a web designer"
2. **Communities with instant access today:**
   - r/freelance (500k+ members)
   - r/webdesign, r/graphic_design
   - Designer Hangout Slack
   - Twitter/X #freelance #webdesign hashtags
   - Facebook "Freelance Web Designers" groups
   - Indie Hackers (build in public — post weekly progress)
3. **Product Hunt launch** — plan for week 8 after MVP is solid
4. **Content angle:** "How I went from 4-hour proposals to 3-minute proposals" — one post, posted everywhere

---

## Why this works for you specifically
- You have written proposals as a web designer — you know exactly what's painful
- You know what a good proposal looks like (your design eye is a direct asset)
- Your network is full of potential beta users right now
- The problem has clear ROI: better proposal = more deals closed = buyer pays for itself in one won project

---

## Risks to watch
- **Competition from big players adding AI** — Proposify or Bonsai could add AI. Mitigation: be faster, cheaper, and better designed for freelancers specifically.
- **AI output quality** — generic proposals won't impress. Mitigation: invest heavily in the prompt engineering. The prompt IS the product.
- **Low conversion free → paid** — Mitigation: make the free watermark obvious enough to motivate upgrade without being annoying.

---

## Next steps
- [ ] Map the full onboarding flow on paper (6 questions → what AI receives → what it outputs)
- [ ] Write the AI prompt that generates the proposal (this is the most important thing to get right)
- [ ] Sign up for Bubble.io and complete their intro course (free, ~4 hours)
- [ ] Build a fake door landing page in Webflow/Carrd to test demand before building the full app
- [ ] Get 10 freelancer friends to describe their proposal pain in their own words (use for marketing copy)
