📄 DocuQuery AI — Intelligent Document Conversational System
Tech Stack: LangChain • OpenAI GPT-4o-mini • Pinecone • OpenAI Embeddings • Python

🔍 Overview
DocuQuery AI is an intelligent, LLM-powered system that allows users to interact with PDF documents using natural language queries. Built using LangChain and GPT-4o-mini, the system transforms static documents into dynamic, searchable knowledge bases.

⚙️ Key Features
📄 Loads and preprocesses PDF documents

✂️ Chunks documents into smaller, meaningful text segments

🧠 Creates vector embeddings using OpenAI Embeddings

📦 Stores embeddings in a Pinecone vector database (total: 58 embeddings)

🧭 Uses cosine similarity for fast and accurate semantic search

💬 Integrates with GPT-4o-mini via LangChain to generate intelligent, context-aware answers

🚀 How It Works
Document Upload: Load any PDF file for processing

Text Chunking: Divide the document into manageable text chunks

Embedding Generation: Create embeddings with OpenAI's embedding model

Vector Storage: Store vectors in Pinecone with unique IDs

Semantic Search: Perform cosine similarity search on user queries

Conversational Answering: Return relevant answers using GPT-4o-mini via LangChain

📌 Use Cases
Legal Document Search

Academic Paper Summaries

Technical Manual Exploration

Business Reports Q&A
