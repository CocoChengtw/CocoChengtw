### Hi, I'm Coco (HsiuWen Cheng)

**Data Scientist / ML Engineer · 7 years building ML for Trust & Safety, fraud, and health data**

I take ML from problem framing to production: defining the right metric, building models that handle messy, imbalanced real-world data, and measuring whether they actually changed outcomes.

- **Trust & Safety / Fraud** — Senior DS at Trend Micro (scam SMS classification, deepfake detection); Data Scientist Intern at TikTok Integrity & Safety
- **Experimentation & causal inference** — Scaled experimentation and campaign measurement for 200+ stakeholders at Far EasTone (~$430K/year value)
- **Health AI: time series & offline RL** — CGM glucose time-series prediction; researcher at UCLA applying offline reinforcement learning to personalized CGM wear scheduling
- MSBA, UCLA Anderson (2026)

---

### Selected work

| Project | What it shows |
|---|---|
| [**Smishing Scam-Type Classifier**](https://github.com/CocoChengtw/smishing-scam-type-classifier) | Multilingual scam-type classification on 34k public smishing messages; template-aware splits expose a 3-point leakage gap, and confidence routing auto-labels 60% of traffic at 96.8% accuracy |
| [**Multi-Agent Dispatch QA (team)**](https://github.com/ucla-msba-s3/seewees-ai-agents-s3) | 4-person UCLA MSBA project extending a LangGraph demo into an audited multi-agent pipeline for specialty-medicine logistics. I built the deterministic AuditAgent (7 rules; failed plans loop back to the planner), the what-if ScenarioAgent, audit routing in the graph, a Gemini backend with an LLM call-budget guard, and tests |
| [**Food-101 CV Benchmark**](https://github.com/CocoChengtw/food101-cv-models) | Systematic comparison of 14 architectures (ResNet → ConvNeXt → ViT); ConvNeXt-Base reached 87.9% top-1 with full fine-tuning |
| [**Deepfake Detection**](https://github.com/CocoChengtw/DeepfakeDetection) | CNN forgery detection on public data, with threshold tuning from ROC/PR analysis |
| [**Lip-Sync Deepfake Detection**](https://github.com/CocoChengtw/LipsyncDetection) | LLM-guided video preprocessing; documents each iteration from 23% to 58% F1 |
| [**Airbnb Market Intelligence Pipeline**](https://github.com/CocoChengtw/airbnb-market-intelligence-pipeline) | Bronze→Silver→Gold pipeline across 4 cities: Spark + Sedona geospatial joins, Airflow, Snowflake |

**Impact highlights from industry work** (code proprietary)
- Multi-layer transformer classifier (EN/JA) sorting scam SMS into 19 sub-categories under severe class imbalance, deployed for daily inference
- Deepfake-detection false-positive fixes that cut user complaints from thousands to dozens

---

### Toolkit
**ML:** PyTorch · Hugging Face · scikit-learn · time-series forecasting (LSTM) · offline RL (CQL, FQE)  
**Data & MLOps:** Spark · Airflow · Snowflake · Databricks · FastAPI · Docker  
**Analysis:** Causal inference (DiD) · A/B testing · Tableau · Looker Studio  
**Languages:** English · 繁體中文

**Contact:** [Website](https://cocochengtw.github.io) · [LinkedIn](https://www.linkedin.com/in/hsiu-wen-cheng/) · [chenghsiuwen.tw@gmail.com](mailto:chenghsiuwen.tw@gmail.com)
