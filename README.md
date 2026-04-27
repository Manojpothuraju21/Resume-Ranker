\# 📄 Chat with PDF using Gemini + RAG (Streamlit App)



\## 🚀 Overview

This project is a \*\*Streamlit-based AI application\*\* that allows users to upload multiple PDF files and interact with them using natural language queries. It uses \*\*Google Gemini (via LangChain)\*\* and \*\*Retrieval-Augmented Generation (RAG)\*\* to extract meaningful answers from documents.



The system supports multiple retrieval strategies like:

\- Basic Similarity Search

\- BM25 Search

\- Multi-Query Retrieval

\- Ensemble-style retrieval (extendable)



\---



\## 🧠 Key Features



\- 📂 Upload multiple PDF files

\- 🔎 Chunk and process PDF text automatically

\- 🧬 Store embeddings using \*\*Google Generative AI Embeddings\*\*

\- 📦 Vector storage using \*\*ChromaDB\*\*

\- 🤖 Chat with PDFs using \*\*Gemini 1.5 Flash\*\*

\- 🔍 Multiple retrieval strategies for better accuracy

\- 📊 Displays uploaded file metadata in UI

\- 🧾 Generates structured, context-based answers



\---



\## 🏗️ Architecture



1\. \*\*PDF Upload (Streamlit UI)\*\*

2\. \*\*Text Extraction (PyPDF2)\*\*

3\. \*\*Chunking + CSV Storage\*\*

4\. \*\*Embedding Generation (Google Embeddings)\*\*

5\. \*\*Vector DB Storage (ChromaDB)\*\*

6\. \*\*Retrieval (Multiple Methods)\*\*

7\. \*\*LLM Response Generation (Gemini 1.5 Flash)\*\*



\---



\## 🛠️ Tech Stack



\- Python 🐍

\- Streamlit

\- LangChain

\- Google Generative AI (Gemini 1.5 Flash)

\- ChromaDB (Vector Database)

\- PyPDF2

\- Pandas

\- dotenv



\---



\## 📁 Project Structure



```text

.

├── app.py                  # Main Streamlit application

├── data.csv               # Chunked document data

├── metadata.csv           # File metadata tracking

├── vector\_store/          # ChromaDB vector storage

├── .env                   # API key configuration

├── requirements.txt       # Dependencies

└── README.md

