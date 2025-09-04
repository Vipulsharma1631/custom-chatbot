A **document-aware chatbot** built with **LangChain**, **Hugging Face embeddings**,  
**Pinecone vector database**, and a **2-bit quantized LLaMA model** for efficient local inference.  
The chatbot supports custom knowledge ingestion, retrieval-augmented generation, and a web UI for interaction.
---

## 🚀 Tech Stack

- **Python** – Core language  
- **LangChain** – Orchestration framework for LLMs and retrieval  
- **Hugging Face Transformers** – Embedding models for vectorization  
- **Pinecone** – Vector database for semantic search  
- **LLaMA (2-bit quantized)** – Lightweight, efficient open-source LLM for answering queries  
- **Flask** – Backend web framework for serving the chatbot  
- **Jinja2 + HTML/CSS/JS** – Web interface (`templates/` + `static/`)  


---

## ✨ Features

- 🔗 **LangChain-powered conversation flow**  
- 📑 **Document ingestion & embedding** with Hugging Face models  
- 📦 **Pinecone integration** for scalable semantic search  
- 🦙 **Local inference with LLaMA (2-bit quantized)** for cost-efficient LLM usage  
- 🌐 **Flask web interface** for chatting in real time  
- ⚡ **Retrieval-Augmented Generation (RAG)** — combines embeddings + LLM output  
- 🧪 **Research scripts** for experimenting with custom models and pipelines  

## 📂 Project Structure

```bash
custom-chatbot/
├── app.py              # Main Flask application
├── requirement.txt     # Dependencies
├── setup.py            # Install script
├── store_index.py      # Builds & stores embeddings into Pinecone
├── template.py         # Template utilities
│
├── data/               # Knowledge base / documents
├── model/              # Quantized LLaMA model files
├── research/           # Experimental notebooks & scripts
├── src/                # Core source code (chains, utils, configs)
├── static/             # CSS, JS, frontend assets
└── templates/          # HTML templates for web interface
