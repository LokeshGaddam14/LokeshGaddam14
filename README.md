![Header](https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:a855f7,100:06b6d4&height=220&section=header&text=Lokesh%20Gaddam&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=AI%20Automation%20Engineer%20%7C%20Building%20Production%20AI%20Systems&descAlignY=58&descSize=17)



---

AI Software Engineer · Python, FastAPI, PostgreSQL, LangGraph · Vijayawada, India

I build backend systems that put LLMs inside real workflows: data pipelines, multi-agent orchestration, and the APIs and dashboards around them. B.Tech in Electronics & Communication Engineering (Data Science specialization), KL University, 2026, CGPA 8.39.

Open to AI software engineer and backend roles.

<!-- TODO: after you rename the portfolio repo, change the Portfolio link below to https://lokeshgaddam14.github.io/ -->

Portfolio LinkedIn Email me

Projects
PipelineAI: lead discovery and outreach engine

Finds leads, scrapes their websites for emails and pain points, enriches the data, and lets an AI decision step shortlist the prospects who then get a cold email automatically. Results sync to HubSpot.

Three-stage LangGraph pipeline (scrape, analyze, enrich) with typed state, structured JSON outputs, and retry handling
FastAPI backend with six REST endpoints and async background tasks that run the pipeline
PostgreSQL storage for processed records
React + TypeScript dashboard for pipeline status, lead data, email previews, and analytics
<!-- TODO: only keep the next line if you can explain exactly how 92% was measured (dataset, number of examples, what counted as correct). Otherwise delete it. -->
92% retrieval precision on enrichment benchmarks

Stack: Python, FastAPI, PostgreSQL, LangGraph, Groq, Apify, Hunter.io, HubSpot API, Docker, React, TypeScript

Live dashboard · Code

<!-- TODO: delete this note once the hosted demo loads quickly -->

The hosted demo can be slow on first load.

SalesIntelligenceAgent: multi-agent research system

Takes a lead through discovery, enrichment, scoring, company research, person research, and a final synthesis, then syncs to the CRM.

Three LangGraph agents (company research, person research, synthesis) passing structured state with deterministic control flow
Automated output-quality check: scoring, validation, and a controlled rewrite step before anything goes downstream
FastMCP server exposing five operational tools
React + TypeScript dashboard showing live execution status

Stack: Python, FastAPI, PostgreSQL, LangGraph, FastMCP, Apify, Hunter.io, HubSpot, Instantly, Docker, React, TypeScript

Status: not deployed yet. Code

<!-- TODO: confirm ai_sales_intelligence is the right repo for this project -->
delivr-engine: notification delivery engine

A production-style notification delivery service with exponential backoff retry, audit logging, and real-time analytics, secured with JWT.

Stack: Java, Spring Boot, MySQL, JWT

Status: not deployed yet. Code

approval-workflow-engine: request and approval workflows

Employees raise leave requests and work requests from ready-made templates, and the requests route up to higher ops in the organization for approval.

Stack: TypeScript

Status: not deployed yet. Code

ai-summarizer: small demo

Paste a link, get a short AI summary of the page.

Live demo · Code

Other work

Freelance automation (2025 to present). Built n8n and Python automations for lead ingestion, qualification, enrichment, CRM sync, and email notifications. Used Apify Google Maps extraction to produce 55 qualified dental clinic leads in a structured sheet for field sales. Debugged live workflow failures, including payload field mismatches and exposed credentials.

Earlier data science projects (Jupyter notebooks): loan default analysis, credit risk, fraud detection, SaaS churn.

Skills

Languages: Python, async Python, Java, TypeScript, SQL Backend: FastAPI, Spring Boot, REST API design, background task processing, API integration Data: PostgreSQL, MySQL, SQLite, data ingestion, validation, transformation pipelines AI: LangGraph, LangChain, RAG, ChromaDB, structured outputs, multi-agent orchestration Frontend: React, TypeScript, Tailwind CSS, Vite DevOps and tools: Docker, Render, Vercel, Git, n8n, Apify
