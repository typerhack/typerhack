# Daniel Dolatabadi

**Senior Full-Stack Developer — React · Next.js · Node.js · TypeScript**

Tehran, Iran (open to relocation) · daniel.dolatabadi@gmail.com · +44 7947 166910
[daniel-dolatabadi.vercel.app](https://daniel-dolatabadi.vercel.app/) · [linkedin.com/in/danieldolatabadi](https://linkedin.com/in/danieldolatabadi) · [github.com/typerhack](https://github.com/typerhack)

---

## Summary

Full-stack developer with 6+ years building and operating production web applications end to end, from data models and APIs to deployment and incident response. Recent work centers on AI-native systems and production hardening: a CRM whose autonomous research agent is walled off from customer data, a clinic platform taken from audit to launch readiness, and an open-source build queue for AI coding agents. MBA background; used to owning a product surface rather than a ticket queue.

---

## Experience

### Independent Full-Stack Developer — Contract
**December 2025 – Present**

*MIU (Market Intelligence Unit)* — multi-branch CRM plus an autonomous market-research agent, live in production for a confidential client; demo available.

- Sandboxed the open-source Hermes agent in a hardened container with no database access and a scoped API key; only a human can promote its findings into the CRM
- Enforced branch data isolation at the repository layer, requiring cross-branch and missing-permission security tests on every endpoint; 4,000+ automated tests overall
- Paced the agent against the AI subscription's weekly allowance, holding work when it is spent, so research runs continuously within a fixed budget
- Added passkey and two-factor sign-in, and replaced polling, the product's largest source of requests, with authorized WebSocket channels

*Clinic Manager Suite* — multi-clinic SaaS that screens aesthetic-treatment patients before booking; Laravel, MySQL, Redis, React.

- Audited the half-built product for production readiness and logged 380+ findings; the audit's depth won the follow-on contract to fix them, with 400+ closed so far
- Encrypted patient records and files at rest while keeping phone and ID lookups searchable, and walled the platform admin off from patient data
- Built the missing administration layer: platform admin panel, subscription billing, clinic questionnaire authoring, and SMS and Telegram error alerts

*Signal Before Noise* — delivered a 4-locale publishing platform with automatic RTL/LTR from zero to production in **9 days** ([signalb4noise.com](https://signalb4noise.com)).

### Senior Full-Stack Developer — Ecom Edge Innovators LLC
**July 2024 – November 2025**

- Cut page load times ~**30%** through code splitting, lazy loading, rendering-strategy tuning, and caching
- Built a drag-and-drop CMS page builder with 37 section types that moved routine content changes from developer tickets to client self-service
- Designed REST APIs and MongoDB schemas for two production applications, with indexes and aggregation pipelines behind search and catalogs
- Built authentication end to end, giving customers and staff controlled access: refresh-token rotation, Google OAuth, OTP, reCAPTCHA v3, and granular RBAC
- Integrated Stripe checkout with webhook-driven order automation, a coupon engine, and a 6-tier spend-based loyalty program
- Patched production against two critical CVEs in React Server Components and MongoDB; wrote 20+ pages of handover docs
- Shipped [athenatelecom.ae](https://athenatelecom.ae) for a Dubai satellite communications firm and [glph.ca](https://glph.ca), MERN e-commerce for a Canadian print manufacturer

### Front-End Developer — Hybevo
**March 2020 – September 2024**

- Raised Google PageSpeed from **46 to 97** through systematic performance work
- Built the reusable component architecture behind the company's production front ends
- Integrated REST APIs and shared application state; owned cross-browser and responsive behavior

---

## Selected Projects

**mulebox** — [github.com/typerhack/mulebox](https://github.com/typerhack/mulebox) · Python, React · open source, on PyPI
Sends AI coding agents' builds and tests to Linux machines through one shared queue, so several agents can verify work without freezing the laptop. Live dashboard, GitHub Actions runners in the same queue, isolated containers per job; 1,800+ tests, in daily use on client projects.

**Zyberis** — [zyberis.com](https://zyberis.com) · Next.js, TypeScript, MongoDB · personal project, in production
Media platform operated by an autonomous AI agent that authors, enriches, and publishes through a token-authenticated API with no database credentials. Content lives in MongoDB, so publishing needs no rebuild; cookieless analytics with live SSE and nightly rollups.

**AI SEO & Marketing Assistant** — Next.js, Playwright · personal project, in development
Multi-provider LLM layer across five providers with automatic failover on rate limits and persistent conversation memory; Playwright crawler with live SSE progress.

---

## Technical Skills

| | |
|---|---|
| **Languages** | TypeScript, JavaScript, Python, PHP, Shell |
| **Frontend** | React 19, Next.js (App Router), Tailwind, Redux Toolkit, SSR/SSG/ISR, RTL interfaces |
| **Backend** | Node.js, Express, Laravel, REST API design, WebSockets, Server-Sent Events, job queues |
| **Data** | MongoDB + Mongoose, MySQL, Redis, data migration, encryption at rest |
| **Security & AI** | JWT/OAuth/RBAC, passkeys and 2FA, agent sandboxing, multi-provider LLM integration |
| **Quality** | Vitest, Playwright, PHPUnit, pytest, GitHub Actions, security audits, Figma-to-code |
| **Infrastructure** | Docker Compose, Ubuntu VPS, PM2, Nginx, Cloudflare, Fail2ban, Stripe |

---

## Education

**MBA, Marketing** — Tehran Business School, 2020–2022
**M.Arch** — Pars University of Art and Architecture, 2016–2018 · thesis: applying AI to BIM workflows
**Bachelor's, Industrial Management** — Shahrood University of Technology, 2007–2011

---

English (professional working proficiency) · Persian (native)
Available immediately. Requires visa sponsorship for relocation.
