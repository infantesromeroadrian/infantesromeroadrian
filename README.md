<!-- GitHub Profile · Adrián Infantes · Story/Impact Edition (EN) -->

<!-- HERO · Dark/Light aware -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.png">
    <img alt="Adrián Infantes — AI Solutions Architect Track" src="./assets/hero-light.png" width="940">
  </picture>
</p>

<h1 align="center">Adrián Infantes</h1>
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com/?lines=AI+Solutions+Architect;AI+Security+Engineer;Cloud+AI+Engineer;Adversarial+ML+%26+Red+Teaming&font=Fira+Code&center=true&width=600&height=30&color=3298dc&vCenter=true&pause=1000" alt="Typing SVG">
  </a>
</p>

<p align="center">
  <em>Architecting secure, scalable, and production-grade AI systems on the Cloud.</em><br/>
  <br/>
  <a href="mailto:infantesromeroadrian@gmail.com">
    <img src="https://img.shields.io/badge/Email-contact-DB4437?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://www.linkedin.com/in/adrianinfantes">
    <img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="https://github.com/infantesromeroadrian">
    <img src="https://img.shields.io/badge/GitHub-follow-181717?style=flat-square&logo=github" alt="GitHub">
  </a>
</p>

---

> 🛰️ **I design, attack and defend AI systems in regulated environments.**  
> - **Who:** AI/ML engineer focused on AI Security & Cloud Architecture in banking/FinCrime.  
> - **What:** Build & harden LLM/RAG platforms on Kubernetes + AWS, with real SLAs and audits.  
> - **Proof:** Zero-Trust LLM stack @BBVA, multi-tenant RAG, measurable lifts in risk & fraud models.

---

## 🎯 Summary

I don't just build AI models; I engineer the **secure cloud ecosystems** that enable them to run in production.

My focus sits at the intersection of **Generative AI**, **Cloud Engineering**, and **Cybersecurity**. I bridge the gap between cutting-edge LLM capabilities (RAG, Agents) and the rigorous demands of enterprise environments (Banking/FinTech). My mission is to deploy systems that are not only intelligent but also resilient, auditable, and hardened against adversarial threats.

---

## 🧠 Core Technical Strengths

* **AI & Cloud Architecture:** `K8s Autoscale` `Multi-tenant GPU Serving` `Serverless AI` `Hybrid Cloud` `Terraform IaC`
* **AI Security & Hardening:** `LLM Red Teaming` `Prompt Guardrails` `PII Redaction Pipelines` `OWASP LLM Top 10` `Model Governance`
* **Generative AI Core:** `Production RAG` `Agentic Systems (LangGraph)` `Fine-tuning (QLoRA)` `DSPy Robust Prompting`

---

## ⚡ Impact at a Glance

| Company      | Role                        | Focus                                 | Key Impact |
|-------------|-----------------------------|---------------------------------------|-----------|
| **BBVA**        | AI/ML Engineer (Senior)     | Secure LLM/RAG platform, FinCrime AI  | Zero-Trust LLM stack, +22% AUC credit-risk, 500k+ guarded queries/month |
| **Ecoembes**    | ML Engineer (Mid)           | Edge CV + Conversational AI           | 89% intent acc., 85% waste classification, −25% logistics km |
| **Capgemini**   | Data Scientist (Junior)     | Data lake, forecasting, BI            | +20% forecast accuracy, −30% analysis cycle time, 10h/analyst/week saved |

---

## 💼 Experience (what I used, why I used it, and what it achieved)

### BBVA — AI/ML Engineer (Senior) · 2024 → Present

**Context**: Architecting secure, multi-tenant LLM platforms for banking. RAG over highly sensitive internal sources with enterprise-grade compliance.

* **The "Why" (Architectural Decisions):**
  * Moved beyond basic RAG to build **verifiable, grounded systems** with re-ranking, crucial for financial data integrity.
  * Engineered **hardened LLM platforms** adopting a "Defense in Depth" approach against prompt injection and context exfiltration.
  * Delivered **cost-efficient GPU compute** via Kubernetes (HPA) and Triton/vLLM, balancing performance with FinOps.

* **The Impact (Metrics):**
  * 🛡️ **Zero Trust AI**: Implemented guardrails processing **>500k queries/month** with 99.95% SLA.
  * ⚡ **Cloud Efficiency**: **−20%** latency via GPU quantization; **p95 < 300 ms** on secure infrastructure.
  * 📈 **Business Value**: **+15%** accuracy on financial analysis tasks & **+22%** AUC-ROC on credit-risk cases.

<h3 align="center">⚡ Visualizing a Secure RAG Architecture (Conceptual)</h3>
<p align="center">
Isolating ingestion, retrieval, and generation layers with security boundaries.
</p>

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#24292e', 'edgeLabelBackground':'#ffffff', 'tertiaryColor': '#f0f0f0'}}}%%
graph LR
    subgraph Client Layer
        A[User Request] --> B(API Gateway / WAF);
    end
    
    subgraph Secure Cloud Zone
        B --> C{Security Middleware};
        C -- "Prompt Injection Check" --> D[Guardrails Service];
        D -- "Blocked" --> E((Audit Log & Deny));
        D -- "Safe" --> F[LangChain Orchestrator];
        
        subgraph Retrieval Layer
            F --> G[(Vector DB - Private Subnet)];
            G -- "Context + Citations" --> F;
        end
        
        subgraph Generation Layer
            F --> H["LLM Serving (Triton/vLLM on GPU K8s)"];
            H -- "Generated Answer" --> C;
        end
    end
    
    C -- "Output Validation & PII Redaction" --> I[Final Response];
    I --> A;

        style B fill:#f9f,stroke:#333,stroke-width:2px
    style D fill:#ffcccc,stroke:#f00,stroke-width:2px
    style G fill:#ccf,stroke:#333,stroke-width:2px,stroke-dasharray: 5 5
    style H fill:#ccf,stroke:#333,stroke-width:2px
    style C fill:#ffffcc,stroke:#ee0
```

<!-- BBVA image -->
<p align="center">
  <img src="Generated Image September 24, 2025 - 10_42PM (1).png" alt="BBVA — Architecture & metrics" width="840"/>
</p>

---

### Ecoembes — Machine Learning Engineer (Mid) · 2020 → 2024

**Context**: Hybrid Cloud & Edge AI. Conversational AI 2.0 and computer vision on the edge for recycling logistics.

* **The "Why" (Architectural Decisions):**
  * Designed a **hybrid architecture (Cloud + Edge)** to run heavy Computer Vision models locally on industrial cameras with cloud synchronization.
  * Migrated legacy chatbots to end-to-end BERT pipelines on containerized infrastructure.

* **The Impact (Metrics):**
  * **89%** intent accuracy (**+40%** lift) on conversational AI.
  * **85%** accuracy in edge-based waste classification.
  * **−25%** logistics kilometers driven via large-scale optimization backend.

<!-- Ecoembes image -->
<p align="center">
  <img src="Generated Image September 24, 2025 - 10_54PM.png" alt="Ecoembes — Architecture & metrics" width="840"/>
</p>

---

### Capgemini — Data Scientist (Junior) · 2017 → 2020

**Context**: Analytics and ML for enterprise clients; data lake build-out, forecasting, and executive BI.

- **Technologies**
  - **ML/Stats**: scikit-learn, statsmodels, XGBoost; pandas/numpy
  - **Data**: Python ETL, SQL/SQLAlchemy; normalization, query tuning
  - **BI**: Tableau, Looker Studio; automated reporting

- **Why I used it**
  - Unify **10+ sources** into a data lake with reproducible ETL and data quality checks.
  - Train **forecasting and scoring** models with traceability/versioning.
  - Democratize **KPIs** via executive dashboards and parameterized reporting.

- **What it achieved (metrics)**
  - **+20%** forecasting accuracy on product adoption.
  - **−35%** SQL response times and **−30%** monthly analysis cycle.
  - Saved **10 h/analyst/week** through report automation.

<!-- Capgemini image -->
<p align="center">
  <img src="Generated%20Image%20September%2024,%202025%20-%2010_14PM.png" alt="Capgemini — Visual summary" width="820"/>
</p>

---

## 📊 What I Monitor in Production (The Architect's Dashboard)

1. **Security & Risk:** Prompt injection attempts blocked, PII leakage detection rate, adversarial drift.
2. **Reliability & SLOs:** p95/p99 latency against targets, GPU saturation vs throughput, error budgets.
3. **RAG Quality:** Groundedness score (hallucination check), retrieval precision/recall, citation accuracy.

---

## 🧱 Secure AI & Cloud Stack

<details open>
  <summary><b>🚀 Cloud, MLOps & Observability</b></summary>
  <br>

| Category | Technologies |
|---|---|
| **Cloud** | AWS (core), Azure (multi-cloud strategy) |
| **Compute** | Amazon EKS, EC2 (g5/p4 instances), Lambda, GPU K8s clusters |
| **IaC & DevOps** | Terraform, GitHub Actions, AWS CDK |
| **MLOps & Obs.** | Amazon SageMaker Pipelines, MLflow, Prometheus, Grafana, OpenTelemetry, Evidently AI |

</details>

<br>

<details open>
  <summary><b>🛡️ AI Security & Governance</b></summary>
  <br>

| Category | Technologies |
|---|---|
| **LLM AppSec** | Prompt Guardrails, custom LangChain security middleware, threat modeling |
| **Red Teaming** | Adversarial ML evaluation, jailbreak test-suites, policy fuzzing |
| **Compliance** | PII masking pipelines, audit trails, AWS KMS, IAM hardening, WAF, policy enforcement |

</details>

<br>

<details>
  <summary><b>🧠 GenAI & Data</b></summary>
  <br>

| Category | Technologies |
|---|---|
| **Models** | GPT-4o, LLaMA-3, Mistral (Fine-tuning with QLoRA) |
| **Orchestration** | LangChain, LangGraph (Agentic flows), DSPy, Amazon Bedrock Agents |
| **RAG Stack** | Pinecone, Amazon OpenSearch Vector Engine, hybrid search + cross-encoder re-ranking, Bedrock Knowledge Bases |
| **Data Eng** | Python, SQL, PySpark, data lakes / lakehouse architectures |

</details>

---

## 📈 GitHub Stats

<p align="center">
  <a href="https://github.com/infantesromeroadrian">
    <img
      height="180"
      src="https://github-readme-stats.vercel.app/api?username=infantesromeroadrian&show_icons=true&theme=transparent&hide_border=true"
      alt="GitHub Stats"
    />
  </a>
  <a href="https://github.com/infantesromeroadrian">
    <img
      height="180"
      src="https://github-readme-stats.vercel.app/api/top-langs/?username=infantesromeroadrian&layout=compact&theme=transparent&hide_border=true"
      alt="Top Languages"
    />
  </a>
</p>


---

## 🔧 Toolkit (Quick View)

<p>
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C?logo=pytorch&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/TensorRT-76B900?logo=nvidia&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/LangChain-000000?style=flat-square"/>
  <img src="https://img.shields.io/badge/MLflow-019B8F?style=flat-square&logo=mlflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
</p>

---

## 🧭 Education & Academic Path

* **BEng (Hons) Software Engineering with Cybersecurity** (Ongoing) — Edinburgh Napier University. *Focus on secure coding and systems defense.*
* **Master in GenAI & Deep Learning** (2020–2021) — MIOTI.
* **Master in Big Data & Data Science** (2023–2024) — MIOTI.
* **B.Sc. in Software Engineering** (UCJC).

---

## 🏅 Certifications (Cloud & AI Focus)

* **AWS Certified Solutions Architect – Associate** (SAA-C03)
* **AWS Certified Machine Learning Engineer - Associate** (MLA-C01) *[Target 2025]*
* **NVIDIA Certified Associate** — AI in the Data Center
* **DeepLearning.AI** — Generative AI with LLMs
* **LangChain Academy** — Introduction to LangGraph
* **ISC2** — Certified in Cybersecurity (CC)

---

## 🗺️ Immediate Roadmap

- **Shift-left Security:** Integrating LLM Red Teaming into CI/CD pipelines.
- **Agentic Scale:** Deploying multi-agent systems on EKS with zero-trust networking.
- **Hardware Optimization:** Deep dive into AWS Trainium/Inferentia for cost reduction.

---

## 🧪 Featured Repositories

> Update the links once the repos are public. These are meant as *proofs*, not just code dumps.

| Repo | What it proves | Link |
|------|----------------|------|
| **banking-secure-rag-platform** | End-to-end secure RAG on K8s with guardrails, audit logging and FinCrime use cases. | [`github.com/infantesromeroadrian/banking-secure-rag-platform`](https://github.com/infantesromeroadrian/banking-secure-rag-platform) |
| **ai-red-teaming-toolkit** | Adversarial ML & jailbreak harness for LLM apps with reporting. | [`github.com/infantesromeroadrian/ai-red-teaming-toolkit`](https://github.com/infantesromeroadrian/ai-red-teaming-toolkit) |
| **jarvis-local-assistant** | Local-first AI assistant (LLM + voice) orchestrated via LangGraph/Ollama. | [`github.com/infantesromeroadrian/jarvis-local-assistant`](https://github.com/infantesromeroadrian/jarvis-local-assistant) |
| **fraud-graph-analytics-lab** | Graph-based fraud detection + LLM copilot flows for analysts. | [`github.com/infantesromeroadrian/fraud-graph-analytics-lab`](https://github.com/infantesromeroadrian/fraud-graph-analytics-lab) |

---

## 🧾 For Hiring Managers & CTOs

- **Roles I fit best:** AI Solutions Architect · AI Security Engineer · Cloud AI Engineer (K8s + LLMs).  
- **Domains where I’m strongest:** Banking, Financial Crime Prevention, regulated environments.  
- **What I actually enjoy:** designing, attacking and hardening LLM/RAG systems in production, not just PoCs.  
- **Location / Work mode:** Based in Spain, open to EU/UK-remote; English/Spanish working proficiency.

---

## 🤝 Collaboration Scope

I'm looking to collaborate on projects designed for production, not just PoCs. Let's connect if you are building:

* Secure, multi-agent systems on Kubernetes.
* Financial grade RAG with strict compliance requirements.
* AI Red Teaming exercises and hardening strategies.

<p align="center">
  <a href="mailto:infantesromeroadrian@gmail.com">infantesromeroadrian@gmail.com</a> · <a href="https://www.linkedin.com/in/adrianinfantes">LinkedIn</a>
</p>
