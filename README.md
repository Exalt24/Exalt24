# Daniel Alexis Cruz

AI agent engineer in Cebu, working remote. I build multi-agent workflows and RAG services in Python and TypeScript, and the API and webhook integrations around them. A wrong answer should get caught before a client sees it, so I put human approval steps, error handling and tests in from the start.

I graduated from UP Cebu with a Computer Science degree in 2025 and I work in Claude Code every day. I also completed Anthropic's courses on Claude Code, the Claude API, Model Context Protocol and agent skills.

Portfolio: [dacruz.vercel.app](https://dacruz.vercel.app) | LinkedIn: [dacruz24](https://linkedin.com/in/dacruz24) | Email: [danielalexiscruz.pro@gmail.com](mailto:danielalexiscruz.pro@gmail.com)

---

## Recent work

**[enterprise-rag-knowledge-base](https://github.com/Exalt24/enterprise-rag-knowledge-base)** is a FastAPI RAG service on Qdrant with vector, BM25 hybrid and optional reranking. I found a ranking bug that put the best results last, fixed it and re-measured: hit-at-one of 85% for vector and 90% for hybrid over 20 questions. I also took torch out of the deployed image so it fits a 512 MB instance.

**[multi-agent-research](https://github.com/Exalt24/multi-agent-research)** has seven LangGraph agents split a market research question. The fact checker can pause the run so a person decides whether to continue.

**[clio-matter-bridge](https://github.com/Exalt24/clio-matter-bridge)** is a Clio integration with live OAuth, a webhook receiver checked against real signed deliveries, and a boundary that keeps anything identifying out of what is sent to a language model. It has 265 assertions, and each guard is proven by deleting it and watching the suite fail.

**[api-analytics-hub](https://github.com/Exalt24/api-analytics-hub)** syncs a live Shopify store into Postgres with row-level security per tenant. Its isolation test caught a cross-tenant leak caused by a superuser connection. It also has an LLM copywriter that refuses to publish any number that is not in the source facts. The hosted demo is offline.

**[clinic-call-console](https://github.com/Exalt24/clinic-call-console)** is an Angular and Spring Boot console for reviewing voice-assistant calls. Details are masked when a call arrives, an admin has to give a reason to reveal one, and every reveal is audited in the same transaction. Synthetic data only.

**[ghl-tenant-bridge](https://github.com/Exalt24/ghl-tenant-bridge)** connects GoHighLevel to Supabase with PostGIS radius matching and an offline capture queue for field crews.

**[AreteusML](https://github.com/Exalt24/AreteusML)** fine-tunes ModernBERT on Banking77 to 91.3% accuracy and serves it as an ONNX INT8 model behind FastAPI, with drift reports and a Dagster pipeline.

Earlier projects: [AutoFlow Pro](https://github.com/Exalt24/autoflow-pro) (browser automation), [NFT-Trading](https://github.com/Exalt24/NFT-Trading) (ERC-721 marketplace), [RataTutor](https://github.com/Exalt24/RataTutor) (an AI study platform I led with a team of 5) and [MAGSEL](https://github.com/Exalt24/MAGSEL) (research presented at WILLS 2025 in Kyoto).

---

## What I work with

AI and agents: LangGraph, LangChain, tool calling, Model Context Protocol, RAG, Qdrant, Claude Code, Codex, PyTorch, ONNX Runtime.
Backend: Python, TypeScript, Node.js, FastAPI, Django, Java, Spring Boot, PostgreSQL, MariaDB, Supabase, Redis.
Frontend: React, Next.js, Angular, Vue.js, Tailwind CSS.
Automation and integration: n8n, Zapier, Playwright, webhooks, OAuth, Shopify, WordPress.
Cloud and testing: Docker, GitHub Actions, AWS, Azure, Cloudflare Workers, Linux, pytest, Vitest, Testcontainers.

---

## Work with me

I'm open to remote contract and full-time work building AI agents and integrations. The fastest way to reach me is email.
