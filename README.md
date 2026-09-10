# 👋 Hi, I'm Aarya Shirsath

### AI/ML Engineer · Full-Stack · Backend

I build **AI-powered platforms, intelligent APIs, and production-grade software** — from idea to a live URL, not just a notebook.

I'm a final-year Computer Science & Engineering student at **VIT Bhopal University**, focused on applied AI/LLM systems, backend engineering, and scalable full-stack products.

> **Build → Engineer → Deploy → Improve**

---

# 🌐 Portfolio

### **[View My Portfolio →](https://portfolio-aarya07.vercel.app/)**

A developer portfolio showcasing my work across **AI/ML, backend engineering, full-stack development, and intelligent software systems**.

---

# 🚀 Featured Work

## 🛕 India's Sacred Heritage Portal — Temple Heritage

### AI-Powered Temple Discovery & Pilgrimage Planning Platform

A full-stack platform for discovering Indian temples, festivals, and traditions, with a **Claude-powered itinerary planner and assistant**, visitor reviews, and gamified pilgrimage tracking.

**Stack:** `Next.js` `React` `TypeScript` `Supabase` `Claude API`

### Highlights

* 🤖 Claude-powered AI itinerary planner & in-app assistant
* 🔐 Supabase-backed authentication & persistence
* ⭐ Visitor reviews with photo uploads & aggregate ratings
* 🛡️ Admin moderation dashboard
* 🗺️ Key-less Google Maps integration for temple locations
* 🛂 Gamified "Pilgrimage Passport" with shareable stamp-book export

**[💻 Repository](https://github.com/Aarya0706/temple-heritage)** · **[🌐 Live Demo](https://temple-heritage-fawn.vercel.app/)**

---

## 🏥 MediAgent AI

### Agentic AI Hospital Triage & Clinical Decision Support Platform

An AI-powered healthcare platform combining **multi-agent LLM workflows, deterministic safety guardrails, clinical triage, department routing, lab analysis, and doctor workflows**.

**Stack:** `Python` `LangChain` `Groq` `LLaMA` `Streamlit` `SQLAlchemy` `Plotly` `OpenFDA`

### Highlights

* 🤖 Multi-agent architecture: Intake → Triage → Recommendation
* 🏥 Smart routing across **13+ hospital departments**
* 💊 Live OpenFDA drug-interaction checks
* 🧪 Lab-report OCR via pdfplumber + Tesseract
* 📊 Plotly analytics dashboard over an SQLAlchemy-backed store
* 📄 AI-generated PDF consult reports

**[💻 Repository](https://github.com/Aarya0706/mediagent-ai)** · **[🌐 Live Demo](https://mediagent-ai.streamlit.app/)**

---

## 🛡️ FraudShield AI

### Real-Time, Explainable Financial Fraud Detection Platform

A production-style fraud detection platform built with **XGBoost and FastAPI**, combining engineered transaction features, real-time fraud scoring, risk classification, SHAP-based explanations, batch prediction, and runtime monitoring.

**Stack:** `Python` `XGBoost` `FastAPI` `Pydantic` `Scikit-learn` `Pandas` `NumPy` `SHAP`

### Highlights

* ⚡ Real-time fraud scoring through a FastAPI REST API
* 📊 **0.9997 ROC-AUC · 0.9933 PR-AUC · 95%+ precision & recall** on a time-aware PaySim evaluation
* 🧠 **SHAP explainability** with human-readable top risk factors
* 🚦 **LOW / MEDIUM / HIGH / CRITICAL** risk classification
* 📦 Batch prediction with Pydantic-validated request/response schemas
* 📈 Runtime prediction monitoring, inference latency tracking & model-version hashing
* 🛡️ Rate limiting, CORS protection, and optional API-key authentication
* 🌐 Full-stack deployment with **Vercel + Render** and interactive Swagger/OpenAPI documentation

> **Note:** These metrics are benchmark results on the synthetic **PaySim** dataset and should not be interpreted as guaranteed real-world banking performance.

**[💻 Repository](https://github.com/Aarya0706/FraudShield-AI)** · **[🌐 Live Demo](https://fraud-detection-api-eta.vercel.app/)** · **[📚 API Docs](https://fraud-detection-api-w9hz.onrender.com/docs)**

---


## 🩺 Healthcare Appointment & Follow-up Manager

### Full-Stack Clinic Platform with Role-Based Portals

A clinic platform with separate **patient, doctor, and admin** portals — pre-visit symptom analysis, post-visit summaries, email notifications, and calendar sync, backed by an LLM.

**Stack:** `Node.js` `Express` `PostgreSQL` `Prisma` `Gemini`

### Highlights

* 🧑‍⚕️ Role-based patient / doctor / admin portals
* 🤖 LLM-generated pre-visit urgency summaries
* 📝 LLM-generated patient-friendly post-visit summaries
* 📧 Email confirmations via Nodemailer
* 📅 Google Calendar sync with OAuth 2.0
* 💊 Automated medication reminders

**[💻 Repository](https://github.com/Aarya0706/healthcare-appointment-manager)** · **[🌐 Live Demo](https://healthcare-appointment-manager-sandy.vercel.app/)**

---

## 🎓 EduGrade-AI

### AI-Powered Virtual Classroom & Assignment Evaluation

A classroom platform combining **OCR, LLM-based grading, plagiarism detection, handwriting comparison, and role-based access** to automate assignment evaluation.

**Stack:** `Python` `Flask` `SQLAlchemy` `Google Document AI` `Gemini` `Bootstrap`

### Highlights

* 📄 PDF/OCR assignment extraction via Google Document AI
* 🤖 Gemini-powered automated grading
* 🔍 Two-layer plagiarism detection
* ✍️ Handwriting comparison escalation
* 🗄️ Normalized SQLAlchemy schema with AI-artifact caching
* 🔐 Role-based access control

**[💻 Repository](https://github.com/Aarya0706/EduGrade-AI)** · **[🌐 Live Demo](https://edugrade-ai-d757.onrender.com/)**

---

## 📚 Document Q&A — RAG Chatbot

### Retrieval-Augmented Chat Over Your Own PDFs

Strictly grounded document Q&A built with **LangChain, Gemini embeddings, and ChromaDB** — every answer cites its source, page, and similarity score.

**Stack:** `Python` `LangChain` `Gemini` `ChromaDB` `Render`

### Highlights

* 📎 Retrieval-augmented generation over uploaded PDFs
* 🔗 Source document, page & similarity-score citations
* 🚫 Says "not in the docs" instead of guessing
* ⏱️ Rate-limit-aware batched ingestion for free-tier API quotas

**[💻 Repository](https://github.com/Aarya0706/rag-chatbot)** · **[🌐 Live Demo](https://rag-chatbot-icae.onrender.com/)**

---

## 🚀 Autonomous Lunar Landing — PPO

### Deep RL Agent for Gymnasium's LunarLander-v3

A PPO agent built with Stable-Baselines3 that learns to land a spacecraft, with a custom callback tracking **safe landings, crashes, and timeouts** rather than relying only on mean reward.

**Stack:** `Python` `Stable-Baselines3` `Gymnasium` `PyTorch` `TensorBoard`

### Highlights

* 🛰️ PPO-trained landing agent with TensorBoard curves
* 📊 Outcome breakdown: safe / crash / timeout
* 💾 50k-step checkpointing
* 🧪 Deterministic evaluation harness across multiple episodes

**[💻 Repository](https://github.com/Aarya0706/Autonomous-Lunar-Landing-PPO)**

---

# 🧑‍💻 About Me

🎓 **B.Tech CSE — VIT Bhopal University**

💻 **Languages:** Java · Python · SQL · JavaScript / TypeScript

⚙️ **Backend:** FastAPI · Node.js · Express · Flask · REST APIs · Pydantic · SQLAlchemy · Prisma

🤖 **AI/ML:** LangChain · Claude API · RAG · Multi-Agent Systems · XGBoost · Scikit-learn

🖥️ **Frontend:** Next.js · React · TypeScript

☁️ **Infrastructure & Deployment:** AWS · Docker · Vercel · Railway · Render · Supabase · Git

🗄️ **Databases:** PostgreSQL · Supabase · MySQL · SQLite · ChromaDB

---

# 🛠️ Tech Stack

### Languages

`Java` `Python` `SQL` `JavaScript` `TypeScript`

### Frontend

`Next.js` `React` `TypeScript` `HTML/CSS/JS` `Streamlit`

### Backend & APIs

`FastAPI` `Node.js` `Express` `Flask` `REST APIs` `Pydantic` `Uvicorn` `SQLAlchemy` `Prisma`

### AI / ML

`LangChain` `Claude API` `RAG` `Multi-Agent Systems` `Prompt Engineering`

`XGBoost` `Scikit-learn` `Pandas` `NumPy`

`Anthropic` `Groq` `Gemini`

### Infrastructure & DevOps

`AWS EC2` `S3` `IAM` `VPC` `Docker` `Vercel` `Railway` `Render` `Git` `GitHub`

### Databases

`PostgreSQL` `Supabase` `MySQL` `SQLite` `ChromaDB`

---

# 💼 Experience

### AI/ML Intern — MPOnline

**May 2026 – July 2026**

Worked across the machine-learning lifecycle, including data preprocessing, model development, and evaluation.

Built CNN classifiers for **CIFAR-10, LFW face recognition, and MRI brain-tumor classification**, achieving **89% accuracy**.

---

### Software Development Engineer Intern — MPOnline

**May 2026 – July 2026**

Built **TaskBoard**, a full-stack task management system using Flask and MySQL.

* 🔐 Bcrypt-secured authentication
* 📋 Employee task management
* 🔄 REST API development
* 📊 Live dashboard for tracking and completing tasks
* 🗄️ MySQL integration

---

# 🏆 Achievements

* 🥇 **TCS CodeVita Season 13** — Top 10% globally · 90th percentile · Global Rank **15,033**
* 💻 **HackerRank Certified Software Engineer**
* ☁️ **AWS Cloud Training** — EC2, S3, IAM & VPC
* 🤖 **ServiceNow Virtual Internship** — Agentic AI & workflow automation
* 🌐 **Computer Networking** — Coursera · TCP/IP, DNS, HTTP
* 📊 **Marketing Analytics** — NPTEL · 95% · Elite
* 🔬 Co-authored research paper: **"Study on Edge Computing for Managing High Volume Data"**
* 🧩 Completed the **50-day #DrGViswanathanChallenge** — DSA in Java

---

# 🎯 Current Focus

I'm currently focused on **AI-powered full-stack platforms, LLM applications, backend engineering, system design, and scalable software development** — while building toward **SDE-1 / new-grad roles**.

---

# 🤝 Let's Connect

<p align="center">

<a href="https://github.com/Aarya0706">
<img src="https://img.shields.io/badge/GitHub-Aarya0706-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<a href="https://www.linkedin.com/in/aarya-shirsath-9b7684340/">
<img src="https://img.shields.io/badge/LinkedIn-Aarya%20Shirsath-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

<a href="mailto:arshir07@gmail.com">
<img src="https://img.shields.io/badge/Email-arshir07%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

</p>

---

<p align="center">

### 🚀 Building intelligent systems, one commit at a time.

</p>
