# Ammons Data Labs

Ammons Data Labs builds intelligent, scalable systems that bridge applied AI, data engineering, and cloud architecture.

Right now the focus is on **Azure Digital Apps & AI consulting** — especially solutions that combine **Azure OpenAI**, **event-driven integration (Service Bus, Logic Apps)**, and **GitHub Actions CI/CD** in production-ready code.

---

## Highlighted Repositories (Azure Digital Apps & AI)

### [ADL M365 Invoice Automation Starter](https://github.com/ammons-datalabs/adl-m365-automation-starter)

Intelligent invoice processing and routing on Azure:

- **Azure Document Intelligence** for OCR and field extraction  
- **FastAPI** backend for orchestration and API surface  
- **Azure Service Bus** events for downstream workflows  
- **Azure Logic Apps + SharePoint + Teams** for human-in-the-loop approvals  
- **Pytest test suite** 65+ tests include Azure-integration tests  
- **GitHub Actions CI/CD**: tests, coverage, container build, and deploy

This repo is a concrete example of an end-to-end Azure app that mixes AI, integration, and automation.

---

### [Observable Agent Starter](https://github.com/ammons-datalabs/observable-agent-starter)

A production-ready template for building **observable AI agents**:

- **FastAPI** service hosting agentic flows  
- **DSPy** for structured prompting and agent composition  
- **Langfuse** for tracing, evaluation, and observability  
- **DeepEval** for regression-style LLM tests and guardrails  
- **GitHub Actions** for CI (90+ tests + high coverage) and deployment automation  

This is a starting point for Azure or OpenAI-backed GPT solutions where reliability and observability matter.

---

## Work in Progress (Active Builds)

These repos are in development and show where Ammons Data Labs is heading.

### [HoldThatThread](https://github.com/ammons-datalabs/HoldThatThread)

A **.NET 9 / C#** reasoning API that separates long-form “thinking” from quick answers:

- ASP.NET Core Web API designed to sit behind APIM  
- Azure OpenAI SDK integration, including streaming responses  
- Clean Architecture: Domain / Application / Infrastructure / API  
- 80+ xUnit tests, configuration validation, and Key Vault integration  

Good example of how I approach C#/.NET, Azure integration, and testing in 2025.

---

### [RoleSkills](https://github.com/ammons-datalabs/RoleSkills)

An **evidence-based portfolio assessment** engine:

- Parses role requirements into a structured skills model  
- Crawls repositories for **concrete proof** (files, tests, commits)  
- Scores coverage using relevance, authorship, recency, and code quality  
- Generates a requirement-by-requirement match report

---

### [O1 Agentic Planner](https://github.com/jaybea/O1AgenticPlanner)

A small but focused project exploring **multi-step agentic reasoning** with GPT models:

- Reproducible plans over multiple reasoning steps  
- JSON-first outputs suitable for automation  
- Designed as a lightweight building block for more complex agent workflows

---

## Research Roots

### [Evaluate-SCAIL](https://github.com/ammons-datalabs/Evaluate-SCAIL)

Long-running **research codebase** behind my work on encrypted deduplication:

- Advanced Python used over several years (data structures, performance tuning, and batch experiments)  
- Evaluation harnesses and analysis scripts for large-scale deduplication benchmarks  
- Directly supports the research that led to my **PhD** and a **published IEEE paper** on scalable, encrypted backup and storage systems  

This repo reflects the more experimental side of Ammons Data Labs: designing, testing, and stress-testing algorithms before they become production systems.

---

## What Ammons Data Labs Does

We design and deploy solutions that combine deep technical foundations with practical AI engineering:

- **AI & Data Engineering Consulting** — high-throughput data pipelines and intelligent workflows.  
- **Cloud Architecture & Modernisation** — scalable, secure systems on Azure (and selected AWS workloads).  
- **Agentic Workflow Automation** — FastAPI, DSPy, Langfuse, and DeepEval for robust, observable AI services.  
- **Encrypted Deduplication Systems** — research-grade designs for scalable, privacy-preserving backup and storage.

---

## Contact

- Email: [jaybe@ammonsdatalabs.com](mailto:jaybe@ammonsdatalabs.com)  
- LinkedIn: [linkedin.com/in/jaybeammons](https://linkedin.com/in/jaybeammons)  
- Website: [ammonsdatalabs.com](https://ammonsdatalabs.com/)
