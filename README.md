<div align="center">

# Jainam Shah

**AI/ML Engineer · Data Scientist · Backend AI Systems**

*I build AI systems that ship to production — not just models that live in notebooks.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jainamshah41)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jainamshah714@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jainam-shah-18)

</div>

---

## About

Currently at **IndiaNIC Infotech**, I'm a core engineer on **LuxeEstate** — a production-grade AI real estate platform where I've architected 10+ REST APIs, integrated **NVIDIA NIM LLMs** (Llama 3.1 + NEVA 22B) for conversational property search and image-based discovery, built real-time WebSocket messaging infrastructure with Redis, and shipped live admin analytics dashboards — deployed end-to-end on Gunicorn + Daphne + Nginx.

On the ML side, I built a **mood-aware music recommender** achieving **Precision@10: 0.345** — a **+47% uplift** over baseline — using a hybrid of collaborative filtering, DistilBERT/RoBERTa emotion classification, and context-aware re-ranking exposed via a FastAPI service.

- 🎯 **Targeting:** AI/ML Engineer · Data Scientist · Data Engineer *(Fresher / 0–1 yr)*
- 🏢 **Currently:** AI/ML Engineer (Trainee) @ IndiaNIC Infotech Ltd
- 🔭 **Exploring:** RAG pipelines · MLflow · LLM fine-tuning · Docker deployment
- 📍 **Location:** Ahmedabad, India

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**AI / ML / NLP**

![LLMs](https://img.shields.io/badge/LLMs-NVIDIA_NIM-76B900?style=flat-square&logo=nvidia&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154F3C?style=flat-square&logo=python&logoColor=white)

**Backend & APIs**

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![DRF](https://img.shields.io/badge/Django_REST-ff1709?style=flat-square&logo=django&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white)

**Data & Visualization**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Databases & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

---

## Featured Projects

### 🏠 [LuxeEstate](https://github.com/jainam-shah-18/LuxeEstate) — AI-Powered Real Estate Platform
> `Django` `FastAPI` `NVIDIA NIM` `PostgreSQL` `Redis` `WebSockets` `Razorpay`

**Situation:** Property platforms lose users when search is keyword-bound — it fails to understand *intent*, causing drop-off before inquiry. Agents lose deals waiting on async communication.

**Action:**
- Architected 10+ production REST APIs (Django + DRF + PostgreSQL) covering property search, auth, payments, and analytics across the full product lifecycle
- Integrated NVIDIA NIM LLMs — Llama 3.1 for conversational natural-language property search and NEVA 22B for image-based listing discovery
- Built real-time bidirectional agent-client messaging using Django Channels, WebSockets, and Redis
- Shipped a live admin analytics dashboard with KPI charts auto-refreshing every 15 seconds
- Deployed a Telegram bot for city-based property search, appointment scheduling, and travel-time queries
- Implemented Google OAuth, OTP auth, Razorpay payment gateway with webhook processing and invoice generation
- Production deployment: Gunicorn + Daphne + Nginx with SEO-optimised URLs and sitemap

**Result:** End-to-end production platform where AI is the core, not a bolt-on — natural language search removes the gap between user intent and listing discovery; real-time messaging eliminates async communication delays between agents and clients.

---

### 🎵 [SpotifyMoodML](https://github.com/jainam-shah-18/mood-spotify-ml) — Mood-Aware Music Recommendation System
> `Scikit-learn` `HuggingFace Transformers` `DistilBERT` `FastAPI` `PostgreSQL` `Power BI`

**Situation:** Standard recommenders use listening history — not emotional state. A user who needed energy at 7 AM needs calm at midnight. Mood is transient; recommendations should be too.

**Action:**
- Engineered a hybrid recommender: Collaborative Filtering (ALS) + Content-Based (TF-IDF + SVD) + Mood-Aware re-ranking
- Built an NLP pipeline using DistilBERT / RoBERTa for lyrics emotion classification + VADER sentiment analysis
- Implemented context-aware re-ranking adjusting for time of day, activity (workout / study / relax), and season
- Extracted multimodal mood signals from Spotify audio features (valence, energy, danceability), lyrics sentiment, and social aggregates
- Exposed via FastAPI REST service: `/recommend`, `/similar`, `/mood` endpoints
- Tracked performance in a 4-page Power BI dashboard with live mood filters and Precision@K / NDCG@K KPI cards

**Result:**

| Model | Precision@10 | Recall@10 | NDCG@10 | Coverage |
|---|---|---|---|---|
| Mood-Only Baseline | 0.235 | — | — | — |
| **Context-Aware Hybrid** | **0.345** | **0.267** | **0.289** | **63.4%** |
| **Uplift** | **+47%** | — | — | — |

---

### 📊 [Amazon Supply Chain Analytics](https://github.com/jainam-shah-18/project_walmart) — Demand & Inventory Intelligence Pipeline
> `Python` `SQL` `Power BI` `Pandas` `NumPy` `SciPy`

**Situation:** Retail operations bleed margin from two failure modes: overstocking slow movers and stockouts on high-velocity SKUs — both rooted in poor demand signal visibility.

**Action:**
- Processed and cleaned 100K+ global transaction rows — achieving 95%+ data quality post-cleaning with outlier detection
- Applied hypothesis testing (t-test, ANOVA) to surface statistically significant sales drivers and regional performance gaps
- Engineered lag features and rolling aggregates to model demand velocity shifts
- Built an advanced SQL layer (CTEs, window functions) for profit margin and shipping delay queries
- Delivered a 5-page Power BI executive dashboard: Revenue Overview · Shipping Delays · Sales Channel Trends · Regional Performance · Executive KPI Summary

**Result:** Compressed raw-data-to-insight cycle into a fully reproducible, automated cross-tool pipeline (Python → SQL → Power BI) — replacing manual reporting with a single dashboard refresh.

---

### 🍳 [ChefGPT](https://github.com/jainam-shah-18) — AI-Powered Recipe Intelligence System
> `Python` `FastAPI` `MySQL` `LLMs` `NLP` `Computer Vision`

Architected an LLM-powered recipe generation platform supporting both text-input and image-based ingredient detection — with nutrition-aware recommendations, BPE tokenization-optimised prompts, and bilingual user guidance delivered via a FastAPI backend with structured MySQL storage.

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jainam-shah-18&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jainam-shah-18&layout=compact&theme=github_dark&hide_border=true)

</div>

---

## Currently Open To

| Role | Type |
|---|---|
| AI/ML Engineer | Full-time · Fresher / 0–1 yr |
| Data Scientist | Full-time · Fresher / 0–1 yr |
| Data Engineer | Full-time · Fresher / 0–1 yr |
| Backend AI / Python Engineer | Full-time · Fresher / 0–1 yr |

Also open to **open-source collaborations** on: NLP tooling · Recommender systems · LLM applications · Data pipelines

---

## Connect

I respond within 24 hours. If you're building AI-powered products or hiring for ML/Data roles — let's talk.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jainamshah41)
[![Email](https://img.shields.io/badge/Email-jainamshah714@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jainamshah714@gmail.com)

*"I don't just build models. I build systems that ship."*

</div>
