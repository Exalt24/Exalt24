# Daniel Alexis Cruz

I work on AI agents, RAG services and the integrations that connect them to real businesses. My rule is simple: I don't trust a safety check until I've deleted it and watched a test fail. Most of what's below was built that way.

Portfolio: [dacruz.vercel.app](https://dacruz.vercel.app) | LinkedIn: [dacruz24](https://linkedin.com/in/dacruz24) | Email: [danielalexiscruz.pro@gmail.com](mailto:danielalexiscruz.pro@gmail.com)

---

## Recent work

**[roofing-site-lab](https://github.com/Exalt24/roofing-site-lab)** is an Astro and Sanity contractor site on Cloudflare Pages whose build refuses dead links, orphan pages and near-duplicate pages, on invented jobs and photos. It also holds a redirect map tool for moving a site off a builder: it writes the Cloudflare redirects file with every 301 spelled out and refuses chains, loops and any rule that would hide a live page. Served through Cloudflare's own local runtime, it showed an old .html address returning a 404, now fixed, and two independent passes tried to break it. It has not moved a client's site.

**[enterprise-rag-knowledge-base](https://github.com/Exalt24/enterprise-rag-knowledge-base)** is a FastAPI RAG service on Qdrant, with vector search, BM25 hybrid and optional reranking. The bug I'm happiest I found: ranking was putting the best results last. After the fix I built a rerunnable evaluation around it, with hit-at-k and MRR on a synthetic corpus, a pinned baseline and a mutation check that run in CI, so the next ranking bug fails a test. It also has a read-only MCP server and an agent skill, so Claude Code can search the knowledge base and cite the chunk each answer came from. I also took torch out of the deployed image so it fits a 512 MB instance.

**[multi-agent-research](https://github.com/Exalt24/multi-agent-research)**: seven LangGraph agents split a market research question between them. The fact checker can pause the run, so a person decides whether to continue. One agent asked Groq's free tier for roughly 11,000 tokens a minute against an 8,000 ceiling and could never finish; its budgets are now named constants that sit under that ceiling.

**[clio-matter-bridge](https://github.com/Exalt24/clio-matter-bridge)** connects to Clio with live OAuth. The webhook receiver is checked against real signed deliveries, and nothing that identifies a client gets sent to a language model. 265 assertions, and every test run deletes three guards to check the suite goes red.

**[api-analytics-hub](https://github.com/Exalt24/api-analytics-hub)** pulls a live Shopify store into Postgres with row-level security per tenant. The isolation test caught a cross-tenant leak that came from a superuser connection. There's also an LLM copywriter that won't publish a number unless it's in the source facts, and a Slack alert for syncs that are stuck or stale. A separate slice compares a daily file of about 400,000 invented carriers with what's held on one hash, raises each alert once behind a UNIQUE key and queues it in an outbox for a CRM, in under 10 s for day 2. A monthly report stage turns stored snapshots into a PowerPoint deck with python-pptx, and a model's wording is only used when every figure in it matches the computed ones. A Google Analytics 4 connector puts the website beside the store in that deck, built against a stand-in server written from Google's documentation. It has 1,429 tests and 209 mutation guards. The hosted demo is offline.

**[clinic-call-console](https://github.com/Exalt24/clinic-call-console)** is an Angular and Spring Boot console for reviewing voice-assistant calls. Details are masked on arrival. To reveal one, an admin has to give a reason, and the reveal is audited in the same transaction. It has 71 Java tests and a script that breaks 28 guards one at a time to check they notice. Synthetic data only.

**[ghl-tenant-bridge](https://github.com/Exalt24/ghl-tenant-bridge)**: GoHighLevel into Supabase, a Cloudflare Worker receiver on D1 with a mutation-checked test suite, a Python relay that fans leads out to Slack, Make, Meta Conversions API and Google Sheets and pulls ad spend (built against vendor-documentation fakes, never a real account), Terraform for ECS Fargate and RDS Postgres (tested offline with a mocked provider and a 49-mutant harness, never applied to AWS), a Hasura GraphQL layer over the PostGIS tables, a history import with a suppression list and a Windows scheduled task for the worker with a heartbeat health check, PostGIS radius matching, a farm-list intake that rejects a bow-tie polygon instead of repairing it into two plots (61 checks, 17 mutants), and an offline capture queue for field crews. A bounding box would have matched a property 67.2 km from a 50 km storm; the PostGIS distance check rejects it.

**[trakie-prototype](https://github.com/Exalt24/trakie-prototype)** pairs a Chrome extension with a phone by QR so invoice photos fill a desktop form through a vision model. The phone now uploads straight to S3-compatible storage with a presigned URL that signs the file's type and size; 146 tests run against a real MinIO and a 19-mutant harness checks the guards. It was not run against AWS S3.

**[AreteusML](https://github.com/Exalt24/AreteusML)** fine-tunes ModernBERT on Banking77 and reaches 91.3% accuracy (the PyTorch model). It's served as an ONNX INT8 model behind FastAPI that answers in 10.11 ms against 45.66 ms for PyTorch; I did not re-score the INT8 model's accuracy.

**[agent-harness-lab](https://github.com/Exalt24/agent-harness-lab)** is a small TypeScript agent harness for local models: loop guards, a context that keeps the full tool result retrievable, and an eval runner that scores a model with confidence intervals. On a 4B model it showed that setting the temperature mattered for tool choice, and that temperature 0 made one case a certain miss. A mutation check removes each guard in turn and a test has to fail.

Earlier projects: [shopify-theme-lab](https://github.com/Exalt24/shopify-theme-lab) (a generated sale page turned into editable Shopify sections, tested through LiquidJS and Chromium), [AutoFlow Pro](https://github.com/Exalt24/autoflow-pro) (browser automation), [NFT-Trading](https://github.com/Exalt24/NFT-Trading) (ERC-721 marketplace), [RataTutor](https://github.com/Exalt24/RataTutor) (an AI study platform I led with a team of 5) and [MAGSEL](https://github.com/Exalt24/MAGSEL) (research presented at WILLS 2025 in Kyoto).

---

## What I work with

AI and agents: LangGraph, LangChain, tool calling, Model Context Protocol, RAG, Qdrant, Ollama, Claude Code, Codex, PyTorch, ONNX Runtime.
Backend: Python, TypeScript, Node.js, FastAPI, Django, Java, Spring Boot, GraphQL, Hasura, PostgreSQL, MariaDB, Supabase, Redis, PDF data extraction.
Frontend and web: React, Next.js, Astro, Angular, Vue.js, Tailwind CSS, technical SEO, Redirect Management.
Automation and integration: n8n, Zapier, Playwright, Appium, webhooks, OAuth, Shopify, JobNimbus, WordPress.
Cloud and testing: Docker, Terraform, GitHub Actions, AWS (ECS Fargate), Azure, Cloudflare Pages and Workers, Linux, pytest, Vitest, Testcontainers.

---

## Work with me

If an agent or a RAG pipeline of yours keeps breaking in annoying ways, I'd like to hear about it. I'm open to remote contract and full-time work. Email is the quickest way to reach me.
