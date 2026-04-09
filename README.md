# aaronishere2025-bot

> **I build autonomous agents. This account hosts the ones I open-source.**

### Hey, I'm Aaron 👋

I'm the founder of **[Stackeroo](https://stackeroo.app)** — an AI-native business automation agency running six concurrent SaaS products on shared infrastructure. I went from zero coding experience to production agentic AI systems in **11 months** by leaning hard into spec-driven development with Claude Code.

Most of what I build falls under one theme: **multi-agent orchestration that replaces expensive cloud inference with smart local routing**. I like building things that are cheap to run, fast to ship, and genuinely autonomous.

---

## 🧩 What I've shipped

### Paperclip — 12-agent local LLM platform
Multi-agent orchestration routing inference across local and cloud LLMs. Cut per-query AI costs **~98%** vs pure cloud API usage by running 80%+ of tasks on local Qwen inference. Each agent owns a specialized domain with shared memory and tool access.
→ **[Read the case study](https://stackeroo.app/labs/paperclip)** · [Repo](https://github.com/aaronishere2025-bot/paperclip)

### Unity Video System — autonomous YouTube pipeline
End-to-end content generation: script → WAN 2.1 / LTX-Video synthesis on RTX 4070 → audio mix → upload → analytics feedback. Dual Thompson Sampling bandits optimize model routing and content style from Qwen auto-eval scores. Multi-seed compositing exploits GPU thermal cooldown for zero-cost parallelism.
→ [Repo](https://github.com/aaronishere2025-bot/unity-video-system)

### Fraud Files — automated dossier generation
Attorney-ready PPP fraud dossiers at **~1/10 the cost** of Westlaw / LexisNexis. Three-layer citation verification with independent damages recalculation and freshness checks. Idempotent data pipeline with universal record design.
→ [Repo](https://github.com/aaronishere2025-bot/fraud-files)

### Outreach Engine — multi-tenant email infrastructure
Shared email service consumed by every Stackeroo venture. IMAP reply classification, Jinja2 templates, domain warmup scheduling, and Thompson Sampling for send-time optimization. **156+ passing tests**.
→ [Repo](https://github.com/aaronishere2025-bot/outreach-engine)

### Stackeroo — shared infrastructure monorepo
The Docker Compose scaffold that runs every Stackeroo product. Shared PostgreSQL, Redis, scraping, outreach, and agent services. `add-project.sh` bootstraps new ventures with full infrastructure inheritance in a single command.
→ [stackeroo.app](https://stackeroo.app) · [Repo](https://github.com/aaronishere2025-bot/stackeroo)

### MaxClaims — roofing insurance SaaS
Full-stack client platform for DFW roofing contractors to automate insurance supplement workflows. Online intake, Stripe payments, client portal. Production on Hetzner VPS.
→ **[maxmyclaims.com](https://maxmyclaims.com)**

### PrimeRoute Oil — mobile oil change booking
Full-stack booking platform with city-targeted SEO landing pages for local search rankings. React / Vite frontend with FastAPI and async PostgreSQL backend.
→ **[primerouteoil.com](https://primerouteoil.com)**

---

## 🛠 Stack

**Languages** · Python · JavaScript / Node.js · Bash · SQL
**AI / ML** · Multi-agent orchestration · Thompson Sampling · Local LLM inference (Qwen 9B, RTX 4070) · WAN 2.1 · LTX-Video · Claude / GPT / Gemini integration
**Backend** · FastAPI · PostgreSQL · Redis · async Python · REST APIs · IMAP / SMTP
**Frontend** · React · Vite · responsive design · SEO-optimized rendering
**Infra** · Docker Compose monorepo · Hetzner VPS · Caddy · CI / CD · WSL2 / Ubuntu
**Dev tooling** · Claude Code · spec-driven development with CLAUDE.md per-project memory

---

## 🌐 Links

- **Agency** → [stackeroo.app](https://stackeroo.app)
- **Paperclip case study** → [stackeroo.app/labs/paperclip](https://stackeroo.app/labs/paperclip)
- **Email** → aaronishere2025@gmail.com

---

*Based in Ada, OK · Open to remote (US) · Currently building Stackeroo full-time*
