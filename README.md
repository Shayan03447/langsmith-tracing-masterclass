# LangSmith Tracing Masterclass 🚀

A **practice-focused repository** that explains **how LangSmith traces work step-by-step** — starting from simple sequential workflows, moving to **RAG pipelines**, and finally **AI Agents & multi-step graphs**.

This repo is designed for **beginners to intermediate AI engineers** who want to **visually understand, debug, and monitor LLM applications in production** using **LangSmith**.

---

## 🔍 What You Will Learn (Simple Words)

By working through this repository, you will clearly understand:

* How **LLM chains** are traced in LangSmith
* How **Sequential workflows** appear in LangSmith UI
* How **RAG systems** (Retriever → Prompt → LLM) are traced
* How **Agents** and **decision-based flows** are monitored
* How LangSmith helps in **debugging, evaluation, and observability**

This is not theory — **everything is implemented with code and verified in LangSmith dashboard**.

---

## 🧠 Course Flow (Learning Path)

### 1️⃣ Sequential Workflows Tracing

**Goal:** Understand basic tracing

* Simple LLM calls
* Prompt → LLM → Output
* Multi-step chains
* How each step appears in LangSmith trace tree

✅ Outcome: You can read and debug LangSmith traces confidently

---

### 2️⃣ RAG (Retrieval-Augmented Generation) Tracing

**Goal:** Learn how knowledge-based systems are traced

* Document loading (PDF / text)
* Text chunking & embeddings
* Vector database retrieval
* Prompt construction with retrieved context
* Final LLM response

🔎 LangSmith shows:

* Retriever calls
* Retrieved documents
* Prompt tokens & latency
* LLM response chain

✅ Outcome: You can debug **why a RAG system gave a wrong answer**

---

### 3️⃣ Agent Tracing (Reasoning & Decisions)

**Goal:** Understand complex AI agent behavior

* Tool calling
* Multi-step reasoning
* Conditional paths
* Agent memory & state

🔎 LangSmith shows:

* Agent thoughts
* Tool usage
* Step-by-step decisions
* Failures & retries

✅ Outcome: You can monitor and improve **production AI agents**

---

## 🛠️ Tech Stack Used

* **Python**
* **LangChain**
* **LangGraph** (for agent workflows)
* **LangSmith** (Tracing & Observability)
* **OpenAI / LLM APIs**
* **Vector Databases** (FAISS / Chroma – optional)

---

## 📂 Repository Structure

```
langsmith-masterclass/
│
├── sequential_workflows/
│   └── basic_tracing.py
│
├── rag_systems/
│   └── pdf_rag_tracing.py
│
├── agents/
│   └── agent_tracing.py
│
├── .env.example
├── requirements.txt
└── README.md
```

---

## ⚙️ How to Run This Project

1️⃣ Clone the repository

```bash
git clone <repo-url>
cd langsmith-masterclass
```

2️⃣ Create virtual environment

```bash
python -m venv myvenv
myvenv\Scripts\activate
```

3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

4️⃣ Setup environment variables

```env
LANGCHAIN_TRACING_V2=true
LANGCHAIN_API_KEY=your_langsmith_key
OPENAI_API_KEY=your_openai_key
```

5️⃣ Run any module and check traces on **LangSmith Dashboard**

---

## 📊 Why LangSmith Matters (For Clients)

* Detect **hidden bugs** in LLM workflows
* Understand **model behavior** clearly
* Improve **accuracy & latency**
* Monitor **production AI systems**
* Evaluate prompts, chains, and agents

👉 Essential for **enterprise-grade AI applications**

---

## 💼 Use Cases

* AI Chatbots
* PDF / Document Q&A Systems
* Customer Support Automation
* AI Agents & Assistants
* Research & Analytics Tools

---

## 🎯 Who Is This For?

* AI Engineers
* ML Engineers
* Freelancers (Upwork / Fiverr)
* Students learning LLMs
* Startups building AI products

---

## ⭐ Why This Repository Stands Out

✔ Beginner-friendly explanations
✔ Real tracing examples (not mock code)
✔ Covers **Chains → RAG → Agents** in one place
✔ Production-focused mindset

---

## 📬 Author

**Shayan**
AI Engineer | LLM Systems | LangChain | LangGraph | LangSmith

If you are a client, this repository shows my **hands-on expertise in building and monitoring real-world AI systems**.

---

✅ *If you understand this repo, you understand LangSmith tracing.*
