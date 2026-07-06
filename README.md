# Hi, I'm Ardra! 👋

I am a B.Tech'2026 graduate in Industrial Engineering and a full-stack AI/ML engineer focused on building, optimising, and deploying production-grade AI systems. Rather than just performing data analysis, I design end-to-end architectures including LLM applications, Retrieval-Augmented Generation (RAG) systems, agentic pipelines, and scalable cloud deployments.

---

## 🏗️ AI & Intelligent Systems

* **[Bolt-Hire AI](https://github.com/ardraxdrowski/Bolt-Hire-AI-virtual-interviewing-system)**
  An intelligent, automated voice and text interview platform. It utilises **Llama 7B (via llama-cpp-python)** for contextual follow-up question generation, **OpenAI Whisper** for speech-to-text transcription, and **Coqui TTS** for speech synthesis. The system runs on a **Flask** backend, tracks candidates with an SQLite DB, and evaluates performance across 5 key dimensions with automated email invites sent via **SendGrid**.

* **[Spare Part Recognition & Smart Inventory Management](https://github.com/ardraxdrowski/spare-part-recognition-and-inventory-tracking-system)**
  An AI-powered computer vision inventory tracking and decision support system. Configured image processing pipelines and trained a custom **YOLOv8** object detection model to identify critical machine parts. Features a **Flask** web portal backed by **SQLite** that maps recognised parts to pricing and stock levels, utilising a custom-weighted Criticality Index formula to suggest reordering decisions.

* **[Talk with your PDF](https://github.com/ardraxdrowski/Talk-with-your-PDF)**
  A Retrieval-Augmented Generation (RAG) chatbot utility that answers questions based on uploaded documents. Developed using **Streamlit** and **LangChain** with **PDFPlumber** for document parsing, **Chroma DB** as a vector database for semantic chunk indexing, and **Mistral AI** to generate grounded responses.

---

## 📊 Product Intelligence & Analytics

* **[OSDeliverIQ](https://github.com/ardraxdrowski/OSDeliverIQ)**
  A project health intelligence tool for open-source repositories. Engineered an async ingestion pipeline using **FastAPI**, **HTTPX**, and **APScheduler** to poll GitHub API data into a **PostgreSQL** database via **SQLAlchemy 2.0**. It integrates the **Anthropic SDK (Claude 3.5 Sonnet)** to programmatically summarise PR blockers and compile PM-ready status reports, presented on a **Jinja2**-templated dashboard.

* **[SQL Customer Behaviour Analysis](https://github.com/ardraxdrowski/sql-customer-behaviour-analysis)**
  An end-to-end SQL analysis of user behaviour from registration to paid conversion. Queried and analysed transaction and event logs to extract actionable insights on conversion rates, onboarding bottlenecks, and engagement delays to drive product-led growth.

* **[Model Evaluation & Hyperparameter Tuning](https://github.com/ardraxdrowski/-Model-evaluation-and-Hyperparameter-tuning)**
  A machine learning regression pipeline for house price prediction. Conducted extensive exploratory data analysis, feature engineering, and trained multiple models (XGBoost, LightGBM) using **scikit-learn** with hyperparameter tuning via **RandomizedSearchCV** to compare predictive accuracy.

---

## 🛠️ Current Focus & Active Initiatives

* **Bolt-Hire AI Cloud Migration:** Migrating database and service components to a scalable cloud environment to support production B2C/B2B workloads.
* **LifeLink AI Refactoring:** Refactoring the backend architecture (FastAPI, Redis, AWS Bedrock) to transition from a prototype to a more reliable, production-ready system for donor matching, resolving integration gaps with AWS SNS/SES, and optimising ECS Fargate container deployments.
* **Converse AI (Private Archive):** Architecting a multi-agent RAG chatbot as the next-generation evolution of *Talk with your PDF*. It replaces single-flow RAG with an **agentic architecture** featuring 3+ specialized agents (Coordinator, Ingestion, Retrieval, and LLM Response) communicating via **Model Context Protocol (MCP)**. Built on a **React** frontend and a **Python** backend, it supports multi-format ingestion (.pdf, .pptx, .csv, .docx, .md) and context-aware multi-turn conversation with source attribution using **FAISS/Chroma**.
* **Agentic Workflows:** Designing and testing autonomous coding and development workflows using frameworks like Antigravity and Cursor to streamline software development lifecycles.

---

## 🛠️ Tech Stack

* **Languages:** Python, JavaScript, SQL, HTML5, CSS3
* **AI / ML / NLP:** Large Language Models (Claude 3.5 Sonnet, Llama, GPT-4), AWS Bedrock, Anthropic SDK, LangChain, Chroma DB, RAG pipelines, OpenAI Whisper, Coqui TTS, YOLOv8, Scikit-Learn, XGBoost, LightGBM
* **Backend:** FastAPI, Flask, SQLite, PostgreSQL, SQLAlchemy 2.0, APScheduler, HTTPX, Jinja2, Streamlit
* **Cloud, Databases & DevOps:** AWS (ECS Fargate, RDS, ElastiCache, S3, CloudFront, SNS, SES), Redis, MySQL, Docker, Docker Compose, Git, SendGrid API

---

## 🏆 Achievements

* **Google Cloud Agentic AI Day Hackathon 2025 Finalist:** Top **7.7%** out of 9,100+ team submissions and 57,000+ developers (representing the top **3.5%** of individual participants).

---

## 🏆 Certifications

* **Python for Data Science** – IIT Madras
* **Transformers in Practice** – DeepLearning.AI
* **Gen AI with Large Language Models** – DeepLearning.AI

---

## 🤝 Connect with me

* **LinkedIn:** [linkedin.com/in/ardra-t-j](https://www.linkedin.com/in/ardra-t-j)
* **GitHub:** [@ardraxdrowski](https://github.com/ardraxdrowski)
