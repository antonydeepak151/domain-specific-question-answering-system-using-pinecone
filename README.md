# 🧠 Domain-Specific Question Answering System using Pinecone & GPT

Welcome to an intelligent pipeline built to **extract insights from domain-specific documents** using the power of **LLMs + Vector Search**. This project leverages `Pinecone`, `OpenAI`, `LangChain`, and a `Gradio` interface to create an **interactive Q&A system**—no more scrolling through long PDFs or manuals.

## 🚀 What This Project Does

- ✅ Parses and cleans PDF documents
- 🧩 Chunks the text into semantically meaningful sections
- 🧠 Converts text into vector embeddings using `text-embedding-ada-002`
- 🔍 Stores and retrieves relevant chunks using **Pinecone Vector DB**
- 💬 Generates accurate responses to user queries via **OpenAI GPT-4**
- 🎛️ Offers a clean UI with `Gradio` for real-time interaction

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Core development language |
| **Pinecone** | Vector storage and semantic search |
| **OpenAI GPT-4** | Natural language understanding and generation |
| **LangChain** | Embedding + retrieval pipeline |
| **Gradio** | User interface for interaction |
| **PyMuPDF / pdfminer** | PDF text extraction |
| **NLTK** | Sentence tokenization |

---

## 🛠️ Features

- Upload any domain-specific document (legal, medical, academic, etc.)
- Ask natural language questions
- System returns highly relevant, context-aware answers
- Built for adaptability across industries

---

## 📦 Installation

Clone the repo and install dependencies:
