<div align="center">

<a href="https://chintan-patel-ai.netlify.app/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1200&color=0D9488&center=true&vCenter=true&width=900&lines=Applied+AI%2FML+Engineer;Explainable+ML%2C+NLP+%26+RAG+Systems;Python+%C2%B7+FastAPI+%C2%B7+React+%C2%B7+Responsible+AI" alt="Chintan Patel — Applied AI/ML Engineer" />
</a>

<br/>

# Chintan Patel

### Applied AI/ML Engineer · Machine Learning · NLP & RAG · AI Product Engineering

I build end-to-end AI systems that are **explainable, evidence-grounded, auditable, and designed for human review**.

📍 Calgary, Alberta, Canada

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0D9488?style=for-the-badge&logo=google-chrome&logoColor=white)](https://chintan-patel-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintan-patel-ai/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:patel.chintan380@gmail.com)

</div>

---

## About

I am an Applied AI/ML engineer with a computer science background, currently completing SAIT's **Integrated Artificial Intelligence** post-diploma certificate.

My work focuses on moving AI beyond notebooks into complete application workflows with:

- model evaluation and error analysis
- FastAPI services and typed API contracts
- React, TypeScript, and Streamlit interfaces
- SQLAlchemy persistence and audit trails
- human-review and safety controls
- Docker, testing, CI/CD, and deployment foundations

I am especially interested in AI systems where **traceability, reliability, privacy, and responsible use** matter as much as model performance.

> **Career focus:** Applied AI/ML Engineering, Machine Learning Engineering, Data Science, MLOps, and AI-focused Software Development.

---

## Featured Projects

### TriageAI / SympDirect

**ESI Clinical Intake & Care Routing Assistant**

A healthcare AI decision-support workflow for structured intake and ESI care routing. The system combines real LightGBM inference with safety-rule escalation, clinician review, audit logging, database persistence, dashboard workflows, and backend-generated PDF summaries.

**Selected engineering evidence**

- LightGBM V2 model registry for ESI 3/4/5 classification with **273 input features**
- Rule-based safety gates for higher-acuity escalation before and after model inference
- Review-first Clinical Intake NLP Safety Layer for extracting demographics, symptoms, vital signs, safety cues, and uncertainty from clinician notes
- React + TypeScript frontend connected to a FastAPI source of truth
- SQLAlchemy persistence, audit events, latency tracking, and ReportLab PDF generation
- Human-in-the-loop accept/override workflow with clear decision-support boundaries

**Verified model evaluation**

| Accuracy | Macro F1 | Weighted F1 | ESI 5 F1 | Unsafe ESI 3→5 downgrade rate |
|---:|---:|---:|---:|---:|
| **78.32%** | **70.37%** | **78.88%** | **54.70%** | **0.68%** |

`Python` `LightGBM` `FastAPI` `React` `TypeScript` `SQLAlchemy` `ReportLab`

[![Repository](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/triageai-esi-care-routing)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/triageai)

> Portfolio and educational clinical decision-support project. It does not diagnose patients or replace clinician judgment.

---

### PolicyGPT Enterprise

**Evidence-First RAG for Policy and Compliance Documents**

A production-shaped retrieval-augmented generation system that retrieves, scores, and displays evidence before answer generation. It is designed to refuse unsupported answers when retrieved evidence does not meet the configured threshold.

**Selected engineering evidence**

- Page-aware PDF extraction, cleaning, chunking, and metadata preservation
- SentenceTransformer embeddings with ChromaDB semantic retrieval
- Evidence scoring, threshold filtering, and citation-backed responses
- Evidence Explorer with retrieval trace, confidence, and source transparency
- Groq, OpenAI, and no-LLM fallback modes
- FastAPI backend with a product-style Streamlit compliance console

`Python` `FastAPI` `Streamlit` `SentenceTransformers` `ChromaDB` `PyMuPDF` `Pydantic`

[![Repository](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/policygpt-enterprise)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/policygpt)

---

### ResumeIQ

**Privacy-Aware Resume Intelligence Platform**

An NLP decision-support platform for resume parsing, role classification, ATS-style compatibility signals, job-description matching, semantic similarity, skill intelligence, sentence-quality analysis, and practical rewrite guidance.

**Selected engineering evidence**

- PDF, DOCX, and TXT parsing with text preprocessing
- TF-IDF role classification and job-description matching
- Semantic similarity and normalized skill extraction
- Template detection and generic-sentence analysis
- FastAPI backend foundation with SQLAlchemy persistence
- Docker Compose, pytest, GitHub Actions, and Azure deployment
- Human-review boundary that supports decisions without automating hiring outcomes

`Python` `NLP` `Scikit-learn` `FastAPI` `Streamlit` `SQLAlchemy` `Docker` `Azure`

[![Live Demo](https://img.shields.io/badge/Live_Demo-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](https://resume-classifier-chintan.azurewebsites.net/)
[![Repository](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/smart-resume-classifier)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/resumeiq)

---

## Applied AI/ML Capabilities

| Area | Practical Experience |
|---|---|
| **Machine Learning** | Preprocessing, feature engineering, classification, class imbalance, threshold tuning, cross-validation, model comparison, error analysis, confusion matrices, precision/recall/F1, and explainability |
| **NLP & Retrieval** | Text cleaning, TF-IDF, document parsing, SentenceTransformers, embeddings, semantic search, vector retrieval, evidence scoring, RAG, citations, and safe fallback |
| **Backend Engineering** | FastAPI, Pydantic, REST APIs, request/response schemas, health/readiness endpoints, SQLAlchemy, audit logs, and PDF/report services |
| **Frontend & Product** | React, TypeScript, Vite, Tailwind CSS, Streamlit, dashboard workflows, loading/error/empty states, and human-review interfaces |
| **MLOps & Delivery** | Model registry design, Docker, pytest, GitHub Actions, structured logging, latency tracking, environment configuration, and Azure App Service |
| **Responsible AI** | Human-in-the-loop review, safe escalation, transparent limitations, evidence grounding, privacy-aware design, auditability, and decision-support boundaries |

---

## Technology Stack

### Languages, Data & ML

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)

### NLP, RAG & Application Engineering

![NLP](https://img.shields.io/badge/NLP-0D9488?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-6D28D9?style=flat-square)
![SentenceTransformers](https://img.shields.io/badge/SentenceTransformers-FFB000?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

### Engineering & Delivery

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Currently Strengthening

These are active learning or future implementation areas, not completed-project claims:

- agentic AI orchestration with LangGraph and approval-gated workflows
- PyTorch and transformer fine-tuning
- MLflow experiment tracking and model registry workflows
- RAG evaluation, faithfulness testing, latency, and cost analysis
- drift monitoring with Prometheus, Grafana, and OpenTelemetry
- PostgreSQL production deployment, cloud secrets, RBAC, and secure AI architecture
- Kubernetes, OpenShift, and hybrid-cloud deployment fundamentals

---

## Next Build: OpsPilot AI

**Status: Planned**

A future AIOps project focused on incident classification, evidence-grounded root-cause analysis, human-approved remediation, observability, and responsible automation.

Planned scope includes:

- ML-based incident severity classification
- log, metric, runbook, and postmortem retrieval
- LangGraph workflow with approval checkpoints
- PostgreSQL, Docker Compose, MLflow, and observability foundations
- transparent audit records and simulated remediation only

> The technologies above are roadmap targets and are not presented as completed project experience.

---

## Education

| Program | Institution | Status |
|---|---|---|
| Post-Diploma Certificate — Integrated Artificial Intelligence | SAIT, Calgary, Canada | In progress, 2026 |
| Post-Graduate Certificate — Supply Chain Management & Logistics | MacEwan University, Edmonton, Canada | Completed, 2025 |
| Bachelor of Engineering — Computer Science | ITM University, Vadodara, India | Completed, 2019 |

---

## Connect

I am open to **co-op, internship, new-graduate, and junior opportunities across Canada** in Applied AI/ML Engineering, Machine Learning Engineering, Data Science, MLOps, and AI-focused Software Development.

[![Portfolio](https://img.shields.io/badge/Portfolio-chintan--patel--ai-0D9488?style=flat-square&logo=google-chrome&logoColor=white)](https://chintan-patel-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Chintan_Patel-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintan-patel-ai/)
[![GitHub](https://img.shields.io/badge/GitHub-chintan--02-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02)
[![Email](https://img.shields.io/badge/Email-patel.chintan380%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:patel.chintan380@gmail.com)

---

<div align="center">
  <i>Building AI systems that are useful, reviewable, and trustworthy.</i>
</div>
