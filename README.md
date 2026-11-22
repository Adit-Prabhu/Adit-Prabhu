<div align="center">

<img src="./assets/hero-banner.svg" alt="Adit Prabhu | M.S. CS @ Columbia · AI Systems, ML Engineering & Game Dev" width="100%" />

<br />

<a href="https://adit-prabhu.github.io/">
  <img src="./assets/press-start.svg" alt="Play Interactive 2D Portfolio | adit-prabhu.github.io" width="460" />
</a>

<br />

<a href="https://adit-prabhu.github.io/">
  <img src="https://img.shields.io/badge/Portfolio-adit--prabhu.github.io-111318?style=flat-square&logo=googlechrome&logoColor=22d3ee" alt="Interactive Portfolio" />
</a>
<a href="https://www.linkedin.com/in/adit-prabhu">
  <img src="https://img.shields.io/badge/LinkedIn-Adit_Prabhu-111318?style=flat-square&logo=linkedin&logoColor=0A66C2" alt="LinkedIn" />
</a>
<a href="mailto:ap4806@columbia.edu">
  <img src="https://img.shields.io/badge/Email-ap4806%40columbia.edu-111318?style=flat-square&logo=gmail&logoColor=f472b6" alt="Email" />
</a>
<a href="https://github.com/Adit-Prabhu">
  <img src="https://img.shields.io/badge/GitHub-@Adit--Prabhu-111318?style=flat-square&logo=github&logoColor=f2f2ee" alt="GitHub" />
</a>

</div>

---

### About

I'm **Adit Prabhu**, an M.S. in Computer Science student at **Columbia University** (ML Track, **4.0/4.0 GPA**, Expected Dec 2026). I build **production ML systems, agentic LLM workflows, physics world models, and retro-inspired games**, previously shipping AI and systems engineering work at **Rivian & Volkswagen Group Technologies**, **RBC Capital Markets**, and **MUFG**.

Before Columbia, I earned my B.S. in Computer Science (**4.0/4.0 GPA**, Dec 2024) from **Arizona State University**, where I conducted security and privacy research in the [**PERSUE Lab**](https://persue-lab-asu.github.io/team/) under Dr. Rakibul Hasan and published in **PoPETs 2025**.

<div align="center">
  <img src="./assets/character-sheet.svg" alt="Adit Prabhu | Profile Overview & Technical Loadout" width="100%" />
</div>

---

### Experience

| Role & Organization | Location & Term | Impact Highlights |
| :--- | :--- | :--- |
| **AI/ML Intern**, Rivian & Volkswagen Group Technologies | Palo Alto, CA · May 2026 – Aug 2026 | Shipped an end-to-end smart climate recommender (**+11%** offline Recall@K/Precision@K/accuracy, rolling out to **150,000+ vehicles**), built an EV charge time estimation model (**10.6% MAPE**, **15% relative gain** over production), and adapted an agentic `autoresearch` experimentation loop cutting tuning from months to **under 1 week**. |
| **AI Engineer Intern**, RBC Capital Markets | New York, NY · Jan 2026 – May 2026 | Engineered a deep LLM agent with **10+ specialized tools** (scenario PnL, leveraged credit, VaR) cutting turnaround **80%**, optimized orchestration via inference caching & dynamic routing (**-65% latency, -40% LLM cost**), and built hybrid RAG across **15+ risk workflows on 4+ desks** (**+25% reasoning accuracy**). |
| **Software Engineer (Intern → Full-Time)**, MUFG | Tempe, AZ · Jun 2024 – Aug 2025 | Built anomaly detection & validation services covering **500+ employees** (**+23%** reporting accuracy), shipped Python microservices automating audit workflows across **3+ regions** (uncovering 4+ control gaps), and tuned SQL/batch jobs from **7+ hrs → under 30 min** (**+17%** data accuracy). |
| **Research Assistant**, PERSUE Lab, ASU | Tempe, AZ · Aug 2023 – Jun 2024 | Built the PII-detection ML pipeline and **Swift/Kotlin** instrumentation analyzing **50M+ messages across 3,000+ Zoom Marketplace apps** for the **PoPETs 2025** privacy audit. |

---

### Selected Projects

| Project | Domain | Summary & Links | Stack |
| :--- | :--- | :--- | :--- |
| **[Overload](https://github.com/Adit-Prabhu/overload)** | Game AI / Action | 256×144 pixel-art top-down shooter (Columbia COMS E6998 final project): 3-sector campaign, 3 three-phase Regulator bosses, 5 evolvable base powers + 30 chance-fused powers, original soundtrack + 81 SFX, and a Cloudflare Worker adaptive rival backed by Vertex AI with strict Evidence v4 schema & deterministic fallback. | `Python` `pygame-ce` `TypeScript` `Cloudflare Workers` `Vertex AI` `Zod` |
| **[Abuse (1996) Remake](https://github.com/Adit-Prabhu/abuse_remake)** | Game Engine / Agent Eval | Faithful 15 Hz Level 1 reconstruction from the original C engine, Common Lisp rules, and level files (COMS E6998 midterm), paired with a 5-op JSONL agent interface benchmarking an LLM player vs. scripted search. [**Watch Demo ↗**](https://youtu.be/Sv1Ex4Y5H7M) | `Python` `pygame-ce` `C/C++` `Common Lisp` `LLM SDKs` |
| **[Foresight Worlds](https://github.com/amaan784/foresight-worlds)** | Physics World Models | Built at the Gemini 4 NYC Hackathon (Nov 2026): lifts 3 seconds of real video into a fitted `pymunk` physics simulation to predict the next 5 seconds of object trajectories for robotics & Physics-IQ evaluation. [**Watch Demo ↗**](https://youtu.be/uZtcHMUKOVQ) | `Python` `FastAPI` `pymunk` `Gemini` `Vite` `TypeScript` |
| **[Dynamic NPC Ecosystem](https://github.com/Adit-Prabhu/Dynamic_NPC_Ecosystem)** | Multi-Agent Simulation | Autonomous multi-agent NPC sandbox: fine-tuned **LLaMA 3.1 8B** via **QLoRA (4-bit)** generating internal monologue + dialogue in a single forward pass, paired with **NetworkX GraphRAG** memory over 100s of entities, Chain-of-Thought (*"Thought Bubble"*) inspection, and viral rumor propagation. | `Python` `LLaMA 3.1` `QLoRA` `NetworkX GraphRAG` `FastAPI` `React / TS` |
| **[AdBlocker RPG](https://github.com/Adit-Prabhu/AdBlocker-RPG)** | Browser Extension / Game | Chrome Extension (Manifest V3) that turns web ads and trackers into tiered monsters (*Tracker-Spider → Fullscreen-Hydra*) with click combat, XP/Gold progression, and a persistent local backend. | `JavaScript` `Chrome MV3` `CSS` `Python` `Flask` |
| **[Kubernetes Self-Healing Agent](https://github.com/sreeram0407/amlc-k8s-self-healing-agent)** | Cloud / Autonomous SRE | Columbia AMLC Spring 2026: autonomous GKE/K8s pod diagnosis and guardrail-gated remediation via 10 MCP tools, authoring the `SKILL.md` runbook, 2-tier Claude model routing (Haiku 4.5 / Sonnet 4.6), and Slack escalation templates. | `Python` `Claude API` `MCP` `GKE / Kubernetes` `SQLite` `Slack` |
| **[Dream Camera](https://github.com/Adit-Prabhu/DreamCamera)** | Multimodal RAG | Local-first multimodal photo library supporting semantic search by vibe/mood or reference image (with GPS & date filters) plus visual, temporal, and hybrid AI album clustering & naming. | `Python` `CLIP` `BLIP` `ChromaDB` `Streamlit` `React / TS` |
| **[BillCheck / MedClear](https://github.com/krishrveera/MedClear)** | Healthcare Verification | Deterministic, auditable medical billing verification engine backed by CMS Medicare Fee Schedule, NCCI, ICD-10, and FDA tables producing dollar-quantified discrepancy reports. | `Python` `FastAPI` `OAuth 2.0` `CMS / NCCI / ICD-10` |

<details>
<summary><strong>Additional Public Projects & Contributions</strong></summary>

- **[Sentinel AI](https://github.com/amanupg/sentry-project)**: Multi-agent Neo4j + Next.js 14 + ElevenLabs accountability investigator.
- **[Motivation Atlas: "Dragon's Hoard"](https://github.com/columbia-university-ai-games/motivation-atlas)**: Contributed the *Dragon's Hoard* chance minigame to Columbia AI Games' interactive motivation explorer.
- **[Deep Stock](https://github.com/Adit-Prabhu/deep-stock)**: Hybrid CNN + LSTM + market-sentiment stock predictor combining price chart images, time-series features, and sentiment analysis (Test MAE `0.0508`).
- **[Automated Counter](https://github.com/automated-street-environment-detection/automated-counter)**: OpenCV/Tkinter computer-vision street traffic video counter.

</details>

---

### Published Research

> **Who's Watching You Zoom? Investigating Privacy of Third-Party Zoom Apps**
> Saharsh Goenka, **Adit Prabhu**, Payge Sakurai, Mrinaal Ramachandran, Rakibul Hasan *(PERSUE Lab, ASU)*
> **Proceedings on Privacy Enhancing Technologies (PoPETs) 2025, Issue 4, pp. 530–548** · DOI: `10.56553/popets-2025-0143`
>
> A one-year longitudinal audit of **50M+ messages across 3,000+ third-party Zoom Marketplace apps** using a custom PII-detection ML pipeline and Swift/Kotlin instrumentation to investigate data over-collection, privacy policy transparency, and potential compliance gaps.
>
> [![PoPETs 2025 PDF](https://img.shields.io/badge/PoPETs_2025-Read_PDF-111318?style=flat-square&logo=adobeacrobatreader&logoColor=fbbf24)](https://petsymposium.org/popets/2025/popets-2025-0143.pdf)
> [![arXiv 2504.04388](https://img.shields.io/badge/arXiv-2504.04388-111318?style=flat-square&logo=arxiv&logoColor=f472b6)](https://arxiv.org/abs/2504.04388)

---

### Tech Stack

**ML, Deep Learning & LLM Systems**

![PyTorch](https://img.shields.io/badge/PyTorch-111318?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![Transformers](https://img.shields.io/badge/Hugging_Face-111318?style=flat-square&logo=huggingface&logoColor=FFD21E)
![LoRA / QLoRA](https://img.shields.io/badge/PEFT_%2F_LoRA_%2F_QLoRA-111318?style=flat-square&logo=pytorch&logoColor=a78bfa)
![LangGraph](https://img.shields.io/badge/LangGraph_%2F_LangChain-111318?style=flat-square&logo=langchain&logoColor=34d399)
![vLLM](https://img.shields.io/badge/vLLM-111318?style=flat-square&logo=python&logoColor=22d3ee)
![Vertex AI / Gemini](https://img.shields.io/badge/Vertex_AI_%2F_Gemini-111318?style=flat-square&logo=googlecloud&logoColor=4285F4)
![Claude API](https://img.shields.io/badge/Claude_API_%2F_MCP-111318?style=flat-square&logo=anthropic&logoColor=D97757)
![XGBoost](https://img.shields.io/badge/XGBoost_%2F_Optuna-111318?style=flat-square&logo=scikitlearn&logoColor=22d3ee)
![Vector Stores](https://img.shields.io/badge/FAISS_%2F_Pinecone_%2F_ChromaDB-111318?style=flat-square&logo=databricks&logoColor=f472b6)
![NetworkX GraphRAG](https://img.shields.io/badge/NetworkX_GraphRAG-111318?style=flat-square&logo=python&logoColor=34d399)

**MLOps, Cloud, Game Dev & Web**

![Kubernetes / GKE](https://img.shields.io/badge/Kubernetes_%2F_GKE-111318?style=flat-square&logo=kubernetes&logoColor=326CE5)
![Docker](https://img.shields.io/badge/Docker-111318?style=flat-square&logo=docker&logoColor=2496ED)
![AWS](https://img.shields.io/badge/AWS-111318?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Ray](https://img.shields.io/badge/Ray-111318?style=flat-square&logo=ray&logoColor=028CF0)
![MLflow / W&B](https://img.shields.io/badge/MLflow_%2F_W%26B-111318?style=flat-square&logo=weightsandbiases&logoColor=fbbf24)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-111318?style=flat-square&logo=cloudflareworkers&logoColor=F38020)
![FastAPI](https://img.shields.io/badge/FastAPI-111318?style=flat-square&logo=fastapi&logoColor=009688)
![React](https://img.shields.io/badge/React_%2F_Vite-111318?style=flat-square&logo=react&logoColor=61DAFB)
![pygame-ce](https://img.shields.io/badge/pygame--ce_%2F_pymunk-111318?style=flat-square&logo=python&logoColor=fbbf24)

**Languages & Data**

![Python](https://img.shields.io/badge/Python-111318?style=flat-square&logo=python&logoColor=3776AB)
![TypeScript](https://img.shields.io/badge/TypeScript-111318?style=flat-square&logo=typescript&logoColor=3178C6)
![JavaScript](https://img.shields.io/badge/JavaScript-111318?style=flat-square&logo=javascript&logoColor=F7DF1E)
![C++](https://img.shields.io/badge/C%2FC%2B%2B-111318?style=flat-square&logo=cplusplus&logoColor=22d3ee)
![Java](https://img.shields.io/badge/Java-111318?style=flat-square&logo=openjdk&logoColor=ED8B00)
![C#](https://img.shields.io/badge/C%23-111318?style=flat-square&logo=dotnet&logoColor=a78bfa)
![Swift](https://img.shields.io/badge/Swift-111318?style=flat-square&logo=swift&logoColor=F05138)
![SQL / PostgreSQL](https://img.shields.io/badge/SQL_%2F_PostgreSQL_%2F_pgvector-111318?style=flat-square&logo=postgresql&logoColor=4169E1)
![Spark / Kafka / Snowflake](https://img.shields.io/badge/Spark_%2F_Kafka_%2F_Snowflake-111318?style=flat-square&logo=snowflake&logoColor=29B5E8)

---

### Contact

- **Interactive Portfolio:** [adit-prabhu.github.io](https://adit-prabhu.github.io/)
- **Email:** [ap4806@columbia.edu](mailto:ap4806@columbia.edu)
- **LinkedIn:** [linkedin.com/in/adit-prabhu](https://www.linkedin.com/in/adit-prabhu)
- **GitHub:** [github.com/Adit-Prabhu](https://github.com/Adit-Prabhu)
