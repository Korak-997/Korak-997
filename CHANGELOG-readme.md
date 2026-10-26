# README rewrite: changelog

## 2026-10-26: evidence update

- Heading now carries the current title; the summary covers real-time AI, TypeScript and Nuxt,
  platform engineering, and leadership.
- Badges cut to TypeScript, Nuxt, NestJS, PostgreSQL, AWS, and AI; the four-row badge table is gone.
- "What I've built" replaced by links to the case studies on korak-kurani.com, so the claims live in
  one place with their boundaries.
- "I lead five developers" corrected to an IT team of five team members (not all developers).
- Banner title changed from "AI platform architect" to "Senior Fullstack Developer".
- Stale `TODO(verify)` comments removed.

## Earlier rewrite

Branch: `readme-rewrite`

## Removed, and why

- Visitor counter: third-party tracking image, reads as a beginner template.
- "Hey there! ✨ I'm Korak 👋" heading and all decorative emoji: replaced by a banner and plain headings.
- "Turning ideas into reality, one line of code at a time." quote: generic, not a fact.
- daily.dev dev card: third-party image, and the link points at a different account than the card.
- "Full-stack Developer" line: out of date, you are Team Lead since July 2026.
- "Tech Arsenal" row of `for-the-badge` badges: loud, mixed brand colours, and it included Ruby (not a core skill per F10), Astro, JavaScript and Git.
- Let's Connect badges for daily.dev and Dev.to: the daily.dev link is the mismatch you flagged; Dev.to was not in the brief.
- Closing "say hi" and "build something amazing" lines: filler.

## Added

- `assets/banner-light.svg`, `assets/banner-dark.svg`: header banner, self-contained SVG, system fonts only.
- `assets/divider-light.svg`, `assets/divider-dark.svg`: matching divider. The divider images use an empty `alt` on purpose: they are decoration, and an empty alt keeps screen readers quiet. Both SVGs are also marked `aria-hidden`.
- New `README.md`: header, two tracks, what I've built, selected open source, how I work, stack, writing, connect.
- `README-CLAIMS.md`, `README-OPEN-QUESTIONS.md`, and this file.

## Not changed

- `.github/workflows/main.yml` (DevCard action), `.github/dependabot.yml`, `devcard.svg`, `devcard.png`, `.whitesource`. See open questions.

## Not added

- Weekly RSS refresh Action: the site could not be reached from this workspace to confirm a feed exists.
