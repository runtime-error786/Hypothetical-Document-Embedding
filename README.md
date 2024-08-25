# Hypothetical Document Embedding

## Project Description

This project leverages LangChain to process and retrieve relevant information from PDF documents. By embedding the contents of multiple PDFs, it enables efficient and contextually accurate question-answering. The system incorporates state-of-the-art models like Hugging Face for embedding and Ollama for generating responses. Additionally, it employs a Chroma vector store to facilitate the retrieval of document segments that are most relevant to user queries.

## Features

- **PDF Document Loading:** Automatically loads and processes PDF documents from a specified directory.
- **Text Chunking:** Utilizes RecursiveCharacterTextSplitter to divide large text into manageable chunks for better retrieval performance.
- **Document Embedding:** Uses Hugging Face embeddings to create vector representations of text chunks for efficient retrieval.
- **Vector Store Integration:** Stores and retrieves document embeddings using Chroma, allowing for quick and accurate search operations.
- **Contextual Question Answering:** Employs Ollama to generate responses based on retrieved document segments, providing answers in context.
- **Customizable Prompts:** Supports custom prompt templates to fine-tune the response generation according to specific requirements.
- **Dynamic Document Retrieval:** Automatically retrieves and provides contextually relevant document segments in response to queries.
