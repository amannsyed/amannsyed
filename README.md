# Aman Syed

**AI/ML Engineer & Data Scientist** — building production AI platforms, hybrid search systems, and LLM pipelines on AWS

- 🏢 AI/ML Engineer at **Penta Group**, London
- 🎓 MSc Statistics with Data Science — **The University of Edinburgh**
- ☁️ Specialising in **hybrid search**, **RAG architectures**, **Synthetic AI personas**, **GPU-accelerated inference**, and **multi-agent orchestration**
- 🔧 Core stack: Python · FastAPI · PostgreSQL/pgvector · PyTorch · Docker · Vertex AI · SageMaker

[![Portfolio](https://img.shields.io/badge/Portfolio-4F46E5?logo=google-chrome&logoColor=white)](https://amannsyed.github.io/portfolio/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/amannsyed)

---

## What I've shipped

- **Penta Brain** — hybrid AI search combining pgvector (EmbeddingGemma-300m, 768-dim HNSW), PostgreSQL full-text search, and GLiNER NER with Reciprocal Rank Fusion, SSE-streamed chat, citation grounding, two-tier semantic cache, and JWT rate-limited FastAPI serving
- **MCP Server** — 5 AI-client tools (hybrid search, vector search, entity search, RAG Q&A) over SSE with JWT auth, enabling external AI agents to query the article knowledge base
- **GPU NLP Pipeline** — 2–3 million daily articles via SQS-driven GPU workers running GLiNER NER and EmbeddingGemma-300m; 30-day SHA256 deduplication, HNSW-indexed pgvector, AWS ECS
- **Synthetic Stakeholders** — AI platform for persona simulation, artifact-grounded conversations, multi-persona debates, semantic search, and belief-state learning; 18 FastAPI routes, OpenAI Responses API streaming, 1,536-dim pgvector memory
- **AI Insights Narrative** — 15-endpoint FastAPI platform generating source-linked, clustered LLM narratives for media intelligence cards; async embeddings with 500 in-flight tasks, KMeans/DBSCAN/MMR selection, 1,245 pytest tests
- **Storyline Identification** — Dockerized GPT-4o API using OpenAI embeddings, UMAP, and HDBSCAN to cluster and refine narratives from up to 10,000 articles; SageMaker-compatible endpoints
- **95% reduction** in manual transcript analysis (20 hrs → under 5 min) via multi-agent NLP pipeline with 3-LLM consensus speaker extraction and 3-stage quote pipeline achieving **92% precision**
- **Sentiment Model Monitoring** — 71% weighted F1 across 33+ prompt configurations and 6 LLMs; F1/drift alerting via SES, 24 metrics persisted to PostgreSQL and S3
- **3x throughput** deploying BERT models as serverless SageMaker endpoints with dynamic batching · **5x faster** file ingestion via chunked-transfer uploads over parallel WebSockets

---

## Featured Projects

| Project | Description | Stack | Links |
|---|---|---|---|
| **Finance Flow** | Full-stack personal finance tracker with analytics, budgets, dark mode, and Google Sheets sync. Backend auto-detects 6 UK bank CSV formats via Strategy Pattern. | React · TypeScript · FastAPI · Tailwind | [Live](https://amannsyed.github.io/finance-flow/) · [Frontend](https://github.com/amannsyed/finance-flow) · [Backend](https://github.com/amannsyed/convert_transaction) |
| **Knock Knock Physio** | Production business website for a mobile physiotherapy practice — booking, WhatsApp integration, pricing, admin dashboard | React · TypeScript · Vite | [Live](https://knockknockphysio.co.uk/) · [Source](https://github.com/amannsyed/knock-knock-physio) |
| **AI Job Application Assistant** | AI assistant for resume optimisation, interview prep, and application enhancement with PDF/DOCX processing | React · TypeScript · Gemini API | [Live](https://amannsyed.github.io/ai-job-application-assistant/) · [Source](https://github.com/amannsyed/ai-job-application-assistant) |
| **AI Code Reviewer** | AI-powered code review tool — bug detection, quality assessment, and optimisation suggestions | React · TypeScript · Gemini API | [Live](https://amannsyed.github.io/ai-code-reviewer/) · [Source](https://github.com/amannsyed/ai-code-reviewer) |
| **GCP Drive Manager** | Zero-backend Google Drive manager using browser Web Crypto API for client-side JWT signing | React · TypeScript · Web Crypto API | [Live](https://amannsyed.github.io/gcp-drive/) · [Source](https://github.com/amannsyed/gcp-drive) |

---

## Tech Stack

**LLMs & Gen AI** &nbsp;·&nbsp; OpenAI GPT-4/4.1 · Google Gemini 2.5 · Anthropic Claude · Vertex AI · RAG · LLM Fine-tuning · Prompt Engineering · HuggingFace Transformers · Multi-agent Orchestration · MCP Server

**ML / NLP** &nbsp;·&nbsp; PyTorch · SentenceTransformers · GLiNER · SpaCy · BERT · Gensim · LDA/NMF · UMAP · HDBSCAN · Scikit-learn · Sentence Embeddings

**Search & Databases** &nbsp;·&nbsp; PostgreSQL (pgvector) · HNSW Indexes · Reciprocal Rank Fusion · Full-text Search (tsvector) · NER Entity Search · MySQL · MongoDB · SQLAlchemy

**Cloud (AWS)** &nbsp;·&nbsp; SageMaker · ECS · Lambda · S3 · SQS · API Gateway · CloudWatch · SSM Parameter Store · CodeBuild · CodePipeline · Vertex AI Agent Engine

**Backend & APIs** &nbsp;·&nbsp; FastAPI · Flask · Pydantic · SSE Streaming · NDJSON Streaming · Docker · Docker Compose · Poetry · pytest · CI/CD · GitHub Actions

**Frontend & Web** &nbsp;·&nbsp; React 19 · TypeScript · Vite · TailwindCSS · Recharts · Framer Motion · Voila · ipywidgets · Plotly

**Languages** &nbsp;·&nbsp; Python · SQL · TypeScript · JavaScript · R · Java

---

## Experience

**AI/ML Engineer & Data Scientist** · Penta Group, London · Oct 2024 – Present

**Financial Research Assistant** · University of Edinburgh Business School · Sep – Oct 2024

**Data Engineer Intern** · C.H. Robinson, Mumbai · Dec 2022 – Aug 2023

---

## Certifications

- Architecting with Google Compute Engine Specialization — Google Cloud
- Machine Learning Foundations: A Case Study Approach — University of Washington

---

📧 [amansyed3342@gmail.com](mailto:amansyed3342@gmail.com) &nbsp;·&nbsp; 🔗 [linkedin.com/in/amannsyed](https://linkedin.com/in/amannsyed) &nbsp;·&nbsp; 🌐 [amannsyed.github.io/portfolio](https://amannsyed.github.io/portfolio/)
