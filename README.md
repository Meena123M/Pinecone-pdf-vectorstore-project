# Pinecone-pdf-vectorstore-project
# PDF Semantic Search with Pinecone and Gemini LLM

This project demonstrates **semantic search on PDF documents** using **Gemini LLM** and **Pinecone vector database**. It loads PDFs, converts text into vector embeddings, stores them in Pinecone, and enables intelligent retrieval using LLM-powered queries.

---

## Features

- Load multiple PDFs from a directory using `PyPDFDirectoryLoader`
- Split text into manageable chunks with `RecursiveCharacterTextSplitter`
- Store vector embeddings in **Pinecone VectorStore**
- Query documents semantically using **Gemini LLM**

---

## Tech Stack

- **Python**  
- **PyPDFDirectoryLoader** – for PDF ingestion  
- **RecursiveCharacterTextSplitter** – for chunking large texts  
- **Pinecone VectorStore** – for vector database storage and retrieval  
- **Gemini LLM** – for semantic understanding and query response  

---

## Installation

# Create a virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

Contribution

Contributions are welcome! Please open an issue or submit a pull request for improvements.


