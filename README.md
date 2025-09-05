# 🚀 Conversational RAG Chatbot with PDF Support

A FastAPI-based backend that lets users upload PDFs and chat with their content using **Retrieval-Augmented Generation (RAG)**, **session-based memory**, and **vector search**.

Perfect for building AI assistants that answer questions from private documents — no frontend needed. Just REST APIs.

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

---

## 🌟 Features

✅ **Upload PDFs** and chat with their content  
✅ **Session-based memory**: follow-up questions work naturally  
✅ **Semantic search** via ChromaDB and OpenAI embeddings  
✅ **RAG pipeline** with history-aware rewriting and grounded answers  
✅ **Persistent vector storage** — no reprocessing on restart  
✅ **Clean, modular code** — easy to extend or learn from  

---

## 🛠️ Tech Stack

- **FastAPI** – High-performance backend
- **LangChain** – RAG, prompts, and chains
- **ChromaDB** – Vector database for document search
- **OpenAI Embeddings** – Semantic chunk embedding
- **Groq** – Fast LLM inference (Gemma2-9b)
- **PyPDFLoader** – PDF parsing
- **Docker & Docker Compose** – Containerization

---

## 🚀 Quick Start

### 1. Clone the repo
```bash
https://github.com/Adelakun1999/pdf-rag-api.git
cd pdf-rag-api
