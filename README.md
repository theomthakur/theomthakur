<h1 align="center">Om Thakur</h1>

<p align="center">
  <b>Software engineer | applied AI and full stack</b>
</p>

<p align="center">
  <a href="https://theomthakur.github.io/portfolio"><img src="https://img.shields.io/badge/Portfolio-1A1815?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/theomthakur"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ot2131@nyu.edu"><img src="https://img.shields.io/badge/Email-C5221F?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://rdcu.be/dkCLA"><img src="https://img.shields.io/badge/Published_Research-00695C?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Research"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/NYU-MS_Computer_Engineering_2026-57068C?style=flat-square&logo=academia&logoColor=white" alt="NYU"/>
  <img src="https://img.shields.io/badge/New_York_City-1A1815?style=flat-square&logo=googlemaps&logoColor=white" alt="NYC"/>
  <img src="https://img.shields.io/badge/Open_to-Full--time_roles_across_the_US-2EA44F?style=flat-square" alt="Open to work"/>
  <img src="https://img.shields.io/badge/Published-PyPI_%26_npm-3775A9?style=flat-square&logo=pypi&logoColor=white" alt="Published packages"/>
</p>

---

## About

I'm a software engineer based in **New York**, with an MS in Computer Engineering from
**NYU**. I build applied AI tools and full-stack applications, from understanding the user’s
problem to building, testing and explaining the finished workflow.

At **NYU Langone Health**, I contributed AWS Bedrock and evaluation integrations to a
collaborative research-literature RAG project. Before that, I spent two years at **4iBiz**,
owning customer-facing features end to end for SaaS products used by **20,000+ users**.

My recent projects focus on useful agent workflows: processing invoices, answering questions
with sources, coordinating work in Slack and purchasing within explicit spending rules.
I also publish tools for evaluating models and replaying agent runs in tests.

---

## Recent projects

<table>
<tr>
<td width="50%" valign="top">

### Invoice Desk
An invoice-processing workspace with separate reader, validator, approver and critic agents.
It checks invoices against mock inventory, routes problems to human review and records
**simulated payments** only after code checks the payment rules. Includes department handoffs,
analytics and readable reports.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

<a href="https://github.com/theomthakur/invoice-desk"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Invoice Desk source code and local demo instructions"/></a>

</td>
<td width="50%" valign="top">

### PolicyPilot
Ask questions about a PDF library and open the original page behind an answer.
The agent can search again, read more evidence or ask for clarification. Includes document
uploads, citation checks and an optional Keycloak sign-in stack with per-user access.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<a href="https://youtu.be/njw7qmk8aTQ"><img src="https://img.shields.io/badge/Demo_video-2EA44F?style=for-the-badge&logo=youtube&logoColor=white" alt="PolicyPilot demo video"/></a>
<a href="https://github.com/theomthakur/policypilot"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="PolicyPilot source code and setup"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### AfterOrder
A purchasing workflow that receives a signed Shopify order, compares supplier offers and
recovers when the first supplier runs out of stock. Merchant rules limit what agents can
buy, and signed dispatch evidence controls **testnet payment** release.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Shopify](https://img.shields.io/badge/Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Monad testnet](https://img.shields.io/badge/Monad_testnet-836EF9?style=flat-square)

<a href="https://github.com/theomthakur/afterorder"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="AfterOrder source code and integration evidence"/></a>

</td>
<td width="50%" valign="top">

### SafeSlackForce
A team-built incident-coordination prototype inside Slack. A Commander delegates to four
specialists to organize tasks, review evidence, notify people and prepare handoff reports.
A dashboard shows agent activity and unresolved work. Demonstrated with synthetic incidents.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Slack Bolt](https://img.shields.io/badge/Slack_Bolt-4A154B?style=flat-square&logo=slack&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-333333?style=flat-square)

<a href="https://youtu.be/xYKxVzRwwRE"><img src="https://img.shields.io/badge/Demo_video-2EA44F?style=for-the-badge&logo=youtube&logoColor=white" alt="SafeSlackForce demo video"/></a>
<a href="https://github.com/theomthakur/safeslackforce"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="SafeSlackForce source code and setup"/></a>

</td>
</tr>
</table>

---

## Published packages

Installable, versioned, and open to anyone who wants to check the work.

<table>
<tr>
<td width="50%" valign="top">

### benchtrace
Evaluate LLM agents from saved run traces. Compare answer quality, retrieval, latency and
cost, then generate an HTML report. Statistical checks help distinguish an improvement from
variation between runs.

```bash
pip install benchtrace
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyPI](https://img.shields.io/pypi/v/benchtrace?style=flat-square)
![mypy](https://img.shields.io/badge/mypy-strict-2EA44F?style=flat-square)

<a href="https://pypi.org/project/benchtrace/"><img src="https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white" alt="PyPI"/></a>
<a href="https://github.com/theomthakur/benchtrace"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

### agentcassette
Record an agent run and replay its model interactions in tests without new API calls.
It stores messages, tool calls and results, and reports where a replay differs from the
recording. Supports multiple provider formats with zero runtime dependencies.

```bash
npm install --save-dev agentcassette
```

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![npm](https://img.shields.io/npm/v/agentcassette?style=flat-square)
![Dependencies](https://img.shields.io/badge/dependencies-0-2EA44F?style=flat-square)

<a href="https://www.npmjs.com/package/agentcassette"><img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"/></a>
<a href="https://github.com/theomthakur/agentcassette"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
</table>

---

## Applied AI

<table>
<tr>
<td width="50%" valign="top">

### EDGAR Lens
An agentic system over SEC 10-K filings that **grades its own work**. It drafts citation-backed
claims, scores its own citation precision with Jaccard token overlap, and escalates the
retrieval strategy from focused to broad until it clears a quality bar. Recorded evaluation results and their limits are documented in the repository.

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

<a href="https://github.com/theomthakur/edgar-lens"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

### Mandate
Agentic commerce with a governance layer. An agent has to produce a **checkable reason** and
clear policy before it can spend anything, and the decision is written to a log either way.
Policy hashes anchored on-chain; real payment rails in sandbox. Built at a hackathon.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/Neon-00E599?style=flat-square&logo=postgresql&logoColor=white)
![Web3](https://img.shields.io/badge/viem-2E2E2E?style=flat-square&logo=ethereum&logoColor=white)

<a href="https://raingentic-team10.vercel.app"><img src="https://img.shields.io/badge/Live_demo-2EA44F?style=for-the-badge&logo=vercel&logoColor=white" alt="Demo"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Answerlight
Drafts a defendant's Answer to a civil complaint and ties **every** reply back to the exact
paragraph it answers. The tie is verified outside the model in plain code, not trusted from it,
so a reviewer can check the draft against the source complaint.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

<a href="https://answer-light.vercel.app"><img src="https://img.shields.io/badge/Live_demo-2EA44F?style=for-the-badge&logo=vercel&logoColor=white" alt="Demo"/></a>
<a href="https://github.com/theomthakur/answer-light"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

### Chartproof
Paste a messy clinical visit note, get a structured SOAP note plus ICD-10 and CPT codes. Every
code's justification is checked in plain code against the clinician's own words, and identifiers
are stripped before the model sees anything. Nothing is final until a human approves it.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

<a href="https://kinstead-clinician-copilot.vercel.app"><img src="https://img.shields.io/badge/Live_demo-2EA44F?style=for-the-badge&logo=vercel&logoColor=white" alt="Demo"/></a>
<a href="https://github.com/theomthakur/kinstead-clinician-copilot"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### DealForge
Multi-agent negotiation. A buyer agent bargains **in parallel** against ten seller agents with
distinct strategies, streamed live over SSE, with per-agent evaluation and a hard turn limit so
negotiations actually terminate.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

<a href="https://github.com/theomthakur/negotiation_ai"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

### Understudy
An LLM discovers a banking workflow once and compiles the successful run into a reviewed,
typed capability. Replay is deterministic with **zero model calls**; policy checks guard both
discovery and replay, and irreversible actions transfer control to a human through a lease.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

<a href="https://github.com/theomthakur/understudy"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
</table>

---

## Systems, backend and ML infrastructure

<table>
<tr>
<td width="50%" valign="top">

### raftlab
A pure Raft state machine with a deterministic fault simulator. A failing `u64` seed reproduces
the same partitions, crashes, persistence acknowledgements, messages, and bytes on every run;
all five Raft safety properties are checked **after every simulated step**.

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

<a href="https://github.com/theomthakur/raftlab"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

### StreamBridge
A high-performance distributed message queue. Async Rust broker core on Tokio and DashMap, with
a Go REST API bridged over cgo/FFI. Benchmarked with Criterion at **8.9M msg/sec**, p99 latency
167–208ns in-process.

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-1A1815?style=flat-square)

<a href="https://github.com/theomthakur/StreamBridge-High-Performance-Distributed-Message-Queue"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Fraud Guard
Real-time risk scoring over streaming transactions. Kafka ingestion, Spark feature engineering,
XGBoost scoring, with **Evidently drift detection and automatic rollback** on threshold breach.
Locust-tested to 250 req/sec at p99 ≤ 660ms.

![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![Kubernetes](https://img.shields.io/badge/K8s-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

<a href="https://github.com/theomthakur/Fraud-Guard"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

### Chest X-Ray Detection
End-to-end MLOps for YOLO chest X-ray detection: **Ray** distributed training, **MLflow**
tracking with hyperparameter sweeps, ONNX conversion, **Triton** serving with canary rollouts
and automated retraining on Kubernetes via ArgoCD.

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Ray](https://img.shields.io/badge/Ray-028CF0?style=flat-square&logo=ray&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Triton](https://img.shields.io/badge/Triton-76B900?style=flat-square&logo=nvidia&logoColor=white)

<a href="https://github.com/theomthakur/ece-gy-9183-group19"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### BidWave
A reactive real-time auction service. Spring WebFlux with R2DBC and Lettuce, using a
**single-pass Redis Lua script** to make bid placement atomic and eliminate the read-then-write
race. Testcontainers integration tests prove exactly one winner under concurrent contention.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_WebFlux-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

<a href="https://github.com/theomthakur/bidwave"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

### parqet
A columnar SQL engine over Parquet, written from scratch in Rust. It has its own typed planner,
switchable optimizer rules, vectorized Arrow operators, row-group/page pruning, and disk spilling.
Correctness is checked by running the same generated queries against **DuckDB as an oracle**.

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Apache Arrow](https://img.shields.io/badge/Apache_Arrow-1293D8?style=flat-square&logo=apache&logoColor=white)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square)

<a href="https://github.com/theomthakur/parqet"><img src="https://img.shields.io/badge/Source_code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
</table>

---

## Toolkit

**AI & LLMs**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/Bedrock-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_%26_Vector_Search-5A189A?style=for-the-badge)
![Evaluation](https://img.shields.io/badge/Model_Evaluation-8A1C1C?style=for-the-badge)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & Frontend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Data & Infrastructure**

![Spark](https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)

---

## Languages I actually write

<p align="center">
  <img width="46%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=theomthakur&theme=transparent" alt="Languages by repository"/>
  <img width="46%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=theomthakur&theme=transparent" alt="Languages by commit"/>
</p>

---

## Research

**[Solar Panel Damage Detection and Localization of Thermal Images](https://rdcu.be/dkCLA)**
*Journal of Failure Analysis and Prevention*, August 2023
A YOLO-based thermal-imaging framework for fault detection, 69% mAP across 1,500+ curated images.

---

<p align="center">
  <a href="https://theomthakur.github.io/portfolio"><img src="https://img.shields.io/badge/theomthakur.github.io%2Fportfolio-1A1815?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:ot2131@nyu.edu"><img src="https://img.shields.io/badge/ot2131%40nyu.edu-C5221F?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>
