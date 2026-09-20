# Hi, I'm Muhammad Hassaan

### AI Research Engineer & Full Stack Developer

I build reinforcement learning evaluation environments for frontier models, and the backend systems around them: APIs, agentic pipelines, document intelligence, and full-stack applications. I also contribute upstream to the AI evaluation and data infrastructure projects I depend on.

![Profile views](https://komarev.com/ghpvc/?username=hassaanch23&color=blueviolet&style=flat) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/imhassaan04) [![Portfolio](https://img.shields.io/badge/Portfolio-Visit-8A2BE2?style=flat&logo=vercel)](https://imhassaan04.vercel.app)

---

## Currently

- **AI Research Engineer (RL) @ Tensium (UK)** — building reinforcement learning evaluation environments for frontier AI models; designing tasks, verifiers, and sandboxed eval pipelines
- **AI & Full Stack Engineer (Contract) @ Atlast** — Barcelona (Remote)

### Focus Areas

- RL evaluation environments for frontier models
- Agentic systems (LangChain / LangGraph, tool-calling agents)
- Scalable backend systems and production LLM pipelines
- Document intelligence, RAG, and OCR

---

## Open Source Contributions

I contribute to AI evaluation and data infrastructure projects, focusing on correctness bugs that fail silently — code that returns the wrong answer without raising an error.

**Merged**

- **[Apache DataFusion #25402](https://github.com/apache/datafusion/pull/25402)** — Order-insensitive aggregates carried ordering fields into their partial state schema, so `min(v ORDER BY k)` in a grouped query failed with an Arrow schema mismatch. Fixed at the builder so the inconsistent state never exists.
- **[DeepEval #2916](https://github.com/confident-ai/deepeval/pull/2916)** — Three silent benchmark mis-scoring bugs. MathQA's answer schema only allowed `a`–`d` while the dataset has five options, making ~20% of it unscoreable even for a perfect model. Also a DROP comma-delimiter corruption, and a BigBenchHard batch path truncating `(A)` to `(A`.
- **[DeepEval #2849](https://github.com/confident-ai/deepeval/pull/2849)** — `UnboundLocalError` crash when a document chunked to zero pieces, masking the real error message.
- **[InsForge #1786](https://github.com/InsForge/InsForge/pull/1786)** — Concurrency bug: a credential read racing a cache invalidation repopulated the cache it was meant to clear.
- **[InsForge #1749](https://github.com/InsForge/InsForge/pull/1749)** — OpenAI spec compliance: the gateway rejected valid assistant messages carrying `tool_calls` without `content`, breaking multi-turn agent tool loops.
- **[InsForge #1740](https://github.com/InsForge/InsForge/pull/1740)** — Token usage reporting for streaming chat completions.
- **[Opik (Comet ML) #8120](https://github.com/comet-ml/opik/pull/8120)** — Removed an orphaned CI workflow that was broken on the project's default branch.

**Co-authored** — landed inside maintainers' release PRs

- **[Instructor #2597](https://github.com/567-labs/instructor/pull/2597)** — Docs lint failures, 34 down to 18. Shipped in Instructor 1.17.0.
- **[TraceRoot #1593](https://github.com/traceroot-ai/traceroot/pull/1593)** — Anthropic model pricing: fast-mode rate cards and dot-notation model IDs.

**Open** — PRs in review across Langfuse, LiteLLM, EleutherAI's lm-evaluation-harness, Hugging Face evaluate, Future AGI, Parea, Ragas, and Graphify.

---

## Tech Stack

**Backend & AI**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)

**Data & Infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge)

---

## Experience

### AI Research Engineer (RL) — Tensium (UK)
- Build **RL evaluation environments** for frontier models
- Design tasks, verifiers, and sandboxed eval pipelines
- Tested against **Claude** and **GPT** on the HUD platform

### AI & Full Stack Engineer (Contract) — Atlast, Barcelona (Remote)
Aug 2026 – Present

### AI Developer — Techfy, Lahore, Pakistan (Remote)
- Built a **financial document intelligence platform** with Azure Document Intelligence, FastAPI, OCR, and structured extraction
- Integrated **LLM chatbots**, **AWS Cognito** authentication, and **Stripe** payments

### Software Engineer — Mercor
- Collaborated with global AI teams including **Anthropic** on AI model training and evaluation
- Designed scalable backend services, database schemas, and FastAPI-based APIs for production AI infrastructure

### Software Engineer — AfterQuery
- Evaluated and optimized AI models

---

## Education

**BS Software Engineering** — FAST National University of Computer and Emerging Sciences, Lahore, Pakistan

---

## GitHub Analytics

<div align="center">

<img height="170" src="https://github-stats-extended.vercel.app/api?username=hassaanch23&show_icons=true&include_all_commits=true&hide_rank=true&hide=stars&theme=tokyonight&hide_border=true" alt="GitHub stats" />
<img height="170" src="https://github-stats-extended.vercel.app/api/top-langs/?username=hassaanch23&layout=compact&hide=jupyter%20notebook,html&theme=tokyonight&hide_border=true" alt="Top languages" />

<img src="https://trophy.ryglcloud.net/?username=hassaanch23&theme=tokyonight&no-frame=true&row=1&column=-1&rank=SECRET,SSS,SS,S,AAA,AA,A,B&margin-w=8" alt="GitHub trophies" />

<!-- Activity graph: the upstream host (github-readme-activity-graph.vercel.app) has returned
     402 DEPLOYMENT_DISABLED since Aug 2026. Uncomment once it is back:
<img src="https://github-readme-activity-graph.vercel.app/graph?username=hassaanch23&theme=tokyo-night&hide_border=true&area=true" alt="Contribution activity graph" />
-->

</div>

---

## Connect

- **Portfolio:** https://imhassaan04.vercel.app
- **LinkedIn:** https://linkedin.com/in/imhassaan04
- **GitHub:** https://github.com/hassaanch23
- **Email:** imhassaan04@gmail.com

Open to collaborations in AI, backend, and full-stack development.
