# 🤖 RAG PDF Chatbot with FRS/Design Document Generator

This project is a **Streamlit web application** that uses **RAG (Retrieval-Augmented Generation)** and **Ollama's LLM** (e.g., LLaMA3) to:

- 💬 Chat with Functional Requirement Specifications (FRS) and Design Documents (PDFs)
- 📄 Automatically generate structured FRS or Design documents based on user-provided project descriptions
- 📁 Export the generated documents as **.docx Word files**

---

## 📦 Features

- 🔍 Load and index multiple FRS and Design Documents (PDF)
- 🧠 RAG-based semantic search using LangChain and FAISS
- 💡 Project-specific FRS / Design Document generation using contextual examples
- 📄 Download Word document output with professional formatting
- 🎛️ Simple UI with Streamlit

---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure you have:

- Python 3.8+
- [Ollama](https://ollama.com/) installed and running with a model like `llama3`
- Required Python packages

### 📥 Installation

```bash
git clone https://github.com/your-username/rag-frs-generator.git
cd rag-frs-generator

# Install Python packages
pip install -r requirements.txt

## 📚 Required Directory Structure
```bash
rag-frs-generator/
├── pdfs/
│   ├── Sample_FRS.pdf
│   └── Sample_Design_Doc.pdf

## 🧠 Usage
### Run the Streamlit app:
```bash
streamlit run app.py
