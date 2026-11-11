# Daniel Dolatabadi

**Senior Full-Stack Developer — React · Next.js · Node.js · TypeScript**

I build and operate production web applications end to end, from data models and APIs to deployment and incident response. Lately that means AI-native systems and production hardening: walling autonomous agents off from customer data, taking half-built products from audit to launch, and building tooling that lets AI coding agents verify their own work.

[Portfolio](https://daniel-dolatabadi.vercel.app/) · [LinkedIn](https://linkedin.com/in/danieldolatabadi) · [Email](mailto:daniel.dolatabadi@gmail.com) · Open to relocation, available immediately

---

## What I'm working on

### MIU — Market Intelligence Unit
Multi-branch CRM plus an autonomous market-research agent, live in production for a confidential client (demo available).

- The research agent runs in a hardened container with **no database access** and a scoped API key; only a human can promote its findings into the CRM
- Branch data isolation enforced at the repository layer, with cross-branch and missing-permission security tests required on every endpoint — **4,000+ automated tests**
- Agent work is paced against the AI subscription's weekly allowance, so research runs continuously within a fixed budget
- Passkeys and two-factor sign-in; polling replaced with authorized WebSocket channels

### Clinic Manager Suite
Multi-clinic SaaS that screens aesthetic-treatment patients before booking. Laravel · MySQL · Redis · React.

- Production-readiness audit of a half-built product: **380+ findings**, which won the follow-on contract to fix them — **400+ closed** so far
- Patient records and files encrypted at rest while phone and ID lookups stay searchable; platform admin walled off from patient data
- Built the missing administration layer: admin panel, subscription billing, questionnaire authoring, SMS and Telegram error alerts

### [mulebox](https://github.com/typerhack/mulebox) · open source, on PyPI
Sends AI coding agents' builds and tests to Linux machines through one shared queue, so several agents can verify work without freezing the laptop.

- Live dashboard, GitHub Actions runners in the same queue, isolated containers per job
- **1,800+ tests**; in daily use on client projects

---

## Impact highlights

| | |
|---|---|
| **9 days** | Zero to production for [Signal Before Noise](https://signalb4noise.com), a 4-locale publishing platform with automatic RTL/LTR |
| **46 → 97** | Google PageSpeed score, through systematic performance work |
| **~30%** | Faster page loads via code splitting, lazy loading, rendering-strategy tuning, and caching |
| **37** | Section types in a drag-and-drop CMS page builder that moved content changes to client self-service |
| **2 CVEs** | Critical React Server Components and MongoDB vulnerabilities patched in production |

## Other projects

- **[Zyberis](https://zyberis.com)** — Media platform run by an autonomous AI agent that authors, enriches, and publishes through a token-authenticated API with no database credentials. Content lives in MongoDB, so publishing needs no rebuild; cookieless analytics with live SSE and nightly rollups.
- **[Signal Before Noise](https://signalb4noise.com)** — Multilingual Next.js publishing platform, 4 locales with automatic RTL/LTR, shipped in 9 days.
- **AI SEO & Marketing Assistant** *(in development)* — LLM layer across five providers with automatic failover on rate limits and persistent conversation memory; Playwright crawler with live SSE progress.
- **Lonely Assistant for Obsidian** — TypeScript plugin connecting Obsidian to local Ollama or OpenAI-compatible servers.

## Experience

- **Independent Full-Stack Developer** — Contract · Dec 2025 – present
- **Senior Full-Stack Developer** — Ecom Edge Innovators LLC · Jul 2024 – Nov 2025 — shipped [athenatelecom.ae](https://athenatelecom.ae) and [glph.ca](https://glph.ca); auth, Stripe checkout, loyalty program, CMS builder
- **Front-End Developer** — Hybevo · Mar 2020 – Sep 2024

MBA in Marketing — I think in business outcomes and prefer owning a product surface to working a ticket queue.

## Tech stack

**Languages** `TypeScript` `JavaScript` `Python` `PHP` `Shell`

**Frontend** `React 19` `Next.js (App Router)` `Tailwind CSS` `Redux Toolkit` `SSR/SSG/ISR` `RTL interfaces`

**Backend** `Node.js` `Express` `Laravel` `REST APIs` `WebSockets` `SSE` `Job queues`

**Data** `MongoDB` `Mongoose` `MySQL` `Redis` `Encryption at rest`

**Security & AI** `JWT` `OAuth` `RBAC` `Passkeys` `2FA` `Agent sandboxing` `Multi-provider LLMs`

**Quality** `Vitest` `Playwright` `PHPUnit` `pytest` `GitHub Actions` `Security audits`

**Infrastructure** `Docker Compose` `Ubuntu VPS` `PM2` `Nginx` `Cloudflare` `Fail2ban` `Stripe`
