# RAG Chatbot (LangChain + Ollama)

This project implements a basic Retrieval-Augmented Generation (RAG) chatbot that answers user queries using a custom dataset.

---

## Features

- Accepts user questions  
- Retrieves relevant data using embeddings  
- Generates answers using a language model  
- Runs locally using Ollama  

---

## How It Works

1. Load data from a file (e.g., CSV)  
2. Convert data into embeddings  
3. Store embeddings in a vector database  
4. For each query:
   - Retrieve relevant documents  
   - Pass them to the model  
   - Generate a response  

---

## Project Structure

- `main.py` – chatbot loop and interaction  
- `vector.py` – embedding and vector database setup  
- `data.csv` – input dataset  

---

## Installation

```bash
pip install langchain langchain-ollama langchain-chroma pandas

