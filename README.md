<div align="center">

# Daniel Alexis Cruz

```
┌─────────────────────────────────────────┐
│  AI · Blockchain · Security             │
│  Building at the intersection.          │
└─────────────────────────────────────────┘
```

**Full-Stack Developer** | Cebu, Philippines 🇵🇭

[![Portfolio](https://img.shields.io/badge/Portfolio-dacruz.vercel.app-0ea5e9?style=for-the-badge&logo=vercel&logoColor=white)](https://dacruz.vercel.app) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dacruz24) [![Email](https://img.shields.io/badge/Email-danielalexiscruz.pro@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:danielalexiscruz.pro@gmail.com)

</div>

---

## Who I Am

UP Cebu Computer Science grad, currently shipping full-stack applications at JinFortis Digital with Django and React.

Did my internship at ChatGenie (Techstars '23), where I learned to build complete applications from scratch in 3-day sprints using technologies I'd never touched before. Turns out the best way to learn Rails and Vue.js is under pressure.

Recently built a **multi-agent AI system** that reduces 6-8 hour research tasks to **1.75 minutes** through strategic coordination. Learned that having all agents run with shared guidance beats trying to dynamically route.

Also architected a **production RAG system** where retrieval quality mattered more than LLM quality, and a **distributed browser automation platform** that taught me WebSocket + job queues is a powerful combination.

I work at the intersection of **AI, Blockchain, and Security**. Not because they're trendy, but because they're where interesting problems live.

Started October 2025 learning Solidity from scratch, by November I was building distributed job processing systems, by December I was orchestrating multi-agent workflows.

**Google Cybersecurity certified** because security isn't something you add later, it's an architectural decision.

```javascript
const daniel = {
  location: "Cebu, Philippines",
  focus: ["AI & Multi-Agent Systems", "Blockchain & Web3", "Security Architecture"],
  current: ["Full-Stack Development", "Production Systems", "Free-Tier Optimization"],
  approach: "Strategic coordination beats dynamic routing",
};
```

---

## The Trinity

### 🤖 AI & Multi-Agent Systems

Built multi-agent orchestration system coordinating **7 specialized agents** with LangGraph, reducing **6-8 hour research to 1.75 minutes**.

Implemented strategic guidance pattern where all agents run with shared JSON objectives. Turns out strategic coordination beats dynamic routing.

Architected production RAG system with **5 retrieval strategies**, achieving **67.7% → 85%+ accuracy** through hybrid search and cross-encoder reranking.

**What I learned:**

Retrieval quality matters more than LLM quality in RAG systems.

Token counting accuracy with `tiktoken` revealed we were undercounting by 72% in some agents, critical for context management.

Parallel execution with LangGraph's `operator.add` for safe state merging taught me memory-safe concurrent patterns apply everywhere.

**Stack:** LangGraph, LangChain, FastAPI, Qdrant, Redis, Ollama, Groq, Sentence Transformers, BullMQ

---

### ⛓️ Blockchain & Web3

Started learning Solidity from scratch in October 2025. By month's end, shipped full-stack **NFT marketplace** with ERC-721 contracts, batch minting, and royalty management.

Built **blockchain explorer** achieving **8-10x performance** through LRU caching, and Web3 game with TypeScript SDK abstracting contract complexity.

Comprehensive testing: **52 contract tests plus 50+ integration tests**. Not just another tutorial project.

**What I learned:**

Gas optimization is an art.

Smart contract testing isn't optional, production systems need comprehensive coverage.

Architectural decisions matter more than code-level optimizations.

Building SDK taught me that good abstraction means hiding complexity without sacrificing control.

**Stack:** Solidity, Hardhat, ethers.js, OpenZeppelin, IPFS, WebSocket, TypeScript, PostgreSQL

---

### 🔒 Security Architecture

**Google Cybersecurity certified.** Security isn't a feature you add later, it's an architectural decision.

Implemented enterprise patterns across projects: **Row-Level Security (RLS)** for multi-tenant isolation, **rate limiting** (100 req/15min), **input sanitization** against injection attacks, secure credential storage, 2-tier fallbacks for reliability.

Applied security thinking from internship where I learned shipping secure matters more than shipping fast.

**What I learned:**

Security is infrastructure.

RLS at database level beats application-layer checks.

Rate limiting protects both your quotas and your users.

Free-tier constraints force production patterns: graceful degradation, quota protection, resilience by default.

**Stack:** PostgreSQL RLS, Rate Limiting, Input Sanitization, Wireshark, Splunk, Burp Suite, Metasploit

---

## Featured Work

### Multi-Agent Market Research Platform
**200x faster research through strategic coordination**

[Live Demo](https://multi-agent-research-frontend.vercel.app) | [Code](https://github.com/Exalt24/multi-agent-research)

Seven specialized agents orchestrated by LangGraph, turning **6-8 hour manual research into 1.75 minutes**.

The breakthrough was implementing **strategic guidance pattern** where the coordinator generates JSON objectives used by all agents, eliminating unreliable dynamic routing.

Parallel execution (Research and Financial Intel concurrent, then Content and Visualization) delivers **30% speedup** while `operator.add` ensures memory-safe state merging.

**Key insights:**

Accurate token counting matters. Migrating from length estimation (22.9% error) to `tiktoken` with model auto-detection revealed we were undercounting by **72% in some agents**.

Human-in-the-Loop quality gates with keyword detection, 5-min timeouts, and graceful continuation taught me workflows should catch issues automatically, not block progress.

Redis caching protects Tavily's 500/month quota while delivering **5-10x speedups**.

---

### Enterprise RAG Knowledge Base
**67.7% to 85%+ accuracy through advanced retrieval**

[Live Demo](https://enterprise-rag-knowledge-base.vercel.app) | [Code](https://github.com/Exalt24/enterprise-rag-knowledge-base)

Production RAG system implementing **5 retrieval strategies**: Hybrid Search (vector 70% plus BM25 keyword 30%), HyDE, Multi-Query, Parent-Child, Cross-Encoder Reranking.

Full-stack deployment (FastAPI and Next.js) with Redis caching (**100x speedup**), 2-tier LLM fallback (Ollama to Groq), and **100% reliability** across 19 test queries.

**Key insight:**

Retrieval quality beats LLM quality. A great LLM with poor retrieval hallucinates, but decent LLM with excellent retrieval gives accurate answers.

Migrated from Chroma to Qdrant Cloud for **2x performance**. Sometimes best optimization is architectural (remote vs local storage) not code-level.

Optimized for **512MB RAM** through strategic cloud API usage while maintaining local dev capabilities.

---

### AutoFlow Pro
**Distributed browser automation with sub-100ms monitoring**

[Live Demo](https://autoflow-pro.vercel.app/) | [Code](https://github.com/Exalt24/autoflow-pro)

Production-ready browser automation platform with visual drag-and-drop workflow builder featuring **23 step types**.

Distributed job processing with BullMQ and Redis achieves **sub-100ms WebSocket latency** for real-time monitoring.

Cron scheduling, automatic failure recovery, and Playwright browser pooling handle production workloads.

**What I learned:**

Built this to understand distributed systems architecture. Coordinating Playwright execution across workers while providing instant user feedback taught me WebSocket plus job queue patterns.

Enterprise security through RLS (multi-tenant database isolation), rate limiting (100 req/15min), and input sanitization.

Free-tier deployment (Vercel, Render, Supabase, Upstash, R2) maintaining **sub-3s page loads** and **sub-500ms API responses** proves constraints drive better architecture.

---

### NFT Trading Platform
**52 contract plus 50+ integration tests for production confidence**

[Code](https://github.com/Exalt24/NFT-Trading)

Full-stack NFT marketplace built in October 2025 while learning Solidity from scratch.

ERC-721 smart contracts with **batch minting** (up to 20 NFTs), royalty management, real-time WebSocket trading feeds, and IPFS metadata storage.

Analytics dashboard with Recharts tracking trading volume and creator metrics.

**What I learned:**

Comprehensive testing demonstrates production readiness with **52 smart contract tests plus 50+ integration tests** covering complete lifecycle.

Built to understand Web3 properly through hands-on implementation, not just tutorials.

Gas optimization taught me efficiency matters when users pay per operation.

---

*More projects:* [**Blockchain Explorer**](https://github.com/Exalt24/Blockchain-Explorer) (8-10x performance via LRU cache), [**MiniWorld**](https://github.com/Exalt24/Miniworld) (Web3 game with TypeScript SDK), [**Math Problem Generator**](https://math-problem-generator-one.vercel.app/) (Gemini AI education platform)

---

## Technical Arsenal

### AI & RAG
LangGraph, LangChain, Multi-Agent Systems, RAG Architecture, Vector Databases (Qdrant, Chroma), Hybrid Search, Cross-Encoder Reranking, Human-in-the-Loop (HITL), Prompt Engineering, FastAPI, Sentence Transformers

### Blockchain & Web3
Solidity, Hardhat, ethers.js, OpenZeppelin, IPFS, Smart Contract Testing, Gas Optimization, Event Indexing

### Security
PostgreSQL RLS, Rate Limiting, Input Sanitization, Secure Authentication, Wireshark, Splunk, Burp Suite, Metasploit

### Full-Stack Development
**Frontend:** React, Next.js, Vue.js, TypeScript, JavaScript, Vite, Tailwind CSS, HTML5, CSS3

**Backend:** Node.js, Fastify, Express, Django, Django REST Framework, Python, Ruby on Rails, Java

### Distributed Systems
BullMQ, Redis, WebSocket, Socket.IO, Real-time Monitoring, Job Queue Architecture, Caching Strategies

### Infrastructure
Docker, Git, Vercel, Render, AWS, Linux, Supabase, PostgreSQL, MongoDB, SQLite, Firebase, Cloudflare R2, AWS S3

### Browser Automation
Playwright, Puppeteer, Workflow Orchestration, Distributed Execution

### Additional
Mobile (React Native, Flutter), Game Development (Unity, Godot), Algorithm Visualization

---

**Rapid Learning**

Proven track record learning under pressure: Rails and Vue.js in 3-day cycles at ChatGenie internship, then Solidity and Web3 in October 2025, followed by Playwright, BullMQ, and distributed systems in November 2025, then LangGraph and multi-agent orchestration in December 2025.

---

## Let's Build

Building something interesting? Want to talk about multi-agent orchestration, smart contract architecture, or how to actually deploy on free-tier infrastructure without compromising quality?

I'm shipping code from Cebu and open to remote opportunities.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-dacruz.vercel.app-0ea5e9?style=for-the-badge&logo=vercel&logoColor=white)](https://dacruz.vercel.app) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dacruz24) [![Email](https://img.shields.io/badge/Email-danielalexiscruz.pro@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:danielalexiscruz.pro@gmail.com)

---

```
┌─────────────────────────────────────────┐
│  "Production-grade results,             │
│   free-tier constraints."               │
└─────────────────────────────────────────┘
```

*Currently exploring: Multi-agent workflow optimization, RAG retrieval techniques, Web3 gaming mechanics*

</div>
