# Hi 👋 I'm Tautik Sinha Roy

### AI/ML Engineer | Generative AI | Agentic AI | PyTorch

I'm a Computer Science Engineering student focused on building **real-world AI/ML systems** rather than just experimenting with models.

My work spans **Deep Learning, Computer Vision, Generative AI, RAG, Agentic AI, and Machine Learning Engineering**. I enjoy taking an idea from data and model development all the way to **evaluation, backend integration, deployment, and production-oriented system design**.

Currently building systems involving **LLM-powered applications, retrieval pipelines, agentic workflows, tool use, and human-in-the-loop AI systems**.

* 🌍 Based in India
* 🧠 Currently focused on **Generative AI, RAG, Agentic AI & AI Engineering**
* 🖥️ Portfolio: [Portfolio](http://portfolio-tautiks-projects-de20d139.vercel.app)
* ✉️ Email: [tautiksinharoy@gmail.com](mailto:tautiksinharoy@gmail.com)
* 💻 GitHub: [Tautik05](https://github.com/Tautik05)

---

## 🚀 Featured Projects

### 🤖 NovaDesk AI — Enterprise Customer Support & Autonomous Resolution Engine

An agentic customer support system built around **LangGraph, MCP, FastAPI, PostgreSQL, and LLM-powered decision making**.

The system handles the complete ticket lifecycle — from classification and entity extraction to context retrieval, deterministic policy enforcement, response generation, and controlled action execution.

**Key engineering features:**

* Stateful agentic workflows with **LangGraph**
* **Model Context Protocol (MCP)** tool integration
* Deterministic business rules and safety guardrails
* Human-in-the-loop approval for consequential actions
* Multi-model LLM fallback and resilience
* PostgreSQL-backed system of record
* FastAPI backend with asynchronous ticket processing
* Automated workflow and policy evaluation
* Customer and support-operator dashboards

**Tech:** `Python` `FastAPI` `LangGraph` `LangChain` `MCP` `Groq` `PostgreSQL` `SQLAlchemy` `Pydantic` `JavaScript`

---

### 📄 Financial Document Intelligence — Production RAG

A production-oriented **Retrieval-Augmented Generation system for financial PDF reports**.

The system preserves document structure during ingestion, performs semantic retrieval using BGE embeddings and Pinecone, and generates grounded answers with source/page attribution using Gemini.

**Key engineering features:**

* Structure-aware PDF parsing and chunking
* BGE embeddings with PyTorch
* Per-document Pinecone namespaces
* Grounded Gemini generation
* Source and page attribution
* PostgreSQL document lifecycle management
* Supabase object storage
* Retrieval benchmarking across financial documents
* Dense vs Hybrid retrieval experiments
* Cross-encoder reranking experiments

**Retrieval benchmark:**

`Dense Retrieval — 93.3% Hit@5`

`Hybrid BM25 + Dense + RRF — 73.3% Hit@5`

The final system uses dense retrieval based on measured performance rather than architectural complexity.

**Tech:** `Python` `FastAPI` `LangChain` `Gemini` `BGE` `PyTorch` `Pinecone` `PostgreSQL` `Supabase` `SQLAlchemy` `Tailwind CSS`

---

### 🐦 Bird Sound Classifier — Species Monitoring

A deep learning system that identifies **30 bird species** from audio recordings using log-mel spectrograms and a CNN.

The project implements a complete ML pipeline from dataset preparation and audio preprocessing to training, evaluation, checkpointing, and interactive inference.

**Results:**

* **69.8% Test Accuracy**
* **64.1% Test Macro F1**
* **1.1760 Test Loss**

**Key engineering features:**

* Recording-level train/validation/test splitting
* Overlapping audio clip generation
* Log-mel spectrogram preprocessing
* Custom CNN architecture
* Mixed-precision PyTorch training
* Label smoothing
* AdamW optimization
* Early stopping and checkpointing
* Confusion matrix and per-class evaluation
* CLI inference
* Gradio deployment

**Tech:** `Python` `PyTorch` `LibROSA` `Scikit-learn` `NumPy` `Pandas` `Gradio`

---

## 🧠 AI / Machine Learning

<p align="left">

<a href="https://pytorch.org/" target="_blank">
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/pytorch-colored.svg" alt="PyTorch" title="PyTorch" width="40" height="40"/>
</a>&nbsp;

<a href="https://huggingface.co/" target="_blank">
<img src="https://huggingface.co/datasets/huggingface/brand-assets/resolve/main/hf-logo.svg" alt="Hugging Face" title="Hugging Face" width="40" height="40"/>
</a>&nbsp;

<a href="https://scikit-learn.org/" target="_blank">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit-learn_logo_small.svg" alt="Scikit-learn" title="Scikit-learn" width="40" height="40"/>
</a>

</p>

**Machine Learning:**
Supervised Learning • Classification • Regression • SVM • Kernels • Naive Bayes • Decision Trees • Ensemble Methods • Cross Validation • Error Analysis

**Deep Learning:**
Neural Networks • CNNs • Backpropagation • Transfer Learning • Computer Vision • Audio Classification • PyTorch

---

## 🤖 Generative AI & Agentic AI

<p align="left">

<a href="https://www.langchain.com/" target="_blank">
<img src="https://avatars.githubusercontent.com/u/126733545?s=200&v=4" alt="LangChain" title="LangChain" width="40" height="40"/>
</a>&nbsp;

<a href="https://www.langchain.com/langgraph" target="_blank">
<img src="https://avatars.githubusercontent.com/u/126733545?s=200&v=4" alt="LangGraph" title="LangGraph" width="40" height="40"/>
</a>

</p>

* **LLM Applications**
* **Retrieval-Augmented Generation (RAG)**
* **Agentic AI**
* **LangChain**
* **LangGraph**
* **Model Context Protocol (MCP)**
* Tool Calling & Tool-Oriented Workflows
* Structured LLM Outputs
* Human-in-the-Loop Systems
* Prompt Engineering
* LLM Evaluation
* Retrieval Evaluation
* Guardrails & Deterministic AI Systems
* Multi-model fallback and LLM resilience

---

## 🔎 RAG & Information Retrieval

* Document ingestion pipelines
* Structure-aware document parsing
* Semantic chunking
* Dense vector retrieval
* Embeddings
* Vector databases
* Pinecone
* BM25
* Reciprocal Rank Fusion (RRF)
* Cross-Encoder reranking
* Retrieval benchmarking
* Grounded generation
* Source attribution

---

## ⚙️ Backend & AI Engineering

<p align="left">

<a href="https://fastapi.tiangolo.com/" target="_blank">
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/fastapi-colored.svg" alt="FastAPI" title="FastAPI" width="40" height="40"/>
</a>&nbsp;

<a href="https://www.docker.com/" target="_blank">
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/docker-colored.svg" alt="Docker" title="Docker" width="40" height="40"/>
</a>

</p>

* FastAPI
* REST APIs
* Async Python
* Pydantic
* SQLAlchemy
* PostgreSQL
* SQLite
* API design
* Background processing
* Model serving
* Evaluation pipelines
* Testing with pytest
* Production-oriented application architecture

---

## 🗄️ Databases & Infrastructure

<p align="left">

<a href="https://www.postgresql.org/" target="_blank">
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/postgresql-colored.svg" alt="PostgreSQL" title="PostgreSQL" width="40" height="40"/>
</a>&nbsp;

<a href="https://www.docker.com/" target="_blank">
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/docker-colored.svg" alt="Docker" title="Docker" width="40" height="40"/>
</a>

</p>

**Databases:** PostgreSQL • SQLite • Pinecone *(Vector DB)*

**Cloud / Infrastructure:** Supabase • Neon • Docker • Vercel

---

## 💻 Languages

<p align="left">

<a href="https://www.python.org/" target="_blank">
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" alt="Python" title="Python" width="40" height="40"/>
</a>&nbsp;

<a href="https://isocpp.org/" target="_blank">
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cplusplus-colored.svg" alt="C++" title="C++" width="40" height="40"/>
</a>&nbsp;

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank">
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" alt="JavaScript" title="JavaScript" width="40" height="40"/>
</a>

</p>

**Python • C++ • JavaScript**

---

## 🛠️ Tools & Libraries

**AI / ML:** PyTorch • Scikit-learn • Hugging Face • LibROSA • NumPy • Pandas

**GenAI:** LangChain • LangGraph • MCP • Gemini • Groq

**Backend:** FastAPI • Uvicorn • Pydantic • SQLAlchemy • Alembic

**Databases:** PostgreSQL • SQLite • Pinecone

**Storage & Cloud:** Supabase • Neon • Vercel

**Testing & Development:** pytest • Git • GitHub • Docker

---

## 📊 What I Build

```text
                    AI / ML ENGINEERING
                           │
          ┌────────────────┼────────────────┐
          │                │                │
    Deep Learning         RAG          Agentic AI
          │                │                │
      PyTorch         Retrieval       LangGraph
          │           Embeddings          │
        CNNs          Pinecone            MCP
          │                │               │
    Computer Vision   Grounding       Tool Calling
          │                │               │
       Audio ML       Evaluation          HITL
          │                │               │
          └────────────────┼────────────────┘
                           │
                     Production APIs
                           │
                       FastAPI
                           │
                 PostgreSQL / Cloud
```

My focus is building systems where **models are only one part of the solution** — combining machine learning with retrieval, backend engineering, evaluation, reliability, and real-world constraints.

---

## 📈 Currently Exploring

* Advanced RAG architectures
* Agent evaluation
* LLM evaluation and observability
* Production LLM systems
* AI system reliability
* Model serving and deployment
* Multimodal AI
* Research paper implementation

---

## 🌐 Connect With Me

<p align="left">

<a href="https://github.com/Tautik05" target="_blank">
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="36" height="36" alt="GitHub" title="GitHub"/>
</a>&nbsp;

<a href="https://x.com/roy_tautik" target="_blank">
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/twitter.svg" width="36" height="36" alt="X" title="X"/>
</a>&nbsp;

<a href="https://www.linkedin.com/in/tautik-sinha-roy-88908128a/" target="_blank">
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" width="36" height="36" alt="LinkedIn" title="LinkedIn"/>
</a>

</p>

---

## 📊 GitHub Stats

<p align="left">
<a href="https://github.com/Tautik05">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Tautik05&stroke=ffffff&background=1c1917&ring=f97316&fire=f97316&currStreakNum=ffffff&currStreakLabel=f97316&sideNums=ffffff&sideLabels=ffffff&dates=ffffff&hide_border=true" />
</a>
</p>

---

### Building AI systems that move beyond notebooks — from models to production.
