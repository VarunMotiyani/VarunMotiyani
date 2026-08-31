<div align="center">

<img src="./assets/banner.svg" alt="Varun Motiyani — AI Engineer at Strategy" width="100%">

</div>

> I work on LLM systems in production — the agent loop, the prompt layer, the
> APIs and datastores under them. Mostly the parts that make language models
> dependable: planning, tool orchestration, memory, structured output, latency,
> and evaluation.

**AI Engineer at Strategy** (formerly MicroStrategy) · Pune, India

🌐 &nbsp;[**varunmotiyani.xyz**](https://varunmotiyani.xyz) &nbsp;·&nbsp; portfolio, projects, and writing

---

### ⚡ What I work on

- **AutoAgents** — the agent framework behind Strategy's AI products, where a
  planner turns a complex question into a tool plan and runs it. I've built major
  pieces of it: the ReWOO/ReAct planning loop, a one-point tool-integration layer
  so new tools plug in without touching the planner, parallel tool execution for
  latency, the MCP client/host layer, and **SimpleMem** — a short- and long-term
  agent-memory package (ClickHouse + Redis) I designed and own, reused across
  several internal AI services.

- **AutoDash** — turns a natural-language request into a built analytics
  dashboard. I contributed the ReAct orchestration engine over parallel intent
  agents, run as a two-stage async task with a fallback for complex sequential work.

- **AutoPrompt** — a microservice I built for provider-aware prompt management:
  prompt versioning and dynamic rendering keyed on model and provider, the piece
  that makes bring-your-own-LLM work across products.

- **Support-case routing** — an LLM service that reads each incoming support case,
  infers the product area, complexity, and skills involved, scores the available
  engineers by current workload, and auto-assigns on a short polling loop. Built
  end to end in async Python — FastAPI, PostgreSQL, Redis.

- **Bootcamp grading** — an LLM grader for sales-training submissions: it pulls
  the trainee's pitch from a call transcript, scores it against a rubric, folds in
  quiz results, and returns a final grade with a written breakdown.
  Schema-constrained extraction; FastAPI + React.

- **EP review automation** — automates the enterprise performance-review cycle: a
  parallel pipeline that scores manager feedback against competency frameworks,
  with video/audio/document ingestion (Whisper, MoviePy), translation, generated
  DOCX reports, and Teams notifications.

---

### 🧪 On the side

- [`fitness-tracker-ios`](https://github.com/VarunMotiyani/fitness-tracker-ios) —
  an adaptive strength & physique coach for iOS: equipment-aware weekly planning,
  rolling adaptation around missed sessions and daily readiness, in-gym logging
  with one-tap machine swaps, and monthly InBody scan analysis. Phone-only, no
  backend, bring-your-own AI key.
- [`dev-playbook`](https://github.com/VarunMotiyani/dev-playbook) — a Claude Code
  plugin that packages one opinionated method for taking a feature from raw idea
  to reviewed, merged code: a coordinating session plus fresh subagents per task,
  with human gates at design, spec, and integration.
- [`llmcontrol`](https://github.com/VarunMotiyani/llmcontrol) — one interface for
  prompts, parameters, and invocation across LLM providers.
- [`crawller`](https://github.com/VarunMotiyani/crawller) — a small Python web crawler.

---

### 🛠 Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**LLM** — agents (ReWOO, ReAct, MCP) · prompt engineering · RAG & GraphRAG ·
knowledge graphs · evaluation (LangSmith, Opik, DeepEval)

---

### 📜 Certifications

- Anthropic Claude Certified Architect – Foundational (CCAF)
- Oracle Cloud Infrastructure — Generative AI Certified Professional
- Neo4j Certified Professional · Neo4j Certified Data Scientist
- Snowflake — Data Warehousing, Data Engineering, and Marketplace badges

---

### 📫 Reach me

[![Portfolio](https://img.shields.io/badge/Portfolio-varunmotiyani.xyz-000000?style=flat-square&logo=vercel&logoColor=white)](https://varunmotiyani.xyz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-varun--motiyani14-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/varun-motiyani14/)
[![Email](https://img.shields.io/badge/Email-varun.motiyani14%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:varun.motiyani14@gmail.com)

Pune, India — open to conversations about AI platform / LLM infrastructure roles.
