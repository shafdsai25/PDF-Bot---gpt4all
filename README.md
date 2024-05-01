# PDF Bot - GPT-4 All

PDF Bot is a Streamlit-based application that allows users to upload PDFs, ask questions, and receive responses based on the content of the uploaded PDFs. This project leverages Llama-based large language models and other machine learning tools to extract insights from PDFs.

## Features
- Extracts text from PDFs using PyPDF2.
- Splits large sections of text into manageable chunks for efficient processing.
- Generates embeddings using sentence-transformers for similarity searches.
- Answers user questions in real-time using LangChain's question-answering capabilities.
- Provides a user-friendly Streamlit interface for PDF uploads and query responses.

## Usage
To use this application, follow these steps:
1. Upload your PDF document.
2. Ask a question about the content.
3. Receive an answer based on the extracted text.

## Installation
To set up this project, you need Python and the following dependencies:
- `streamlit`
- `PyPDF2`
- `langchain`
- `langchain_community`
- `sentence-transformers`
- `qdrant-client`
- `llama-cpp-python`

After installing Python, clone the repository and install the dependencies:
```bash
git clone https://github.com/shafdsai25/PDF-Bot---gpt4all.git
cd PDF-Bot---gpt4all
pip install -r requirements.txt
