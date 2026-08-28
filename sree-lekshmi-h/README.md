# 📝 NotePilot – AI Notes Assistant

NotePilot is a **RAG-based AI study assistant** that lets students upload PDF notes and ask questions based on their content.

### ✨ Features

* 📄 Upload PDF notes
* 🔍 Semantic search with ChromaDB
* 🤖 AI answers using Groq
* 📝 Generate MCQs and summaries
* 📚 Show sources and page numbers

### 🛠️ Tech Stack

**Python • FastAPI • Streamlit • ChromaDB • Sentence Transformers • PyMuPDF • Groq**

### 🔄 RAG Pipeline

```text
PDF → Text Extraction → Chunking → Embeddings
→ ChromaDB → Retrieval → Groq → Answer
```

### 🚀 Run

```bash
pip install -r requirements.txt
```

Backend:

```bash
uvicorn main:app --reload
```

Frontend:

```bash
streamlit run app.py
```

### 🔑 Environment

Create `.env`:

```env
GROQ_API_KEY=your_api_key
```

> **NotePilot — Upload your notes. Ask questions. Study smarter.**
