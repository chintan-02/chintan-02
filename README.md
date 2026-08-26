<div align="center">

# Chintan Patel

### Applied AI/ML Engineer · Machine Learning · NLP · GenAI/RAG

I build end-to-end AI systems that connect **reliable data, evaluated models, retrieval pipelines, typed APIs, usable interfaces, human review, and operational evidence**.

📍 Calgary, Alberta, Canada  
🎯 Open to new-graduate and junior Applied AI/ML opportunities across Canada

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0D9488?style=for-the-badge&logo=google-chrome&logoColor=white)](https://chintan-patel-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintan-patel-ai/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:patel.chintan380@gmail.com)

</div>

---

## About Me

I am a Computer Science and Engineering graduate with more than three years of software-development and client-delivery experience. In August 2026, I completed SAIT's **Post-Diploma Certificate in Integrated Artificial Intelligence**.

My work focuses on applied AI systems where model or retrieval output must be **explainable, evidence-backed, reviewable, and honest about uncertainty and limitations**. I work across machine learning, NLP, RAG, backend APIs, frontend integration, testing, containerization, and deployment.

My strongest project areas are:

- Review-first healthcare decision support with clinical NLP, safety escalation, clinician oversight, and audit evidence
- Evidence-grounded enterprise RAG with page citations, answerability controls, safe fallback, and evaluation
- Privacy-aware resume intelligence with parsing, classification, semantic matching, skill-gap analysis, and human review
- AI-agent workflows that keep deterministic business logic separate from LLM reasoning

---

## Featured Projects

### TriageAI / SympDirect

**Review-first clinical intake and ESI care-routing decision support**

- LightGBM classifier for ESI 3/4/5 with a reproducible **273-feature runtime contract**
- Clinical NLP extraction with editable fields, evidence snippets, safety cues, and missing-data warnings
- Explicit ESI 1/2 safety-rule escalation outside the classifier
- Clinician accept, override, and review workflows with audit trails and PDF reporting
- React/TypeScript frontend, FastAPI backend, SQLAlchemy persistence, and automated testing

| Accuracy | Macro F1 | Weighted F1 | ESI 5 F1 | Unsafe ESI 3→5 rate |
|---:|---:|---:|---:|---:|
| 78.32% | 70.37% | 78.88% | 54.70% | 0.68% |

`Python` `LightGBM` `FastAPI` `React` `TypeScript` `SQLAlchemy` `ReportLab`

[Repository](https://github.com/chintan-02/triageai-esi-care-routing) · [Case study](https://chintan-patel-ai.netlify.app/case-studies/triageai) · [Model article](https://chintan-patel-ai.netlify.app/writing/lightgbm-vs-xgboost)

> **Scope:** Educational and portfolio decision-support system. It is not diagnostic, clinically validated, or a replacement for clinician judgment.

---

### PolicyGPT Enterprise

**Evidence-grounded RAG for policy and compliance documents**

- PDF validation, SHA-256 duplicate prevention, lifecycle metadata, and page-aware extraction
- SentenceTransformer embeddings with ChromaDB retrieval
- Calibrated answerability, evidence gating, page citations, and unsupported-question rejection
- Citation-only fallback when generation is unavailable or unsafe
- FastAPI, Next.js, PostgreSQL, migrations, request IDs, structured logging, and readiness checks
- Verified local Docker Compose release with **230 backend tests**, **128 frontend tests**, and a controlled **16-case evaluation workflow**

`Python` `FastAPI` `Next.js` `PostgreSQL` `SentenceTransformers` `ChromaDB` `Docker Compose`

[Repository](https://github.com/chintan-02/policygpt-enterprise) · [Case study](https://chintan-patel-ai.netlify.app/case-studies/policygpt-enterprise) · [RAG evaluation article](https://chintan-patel-ai.netlify.app/writing/rag-evaluation-beyond-demo)

> **Scope:** Verified local release profile. It does not claim production authentication, multitenancy, managed cloud operations, or commercial adoption.

---

### ResumeIQ

**Privacy-aware resume intelligence and job-application decision support**

- PDF, DOCX, and TXT parsing with normalization and structured review
- TF-IDF role classification plus keyword and semantic job-description matching
- Skill-gap analysis, writing guidance, batch comparison, and reviewer notes
- Privacy-safe portfolio mode and human-reviewed recommendations
- Streamlit application with optional FastAPI, SQLite, SQLAlchemy, Docker, testing, and CI foundations

`Python` `NLP` `scikit-learn` `Streamlit` `FastAPI` `SQLAlchemy` `Docker` `Azure App Service`

[Live demo](https://resume-classifier-chintan.azurewebsites.net/) · [Repository](https://github.com/chintan-02/smart-resume-classifier) · [Case study](https://chintan-patel-ai.netlify.app/case-studies/resumeiq)

> **Scope:** Decision-support portfolio system. It does not automate hiring decisions or present model output as employment truth.

---

### Product Finder AI Agent

**Grounded product-search agent built with Google ADK**

- Natural-language product requests parsed through a single ADK agent and search tool
- Deterministic Python filtering for category, price, product name, and availability constraints
- FastAPI service, React/Vite interface, Docker packaging, tests, and structured error handling
- Google Cloud Run backend and Netlify frontend deployment architecture

`Google ADK` `Python` `FastAPI` `React` `Docker` `Google Cloud Run`

[Repository](https://github.com/chintan-02/product-finder-adk-agent) · [Live demo](https://product-finder-adk-chintan.netlify.app/)

---

## Engineering Stack

| Area | Technologies and practices |
|---|---|
| **Languages & Data** | Python, SQL, TypeScript, JavaScript, Pandas, NumPy, PostgreSQL, SQLite |
| **ML & Evaluation** | scikit-learn, LightGBM, XGBoost, feature engineering, class-level metrics, threshold tuning, calibration, error analysis |
| **NLP & RAG** | TF-IDF, clinical NLP, semantic matching, SentenceTransformers, ChromaDB, evidence gating, citations, RAG evaluation |
| **Backend & Frontend** | FastAPI, Pydantic, SQLAlchemy, Alembic, React, Next.js, Streamlit, Tailwind CSS |
| **Delivery & Reliability** | Docker, Docker Compose, GitHub Actions, Azure App Service, Google Cloud Run, pytest, Vitest, structured logging, health/readiness checks |
| **Responsible AI** | Human review, privacy-aware design, safe escalation, evidence provenance, auditability, transparent limitations |

---

## Technical Writing

- [What It Would Cost to Run PolicyGPT for 10,000 Queries](https://chintan-patel-ai.netlify.app/writing/policygpt-cost-10000-queries)
- [Building TriageAI's ESI 3/4/5 Model: Why LightGBM Won](https://chintan-patel-ai.netlify.app/writing/lightgbm-vs-xgboost)
- [How I Evaluate a RAG System Beyond Demo Questions](https://chintan-patel-ai.netlify.app/writing/rag-evaluation-beyond-demo)
- [From Notebook to FastAPI: Building a Reproducible Model Registry](https://chintan-patel-ai.netlify.app/writing/model-registry-to-fastapi)
- [Designing Drift Monitoring for Production ML Systems](https://chintan-patel-ai.netlify.app/writing/data-drift)
- [Evaluating Applied ML Systems Beyond Accuracy](https://chintan-patel-ai.netlify.app/writing/model-evaluation)

---

## Current Focus

- Building **RegImpact AI**, a regulatory-change intelligence and human-review workflow, as the next production-style project
- Deepening agentic workflows, document versioning, change detection, background processing, RBAC, observability, and cloud deployment
- Preparing for new-graduate and junior roles in Applied AI/ML Engineering, Machine Learning, GenAI/RAG, NLP, AI-focused Software Development, and Junior MLOps

---

## Education

| Credential | Institution | Completion |
|---|---|---|
| Post-Diploma Certificate, Integrated Artificial Intelligence | SAIT, Calgary, Canada | August 2026 |
| Professional Development Certificate, Supply Chain Management & Logistics | MacEwan University, Edmonton, Canada | December 2025 |
| Bachelor of Engineering, Computer Science and Engineering | Gujarat Technological University (ITM Universe), India | August 2019 |

---

## Connect

I am open to **new-graduate and junior opportunities across Canada** in Applied AI/ML Engineering, Machine Learning Engineering, GenAI/RAG, NLP, AI-focused Software Development, and Junior MLOps.

[Portfolio](https://chintan-patel-ai.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/chintan-patel-ai/) · [Email](mailto:patel.chintan380@gmail.com)

<div align="center">
  <i>Building AI systems that are useful, reviewable, evidence-grounded, and honest about their limits.</i>
</div>
