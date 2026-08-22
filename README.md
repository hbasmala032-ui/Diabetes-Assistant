# Diabetes-Assistant
# 🧠 WHO Diabetes Assistant

<div align="center">

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Gradio](https://img.shields.io/badge/Gradio-6.0+-orange.svg)
![SentenceTransformers](https://img.shields.io/badge/SentenceTransformers-2.2+-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

</div>

---

## 📖 **About The Project**

**WHO Diabetes Assistant** is an intelligent question-answering system built on the **WHO Guideline for Diagnosis and Management of Type 2 Diabetes** (WHO/UCN/NCD/20.1). It uses advanced **Retrieval-Augmented Generation (RAG)** techniques to provide accurate answers with source citations directly from the official WHO document.

This project demonstrates how to:
- 📄 Extract and process PDF documents
- 🧠 Generate semantic embeddings using Sentence Transformers
- 🔍 Perform efficient similarity search with ChromaDB
- 🎨 Build a beautiful, interactive UI with Gradio

---

## 🎯 **Features**

| Feature | Description |
|---------|-------------|
| 📄 **PDF Processing** | Automatic extraction and cleaning of text from WHO guideline |
| 🧠 **Semantic Search** | Uses `all-MiniLM-L6-v2` model for high-quality embeddings |
| 📚 **Source Attribution** | Shows which section and page each answer comes from |
| 🎯 **Confidence Scoring** | Displays similarity scores for each retrieved chunk |
| 🌐 **Bilingual Support** | Works with both Arabic and English queries |
| 🎨 **Premium UI** | Modern glass-morphism design with gradient effects |
| 📊 **Performance Metrics** | Built-in evaluation with Precision@5, Faithfulness, and Citation Accuracy |

---

## 🛠️ **Tech Stack**

<div align="center">

| Technology | Purpose |
|------------|---------|
| **Python 3.9+** | Core programming language |
| **PyMuPDF (fitz)** | PDF text extraction |
| **Sentence-Transformers** | Embedding generation |
| **ChromaDB** | Vector database for similarity search |
| **Gradio 6.0** | Web interface |
| **Pandas** | Data analysis & benchmarking |
| **scikit-learn** | Similarity metrics |

</div>

---

## 🚀 **Quick Start**

### **1️⃣ Clone the Repository**

```bash
git clone https://github.com/Basmala Hisham/who-diabetes-assistant.git
cd who-diabetes-assistant
