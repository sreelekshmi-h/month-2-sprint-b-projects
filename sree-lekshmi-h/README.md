# 📝 NotePilot – AI Notes Assistant

NotePilot is a **RAG-based AI study assistant** that lets students upload PDF notes and ask questions based on their content.
<img width="932" height="482" alt="image" src="https://github.com/user-attachments/assets/176419e9-9c2b-45d1-ade7-c133f8d4f75f" />
<img width="945" height="479" alt="Screenshot 2026-08-28 211747" src="https://github.com/user-attachments/assets/3f267484-245c-4c7f-84c0-ccba32e45fc8" />

<img width="941" height="455" alt="Screenshot 2026-08-28 211823" src="https://github.com/user-attachments/assets/693de7af-2bbc-4432-b7d7-a75f62015259" />
<img width="911" height="424" alt="Screenshot 2026-08-28 211808" src="https://github.com/user-attachments/assets/4dd34093-12cd-41af-aad2-0323e2ee6e51" />
<img width="930" height="479" alt="Screenshot 2026-08-28 211815" src="https://github.com/user-attachments/assets/f13c19b4-ac1a-4661-b11f-1ad7f2adef72" />



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
