<div align="center">

<a href="https://chintan-patel-ai.netlify.app/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1200&color=0D9488&center=true&vCenter=true&width=900&lines=Applied+AI+Engineer;Full-Stack+AI+Systems;ML+%C2%B7+RAG+%C2%B7+Agents+%C2%B7+Cloud;Reviewable+%C2%B7+Evaluated+%C2%B7+Production-Minded" alt="Chintan Patel — Applied AI Engineer · Full-Stack AI Systems" />
</a>

# Chintan Patel

### Applied AI Engineer · Full-Stack AI Systems

I build AI systems from **models and retrieval through APIs, product interfaces, cloud delivery, evaluation, observability, and human-review workflows**.

📍 Calgary, Alberta, Canada &nbsp;·&nbsp; 🎯 Open to Applied AI Engineer, Machine Learning Engineer, and Full-Stack AI Engineer opportunities across Canada

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0D9488?style=for-the-badge&logo=google-chrome&logoColor=white)](https://chintan-patel-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintan-patel-ai/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:patel.chintan380@gmail.com)

</div>

---

## Profile

Computer Science and Engineering graduate with more than three years of software-development and client-delivery experience, plus a completed **Post-Diploma Certificate in Integrated Artificial Intelligence from SAIT**.

My focus is applied AI systems where outputs need to be **evaluated, evidence-backed, reviewable, operationally reliable, and honest about system boundaries**. I work across machine learning, RAG, agentic applications, APIs, frontend integration, databases, asynchronous workflows, testing, containerization, cloud deployment, and observability.

> **Primary role family:** Applied AI Engineer · Machine Learning Engineer · Full-Stack AI Engineer  
> **Supporting strengths:** Backend AI · RAG / Retrieval · AI Agents · Cloud / Reliability · Human-in-the-Loop Systems

---

## Engineering Evidence

| Project | Selected proof | Delivery state |
|---|---|---|
| **RegImpact AI** | Hybrid retrieval · pgvector · RBAC · human approval · async workers · OIDC · Bicep | **v0.5.0 verified Azure staging release** |
| **TriageAI / SympDirect** | 273-feature LightGBM workflow · 70.37% Macro F1 · 0.68% unsafe ESI 3→5 · clinician review | Verified local clinical decision-support workflow |
| **PolicyGPT Enterprise** | 230 backend tests · 128 frontend tests · 16-case evaluation · evidence gating · citations | **v0.3.0 verified local release** |
| **Product Finder AI Agent** | Google ADK · Gemini tool use · deterministic filtering · FastAPI · React | **Cloud Run backend + Netlify frontend** |
| **ResumeIQ** | PDF/DOCX/TXT parsing · semantic JD matching · multi-signal review · human oversight | Azure-hosted portfolio demo |

---

## Featured Systems

### 🏛️ RegImpact AI

#### Regulatory Change Impact & Controls Assurance Platform · v0.5.0

An evidence-linked regulatory intelligence platform that versions source documents, detects section-level changes, identifies obligation candidates, retrieves relevant controls, and routes consequential or uncertain findings to authorized reviewers.

- FastAPI + Next.js application architecture
- PostgreSQL system of record with **pgvector + full-text hybrid retrieval**
- Versioned ingestion, SHA-256 identity, deterministic section-change detection, and evidence-linked obligation analysis
- Redis + Dramatiq asynchronous processing with transactional outbox, retries, leases, and dead-letter handling
- Tenant-aware RBAC, mandatory reviewer rationale, creator/approver separation, and append-only audit history
- Structured logs, metrics, W3C trace context, Application Insights, and Log Analytics
- **GitHub Actions + OIDC + Bicep + Azure Container Apps / Jobs**
- Verified **v0.5.0 Azure staging release** with migration-gated promotion and immutable deployment evidence
- Current staging lifecycle is **ephemeral by default** after validation and evidence capture to avoid unnecessary idle cost

`Python` `FastAPI` `Next.js` `PostgreSQL` `pgvector` `Redis` `Dramatiq` `Docker` `Bicep` `Azure`

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/regimpact-ai)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/regimpact-ai)
[![Release](https://img.shields.io/badge/Release-v0.5.0-0078D4?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/chintan-02/regimpact-ai/releases/tag/v0.5.0)

> **Scope:** Verified Azure staging, not approved production. LangGraph and AKS/Kubernetes remain planned; the regulatory classifier is not yet trained and promoted.

---

### 🩺 TriageAI / SympDirect

#### Review-First Clinical Intake & ESI Care-Routing Decision Support

A safety-aware clinical decision-support workflow connecting clinician notes and structured intake to ESI 3/4/5 prediction, explicit safety escalation, clinician review, audit evidence, and PDF reporting.

- **273-feature** LightGBM V2 model contract
- Clinical NLP with editable fields, evidence snippets, safety cues, and missing-data warnings
- Explicit safety escalation outside the classifier
- Clinician accept, override, and needs-review workflows
- React/TypeScript frontend, FastAPI backend, SQLAlchemy persistence
- **96 backend tests** and **52 frontend tests**

| Accuracy | Macro F1 | Weighted F1 | ESI 5 F1 | Unsafe ESI 3→5 |
|---:|---:|---:|---:|---:|
| **78.32%** | **70.37%** | **78.88%** | **54.70%** | **0.68%** |

`Python` `LightGBM` `FastAPI` `React` `TypeScript` `SQLAlchemy`

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/triageai-esi-care-routing)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/triageai)

> **Scope:** Educational portfolio decision support. It is not diagnostic, clinically validated, or a replacement for clinician judgment.

---

### 📚 PolicyGPT Enterprise

#### Evidence-Gated Policy RAG System · v0.3.0

A verified local RAG release designed around durable document identity, evidence sufficiency, page citations, unsupported-question rejection, controlled fallback, and operational readiness.

- SHA-256 duplicate prevention and PostgreSQL document lifecycle
- SentenceTransformers + persistent ChromaDB retrieval
- Evidence gating, answerability diagnostics, page-level citations, and citation-only fallback
- FastAPI + Next.js + SQLAlchemy + Alembic
- Structured logs, request IDs, liveness, and dependency readiness
- **230 backend tests**, **128 frontend tests**, and a controlled **16-case evaluation**

`Python` `FastAPI` `Next.js` `PostgreSQL` `SentenceTransformers` `ChromaDB` `Docker Compose`

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/policygpt-enterprise)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/policygpt-enterprise)
[![Release](https://img.shields.io/badge/Release-v0.3.0-6D28D9?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/policygpt-enterprise/releases/tag/v0.3.0)

> **Scope:** Verified local release. No claim of cloud production, commercial adoption, authentication/RBAC, or generated-answer accuracy from the provider-disabled evaluation.

---

## Additional Verified Projects

### 🔎 Product Finder AI Agent
Grounded product-search agent using **Google ADK + Gemini** for intent interpretation while deterministic Python remains authoritative for category, price, product-name, and availability filtering.

- FastAPI backend packaged in a non-root Docker container
- Backend deployed to **Google Cloud Run**
- React frontend deployed to **Netlify**
- Gemini API key stored in **Google Secret Manager**

[Live Demo](https://product-finder-adk-chintan.netlify.app/) · [Repository](https://github.com/chintan-02/product-finder-adk-agent)

### 📄 ResumeIQ
Privacy-aware resume intelligence and human decision-support workflow for multi-format parsing, baseline classification, semantic JD matching, skill-gap analysis, writing review, and recruiter workflows.

- PDF, DOCX, and TXT parsing
- TF-IDF / scikit-learn foundations
- Semantic job-description matching and normalized skill intelligence
- Streamlit interface with FastAPI / persistence foundations
- Azure-hosted portfolio demonstration

[Live Demo](https://resume-classifier-chintan.azurewebsites.net/) · [Repository](https://github.com/chintan-02/smart-resume-classifier) · [Case Study](https://chintan-patel-ai.netlify.app/case-studies/resumeiq)

---

## Current Engineering Stack

### AI / ML / Retrieval

`scikit-learn` · `LightGBM` · `XGBoost` · `Pandas` · `NumPy` · `SentenceTransformers` · `ChromaDB` · `pgvector` · `TF-IDF` · `SHAP`

### Backend / Data

`Python` · `FastAPI` · `Pydantic` · `SQLAlchemy` · `Alembic` · `PostgreSQL` · `Redis` · `Dramatiq`

### Product

`React` · `Next.js` · `TypeScript` · `JavaScript` · `Streamlit`

### Cloud / Delivery / Reliability

`Docker` · `Docker Compose` · `GitHub Actions` · `Azure Container Apps` · `Azure App Service` · `Bicep` · `Google Cloud Run` · `Secret Manager` · `Application Insights`

---

## Final Two Portfolio Builds — Planned

I am intentionally limiting the portfolio to **two additional major projects**. These are roadmap items, not completed experience.

### 1. AssetPulse AI — next

**Industrial Asset Intelligence & MLOps Platform**

Goal: close the remaining ML-engineering platform gap with a project centered on multivariate industrial telemetry, time-series modeling, predictive maintenance, remaining useful life, model lifecycle, and production ML operations.

Planned learning / implementation areas:

`PyTorch` · `TensorFlow / Keras` · `Databricks` · `PySpark` · `Delta Lake` · `MLflow` · time-series ML · anomaly detection · drift monitoring · batch + real-time inference · controlled retraining

> **Status:** Planned. None of these planned capabilities are claimed as current implementation until verified in the repository.

### 2. LedgerGuard AI — after AssetPulse

**Real-Time Transaction Risk & Financial Operations Platform**

Goal: add a fintech-specific system that demonstrates financial transaction engineering, ML risk scoring, distributed messaging, operational reliability, and auditability.

Planned focus:

FastAPI transaction APIs · PostgreSQL ledger integrity · idempotency · reconciliation · RabbitMQ · transactional outbox · retries / DLQ · LightGBM / XGBoost risk scoring · SHAP · analyst review · OpenTelemetry · load testing · Azure · AKS/Kubernetes after base-system verification

> **Status:** Planned. The project will not be presented as implemented until the corresponding evidence exists.

---

## Education

| Credential | Institution | Completion |
|---|---|---|
| **Post-Diploma Certificate, Integrated Artificial Intelligence** | SAIT · Calgary, Canada | August 2026 |
| **Professional Development Certificate, Supply Chain Management & Logistics** | MacEwan University · Edmonton, Canada | December 2025 |
| **Bachelor of Engineering, Computer Science and Engineering** | Gujarat Technological University (ITM Universe) · India | August 2019 |

---

## Engineering Principles

- **Evidence before confidence** — evaluation, citations, metrics, and explicit uncertainty matter.
- **Ship the whole system** — model logic is only one part of APIs, data, product workflow, deployment, and reliability.
- **Keep people in consequential decisions** — automation should support authorized human judgment in high-impact workflows.
- **Separate implemented from planned** — roadmap technologies do not become resume skills until they are actually built and verified.

---

## Let's Connect

I am open to opportunities across Canada in **Applied AI Engineering, Machine Learning Engineering, Full-Stack AI Engineering, AI Software Development, and backend/platform-oriented AI roles**.

[![Portfolio](https://img.shields.io/badge/Portfolio-chintan--patel--ai-0D9488?style=flat-square&logo=google-chrome&logoColor=white)](https://chintan-patel-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Chintan_Patel-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintan-patel-ai/)
[![GitHub](https://img.shields.io/badge/GitHub-chintan--02-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02)
[![Email](https://img.shields.io/badge/Email-patel.chintan380%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:patel.chintan380@gmail.com)

<div align="center">

---

<i>Building evaluated AI systems from models and retrieval to APIs, products, cloud infrastructure, and reliable delivery.</i>

</div>
