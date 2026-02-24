# Daniel Dolatabadi

**Senior Full-Stack Developer | Node.js | React | TypeScript | AI/LLM Integration**

**Location:** Tehran, Iran (Open to Relocation)
**Email:** daniel.dolatabadi@gmail.com
**Phone:** +44 7947 166910 (WhatsApp available)
**Website:** [daniel-dolatabadi.vercel.app](https://daniel-dolatabadi.vercel.app/)
**LinkedIn:** [linkedin.com/in/danieldolatabadi](https://linkedin.com/in/danieldolatabadi) (500+ connections)
**GitHub:** [github.com/typerhack](https://github.com/typerhack)

---

## Professional Summary

Senior Full-Stack Developer with 5+ years of experience building production-grade applications with Node.js, React, Next.js, and TypeScript. Proven track record owning projects end-to-end — from backend API and database architecture through frontend delivery and production deployment.

Hands-on experience designing multi-provider AI/LLM integrations, including provider abstraction layers, prompt engineering, memory-aware conversational systems, and structured output parsing. Built complete authentication systems, real-time SSE streaming, payment integrations, and complex UI systems including a custom drag-and-drop CMS page builder.

MBA background informs a product mindset: building systems that solve real business problems, not just working code. Security-conscious — responded to critical CVEs in production. Available immediately for full-time remote or relocating positions.

---

## Technical Skills

| Category | Technologies |
|---|---|
| **Frontend** | React.js (v18/v19), Next.js (v15/v16 + Turbopack), TypeScript, JavaScript (ES6+), HTML5, CSS3 |
| **State Management** | Redux Toolkit (multi-slice: cart, auth, consent, config; Redux Persist, localStorage hydration), Context API |
| **Rendering** | SSR, SSG, ISR — applied per page type based on content freshness and performance requirements |
| **Styling & UI** | Tailwind CSS (v3/v4), shadcn/ui, CSS Modules, Framer Motion, Responsive Design, Dark Mode, RTL/LTR layouts |
| **CMS / Page Builder** | Custom drag-and-drop page builder (37 section types, @dnd-kit core/sortable/modifiers), dynamic component registry, Zod-validated section schemas, lazy-loaded editors, real-time unsaved change tracking |
| **Real-time & Async** | Server-Sent Events (SSE) — streaming progress, global connection registry, pause/resume/cancel patterns, heartbeat mechanism; node-cron (scheduled jobs) |
| **AI/LLM Integration** | Multi-provider abstraction (OpenRouter 200+ models, Google Gemini, Ollama, OpenAI, Anthropic), AIManager singleton + factory pattern, auto-fallback on rate limits, provider health monitoring, per-model usage tracking, 4-tier persistent conversation memory (history, preferences, context, knowledge), prompt engineering, structured JSON output parsing with multi-format fallback, circuit breaker pattern, chunked batch AI processing |
| **Web Automation** | Playwright (headless browser crawling, full DOM rendering, SEO data extraction, robots.txt compliance) |
| **Forms & Validation** | React Hook Form, Zod (frontend + API layer), express-validator |
| **UI Libraries** | dnd-kit, TipTap (rich text with extensions), Quill, Recharts (data dashboards), Swiper, Framer Motion, React Dropzone, React Hot Toast, shadcn/ui, Crisp Chat |
| **Auth & Security** | JWT (access + refresh token rotation, httpOnly Secure SameSite cookies), Google OAuth, OTP verification, bcrypt (10 salt rounds), reCAPTCHA v3, device tracking (multi-device sessions), RBAC with granular permissions, DOMPurify (XSS sanitization) |
| **Backend** | Node.js, TypeScript, Express.js (v5), Next.js API routes, MVC pattern, REST API design (40–65+ endpoints per project), rate limiting, pagination, full-text search, webhook handling |
| **Database** | MongoDB + Mongoose ODM (up to 44 models, text indexes, aggregation pipelines, TTL indexes, compound indexes, connection pooling), SQL fundamentals |
| **Payments** | Stripe (session-based checkout, webhook-driven order automation), coupon/discount system, tiered loyalty program (6 tiers, spend-based calculation) |
| **File Uploads & Media** | Multer (multipart form handling), Sharp (image processing, validation, resizing), media library with year/month organization |
| **Email** | Nodemailer + React Email templates, configurable SMTP (Zoho Mail, Gmail), transactional emails with audit logging |
| **External APIs** | Google Search Console API (OAuth2, query analytics), Google PageSpeed Insights API (Core Web Vitals), Google Drive API (backup/restore), Google Tag Manager (consent mode v2), Google Analytics, OpenRouter API, Google Gemini API, Ollama API |
| **SEO** | Dynamic meta tags (react-helmet-async), XML sitemap generation with caching, schema.org structured data, Open Graph + Twitter Card, canonical URLs |
| **Data Export** | ExcelJS (Excel export), PapaParse (CSV parsing/export) |
| **Logging** | Winston structured logging with daily file rotation (winston-daily-rotate-file) |
| **Performance** | Code splitting (Vite manual chunks), React.lazy + Suspense, Turbopack, bundle analysis, memory-optimized builds, database indexing |
| **Testing** | Jest, React Testing Library |
| **DevOps & Infrastructure** | PM2 (process management), Nginx (reverse proxy, security headers, SSL termination), Fail2Ban (brute-force protection), AppArmor, Let's Encrypt SSL (automated renewal), Ubuntu VPS, CI/CD, Security Incident Response |
| **Containerization** | Docker (custom images, Docker Compose, multi-container environments) — personal project experience |
| **Design Tools** | Figma (design-to-code implementation) |
| **Tools** | Git, Agile/Scrum, Code Review, Technical Documentation (20+ pages per project) |

---

## Professional Experience

### Senior Full-Stack Developer
**Ecom Edge Innovators LLC** | July 2024 - November 2025 | Full-time

Built and maintained production applications in a startup environment, owning features end-to-end from backend API design through frontend delivery and production deployment.

**Key Achievements:**

- Designed and built a **custom drag-and-drop CMS page builder** (37 section types, @dnd-kit) — enables non-technical clients to compose pages from a registry of pre-built, Zod-validated section components with real-time unsaved change tracking and lazy-loaded editors
- Designed and maintained **REST APIs** across two production applications — 30–44 endpoints per project covering authentication, product catalog, search, user management, media, and business logic
- Built **complete authentication systems** from scratch: JWT access + refresh token rotation, Google OAuth, OTP email verification, reCAPTCHA v3, bcrypt, device tracking, and role-based access control with granular permissions (owner/admin/editor/customer)
- Implemented **Redux Toolkit multi-slice state management** across complex applications: shopping cart with deduplication and localStorage persistence (Redux Persist), user auth state, cookie consent, and global config — with client-side hydration to prevent SSR mismatches
- Applied **SSR, SSG, and ISR strategically** per page type in Next.js — balancing freshness, SEO, and performance
- Built **real-time SSE streaming** for long-running operations (web crawling, PageSpeed analysis) — global connection registry, per-channel routing, heartbeat mechanism, pause/resume/cancel
- Designed **21–44 MongoDB models** per project with Mongoose ODM: text indexes for full-text search, aggregation pipelines for complex queries, TTL indexes for session expiration, compound indexes for query optimization
- Implemented **Stripe payment integration**: session-based checkout, webhook-driven order status automation, coupon/discount system with usage tracking, tiered loyalty program (6 tiers, spend-based automatic calculation)
- Built file upload and media management system using **Multer + Sharp**: image processing, validation, type enforcement, organized storage
- Integrated **Nodemailer** with configurable SMTP (Zoho Mail, Gmail) and React Email templates for transactional emails with audit logging
- Integrated **Google Drive API** (OAuth2) for automated database backup/restore with progress tracking and scheduling
- Managed **PM2 + Nginx + Fail2Ban + AppArmor + Let's Encrypt SSL** on Ubuntu VPS — production deployment, certificate auto-renewal, reverse proxy configuration, security hardening
- Reduced page load times by approximately **30%** through code splitting, lazy loading, Turbopack migration, and caching
- Responded to critical security incidents (CVE-2025-55182, CVE-2025-14847) — assessed exposure, patched production systems, implemented hardening measures
- Translated Figma designs into **pixel-perfect, accessible, responsive implementations** including RTL/LTR multilingual layouts
- Wrote **20+ pages of technical documentation** per project covering API patterns, auth system, deployment, backup system, and design system

**Projects Delivered:**

**Athena Telecom LLC** | [athenatelecom.ae](https://athenatelecom.ae)
Enterprise Next.js 16 application for a satellite communications company (Dubai, UAE). Built the custom drag-and-drop CMS page builder (37 section types, @dnd-kit), Redux Toolkit multi-slice state (cart, user, consent), full blog engine with Quill rich text editor, product/services/solutions catalog, unified full-text search, quote cart system, complete JWT auth (refresh token rotation, device tracking, reCAPTCHA v3, Google OAuth, OTP, RBAC), Google Drive backup integration, Nodemailer + React Email template system, Google Tag Manager with consent mode v2, PM2 + Nginx + Fail2Ban production deployment.

**Green Leaf Printing House** | [glph.ca](https://glph.ca)
Production e-commerce platform (MERN stack, monorepo) for a Canadian printing company. Backend: Express.js v5 with 27 route files, 38 controllers, 44 MongoDB models. Features: Stripe checkout + webhook-driven order status, tiered loyalty program (6 tiers, spend-based calculation), coupon system, Multer + Sharp file uploads, Nodemailer (Zoho Mail SMTP) transactional emails, advanced popup manager with analytics (views, clicks, email captures), XML sitemap with caching, PM2 + Nginx + Let's Encrypt SSL. Frontend: React 18 + Vite with TypeScript, Redux Toolkit + Redux Persist (cart/auth), React Hook Form + Zod, Framer Motion animations, Recharts data dashboards, TipTap rich text editor, Axios interceptors for token handling, Crisp Chat live support.

**Technologies:** React, Next.js, TypeScript, Node.js, Express.js, MongoDB, Mongoose, JWT, OAuth, Stripe, Multer, Sharp, Nodemailer, Redux Toolkit, Framer Motion, TipTap, Recharts, dnd-kit, SSR/SSG/ISR, SSE, REST APIs, PM2, Nginx, Let's Encrypt, Git

---

### Front-End Developer
**Hybevo** | March 2020 - September 2024 | 4 years 7 months | Full-time

Developed production front-end applications with focus on performance, scalability, and user experience.

**Key Achievements:**

- Improved Google PageSpeed score from **46 to 97** through systematic performance optimization, code splitting, and asset optimization
- Built scalable UI component architecture emphasizing reusability and maintainability
- Integrated REST APIs and implemented Context API for shared application state
- Collaborated closely with designers and backend developers to implement features accurately
- Enhanced cross-browser compatibility and responsive design across devices

**Technologies:** React, Next.js, TypeScript, JavaScript, Context API, REST APIs, HTML5, CSS3, Git

---

### Computational Design Instructor (Grasshopper)
**Pars University of Art and Architecture** | December 2017 - March 2020 | 2 years 4 months

- Taught Grasshopper (parametric/computational design) to architecture students
- Developed curriculum for visual programming and algorithmic thinking in architectural design

---

## Projects

**AI-Powered SEO & Marketing Assistant** | Next.js 15, Node.js, TypeScript, MongoDB, Playwright | Personal Project | In Development
Full-stack AI platform with 63 API routes, 18 MongoDB models, and 11 dashboard sections. Core: built a **multi-provider AI abstraction layer** from scratch — unified interface across OpenRouter (200+ models), Google Gemini, Ollama (local LLMs), OpenAI, and Anthropic. Implemented auto-fallback on rate limits, provider health monitoring, per-model usage tracking, and a 4-tier persistent conversation memory system (history, preferences, context, knowledge) injected into every prompt. Additional features: Playwright headless browser web crawling with real-time SSE progress streaming (pause/resume/cancel); Google Search Console API (OAuth2, query analytics, weekly AI reports via node-cron); Google PageSpeed Insights API (Core Web Vitals, desktop/mobile); AI-driven keyword categorization with chunked batch processing; structured JSON output parsing with multi-format fallback; circuit breaker error recovery pattern; Winston structured logging with daily file rotation. Available for local demonstration.

**Lonely Assistant for Obsidian** | TypeScript | Open Source
AI assistant plugin for Obsidian enabling chat with local Ollama or OpenAI-compatible servers. TypeScript, plugin architecture, and API integration.

**LAMP Install Script** | Shell
Automated development environment setup script for Ubuntu/WSL. DevOps and infrastructure automation.

---

## Education

**Master of Business Administration (MBA)** - Marketing
Tehran Business School | 2020 - 2022
*Focus on business operations and client-centric product development.*

**Master of Architecture (M.Arch.)**
Pars University of Art and Architecture | 2016 - 2018
*Thesis: "Application of AI with BIM for Architectural Design" — applied AI to optimize building information modeling processes.*

**Bachelor's Degree** - Industrial Management
Shahrood University of Technology | 2007 - 2011

---

## Certifications

| Certificate | Issuer | Date |
|---|---|---|
| HTML, CSS, and JavaScript for Web Developers | Coursera | March 2022 |

---

## Languages

- **English:** Professional working proficiency
- **Persian:** Native proficiency

---

## Additional Information

- Available for full-time remote or relocating positions (visa sponsorship required)
- Comfortable with remote, hybrid, or on-site arrangements
- Experienced with pair programming, code review, and agile practices
