<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     MANIKANT — PROFILE README                  -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0d0d0d,50:0a1628,100:0d0d0d&height=200&section=header&text=MANIKANT&fontSize=72&fontColor=00d4ff&animation=fadeIn&fontAlignY=45&desc=AI%20Engineer%20·%20ML%20Researcher%20·%20Data%20Scientist&descAlignY=68&descColor=ffffff&descSize=16&stroke=00d4ff&strokeWidth=1" width="100%"/>

</div>

<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=3000&pause=800&color=00D4FF&center=true&vCenter=true&multiline=false&repeat=true&width=580&height=45&lines=Building+AI+that+solves+real+problems+%F0%9F%94%A5;Computer+Vision+%7C+NLP+%7C+Agentic+AI;From+Raw+Data+%E2%86%92+Production+Systems;Open+to+AI%2FML+%26+Data+roles+%E2%80%94+Let%27s+connect!" alt="Typing SVG" /></a>

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/manikant14)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Manikant-14)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:manikantmgr14@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=Manikant-14&color=00d4ff&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/Manikant-14)

</div>

<br/>

---

## `> whoami`

```python
manikant = {
    "role"       : ["AI Engineer", "ML Researcher", "Data Scientist"],
    "education"  : "B.Tech CSE (AI & ML) @ Sharda University · CGPA ~8.0 · 2028",
    "focus"      : "End-to-end AI systems — from raw data to deployed products",
    "superpower" : "Making models that don't just predict — they explain & act",
    "status"     : "🟢 Open to AI/ML & Data internships",
}
```

---

<br/>

## ⚡ What I Build

<table width="100%">
<tr>
<td width="33%" valign="top">

**🧠 AI / ML Systems**

Production-grade pipelines — computer vision, NLP, deep learning. Not just models, but systems that ship.

`PyTorch` `TensorFlow` `Scikit-learn` `OpenCV` `HuggingFace`

</td>
<td width="33%" valign="top">

**🔍 Data Science**

EDA → Feature Engineering → Modeling → Explainability (SHAP / Grad-CAM). Every prediction has a *reason*.

`Pandas` `NumPy` `XGBoost` `SHAP` `Statsmodels`

</td>
<td width="33%" valign="top">

**📊 Data Analytics**

KPI dashboards, business insight extraction, visual storytelling. Data that drives decisions.

`SQL` `Power BI` `Excel` `Matplotlib` `Seaborn`

</td>
</tr>
</table>

<br/>

---

## 🚀 Featured Projects

> *These aren't tutorials. These are real systems built to solve real problems.*

<br/>

### 🏥 AI Dermatology Intelligence System
**`Research-grade Clinical AI · End-to-end · Production Stack`**

> Melanoma kills when caught late. AI can screen at scale.

A full-stack clinical AI system that classifies skin lesions, segments affected regions, scores severity using the ABCD dermoscopy rule, and generates LLM-powered patient reports — all in one pipeline.

| Module | Method | Result |
|--------|--------|--------|
| Classification | MobileNetV2 · HAM10000 · 7-class | **~77% accuracy** |
| Segmentation | U-Net · ISIC 2018 | **~0.86 Dice Score** |
| Explainability | Grad-CAM heatmaps | Clinician-interpretable |
| Severity Scoring | ABCD rule automation | Risk triage in seconds |
| LLM Reports | BioMistral-7B · 4-bit quantized | PDF generation, offline |
| Deployment | FastAPI + Streamlit + MongoDB | Demo-ready |

**Datasets used:** HAM10000 · ISIC 2018 · PH2 · ISIC 2019 (~25K+ images)

**Stack:** `PyTorch` `TensorFlow` `MobileNetV2` `U-Net` `Grad-CAM` `SHAP` `FastAPI` `Streamlit` `MongoDB` `BioMistral-7B`

> 💡 *Impact: A system that could assist dermatologists in high-volume screening — where early detection literally saves lives.*

[![View Project](https://img.shields.io/badge/View_Project-0d1117?style=for-the-badge&logo=github&logoColor=00d4ff)](https://github.com/Manikant-14/ai-dermatology-system)

<br/>

---

### 🤖 AutoStream — Social-to-Lead AI Agent
**`Agentic AI · LangGraph · RAG · Tool Execution`**

> SaaS companies lose high-intent users who bounce. This agent catches them.

A production conversational agent that understands context, retrieves product knowledge via RAG, detects purchase intent, and captures leads through natural multi-turn dialogue — fully autonomous.

```
User Message
     │
     ▼
┌─────────────────┐
│  Intent Router  │ ← Groq Llama 3.3 70B classifies in <200ms
└────────┬────────┘
         │
   ┌─────┼──────────┐
   ▼     ▼          ▼
Greet  Product   High Intent
       Query +   → Lead Flow
       FAISS RAG   (name→email
                    →platform)
                        │
                        ▼
                  leads/leads.json
```

| Component | Detail |
|-----------|--------|
| Agent Framework | LangGraph StateGraph |
| LLM | Groq · Llama-3.3-70B-Versatile (free) |
| RAG | FAISS + HuggingFace `all-MiniLM-L6-v2` |
| Backend | FastAPI · `/chat` + `/leads` |
| Frontend | Streamlit · dark branded UI |

**Stack:** `LangGraph` `LangChain` `Groq` `FAISS` `FastAPI` `Streamlit`

> 💡 *ML Intern Assignment for ServiceHive × Inflx — shipped end-to-end in 48 hours.*

[![View Project](https://img.shields.io/badge/View_Project-0d1117?style=for-the-badge&logo=github&logoColor=00d4ff)](https://github.com/Manikant-14/social-lead-agent)

<br/>

---

### 📊 Student Performance Predictor
**`Explainable ML · SHAP · Streamlit · PDF Reports`**

> Prediction without explanation is useless in education. This system explains *why*.

End-to-end ML pipeline predicting student performance with SHAP-powered explanations — so educators understand the *reason* behind every flag, not just the score.

| Stage | Approach |
|-------|----------|
| EDA | Distribution, correlation, outlier analysis |
| Feature Engineering | Encoding, scaling, interaction terms |
| Model Comparison | Random Forest vs XGBoost vs Logistic Regression |
| Explainability | SHAP summary + per-student force plots |
| Output | Automated PDF report per student |
| UI | Streamlit real-time prediction dashboard |

**Stack:** `Scikit-learn` `XGBoost` `SHAP` `Pandas` `Streamlit` `ReportLab`

[![View Project](https://img.shields.io/badge/View_Project-0d1117?style=for-the-badge&logo=github&logoColor=00d4ff)](https://github.com/Manikant-14/student-performance-predictor)

<br/>

---

### 📈 Tourism Recovery Analytics Dashboard
**`Business Intelligence · Power BI · Excel · Executive Insights`**

> Numbers without context mislead. This dashboard tells the full story.

Multi-layer analytics covering 20-year growth trends, COVID impact quantification, arrivals-vs-revenue paradox analysis, market concentration risk, and scenario-based recovery projections.

**Key Insight Delivered:** *High arrivals ≠ high revenue* — identified structural inefficiencies driving the gap, with actionable recommendations for tourism boards.

**Output:** 13-slide executive presentation + interactive Excel dashboard with slicers

**Stack:** `Power BI` `Excel` `Python` `Pandas` `Matplotlib` `Seaborn`

[![View Project](https://img.shields.io/badge/View_Project-0d1117?style=for-the-badge&logo=github&logoColor=00d4ff)](https://github.com/Manikant-14/tourism-analytics-dashboard)

<br/>

---

## 🛠️ Full Tech Stack

<div align="center">

**AI & Machine Learning**

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=flat-square&logo=OpenCV&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square&logo=xgboost&logoColor=white)

**Generative AI & LLM**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B6B?style=flat-square&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-black?style=flat-square&logo=ollama&logoColor=white)

**Data Science & Analytics**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-7DB0BC?style=flat-square)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)

**Databases & Deployment**

![MySQL](https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=flat-square&logo=mongodb&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=Streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

<br/>

---

## 🧭 My Problem-Solving Pipeline

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   📥 UNDERSTAND       →   What is the real-world problem?        ║
║        │                                                         ║
║   🔍 EXPLORE          →   What does the data actually say?       ║
║        │                                                         ║
║   ⚙️  ENGINEER        →   What features drive the outcome?       ║
║        │                                                         ║
║   🤖 MODEL            →   Which approach fits best — and why?    ║
║        │                                                         ║
║   📊 EVALUATE         →   Does it work on data it hasn't seen?   ║
║        │                                                         ║
║   💡 EXPLAIN          →   Why does it predict what it predicts?  ║
║        │                                                         ║
║   🚀 DEPLOY           →   Can a real user interact with it?      ║
║        │                                                         ║
║   📈 IMPACT           →   What decision does this enable?        ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

> Most people stop at **MODEL**. I go all the way to **IMPACT**.

<br/>

---

## 📊 GitHub Activity

<div align="center">

<img height="170px" src="https://github-readme-stats.vercel.app/api?username=Manikant-14&show_icons=true&theme=github_dark&hide_border=true&title_color=00d4ff&icon_color=00d4ff&text_color=ffffff&bg_color=0d1117&include_all_commits=true&count_private=true" />
&nbsp;&nbsp;
<img height="170px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Manikant-14&layout=compact&theme=github_dark&hide_border=true&title_color=00d4ff&text_color=ffffff&bg_color=0d1117&langs_count=8" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Manikant-14&theme=github-dark-blue&hide_border=true&ring=00d4ff&fire=00d4ff&currStreakLabel=00d4ff&background=0d1117)](https://git.io/streak-stats)

</div>

<br/>

---

## 🔭 Currently

```python
now = {
    "building"  : "AI Dermatology System — Phase 6 (multi-dataset generalization)",
    "learning"  : ["MLOps", "LLM fine-tuning (LoRA/QLoRA)", "Vector DBs", "Multimodal AI"],
    "reading"   : "Attention Is All You Need + Andrej Karpathy's lectures",
    "targeting" : "AI/ML & Data Science internships — Summer 2026",
}
```

---

## 💎 Why I'm Different

```
  ┌─────────────────────────────────────────────────────────┐
  │                                                         │
  │  ✦  I build systems, not scripts                        │
  │  ✦  Every model I build has an explanation layer        │
  │  ✦  I work with real, messy data — not curated Kaggle   │
  │  ✦  I ship — FastAPI + Streamlit + deployment, always   │
  │  ✦  I think in pipelines: data → insight → decision     │
  │  ✦  I ask "why does this work?" before "does it work?"  │
  │                                                         │
  └─────────────────────────────────────────────────────────┘
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,50:0a1628,100:0d0d0d&height=120&section=footer&text=Let%27s+Build+Something+Impactful&fontSize=20&fontColor=00d4ff&animation=fadeIn&fontAlignY=65"/>

**B.Tech CSE (AI & ML) · Sharda University · Open to Opportunities**

[![Email Me](https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:manikantmgr14@gmail.com)
[![Connect on LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/manikant14)

*"The best model is the one that ships and creates impact."*

</div>
