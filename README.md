🧠 Vector Database with Pinecone + LangChain

This project demonstrates how to build a semantic search pipeline using Pinecone, LangChain, and HuggingFace embeddings.
It processes and chunks documents, generates embeddings, and stores them in a vector database for efficient similarity-based retrieval.

🚀 Features

📄 Reads and processes documents (PDF, text, etc.)

✂️ Splits text into meaningful chunks for embedding

🧬 Generates embeddings using open-source models (e.g., MiniLM)

🗃️ Stores and manages vectors in Pinecone

🔍 Performs semantic search queries over the vector store

🔐 Loads API keys securely via environment variables

🧩 Tech Stack
Component	Description
LangChain	For document loading, chunking, and vector store management
Pinecone	Serverless vector database for high-speed similarity search
Sentence Transformers	To create semantic embeddings (all-MiniLM-L6-v2)
Python	Core programming language
.env	Securely stores API keys
