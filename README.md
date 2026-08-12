<h1 align="center">Om Thakur</h1>

<p align="center">
  <a href="https://git.io/typing-svg" target="_blank" rel="noopener noreferrer"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=8A1C1C&center=true&vCenter=true&width=680&lines=Software+engineer+%E2%80%94+applied+AI+and+full+stack;I+build+the+AI%2C+then+the+thing+that+proves+it+works;Anyone+can+demo+a+model.+The+work+is+the+thousandth+query." alt="Typing SVG" /></a>
</p>

<p align="center">
  <a href="https://theomthakur.github.io/portfolio" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Portfolio-1A1815?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/theomthakur" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ot2131@nyu.edu" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Email-C5221F?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://rdcu.be/dkCLA" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Published_Research-00695C?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Research"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MS_Computer_Engineering-NYU_2026-57068C?style=flat-square" alt="NYU"/>
  <img src="https://img.shields.io/badge/Based_in-New_York_City-1A1815?style=flat-square" alt="NYC"/>
  <img src="https://img.shields.io/badge/Open_to-Full--time_roles_across_the_US-2EA44F?style=flat-square" alt="Open to work"/>
</p>

---

## 👋 About

A year at **NYU Langone Health** building clinical AI in production: a retrieval system real
physicians used, and the evaluation framework that measured whether it was actually right.
Before that, two years at an **eight-engineer startup**, owning features end to end and shipping
to **20,000+ users**.

The thread through all of it: **anyone can demo a model, the work is proving it still holds on
the thousandth query.** Almost everything I build has a deterministic verification layer sitting
under the AI, because in the domains I care about a confident wrong answer is the expensive
failure, not a wrong one somebody notices.

---

## 🚀 Featured work

### Applied AI, with a verification layer

<table>
<tr>
<td width="50%" valign="top">

#### 🩺 Chartproof
Paste a messy clinical visit note, get a structured SOAP note plus billing codes. Every code's
justification is checked **in plain code** against the clinician's own words. Identifiers are
stripped before the model sees anything.

`Next.js` `TypeScript` `OpenAI` `Tailwind`

<a href="https://kinstead-clinician-copilot.vercel.app" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/▶_Live_demo-2EA44F?style=for-the-badge&logoColor=white" alt="Demo"/></a>
<a href="https://github.com/theomthakur/kinstead-clinician-copilot" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

#### ⚖️ Answerlight
Drafts a defendant's Answer to a civil complaint and ties every reply back to the exact
paragraph it answers. The tie is verified outside the model, not trusted from it.

`Next.js` `TypeScript` `LLM` `Grounding`

<a href="https://answer-light.vercel.app" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/▶_Live_demo-2EA44F?style=for-the-badge&logoColor=white" alt="Demo"/></a>
<a href="https://github.com/theomthakur/answer-light" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔍 Relevance Lens
Natural-language people search with a deterministic relevance score, a grounded per-criterion
match breakdown, and a ranking-accuracy metric measured against a labelled answer set.

`Next.js` `TypeScript` `Retrieval` `Evaluation`

<a href="https://relevance-lens.vercel.app" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/▶_Live_demo-2EA44F?style=for-the-badge&logoColor=white" alt="Demo"/></a>

</td>
<td width="50%" valign="top">

#### 🛡️ Mandate
Agentic commerce. An agent has to produce a checkable reason and clear policy **before** it can
spend anything, and the decision is written to a log either way.

`Next.js` `Agents` `Policy` `Payment rails`

<a href="https://raingentic-team10.vercel.app" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/▶_Live_demo-2EA44F?style=for-the-badge&logoColor=white" alt="Demo"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📊 EDGAR Lens
Agentic analysis of SEC 10-K filings that scores its **own** citation precision and re-runs
retrieval with a wider strategy until it clears a quality bar. 100% citation grounding across
19 filings, median one round to converge.

`FastAPI` `Next.js` `PostgreSQL` `Agents`

<a href="https://github.com/theomthakur/edgar-lens" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

#### 🤝 DealForge
Multi-agent negotiation. A buyer agent bargains in parallel against ten seller agents with
distinct strategies, streamed live to a dashboard, with per-agent evaluation.

`Python` `asyncio` `Next.js` `SSE`

<a href="https://github.com/theomthakur/negotiation_ai" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
</table>

### Systems and backend

<table>
<tr>
<td width="50%" valign="top">

#### ⚡ StreamBridge
Distributed message queue. Async Rust broker core (Tokio, DashMap) with a Go REST API over
cgo/FFI. Benchmarked at **8.9M msg/sec**.

`Rust` `Go` `Tokio` `Criterion`

<a href="https://github.com/theomthakur/StreamBridge-High-Performance-Distributed-Message-Queue" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

#### 🗳️ Raft-KV
Linearizable key-value store implementing Raft: leader election, log replication, snapshots,
with safety and liveness **machine-checked in TLA+**.

`Rust` `TLA+` `Consensus`

<a href="https://github.com/theomthakur/Raft-KV-Raft-TLA-Verified" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔨 BidWave
Reactive auction service. Spring WebFlux + R2DBC with a single-pass Redis Lua script making bid
placement atomic, so exactly one winner survives concurrent contention.

`Java` `Spring WebFlux` `Redis` `R2DBC`

<a href="https://github.com/theomthakur/bidwave" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

#### 🚨 Fraud Guard
Real-time risk scoring over streaming transactions. Kafka ingestion, Spark features, XGBoost,
drift detection with automatic rollback on threshold breach.

`Kafka` `Spark` `XGBoost` `Kubernetes`

<a href="https://github.com/theomthakur/Fraud-Guard" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🎟️ Eventify
Event ticketing with concurrency-safe seat reservation under optimistic locking, QR check-in,
role-based JWT auth, and Stripe webhooks with idempotency.

`Java` `Spring Boot` `PostgreSQL` `Stripe`

<a href="https://github.com/theomthakur/Eventify-Book-and-Plan-Events-Platform" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

#### 🩻 Chest X-Ray Detection
End-to-end MLOps for YOLO chest X-ray detection: Ray distributed training, MLflow sweeps, ONNX
conversion, Triton serving with canary rollouts on Kubernetes.

`PyTorch` `Ray` `MLflow` `Triton`

<a href="https://github.com/theomthakur/ece-gy-9183-group19" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
</table>

---

## 🧰 Toolkit

**AI & LLMs**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_&_Vector_Search-5A189A?style=for-the-badge)
![Evals](https://img.shields.io/badge/Model_Evaluation-8A1C1C?style=for-the-badge)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
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

## 📈 GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=theomthakur&show_icons=true&hide_border=true&title_color=8A1C1C&icon_color=8A1C1C&count_private=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=theomthakur&layout=compact&hide_border=true&title_color=8A1C1C&langs_count=8" alt="Top languages"/>
</p>

---

## 📄 Research

**[Solar Panel Damage Detection and Localization of Thermal Images](https://rdcu.be/dkCLA)**
*Journal of Failure Analysis and Prevention*, August 2023
YOLO-based thermal imaging framework, 69% mAP across 1,500+ curated images.

---

<p align="center">
  <a href="https://theomthakur.github.io/portfolio" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/theomthakur.github.io%2Fportfolio-1A1815?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:ot2131@nyu.edu" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/ot2131%40nyu.edu-C5221F?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>
