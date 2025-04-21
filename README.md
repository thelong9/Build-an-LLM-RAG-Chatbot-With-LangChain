# Build an LLM RAG Chatbot With LangChain

# Medical Chatbot with Gemini 1.5 Pro and LangChain

[![LangChain](https://img.shields.io/badge/LangChain-1.0.0-blue)](https://python.langchain.com/)
[![Google Generative AI](https://img.shields.io/badge/Gemini-1.5--pro-yellow)](https://ai.google.dev/)

A Retrieval-Augmented Generation (RAG) medical chatbot that provides accurate health information using Gemini 1.5 Pro as the LLM backbone. This project is adapted from the [RealPython RAG Chatbot tutorial](https://realpython.com/build-llm-rag-chatbot-with-langchain/), replacing OpenAI's GPT with Google's Gemini model.

## Features

- **Medical Q&A System**: Answers health-related questions with context-aware responses
- **RAG Architecture**: Combines retrieval from medical documents with generative AI
- **Gemini 1.5 Pro Integration**: Leverages Google's latest LLM for medical conversations
- **Vector Database**: Uses Neo4j for efficient document retrieval

## Prerequisites

- Python 3.8+
- Google API key (for Gemini access)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/medical-chatbot-gemini.git
   cd medical-chatbot-gemini

2. Install dependencies


```bash
pip install -r requirements.txt
```

3. Add your API key

```bash
GOOGLE_API_KEY = "YOUR API KEY"  # Thay bằng API key của bạn
```

4. Run Docker & Open Local Web

```python
docker-compose up --build
```




