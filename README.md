# 📄 RAG-Based PDF Chatbot Using Generative AI

## 📌 Project Overview

This project implements a Retrieval-Augmented Generation (RAG) based PDF chatbot using Python and Generative AI. It enables users to ask questions about PDF documents and receive relevant answers based on the document's content.

The application uses LangChain for document processing, Sentence Transformers for generating embeddings, FAISS for vector similarity search, and Hugging Face's FLAN-T5 model for answer generation.

## 🚀 Features

* PDF document text extraction
* Text chunking for efficient document processing
* Semantic search using vector embeddings
* FAISS vector database for similarity-based retrieval
* Context-aware answer generation using FLAN-T5
* Retrieval of the top three relevant text chunks
* Source-page identification for retrieved content
* Streamlit interface setup

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Generative AI:** Retrieval-Augmented Generation (RAG)
* **LLM:** Google FLAN-T5 Base
* **Framework:** LangChain
* **Embeddings:** Sentence Transformers
* **Vector Database:** FAISS
* **Document Processing:** PyPDFLoader
* **User Interface:** Streamlit

## ⚙️ How It Works

1. Load a PDF document and extract its text.
2. Split the extracted text into smaller chunks.
3. Convert the text chunks into vector embeddings.
4. Store the embeddings in a FAISS vector database.
5. Retrieve the three most relevant chunks for a user's question.
6. Pass the retrieved context and question to the FLAN-T5 model.
7. Generate an answer based on the retrieved information.
8. Identify the source pages to help users locate relevant content.

## 🎯 Project Objective

The objective is to demonstrate how Generative AI, semantic search, vector databases, and retrieval-based architectures can be combined to build a document question-answering system.

## 👨‍💻 Skills Demonstrated

Python Programming, Generative AI, RAG Architecture, LangChain, Prompt Engineering, Text Embeddings, Vector Search, FAISS, Hugging Face Transformers, and NLP.

