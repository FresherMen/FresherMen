<div align="center">

# Ankur Pal

**AI/ML Software Engineer &bull; Cloud Infrastructure &bull; Production GenAI &bull; Computer Vision**  
Mohali, India &bull; Remote Available

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Space+Mono&size=16&duration=2800&pause=1000&color=94A3B8&center=true&vCenter=true&width=680&lines=Production+Hybrid+RAG+(ChromaDB+%2B+BM25+%2B+RRF);Autonomous+Agentic+Reasoning+%26+Tool+Dispatch;Computer+Vision+(YOLO,+Facial+Landmarks,+ANPR);Cloud+Deployments+on+AWS+%26+GCP+with+Docker)](https://git.io/typing-svg)

---

[Interactive Portfolio Website](https://freshermen.github.io) &nbsp;|&nbsp; [Email](mailto:palsaab1966@gmail.com) &nbsp;|&nbsp; [GitHub Repositories](https://github.com/FresherMen) &nbsp;|&nbsp; [Download Resume (PDF)](./Ankur_Pal_Resume.pdf)

</div>

---

## Executive Summary

AI/ML Software Engineer with 4+ years of hands-on experience designing, training, and deploying machine learning, deep learning, and Generative AI systems across computer vision, NLP, and autonomous agentic workflows. Extensive experience managing the complete machine learning lifecycle: data ingestion and ETL preprocessing, model development and fine-tuning (LoRA/QLoRA), validation, error analysis, and containerized cloud deployment on AWS and GCP through REST APIs and Docker microservices. Delivered production AI solutions for international clients across Australia, Japan, Saudi Arabia, and Brazil, cutting manual operational overhead by 35% to 70%.

---

## Detailed Technical Competencies

### 1. Python Software Engineering & Backend Architecture
- **Languages:** Python (3.10+), SQL (PostgreSQL, MySQL), Bash / Shell Scripting
- **Frameworks & APIs:** FastAPI, Django, Flask, Pydantic (v2), Uvicorn, RESTful API Design, Microservices Architecture
- **Engineering Practices:** Object-Oriented Programming (OOP), Asynchronous Programming (asyncio), Design Patterns, Modular Package Design, Virtual Environments (uv, venv, poetry), Git Workflow, PyTest

### 2. Cloud Infrastructure, Deployment & MLOps
- **Cloud Platforms:** Amazon Web Services (AWS EC2, S3), Google Cloud Platform (GCP Compute Engine, L40 GPU instances), Microsoft Azure (Document Intelligence, Logic Apps)
- **Containerization & Orchestration:** Docker, Docker Compose, Multi-Stage Builds, Container Registries
- **MLOps & Optimization:** Model Monitoring & Alerting, ONNX Runtime Inference Acceleration, LoRA & QLoRA Fine-Tuning, Quantization, CI/CD Integration, Linux Server Administration

### 3. Generative AI, RAG & Autonomous Agents
- **Architectures:** Retrieval-Augmented Generation (RAG), ReAct Reasoning Loops, Autonomous AI Agents, Multi-Agent Coordination, Tool Use / Function Calling, Prompt Engineering
- **Orchestration Frameworks:** LangChain, LangGraph, LlamaIndex, Anthropic Claude API, OpenAI GPT-4o, Groq LPU (LLaMA 3.3 70B)
- **Information Retrieval & Vector DBs:** ChromaDB, Pinecone Serverless, Dense Embeddings (SentenceTransformers all-MiniLM-L6-v2), Sparse Lexical Matching (BM25), Reciprocal Rank Fusion (RRF), Contextual Chunk Compression, Automated RAGAS Evaluation

### 4. Computer Vision & Real-Time Video Analytics
- **Object Detection & Tracking:** YOLO (v5/v8), Real-Time Video Analytics (30 FPS), Anomaly Detection, Road Asset Localization, Automatic Number Plate Recognition (ANPR) with OCR
- **Facial & Biometric Analysis:** Dlib 68-Point Facial Landmarks, Face Detection & Recognition (YuNet, InsightFace), Eye Aspect Ratio (EAR) Fatigue Monitoring, Facial Morphometry, Biometric Attribute Estimation (FairFace)
- **Multimodal Models:** Vision Language Models (LLaVA, Qwen-VL) for automated false positive/negative validation

### 5. Machine Learning, Data Science & Analytics
- **Libraries & Toolkits:** PyTorch, TensorFlow, Scikit-Learn, NumPy, Pandas, OpenCV, SciPy, Joblib
- **Data Engineering:** Star-Schema Dimensional Modeling, Automated Web Scraping (BeautifulSoup, Requests), ETL Pipelines, Exploratory Data Analysis (EDA)

---

## Professional Experience

### FutureVision &mdash; Remote
**Software Engineer &ndash; AI/ML** &bull; *Jul 2026 &ndash; Present*
- Build and deploy production computer vision and facial-analysis systems for Australian clients, serving PyTorch and ONNX deep learning models behind high-throughput FastAPI backends.
- **Rayted:** Trained classification and regression models for dermatological condition screening (23-class screening, 18-metric severity scoring) and facial symmetry analysis using landmark extraction to compute per-region alignment metrics.
- Built end-to-end biometric AI pipelines for facial morphometry, biological age/gender estimation, and multi-angle facial orientation analysis.
- Designed LangChain and LangGraph agent layers to aggregate multi-model outputs into structured, personalized recommendations exposed through authenticated REST APIs.

### HanuAI Private Limited &mdash; Mohali, India
**Software Engineer &ndash; AI/ML** &bull; *May 2023 &ndash; Jul 2026*
- **Road Asset Detection (NHAI):** Engineered an end-to-end computer vision system utilizing YOLO and Transformer architectures to detect road signs, highway anomalies, and GPS-tagged assets across 500+ km of highway data. Trained on 15,000+ custom-annotated images achieving 92% mAP (18% above baseline), with automated ETL preprocessing reducing manual survey effort by 60%.
- **Automatic Number Plate Recognition (ANPR):** Deployed a real-time YOLO + OCR system achieving 98% detection accuracy at 30 FPS on live video feeds; containerized with Docker on AWS EC2, with automatic plate blurring for privacy compliance and REST API database integration for vehicle lookup and logging.
- **Driver Fatigue & Alertness Monitoring:** Developed a real-time CNN-based model with 95% accuracy for driver fatigue and distraction alerting; integrated model monitoring in production, reducing manual monitoring by 70% and operational costs by 35%.
- **Furniture Anomaly Detection:** Delivered an object detection product with 90% precision, deployed as a Dockerized microservice across 5 client environments on HanuAI's core monitoring platform.
- **MLOps Benchmarking Framework:** Built a modular benchmarking framework (precision, recall, F1-score, inference speed) with CI/CD hooks for automated model evaluation; adopted across 8 internal projects, cutting evaluation time by 40%.
- **Vision Language Model (VLM) Pipeline:** Integrated LLaVA and Qwen-VL into an automated review pipeline to filter false positives and false negatives from detection outputs via REST APIs.
- **Internal QA Automation Platform:** Designed a full-stack Django dashboard deployed on AWS EC2 via Docker, featuring real-time data filtering, annotation review workflows, and role-based access control.
---

## Featured Systems & Repositories

### Production Generative AI & Autonomous Agent Systems

#### [DocMind-Hybrid-RAG](https://github.com/FresherMen/DocMind-Hybrid-RAG)
**Enterprise Hybrid Search & Evaluation System**  
Production-grade full-stack RAG application deployed via Docker Compose. Combines dense vector similarity (ChromaDB) with sparse lexical matching (BM25) through Reciprocal Rank Fusion (RRF). Features LLM multi-query expansion, contextual chunk compression, and automated RAGAS evaluation metrics (faithfulness, relevancy, context precision).  
*Stack: Python, FastAPI, React 18, ChromaDB, BM25, Docker Compose*

#### [Autonomous-AI-Research-Agent](https://github.com/FresherMen/Autonomous-AI-Research-Agent)
**Agentic Multi-Step Research Assistant**  
Autonomous research assistant powered by Groq LLaMA 3.3 70B with native function calling. Autonomously dispatches between document vector search, live web queries, and persistent markdown note taking across multi-iteration ReAct loops. Includes an automated report synthesizer for executive briefs and comparative studies, paired with a React 19 workspace.  
*Stack: Python, FastAPI, React 19, Vite, Groq Llama 3.3, ChromaDB*

#### [Financial-Analyst-RAG](https://github.com/FresherMen/Financial-Analyst-RAG)
**SEC Form 10-K Quantitative Intelligence Assistant**  
Specialized financial RAG assistant for analyzing corporate annual filings (NVIDIA FY2024 Form 10-K). Configured with temperature=0 for deterministic, hallucination-free numerical extraction, LangChain orchestration, Pinecone serverless vector database, and an interactive Streamlit dashboard with expandable source evidence verification.  
*Stack: Python, LangChain, Pinecone, Groq Llama 3.3, Streamlit, MiniLM*

---

### Machine Learning, Computer Vision & Data Analytics

#### [driver-drowsiness-detection](https://github.com/FresherMen/driver-drowsiness-detection)
**Real-Time Computer Vision Driver Fatigue Monitor**  
Computer vision pipeline monitoring driver alertness in real-time video streams using facial landmark localization and continuous Eye Aspect Ratio (EAR) calculation with consecutive-frame threshold alarms.  
*Stack: Python, OpenCV, NumPy, SciPy, Imutils*

#### [loan-default-prediction](https://github.com/FresherMen/loan-default-prediction)
**Credit Risk Scoring & Loan Eligibility System**  
End-to-end supervised machine learning classification pipeline evaluating demographic, credit, and financial risk attributes, integrated with a responsive Flask web application for instant eligibility scoring.  
*Stack: Python, Scikit-Learn, Flask, Pandas, Joblib*

#### [t20-cricket-analytics](https://github.com/FresherMen/t20-cricket-analytics)
**T20 World Cup Sports Analytics & Best 11 Pipeline**  
Automated web scraping pipeline from ESPNcricinfo, data transformation in Pandas, and star-schema dimensional modeling (fact and dimension tables) evaluating performance metrics across match phases to select an optimal tournament team.  
*Stack: Python, Pandas, Web Scraping, Star Schema, Power BI*

---

## Education

**Punjab Technical University** &mdash; Punjab, India  
*Bachelor of Technology (B.Tech) &ndash; Computer Engineering* &bull; Jan 2019 &ndash; May 2023  
- CGPA: 7.8 / 10

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=FresherMen&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub Stats" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=FresherMen&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages" width="48%" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=FresherMen&theme=github_dark&hide_border=true" alt="Contribution Streak" width="97%" />

</div>

---

<div align="center">
  <sub>Ankur Pal &bull; AI/ML Software Engineer &bull; 2026</sub>
</div>
