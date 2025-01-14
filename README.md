# Conversational RAG System

A sophisticated Retrieval-Augmented Generation (RAG) system that enables contextual conversation with document-based knowledge using LangChain and OpenAI.

## Features

- Context-aware question answering
- Conversation memory persistence
- Session-based chat management
- Advanced document retrieval
- Scalable architecture for handling multiple chat sessions

## Prerequisites

- Python 3.11.4
- Poetry for dependency management
- OpenAI API key
- LangChain API key

## Installation

1. Clone the repository:
```bash
git clone [repo-url]
cd [project-directory]
```

2. Set up Python environment:
```bash
pyenv local 3.11.4
poetry install
poetry shell
```

3. Create and configure .env file:
```
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_TRACING_V2=true
LANGCHAIN_ENDPOINT=https://api.smith.langchain.com
LANGCHAIN_API_KEY=your_langchain_api_key
LANGCHAIN_PROJECT=your_project_name
```

## Project Structure

```
project/
├── data/
│   └── be-good.txt         # Source document for RAG
├── notebooks/
│   └── conversational-rag.ipynb
├── src/
│   └── conversational-rag.py
├── .env.example
├── pyproject.toml
└── README.md
```

## Usage

### Jupyter Notebook
```bash
jupyter lab
# Navigate to notebooks/conversational-rag.ipynb
```

### Python Script
```bash
python src/conversational-rag.py
```
