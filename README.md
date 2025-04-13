# 📄 DocuQuery AI — Intelligent Document Conversational System

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python)
![LangChain](https://img.shields.io/badge/LangChain-Enabled-yellowgreen?style=flat)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o--mini-brightgreen?style=flat)
![Pinecone](https://img.shields.io/badge/Pinecone-VectorDB-blueviolet?style=flat)

## 🔍 Overview

**DocuQuery AI** is an advanced document intelligence system that enables users to **chat with PDFs** using natural language. Powered by **LangChain**, **GPT-4o-mini**, and **Pinecone**, it transforms static documents into dynamic, conversational knowledge sources.

---

## 🚀 Features

- 📄 Load and process PDF documents
- ✂️ Chunk documents into smaller, semantically meaningful text segments
- 🧠 Generate vector embeddings with `OpenAI Embeddings`
- 📦 Store embeddings in `Pinecone Vector Database` (Total: **58 embeddings** generated)
- 🧭 Use `cosine similarity` for efficient semantic retrieval
- 💬 Respond to natural language queries using `GPT-4o-mini` via LangChain
- ⚡ Fast, accurate, and highly scalable for various document types

---

## ⚙️ How It Works

```mermaid
graph TD
    A[Load PDF] --> B[Split into Chunks]
    B --> C[Generate Embeddings with OpenAI]
    C --> D[Store in Pinecone Vector DB]
    E[User Query] --> F[Cosine Similarity Search]
    F --> G[Retrieve Relevant Chunks]
    G --> H[LLM Response using GPT-4o-mini]
