# 👋 Hi, I'm Xiaolei Bao (Alex)

Senior Full Stack Engineer in Stockholm, Sweden 🇸🇪. I build production LLM agents, retrieval systems and the evals that keep them honest. Open to new roles in Stockholm.

- 🤖 I build AI agents that work with real data and take real actions through external APIs
- ✅ I work on making agents reliable: deterministic calculation tools, validators, and LLM-as-judge evals
- 🏗 I architected a 13-microservice e-commerce order platform on GCP at Footway
- 🎓 10+ years in software, Master of Software Engineering from Tsinghua University

## 🔭 Current project: PermitNav

[PermitNav](https://github.com/bxljoy/permitnav) is an open-source RAG assistant for Swedish work-permit and residence rules. It answers in English or Swedish from the law, Migrationsverket's guidance and court rulings, and every claim cites its source with a date and an exact quote.

- **Hybrid retrieval:** bge-m3 vectors and BM25 in PostgreSQL (pgvector), fused with Reciprocal Rank Fusion; recall@5 rose from 0.32 to 0.53 on the development set
- **Evaluation first:** a golden set written before the code, private hold-outs run once each, and a calibrated LLM judge; 91% of answers judged correct on a fresh hold-out, 61% on a harder one
- **Deployed:** FastAPI on GCP with Terraform, deploy on merge with automatic rollback, OpenTelemetry traces, and a retrieval eval that gates every pull request

## 🛠 Skills

- **AI / LLM:** Agentic tool-use pipelines, RAG (hybrid retrieval, pgvector, bge-m3), LLM-as-judge and retrieval evals, prompt optimisation loops, MCP servers (OAuth), Claude, OpenAI, Gemini, Mistral, LiteLLM
- **Backend:** TypeScript / Node.js, NestJS, tRPC, Prisma, Java 21, Spring Boot 3, Python, FastAPI, GraphQL, REST
- **Frontend:** React 19, Next.js, React Native, Vite, TanStack Query, Tailwind CSS, shadcn/ui
- **Data:** PostgreSQL, BigQuery, Snowflake, MongoDB, Redis
- **Cloud / Infra:** GCP (Cloud Run, Pub/Sub, Cloud SQL), AWS, Terraform, Docker, GitHub Actions, OpenTelemetry, Langfuse, k6
- **Integrations:** Google Ads API, Meta Marketing API, GA4, Shopify Admin API
- **Practices:** Event-driven architecture, microservices, zero-downtime migrations, AI-assisted development with Claude Code and Codex

## 📫 Contact

- [LinkedIn](https://www.linkedin.com/in/xiaolei-bao-aa4b7b257)
- Email: bxljoy@gmail.com
