# GenAI PDF Chatbot

A chatbot that can answer questions about PDF documents using OpenAI's language models and embeddings. Built as part of the [Generative AI for Beginners](https://udemy.com/course/generative-ai-for-beginners-b/) course.

## Features

- Upload PDF documents
- Extract and process text content
- Generate embeddings using OpenAI
- Answer questions about the document content using GPT-3.5

## Technologies

- Streamlit - Web interface
- LangChain - LLM framework
- OpenAI - Language model and embeddings
- FAISS - Vector store
- PyPDF2 - PDF processing

## Setup

1. Set up your environment:

   ```bash
   uv venv
   ```

2. Install dependencies:

   ```bash
   uv pip install --requirements requirements.txt
   ```

3. Set your OpenAI API key as an environment variable:

   ```bash
   export OPENAI_API_KEY='your-api-key-here'
   ```

## Running the Application

Start the Streamlit server:

   ```bash
   uv streamlit run chatbot.py
   ```

## Usage

1. Upload a PDF file using the sidebar
2. Ask questions about the document content
3. Get AI-generated responses based on the document context
