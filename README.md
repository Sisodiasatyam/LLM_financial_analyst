
# LLM Financial Analyst (Fine-Tuned LLaMA, RAG)  
LLM-Powered Financial Q&A System with SEC Data Retrieval  

This project implements a financial analysis AI solution by fine-tuning **LLaMA-3-8B** with **LoRA adapters** on 10-K Q&A datasets, combined with a **RAG pipeline** that retrieves and utilizes real-time SEC filings. The system focuses on Sections 1A (Risk Factors) and 7 (Management's Discussion & Analysis), leveraging open-source embeddings (**BAAI/bge-large-en**) to provide precise answers to complex financial questions.  

By combining parameter-efficient large language model training with semantic search, this solution enables scalable and insightful analysis of SEC filings for enterprise use cases.

---

## Overview  

This project includes:  

- **Fine-tuning a LLaMA-3 model (`meta-llama/Meta-Llama-3-8B-Instruct`) using LoRA adapters** on 10-K Q&A data, supported by the Unsloth AI framework.  
- **A real-time SEC 10-K retrieval pipeline** powered by the SEC API.  
- **Local embeddings (BAAI/bge-large-en-v1.5)** for semantic search and contextual matching.  
- **In-memory vector store** for efficient contextual retrieval.  
- **RAG pipeline** that integrates context into LLM inference for accurate financial Q&A.  

The system answers financial queries using relevant context extracted from SEC 10-K reports.

---

## Features  

🦙 Parameter-efficient fine-tuning with LoRA adapters  
📈 Real-time SEC API integration for 10-K retrieval  
🔍 Semantic search using open-source embeddings  
💡 End-to-end RAG (Retrieval-Augmented Generation) pipeline  
