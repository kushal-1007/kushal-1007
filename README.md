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
  🔍 <strong>Actively seeking:</strong> Data Science · Machine Learning · MLOps roles
</p>

<p align="center">
  <a href="https://linkedin.com/in/kushal-trivedi10">
    <img src="https://img.shields.io/badge/LinkedIn-kushal--trivedi10-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:kushaltrivedi82@gmail.com">
    <img src="https://img.shields.io/badge/Email-kushaltrivedi82%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://your-portfolio-link-here">
    <img src="https://img.shields.io/badge/Portfolio-Website-4B8BBE?style=for-the-badge" />
  </a>
  <a href="https://your-resume-link-here">
    <img src="https://img.shields.io/badge/Resume-PDF-43A047?style=for-the-badge" />
  </a>
</p>

---

## 🛠 Skills & Tech Stack

**Languages & Frameworks**
Python · Java · JavaScript/TypeScript · C/C++ · Django · Flask · FastAPI · React

**ML, DL & NLP**
PyTorch · TensorFlow · scikit-learn · Transformers (Hugging Face) · DistilBERT Fine-Tuning · RAG · LangChain · ChromaDB · ETL Pipelines

**MLOps & Experiment Tracking**
MLflow · DVC · Custom Drift Monitoring · Docker · GitHub Actions (CI/CD)

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
**Stack:** Python · Flask · NASA GIBS Satellite Imagery · Groq LLM API · Chart.js · SciPy · Matplotlib

An interactive dashboard that tracks Gangotri Glacier retreat alongside Bay of Bengal ocean temperature and sea level anomalies, built for a research-style assignment with staged manager reviews at every phase.

- Built a 4-stage pixel analysis pipeline computing year-over-year glacier coverage, ocean temperature index, and sea level anomaly index from raw satellite imagery
- Fitted and compared linear and sine-trend regression models on 16 years of coverage data (2010–2025); the two independent models converge on a melt window of 2049–2052, with 50% coverage loss already projected around 2030
- Ran Pearson correlation analysis across all three signals on outlier-cleaned years, surfacing a weak positive coupling between glacier coverage and ocean temperature (r = 0.39) and coverage and sea level (r = 0.38)
- Shipped a live Flask dashboard with a global year-range filter, click-to-satellite-image inspection, and a watchdog-driven auto-refresh pipeline that pulls new NASA imagery automatically
- Added an AI Insights tab powered by the Groq API (Llama 3.1) with an Anthropic fallback, generating narrative summaries and deterministic KPI-based key findings from live dashboard data
- Layered a RAG + function-calling chatbot on top of the dashboard (ChromaDB, sentence-transformers, ReAct-style tool use) so the model can answer questions about the project's own findings in plain language

---

### 🎯 Sentiment Intelligence Platform
**Stack:** Python · PyTorch · Transformers (DistilBERT) · FastAPI · React · Docker · MLflow · DVC

- Fine-tuned DistilBERT on Yelp reviews and shipped it as a production NLP system rather than a notebook model
- Built a FastAPI + React serving stack, containerized end-to-end with Docker for reproducible deployment
- Set up MLflow and DVC for experiment tracking and data versioning, plus a custom drift monitor to catch model decay after deployment
- Wrote up the full build in an IEEE-format technical report

---

### 🚕 NYC Taxi Trip Data Mining & Fare Prediction
**Stack:** Python · scikit-learn · Pandas · NumPy · pytest

- Mined and engineered features across 11.2M+ NYC taxi records through a large-scale ETL and EDA pipeline
- Trained Linear Regression and Random Forest models, reaching R² ≈ 0.93 with a ~3% RMSE reduction over baseline
- Flagged fare anomalies using K-Means clustering (k=5, silhouette ≈ 0.38), z-score analysis, and Isolation Forest

---

### 📚 Book Recommendation System — Collaborative Filtering
**Stack:** Python (OOP) · FastAPI · Sparse Matrices

- Built a cosine-similarity recommendation engine over large sparse user–item matrices
- Served 210,000+ personalized recommendations to 105,000+ users through a FastAPI REST interface

---

### 🚗 Self-Driving Car Simulation — Neural Networks & Genetic Evolution
**Stack:** JavaScript (OOP) · Custom Neural Network

- Built a 3-layer feedforward neural network (5→6→4) from scratch, no external ML libraries
- Evolved 1,000 concurrent AI agents per generation via lerp-based mutation, cutting collisions by ~20%

---

### 🖐️ AI-Based Virtual Mouse System
**Stack:** Python · OpenCV · MediaPipe · PyAutoGUI

- Built real-time, hardware-free touchless mouse control tracking 21 hand landmarks per frame
- Tuned a pinch-gesture click mechanism to a 20px proximity threshold for reliable detection

---

## 🏆 Impact Snapshot

| ⚡ Performance                            | 📈 Scale                               | 🔧 Quality & Ownership                          |
| ----------------------------------------- | --------------------------------------- | ------------------------------------------------ |
| Glacier melt window narrowed to 2049–2052 across 2 independent models | 11.2M+ taxi records processed           | Full MLOps stack on sentiment platform: MLflow, DVC, Docker, drift monitoring |
| R² ≈ 0.93, ~3% RMSE reduction (taxi fares) | 210,000+ recommendations, 105K+ users   | pytest-validated pipelines, Git-managed code     |
| ~20% collision reduction (self-driving sim)| 16 years of satellite imagery analyzed  | Zero external ML libs on custom neural net        |

---

## 🌐 Let's Connect

| Type      | Link                                               |
| --------- | --------------------------------------------------- |
| GitHub    | https://github.com/kushal-1007                     |
| LinkedIn  | https://linkedin.com/in/kushal-trivedi10            |
| Email     | kushaltrivedi82@gmail.com                          |
| Portfolio | _Replace with your portfolio URL_                   |

---

## 📊 GitHub Activity Map

<p align="center">
  <img
    src="https://kushal-github-stats.vercel.app/api?username=kushal-1007&show_icons=true&include_all_commits=true&count_private=true"
    alt="Kushal Trivedi GitHub Stats"
    height="165"
  />
  <img
    src="https://kushal-github-stats.vercel.app/api/top-langs/?username=kushal-1007&layout=compact"
    alt="Top Languages"
    height="165"
  />
</p>

<p align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=kushal-1007"
    alt="GitHub Activity Graph"
    width="95%"
  />
</p>

<p align="center">
  <img
    src="https://github.com/kushal-1007/kushal-1007/raw/main/profile-3d-contrib/profile-gitblock.svg"
    alt="3D Contribution Graph"
    width="600"
  />
</p>

<p align="center">
  <img
    src="https://raw.githubusercontent.com/kushal-1007/kushal-1007/output/github-contribution-grid-snake-dark.svg"
    alt="Contribution Snake"
    width="600"
  />
</p>

<p align="center">
  Made with ❤️ by <strong>Kushal Trivedi</strong> · Always learning, always building
</p>
