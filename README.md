# 👋 Hi, I'm Kapil Kumar

**AI Engineer · Python Developer · Software Developer** — Associate Software Engineer at Aviara Labs, Noida.

I build production AI systems: LangGraph agent workflows, RAG pipelines, and voice agents that handle 50,000+ calls a month, plus the evaluation tooling that keeps them reliable. Most of my work is Python backends (FastAPI, Django) deployed with Docker on Azure.

---

## 💻 Tech Stack

| Area | Tools |
|---|---|
| **Languages** | Python, SQL, TypeScript, Java |
| **AI & Agents** | LangGraph, LangChain, RAG, LLM integration, prompt engineering, ElevenLabs Voice AI, Groq |
| **Retrieval** | pgvector, sentence-transformers embeddings, sqlglot query guardrails |
| **Backend** | FastAPI, Django, Django REST Framework, Flask, Pydantic v2, SQLAlchemy + Alembic, microservices |
| **Realtime** | REST APIs, WebSockets, Server-Sent Events (SSE), webhooks |
| **Data** | PostgreSQL, DuckDB, Parquet, Polars, Pandas, NumPy, MongoDB, Redis, Power BI, Excel |
| **Cloud & DevOps** | Azure (VM, Blob Storage, PostgreSQL), Docker, Docker Compose, GitHub Actions CI/CD, Nginx, Caddy |
| **Automation** | Make.com, n8n, UiPath |
| **Tools** | Git, GitHub, Postman, VS Code |

---

## 💼 Experience

### 🏢 Associate Software Engineer — *Aviara Labs*
📍 Noida | 🗓️ Dec 2025 – Present

- Build and run low-latency, full-duplex **ElevenLabs voice agents** for healthcare clinics, handling scheduling and live call transfers across **50,000+ calls and 100k+ minutes a month**
- Designed **multi-agent LangGraph workflows** for a healthcare scheduling platform across **Django and FastAPI** microservices, cutting appointment scheduling time from **20 minutes to 8**
- Built **VoiceQA**, an agent evaluation service that runs scenario-driven test calls, scores transcripts with a two-stage LLM pipeline, stores every run in PostgreSQL, and reports pass rates over REST and CLI
- Made VoiceQA reusable: onboarding a new agent takes one scenario file and no code changes
- Built automation pipelines with **Make.com** and **n8n** connecting external APIs, CRM and backend systems

### ✈️ Apprentice, Data Analytics — *Air India Limited*
📍 Gurugram | 🗓️ Oct 2025 – Dec 2025

- Cleaned, transformed and analysed business and financial datasets using **Python (Pandas, NumPy), SQL and Excel**
- Built interactive **Power BI dashboards** for non-technical stakeholders
- Produced insights that supported strategic decision-making

---

## 🚀 Featured Projects

### 🧭 [ApplyPilot](https://applypilot.kapilp.tech) — *live*
**FastAPI • PostgreSQL + pgvector • Redis • Celery • Next.js • Typst • LaTeX • Docker • Azure**

- Human-in-the-loop job-application copilot: job discovery, an Overleaf-style résumé editor, and JD-driven tailoring
- Pulls jobs from **9 keyless ATS feeds** (including Workday), filtered by country at the source
- Every tailored bullet is checked against the résumé's evidence; unsupported numbers, tools or employers are **blocked from export**
- Compatibility report compiles the PDF and reads it back with two parsers instead of guessing an "ATS score"
- **623 tests**, including a red-team suite for the verifier

### 📊 [ExcelMind](https://excelmind.kapilp.tech) — *live*
**FastAPI • DuckDB • Parquet • Polars • PostgreSQL + pgvector • Redis • Azure Blob • LangGraph • React + TypeScript**

- Upload spreadsheets up to **200 MB** and browse millions of rows with **sub-100 ms** queries
- Rebuilt ingestion with python-calamine + Polars for a **~50× faster parse**
- Chat with your sheet in plain English: NL→SQL behind a sqlglot guard, **98% exact match** on a 52-case eval
- Optional LangGraph "deep mode" agent and auto-generated dashboards

### 📄 [Contract Intelligence API](https://github.com/Kapilkumar16/contract-intelligence-api)
**FastAPI • RAG • LLMs • Docker • Redis • SSE**

- RAG-based contract analysis REST API with PDF ingestion and automated field extraction
- Question answering across multiple LLM providers with real-time SSE streaming and webhook callbacks
- Risk-audit engine with a regex fallback, so it keeps working during LLM outages or rate limits

### 🖥️ [Process Monitor Agent](https://github.com/Kapilkumar16/Process-monitoring-agent)
**Python • Django REST Framework • Channels • WebSockets • Redis • psutil**

- Cross-platform monitoring: a lightweight agent streams CPU, memory and process-tree metrics using `psutil`
- Django REST API with per-host API key authentication
- Live dashboard updates over WebSockets (Django Channels + Redis)

---

## 🎓 Education

**College of Engineering Roorkee** — B.Tech, Computer Science and Engineering
📅 Sep 2021 – Jun 2025

---

## 📜 Certifications

- Django Full Stack Development — Udemy
- Data Visualization — TATA (Forage)

---

## 📫 Connect With Me

📍 Gurugram, Haryana, India
📧 **kapil10kumar2004@gmail.com**

- 💼 LinkedIn: [kapil-kumar-3b8748249](https://www.linkedin.com/in/kapil-kumar-3b8748249/)
- 💻 GitHub: [Kapilkumar16](https://github.com/Kapilkumar16)

---

## ⚡ Currently Exploring

- Multi-agent systems and agent evaluation
- Advanced RAG architectures
- LLM-powered automation
- Scalable backend infrastructure

---

> 💡 *Building intelligent systems that combine AI, automation and scalable backend engineering.*
