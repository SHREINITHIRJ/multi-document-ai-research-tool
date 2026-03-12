# Multi-Document AI Research Tool

## Overview
This project is a **Generative AI Research Assistant** built using a **Retrieval-Augmented Generation (RAG)** pipeline.  
It allows users to upload multiple PDF documents and ask questions. The system retrieves relevant information from the documents and generates answers using a Large Language Model.

---

## Features
- Question answering from multiple PDF documents
- Semantic search using vector embeddings
- Context-aware responses using an LLM
- Retrieval-Augmented Generation (RAG) pipeline

---

## Tech Stack
- Python
- LangChain
- HuggingFace Transformers
- SentenceTransformers
- ChromaDB
- Google Colab

---

## Architecture

User Question  
↓  
Convert question to embedding  
↓  
Search similar document chunks in vector database  
↓  
Retrieve relevant context  
↓  
Send context + query to LLM  
↓  
Generate answer  

---

## Project Workflow
1. Load multiple PDF documents  
2. Split documents into smaller text chunks  
3. Generate embeddings using Sentence Transformers  
4. Store embeddings in Chroma vector database  
5. Retrieve relevant document chunks using similarity search  
6. Generate answers using a HuggingFace LLM  

---

## Author
**Shrei Nithi RJ**

AI & Data Science Student  

 
LinkedIn: https://www.linkedin.com/in/shreinithirj
