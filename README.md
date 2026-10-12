# VINAY JOGANI

**Software Development Engineer at Amazon | ML & Agentic AI Systems | LLM Engineering, MLOps & Data Infrastructure**

Software Development Engineer at Amazon (Devices & Services), based in Irvine, CA. Previously a Machine Learning Engineer at RSK IT International, building real-time voice agents running in production at drive-thrus, toll booths, and parking lots. MS in Information Systems, Northeastern University (August 2025). I bridge research and production: 4 peer-reviewed publications on explainable AI and adversarial robustness, open-source AI infrastructure on PyPI and npm, and production systems from streaming audio pipelines to agentic LLM workflows.

**Resume:** [View Resume (PDF)](https://vinayjogani14.github.io/Vinay%20Jogani_Resume.pdf)

---

## About Me

I build ML systems that survive contact with production. I'm now a Software Development Engineer at Amazon in the Devices & Services organization.

Before Amazon, I built real-time voice AI at RSK IT International: streaming audio pipelines with 80-120 ms chunking, VAD and directed-speech gating, ASR/NLU integration, and intent routing into POS, tolling, and gate-control systems, holding end-to-end turn times under ~500 ms across 3 live sites, deployed on-prem and in hybrid edge/cloud setups for 3 production customers and 2 POCs.

I've also designed and shipped open-source AI infrastructure focused on making LLM and agentic systems reliable: evals, guardrails, and observability. Earlier, I did AI research at Northeastern's Amal Lab (medical image segmentation, 18TB+ multi-omics processing, multi-GPU training) and clinical data science at Brigham and Women's Hospital (transformer NLP over 10,000+ pharma reports, market microstructure analysis).

---

## Open-Source AI Infrastructure

| Project | What it does |
|---|---|
| [**tracewall**](https://github.com/VinayJogani14/tracewall) | Flight recorder + firewall for AI coding agents: records every tool call, tracks lethal-trifecta taint, blocks prompt-injection exfiltration. Zero dependencies, on PyPI. |
| [**spareloop**](https://github.com/VinayJogani14/spareloop) | Scheduler + optimizer for AI coding CLIs (Claude Code, Codex, Cursor): learns your usage rhythm, queues work into spare capacity, prewarms your usage window. On npm. |
| [**whichmodel**](https://github.com/VinayJogani14/whichmodel) | Describe your task, get one AI model recommendation backed by benchmarks and real developer sentiment. Zero-dependency, CI-validated dataset. |

## Featured Projects

| Project | Highlights |
|---|---|
| [Bank Reconciliation Agent](https://github.com/VinayJogani14/bank-recon-agent) | Production agentic pipeline (Claude tool calling + rules): 90.6% accuracy / 92.5% F1 on a golden eval suite, invariants, traces, replay |
| [Agentic RAG for 10-K Analysis](https://github.com/VinayJogani14/fireworks-rag-agent) | ReAct agent routing SQL + semantic search, 89% accuracy graded by LLM-as-a-judge |
| [Healthcare Data Pipeline](https://github.com/VinayJogani14/Healthcare-Data-Pipeline) | 10M+ patient records: Kafka + Spark Streaming, dbt medallion (31 models), Great Expectations, Terraform, Prometheus/Grafana |
| [Skin Cancer Classification at Scale](https://github.com/VinayJogani14/Skin-Cancer-Classification-Using-High-Parallel-Machine-Learning) | 91.8% across 35 conditions on 245K images; 3.37x training speedup via PyTorch DDP on 4x A100 + AMP |
| [NBA Injury Prediction System](https://github.com/VinayJogani14/NBA-Injury-Prediction-System) | Full MLOps: FastAPI at sub-100ms p95, 1000+ RPS, MLflow, Prometheus/Grafana, K8s |
| [BankNifty Vectorized Backtester](https://github.com/VinayJogani14/BankNifty-Strangle-Backtest) | 10.3M rows of 1-minute options data processed in under 8 seconds, zero loops |

---

## Experience

**Software Development Engineer, Amazon (September 2026 – Present)**
- Devices & Services organization, Irvine, CA

**Machine Learning Engineer, RSK IT International (September 2025 – August 2026)**
- Engineered low-latency streaming audio pipelines for drive-thru, toll-booth, and parking-lot voice agents across 3 live sites (80-120 ms chunking, VAD/directed-speech gating, ASR, intent routing), holding end-to-end turn times under ~500 ms
- Architected and deployed serving topologies for 3 production customers and 2 POCs across on-prem edge and hybrid edge/cloud, with containerized ASR/NLU microservices and gRPC/WebRTC streaming
- Built a RAG-based post-sales QA helper over ~75 internal runbooks and a three-agent ticket-routing layer, cutting misrouted tickets and cross-team handoffs

**AI/ML Research Assistant, Amal Lab, Northeastern University (June 2024 – August 2025)**
- Engineered Med-SAM medical image segmentation for multi-modal datasets (MRI, CT, histopathology) with fine-tuned transformer architectures
- Processed 18TB+ TCGA multi-omics data on Spark and Dask for biomarker discovery across 33+ cancer types
- Trained a production skin-cancer classifier to 97.28% accuracy with ensembles and external validation across 3 datasets

**Research Data Scientist, Brigham and Women's Hospital (August 2024 – December 2024)**
- Built transformer-based NLP analytics (BERT, RoBERTa) over 10,000+ pharmaceutical reports linking media sentiment to regulatory outcomes
- Designed a HIPAA-compliant meta-analysis framework across ClinicalTrials.gov and PubMed with statistical modeling

---

## Education

**Northeastern University, Boston, MA**
Master of Science in Information Systems (August 2025)
*Focused Coursework:* Advanced Data Science & Architecture, Parallel Machine Learning & AI, LLM with Knowledge Graph Databases, Natural Language Engineering, AI Generative Modeling with focus in Finance

**Veermata Jijabai Technological Institute, Mumbai, India**
Bachelor of Technology in Information Technology (June 2023)

---

## Technical Skills

**Programming:** Python, SQL, C++, TypeScript, Java, R, JavaScript, MATLAB, Cypher

**LLM & Agentic AI:** Claude API (tool calling, MCP), GPT-4o, LangChain, RAG, FAISS, ChromaDB, Sentence Transformers, CLIP, Prompt Engineering, LLM-as-a-Judge Evaluation, Agent Orchestration, Evals & Guardrails

**Voice & Real-Time Systems:** ASR/NLU Integration, Voice Activity Detection, gRPC/WebRTC Streaming, Real-Time Audio Chunking, Session State Machines, On-Prem/Edge/Hybrid Deployment

**Machine Learning & Deep Learning:** PyTorch, TensorFlow, Keras, Scikit-learn, XGBoost, LightGBM, CNN, Vision Transformers, GANs, Reinforcement Learning (PPO, DQN), Distributed Data Parallel, Multi-GPU Training, Optuna

**Data Engineering:** Apache Spark, PySpark, Kafka, Airflow, dbt, Dask, Stream Processing, ETL/ELT, Great Expectations, Medallion Architecture

**Databases & Cloud:** PostgreSQL, MySQL, MongoDB, Neo4j, Snowflake, BigQuery, Redis, Supabase, AWS (EC2, S3, Lambda), GCP (BigQuery, GCS, Pub/Sub)

**MLOps & Production:** Docker, Kubernetes, MLflow, CI/CD, GitHub Actions, Model Monitoring, Prometheus, Grafana, Terraform, FastAPI, gRPC, Package Publishing (PyPI, npm)

**Statistics & Experimentation:** A/B Testing, Bayesian Inference, Sequential Testing, Multi-Armed Bandits, Causal Inference, Time Series (ARIMA, GARCH), Monte Carlo

**Quantitative Finance:** Options Pricing (Black-Scholes, Heston, Monte Carlo), Portfolio Optimization, Vectorized Backtesting, Statistical Arbitrage, VaR/Expected Shortfall

---

## Publications

- [Analysis of Explainable AI Methods on Medical Image Classification](https://ieeexplore.ieee.org/document/10118312) - IEEE ICAECT 2023
- [Adversarial Attacks and Defenses for Skin Cancer Classification](https://ieeexplore.ieee.org/document/10080537) - IEEE ICONAT 2023
- [Intrusion Detection: A Deep Learning Approach](https://arxiv.org/abs/2306.07601) - IEEE ICEEICT 2023
- [Image Captioning Using Transformer: VisionAid](https://www.irjet.net/archives/V9/i10/IRJET-V9I1087.pdf) - IRJET 2022

---

## What Makes Me Different

I don't just build models, I build the entire system around them: streaming ingestion, serving, evals, monitoring, and the deployment that makes it real. I've published research AND shipped production code that paying customers run every day. I understand both the math and the engineering.

---

## Contact

- **Email:** joganivinay@gmail.com
- **Portfolio:** [https://vinayjogani14.github.io/](https://vinayjogani14.github.io)
- **LinkedIn:** [linkedin.com/in/vinayjogani](https://www.linkedin.com/in/vinayjogani/)
- **X:** [@jogani_vinay](https://x.com/jogani_vinay)
- **Google Scholar:** [View Profile](https://scholar.google.com/citations?hl=en&user=Xnowpo4AAAAJ)
- **Scopus ID:** [58030923600](https://www.scopus.com/authid/detail.uri?authorId=58030923600)
- **ORCiD:** [0009-0005-9568-5747](https://orcid.org/0009-0005-9568-5747)
