# Pinecone-pdf-vectorstore-project

# 📄 PDF Semantic Search with Pinecone & Gemini LLM

**Author:** Meena M 👩‍💻

This project demonstrates **semantic search on PDF documents** using **Gemini LLM** and **Pinecone vector database**. It loads PDFs, converts text into vector embeddings, stores them in Pinecone, and enables intelligent retrieval using LLM-powered queries.

---

## 🚀 Features

- 📂 Load multiple PDFs from a directory using `PyPDFDirectoryLoader`
- ✂️ Split text into manageable chunks with `RecursiveCharacterTextSplitter`
- 🗄️ Store vector embeddings in **Pinecone VectorStore**
- 🤖 Query documents semantically using **Gemini LLM**

---

## 🛠 Tech Stack

- **Python**  
- **PyPDFDirectoryLoader** – for PDF ingestion  
- **RecursiveCharacterTextSplitter** – for chunking large texts  
- **Pinecone VectorStore** – for vector database storage and retrieval  
- **Gemini LLM** – for semantic understanding and query response  

---

## ⚡ Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/pdf-semantic-search-pinecone.git
cd pdf-semantic-search-pinecone

# Create a virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
