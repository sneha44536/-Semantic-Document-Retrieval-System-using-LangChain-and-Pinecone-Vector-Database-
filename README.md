# -Semantic-Document-Retrieval-System-using-LangChain-and-Pinecone-Vector-Database-
Built a semantic document retrieval system using LangChain and Pinecone. The system processes PDFs, converts text into embeddings, and retrieves relevant chunks using vector search.
# 📄 AI-Powered Document Retrieval System using LangChain & Pinecone

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=for-the-badge)
![Pinecone](https://img.shields.io/badge/Pinecone-1E90FF?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-Natural%20Language%20Processing-blue?style=for-the-badge)
![VectorDB](https://img.shields.io/badge/Vector%20Database-Semantic%20Search-green?style=for-the-badge)

---
# 📌 Project Overview

The **AI-Powered Document Retrieval System** is a Retrieval-Augmented Generation (RAG) based application that processes PDF documents, converts them into semantic embeddings, and stores them in a vector database (Pinecone) for efficient information retrieval.

The system allows users to query large documents and retrieve the most relevant sections using **semantic similarity search instead of keyword-based search**.

This project demonstrates how modern AI systems use **embeddings + vector databases + LLM pipelines** to build intelligent knowledge retrieval systems.

---

# 🚀 Problem Statement

Traditional document search systems face several limitations:

- Keyword-based search fails to understand meaning
- Large PDF documents are difficult to analyze manually
- No contextual understanding of queries
- Slow and inefficient information retrieval

👉 This project solves these issues by:
- Converting text into embeddings
- Storing embeddings in a vector database
- Performing semantic similarity search for accurate retrieval

---

# ⚙️ How the System Works

1. User uploads PDF documents  
2. Documents are loaded using `PyPDFDirectoryLoader`  
3. Text is split into chunks using `RecursiveCharacterTextSplitter`  
4. Each chunk is converted into embeddings using OpenAI Embeddings  
5. Embeddings are stored in Pinecone Vector Database  
6. User enters a query  
7. Query is converted into vector form  
8. Similar chunks are retrieved using cosine similarity search  
9. Relevant results are returned  

---

# 🧠 Why These Techniques Are Used

## 📌 LangChain Framework
Used to simplify building LLM-based applications.

**Why?**
- Prebuilt tools for RAG pipelines  
- Easy integration with LLMs and vector DBs  
- Reduces boilerplate code  

---

## 📌 RecursiveCharacterTextSplitter
Used for splitting large documents into smaller chunks.

**Why chunking is needed?**
- LLMs cannot process large documents directly  
- Improves retrieval accuracy  
- Maintains semantic meaning of text  

---

## 📌 OpenAI Embeddings
Used to convert text into vector representations.

**Why embeddings?**
- Captures semantic meaning of text  
- Enables similarity-based search  
- Works better than keyword matching  

---

## 📌 Pinecone Vector Database
Used for storing and retrieving embeddings.

**Why Pinecone?**
- Fast and scalable similarity search  
- Cloud-based managed vector database  
- Optimized for high-dimensional data  

---

## 📌 Cosine Similarity
Used to find similarity between query and documents.

**Why cosine similarity?**
- Measures semantic closeness between vectors  
- Works better than exact keyword matching  
- Provides accurate contextual retrieval  

---

# 📊 Output Features

- PDF document ingestion  
- Automatic text chunking  
- Embedding generation  
- Vector storage in Pinecone  
- Semantic search functionality  
- Context-based document retrieval  

---

# 📁 Project Structure
