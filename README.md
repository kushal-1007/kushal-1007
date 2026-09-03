<p align="center">
  <img src="https://github.com/kushal-1007.png" width="140" alt="Kushal Trivedi Avatar" />
</p>

<h1 align="center">Hi, I'm Kushal Trivedi 👋</h1>

<p align="center">
  <a href="https://github.com/kushal-1007">
    <img
      src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1200&center=true&vCenter=true&width=650&lines=Data+Scientist;Machine+Learning+Engineer;NLP+%2F+Computer+Vision+Enthusiast;Building+End-to-End+ML+Pipelines"
      alt="Typing SVG"
    />
  </a>
</p>

<p align="center">
  📍 Tempe, Arizona · 🎓 MS Data Science @ Arizona State University (Expected Dec 2026)
  <br />
  🔍 <strong>Actively seeking:</strong> Software Development · Data Science · Machine Learning · MLOps roles
</p>

<p align="center">
  <a href="https://github.com/kushal-1007">
    <img src="https://img.shields.io/badge/GitHub-kushal--1007-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/kushal-trivedi10">
    <img src="https://img.shields.io/badge/LinkedIn-kushal--trivedi10-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:kushaltrivedi82@gmail.com">
    <img src="https://img.shields.io/badge/Email-kushaltrivedi82%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<!-- TODO: once your portfolio site / hosted resume are live, add two more badges here
     pointing to real URLs — don't ship placeholder links. -->

---

## ⚡ Quick Stats

- 🧊 Glacier melt window narrowed to **2049–2052** across two independent regression models
- 🎯 Production NLP platform: DistilBERT + FastAPI + Docker + MLflow/DVC, fully deployed
- 🚕 R² ≈ **0.93** on 11.2M+ NYC taxi records · 📚 210K+ recommendations served to 105K+ users

---

## 🛠 Skills & Tech Stack

**Languages & Frameworks**
Python · Java · JavaScript/TypeScript · C/C++ · Django · Flask · FastAPI · React

**ML, DL & NLP**
PyTorch · TensorFlow · scikit-learn · Transformers (Hugging Face) · DistilBERT Fine-Tuning · RAG · LangChain · ChromaDB · SHAP

**MLOps & Experiment Tracking**
MLflow · DVC · Evidently (Drift Monitoring) · Docker · GitHub Actions (CI/CD) · pytest

**Cloud & Databases**
AWS (S3, EC2) · PostgreSQL · MySQL · SQLite · MongoDB

---

## 🎓 Education

| School                   | Degree                    | Status                        |
| ------------------------ | ------------------------- | ----------------------------- |
| Arizona State University | MS, Data Science          | In progress · Exp. Dec 2026   |

---

## 💼 Work Experience

| Period              | Organization             | Role                        |
| ------------------- | ------------------------ | ---------------------------- |
| Jan 2024 – Jun 2024 | Praxware Technologies    | Software Developer Intern   |

### Praxware Technologies

- Built a full-stack placement management platform (Django, JavaScript, MySQL) using OOP design and REST APIs
- Rewrote core MySQL queries and ETL workflows, cutting query latency under concurrent load
- Set up Git/GitHub version control with structured commits and pytest-covered modules

---

## 🚀 Featured Projects

### 🧊 Glacier Melt Prediction & Climate Impact Analysis
**Stack:** Python · Flask · NASA GIBS Satellite Imagery · Groq LLM API (Llama 3.1) · Chart.js · SciPy · Matplotlib

Two independent regression models (linear + sine-trend) fit on 16 years of Gangotri Glacier coverage data converge on a **2049–2052 melt window**, with 50% coverage loss already projected around 2030.

- Built a 4-process pipeline computing year-over-year glacier coverage (calibrated RGB spectral index), ocean temperature index, and sea level anomaly index from raw NASA satellite imagery
- Ran Pearson correlation analysis across all three signals on outlier-cleaned years, surfacing weak positive coupling between glacier coverage and ocean temperature (r = 0.39) and coverage and sea level (r = 0.38)
- Shipped a live Flask dashboard with global year-range filtering, click-to-satellite-image inspection, and a watchdog-driven auto-refresh pipeline pulling new NASA imagery automatically
- Added an AI Insights tab (Groq/Llama 3.1, Anthropic fallback) that reads all 19 live dashboard panel values and generates narrative summaries and deterministic KPI-based key findings
- Layered a RAG + function-calling chatbot on top of the dashboard (ChromaDB, sentence-transformers, ReAct-style tool use) so users can query the project's own findings in plain language

---

### 🎯 Sentiment Intelligence Platform
**Stack:** Python · PyTorch · Transformers (DistilBERT) · FastAPI · Docker · MLflow · DVC · SHAP · Evidently · GitHub Actions

A 5-class Yelp review sentiment classifier shipped as a full production system, not a notebook model.

- Fine-tuned DistilBERT and served it through a FastAPI backend powering both the REST API and an HTML/JS dashboard
- Containerized end-to-end with Docker and wired up GitHub Actions CI/CD
- Set up MLflow and DVC for experiment tracking and data versioning, SHAP for explainability, and Evidently for post-deployment drift monitoring
- Added a pytest unit/integration test suite and wrote up the full build in an IEEE-format technical report

---

### 🚕 NYC Taxi Trip Data Mining & Fare Prediction
**Stack:** Python · scikit-learn · Pandas · NumPy · pytest · *4-person team project*

- Engineered features across 11.2M+ NYC taxi records through a large-scale ETL and EDA pipeline
- Trained Linear Regression and Random Forest models, reaching R² ≈ 0.93 with a ~3% RMSE reduction over baseline
- Flagged fare anomalies using K-Means clustering (k=5, silhouette ≈ 0.38), z-score analysis, and Isolation Forest

---

### 📚 More Projects

| Project | Stack | Highlight |
|---|---|---|
| Book Recommendation System | Python (OOP), FastAPI, Sparse Matrices | 210K+ recommendations served to 105K+ users via cosine-similarity engine |
| Self-Driving Car Simulation | JavaScript, Custom Neural Net | 3-layer NN (5→6→4) from scratch; 1,000 concurrent agents/generation, ~20% fewer collisions |
| AI-Based Virtual Mouse | Python, OpenCV, MediaPipe | Touchless mouse control tracking 21 hand landmarks/frame, 20px pinch-click threshold |

---

## 🏆 Impact Snapshot

| ⚡ Performance                            | 📈 Scale                               | 🔧 Quality & Ownership                          |
| ----------------------------------------- | --------------------------------------- | ------------------------------------------------ |
| Glacier melt window narrowed to 2049–2052 across 2 independent models | 11.2M+ taxi records processed           | Full MLOps stack on sentiment platform: MLflow, DVC, SHAP, Evidently, Docker, CI/CD, pytest |
| R² ≈ 0.93, ~3% RMSE reduction (taxi fares) | 210,000+ recommendations, 105K+ users   | Zero external ML libs on custom neural net        |
| ~20% collision reduction (self-driving sim)| 16 years of satellite imagery analyzed  | pytest-validated pipelines, Git-managed code     |

---

## 📊 GitHub Activity

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=kushal-1007&show_icons=true&include_all_commits=true&count_private=true"
    alt="Kushal Trivedi GitHub Stats"
    height="165"
  />
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=kushal-1007&layout=compact"
    alt="Top Languages"
    height="165"
  />
</p>

<p align="center">
  Always learning, always building.
</p>
