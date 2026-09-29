# README claims map

Every sentence in `README.md` and the fact it rests on. Fact IDs F1–F11 come from the prompt's FACT SHEET. V1 and V2 are facts I verified by reading the public repos on 2026-09-29 (shallow clones of `agemon` and `qrgen`).

Where a sentence is a light paraphrase or elaboration of a fact rather than a direct restatement, the note column says so, so you can veto it.

## Banner (`assets/banner-*.svg`)

| Text | Fact | Note |
| --- | --- | --- |
| Korak Kurani | F1 | |
| Team Lead & AI platform architect | F2, F3 | "AI platform architect" is the wording from your manual bio step |
| Oracom Intelligence · Nishan Systems · Berlin | F2, F6, F1 | |
| `$ whoami` | none | Decorative terminal prompt, no claim |

## Intro

| Sentence | Fact | Note |
| --- | --- | --- |
| I lead engineering at Oracom Intelligence and run my own studio, Nishan Systems. | F2, F4, F6 | |
| I'm based in Berlin. | F1 | |
| I care about systems thinking, developer experience, and teams that don't burn out. | F11 | |

## Two tracks

| Sentence | Fact | Note |
| --- | --- | --- |
| Leading engineering at Oracom Intelligence | F2, F4 | Column heading |
| Building Nishan Systems | F6 | Column heading |
| I lead five developers and own architecture, people management and product decisions. | F4 | Seniority mix ("mostly mid-level") left out on purpose |
| I report to the CEO and set the roadmap with them. | F4 | |
| A Berlin studio for software, brand and marketing, founded in September 2026. | F6 | Sole-proprietorship status and the Kurdish meaning of "Nishan" left out |
| Morika, a digital loyalty stamp-card product for local merchants in DACH, is in development. | F7 | No pricing, competitors, MVP date or financials |
| ki.oracom.de (link) | F3 | See open question 1 |
| nishansystems.de (link) | F6 | |

## What I've built

| Sentence | Fact | Note |
| --- | --- | --- |
| I joined Oracom when it was a call center. | F3 | |
| I was a principal architect and hands-on builder of its AI platform, which is in its pre-sales phase. | F3 | |
| Agent flow builder. Defines how the AI handles specific situations. Built, then refactored. | F5 (bullet 1) | |
| Device delivery pipeline. Intake, registration, connection and remote start for on-site AI assistant devices. Major refactor. | F5 (bullet 2) | I dropped "encrypted" to stay clear of security architecture detail |
| Door-access integration. Connects a physical door-access system to the assistant through a Raspberry Pi, with QR scanning and employee-list checks. | F5 (bullet 3) | Dropped "over a secure channel" for the same reason. Your role (built vs led) is unstated, see open question 2 |
| Document-to-RAG pipeline. Document upload, embedding and RAG. I designed it, a teammate built it. | F5 (bullet 4) | |
| Infrastructure rebuild (in progress). Toward zero downtime, autoscaling and continuous delivery. | F5 (bullet 5) | Labelled in progress |

## Selected open source

| Sentence | Fact | Note |
| --- | --- | --- |
| agemon bootstraps an AI coding-agent environment in a repository and cleanly reverses it. | F8, V1 | |
| TypeScript, MIT, tested, with a dry-run mode. | F8, V1 | V1: `src/` is TypeScript, `LICENSE` and `package.json` say MIT, `test/` exists, `--dry-run` is in the CLI |
| Ubuntu only today. | V1 | agemon's README lists Ubuntu as the supported platform |
| Install and usage (link to `#install`) | V1 | The README has an `## Install` heading |
| qrgen is a free, ad-free QR code generator built with Vue. | F8, V2 | V2: repo description says free, simple and ad-free; `package.json` keywords include vue |

## How I work

| Sentence | Fact | Note |
| --- | --- | --- |
| Systems first. I look at how the parts interact before I optimise one of them. | F11 | Elaboration of "systems thinking" |
| Developer experience is a feature. Friction costs the team every day. | F11 | Elaboration of "developer experience" |
| People first. I coach daily and protect the team from burnout. | F4, F11 | |
| Teach the tools. Nuxt and Tailwind, Git, MCP, agentic AI, RAG, embeddings. | F4 | |

## Stack

| Group | Items | Fact |
| --- | --- | --- |
| Daily | TypeScript, Vue, Nuxt, Tailwind, Node.js, NestJS, PostgreSQL | F10 |
| Regularly | AWS, Docker, CI/CD, Cloudflare | F10 |
| AI work | RAG, embeddings / vector DBs, agentic systems, Ollama, MCP | F10 |
| Homelab | Coolify, Linux, Home Assistant | F10 |

No Ruby, Python, JavaScript, Astro or Git badges. The old README's Ruby badge is gone per F10.

## Writing

| Sentence | Fact | Note |
| --- | --- | --- |
| 30 Jun 2026: Building an AI-Powered Second Brain: Obsidian + Syncthing + Tailscale + Ollama | F9 | |
| 30 Apr 2026: The Invisible Burn: Why DX Is Not Optional | F9 | |
| 14 Mar 2026: The Three-Layer Fortress: Private Cloud with Coolify, Directus and Cloudflare | F9 | |

## Connect

| Sentence | Fact | Note |
| --- | --- | --- |
| Website: korak-kurani.com | F1 | |
| LinkedIn: Korak Kurani | prompt, structure item 8 | URL given in the prompt |
| Studio: Nishan Systems | F6 | |
