# Daniel Alexis Cruz

I work on AI agents, RAG services and the integrations that connect them to real businesses. My rule is simple: I don't trust a safety check until I've deleted it and watched a test fail. Most of what's below was built that way.

Portfolio: [dacruz.vercel.app](https://dacruz.vercel.app) | LinkedIn: [dacruz24](https://linkedin.com/in/dacruz24) | Email: [danielalexiscruz.pro@gmail.com](mailto:danielalexiscruz.pro@gmail.com)

---

## Recent work

**[enterprise-rag-knowledge-base](https://github.com/Exalt24/enterprise-rag-knowledge-base)** is a FastAPI RAG service on Qdrant, with vector search, BM25 hybrid and optional reranking. The bug I'm happiest I found: ranking was putting the best results last. After the fix I re-measured, and hit-at-one is 85% for vector and 90% for hybrid over 20 questions. I also took torch out of the deployed image so it fits a 512 MB instance.

**[multi-agent-research](https://github.com/Exalt24/multi-agent-research)**: seven LangGraph agents split a market research question between them. The fact checker can pause the run, so a person decides whether to continue.

**[clio-matter-bridge](https://github.com/Exalt24/clio-matter-bridge)** connects to Clio with live OAuth. The webhook receiver is checked against real signed deliveries, and nothing that identifies a client gets sent to a language model. 265 assertions, and every guard has been deleted once to prove the suite notices.

**[api-analytics-hub](https://github.com/Exalt24/api-analytics-hub)** pulls a live Shopify store into Postgres with row-level security per tenant. The isolation test caught a cross-tenant leak that came from a superuser connection. There's also an LLM copywriter that won't publish a number unless it's in the source facts. The hosted demo is offline.

**[clinic-call-console](https://github.com/Exalt24/clinic-call-console)** is an Angular and Spring Boot console for reviewing voice-assistant calls. Details are masked on arrival. To reveal one, an admin has to give a reason, and the reveal is audited in the same transaction. Synthetic data only.

**[ghl-tenant-bridge](https://github.com/Exalt24/ghl-tenant-bridge)**: GoHighLevel into Supabase, PostGIS radius matching, and an offline capture queue for field crews.

**[AreteusML](https://github.com/Exalt24/AreteusML)** fine-tunes ModernBERT on Banking77 and reaches 91.3% accuracy. It's served as an ONNX INT8 model behind FastAPI, with drift reports and a Dagster pipeline.

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

If an agent or a RAG pipeline of yours keeps breaking in annoying ways, I'd like to hear about it. I'm open to remote contract and full-time work. Email is the quickest way to reach me.
