<div align="center">

<img src="./assets/banner.svg" alt="Varun Motiyani — AI Engineer at Strategy" width="100%">

</div>

> I build LLM systems end to end — from the agent loop and the prompt layer down
> to the APIs, the databases, and the deploy. Most of my work is the part that
> makes language models dependable in production: planning, tool orchestration,
> memory, structured output, latency, and evaluation.

**AI Engineer at Strategy** (formerly MicroStrategy) · Pune, India

---

### ⚡ What I build

- **AutoAgents** — the agentic framework behind Strategy's AI products. A planner
  turns a complex question into a tool plan and executes it. I'm the sole
  architect: a ReWOO plan-then-execute loop with a ReAct fallback, tools decoupled
  behind a single integration point so new ones (web, geospatial, proximity
  search) plug in without touching the planner, and parallel tool calls that cut
  response latency by more than half. I also built the MCP layer — AutoAgents as
  both MCP client and host via `fastmcp`, so it can talk to Atlassian, GitHub,
  Notion, and others — and **SimpleMem**, a short- and long-term agent memory
  package (ClickHouse + Redis) now used across three internal AI services.

- **AutoDash** — turns a natural-language request into a built analytics
  dashboard. Built it end to end, architecture through deploy: a ReAct
  orchestration engine over parallel intent agents, run as a two-stage async task
  with a fallback path for complex sequential work.

- **AutoPrompt** — a microservice that serves the right prompt for whichever model
  and provider is in play. Prompt versioning plus dynamic rendering keyed on
  provider and model variant — the piece that makes bring-your-own-LLM work
  cleanly across every AI product.

- **CLS AutoBot** (`ai-cls-router`) — reads each incoming support case with an LLM
  and auto-assigns the right engineer on a 60-second loop. A five-step routing
  pipeline with a custom workload-scoring algorithm, skill-pool and overflow-chain
  rules, ~95 REST endpoints across 16 routers, and real-time audit streaming over
  WebSockets on Redis Streams. Python/FastAPI, PostgreSQL, Redis, Azure OpenAI,
  on AWS EKS.

- **EP Review Processing** — automates the enterprise performance-review cycle. A
  parallel pipeline scoring 100+ reviews at once against competency frameworks,
  with multi-format ingestion (Whisper for video, MoviePy for audio, plus
  documents), language detection and translation, generated DOCX reports, and
  Teams-bot notifications. Exactly-once state tracking keeps reruns safe.

---

### 🧪 On the side

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

[![LinkedIn](https://img.shields.io/badge/LinkedIn-varun--motiyani14-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/varun-motiyani14/)
[![Email](https://img.shields.io/badge/Email-varun.motiyani14%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:varun.motiyani14@gmail.com)

Pune, India — open to conversations about AI platform / LLM infrastructure roles.

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=VarunMotiyani&show_icons=true&hide=stars,issues&hide_title=true&hide_border=true&theme=github_dark&custom_title=Activity&count_private=true" alt="GitHub stats" height="150">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=VarunMotiyani&theme=github-compact&hide_border=true&area=true" alt="Contribution activity" width="100%">

</div>
