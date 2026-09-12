<h1 align="center">Hi, I'm Sergio 👋</h1>
<h3 align="center">Senior AI Backend Engineer · Founding Engineer / Tech Lead scope · Python · Go · PHP/Symfony · LLM · Agentic SDLC</h3>

<p align="center">
  I build production <b>AI/LLM backends</b> and the platforms under them: clean architecture,
  data integrity, infrastructure as code, systems that stay stable under load.<br/>
  Most recently <b>Founding Engineer (acting CTO scope)</b> at a B2B marketplace: took over a stalled
  <b>19-repository</b> build, rebuilt it as one modular monolith and shipped it to production in <b>~7 weeks</b> —
  one engineer plus AI coding agents as the delivery workforce (<b>~670 merged PRs in 10 weeks</b>).<br/>
  8+ years in production. <b>Python</b> and <b>PHP/Symfony</b> are my deep base; <b>Go</b> through independent production-shaped projects.
  Based in Astana 🇰🇿 (UTC+5) · remote.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sergio-o-sel"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sergosel9+fromGithubReadme06.2026@gmail.com"><img src="https://img.shields.io/badge/Email-6C4FB6?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## 🧠 What I do

- **AI / LLM in production** — prompt management, multi-model routing (OpenAI · Azure OpenAI · Anthropic · Gemini), structured JSON output, RAG/retrieval patterns, real-time voice (**Gemini Live**), and **MCP** (OpenAPI-as-MCP; a read-only catalog MCP server running in production).
- **LLM evaluation** — Quality Assessment, golden/labelled datasets, scorecards, human-feedback comparison, eval loops for non-deterministic output.
- **Agentic SDLC** — a worktree-per-session dev platform (**>50** parallel worktrees, each with its own DB / S3 / Redis), Claude Code as builder + Codex as adversarial reviewer, spec → parallel plan zones → merge train, monthly process retros; an LLM-maintained Obsidian knowledge base (**214** pages, **11** ADRs) as shared context for people and agents.
- **Architecture** — DDD, CQRS, event-driven, modular monolith, transactional outbox, idempotent handlers, dead-letter queues; boundaries enforced by deptrac / phparkitect in CI.
- **Platform / IaC** — Kubernetes + Helm (migration hooks, atomic rollback, default-deny NetworkPolicies), OpenTofu / Terraform, GitHub Actions with OIDC (no long-lived cloud keys), External Secrets, WireGuard, encrypted offsite backups.
- **Data pipelines** — web crawl + supplier parsers in Python, staged imports with human review and integrity checks, BigQuery analytics pipelines.
- **Go as a secondary backend stack** — deployed independent projects with workers, queues, concurrency caps, graceful shutdown and CI.

📄 **Full experience & CV:** [LinkedIn →](https://www.linkedin.com/in/sergio-o-sel)

---

## 🚀 Featured projects

| Project | What it is | Stack |
|---|---|---|
| **[OutboxLab](https://github.com/selivanov-tech/outboxlab)** | AI cold-outreach engine: send → reply-detect → **LLM intent-classify** → auto-pause. Bounce/suppression, per-mailbox send caps, OpenAPI-as-MCP, tests, CI, clean domain boundaries. | `Python 3.14` · `FastAPI` · `PostgreSQL` · `Anthropic` · `Gmail API` · `LangChain/LangGraph (R&D)` · `DDD/Hexagonal` |
| **[tg-audio-bot](https://github.com/selivanov-tech/tg-audio-bot)** | Downloads YouTube audio to Telegram (`yt-dlp` + `ffmpeg`). Hexagonal/DDD with a pluggable **provider registry**, per-user queue + global concurrency caps (a flood of links cannot OOM a 512 MB VM), throttled live progress, webhook intake + **Fly.io zero-scale**. | `Go 1.26` · `Telegram Bot API` · `yt-dlp` · `Fly.io` |
| **[symfony-ddd-demo](https://github.com/selivanov-tech/symfony-ddd-demo)** | DDD/CQRS **modular monolith** (loan eligibility): bounded-context modules + a shared kernel, command/query buses, rich aggregates + domain events, an **anti-corruption layer** between contexts, and **deptrac-enforced** layers *and* per-module boundaries. `apps/{api,cli}` split, sync-now/async-ready, **OpenAPI 3 + Swagger UI**. | `PHP 8.3` · `Symfony 7.4 LTS` · `Doctrine ORM 3` · `DDD/CQRS` · `deptrac` · `OpenAPI` · `PHPUnit` |

<!-- Add rows when public / documented: STT service (Go + Python, WER/CER eval harness) · agent-skills (worktree-per-session tooling) · Coffee-shop scheduler (TypeScript, still a skeleton) · Boxing platform (Laravel/Livewire) · Aria (FastAPI). -->
<!-- Tip: a featured repo needs a description + README, or it looks empty. -->

---

## 🛠️ Tech I use

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
</p>

**Backend & AI**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Symfony-000000?style=for-the-badge&logo=symfony&logoColor=white"/>
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini-886FBF?style=for-the-badge&logo=googlegemini&logoColor=white"/>
</p>

**Data & messaging**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"/>
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white"/>
</p>

**Platform & cloud**

<p>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenTofu-FFDA18?style=for-the-badge&logo=opentofu&logoColor=black"/>
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Yandex_Cloud-5282FF?style=for-the-badge&logo=yandexcloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/Fly.io-7B3FE4?style=for-the-badge&logo=flydotio&logoColor=white"/>
</p>

**Frontend**

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nuxt-00DC82?style=for-the-badge&logo=nuxtdotjs&logoColor=white"/>
</p>

---

## 🔬 Currently exploring

Agent orchestration for software delivery: multi-agent merge trains, worktree isolation, MCP servers as the safe interface to production data. **LangChain / LangGraph / ADK** for agent workflows; **Langfuse / Phoenix** for LLM tracing; **MLflow GenAI** for golden datasets and eval pipelines. A **speech-to-text service** in Go + Python (worker pool, job store, WER/CER eval harness).

---

## 📊 GitHub stats

<!-- Cards are just images — no setup, no Actions. -->

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=selivanov-tech&show_icons=true&hide_border=true&title_color=6C4FB6&icon_color=9B7EDE&text_color=2A2433&bg_color=FFFFFF"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=selivanov-tech&layout=compact&hide_border=true&title_color=6C4FB6&text_color=2A2433&bg_color=FFFFFF"/>
</p>

---

<p align="center">
  <i>Open to remote backend / AI engineering roles · Kazakhstan labor contract or B2B with my Kazakhstan-registered company.</i>
</p>
