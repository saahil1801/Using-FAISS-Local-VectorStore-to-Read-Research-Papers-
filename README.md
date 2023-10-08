# Using-FAISS-Local-VectorStore-to-Read-Research-Papers-

This Python script demonstrates how to use the LangChain and FAISS library along with OpenAI to perform document processing tasks. In this example, we'll load and process a PDF document using LangChain, generate embeddings using OpenAI, and perform retrieval-based question-answering.

## Getting Started

To run the script, you'll need to have Python and the required libraries installed. You'll also need an OpenAI API key.

### Prerequisites

Before running the script, make sure you have the following prerequisites installed:

- Python (3.x recommended)
- LangChain library (Install using `pip install langchain`)
- OpenAI Python library (Install using `pip install openai`)

### Set Your OpenAI API Key

You need to set your OpenAI API key as an environment variable before running the script. Replace `"YOUR_API_KEY"` with your actual API key.

## Usage
The script performs the following steps:

Load a PDF document using LangChain's PyPDFLoader.
Split the document into smaller text chunks.
Generate embeddings for the text chunks using OpenAI.
Create a vector store using FAISS for efficient similarity search.
Save and load the vector store locally.
Perform retrieval-based question-answering using LangChain's RetrievalQA.
You can customize the script for your specific use case and questions.

## About FAISS (Facebook AI Similarity Search)
FAISS is a library developed by Facebook AI Research for efficient similarity search and clustering of large datasets. It provides GPU-accelerated implementations of various similarity search algorithms, making it well-suited for tasks like content-based search, recommendation systems, and more.

In this script, we utilize FAISS to create a vector store, allowing us to perform similarity-based queries on the document embeddings generated by OpenAI.

## Acknowledgments
LangChain: https://github.com/langchain
OpenAI: https://openai.com
FAISS: https://github.com/facebookresearch/faiss
