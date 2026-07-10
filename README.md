<div align="center">

<a href="https://chintan-patel-ai.netlify.app/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1200&color=0D9488&center=true&vCenter=true&width=900&lines=Applied+AI%2FML+Engineer+%26+Data+Science+Builder;Building+Explainable+ML%2C+RAG+%26+Decision-Support+Systems;Python+%C2%B7+FastAPI+%C2%B7+React+%C2%B7+NLP+%C2%B7+Responsible+AI" alt="Chintan Patel — Applied AI/ML Engineer" />
</a>

<br/>

# Chintan Patel

### Applied AI/ML Engineer · Data Science · NLP & RAG · AI Product Engineering

I build production-minded AI systems that are **explainable, evidence-grounded, auditable, and designed for human review**.

📍 Calgary, Alberta, Canada

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0D9488?style=for-the-badge&logo=google-chrome&logoColor=white)](https://chintan-patel-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintan-patel-ai/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:patel.chintan380@gmail.com)

</div>

---

## 👨‍💻 About Me

I am a Computer Science Engineer completing a **Post-Diploma Certificate in Integrated Artificial Intelligence at SAIT**. My work focuses on moving AI beyond notebooks into real application workflows with APIs, user interfaces, databases, model evaluation, safety controls, and deployment foundations.

I currently build across:

- **Applied machine learning:** preprocessing, feature engineering, classification, class imbalance, threshold tuning, error analysis, and explainability
- **NLP and RAG:** document parsing, embeddings, semantic retrieval, evidence scoring, grounded generation, citations, and safe fallback behavior
- **AI product engineering:** FastAPI services, React/TypeScript and Streamlit interfaces, SQLAlchemy persistence, PDF/report workflows, and API contracts
- **Production readiness:** testing, Docker, CI/CD foundations, model registries, logging, health/readiness checks, and Azure deployment
- **Responsible AI:** human review, audit trails, transparent limitations, privacy-aware design, and decision-support boundaries

> **Current goal:** contribute as an Applied AI/ML Engineer, Machine Learning Engineer, Data Scientist, or AI Software Developer building reliable and responsible AI products.

---

## 🚀 Featured Projects

### 🏥 TriageAI / SympDirect

**ESI Clinical Intake & Care Routing Assistant**

A backend-connected healthcare AI decision-support workflow for structured clinical intake and ESI 3/4/5 care routing. The system combines real LightGBM inference with transparent safety-rule escalation, clinician accept/override review, server-side audit logging, database persistence, dashboard workflows, and backend-generated PDF summaries.

**Engineering highlights**

- Final LightGBM V2 model registry with **273 input features**
- Safety-sensitive ESI routing with human-in-the-loop review
- React + TypeScript frontend connected to a FastAPI source of truth
- SQLAlchemy persistence, audit events, prediction latency tracking, and ReportLab PDF generation
- Healthcare-safe positioning: decision support, not diagnosis or autonomous clinical action

**Verified model evaluation**

| Accuracy | Macro F1 | Weighted F1 | ESI 5 F1 | Unsafe ESI 3→5 downgrade rate |
|---:|---:|---:|---:|---:|
| **78.32%** | **70.37%** | **78.88%** | **54.70%** | **0.68%** |

`Python` `LightGBM` `FastAPI` `React` `TypeScript` `SQLAlchemy` `SQLite/PostgreSQL` `ReportLab`

[![Repository](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/triageai-esi-care-routing)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/triageai)

> Portfolio and educational clinical decision-support project. It does not diagnose patients or replace clinician judgment.

---

### 📚 PolicyGPT Enterprise

**Evidence-First RAG for HR, SOP, Policy, and Compliance Documents**

A production-style retrieval-augmented generation system that retrieves and scores document evidence before answer generation. Unlike a generic PDF chatbot, PolicyGPT exposes the retrieval process and refuses unsupported answers when evidence does not meet the configured threshold.

**Engineering highlights**

- Page-aware PDF extraction, cleaning, chunking, and metadata preservation
- SentenceTransformer embeddings with ChromaDB semantic retrieval
- Evidence scoring, threshold filtering, and citation-backed responses
- Evidence Explorer with retrieval trace, confidence, and source transparency
- Provider-agnostic generation with Groq, OpenAI, and no-LLM fallback modes
- FastAPI backend with a product-style Streamlit compliance console

`Python` `FastAPI` `Streamlit` `SentenceTransformers` `ChromaDB` `PyMuPDF` `Groq/OpenAI` `Pydantic`

[![Repository](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/policygpt-enterprise)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/policygpt)

---

### 📄 ResumeIQ

**AI-Assisted Resume Intelligence & Job Application Platform**

A privacy-aware NLP decision-support platform for resume parsing, role classification, ATS-style compatibility signals, job-description matching, semantic similarity, skill intelligence, sentence-quality analysis, practical rewrite guidance, and recruiter review workflows.

**Engineering highlights**

- PDF, DOCX, and TXT parsing with text preprocessing
- TF-IDF classification, job-description matching, and semantic similarity
- Normalized skill extraction, template detection, and generic sentence analysis
- FastAPI backend foundation with SQLAlchemy persistence
- Docker Compose, pytest, GitHub Actions, Azure deployment, and responsible AI documentation
- Human-review boundary: supports decisions without automating hiring outcomes

`Python` `NLP` `TF-IDF` `Scikit-learn` `FastAPI` `Streamlit` `SQLAlchemy` `Docker` `GitHub Actions` `Azure`

[![Live Demo](https://img.shields.io/badge/Live_Demo-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](https://resume-classifier-chintan.azurewebsites.net/)
[![Repository](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/smart-resume-classifier)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/resumeiq)

---

## 🧭 Planned Flagship Project

### 🛠️ OpsPilot AI

**Agentic AIOps Platform for Incident Detection, Root-Cause Analysis & Human-Approved Remediation**

Planned enterprise AI engineering project combining predictive ML, log and metric anomaly detection, evidence-grounded RAG, an agentic incident workflow, human approval gates, MLOps, observability, and responsible AI governance.

```text
Incident Intake
    → Severity Classification
    → Metrics / Log Analysis
    → Runbook & Postmortem Retrieval
    → Root-Cause Hypothesis
    → Recommended Action
    → Human Approval
    → Simulated Ticket / Remediation
    → Audit & Monitoring
```

**Planned engineering scope**

- LightGBM/XGBoost severity baseline plus a PyTorch/DistilBERT ticket classifier
- LangGraph workflow with tools, state, structured outputs, and approval checkpoints
- Qdrant or pgvector for runbook and postmortem retrieval
- MLflow, DVC, model registry, evaluation pipelines, and GitHub Actions
- Evidently, Prometheus, Grafana, and OpenTelemetry for drift and service observability
- PostgreSQL, Redis/background tasks, Docker Compose, RBAC, PII masking, model cards, and data cards

> **Status:** Planned. The technologies above are roadmap targets and are not presented as completed project experience.

---

## 🧠 Applied AI/ML Skills

| Area | Current Practical Skills |
|---|---|
| **Machine Learning** | Data preprocessing, feature engineering, classification, model comparison, class imbalance, threshold tuning, cross-validation, error analysis, confusion matrices, precision/recall/F1, and explainability |
| **NLP & Retrieval** | Text cleaning, TF-IDF, document parsing, SentenceTransformers, embeddings, semantic search, vector retrieval, evidence scoring, RAG, citations, prompt guardrails, and fallback handling |
| **Backend Engineering** | FastAPI, Pydantic, REST APIs, request/response schemas, health/readiness endpoints, SQLAlchemy, persistence workflows, audit logs, and PDF/report services |
| **Frontend & Product** | React, TypeScript, Vite, Tailwind CSS, Streamlit, dashboard workflows, data visualization, loading/error/empty states, and human-review interfaces |
| **MLOps & Delivery** | Model registry design, Docker, pytest, GitHub Actions, structured logging, latency tracking, environment configuration, Azure App Service, and deployment documentation |
| **Responsible AI** | Human-in-the-loop review, model limitations, safe escalation, evidence grounding, privacy-aware displays, auditability, transparent fallbacks, and decision-support positioning |

---

## 🛠️ Technology Stack

### Languages & Data

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

### Machine Learning, NLP & RAG

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-EC0000?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-0D9488?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-6D28D9?style=flat-square)
![SentenceTransformers](https://img.shields.io/badge/SentenceTransformers-FFB000?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)

### Application Engineering

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

### Engineering & Deployment

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📈 Currently Strengthening

These are active learning and future implementation areas—not inflated current claims:

- Agentic AI orchestration with LangGraph and approval-gated workflows
- PyTorch and transformer fine-tuning
- MLflow experiment tracking and model registry workflows
- RAG evaluation, faithfulness testing, latency, and cost analysis
- Drift monitoring, Prometheus/Grafana dashboards, and OpenTelemetry
- PostgreSQL production deployment, cloud secrets, RBAC, and secure AI architecture
- Kubernetes, OpenShift, and hybrid-cloud deployment fundamentals

---

## 🎓 Education

| Program | Institution | Year |
|---|---|---:|
| Post-Diploma Certificate — Integrated Artificial Intelligence | SAIT, Calgary, Canada | 2026 |
| Certificate — Supply Chain Management & Professional Communication | MacEwan University, Edmonton, Canada | 2025 |
| Bachelor of Engineering — Computer Science | ITM University, Vadodara, India | 2019 |

---

## 🤝 Let’s Connect

I am open to **co-op, internship, new-graduate, and junior opportunities across Canada** in Applied AI/ML Engineering, Machine Learning Engineering, Data Science, MLOps, and AI-focused Software Development.

[![Portfolio](https://img.shields.io/badge/Portfolio-chintan--patel--ai-0D9488?style=flat-square&logo=google-chrome&logoColor=white)](https://chintan-patel-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Chintan_Patel-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintan-patel-ai/)
[![GitHub](https://img.shields.io/badge/GitHub-chintan--02-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02)
[![Email](https://img.shields.io/badge/Email-patel.chintan380%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:patel.chintan380@gmail.com)

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=chintan-02&style=flat-square&color=0D9488" alt="GitHub profile views" />
  <br/><br/>
  <i>Building AI systems that are useful, reviewable, and trustworthy.</i>
</div>
