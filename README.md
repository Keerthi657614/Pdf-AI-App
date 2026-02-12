# 📘 SmartDocs AI – Intelligent PDF Q&A System (RAG-Based)

## 🚀 Overview

SmartDocs AI is a Retrieval-Augmented Generation (RAG) system that allows users to upload multiple PDF documents and ask intelligent, context-aware questions.

The system extracts text, cleans it, chunks it with overlap, generates embeddings, stores them in ChromaDB, performs similarity search, and generates grounded responses using OpenAI.

All answers are generated strictly from retrieved document context with proper source attribution.

---

## 🎯 Key Features

- 📂 Multi-PDF Upload
- 🧠 Intelligent Text Chunking (Token + Sentence Based)
- 🔎 Cosine Similarity Search
- 🗃️ Persistent ChromaDB Vector Storage
- 🧾 Context-Aware GPT Responses
- 📌 Source Attribution with Page Numbers
- 📊 Document Contribution Visualization
- 📄 Integrated PDF Viewer
- 💬 Session Management & Chat History
- 💾 Export Q&A (TXT / Markdown / PDF)
- ⚡ Performance Optimization & Caching
- 🛡️ Robust Error Handling
- 🧪 Unit & Integration Testing (pytest)

---
```
PDF Upload
↓
PDFProcessor
↓
TextCleaner
↓
TextChunker
↓
EmbeddingGenerator
↓
ChromaDB
↓
SearchEngine
↓
QAEngine
↓
React UI
```
---

## 🛠️ Tech Stack

**Backend**
- Python 3.8+
- OpenAI API
- ChromaDB
- PyMuPDF
- pdfplumber
- LangChain
- tiktoken
- python-dotenv

**Frontend**
- Streamlit

---

## ⚙️ Installation

### Clone Repository
```bash
git clone https://github.com/Keerthi657614/SmartDocs-AI.git
cd SmartDocs-AI
```
Create Virtual Environment
python -m venv venv
Activate:

Windows:
```bash
venv\Scripts\activate
```
MAC/Linux
``` bash
source venv/bin/activate

```
Install Dependencies
pip install -r requirements.txt
🔑 Environment Variables

Create .env file in root directory:
```
OPENAI_API_KEY=your_openai_api_key_here
```
▶️ Run Application
cd smartdocs-frontend
npm run dev


App will open at:
```
http://localhost:5173
```
👤 Author

Keerthi Mittapalli
AI & ML Student
## 🏗️ Architecture

