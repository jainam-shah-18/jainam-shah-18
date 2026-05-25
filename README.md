<div align="center">

<!-- ANIMATED HEADER BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Jainam%20Shah&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=AI%20%2F%20ML%20Engineer%20%C2%B7%20Data%20Scientist%20%C2%B7%20Building%20Real%20Systems&descAlignY=55&descSize=16"/>

<!-- ANIMATED TYPING SVG -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&random=false&width=600&lines=AI+%2F+ML+Engineer+%40+IndiaNIC+Infotech;Building+Production+AI+Systems+%F0%9F%9A%80;LLMs+%C2%B7+NLP+%C2%B7+Recommender+Systems;Django+%C2%B7+FastAPI+%C2%B7+PostgreSQL+%C2%B7+Redis;Turning+Data+Into+Decisions+%F0%9F%A7%A0" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=jainam-shah-18&label=Profile+Views&color=0e75b6&style=flat" alt="profile views"/>
<img src="https://img.shields.io/github/followers/jainam-shah-18?label=Followers&style=social" alt="followers"/>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jainamshah41)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jainamshah714@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jainam-shah-18)

</div>

---

## 🧠 About Me

```python
jainam = {
    "role"        : "AI/ML Engineer (Trainee) @ IndiaNIC Infotech Ltd",
    "location"    : "Ahmedabad, India 🇮🇳",
    "focus"       : ["LLMs", "NLP", "Recommender Systems", "Data Pipelines"],
    "currently"   : "Shipping LuxeEstate — production AI real estate platform",
    "stack"       : ["Python", "Django", "FastAPI", "PyTorch", "PostgreSQL", "Redis"],
    "superpower"  : "I build AI systems that ship — not just notebooks that demo",
    "open_to"     : "Data Scientist · ML Engineer · AI Engineer (Fresher / 0-1 yr)",
    "contact"     : "jainamshah714@gmail.com"
}
```

> 🚀 Currently integrating **NVIDIA NIM LLMs** into a production platform serving real users.
> 📊 Built a hybrid recommender with **Precision@10: 0.345** — a **+47% uplift** over baseline.

---

## 🔥 What I'm Working On

<table>
<tr>
<td width="50%">

### 🏠 LuxeEstate *(Active — Production)*
AI-powered real estate platform at IndiaNIC Infotech. Shipping real features to real users.

`NVIDIA NIM` `LLMs` `Django` `WebSockets` `Redis`

</td>
<td width="50%">

### 🎵 SpotifyMoodML *(Shipped)*
Mood-aware hybrid recommender. **+47% precision uplift** over baseline.

`DistilBERT` `Collaborative Filtering` `FastAPI` `Power BI`

</td>
</tr>
<tr>
<td width="50%">

### 📊 Amazon Supply Chain *(Shipped)*
100K+ transaction analytics pipeline with hypothesis testing and Power BI dashboards.

`Pandas` `SQL` `SciPy` `Power BI`

</td>
<td width="50%">

### 🍳 ChefGPT *(Shipped)*
LLM-powered recipe intelligence with image-based ingredient detection.

`FastAPI` `LLMs` `NLP` `MySQL`

</td>
</tr>
</table>

---

## 🏆 Featured Projects

<details>
<summary><b>🏠 LuxeEstate — AI-Powered Real Estate Platform (click to expand)</b></summary>
<br/>

> **Stack:** `Python` `Django` `FastAPI` `DRF` `PostgreSQL` `Redis` `WebSockets` `NVIDIA NIM` `Razorpay`

**The Problem:** Property search is intent-blind — keyword filters fail to understand what users *actually* want, causing drop-off before inquiry. Agents lose deals in async communication lag.

**What I Built & Shipped:**
- ⚡ **10+ production REST APIs** — property search, auth, payments, analytics across the full lifecycle
- 🤖 **NVIDIA NIM LLM integration** — Llama 3.1 for conversational natural-language search; NEVA 22B for image-based listing discovery
- 💬 **Real-time bidirectional messaging** — Django Channels + WebSockets + Redis at scale
- 📊 **Live admin dashboard** — KPI charts auto-refreshing every 15 seconds, zero manual reporting
- 🤖 **Telegram bot** — city-based property search, appointment scheduling, travel-time queries
- 🔐 **Auth + Payments** — Google OAuth, OTP, Razorpay with webhook processing and invoice generation
- 🚀 **Production deployed** — Gunicorn + Daphne + Nginx, SEO-optimised URLs + sitemap

**Impact:** Natural language search bridges user intent to listing discovery. Real-time messaging eliminates agent-client communication delays. System is live in production.

</details>

<details>
<summary><b>🎵 SpotifyMoodML — Mood-Aware Music Recommendation System (click to expand)</b></summary>
<br/>

> **Stack:** `Python` `Scikit-learn` `HuggingFace` `DistilBERT` `RoBERTa` `VADER` `FastAPI` `PostgreSQL` `Power BI`

**The Problem:** Playlist engines use listening history — not how you feel *right now*. Mood is transient; recommendations should be too.

**What I Built:**
- 🧠 **Hybrid architecture** — Collaborative Filtering (ALS) + Content-Based (TF-IDF + SVD) + Mood-Aware re-ranking
- 📝 **NLP emotion pipeline** — DistilBERT / RoBERTa for lyrics emotion classification + VADER sentiment analysis
- ⏰ **Context-aware re-ranking** — adjusts by time of day, activity (workout / study / relax), and season
- 🎵 **Multimodal mood signals** — Spotify audio features (valence, energy, danceability) + lyrics + social sentiment
- 🌐 **FastAPI REST service** — `/recommend`, `/similar`, `/mood` endpoints
- 📊 **4-page Power BI dashboard** — live mood filters + Precision@K / NDCG@K KPI cards

**Results:**

| Model | Precision@10 | Recall@10 | NDCG@10 | Coverage |
|:---|:---:|:---:|:---:|:---:|
| Mood-Only Baseline | 0.235 | — | — | — |
| **Context-Aware Hybrid** | **0.345** | **0.267** | **0.289** | **63.4%** |
| **Uplift vs Baseline** | **+47%** ✅ | — | — | — |

</details>

<details>
<summary><b>📊 Amazon Supply Chain Analytics — Demand & Inventory Intelligence (click to expand)</b></summary>
<br/>

> **Stack:** `Python` `SQL` `Power BI` `Pandas` `NumPy` `SciPy`

**The Problem:** Retail bleeds margin from overstocking slow movers and stockouts on high-velocity SKUs — both caused by poor demand signal visibility.

**What I Built:**
- 🗄️ Processed **100K+ global transaction rows** — 95%+ data quality post-cleaning with outlier detection
- 📐 **Hypothesis testing** (t-test, ANOVA) to surface statistically significant sales drivers
- 🔧 **Advanced SQL** — CTEs, window functions for profit margin and shipping delay queries
- 📊 **5-page Power BI executive dashboard** — Revenue · Shipping Delays · Sales Channel · Regional Performance · KPI Summary

**Pipeline:** `Python EDA` → `Feature Engineering` → `SQL Analytics` → `Power BI Dashboards`

</details>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**AI / ML / NLP**

![NVIDIA NIM](https://img.shields.io/badge/NVIDIA_NIM-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154F3C?style=for-the-badge&logo=python&logoColor=white)

**Backend & APIs**

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![DRF](https://img.shields.io/badge/Django_REST-ff1709?style=for-the-badge&logo=django&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socket.io&logoColor=white)

**Data & Visualization**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

**Databases & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=jainam-shah-18&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=jainam-shah-18&theme=tokyonight&hide_border=true" />

<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jainam-shah-18&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

</div>

---

## 🐍 Contribution Snake

<div align="center">
  <img src="https://raw.githubusercontent.com/jainam-shah-18/jainam-shah-18/output/github-snake-dark.svg" alt="Snake animation" />
</div>

---

## 🏅 GitHub Trophies

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=jainam-shah-18&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&row=1)

</div>

---

## 📈 Activity Graph

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=jainam-shah-18&theme=tokyo-night&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🎯 Currently Open To

<div align="center">

| Role | Type | Status |
|:---|:---|:---:|
| 🤖 AI / ML Engineer | Full-time · Fresher | ✅ Open |
| 📊 Data Scientist | Full-time · Fresher | ✅ Open |
| 🔧 Data Engineer | Full-time · Fresher | ✅ Open |
| 🐍 Backend Python / AI Engineer | Full-time · Fresher | ✅ Open |
| 🤝 Open Source Collaboration | NLP · RecSys · LLM Apps | ✅ Open |

</div>

---

## 📬 Let's Connect

<div align="center">

I respond within 24 hours. Building AI products or hiring for ML/Data roles? **Let's talk.**

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jainamshah41)
[![Email](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jainamshah714@gmail.com)

<br/>

*"I don't just build models. I build systems that ship."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>

</div>
