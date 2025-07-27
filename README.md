# 🧠 RAG Pipeline for Intelligent Document Retrieval and Question Answering

This project implements a Retrieval-Augmented Generation (RAG) pipeline using **LangChain**, **FAISS**, and **Ollama** models to enable semantic search and intelligent question answering over diverse document types such as PDF, web articles, and plain text files.

---

## 🚀 Features

- 📄 Multi-source document ingestion (PDFs, web pages, .txt files)
- ✂️ Advanced text chunking using LangChain’s `RecursiveCharacterTextSplitter`
- 🔍 Vector-based semantic search with **FAISS**
- 🧠 LLM-powered answers using **Ollama**-backed embeddings and chat models
- 🛠️ Modular and extensible architecture for new data types

---


## 📦 Dependencies

- Python 3.10+
- [LangChain](https://www.langchain.com/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Ollama](https://ollama.com/)
- bs4, requests, dotenv

Install requirements:
```bash
pip install langchain faiss-cpu requests beautifulsoup4 python-dotenv
