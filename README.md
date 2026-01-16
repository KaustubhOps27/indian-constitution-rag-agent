# indian-constitution-rag-agent
"Constitutional Sage"! This intelligent system processes the Constitution of India (2024 edition) to deliver precise, hallucination-free legal answers.
# Constitutional Sage - RAG Agent

*n8n-powered RAG agent delivering accurate answers from Constitution of India (2024 edition)*


## What It Does
Transforms Constitution PDF into intelligent Q&A system. 

## Two Pipelines

*📄 Document Pipeline*  
PDF Loader → Text Splitter → Google Embeddings → Vector Store  
Prepares constitution for semantic search

*🔍 Retrieval Pipeline*  
Retriever Agent → Router + AI Grader → AI Agent → Query Tool  
Finds + explains relevant constitutional sections

## Quick Start
Import n8n workflow JSON
Set-up your credentials
Upload Constitution PDF (2024)
Run manual trigger

# Author
Kaustubh Kishor Nikam
