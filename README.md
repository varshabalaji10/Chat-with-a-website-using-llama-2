# Chat with a Website Using LLaMA2

## Overview

This project enables the integration of an AI chat functionality into websites using the LLaMA2 model. It leverages two Jupyter notebooks: chat.ipynb and vector_store.ipynb, to handle chat interactions and data storage, respectively. The setup provides a seamless way to incorporate conversational AI into web services for enhanced user engagement.

## Requirements
Before starting, ensure you have the following:

Python 3.8 or higher.

Jupyter Notebook or JupyterLab installed.

Access to LLaMA2 model via Hugging Face or a compatible service.

A Pinecone account for vector data storage (used in vector_store.ipynb).

## Configuration

### Obtaining Pinecone API Key:
Sign up or log in to your Pinecone account.

Navigate to the API keys section and generate a new API key.

Store the key securely; you'll need to insert it into vector_store.ipynb.

### Obtaining Hugging Face Credentials:

Create or log in to your Hugging Face account.

Go to your account settings, find the Access Tokens section, and create a new token.

Securely store this token as it will be used in chat.ipynb to access the LLaMA2 model.
## Usage

Chat Notebook (chat.ipynb): Follow the instructions within the notebook to initialize the chat model and start handling chat requests from your website. Make sure to insert your Hugging Face credentials where indicated.

Vector Store Notebook (vector_store.ipynb): This notebook sets up the vector database using Pinecone. Enter your Pinecone API key as instructed to initialize the vector storage service.

## Troubleshooting

Pinecone Connection Issues: Ensure your API key is correct and that you have an active internet connection. If problems persist, consult the Pinecone documentation or support.

Hugging Face Model Access: Verify your token is correctly entered and that you have permissions to access the LLaMA2 model. Hugging Face's support can assist with access issues.

For more detailed instructions and guidance, refer to the comments within each notebook and the official documentation for Hugging Face and Pinecone's documentation.

