<p align="center">
  <a href="https://alexuswingz.github.io"><img src="assets/header.svg" alt="Alexus Karl Joaquin — Senior Full Stack Lead Engineer" width="100%"></a>
</p>

<p align="center">
  <a href="https://alexuswingz.github.io"><img src="https://img.shields.io/badge/Portfolio_%26_live_demos-alexuswingz.github.io-0b0d0c?style=for-the-badge&logo=googlechrome&logoColor=8FE6AE" alt="Portfolio and live demos"></a>
  <a href="https://apps.apple.com/app/id6789244062"><img src="https://img.shields.io/badge/App_Store-Cashn't-0D96F6?style=for-the-badge&logo=apple&logoColor=white" alt="Cashn't on the App Store"></a>
  <a href="https://alexuswingz.github.io/assets/Alexus_Karl_Joaquin_CV.pdf"><img src="https://img.shields.io/badge/CV-PDF-8FE6AE?style=for-the-badge&logo=readdotcv&logoColor=0b0d0c" alt="CV"></a>
  <a href="mailto:alexuskarljoaquin@gmail.com"><img src="https://img.shields.io/badge/Email-alexuskarljoaquin%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

Eight years of full-stack engineering, four of them leading five-engineer teams, and a habit of shipping the whole thing myself: product design, API, infrastructure, security, App Store review. Twice trusted to architect financing platforms from scratch. Twice led an engineering organization's move to AI-native development.

Most of my work lives in private repositories. Instead of reading about it, **[try the real app bundles in your browser](https://alexuswingz.github.io)**, or buy the one on the App Store.

<br>

## What I bring

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🚀 Full product ownership, proven publicly</h3>
      Cashn't is a <b>paid</b> budget-tracking app live on the Apple App Store, built entirely solo: product design, AI coach, backend API, privacy compliance and App Store review. Passed review on the first submission.
    </td>
    <td width="50%" valign="top">
      <h3>✨ AI transformation leader, not just a user</h3>
      Introduced MCP, Claude Code and Cursor to entire engineering orgs, wrote the adoption standards and trained the engineers. Teams hiring for AI-readiness get someone who has already led that transition twice.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏗️ Builds from zero, at production quality</h3>
      Twice trusted to architect financing platforms from scratch. Systems handling real money, delivered with high-availability AWS infrastructure, observability and automated pipelines.
    </td>
    <td width="50%" valign="top">
      <h3>🤝 Multiplies teams</h3>
      Led and mentored 5-engineer teams at three consecutive companies, running disciplined Agile delivery while raising the bar through code review, documentation culture and hands-on coaching.
    </td>
  </tr>
</table>

<br>

## Featured work

Eight products, every one designed, built, deployed and operated by me alone. The portfolio runs the real builds in your browser.

<br>

### <img src="assets/cashnt-icon.png" width="30" align="top"> &nbsp;Cashn't &nbsp;·&nbsp; <sub>Paid iOS app, live on the App Store</sub>

> A budget tracker that gives you one honest number: **what is safe to spend today**. With an AI money coach built from your real numbers.

<p align="center">
  <img src="assets/cashnt-1.webp" width="19%" alt="Cashn't home">&nbsp;
  <img src="assets/cashnt-2.webp" width="19%" alt="Cashn't spend">&nbsp;
  <img src="assets/cashnt-3.webp" width="19%" alt="Cashn't goals">&nbsp;
  <img src="assets/cashnt-4.webp" width="19%" alt="Cashn't trips">
</p>

- **"Safe to spend today" engine** computes one daily number from balances, bills, paydays and savings goals.
- **AI money coach**: ask "can I afford this?" in plain language and get a plan generated from your actual financial data. Production LLM integration, not a demo.
- Net worth across cash, banks, e-wallets, investments and crypto; recurring bills and payday detection; envelope-style trip budgets; group pots with automatic who-owes-who settlement.
- **Privacy as a feature**: local-first guest mode, Face ID lock, privacy masking, in-app account deletion. Custom sync API on Railway with Apple / Google / email sign-in.

`React 19` `TypeScript` `Vite` `Capacitor 8` `Firebase Auth` `Express` `PostgreSQL` `Railway` `Recharts` `PWA` `Xcode / App Store Connect`

**[▶ Try the live demo](https://alexuswingz.github.io/#projects)** &nbsp;·&nbsp; **[View on the App Store](https://apps.apple.com/app/id6789244062)**

<br>

### <img src="assets/loca-icon.svg" width="30" align="top"> &nbsp;LOCA &nbsp;·&nbsp; <sub>Hyperlocal social app · Web + iOS · Live on Railway</sub>

> Your stuff. Your people. Nearby. Neighbors give things away, ask for things, borrow things and offer help.

<p align="center">
  <img src="assets/loca-1.webp" width="19%" alt="LOCA home">&nbsp;
  <img src="assets/loca-2.webp" width="19%" alt="LOCA thread">&nbsp;
  <img src="assets/loca-3.webp" width="19%" alt="LOCA messages">&nbsp;
  <img src="assets/loca-4.webp" width="19%" alt="LOCA profile">
</p>

- **pnpm monorepo**: React web app, NestJS + Prisma API, shared packages. 34-table schema, 18 migrations, 17 end-to-end test suites.
- **Auth end to end**: email verification and reset, Google and Apple via Firebase, cookie sessions for web and token sessions for native, rate-limited and CSRF-checked by origin.
- Real domain logic: give / ask / borrow / help posts, offers and acceptance, two-sided borrow handoff and returns, messaging with unread state, saved searches and a rules-based matching engine.
- **Live feed over server-sent events**, APNs push on local time slots, message moderation in English and Tagalog plus OpenAI moderation. CSP, HSTS, per-client rate limits, media retention sweeps.
- Deployed on Railway: Caddy serves the web app and proxies `/api` to a private API over the internal network. Postgres and object storage never get a public address.

`React` `Vite` `NestJS` `Prisma` `PostgreSQL 18` `Capacitor (iOS)` `Firebase` `APNs` `S3` `Apple Maps` `OpenAI` `Resend` `Caddy` `Railway`

**[↗ Open the live app](https://web-production-202cdf.up.railway.app/)**

<br>

### <img src="assets/studyverse-icon.png" width="30" align="top"> &nbsp;Studyverse &nbsp;·&nbsp; <sub>Student productivity &amp; social learning · Mobile-first</sub>

> Schedules, reviewers, flashcards and a class community for Filipino students, with AI that turns photos into timetables and notes into reviewers.

<p align="center">
  <img src="assets/studyverse-1.webp" width="19%" alt="Studyverse home">&nbsp;
  <img src="assets/studyverse-2.webp" width="19%" alt="Studyverse schedule">&nbsp;
  <img src="assets/studyverse-3.webp" width="19%" alt="Studyverse study">&nbsp;
  <img src="assets/studyverse-4.webp" width="19%" alt="Studyverse community">
</p>

- **Brand identity and design system from scratch**: a scripted SVG pipeline renders every logo, icon and favicon from geometry, with light and dark themes and WCAG AA contrast on every token pair.
- **AI in production**: photograph a timetable and it becomes your schedule; photograph notes and get a saved reviewer with a flashcard deck.
- Data layer built for a native feel: stale-while-revalidate cache, prefetched tab roots so no screen shows a skeleton, WebSocket client with reconnect, backoff and heartbeat.
- Runs fully on in-memory mocks without a server, and against the real API with a single env variable.

`React 19` `TypeScript (strict)` `Vite 8` `Tailwind CSS 4` `React Router 7` `Zustand` `Motion` `Capacitor 8` `Node` `PostgreSQL` `WebSockets` `OpenAI` `Railway`

**[▶ Try the live demo](https://alexuswingz.github.io/#projects)**

<br>

### <img src="assets/ghostnt-icon.png" width="30" align="top"> &nbsp;Ghostn't &nbsp;·&nbsp; <sub>Dating app · iOS · API live on Railway</sub>

> The dating app where ghosting is impossible. One hour a night, answers before faces, then you both choose: **hold or cut**.

<p align="center">
  <img src="assets/ghostnt-1.webp" width="19%" alt="Ghostn't room">&nbsp;
  <img src="assets/ghostnt-2.webp" width="19%" alt="Ghostn't chat">&nbsp;
  <img src="assets/ghostnt-3.webp" width="19%" alt="Ghostn't ticket">&nbsp;
  <img src="assets/ghostnt-4.webp" width="19%" alt="Ghostn't lines">
</p>

- **A product with real rules**: the room opens for one hour a night, one answered question is your ticket in, you pick people by their answers, and held lines climb a reveal ladder: voices, first names, then faces. Miss two nights and the line flatlines.
- **Live chat over WebSockets** with heartbeat reaping, server-authoritative countdowns with clock skew measured on every API call, and in-app calls with native CallKit integration.
- **Backend built for cost and speed**: one pg pool with statement timeouts, every endpoint a single round-trip (CTEs, lateral joins, no N+1), keyset pagination, partial indexes, advisory locks to serialize competing line-opens.
- Route-level code splitting (1–5 KB per screen), sockets only while a line is alive, reduced-motion support. Shipped through the same headless App Store pipeline as Cashn't.

`React 19` `TypeScript` `Vite` `Capacitor 8` `Express 5` `PostgreSQL` `WebSockets` `Firebase Auth` `CallKit (Swift)` `Railway` `App Store Connect`

**[See it in the portfolio](https://alexuswingz.github.io/#projects)** &nbsp;·&nbsp; iOS build in App Store review

<br>

### <img src="assets/proof-icon.svg" width="30" align="top"> &nbsp;Cinemi &nbsp;·&nbsp; <sub>AI photo studio · Design system + product</sub>

> A mobile-first AI image studio driven by photography slash-commands. Type `/85mm` or `/filmgrain`, compare before and after, retouch faces on-device.

<p align="center">
  <img src="assets/proof-1.webp" width="19%" alt="Cinemi home">&nbsp;
  <img src="assets/proof-2.webp" width="19%" alt="Cinemi create">&nbsp;
  <img src="assets/proof-3.webp" width="19%" alt="Cinemi styles">&nbsp;
  <img src="assets/proof-4.webp" width="19%" alt="Cinemi images">
</p>

- **"Editorial After Dark" design system**: 60+ components, semantic tokens, dark and light themes, motion and safe-area tokens. The reference page reads token values live from the CSS, so docs cannot drift from code.
- **On-device face retouching** with MediaPipe's face landmarker in WebAssembly. Photos never leave the phone.
- Slash-command prompt composer with searchable catalogue, prompt preview and compile step; before/after compare slider; monetization components designed in from day one.

`React 19` `TypeScript 6` `Vite 8` `Tailwind CSS 4` `Radix UI` `CVA` `MediaPipe (WASM)` `shadcn/ui` `Capacitor-ready`

**[▶ Try the live demo](https://alexuswingz.github.io/#projects)** &nbsp;·&nbsp; **[Design-system reference](https://alexuswingz.github.io/demos/proof/)**

<br>

### <img src="assets/jobfinder-icon.svg" width="30" align="top"> &nbsp;Job Finder &nbsp;·&nbsp; <sub>CV-matched job feed · FastAPI + React</sub>

> One feed that aggregates LinkedIn, Indeed, JobStreet and Google Jobs, scores every listing against your CV and explains why it matched.

<p align="center">
  <img src="assets/jobfinder-1.webp" width="19%" alt="Job Finder feed">&nbsp;
  <img src="assets/jobfinder-2.webp" width="19%" alt="Job Finder detail">&nbsp;
  <img src="assets/jobfinder-3.webp" width="19%" alt="Job Finder saved">&nbsp;
  <img src="assets/jobfinder-4.webp" width="19%" alt="Job Finder profile">
</p>

- **Scoring engine** gives every job a 0–100 match: skill overlap, title relevance, recency, location and remote fit, with a seniority adjustment. Matched skills shown on every card.
- Concurrent fan-out to four job boards with free direct scrapers first and RapidAPI fallbacks only when a direct fetch returns nothing. Deduplication across sources and a 6-hour cache.
- Upload a `.docx` CV and the matching profile is re-extracted automatically. Same codebase runs as web and Capacitor mobile app.

`Python` `FastAPI` `httpx` `SQLite / PostgreSQL` `React` `TypeScript` `Tailwind CSS 4` `TanStack Query` `Railway`

**[↗ Open the app](https://alexuswingz.github.io/demos/jobfinder/feed)**

<br>

### <img src="assets/matteosbrew-icon.png" width="30" align="top"> &nbsp;Matteo's Brew &nbsp;·&nbsp; <sub>Coffee shop website + digital menu · Client work</sub>

> A warm, motion-rich website for a neighbourhood coffee shop, with a searchable digital menu customers open from a QR code at the counter.

<p align="center">
  <img src="assets/matteosbrew-1.webp" width="39%" alt="Matteo's Brew home">&nbsp;
  <img src="assets/matteosbrew-2.webp" width="39%" alt="Matteo's Brew digital menu">&nbsp;
  <img src="assets/matteosbrew-m1.webp" width="17%" alt="Matteo's Brew on a phone">
</p>

- Full-bleed video hero and animated sections for the story, menu preview, events, packages and location, all tuned for phones first.
- **Digital menu**: 26 drinks across six categories with instant search and category filters, plus a QR-code section that drops customers straight into the menu from the table.
- Ships as a static build, so hosting costs nothing and it loads instantly.

`React 19` `Vite 7` `Tailwind CSS 4` `Framer Motion` `React Router 7` `QR codes` `Static hosting`

**[↗ Open the live site](https://alexuswingz.github.io/demos/matteosbrew/)** &nbsp;·&nbsp; **[Source](https://github.com/alexuswingz/MatteosBrew)**

<br>

### <img src="assets/lawsystem-icon.png" width="30" align="top"> &nbsp;Alexus Legal AI &nbsp;·&nbsp; <sub>AI legal assistant · Philippine law · Next.js</sub>

> A conversational AI legal companion for Filipinos: explains Philippine law in plain language, relates it to your situation and ends with concrete next steps.

<p align="center">
  <img src="assets/lawsystem-desktop.webp" width="56%" alt="Alexus Legal AI on desktop">&nbsp;
  <img src="assets/lawsystem-1.webp" width="17%" alt="Alexus Legal AI welcome">&nbsp;
  <img src="assets/lawsystem-2.webp" width="17%" alt="Alexus Legal AI conversation">
</p>

- **Streaming chat** on the Next.js App Router with a system prompt engineered for empathy: acknowledge the situation, tie answers to the specific case, explain statutes simply, always finish with actionable steps.
- Covers the Constitution, Civil Code, Revised Penal Code, Labor Code, Family Code, property, tax, corporate and procedural law, with a clear "not legal advice" boundary.
- Per-user conversation history in PostgreSQL with an auto-initialised schema, image upload for document analysis, and a PWA manifest so it installs like a native app.

`Next.js 14` `TypeScript` `Tailwind CSS` `OpenAI` `PostgreSQL` `PWA` `Railway`

**[See it in the portfolio](https://alexuswingz.github.io/#projects)** &nbsp;·&nbsp; **[Source](https://github.com/alexuswingz/LawSystem)**

<br>

### <img src="assets/bananas-logo.png" width="30" align="top"> &nbsp;1000 Bananas Platform &nbsp;·&nbsp; <sub>Company project · The Jungle Group / TPS Nutrients · Built solo</sub>

> The operations platform behind a multi-account Amazon business: demand forecasting, inventory and shipments, and a keyword "battlefield" command centre with an automated bid engine.

<table>
  <tr>
    <td align="center"><b>252 + 230</b><br><sub>API routes</sub></td>
    <td align="center"><b>44 + 72</b><br><sub>pages</sub></td>
    <td align="center"><b>~97</b><br><sub>tables</sub></td>
    <td align="center"><b>450</b><br><sub>typed API client methods</sub></td>
    <td align="center"><b>1</b><br><sub>MCP server for AI assistants</sub></td>
  </tr>
</table>

- **N-GOOS**: Next.js 14 + Django REST platform for forecasting, inventory, shipments and new-product development. JWT auth and tenant-scoped realtime over Django Channels.
- **Battlefield Command**: FastAPI + Next.js 16 command centre for search-term domination. A bid engine with editable strategy parameters, inventory-aware ad throttling, placement policy and cron services.
- **Amazon integrations**: SP-API catalog sync (fixed a silent gap that dropped ~346 merchant-fulfilled listings), Ads API reporting, multi-seller-account isolation.
- An **MCP server** that exposes platform capabilities to AI assistants, plus an Anthropic-powered tool builder with schema introspection and a hardened read-only SQL runner.

`Next.js 14 / 16` `React` `TypeScript` `Django 5 + DRF` `FastAPI` `PostgreSQL` `Django Channels` `Amazon SP-API` `Amazon Ads API` `MCP` `Sentry` `Railway`

Proprietary, so no public demo. Happy to walk through the live system on a call.

<br>

## Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django">
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=flat-square&logo=rubyonrails&logoColor=white" alt="Ruby on Rails">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <br>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" alt="Elasticsearch">
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white" alt="Railway">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana">
  <img src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white" alt="Sentry">
  <br>
  <img src="https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white" alt="iOS">
  <img src="https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white" alt="Capacitor">
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code">
  <img src="https://img.shields.io/badge/MCP-0b0d0c?style=flat-square&logo=modelcontextprotocol&logoColor=8FE6AE" alt="Model Context Protocol">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI">
</p>

| | |
|---|---|
| **Backend** | Python (Flask, Django, FastAPI), Ruby on Rails, Node (NestJS, Express), REST API design |
| **Frontend** | React, Next.js, TypeScript, Tailwind CSS, design systems, Angular |
| **Mobile** | iOS via Capacitor, App Store publishing and review, release management |
| **Data** | PostgreSQL, MySQL, MongoDB, Elasticsearch, Prisma |
| **Cloud & DevOps** | AWS (EC2, S3, RDS, CloudFront, ELB), Docker, GitHub Actions, Railway, Caddy |
| **AI** | LLM integration in production, Model Context Protocol servers, AI agents, Claude Code and Cursor adoption programs |
| **Observability** | Grafana, Sentry, alert-first incident handling |
| **Leadership** | Agile / Scrum, mentoring, code review culture, technical documentation (Notion) |

<br>

## Experience

| | Company | Role | Highlights |
|---|---|---|---|
| **2025 → now** | **Cloud Employee** | Senior Full Stack Engineer | Rails + React + PostgreSQL production apps. Pioneered the company's shift to AI-native engineering: MCP integrations, company-wide Claude Code and Cursor rollout, authored the AI-assisted development standards. Designed the Grafana + Sentry observability stack. |
| **2024 → 2025** | **Capital Source Group** | Senior Full Stack Lead Engineer | Designed, built and launched the core Financing System from scratch. Architected the AWS production environment (RDS, Elasticsearch, load balancers). Owned CI/CD end to end. Led a team of 5. |
| **2021 → 2024** | **Vertere Global Solutions** | Senior Full Stack Lead Engineer | Spearheaded financing systems through multiple major iterations. Full AWS stack, Selenium data pipelines, GitHub Actions CI/CD. Led and mentored a 5-member team. |
| **2018 → 2021** | **FurtherEdge Co.** | Software Engineer | Recruited on the strength of freelance work delivered as a second-year student. Angular + Python client apps, REST APIs, AWS hosting. Graduated BS Information Technology, Magna Cum Laude, while working. |

<br>

## Let's talk

Open to senior and lead full-stack roles, remote-first. Based in the Philippines.

<p>
  <a href="mailto:alexuskarljoaquin@gmail.com"><img src="https://img.shields.io/badge/alexuskarljoaquin%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://alexuswingz.github.io"><img src="https://img.shields.io/badge/alexuswingz.github.io-0b0d0c?style=for-the-badge&logo=googlechrome&logoColor=8FE6AE" alt="Portfolio"></a>
  <a href="https://alexuswingz.github.io/assets/Alexus_Karl_Joaquin_CV.pdf"><img src="https://img.shields.io/badge/Download_CV-8FE6AE?style=for-the-badge&logo=readdotcv&logoColor=0b0d0c" alt="CV"></a>
</p>

<sub>Most repositories here are private because they are commercial products or client work. The portfolio runs the real builds in your browser; source walkthroughs are available on request.</sub>
