# Oussama Abouyahia

**Software Engineer focused on AI infrastructure, backend platforms, developer tools, and retrieval systems.**

I build practical AI/backend systems that connect LLMs, data pipelines, and production workflows. My strongest interests are developer platforms, RAG systems, agent workflows, scalable backend architecture, and tools that help engineers move faster.

- **Core stack:** Python, TypeScript, FastAPI, Next.js/React, PostgreSQL, Redis, Docker
- **Focus areas:** AI infrastructure, API platforms, code intelligence, RAG, agents, backend systems
- **Currently improving:** system design, production AI apps, open-source developer tooling
- **Contact:** [oabouyahia@gmail.com](mailto:oabouyahia@gmail.com)

[LinkedIn](https://www.linkedin.com/in/oussama-abouyahia/) · [LeetCode](https://leetcode.com/u/ousamazing/) · [Code Intel Demo](https://codebase-intelligence.vercel.app)

---

## Selected Work

### [Docu Meter API](https://github.com/Oussamcsc/docu-meter-api)
**Universal API auth and metering engine with a document analyzer built in.**

Docu Meter is a production-style developer API platform that gives any microservice a reusable request ladder: API key identity, Redis rate limiting, project quota checks, service execution, and Postgres usage tracking.

- Built a FastAPI protected API with HMAC-SHA-256 API key verification and one-time secret disclosure.
- Added Redis-backed project-level rate limiting and monthly quota enforcement before expensive service work runs.
- Implemented Postgres-backed usage tracking, project metrics, and a Next.js dashboard for API key/usage visibility.
- Dockerized the full stack with FastAPI, Next.js, Postgres 15, Redis 7, Alembic auto-migrations, and persistent volumes.
- Designed the architecture to support arbitrary service logic beyond document analysis: scraping, data fetching, enrichment APIs, ML inference, and internal tools.

### [Code Intel](https://github.com/Oussamcsc/codebase-intelligence)
**AI-powered codebase analysis platform for understanding and reviewing repositories.**

Code Intel combines static analysis, AST parsing, graph traversal, vector retrieval, and LLM reasoning to scan repositories and surface code quality, architecture, security, and performance insights.

- Built GitHub repository scanning with file/line-level analysis.
- Implemented circular dependency detection using directed graph traversal.
- Combined static analysis with vector embeddings for context-aware code insights.
- Designed multi-agent review workflows for security, performance, and architecture checks.
- Deployed full-stack app with FastAPI, React, ChromaDB, PostgreSQL, Docker, and OpenAI.

**Live demo:** https://codebase-intelligence.vercel.app

### [ListflowAI MVP UI](https://github.com/Oussamcsc/ListflowAi-mvp-UI)
**Frontend MVP for an AI-assisted email automation and lead workflow platform.**

ListflowAI is designed around lead ingestion, scoring, personalization, inbox rotation, and campaign orchestration. The public repo currently shows the UI layer while backend automation workflows are planned around Supabase, n8n, OpenAI-assisted personalization, PostgreSQL, and REST APIs.

- Built TypeScript/React MVP interface for campaign and workflow management.
- Designed product flow around lead scoring, personalization, and campaign operations.
- Created authenticated app flows, onboarding UX, dashboard screens, and campaign setup views.

---

## Technical Focus

**AI / ML Systems**  
RAG pipelines, semantic search, vector databases, LangChain, OpenAI API, agent workflows, evaluation loops

**Backend Engineering**  
FastAPI, Node.js, REST APIs, WebSockets, PostgreSQL, Redis, caching, API auth, system architecture

**Frontend / Product**  
React, TypeScript, Next.js, interfaces for developer tools and AI workflows

**Infra / Tools**  
Docker, Git, Vercel, Railway, Supabase, AWS fundamentals, CI/CD fundamentals

---

## What I’m Looking For

I’m open to software engineering roles involving backend systems, AI/ML infrastructure, developer tools, retrieval systems, or agent platforms.

I’m especially interested in teams building practical AI systems where correctness, latency, reliability, and user workflow matter.
