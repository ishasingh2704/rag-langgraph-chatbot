# 🚀 RAG LangGraph Chatbot

**Agentic Retrieval-Augmented Generation System using LangGraph & FAISS**

---

## 📌 Overview

This project implements an **Agentic RAG (Retrieval-Augmented Generation) chatbot** using **LangGraph** for orchestration and **FAISS** for efficient semantic retrieval.
The system intelligently retrieves relevant knowledge from a custom knowledge base and generates **context-aware, accurate responses** using Large Language Models.

Unlike basic chatbots, this project follows an **agent-based workflow**, enabling modular reasoning, retrieval, and response generation.

---

## 🧠 Key Features

* 🔗 **LangGraph-based Agentic Workflow**
* 📚 **FAISS Vector Store** for fast semantic search
* 🧩 **Custom Knowledge Base ingestion**
* 🧠 **Context-aware LLM responses**
* 🧱 Modular backend architecture
* 🌐 Frontend + Backend separation
* ⚡ Optimized for scalability and extensibility

---

## 🏗️ Architecture

```
User Query
   ↓
LangGraph Agent
   ↓
Retriever (FAISS Vector Store)
   ↓
Relevant Context from Knowledge Base
   ↓
LLM Response Generator
   ↓
Final Answer
```

---

## 🛠️ Tech Stack

**Core AI**

* LangGraph
* LangChain
* FAISS
* HuggingFace / LLM APIs

**Backend**

* Python
* FastAPI

**Frontend**

* HTML / CSS / JavaScript (or React, if applicable)

**Other Tools**

* Virtual Environment (venv)
* Git & GitHub

---

## 📂 Project Structure

```
rag-langgraph-chatbot/
│
├── backend/            # API & agent logic
├── frontend/           # UI layer
├── knowledge_base/     # Source documents
├── faiss_index/        # Vector embeddings
├── demo/               # Demo / test scripts
├── screenshots/        # Project visuals
├── pip_installs.txt    # Dependencies
├── .gitignore
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/ishasingh2704/rag-langgraph-chatbot.git
cd rag-langgraph-chatbot
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate:

* **Windows**

```bash
venv\Scripts\activate
```

* **Mac/Linux**

```bash
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r pip_installs.txt
```

---

### 4️⃣ Run Backend

```bash
cd backend
uvicorn main:app --reload
```

---

### 5️⃣ Access Application

```
http://localhost:8000
```

---

## 📊 Use Cases

* Enterprise knowledge assistants
* Internal documentation Q&A bots
* AI-powered customer support
* Research & academic assistants
* Domain-specific chatbots

---

## 🚀 What Makes This Project Stand Out

✅ Uses **LangGraph** instead of linear chains
✅ Implements **Agentic AI patterns**
✅ Demonstrates **real-world RAG architecture**
✅ Scalable and production-aligned design
✅ Strong relevance for **AI/ML & Backend roles**

---

## 🎯 Skills Demonstrated

* Retrieval-Augmented Generation (RAG)
* Agent-based system design
* Vector databases (FAISS)
* LLM orchestration
* Backend API development
* System architecture & modular design

---

## 🔮 Future Improvements

* Multi-agent collaboration
* Streaming responses
* Authentication & user sessions
* Cloud deployment (AWS/GCP)
* Observability & logging

---

## 👩‍💻 Author

**Isha Singh**
Computer Science Undergraduate
Interested in **Agentic AI, Backend Systems & Intelligent Applications**

---

## ⭐ If you find this useful

Give the repo a ⭐ — it helps others discover it!

