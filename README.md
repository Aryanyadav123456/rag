RAG Workflow Summary
Load documents (PDFs, websites).
Split into chunks for better retrieval.
Convert chunks into embeddings.
Store embeddings in ChromaDB.
Convert user query into an embedding.
Retrieve the most relevant chunks based on similarity.
Pass retrieved content to LLM for response generation.
