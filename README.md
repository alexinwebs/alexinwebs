<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:58A6FF&height=180&section=header&text=Abbas%20Ansari&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=38" alt="Header" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=24&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=800&lines=AI-Assisted+Developer;Backend+%26+Full-Stack+Engineering;Building+Secure%2C+Real-World+Products;Practical+AI+%2B+Software+Engineering" alt="Animated developer introduction" />
</p>

<h3 align="center">AI-Assisted Developer | Backend & Full-Stack Engineering</h3>

<p align="center">
  Building useful software with thoughtful architecture, secure backend systems, and practical AI integrations.
</p>

<p align="center">
  📍 Ghaziabad, Uttar Pradesh, India · 🎓 CS Undergraduate, 2027 · 💼 Open to internships & entry-level roles
</p>

<p align="center">
  <a href="https://github.com/alexinwebs">
    <img src="https://img.shields.io/badge/GitHub-alexinwebs-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/alexinwebs">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
  <a href="https://alexinwebs.site">
    <img src="https://img.shields.io/badge/Portfolio-Explore-58A6FF?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="mailto:alexinwebs@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## `who-am-i`

I'm a Computer Science undergraduate graduating in 2027, focused on backend and full-stack development.

I build applications with TypeScript, Node.js, React, PostgreSQL, and modern backend tooling. My work spans secure authentication, background processing, database design, automated testing, deployment, and AI-assisted workflows.

I use Cursor, Claude, ChatGPT, and Gemini throughout planning, implementation, debugging, and testing, while taking ownership of architecture, understanding the code, integration, and validation.

- **Backend engineering:** REST APIs, validation, background jobs, and database architecture.
- **Application security:** OAuth 2.0, RBAC, secure sessions, 2FA, and encrypted tokens.
- **Practical AI:** LLM integrations with structured validation and human oversight.
- **Engineering quality:** Unit, integration, and browser-based end-to-end testing.
- **Deployment:** Docker Compose, CI pipelines, and production-oriented application workflows.

---

## Featured Projects

### 01 · PaperVault
**College Question-Paper Archive**

[![Live Project](https://img.shields.io/badge/Live-papervault.duckdns.org-2ea44f?style=flat-square&logo=googlechrome&logoColor=white)](https://papervault.duckdns.org)
[![Source Code](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/alexinwebs/papervault)

A deployed, moderated academic archive for discovering and organizing college question papers.

**Highlights**
- Hierarchical browsing, paginated search, PDF-text search, and multi-branch paper listings.
- Local PDF text extraction and OCR using unpdf, Poppler, Tesseract, and Sharp.
- Editable metadata suggestions with processing limits, timeouts, and manual-entry fallback.
- ClamAV file scanning and duplicate detection using file hashes and extracted text.
- College-scoped role-based access, revocable sessions, bcrypt, administrator TOTP 2FA, and Redis rate limiting.
- GitHub Actions for automated testing, dependency audits, image builds, and CodeQL.
- Docker Compose deployment with Caddy HTTPS.

**Stack:** Next.js · React · TypeScript · PostgreSQL · Prisma · Redis · Tesseract · Poppler · Sharp · ClamAV · Docker Compose

---

### 02 · MailPilot
**Self-Hosted AI Email Assistant for Gmail**

[![Source Code](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/alexinwebs/mailpilot-ai)

A solo-built, MIT-licensed AI email assistant that helps users understand their inbox, identify emails needing attention, and draft replies without surrendering control of the sending process.

**Highlights**
- Gmail synchronization through Google OAuth 2.0 and the Gmail API.
- Email-thread reconstruction, message classification, and reply-needed detection.
- LLM-powered reply drafting and critique.
- Human-in-the-loop review with Zod validation and a deterministic policy engine.
- The model never sends email directly; sending is designed to be idempotent.
- 25 REST API endpoints, 15 Prisma models, and a nine-route React dashboard.
- Six LLM provider integrations and Redis/BullMQ background processing.
- AES-256-GCM encrypted OAuth tokens.
- Verified on a live Render deployment.

**Stack:** React · TypeScript · Vite · Node.js · Fastify · PostgreSQL · Prisma · Zod · Redis · BullMQ · Docker Compose

---

### 03 · VIBE
**Driver-First Ride-Hailing Prototype**

[![Source Code](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/alexinwebs/vibe)
![Prototype](https://img.shields.io/badge/Status-Prototype-orange?style=flat-square)

A ride-hailing prototype designed around driver workflows, shared TypeScript contracts, and a differentiated commission model.

**Highlights**
- Rider and Driver mobile applications built with React Native and Expo.
- Node.js and Fastify REST API in a pnpm workspace monorepo.
- Shared data contracts through a dedicated `@vibe/types` package.
- Ride lifecycle: Searching → Driver Assigned → Driver Arriving → Ride Started → Ride Completed.
- Driver online/offline availability, ride history, and server-side fare and earnings calculations.
- Proposed commission model: 0% on VIBE+ rides and 15% on Free rides across bike, auto, and cab services.

**Stack:** React Native · Expo · TypeScript · React Navigation · Node.js · Fastify · REST APIs · pnpm Workspaces

*Status: Prototype using in-memory storage; not deployed.*

---

## Technical Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,nodejs,react,nextjs,tailwind,postgres,prisma,redis,docker,githubactions,git,postman,vscode&perline=7" alt="Skill icons"/>
</p>

**Languages:** TypeScript · JavaScript · SQL · HTML · CSS

**Backend & Frameworks:** Node.js · Fastify · Next.js · React · React Native · Tailwind CSS · RESTful APIs · Zod · BullMQ

**Databases & Data Processing:** PostgreSQL · Prisma · Redis

**Security & Authentication:** OAuth 2.0 · RBAC · TOTP 2FA · bcrypt · Encrypted OAuth Tokens

**Testing & DevOps:** Vitest · Playwright · Unit, Integration & E2E Testing · Docker Compose · GitHub Actions · Caddy · Render

**Familiar With:** Express.js · MongoDB · Mongoose · JWT · SQLite · Core Java

---

## AI-Assisted Development

I use AI as an engineering tool across the development lifecycle, not as a substitute for understanding the system.

| Stage | Approach |
|---|---|
| Planning | Breaking product requirements into implementation steps |
| Development | AI-assisted implementation and refactoring |
| Debugging | Investigating errors, edge cases, and integration failures |
| Validation | Reviewing generated code, testing behavior, and checking assumptions |
| Delivery | Verifying integrations, configuration, and deployment readiness |

**Tools:** Cursor · Claude · ChatGPT · Gemini

---

## GitHub Statistics

<p align="center">
  <img height="165" src="https://github-readme-stats-lyart-tau.vercel.app/api?username=alexinwebs&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true" alt="GitHub statistics"/>
  <img height="165" src="https://github-readme-stats-lyart-tau.vercel.app/api/top-langs/?username=alexinwebs&layout=compact&theme=github_dark&hide_border=true" alt="Most-used languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=alexinwebs&theme=github-dark-blue&hide_border=true" alt="GitHub contribution streak"/>
</p>

---

## Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/alexinwebs/alexinwebs/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/alexinwebs/alexinwebs/output/snake-light.svg" />
    <img alt="Animated GitHub contribution snake" src="https://raw.githubusercontent.com/alexinwebs/alexinwebs/output/snake-light.svg" width="100%" />
  </picture>
</p>

---

## Let's Connect

<p align="center">
  <a href="https://github.com/alexinwebs">GitHub</a> ·
  <a href="https://www.linkedin.com/in/alexinwebs">LinkedIn</a> ·
  <a href="https://alexinwebs.site">Portfolio</a> ·
  <a href="mailto:alexinwebs@gmail.com">Email</a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=alexinwebs&label=Profile%20Views&color=58A6FF&style=flat-square" alt="Profile views"/>
</p>

<p align="center">
  <i>Understand the system. Engineer the solution. Ship useful software.</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:58A6FF&height=100&section=footer" alt="Footer" width="100%"/>
</p>
