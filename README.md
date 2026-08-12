<h1 align="center">Om Thakur</h1>

<p align="center">
  <b>Software engineer — applied AI and full stack.</b><br/>
  I build the AI, then I build the thing that proves it works.
</p>

<p align="center">
  <a href="https://theomthakur.github.io/portfolio"><img src="https://img.shields.io/badge/Portfolio-1a1815?style=for-the-badge&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/theomthakur"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ot2131@nyu.edu"><img src="https://img.shields.io/badge/Email-8a1c1c?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

### About

MS in Computer Engineering from **NYU** (2026). Most recently a year at **NYU Langone Health**
building clinical AI in production: a retrieval system real physicians used, and the evaluation
framework that measured whether it was actually right. Before that, two years at an
eight-engineer startup shipping a platform to **20,000+ users**.

The thread through all of it: **anyone can demo a model. The work is proving it still holds on
the thousandth query.** Most of what I build has a deterministic verification layer sitting
under the AI, because in the domains I care about, a confident wrong answer is the expensive
failure.

Currently open to full-time roles anywhere in the US.

---

### Selected work

| Project | What it does | Live |
|---|---|---|
| **[Chartproof](https://github.com/theomthakur/kinstead-clinician-copilot)** | Clinician pastes a messy visit note; drafts a SOAP note and billing codes. Every code's justification is checked **in plain code** against the clinician's own words. Identifiers stripped before the model sees anything. | [demo](https://kinstead-clinician-copilot.vercel.app) |
| **Answerlight** | Drafts a defendant's Answer to a civil complaint and ties every reply back to the exact paragraph it answers, verified outside the model. | [demo](https://answer-light.vercel.app) |
| **Relevance Lens** | Natural-language people search with a deterministic relevance score and a grounded per-criterion match breakdown, plus a ranking-accuracy metric. | [demo](https://relevance-lens.vercel.app) |
| **Mandate** | Agentic commerce. An agent must produce a checkable reason and clear policy **before** it can spend anything, with the decision logged either way. | [demo](https://raingentic-team10.vercel.app) |
| **[EDGAR Lens](https://github.com/theomthakur/edgar-lens)** | Agentic analysis of SEC 10-K filings that scores its **own** citation precision and re-runs retrieval until it clears a quality bar. 100% citation grounding across 19 filings. | — |
| **[StreamBridge](https://github.com/theomthakur/StreamBridge-High-Performance-Distributed-Message-Queue)** | Distributed message queue. Async Rust broker core (Tokio, DashMap) with a Go REST API over cgo/FFI. Benchmarked at 8.9M msg/sec. | — |
| **[Raft-KV](https://github.com/theomthakur/Raft-KV-Raft-TLA-Verified)** | Linearizable key-value store implementing Raft — leader election, log replication, snapshots — with safety and liveness **machine-checked in TLA+**. | — |
| **[Fraud Guard](https://github.com/theomthakur/Fraud-Guard)** | Real-time risk scoring over streaming transactions. Kafka ingestion, Spark features, XGBoost, drift detection with automatic rollback. | — |
| **[BidWave](https://github.com/theomthakur/bidwave)** | Reactive auction service. Spring WebFlux + R2DBC, with a single-pass Redis Lua script making bid placement atomic so exactly one winner survives concurrent contention. | — |
| **[Eventify](https://github.com/theomthakur/Eventify-Book-and-Plan-Events-Platform)** | Event ticketing with concurrency-safe seat reservation under optimistic locking, QR check-in, and Stripe webhooks with idempotency. | — |

---

### Toolkit

**AI & LLMs** · RAG · agentic workflows · evaluation frameworks · embeddings & vector search · OpenAI · Anthropic · AWS Bedrock · Ollama · LangChain · Hugging Face

**Languages** · Python · TypeScript · Java · Rust · Go · C++ · SQL

**Backend** · FastAPI · Node/Express · Spring Boot · REST · WebSockets · SSE

**Frontend** · React · Next.js · Angular · Tailwind

**Data** · Spark · Kafka · Airflow · dbt · ETL/ELT · Parquet · Delta Lake · HPC/SLURM

**Stores** · PostgreSQL · MongoDB · Redis · TimescaleDB · DuckDB · FAISS · Chroma

**Infra** · AWS (S3, EC2, Glue, Athena, Bedrock) · Docker · Kubernetes · Terraform · GitHub Actions

---

### Research

**[Solar Panel Damage Detection and Localization of Thermal Images](https://rdcu.be/dkCLA)**
*Journal of Failure Analysis and Prevention*, August 2023.
YOLO-based thermal imaging framework, 69% mAP across 1,500+ curated images.

---

<p align="center">
  <a href="https://theomthakur.github.io/portfolio">theomthakur.github.io/portfolio</a> ·
  <a href="mailto:ot2131@nyu.edu">ot2131@nyu.edu</a>
</p>
