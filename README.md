# Tibyan.AI

## Project Overview
This project demonstrates the application of **Retrieval-Augmented Generation (RAG)** techniques with **Large Language Models (LLMs)** to religious texts — specifically, **Hadith** and their explanations.  

The workflow integrates **LangChain**, **ChromaDB**, and **OpenAI embeddings** to build a retriever system where users can query Hadith content, and the model responds with contextually grounded answers.

The project highlights:
- How to **structure and preprocess** a Hadith dataset from Excel format.  
- How to **combine Hadith with their explanations** into a retrieval-friendly format.  
- How to **embed and index** the dataset using OpenAI embeddings.  
- How to **query via RAG pipelines** for accurate, context-aware answers.

---

## Research Motivation
Traditional QA systems struggle when applied to classical texts (like Hadith) because they require both **semantic understanding** and **contextual grounding**.  
By leveraging RAG:
- We ensure the LLM retrieves **relevant passages** before answering.  
- This reduces hallucinations and increases **factual grounding**.  
- It opens doors for applications in **digital humanities**, **Islamic studies**, and **AI-assisted education**.

---

## Tech Stack
- **Python 3.10+**
- **LangChain** (retrieval pipeline)  
- **ChromaDB** (vector database)  
- **OpenAI embeddings** + `ChatOpenAI` (LLM interface)  
- **Pandas** (dataset handling)  
- **BeautifulSoup** & **Unstructured** (document parsing utilities)  

---

