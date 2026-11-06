# VectorDB — Build a Vector Database from Scratch in C++

A C++ vector database implementing **HNSW, KD-Tree, and Brute Force** search algorithms with a web-based interface for exploring and benchmarking vector similarity search.

- **Algorithms:** HNSW (approximate nearest-neighbor), KD-Tree, and Brute Force search.
- **Distance Metrics:** Cosine Similarity, Euclidean Distance, and Manhattan Distance.
- **Visualization:** Interactive 2D PCA scatter plot for exploring semantic vector clusters.
- **Embeddings:** Generate real document embeddings locally using Ollama and `nomic-embed-text` (768D).
- **RAG Pipeline:** Retrieve relevant document chunks using HNSW and generate contextual answers with `llama3.2`.
- **Backend:** C++17, REST API, and `cpp-httplib`; **Frontend:** HTML, CSS, and JavaScript.
- **Features:** Vector search, document insertion/deletion, semantic retrieval, algorithm benchmarking, and AI-powered Q&A.
- **Requirements:** Windows, MSYS2 (G++), Git, Ollama, `nomic-embed-text`, and `llama3.2`.
- **Run:** `g++ -std=c++17 -O2 main.cpp -o db.exe -lws2_32` → `.\db.exe` → open `http://localhost:8080`.
- **Purpose:** An educational implementation demonstrating how vector databases and retrieval-augmented generation (RAG) work under the hood, inspired by systems such as Pinecone, Weaviate, and Chroma.