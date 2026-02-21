# 🤖 RAG Chatbot

A **Retrieval-Augmented Generation (RAG) Chatbot** that combines fast vector search with a powerful large language model to generate accurate, context-aware responses.

---

## 📌 Project Overview

This chatbot enhances response quality by retrieving relevant documents before generating answers. It uses semantic search to find the most relevant information and then feeds it into a large language model for response generation.

---

## ⚙️ Tech Stack & Components

### 🔎 Embedding Model

**mixedbread-ai/mxbai-embed-large-v1**
Transforms text into high-dimensional vector embeddings for semantic similarity search.

### 📚 Dataset

**KarthikaRajagopal/wikipedia-2**
A curated Wikipedia-based dataset used as the knowledge source for retrieval.

### ⚡ Vector Search (FAISS)

FAISS enables efficient similarity search across large volumes of embedded documents, ensuring fast and relevant retrieval.

### 🧠 Language Model

**Meta-Llama-3-8B-Instruct**
Generates coherent and context-aware responses using the retrieved information.

---

## 🏃 Running Locally

Follow these steps to run the chatbot on your machine:

```bash
git clone https://github.com/KarthikaRajagopal44/RAG-Chatbot.git
cd RAG_Chatbot
pip install -r requirements.txt
```

After installing dependencies, start the application as described in the project files.
