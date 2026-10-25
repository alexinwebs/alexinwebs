<h1 align="center">Hey, I'm Abbas Ansari 👋</h1>

<h3 align="center">Backend & Full-Stack Engineer</h3>

<p align="center">
  I build secure, well-tested web applications with TypeScript, Node.js, React, and PostgreSQL,<br/>
  and integrate AI where it adds real value, with human oversight.
</p>

<p align="center">
  📍 Ghaziabad, Uttar Pradesh, India · 🎓 B.Tech Computer Science, graduating 2027<br/>
  💼 Open to backend / full-stack internships and entry-level roles
</p>

<p align="center">
  <a href="https://alexinwebs.site"><img src="https://img.shields.io/badge/Portfolio-Explore-58A6FF?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/alexinwebs"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/></a>
  <a href="mailto:alexinwebs@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## About me

I'm a Computer Science undergraduate focused on backend and full-stack development. My work covers secure authentication, background processing, database design, automated testing, and deployment.

- **Backend:** REST APIs, request validation, background jobs, database architecture
- **Security:** OAuth 2.0, RBAC, revocable sessions, TOTP 2FA, encrypted tokens
- **Practical AI:** LLM integrations with structured validation and human-in-the-loop control
- **Quality:** unit, integration, and browser-based end-to-end tests
- **Delivery:** Docker Compose, GitHub Actions CI, HTTPS deployments

---

## Featured Projects

### 🗂️ PaperVault: College Question-Paper Archive

[![Live](https://img.shields.io/badge/Live-papervault.duckdns.org-2ea44f?style=flat-square&logo=googlechrome&logoColor=white)](https://papervault.duckdns.org)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/alexinwebs/papervault)

A deployed, moderated archive for discovering and organizing college question papers.

- Hierarchical browsing, paginated search, PDF-text search, and multi-branch paper listings
- Local PDF text extraction and OCR with unpdf, Poppler, Tesseract, and Sharp, with processing limits, timeouts, and a manual-entry fallback
- ClamAV file scanning and duplicate detection using file hashes and extracted text
- College-scoped RBAC, revocable sessions, bcrypt, administrator TOTP 2FA, and Redis rate limiting
- GitHub Actions for automated tests, dependency audits, image builds, and CodeQL
- Docker Compose deployment behind Caddy HTTPS

**Stack:** Next.js · React · TypeScript · PostgreSQL · Prisma · Redis · Tesseract · Poppler · Sharp · ClamAV · Docker Compose

---

### ✉️ MailPilot: Self-Hosted AI Email Assistant for Gmail

[![Source](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/alexinwebs/mailpilot-ai)

A solo-built, MIT-licensed assistant that helps users understand their inbox, spot emails that need replies, and draft responses, while keeping the user in control of sending.

- Gmail sync via Google OAuth 2.0 and the Gmail API
- Thread reconstruction, message classification, and reply-needed detection
- LLM reply drafting and critique, validated with Zod and gated by a deterministic policy engine
- The model never sends email directly; sending is designed to be idempotent
- 25 REST endpoints, 15 Prisma models, a nine-route React dashboard, and six LLM provider integrations
- Redis/BullMQ background processing and AES-256-GCM encrypted OAuth tokens
- Verified on a live Render deployment

**Stack:** React · TypeScript · Vite · Node.js · Fastify · PostgreSQL · Prisma · Zod · Redis · BullMQ · Docker Compose

---

### 🚗 VIBE: Driver-First Ride-Hailing Prototype

[![Source](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/alexinwebs/vibe)
![Prototype](https://img.shields.io/badge/Status-Prototype-orange?style=flat-square)

A prototype built around driver workflows: React Native (Expo) rider and driver apps, a Fastify API in a pnpm monorepo, shared TypeScript contracts via `@vibe/types`, a full ride lifecycle, and server-side fare and earnings calculation. Uses in-memory storage and is not deployed.

**Stack:** React Native · Expo · TypeScript · Node.js · Fastify · pnpm Workspaces

---

## Technical Skills

**Languages:** TypeScript · JavaScript · SQL · HTML · CSS

**Backend & Frameworks:** Node.js · Fastify · Next.js · React · React Native · Tailwind CSS · REST APIs · Zod · BullMQ

**Databases:** PostgreSQL · Prisma · Redis

**Security & Auth:** OAuth 2.0 · RBAC · TOTP 2FA · bcrypt · Encrypted OAuth Tokens

**Testing & DevOps:** Vitest · Playwright · Docker · Docker Compose · GitHub Actions · Caddy · Render · Git · Postman

**Familiar with:** Express.js · MongoDB · Mongoose · JWT · SQLite · Core Java

---

## How I Use AI

I use Cursor, Claude, ChatGPT, and Gemini for planning, implementation, debugging, and testing. I own the architecture, review and understand the code, and validate behavior through tests and deployment checks. AI speeds me up, but it doesn't replace understanding the system.

---

## Let's Connect

I'm looking for backend / full-stack internship and entry-level opportunities. Reach me on [LinkedIn](https://www.linkedin.com/in/alexinwebs), via [email](mailto:alexinwebs@gmail.com), or on my [portfolio](https://alexinwebs.site).

<p align="center"><i>Understand the system. Engineer the solution. Ship useful software.</i></p>
