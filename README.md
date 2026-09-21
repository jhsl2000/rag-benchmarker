# RAG Pipeline Benchmarker

A systematic evaluation framework for Retrieval-Augmented Generation (RAG) 
pipelines — comparing chunking strategies, embedding models, retrieval 
approaches, and measuring quality, latency and cost.

## What this benchmarks
- **Chunking:** Fixed-size, sentence-based, semantic, recursive
- **Embeddings:** OpenAI, HuggingFace sentence-transformers
- **Retrieval:** Similarity search, MMR, reranking
- **Evaluation:** RAGAS metrics + custom latency/cost tracking

## Status
🚧 In progress

## Tech Stack
Python · LangChain · ChromaDB · RAGAS · MLflow · Streamlit
