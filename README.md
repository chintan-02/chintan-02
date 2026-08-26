<div align="center">

<a href="https://chintan-patel-ai.netlify.app/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1200&color=0D9488&center=true&vCenter=true&width=900&lines=Applied+AI%2FML+Engineer;Machine+Learning+%C2%B7+NLP+%C2%B7+GenAI%2FRAG;Reviewable+%C2%B7+Evidence-Grounded+%C2%B7+Production-Minded" alt="Chintan Patel — Applied AI/ML Engineer" />
</a>

# Chintan Patel

### Applied AI/ML Engineer · Machine Learning · NLP · GenAI/RAG

I build end-to-end AI systems that connect **reliable data, evaluated models, retrieval pipelines, typed APIs, usable interfaces, human review, and operational evidence**.

📍 Calgary, Alberta, Canada &nbsp;·&nbsp; 🎯 Open to new-graduate and junior opportunities across Canada

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0D9488?style=for-the-badge&logo=google-chrome&logoColor=white)](https://chintan-patel-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintan-patel-ai/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:patel.chintan380@gmail.com)

</div>

---

## Profile

Computer Science and Engineering graduate with more than three years of software-development and client-delivery experience, plus a completed **Post-Diploma Certificate in Integrated Artificial Intelligence from SAIT**.

I focus on applied AI systems where outputs must be **explainable, evidence-backed, reviewable, and honest about uncertainty and limitations**. My work spans machine learning, NLP, RAG, APIs, product interfaces, testing, containerization, and deployment.

> **Target roles:** Applied AI/ML Engineer · Machine Learning Engineer · GenAI/RAG Engineer · NLP Engineer · AI-Focused Software Developer · Junior MLOps Engineer

---

## Engineering Evidence

| Project | Selected proof | Delivery state |
|---|---|---|
| **TriageAI / SympDirect** | 273-feature model contract · held-out evaluation · safety escalation · clinician review · audit trail | Verified local decision-support workflow |
| **PolicyGPT Enterprise** | 230 backend tests · 128 frontend tests · 16-case evaluation · citations · evidence gating | Verified Docker Compose release |
| **ResumeIQ** | Multi-format parsing · multi-signal analysis · privacy-safe mode · human review | Live Azure portfolio demo |
| **Product Finder Agent** | Google ADK · deterministic filtering · FastAPI · React · Docker | Deployed portfolio-scale agent workflow |

---

## Featured Projects

### 🩺 TriageAI / SympDirect

#### Review-First Clinical Intake & ESI Care-Routing Decision Support

A clinical decision-support workflow connecting clinician notes and structured intake to ESI 3/4/5 prediction, explicit safety escalation, clinician decisions, audit evidence, and PDF reporting.

- Final LightGBM V2 registry with **273 ordered runtime features**
- Clinical NLP with editable fields, evidence snippets, safety cues, and missing-data warnings
- Explicit ESI 1/2 safety escalation outside the classifier
- Clinician accept, override, and needs-review workflows with audit history
- React/TypeScript frontend, FastAPI backend, SQLAlchemy persistence, and automated tests

| Accuracy | Macro F1 | Weighted F1 | ESI 5 F1 | Unsafe ESI 3→5 rate |
|---:|---:|---:|---:|---:|
| **78.32%** | **70.37%** | **78.88%** | **54.70%** | **0.68%** |

`Python` `LightGBM` `FastAPI` `React` `TypeScript` `SQLAlchemy` `ReportLab`

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/triageai-esi-care-routing)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/triageai)
[![Model Article](https://img.shields.io/badge/Model_Article-B45309?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/writing/lightgbm-vs-xgboost)

> **Scope:** Educational portfolio decision support. It is not diagnostic, clinically validated, or a replacement for clinician judgment.

---

### 📚 PolicyGPT Enterprise

#### Evidence-Grounded RAG for Policy & Compliance Documents · v0.3.0

A local release-style RAG system designed around durable document identity, evidence sufficiency, page citations, controlled rejection, provider failure, and operational readiness.

- SHA-256 duplicate prevention and PostgreSQL document-lifecycle metadata
- SentenceTransformer embeddings with ChromaDB retrieval
- Calibrated answerability, evidence gating, page citations, and unsupported-question rejection
- Provider-resilient citation-only fallback
- FastAPI, Next.js, SQLAlchemy, Alembic, request IDs, structured logs, and readiness checks
- **230 backend tests**, **128 frontend tests**, and a controlled **16-case evaluation workflow**

| Cases | Supported | Unsupported | Expected-page hit rate | Request errors |
|---:|---:|---:|---:|---:|
| **16** | **11** | **5** | **100%** | **0** |

The verified run intentionally disabled generation. It validates retrieval, answerability, unsupported-question handling, expected-page retrieval, and citation-only fallback—not generated-answer quality or production accuracy.

`Python` `FastAPI` `Next.js` `PostgreSQL` `SentenceTransformers` `ChromaDB` `Docker Compose`

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/policygpt-enterprise)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/policygpt-enterprise)
[![RAG Evaluation](https://img.shields.io/badge/RAG_Evaluation-6D28D9?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/writing/rag-evaluation-beyond-demo)
[![Cost Analysis](https://img.shields.io/badge/10K_Query_Cost-B45309?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/writing/policygpt-cost-10000-queries)

> **Scope:** Verified local release. No claim of production authentication/RBAC, multitenancy, managed cloud operations, commercial adoption, or generated-answer accuracy.

---

### 📄 ResumeIQ

#### Privacy-Aware Resume Intelligence & Job-Application Decision Support

An NLP platform that separates parsing, role classification, keyword evidence, semantic job matching, skill gaps, writing quality, and reviewer workflow instead of presenting one unexplained hiring score.

- PDF, DOCX, and TXT parsing with normalization and structured review
- TF-IDF role classification plus keyword and semantic job-description matching
- Skill-gap analysis, writing guidance, batch comparison, and reviewer notes
- Privacy-safe display mode and human-reviewed recommendations
- Streamlit application with optional FastAPI, SQLite, SQLAlchemy, Docker, testing, and CI foundations

`Python` `NLP` `scikit-learn` `Streamlit` `FastAPI` `SQLAlchemy` `Docker` `Azure App Service`

[![Live Demo](https://img.shields.io/badge/Live_Demo-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](https://resume-classifier-chintan.azurewebsites.net/)
[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/smart-resume-classifier)
[![Case Study](https://img.shields.io/badge/Case_Study-0D9488?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/case-studies/resumeiq)
[![Design Article](https://img.shields.io/badge/Multi--Signal_Design-B45309?style=flat-square&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/writing/resume-intelligence-multi-signal)

> **Scope:** Human-reviewed decision support. It does not automate hiring decisions or present model output as employment truth.

---

### 🔎 Product Finder AI Agent

#### Grounded Product Search with Google ADK & Deterministic Filtering

A technical assignment evolved into a portfolio project that separates natural-language interpretation from verified business rules.

- Focused Google ADK agent with tool-based product search
- Deterministic Python filtering for category, price, name, and availability constraints
- FastAPI service, React/Vite interface, Docker packaging, tests, and structured error handling
- Google Cloud Run backend and Netlify frontend deployment architecture

`Google ADK` `Python` `FastAPI` `React` `Vite` `Docker` `Google Cloud Run`

[![Live Demo](https://img.shields.io/badge/Live_Demo-00A98F?style=flat-square&logo=netlify&logoColor=white)](https://product-finder-adk-chintan.netlify.app/)
[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02/product-finder-adk-agent)

> **Scope:** Portfolio-scale workflow with a small validated catalogue; not a commercial recommendation engine.

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

![Clinical NLP](https://img.shields.io/badge/Clinical_NLP-0D9488?style=flat-square)
![TF-IDF](https://img.shields.io/badge/TF--IDF-475569?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-6D28D9?style=flat-square)
![SentenceTransformers](https://img.shields.io/badge/SentenceTransformers-FFB000?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![PyMuPDF](https://img.shields.io/badge/PyMuPDF-3B82F6?style=flat-square)

### APIs, Product & Delivery

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure App Service](https://img.shields.io/badge/Azure_App_Service-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Google Cloud Run](https://img.shields.io/badge/Google_Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

## Selected Technical Writing

- [What It Would Cost to Run PolicyGPT for 10,000 Queries](https://chintan-patel-ai.netlify.app/writing/policygpt-cost-10000-queries)
- [Building TriageAI's ESI 3/4/5 Model: Why LightGBM Won](https://chintan-patel-ai.netlify.app/writing/lightgbm-vs-xgboost)
- [Designing a Review-First Clinical NLP Safety Layer](https://chintan-patel-ai.netlify.app/writing/clinical-nlp-safety-layer)
- [How I Evaluate a RAG System Beyond Demo Questions](https://chintan-patel-ai.netlify.app/writing/rag-evaluation-beyond-demo)
- [From Notebook to FastAPI: Building a Reproducible Model Registry](https://chintan-patel-ai.netlify.app/writing/model-registry-to-fastapi)
- [Designing Drift Monitoring for Production ML Systems](https://chintan-patel-ai.netlify.app/writing/data-drift)

[![View All Writing](https://img.shields.io/badge/View_All_Technical_Writing-0D9488?style=for-the-badge&logo=readme&logoColor=white)](https://chintan-patel-ai.netlify.app/writing)

---

## Current Focus

- Building **RegImpact AI**, a regulatory-change intelligence and human-review workflow
- Deepening agentic workflows, document versioning, change detection, background processing, RBAC, observability, and cloud deployment
- Preparing for new-graduate and junior Applied AI/ML opportunities across Canada

---

## Education

| Credential | Institution | Completion |
|---|---|---|
| **Post-Diploma Certificate, Integrated Artificial Intelligence** | SAIT · Calgary, Canada | August 2026 |
| **Professional Development Certificate, Supply Chain Management & Logistics** | MacEwan University · Edmonton, Canada | December 2025 |
| **Bachelor of Engineering, Computer Science and Engineering** | Gujarat Technological University (ITM Universe) · India | August 2019 |

---

## Let's Connect

I am open to **new-graduate and junior opportunities across Canada** in Applied AI/ML Engineering, Machine Learning Engineering, GenAI/RAG, NLP, AI-focused Software Development, and Junior MLOps.

[![Portfolio](https://img.shields.io/badge/Portfolio-chintan--patel--ai-0D9488?style=flat-square&logo=google-chrome&logoColor=white)](https://chintan-patel-ai.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Chintan_Patel-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintan-patel-ai/)
[![GitHub](https://img.shields.io/badge/GitHub-chintan--02-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chintan-02)
[![Email](https://img.shields.io/badge/Email-patel.chintan380%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:patel.chintan380@gmail.com)

<div align="center">

---

<i>Building AI systems that are useful, reviewable, evidence-grounded, and honest about their limits.</i>

</div>
