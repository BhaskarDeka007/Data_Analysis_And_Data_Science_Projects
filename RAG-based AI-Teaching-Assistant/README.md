# RAG-based AI Teaching Assistant

[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)

## Overview
This project is an AI-powered teaching assistant built using **Retrieval-Augmented Generation (RAG)**.  
It converts lecture videos and course materials into a **searchable knowledge base** and provides **context-aware answers** for Data Science topics, simulating a real teaching assistant.

## Features
- Transcribes lecture videos using **Whisper**.  
- Breaks content into chunks and manages **metadata** for structured storage.  
- Generates **embeddings** for each chunk and performs **vector search** to retrieve relevant content.  
- Uses **custom prompts** for accurate LLM responses.  
- Automates the conversion of lectures into a **searchable knowledge base** for fast query answering.

## Tech Stack
- **Python**  
- **Whisper** – for video/audio transcription  
- **Pandas** – for embeddings and data management  
- **Vector Search / FAISS** – for retrieval  
- **LLM** – for natural language responses  

## Installation
```bash
git clone https://github.com/your-username/rag-teaching-assistant.git
cd rag-teaching-assistant
pip install -r requirements.txt
