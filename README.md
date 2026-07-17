<div align="center">

<a href="https://chintan-patel-ai.netlify.app/">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1200&color=0D9488&center=true&vCenter=true&width=900&lines=Applied+AI%2FML+Engineer;Healthcare+ML+%C2%B7+NLP+%C2%B7+RAG+Systems;Python+%C2%B7+FastAPI+%C2%B7+React+%C2%B7+Next.js;Explainable+%C2%B7+Evidence-Grounded+%C2%B7+Human-Reviewed"
    alt="Chintan Patel — Applied AI/ML Engineer"
  />
</a>

<br />

# Chintan Patel

### Applied AI/ML Engineer · Data Science · GenAI/RAG · AI Product Engineering

I build end-to-end AI systems that connect **data, evaluated models, retrieval pipelines, typed APIs, human review, and operational evidence**.

📍 Calgary, Alberta, Canada  
🎯 Open to co-op, internship, new-graduate, and junior AI/ML opportunities across Canada

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0D9488?style=for-the-badge&logo=google-chrome&logoColor=white)](https://chintan-patel-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintan-patel-ai/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:patel.chintan380@gmail.com)

</div>

---

## About

I am a Computer Science graduate completing SAIT's **Integrated Artificial Intelligence** postgraduate certificate in Calgary.

My work focuses on practical AI engineering across three areas:

- **Healthcare decision support** with review-first clinical NLP, safety-sensitive model evaluation, clinician oversight, and audit evidence
- **Privacy-aware resume intelligence** with multi-format parsing, transparent NLP signals, semantic matching, and human review
- **Evidence-grounded policy RAG** with durable document identity, calibrated answerability, citations, unsupported-question controls, and evaluation

I am especially interested in systems where model or retrieval output must be **explainable, evidence-backed, reviewable, and honest about uncertainty, failure states, and limitations**.

> **Target roles:** AI/ML Engineering, Data Science, GenAI/RAG, Applied Software, and Junior MLOps.

---

## Featured Projects

### 1. TriageAI / SympDirect

**Clinical Intake & ESI Care Routing Assistant**

A review-first healthcare AI decision-support workflow that connects clinician notes and structured intake to ESI 3/4/5 prediction, transparent safety escalation, clinician decisions, audit evidence, dashboard workflows, and backend-generated PDF summaries.

**Workflow**

```text
Clinical note or structured intake
→ evidence-linked NLP extraction
→ clinician review and correction
→ reproducible feature builder
→ LightGBM ESI 3/4/5 prediction
→ explicit safety-rule escalation
→ clinician accept / override / needs review
→ server-side audit trail
→ PDF decision-support summary
```

**Selected engineering evidence**

- Final LightGBM V2 registry with **273 ordered runtime features**
- Review-first Clinical Intake NLP Safety Layer with editable fields, evidence snippets, safety cues, and missing-data warnings
- React + TypeScript frontend connected to a FastAPI source of truth
- SQLAlchemy persistence, reviewed NLP audit metadata, clinician decision history, and ReportLab PDF generation
- Explicit safety rules remain visible around the model instead of being hidden inside an unsupported classifier claim
- Final system wording preserves the clinician as the decision-maker

**Verified held-out test evaluation**

| Accuracy | Macro F1 | Weighted F1 | ESI 5 F1 | Unsafe ESI 3→5 rate |
|---:|---:|---:|---:|---:|
| **78.32%** | **70.37%** | **78.88%** | **54.70%** | **0.68%** |

`Python` `LightGBM` `FastAPI` `React` `TypeScript` `SQLAlchemy` `ReportLab` `pytest`

[![Repository](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/triageai-esi-care-routing)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/triageai)
[![Model Article](https://img.shields.io/badge/Model_Article-B45309?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/writing/lightgbm-vs-xgboost)

> **Boundary:** Portfolio and educational clinical decision-support project. It does not diagnose patients, replace clinician judgment, establish clinical safety, or claim regulatory approval.

---

### 2. PolicyGPT Enterprise

**Production-Style Evidence Intelligence for Policy Documents · v0.3.0**

A local release-style policy RAG system that treats document identity, evidence sufficiency, citations, unsupported requests, provider failure, evaluation, and operational readiness as product requirements—not optional backend details.

**Architecture**

```text
Next.js 16 + React 19 + TypeScript
→ server-side BFF
→ FastAPI evidence service
→ PostgreSQL 16 document lifecycle and identity
→ PyMuPDF extraction and chunking
→ SentenceTransformer embeddings
→ ChromaDB retrieval
→ calibrated answerability and evidence gate
→ generated answer, citation-only fallback, or controlled rejection
```

**Selected engineering evidence**

- SHA-256 duplicate prevention and atomic source-document storage
- PostgreSQL lifecycle metadata with SQLAlchemy and Alembic migrations
- Calibrated answerability using retrieval strength, coverage, numeric consistency, direct support, and scope-risk signals
- Page-level citations and provider-resilient citation-only fallback
- Controlled rejection for unsupported or externally authoritative requests
- Separate **Documents, Ask, Evaluation, and System** product workspaces
- Four-service Docker Compose release profile with non-root containers, health/readiness gates, structured logs, and request IDs
- **229 backend tests** and **112 frontend tests**

**Controlled local benchmark**

| Cases | Supported | Unsupported | Expected-page hit rate | Request errors |
|---:|---:|---:|---:|---:|
| **16** | **11** | **5** | **100%** | **0** |

The verified benchmark run intentionally disabled the generation provider. Supported cases returned citation-only evidence, so the result validates retrieval, answerability, unsupported-question handling, and fallback behaviour—not generated-answer quality or production accuracy.

`Next.js` `React` `TypeScript` `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `PyMuPDF` `SentenceTransformers` `ChromaDB` `Docker Compose` `Vitest`

[![Repository](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/policygpt-enterprise)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/policygpt)
[![Evaluation Article](https://img.shields.io/badge/RAG_Evaluation-6D28D9?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/writing/rag-evaluation-beyond-demo)

> **Boundary:** Verified local release profile. No cloud deployment, production authentication/RBAC, multitenancy, managed backups, hosted monitoring, or commercial deployment claim.

---

### 3. ResumeIQ

**Privacy-Aware Resume Intelligence Platform**

An NLP decision-support platform that separates parsing, baseline role classification, ATS-style compatibility, keyword evidence, semantic job-description matching, skill gaps, writing quality, and reviewer workflow instead of presenting one unexplained hiring score.

**Selected engineering evidence**

- PDF, DOCX, and TXT parsing with normalization and section-aware review
- TF-IDF baseline classification
- Exact keyword coverage plus semantic job-description matching
- Normalized skill intelligence and visible skill-gap analysis
- Writing-quality and structure guidance
- Batch resume comparison, reviewer notes, and human decision boundaries
- Privacy-safe display mode for portfolio demonstrations
- Optional FastAPI, SQLite, SQLAlchemy, Docker Compose, pytest, and GitHub Actions foundations
- Working Azure App Service portfolio demo

No headline classifier accuracy is promoted until leakage, duplication, split quality, calibration, and independent benchmark design are fully validated.

`Python` `NLP` `TF-IDF` `scikit-learn` `Streamlit` `FastAPI` `SQLAlchemy` `Docker Compose` `GitHub Actions` `Azure App Service`

[![Live Demo](https://img.shields.io/badge/Live_Demo-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](https://resume-classifier-chintan.azurewebsites.net/)
[![Repository](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/smart-resume-classifier)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/resumeiq)
[![Design Article](https://img.shields.io/badge/Multi--Signal_Design-B45309?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/writing/resume-intelligence-multi-signal)

> **Boundary:** Decision-support portfolio project. It does not automate hiring decisions, claim commercial ATS integration, or present model output as employment truth.

---

## Applied AI Engineering Stack

| Layer | Demonstrated capabilities |
|---|---|
| **Data & Persistence** | Python, NumPy, Pandas, SQL, PostgreSQL, SQLite, SQLAlchemy, Alembic, PyMuPDF, feature engineering, lifecycle metadata |
| **ML & Evaluation** | scikit-learn, LightGBM, XGBoost, Random Forest, class imbalance, threshold tuning, calibration, per-class evaluation, confusion analysis |
| **NLP, Retrieval & RAG** | Clinical NLP, TF-IDF, semantic matching, embeddings, SentenceTransformers, ChromaDB, evidence gating, citation grounding, RAG evaluation |
| **APIs & Product** | FastAPI, Pydantic v2, REST APIs, React, TypeScript, Next.js, Streamlit, Tailwind CSS, ReportLab, server-side BFF patterns |
| **Delivery & Reliability** | Docker, Docker Compose, GitHub Actions, Azure App Service, pytest, Vitest, ESLint, structured logging, request IDs, health/readiness contracts |
| **Responsible AI** | Human review, safe escalation, evidence provenance, privacy-aware design, auditability, controlled fallback, transparent limitations |

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
![XGBoost](https://img.shields.io/badge/XGBoost-EB5B29?style=flat-square)

### NLP, Retrieval & RAG

![NLP](https://img.shields.io/badge/Clinical_NLP-0D9488?style=flat-square)
![TF-IDF](https://img.shields.io/badge/TF--IDF-475569?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-6D28D9?style=flat-square)
![SentenceTransformers](https://img.shields.io/badge/SentenceTransformers-FFB000?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![PyMuPDF](https://img.shields.io/badge/PyMuPDF-3B82F6?style=flat-square)

### Backend, Frontend & Persistence

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic_v2-E92063?style=flat-square&logo=pydantic&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

### Delivery & Quality

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure App Service](https://img.shields.io/badge/Azure_App_Service-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Selected Technical Writing

- [Building TriageAI's ESI 3/4/5 Model: Why LightGBM Won](https://chintan-patel-ai.netlify.app/writing/lightgbm-vs-xgboost)
- [Designing a Review-First Clinical NLP Safety Layer](https://chintan-patel-ai.netlify.app/writing/clinical-nlp-safety-layer)
- [From Notebook to FastAPI: Building a Reproducible Model Registry](https://chintan-patel-ai.netlify.app/writing/model-registry-to-fastapi)
- [How I Evaluate a RAG System Beyond Demo Questions](https://chintan-patel-ai.netlify.app/writing/rag-evaluation-beyond-demo)
- [Why ResumeIQ Uses Multiple Signals Instead of One ATS Score](https://chintan-patel-ai.netlify.app/writing/resume-intelligence-multi-signal)

---

## Current Focus

- Expanding PolicyGPT retrieval experiments, provider-enabled answer-quality evaluation, and deployment planning
- Completing real screenshots, documentation, and recruiter-facing evidence for TriageAI and ResumeIQ
- Deepening production ML, RAG evaluation, observability, secure data lifecycles, cloud services, and MLOps foundations
- Preparing for AI/ML co-op, internship, new-graduate, and junior opportunities across Canada

---

## Education

| Program | Institution | Status |
|---|---|---|
| Postgraduate Certificate — Integrated Artificial Intelligence | SAIT, Calgary, Canada | In progress · 2026 |
| Postgraduate Certificate — Supply Chain & Logistics | MacEwan University, Edmonton, Canada | Completed · 2025 |
| Bachelor of Engineering — Computer Science | ITM University, Vadodara, India | Completed · 2019 |

---

## Connect

I am open to **co-op, internship, new-graduate, and junior opportunities across Canada** in AI/ML Engineering, Data Science, GenAI/RAG, Applied Software, Analytics, and Junior MLOps.

[![Portfolio](https://img.shields.io/badge/Portfolio-chintan--patel--ai-0D9488?style=flat-square&logo=google-chrome&logoColor=white)](https://chintan-patel-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Chintan_Patel-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintan-patel-ai/)
[![GitHub](https://img.shields.io/badge/GitHub-chintan--02-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02)
[![Email](https://img.shields.io/badge/Email-patel.chintan380%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:patel.chintan380@gmail.com)

---

<div align="center">
  <i>Building AI systems that are useful, reviewable, evidence-grounded, and honest about their limits.</i>
</div>
