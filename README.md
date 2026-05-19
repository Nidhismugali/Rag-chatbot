# Retrieval-Augmented Generation (RAG) Chatbot

This project implements a simple Retrieval-Augmented Generation (RAG) based chatbot using LangChain, HuggingFace embeddings, ChromaDB, and Transformers.

The chatbot answers user queries based only on the provided document content.

---

## Features

- Document loading and text processing
- Text chunking using LangChain
- Embedding generation using Sentence Transformers
- Vector database creation with ChromaDB
- Question-answering using HuggingFace FLAN-T5 model
- Interactive chatbot interface

---

## Technologies Used

- Python
- LangChain
- ChromaDB
- HuggingFace Transformers
- Sentence Transformers
- Google Colab

---

## Project Workflow

1. Load text document
2. Split document into chunks
3. Generate embeddings
4. Store embeddings in vector database
5. Retrieve relevant context
6. Generate answer using LLM

---

## Installation

Install the required libraries:

```python
pip install langchain
pip install langchain-community
pip install chromadb
pip install sentence-transformers
pip install transformers
```

---

## Run the Project

Open the notebook in Google Colab or Jupyter Notebook and run all cells sequentially.

---

## Example Query

```text
What is the attendance requirement?
```

Example Output:

```text
Minimum attendance required is 75%.
```

---

## Future Improvements

- PDF and DOCX document support
- Streamlit web interface
- Memory-enabled chatbot
- Multi-document retrieval
- Better LLM integration

---

## Author

Nidhi S Mugali
