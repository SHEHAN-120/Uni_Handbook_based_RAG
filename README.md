# 🤖 RAG-Based Q\&A System for Science Faculty Handbook

## 📘 Overview

This project implements a **Retrieval-Augmented Generation (RAG)** system using the **OpenAI API** to answer user queries based on the content of the **Science Faculty Handbook**. The goal is to build a smart assistant that helps students and staff efficiently retrieve handbook-related information through natural language queries.

## ✨ Features

* Chunked and indexed handbook documents using vector embeddings
* Semantic search powered by OpenAI Embeddings
* Query answering using `gpt-4` with context retrieved from vector store
* User interface for asking and retrieving answers interactively

## 👨‍💻 Responsibilities

As the project developer, I was responsible for:

* Preprocessing and chunking the Science Faculty Handbook into manageable sections
* Creating vector embeddings using OpenAI’s Embeddings API
* Storing and querying embeddings using a vector store ( FAISS )
* Designing the RAG pipeline: document retrieval + answer generation
* Evaluating system performance with sample queries

## 🛠️ Techniques Used

* Document preprocessing: text extraction, cleaning, and chunking (fixed-size and overlap)
* Vector similarity search using FAISS
* Prompt engineering for context-aware question answering
* API integration (OpenAI, FAISS)


## ⚠️ Challenges Faced

* **Handling large documents**: Splitting content while preserving semantic coherence
* **Embedding quality**: Ensuring relevant context retrieval for complex queries
* **Answer hallucination**: Mitigating GPT-generated content not grounded in the handbook
* **Maintaining context relevance**: Optimizing chunk retrieval for accurate answers

