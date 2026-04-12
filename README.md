<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Manikant&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=AI%20Engineer%20%7C%20ML%20Researcher%20%7C%20Data%20Scientist&descAlignY=55&descSize=18"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Building+AI+that+solves+real+problems.;End-to-end+ML+%7C+Computer+Vision+%7C+NLP;RAG+Pipelines+%7C+LLM+Applications;From+Data+to+Deployment+%E2%80%94+Full+Stack+AI." alt="Typing SVG" />
</a>

<br/>

> **"I build AI systems and data-driven solutions that create measurable real-world impact."**

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/manikant14)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Manikant-14)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:manikantmgr14@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white)](#)

![Profile Views](https://komarev.com/ghpvc/?username=Manikant-14&color=00d4ff&style=flat-square&label=Profile+Views)

</div>

---

## 🧠 What I Do

<table>
<tr>
<td width="33%" align="center">

### 🤖 AI / ML Engineering
Building production-ready ML systems — computer vision, NLP, deep learning pipelines with real-world deployment.

</td>
<td width="33%" align="center">

### 📊 Data Science
End-to-end: EDA → feature engineering → modeling → evaluation → business recommendations backed by statistical rigor.

</td>
<td width="33%" align="center">

### 📈 Data Analytics
Turning raw data into actionable insights through dashboards, KPI tracking, and visual storytelling.

</td>
</tr>
</table>

---

## 🚀 Featured Projects

### 🏥 1. AI Dermatology Intelligence System
> *Real-world healthcare AI — not a toy project*

**Problem:** Dermatological conditions like melanoma are life-threatening when diagnosed late. Access to dermatologists is limited, especially in rural areas.

**What I Built:** A full-stack clinical AI system that classifies skin lesions, segments affected areas, scores severity, and generates patient reports — end-to-end.

| Component | Approach | Result |
|---|---|---|
| Classification | MobileNetV2 fine-tuned on HAM10000 | ~77% accuracy, 7 classes |
| Segmentation | U-Net on ISIC 2018 | ~0.86 Dice Score |
| Explainability | Grad-CAM heatmaps | Clinician-interpretable |
| Severity Scoring | ABCD dermoscopy rule | Automated risk triage |
| Report Generation | BioMistral-7B (4-bit quantized) | LLM-powered PDF reports |
| Deployment | FastAPI + Streamlit + MongoDB | Full-stack, demo-ready |

**Datasets:** HAM10000 · ISIC 2018 · PH2 · ISIC 2019 (~25K images)

**Stack:** `PyTorch` `TensorFlow` `MobileNetV2` `U-Net` `Grad-CAM` `SHAP` `FastAPI` `Streamlit` `MongoDB` `BioMistral-7B`

**Impact:** Bridges the gap between clinical diagnosis and AI — a tool that could assist dermatologists in high-volume screening environments.

[![Repo](https://img.shields.io/badge/View_Repo-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Manikant-14/ai-dermatology-system)

---

### 🤖 2. AutoStream — Social-to-Lead AI Agent
> *Agentic AI with intent detection, RAG, and tool execution*

**Problem:** SaaS companies lose high-intent users who bounce from product pages without converting. Manual follow-up is too slow.

**What I Built:** A production-style conversational agent that handles product queries via RAG, detects purchase intent, and autonomously captures leads through natural conversation.

| Component | Implementation |
|---|---|
| Agent Framework | LangGraph StateGraph (3-node pipeline) |
| Intent Detection | Groq Llama 3.3 70B — 3-class classifier |
| RAG Pipeline | FAISS + HuggingFace `all-MiniLM-L6-v2` |
| Lead Capture Tool | Stateful multi-turn form → JSON storage |
| Backend | FastAPI with `/chat` + `/leads` endpoints |
| Frontend | Streamlit with branded dark UI |

**Stack:** `LangGraph` `Groq` `Llama-3.3-70B` `FAISS` `LangChain` `FastAPI` `Streamlit`

**Result:** Full agentic loop — perceive intent → retrieve context → take action → capture lead. Zero hallucination on product facts (grounded by RAG).

[![Repo](https://img.shields.io/badge/View_Repo-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Manikant-14/social-lead-agent)

---

### 📊 3. Student Performance Predictor
> *Explainable ML with SHAP — not just predictions, but reasons*

**Problem:** Educational institutions struggle to identify at-risk students early enough to intervene effectively.

**What I Built:** An end-to-end ML system that predicts student performance, explains predictions using SHAP, and exports PDF reports for educators.

| Stage | Detail |
|---|---|
| EDA | Distribution analysis, correlation heatmaps, outlier detection |
| Feature Engineering | Encoding, scaling, interaction features |
| Modeling | Random Forest, XGBoost, Logistic Regression — compared |
| Explainability | SHAP summary + force plots per student |
| Report Export | Automated PDF with predictions + explanations |
| UI | Streamlit dashboard with real-time prediction |

**Stack:** `Scikit-learn` `XGBoost` `SHAP` `Pandas` `Matplotlib` `Streamlit` `ReportLab`

**Impact:** Moves beyond black-box ML — educators can see *why* a student is flagged, enabling targeted intervention.

[![Repo](https://img.shields.io/badge/View_Repo-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Manikant-14/student-performance-predictor)

---

### 📈 4. Tourism Recovery & Revenue Risk Dashboard
> *Business analytics — from raw data to executive insights*

**Problem:** Tourism boards need to understand post-COVID recovery trajectories and identify revenue concentration risks.

**What I Built:** A multi-layer analytics dashboard covering 20-year growth trends, COVID impact quantification, market concentration analysis, and recovery projections.

| Analysis | Insight Delivered |
|---|---|
| COVID Impact | Revenue drop quantified by region and segment |
| Arrivals vs Revenue Paradox | High arrivals ≠ high revenue — identified why |
| Market Concentration | HHI analysis — dependency risk flagged |
| Recovery Projection | Scenario modeling: base / optimistic / pessimistic |

**Stack:** `Excel` `Power BI` `Python` `Pandas` `Matplotlib` `Seaborn`

**Output:** 13-slide executive presentation + interactive Excel dashboard with slicers.

[![Repo](https://img.shields.io/badge/View_Repo-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Manikant-14/tourism-analytics-dashboard)

---

## 🛠️ Tech Stack

<div align="center">

### 🤖 AI / Machine Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### 🧠 Generative AI & LLM Stack
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B6B?style=for-the-badge&logo=graph&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)

### 📊 Data Science & Analytics
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-7DB0BC?style=for-the-badge&logo=seaborn&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

### 🗄️ Databases & Backend
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

</div>

---

## 🔄 How I Build AI Solutions

```
📥 Data Collection & Understanding
        ↓
🔍 Exploratory Data Analysis (patterns, anomalies, distributions)
        ↓
⚙️  Feature Engineering (domain knowledge + statistical methods)
        ↓
🤖 Modeling (baseline → iterate → ensemble)
        ↓
📊 Evaluation (metrics + business context)
        ↓
💡 Explainability (SHAP / Grad-CAM — WHY does it predict this?)
        ↓
🚀 Deployment (FastAPI + Streamlit + Docker-ready)
        ↓
📈 Monitoring & Iteration
```

> This is not just a coding mindset — it's a **product mindset**. Every step asks: *"What decision does this enable?"*

---

## 🏆 Experience & Achievements

| | |
|---|---|
| 🎓 | B.Tech CSE (AI & ML) — Sharda University, Greater Noida · CGPA: ~8.0 · 2024–2028 |
| 💼 | Data Handling Training — SQL (MySQL) + NoSQL (MongoDB) data pipelines |
| 🤖 | ML Intern Assignment — ServiceHive × Inflx · Agentic AI system (April 2026) |
| 📊 | Data Analysis & Visualization Lab · Power BI + Python EDA |
| 🏥 | AI Dermatology System — flagship research-grade project |

---

## 📚 Currently Building & Learning

```python
current_focus = {
    "building":   ["AI Dermatology System (Phase 6→8)", "RAG pipelines", "LLM agents"],
    "learning":   ["MLOps (experiment tracking, model registry)", "Vector databases",
                   "Multimodal AI", "LLM fine-tuning (LoRA/QLoRA)"],
    "exploring":  ["Agentic workflows", "AI safety basics", "Production ML systems"]
}
```

---

## 💡 Why Work With Me

```
✅ I build end-to-end systems — not just notebooks
✅ I focus on WHY a model predicts what it predicts (explainability-first)
✅ I work with real, messy datasets — not clean Kaggle toys
✅ I think in pipelines — data → insight → decision → impact
✅ I ship — FastAPI + Streamlit + deployment, not just .ipynb files
✅ I'm building at the intersection of AI + real-world problems
```

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Manikant-14&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Manikant-14&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Manikant-14&theme=tokyonight&hide_border=true&background=0d1117)](https://git.io/streak-stats)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>

**Open to AI/ML Engineer · Data Scientist · Data Analyst roles & internships**

[![Email](https://img.shields.io/badge/Reach_Out-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:manikantmgr14@gmail.com)

*"The best model is the one that ships and creates impact."*

</div>
