# Winter Projects 2025/26

A central hub for all projects built during **Winter 2025**. Each project explores a high‑impact domain - Agentic AI, backend systems, embedded ML, optimizations, and scalable architecture - packaged cleanly so reviewers, recruiters, and collaborators can navigate effortlessly.

This repository acts as a structured master folder that **redirects users to individual project repositories** while maintaining a consistent layout and standardized documentation.

## Featured Projects

### 1. Agentic AI Memory Systems

This project demonstrates two fundamental memory systems for AI agents:

- Short-Term Memory (STM): Maintains conversation context within a session using LangGraph's checkpoint system
- Long-Term Memory (LTM): Stores and retrieves information across sessions using FAISS vector database

**See full repository:**
[*Agentic AI Memory Systems*](https://github.com/JashT14/AI-Memory-Systems)

### 2. Java Embedded ML

This project focuses on embedding machine-learning models directly inside Java applications:

- Zero-overhead integration of ML into legacy Java monoliths
- Inference inside the same JVM (no microservices, no external servers)
- ONNX runtime + DJL for loading and running models
- Endpoints demonstrating model inference (e.g., iris classification)
- Architecture designed for edge devices and constrained enterprise environments


**See full repository:**
[*Java Embedded ML*](https://github.com/JashT14/Java-Embedded-ML)

### 3. KnowledgeVault — Local Notes App (with RAG Implementation)

A privacy-focused, on-device knowledge system that converts your personal notes into a searchable, intelligent knowledge base using Retrieval-Augmented Generation (RAG). Designed as a completely offline alternative to cloud-based AI note systems.

- Local-first architecture with zero external API dependencies  
- Notes → chunking → embeddings → vector store pipeline  
- RAG retrieval to answer queries directly from your stored notes  
- Clean interface for adding, editing, and managing notes  
- Supports quantized local LLM inference  
- Ideal for personal assistants, study workflows, and offline knowledge engines  

**See full repository:**  
[**KnowledgeVault**](https://github.com/JashT14/KnowledgeVault)

### 4. VectorVault — Offline Semantic Search Engine (C + WebAssembly)

**VectorVault** is a low-level, from-first-principles implementation of a semantic search engine, built entirely in **C** and compiled to **WebAssembly (WASM)**. The project explores how modern semantic search concepts—embeddings, vector similarity, and ranking - can be implemented **without Python, ML frameworks, or cloud services**.

It is designed as a systems-level learning project that prioritizes **control, performance, and architectural clarity** over abstraction.

* Implements semantic search using **GloVe word embeddings**
* End-to-end pipeline: text ingestion → vectorization → similarity computation
* Cosine similarity implemented manually in C
* Fully offline execution model
* Compiled to WebAssembly for browser-level portability
* Demonstrates how ML primitives work beneath high-level libraries
* Emphasizes memory layout, numerical computation, and algorithmic efficiency

This project serves as a **ground-truth reference** for understanding how embedding-based retrieval systems function internally, making it especially relevant for systems engineers, ML infra learners, and anyone interested in stripping AI systems down to their mechanical core.

**See full repository:**
[**VectorVault**](https://github.com/JashT14/VectorVault)

