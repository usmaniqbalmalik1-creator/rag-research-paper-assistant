# RAG Research Paper Assistant

A Retrieval-Augmented Generation application for asking questions about research-paper content through a simple Streamlit interface.

## Features
- LLM-powered question answering or analysis
- Context-aware processing
- Streamlit interface
- Environment-based API configuration
- Clear project structure for extension

## Workflow
User Input -> Context / Schema -> LLM -> Validation or Retrieval -> Result

## Project Structure
```text
rag-research-paper-assistant/
├── app.py
├── requirements.txt
└── .env.example
```

## Quick Start
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
pip install -r requirements.txt
```

Configure the required variables in `.env` using `.env.example`, then run:

```bash
streamlit run app.py
```

## Portfolio Focus
**RAG • LLM Applications • Information Retrieval • Python • Streamlit**

> Never commit API keys, passwords, or private user/company data.