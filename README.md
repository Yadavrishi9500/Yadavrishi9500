<div align="center">

# Hi, I'm Rishi Yadav 👋

### AI & Software Developer

**Computer Vision • Generative AI & LLMs • Backend Engineering • Full-Stack Development**

<p>
  <a href="https://github.com/Yadavrishi9500">
    <img src="https://img.shields.io/badge/GitHub-Yadavrishi9500-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/rishi-yadav-5a2783298/">
    <img src="https://img.shields.io/badge/LinkedIn-Rishi_Yadav-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

</div>

---

## 👨‍💻 About Me

I'm a **Computer Science student and developer** interested in building AI-powered software systems that solve practical problems.

My work currently spans:

* 👁️ **Computer Vision & Edge AI**
* 🧠 **Generative AI, LLMs & Retrieval-Augmented Generation**
* ⚙️ **Backend Engineering & REST APIs**
* 🌐 **Full-Stack Application Development**
* 🗄️ **Databases & Data-Driven Systems**
* 🐳 **Containerization, Testing & CI**

I enjoy going beyond basic prototypes — understanding the problem, designing the architecture, integrating different technologies, debugging difficult issues, and turning ideas into complete working systems.

> **I’m most interested in building AI systems that interact with real-world data — video, images, documents, APIs, and production-style applications.**

---

# ⭐ Flagship Project

## 🚦 [Traffic Guardian Pro](https://github.com/Yadavrishi9500/Traffic-Guardian-Pro)

### Edge-AI Dashcam Surveillance for Wrong-Way Vehicle Detection

Traffic Guardian Pro is an **edge-computing computer vision system** designed to detect and track wrong-way vehicles from a moving dashcam feed.

The system combines **real-time object detection, spatial tracking, motion analysis, evidence capture, OCR, and automated violation logging** into one complete AI pipeline.

<p>
  <a href="https://github.com/Yadavrishi9500/Traffic-Guardian-Pro">
    <img src="https://img.shields.io/badge/View_Project-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

### 🔍 Core AI Pipeline

```text
Dashcam Video
      │
      ▼
YOLOv8 Vehicle Detection
      │
      ▼
12-Frame Spatial Tracking
      │
      ▼
Motion + Bounding Box Analysis
      │
      ▼
Wrong-Way Decision Logic
      │
      ▼
Close-Range Evidence Capture
      │
      ▼
OpenCV Plate Preprocessing
      │
      ▼
EasyOCR License Plate Recognition
      │
      ▼
Automatic Violation Logging
```

### ✨ Key Features

* 🚗 Real-time vehicle detection using **YOLOv8**
* 🎯 12-frame spatial vehicle tracking
* 🧭 Direction analysis using movement vectors
* 📈 Bounding-box growth analysis for approaching vehicles
* 🧠 Multi-factor wrong-way detection logic
* 🎥 Designed around moving-camera / dashcam input
* 📸 Close-range evidence capture
* 🔤 License plate recognition using **EasyOCR**
* 🖼️ OpenCV preprocessing with filtering and contrast enhancement
* 📝 Automatic CSV violation logging
* 🖥️ Real-time Tkinter monitoring dashboard
* 📄 Complete project documentation including SRS and technical report

### 🧰 Tech Stack

`Python` `YOLOv8` `OpenCV` `EasyOCR` `Tkinter` `Computer Vision` `Object Detection` `OCR`

> **What makes this project important to me:** it combines multiple AI and software components into one complete system rather than stopping at object detection alone.

---

# 🧠 Generative AI / LLM Project

## 📚 [DocuMind RAG](https://github.com/Yadavrishi9500/documind-rag)

### Local Multi-Document Retrieval-Augmented Generation Assistant

DocuMind is a privacy-focused **RAG-based AI research assistant** that allows users to upload multiple PDF documents and ask grounded questions about them.

Instead of sending the entire document to an LLM or relying only on model knowledge, DocuMind retrieves the most relevant document chunks using **semantic similarity** and passes only that evidence to a locally running **Llama 3.2 model through Ollama**.

<p>
  <a href="https://github.com/Yadavrishi9500/documind-rag">
    <img src="https://img.shields.io/badge/View_Project-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://lnkd.in/p/gQq-AJts">
    <img src="https://img.shields.io/badge/Watch_Demo-E4405F?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

### 🧠 RAG Pipeline

```text
PDF Documents
      │
      ▼
Page-Level Text Extraction
      │
      ▼
Overlapping Text Chunking
      │
      ▼
Sentence Transformer Embeddings
      │
      ▼
Vector Index
      │
      │
User Question
      │
      ▼
Query Embedding
      │
      ▼
Semantic Similarity Search
      │
      ▼
Top-K Relevant Chunks
      │
      ▼
Context Construction
      │
      ▼
Ollama + Llama 3.2
      │
      ▼
Grounded Answer
 + Page-Level Sources
```

### ✨ Key Features

* 📄 Multi-PDF knowledge base
* 🧩 Page-aware overlapping chunking
* 🧠 Local embeddings using **Sentence Transformers**
* 🔍 Semantic retrieval using vector similarity
* 📚 Lightweight persistent vector index
* 🤖 Local **Llama 3.2** inference through Ollama
* 🔗 Page-level source citations
* 👀 Retrieved source previews
* 📊 Similarity confidence scores
* 🛡️ Guardrails for unsupported questions
* ⚡ FastAPI backend
* 💬 Streamlit chat interface
* 🧪 Pytest unit tests
* ✅ GitHub Actions CI

### 🧰 Tech Stack

`Python` `RAG` `Llama 3.2` `Ollama` `Sentence Transformers` `FastAPI` `Streamlit` `PyMuPDF` `NumPy` `Pytest` `GitHub Actions`

> Built to understand the **core mechanics of Retrieval-Augmented Generation** — embeddings, chunking, semantic retrieval, context construction, grounding, and local LLM inference — rather than hiding the full pipeline behind a high-level framework.

---

# ⚙️ Full-Stack Engineering Project

## 📝 [Form Builder & Response Management System](https://github.com/Yadavrishi9500/form-builder-app)

### Full-Stack Internship Project • Team Lead

A complete form-building and response-management platform integrating a **Flutter frontend with a FastAPI backend**.

The application supports dynamic forms, authentication, responses, file uploads, exports, databases, caching, and containerized deployment.

### 🏗️ Architecture

```text
                    Browser
                       │
                       ▼
                 Flutter Web
                       │
                       ▼
                    FastAPI
                  /          \
                 ▼            ▼
           PostgreSQL       Redis
```

### ✨ Highlights

* Dynamic form creation
* Multiple configurable field types
* User authentication
* JWT-secured API requests
* Dynamic schema validation
* Response submission and management
* File upload support
* PDF export
* Excel export
* PostgreSQL persistence
* Redis integration
* Flutter frontend
* FastAPI REST backend
* Dockerized development environment
* Nginx-served Flutter Web application

### 👨‍💻 My Role

* Team Lead
* Frontend-backend integration
* REST API integration
* Authentication flow integration
* API schema mapping
* Debugging and issue resolution
* End-to-end system coordination
* Docker environment integration

### 🧰 Tech Stack

`Flutter` `Dart` `FastAPI` `Python` `PostgreSQL` `Redis` `SQLAlchemy` `JWT` `Docker` `Nginx`

---

# ☕ Other Project

## [Macro Manager System](https://github.com/Yadavrishi9500/Macro-Manager-System)

A Java-based application focused on **object-oriented programming, structured application development, and modular software design**.

`Java` `Maven` `OOP`

---

# 🧰 Technical Skills

<div align="center">

## 💻 Programming Languages

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />

<br><br>

## 🤖 Artificial Intelligence & Computer Vision

<img src="https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
<img src="https://img.shields.io/badge/Computer_Vision-FF6F00?style=for-the-badge" />
<img src="https://img.shields.io/badge/Object_Tracking-4B8BBE?style=for-the-badge" />
<img src="https://img.shields.io/badge/OCR-6A5ACD?style=for-the-badge" />
<img src="https://img.shields.io/badge/EasyOCR-2E8B57?style=for-the-badge" />

<br><br>

## 🧠 Generative AI & LLMs

<img src="https://img.shields.io/badge/RAG-7B2CBF?style=for-the-badge" />
<img src="https://img.shields.io/badge/LLM_Integration-5B5BD6?style=for-the-badge" />
<img src="https://img.shields.io/badge/Llama_3.2-5B5BD6?style=for-the-badge" />
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge" />
<img src="https://img.shields.io/badge/Sentence_Transformers-FFB000?style=for-the-badge" />
<img src="https://img.shields.io/badge/Embeddings-8A2BE2?style=for-the-badge" />
<img src="https://img.shields.io/badge/Semantic_Search-6C63FF?style=for-the-badge" />
<img src="https://img.shields.io/badge/Prompt_Grounding-944DFF?style=for-the-badge" />

<br>

**Working knowledge of:**

`Retrieval-Augmented Generation` • `Embedding Models` • `Semantic Retrieval` • `Vector Similarity` • `Context Construction` • `Local LLM Inference` • `Prompt Grounding` • `Document AI`

<br><br>

## ⚙️ Backend Engineering & APIs

<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/REST_APIs-02569B?style=for-the-badge" />
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" />
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
<img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" />

<br><br>

## 🗄️ Databases & Data

<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />

<br><br>

## 🌐 Application Development

<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/Tkinter-3776AB?style=for-the-badge&logo=python&logoColor=white" />

<br><br>

## 🛠️ DevOps, Testing & Tools

<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />

</div>

---

# 🧠 What I Enjoy Building

<table>
<tr>
<td width="50%" valign="top">

### 👁️ Computer Vision Systems

Real-time AI systems involving:

* Object detection
* Vehicle tracking
* Motion analysis
* OCR
* Image preprocessing
* Evidence capture
* Edge-AI workflows

</td>
<td width="50%" valign="top">

### 🤖 Generative AI Systems

Applications involving:

* Retrieval-Augmented Generation
* LLM integration
* Embeddings
* Semantic search
* Grounded generation
* Local LLM inference
* Document intelligence

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ⚙️ Backend Engineering

Building:

* REST APIs
* Authentication systems
* Database-driven services
* API integrations
* Validation pipelines
* Reliable application backends

</td>

<td width="50%" valign="top">

### 🏗️ Complete Software Systems

Connecting:

* AI models
* Backend services
* Frontends
* Databases
* Containers
* Testing & CI

into complete working applications.

</td>
</tr>
</table>

---

# 🔬 Currently Exploring

```text
Generative AI
├── Advanced RAG Architectures
├── LLM Application Design
├── Hybrid Retrieval
├── Reranking
├── Vector Databases
└── RAG Evaluation

Computer Vision
├── Real-Time Detection
├── Multi-Object Tracking
├── Edge AI
└── Intelligent Video Analytics

Software Engineering
├── Backend Architecture
├── Testing & CI/CD
├── Containerized Applications
└── Production AI Systems
```

---

# 📊 GitHub Stats

<div align="center">

<img
src="https://github-readme-stats.vercel.app/api?username=Yadavrishi9500&show_icons=true&hide_border=true&rank_icon=github"
height="170"
/>

<img
src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yadavrishi9500&layout=compact&hide_border=true"
height="170"
/>

</div>

---

# 🎯 Engineering Philosophy

I enjoy projects where **AI is only one part of the solution**.

The interesting part for me is connecting models with tracking logic, retrieval systems, APIs, databases, user interfaces, testing, and application infrastructure to turn an AI capability into a usable software system.

```text
Problem
   ↓
Understand the Data
   ↓
Design the System
   ↓
Build the AI / Logic
   ↓
Integrate Components
   ↓
Test & Debug
   ↓
Build Something People Can Use
```

---

# 🤝 Let's Connect

<div align="center">

I'm always interested in discussing:

**Artificial Intelligence • Computer Vision • Generative AI • LLM Applications • Backend Engineering • Full-Stack Development**

<br>

<a href="https://www.linkedin.com/in/rishi-yadav-5a2783298/">
  <img src="https://img.shields.io/badge/LinkedIn-Rishi_Yadav-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://github.com/Yadavrishi9500">
  <img src="https://img.shields.io/badge/GitHub-Yadavrishi9500-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br><br>

### Build. Learn. Improve. Repeat.

*Turning ideas into practical AI-powered software systems.*

</div>
