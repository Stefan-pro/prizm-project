---
date: 2026-05-21
tags: [project, marketing, landing-page]
status: active
project: proposal-generator
---

# Landing Page — Prizm

## Live URL
https://landing-page-idsglmwsf-temelkoskistefan-4408s-projects.vercel.app

## Inspect / Vercel dashboard
https://vercel.com/temelkoskistefan-4408s-projects/landing-page/7pfCH5HK6sv3QhSejusTZzETeLUK

## Source
`~/Obsidian/Builders/Project/landing-page/index.html`
Cloned from: https://github.com/Builders-mk/rails-starter

---

## Sections built

1. **Hero** — Headline "Create Client Proposals 10x Faster", subhead, two CTAs side by side
2. **Social proof strip** — Testimonial placeholder + 3 trust signals (2+ yrs, <10 min, $0 to start)
3. **The Problem** — 4 pain cards: hours lost, pricing anxiety, inconsistency, silent losses
4. **Who this is for** — 3 trait cards on dark background
5. **How it works** — 3 numbered steps
6. **Pricing** — $29/month, 6 deliverables listed, 30-day free trial, single CTA
7. **FAQ** — 4 objections: price, timeline, solo fit, risk
8. **Risk reversal** — "Try it free for 30 days — if it doesn't help you close more deals, you pay nothing."
9. **Final CTA** — Same two buttons as hero
10. **Lead magnet opt-in** — ConvertKit placeholder (section id="lead-magnet")
11. **Footer** — Name, email, LinkedIn, Twitter/X

---

## TODOs before going live to real traffic

- [ ] Replace ConvertKit placeholder in `#lead-magnet` section with your actual embed code
- [ ] Update footer email (`hello@proposalkit.io` → your real email)
- [ ] Update footer LinkedIn and Twitter links to your real profiles
- [ ] Add first real testimonial when you have one (marked clearly with a placeholder)
- [ ] Connect a custom domain in Vercel dashboard (Settings → Domains)
- [ ] Run Google PageSpeed Insights on the live URL and confirm 90+ score

---

## Design decisions

- **Brand:** Prizm — logo embedded as base64 data URI (no external image dependency)
- **Accent color:** Indigo (`#6366f1`) — matches Prizm logo's purple-blue iridescent aesthetic
- **Font:** Inter via Google Fonts — clean, modern, readable at all sizes
- **Mobile-first:** All sections stack vertically on mobile, side-by-side on sm+ breakpoints
- **No animations, no carousels, no popups** — fast load, scannable, zero friction
- **Tailwind CDN** — no build step, deploys as pure static HTML

---

## Redeploy after changes

```powershell
$env:PATH = 'C:\Program Files\nodejs;C:\Users\User\AppData\Roaming\npm;' + $env:PATH
Set-Location 'C:\Users\User\Obsidian\Builders\Project\landing-page'
& 'C:\Users\User\AppData\Roaming\npm\vercel.cmd' --prod --yes
```

---

## Prompt used to build this

Read `02-Offer.md` and `04-Lead-Magnet.md`. Clone rails-starter repo. Build a
single-page Tailwind landing site with 10 sections in order: Hero, Social Proof,
Problem, Who It's For, How It Works, Pricing, FAQ, Risk Reversal, Final CTA,
Lead Magnet Opt-in, Footer. White background, indigo accent, mobile-first,
8th-grade reading level, no animations. Logo from ~/Obsidian/Builders/Marketing/Logo.png.
Deploy with `vercel --prod`.
