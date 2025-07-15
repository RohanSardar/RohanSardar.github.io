---
title: "ChatBot with RAG on PDF"
excerpt: "Takes one or more PDFs as input and then users can ask questions and it will answer based on those provided documents."
collection: portfolio
---

🔗 **Deployed Link:** [ChatBot with RAG on PDF](https://rag-pdf-bot.streamlit.app/)

## Tech Stack  
- Python  
- Streamlit  
- LangChain  
- GROQ  
- LangSmith  

## Features

### Document Ingestion
- Accepts one or more PDFs as input.
- Uses LangChain document loaders to split and clean the text.

### Embedding & Vector Store
- Generates embeddings using **Hugging Face models**.
- Stores and indexes them using **FAISS vector database** for efficient retrieval.

### RAG Pipeline
- Retrieves relevant document chunks based on user queries.
- Feeds the context into an **open-source LLM** for grounded answer generation.
- Powered by GROQ for fast and accurate response.

### User Interface
- Built with **Streamlit** for seamless UX.
- Users can upload PDFs and ask contextual questions.

### Observability & Monitoring
- Integrated with **LangSmith** for pipeline debugging and performance tracking.

## Workflow

1. **PDF Upload**  
   Users upload documents; text is extracted and preprocessed.

2. **Embedding & Storage**  
   Content is chunked and converted into embeddings using Hugging Face models, then stored in FAISS.

3. **Query Handling**  
   User queries are matched against the vector store to fetch the most relevant chunks.

4. **Answer Generation**  
   Retrieved context is passed into an LLM, and the generated answer is returned to the user.

## Highlights

- 📄 Multi-PDF ingestion  
- 🔍 RAG-powered contextual answers  
- ⚡ Fast inference using GROQ and FAISS  
- 📈 Observability via LangSmith
