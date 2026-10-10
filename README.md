<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:a855f7,100:06b6d4&height=220&section=header&text=Lokesh%20Gaddam&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=AI%20Software%20Engineer&descAlignY=58&descSize=20" width="100%" alt="Lokesh Gaddam, AI Software Engineer">

### I build the backends, pipelines and dashboards that put LLMs inside real workflows.

Python · FastAPI · PostgreSQL · LangGraph · Java · TypeScript
<br>
Vijayawada, India · Open to AI software engineer and backend roles

<!-- TODO: after you rename the portfolio repo, change the Portfolio link to https://lokeshgaddam14.github.io/ -->
[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=githubpages&logoColor=white)](https://lokeshgaddam14.github.io/Portofolio/index.html)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lokesh-gaddam-ai-engineer/)
[![Email me](https://img.shields.io/badge/Email_me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lokeshgaddam2514@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-6366f1?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1M1hcc7yvGF3RpgS-TKO3pu5xeloWXlsF/view?usp=sharing)

</div>

<br>

## About

B.Tech in Electronics & Communication Engineering with a Data Science specialization from KL University (2026, CGPA 8.39). I work on the backend side of AI products: pipelines that collect and clean data, LLM agents that work through it in controlled steps, and the APIs and dashboards that let a person see what happened.

| Backend and APIs | AI agents | Data pipelines |
| :-- | :-- | :-- |
| FastAPI and Spring Boot services, REST design, async background jobs, JWT auth | LangGraph orchestration with typed state, structured outputs, retries, quality checks | Ingestion, extraction, enrichment and validation into PostgreSQL and MySQL |

<br>

## Projects

| Project | What it does | Stack | Links |
| :-- | :-- | :-- | :-- |
| **PipelineAI** | Finds leads, scrapes their sites, enriches the data, and emails the prospects an AI decision step shortlists | Python, FastAPI, PostgreSQL, LangGraph, React | [Live demo](https://pipelineai-dashboard.onrender.com/) · [Code](https://github.com/LokeshGaddam14/pipelineai) |
| **SalesIntelligenceAgent** | Three LangGraph agents research a company and a person, then write a summary, with an automated quality check | Python, FastAPI, LangGraph, FastMCP, React | [Code](https://github.com/LokeshGaddam14/ai_sales_intelligence) |
| **delivr-engine** | Notification delivery with exponential backoff retries, audit logging and real-time analytics | Java, Spring Boot, MySQL, JWT | [Code](https://github.com/LokeshGaddam14/delivr-engine) |
| **approval-workflow-engine** | Leave and work requests from ready-made templates, routed up to higher ops for approval | TypeScript | [Code](https://github.com/LokeshGaddam14/approval-workflow-engine) |
| **ai-summarizer** | Paste a link, get a short AI summary of the page | JavaScript | [Live demo](https://ai-summarizer-peach-seven.vercel.app/) · [Code](https://github.com/LokeshGaddam14/ai-summarizer) |

<!-- TODO: when SalesIntelligenceAgent, delivr-engine or approval-workflow-engine go live, add "[Live demo](URL) · " in front of "[Code]" in its row -->

<!-- TODO: add a screenshot of the PipelineAI dashboard. Upload it to this repo as assets/pipelineai.png, then remove the comment markers around the next line. -->
<!-- <p align="center"><img src="assets/pipelineai.png" width="85%" alt="PipelineAI dashboard"></p> -->

<br>

### PipelineAI

```mermaid
flowchart LR
    A[Lead discovery] --> B[Scrape website]
    B --> C[Analyze with LLM]
    C --> D[Enrich contact data]
    D --> E{AI shortlist}
    E -->|shortlisted| F[Cold email]
    E -->|skipped| G[(PostgreSQL)]
    F --> G
    F --> H[HubSpot sync]
    G --> I[React dashboard]
```

- Three-stage LangGraph pipeline (scrape, analyze, enrich) with typed state, structured JSON outputs and retry handling
- FastAPI backend with six REST endpoints and async background tasks that run the pipeline
- PostgreSQL storage for processed records, synced to HubSpot
- React and TypeScript dashboard for pipeline status, lead data, email previews and analytics
<!-- TODO: keep the next line only if you can explain how 92% was measured (dataset, number of examples, what counted as correct). Otherwise delete it. -->
- 92% retrieval precision on enrichment benchmarks

<!-- TODO: delete the next line once the hosted demo loads quickly -->
<sub>The hosted demo can take a minute to wake up on first load.</sub>

### SalesIntelligenceAgent

```mermaid
flowchart LR
    A[Lead] --> B[Company research agent]
    A --> C[Person research agent]
    B --> D[Synthesis agent]
    C --> D
    D --> E{Quality check}
    E -->|passes| F[CRM sync]
    E -->|fails| G[Controlled rewrite]
    G --> E
```

- Three LangGraph agents (company research, person research, synthesis) passing structured state with deterministic control flow
- Automated output-quality check with scoring, validation and a controlled rewrite step before anything moves downstream
- FastMCP server exposing five operational tools
- React and TypeScript dashboard showing live run status
<!-- TODO: confirm ai_sales_intelligence is the right repo for this project -->

<br>

## Tech stack

<img src="https://skillicons.dev/icons?i=python,java,ts,fastapi,spring,postgres,mysql,react,tailwind,vite,docker,git&perline=12" alt="Python, Java, TypeScript, FastAPI, Spring Boot, PostgreSQL, MySQL, React, Tailwind CSS, Vite, Docker, Git">

**AI and agents:** LangGraph, LangChain, RAG, ChromaDB, Groq, structured outputs, multi-agent orchestration, FastMCP
**Data and integrations:** Apify, Hunter.io, HubSpot API, n8n, Google APIs, SQLite
**Deploy:** Render, Vercel, Docker

<br>

## Other work

**Freelance automation, 2025 to present.** Built n8n and Python workflows for lead intake, qualification, enrichment, CRM sync and email notifications. Used Apify Google Maps extraction to build a sheet of 55 qualified dental clinic leads for field sales. Debugged live workflow failures, including mismatched payload fields and exposed credentials.

<details>
<summary><b>Earlier data science projects</b> (Jupyter notebooks)</summary>
<br>

- [Bank loan default analysis](https://github.com/LokeshGaddam14/bank-loan-default-analysis)
- [Credit risk analytics](https://github.com/LokeshGaddam14/credit-risk-analytics)
- [Fraud detection](https://github.com/LokeshGaddam14/fraud-detection)
- [SaaS churn analysis](https://github.com/LokeshGaddam14/saas-churn-analysis)

</details>

**Certifications:** Google AI Professional Certificate, DeepLearning.AI Generative AI with LLMs.

<br>

<div align="center">

**Want to talk about a role or a project? [Email me](mailto:lokeshgaddam2514@gmail.com) or message me on [LinkedIn](https://www.linkedin.com/in/lokesh-gaddam-ai-engineer/).**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:a855f7,100:6366f1&height=100&section=footer" width="100%" alt="">

</div>
