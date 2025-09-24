<!-- GitHub Profile · Adrián Infantes · Story/Impact Edition (EN) -->

<!-- HERO · Dark/Light aware -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.png">
    <img alt="Adrián Infantes — AI Solutions Architect Track" src="./assets/hero-light.png" width="940">
  </picture>
</p>

<h1 align="center">Adrián Infantes — AI Engineer → AI Solutions Architect</h1>
<p align="center">
  <em>LLMs · RAG · Agentic Systems · AI Security · GPU Serving</em><br/>
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

## 🎯 Summary
I design, deploy, and harden end-to-end AI systems: from datasets and fine-tuning to GPU serving and AI security (guardrails, red teaming, auditing). Near-term goal: **AI Solutions Architect** with production-grade metrics and reliability.

---

## 💼 Experience (what I used, why I used it, and what it achieved)

### BBVA — AI/ML Engineer (Senior) · 2024 → Present
**Context**: LLM platforms for banking, RAG over internal sources, enterprise-grade observability and compliance.

- **Technologies**
  - **Models/Tokenization**: GPT-4/LLaMA-3/Mistral, tiktoken, cross/biencoder re-rankers
  - **RAG/Agents**: LangChain, LangGraph, DSPy; Pinecone, Azure Cognitive Search, FAISS
  - **Serving/Infra**: vLLM, Triton Inference Server, TensorRT, CUDA; Docker, Kubernetes (HPA); Terraform
  - **MLOps/Observability**: Azure ML, MLflow, Prometheus/Grafana, OpenTelemetry, Evidently AI, Elasticsearch
  - **Speech/NLP**: Azure Speech, BERT, spaCy

- **Why I used it**
  - Build **verifiable RAG** with grounding and re-ranking for documentation and financial data
  - Orchestrate **tool-using agents** for back-office workflows with stable p95 latency and high SLA
  - Deliver **multi-tenant GPU serving** with autoscaling and cost control
  - Implement **observability**: accuracy, coverage, latency, citation quality; drift and data quality monitoring
  - **Harden** the LLM platform against prompt injection and context exfiltration

- **What it achieved (metrics)**
  - **+15%** accuracy on financial analysis tasks
  - **−20%** latency after GPU quantization; **p95 < 300 ms** on common queries
  - **SLA 99.95%** on assistants and **99.9%** on serving; **>500k** queries/month on core assistant
  - **−40%** time-to-market via standardized CI/CD and lifecycle governance
  - **+22%** AUC-ROC on credit-risk use cases; **50k docs/day** processed for near-real-time decisions

<!-- BBVA image (keep filename as provided; URL-encoded spaces/commas) -->
<p align="center">
  <img src="Generated Image September 24, 2025 - 10_42PM (1).png" alt="BBVA — Architecture & metrics" width="840"/>
</p>

---

### Ecoembes — Machine Learning Engineer (Mid) · 2020 → 2024
**Context**: Conversational AI 2.0, computer vision for recycling, and large-scale logistics optimization.

- **Technologies**
  - **NLP**: Multilingual BERT, spaCy, CRF, Word2Vec; Azure Databricks → Azure Container Instances
  - **CV**: TensorFlow 2, PyTorch, OpenCV; Azure IoT Hub, Stream Analytics; Synapse
  - **Optimization/Backend**: Google OR-Tools on Azure Batch
  - **MLOps/BI**: MLflow, Power BI Embedded, Application Insights

- **Why I used it**
  - Migrate RNN/LSTM chatbots to **BERT** with an end-to-end Azure pipeline
  - Design **hybrid architecture** for waste classification with industrial cameras
  - Rewrite **route optimization** heuristics and telemetry processing for logistics

- **What it achieved (metrics)**
  - **89%** intent accuracy (**+40%** vs previous generation) and **−40%** false positives
  - **85%** accuracy across 12 waste classes (**+15%** vs manual inspection)
  - **−25%** kilometers driven and **−18%** CO₂ in 2022–2023; dashboards powered by **50+** telemetry APIs
 

<!-- Ecoembes image (keep filename as provided; URL-encoded spaces/commas) -->
<p align="center">
  <img src="Generated Image September 24, 2025 - 10_54PM.png" alt="BBVA — Architecture & metrics" width="840"/>
</p>

---

### Capgemini — Data Scientist (Junior) · 2017 → 2020
**Context**: Analytics and ML for enterprise clients; data lake build-out, forecasting, and executive BI.

- **Technologies**
  - **ML/Stats**: scikit-learn, statsmodels, XGBoost; pandas/numpy
  - **Data**: Python ETL, SQL/SQLAlchemy; normalization, query tuning
  - **BI**: Tableau, Looker Studio; automated reporting

- **Why I used it**
  - Unify **10+ sources** into a data lake with reproducible ETL and data quality checks
  - Train **forecasting and scoring** models with traceability/versioning
  - Democratize **KPIs** via executive dashboards and parameterized reporting

- **What it achieved (metrics)**
  - **+20%** forecasting accuracy on product adoption
  - **−35%** SQL response times and **−30%** monthly analysis cycle
  - Saved **10 h/analyst/week** through report automation

<!-- Capgemini image (keep filename as provided; URL-encoded spaces/commas) -->
<p align="center">
  <img src="Generated%20Image%20September%2024,%202025%20-%2010_14PM.png" alt="Capgemini — Visual summary" width="820"/>
</p>

---

## 🧠 Core Technical Strengths
- **LLMs**: fine-tuning/QLoRA, robust prompting (DSPy), tool-using agents with verification  
- **RAG**: re-ranking, result fusion, groundedness/citations, full traceability  
- **GPU Serving**: vLLM, Triton, TensorRT, quantization (GGUF/AWQ), batching/throughput tuning  
- **MLOps**: MLflow, automated evals, drift monitoring, end-to-end lineage  
- **AI Security**: LLM threat modeling, guardrails, context isolation, auditing and policy enforcement  
- **Data**: SQL, PySpark, validation/lineage; vector DBs (Pinecone, Milvus, FAISS)

---

## 🧭 Education & Academic Path
- **Dual Degree (ongoing)** — Cybersecurity & Hacking + Mechatronics Engineering. Final year via Pearson agreement, Napier University, Edinburgh).
- **MIOTI — GenAI & Deep Learning** (2020–2021) ·
- **MIOTI — Big Data & Data Science** (2023–2024)
- **B.Sc. in Software Engineering** (UCJC) ·

---

## 🏅 Certifications (selected)
- AI-900 · AI-102 (Microsoft)
- NVIDIA Accelerated
- Data Literacy Fundamentals
- LangChain for LLM App Dev
- Intro to Cybersecurity
- Python for Advanced Tech Training

---

## 📊 What I monitor in production
Quality: accuracy, coverage, groundedness/citations, adversarial robustness  
Performance: p50/p95/p99 latency, tokens/s, GPU throughput, queueing  
Cost: cost per 1k tokens, per request, per tenant  
Reliability: uptime, error categories, SLOs/SLA and alerting

---

## 🗂️ Technology Matrix (by category)
<details>
  <summary><b>Open Tech Matrix</b></summary>

### Programming Languages
| Category | Technologies |
|---|---|
| General purpose | Python, C++ |
| Data/Query | SQL (ANSI, T-SQL), SQLAlchemy |
| Scientific/Stats | R |
| Scripting/CLI | Bash, PowerShell |

### ML/DL (Classical)
| Category | Technologies |
|---|---|
| Modeling | scikit-learn, XGBoost, statsmodels |
| Preprocessing | pandas, numpy, feature pipelines |
| Validation | MLflow (runs/models), cross-validation, pipeline testing |

### LLM & Generative AI
| Category | Technologies |
|---|---|
| Models | GPT-4/-o, LLaMA-2/3, Mistral |
| Fine-tuning | LoRA/QLoRA, FSDP/DeepSpeed |
| Serving | vLLM, Triton Inference Server, TensorRT |
| Tokenization/Parsers | tiktoken |
| Orchestration | LangChain, LangGraph, DSPy |
| Evaluation | Automated evals, groundedness/citations checks |

### RAG & Search
| Category | Technologies |
|---|---|
| Vector DBs | Pinecone, Milvus, FAISS |
| Search | Azure Cognitive Search, Elasticsearch |
| Re-ranking | Cross-encoders/bi-encoders, fusion strategies |
| Guardrails | Policy enforcement, content filters |

### NLP, CV & Multimodal
| Category | Technologies |
|---|---|
| NLP | BERT, spaCy, NLTK, CRF, Word2Vec |
| CV | TensorFlow 2, PyTorch, OpenCV |
| Speech | Azure Speech (ASR/TTS) |

### Data Engineering & Streaming
| Category | Technologies |
|---|---|
| ETL/Batch | PySpark, Azure Databricks, Synapse |
| Streaming/IoT | Azure IoT Hub, Stream Analytics |
| Data Lakes | Lake architectures, lineage tracking |

### MLOps, Observability & Governance
| Category | Technologies |
|---|---|
| MLOps | Azure ML, MLflow |
| Observability | Prometheus, Grafana, OpenTelemetry, Evidently AI |
| Governance | Model/version control, auditability, drift monitoring |

### Infrastructure, Cloud & DevOps
| Category | Technologies |
|---|---|
| Containers/Orchestration | Docker, Kubernetes, HPA |
| GPU | CUDA, TensorRT, quantization (GGUF/AWQ) |
| IaC | Terraform |
| Clouds | Azure, AWS, GCP |

### BI & Visualization
| Category | Technologies |
|---|---|
| Dashboards | Power BI, Tableau, Looker Studio |
| Data Apps | Dash/Plotly, FastAPI backends |

### Security & Compliance (AI-focused)
| Category | Technologies |
|---|---|
| AppSec for LLMs | Threat modeling, prompt guardrails, context isolation |
| Platform Security | Rate limiting, policy enforcement, audit trails |
| Testing | Prompt red teaming, adversarial evaluation |

</details>

---

## 🔧 Toolkit (quick view)
<p>
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C?logo=pytorch&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/TensorRT-76B900?logo=nvidia&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/vLLM-000000?style=flat-square"/>
  <img src="https://img.shields.io/badge/Triton%20Server-000000?style=flat-square"/>
  <img src="https://img.shields.io/badge/LangChain-000000?style=flat-square"/>
  <img src="https://img.shields.io/badge/MLflow-019B8F?style=flat-square&logo=mlflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
</p>

---

## 🗺️ Immediate Roadmap
- Shift-left security across AI pipelines  
- Zero-downtime, multi-tenant agent serving on K8s with intelligent autoscaling  
- Mechatronics integration: perception-decision-action with programmatic verification

---

## 📈 GitHub Stats (optional)
<!-- Transparent theme pairs well with both dark/light -->
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=infantesromeroadrian&theme=transparent&show_icons=true&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=infantesromeroadrian&layout=compact&theme=transparent&hide_border=true)
<!-- Optional: lowlighter/metrics → requires a GH Action to render metrics.svg -->
<!-- ![Metrics](./metrics.svg) -->

---

## 🤝 Collaboration
LLM architecture, RAG and tool-using agents with production criteria; AI hardening and red teaming; measurable PoCs with clear metrics.  
<a href="mailto:infantesromeroadrian@gmail.com">infantesromeroadrian@gmail.com</a> · <a href="https://www.linkedin.com/in/adrianinfantes">LinkedIn</a>


