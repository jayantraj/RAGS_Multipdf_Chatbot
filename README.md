**Question Answering RAG ChatBot**

This repository contains the code for a Question Answering (QA) Retrieval-Augmented Generation (RAG) ChatBot. 
The bot leverages Pinecone's Vector Database for efficient similarity search and retrieval and is deployed using Streamlit for an interactive user interface.

**Features**

Retrieval-Augmented Generation: Combines the strengths of information retrieval and natural language generation for accurate and contextually relevant answers.

Vector Database: Utilizes Pinecone's Vector Database to store and efficiently retrieve embeddings, enabling quick responses to user queries.

Streamlit Deployment: The bot is deployed using Streamlit, providing a user-friendly interface for interaction.

**Prerequisites**

Python 3.7 or higher

Streamlit

Pinecone

Hugging Face Transformers (optional, for custom models)


**Usage**

Once the application is running, you can access the chat interface in your web browser. 
Enter your questions, and the bot will provide answers based on the stored knowledge base.

**Customization**

Adding Your Own Data

To customize the bot with your own data, you can:

Preprocess your documents and generate embeddings.
Index the embeddings in the Pinecone vector database.

**Modifying the Model**

You can replace the underlying model with any transformer model from the Hugging Face library. 

Update the model loading and inference code in the app.py file as needed.
