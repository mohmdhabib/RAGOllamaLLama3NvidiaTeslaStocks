RAG App: NVIDIA & Tesla Stocks Querying
This notebook provides an on-the-go Retrieval-Augmented Generation (RAG) pipeline for querying real-time information about NVIDIA and Tesla stocks. The application uses embedded documents stored in ChromaDB, retrieved with LangChain, and queried using the Llama-3.1-8b model.

Features
Embedding: Stock information about NVIDIA and Tesla is embedded using the nomic-embed-text model.
Storage: Embedded data is stored and managed using ChromaDB, a fast and scalable vector database.
Retrieval: The embedded stock data is retrieved using LangChain, enabling efficient similarity search and context-aware queries.
Query Generation: The final query is processed by the Llama-3.1-8b language model, providing comprehensive answers to user questions based on the retrieved context.
