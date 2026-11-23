<h1 align="center">Anuroop</h1>

<p align="center">
  <strong>Software Engineering · Backend Systems · Automation · Applied AI</strong>
</p>

<p align="center">
  I build software that connects complex workflows to useful, testable systems — from browser automation and API-backed products to retrieval pipelines, data applications, and computer-vision models.
</p>

<p align="center">
  <a href="https://autonomous-career-agent-cloud.pages.dev/#/">Career Agent · Live Website</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/anuroop258">GitHub</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/anuroop258?tab=repositories">All repositories</a>
</p>

---

## What I build

- **Backend and workflow systems** — APIs, browser automation, stateful workflows, integrations, and human-reviewed actions.
- **Applied AI and retrieval** — agent orchestration, hybrid search, reranking, document ingestion, and tool-using research systems.
- **Data and machine learning applications** — analytics pipelines, computer vision, segmentation, and measurable model evaluation.

I prefer engineering work where the behavior can be inspected, tested, and explained — not just demonstrated once.

## Selected engineering work

### 01 · [Autonomous Career Agent](https://github.com/anuroop258/autonomous-career-agent-cloud)
**A multi-portal job-search and application workspace**

Built a platform that brings together portal-specific browser agents, job-description screening, resume tailoring, reusable application answers, recruiter workflows, and a web dashboard.

- Six portal integrations in the codebase: Naukri, Indeed, LinkedIn, Shine, TimesJobs, and Glassdoor.
- Python and Playwright automation with a FastAPI backend and React + TypeScript dashboard.
- Includes application tracking, approval flows, logs, and a dedicated Custom Q&A workflow.
- Designed with explicit eligibility checks and verification steps; a browser click is not treated as proof of a successful submission.

**[Open live website](https://autonomous-career-agent-cloud.pages.dev/#/)** · **[Explore the code](https://github.com/anuroop258/autonomous-career-agent-cloud)**

### 02 · [Multi-Source Agentic RAG](https://github.com/anuroop258/multi-source-agentic-rag)
**A research assistant that combines documents, web sources, and tool use**

Designed a LangGraph-based research workflow that can retrieve from uploaded documents and use web-research tools, while exposing the steps taken by the agent.

- Hybrid retrieval: ChromaDB dense search + BM25 keyword search.
- Reciprocal Rank Fusion followed by Cross-Encoder reranking.
- Document ingestion for PDF, DOCX, TXT, Markdown, and CSV.
- SQLite conversation history, bounded tool-calling loop, and a FastAPI-served React interface.
- Uses GPT-OSS 120B through Groq for generation; embeddings and reranking run through local open-source models.

**[Explore the code](https://github.com/anuroop258/multi-source-agentic-rag)**

### 03 · [DroneVision](https://github.com/anuroop258/Dronevision)
**Aerial-image analysis for road-construction monitoring**

Implemented a computer-vision pipeline that segments road regions in drone imagery and compares images captured at different times to highlight possible construction changes.

- ResNet-34 encoder + U-Net decoder for road segmentation.
- SSIM-based difference maps and IoU comparison for change analysis.
- The repository reports held-out project-evaluation results of **0.89 IoU**, **94.6% pixel accuracy**, and **0.91 F1**; these are the figures documented in the project report.

**[Explore the code](https://github.com/anuroop258/Dronevision)**

### 04 · [Retail Sales Analytics](https://github.com/anuroop258/Retail-Sales-Analytics)
**A tested analytics workflow from transactions to business insights**

Built a Python analytics pipeline and Streamlit dashboard over **15,000 synthetic retail orders** spanning 20 stores and five regions.

- Data cleaning and typed transformations with Pandas and NumPy.
- Reusable KPI and aggregation functions, with equivalent SQL queries.
- Streamlit + Plotly dashboard with filters, drill-downs, and CSV export.
- Analytics logic is separated from the UI and covered by unit tests documented in the repository.

**[Explore the code](https://github.com/anuroop258/Retail-Sales-Analytics)**

## Engineering approach

- Reproduce the behavior before changing it; trace the actual implementation rather than guessing from symptoms.
- Prefer small, reviewable changes that preserve working behavior.
- Add regression tests for the behavior being fixed and run the relevant checks.
- Use deterministic rules for high-consequence decisions, with explicit human review where needed.
- Document setup, limitations, and what has actually been verified.

## Technical toolkit

| Area | Tools and technologies |
|---|---|
| Languages | Python, Java, C++, C, SQL |
| Backend and APIs | FastAPI, Flask, REST APIs, PostgreSQL, SQLite |
| Automation | Playwright, browser/CDP workflows, GitHub Actions |
| AI and retrieval | LangGraph, LangChain, RAG, FAISS, ChromaDB, BM25, Sentence Transformers, Cross-Encoder reranking |
| ML and data | TensorFlow, Keras, PyTorch, Pandas, NumPy, Matplotlib, OpenCV, scikit-image |
| Interfaces | React, TypeScript, Streamlit, Plotly |
| Engineering tools | Git, Docker, Cloudflare Pages, Cloudflare D1 |

## Current focus

Going deeper into backend engineering and established software codebases: correctness, API behavior, concurrency, data integrity, testing infrastructure, and maintainable developer tooling — alongside applied AI systems.

## Background

**Electronics and Communication Engineering** · Vasavi College of Engineering, Hyderabad · 2022–2026

**Based in:** Hyderabad, India · **Open to:** Software engineering opportunities

---

<p align="center"><em>Build it. Measure it. Test it. Make the evidence easy to inspect.</em></p>
