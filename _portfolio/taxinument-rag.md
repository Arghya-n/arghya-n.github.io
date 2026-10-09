---
title: "Taxinument — RAG Financial Document Assistant"
excerpt: "Retrieval-Augmented Generation system for intelligent natural-language querying of financial and tax documents."
collection: portfolio
---

**Tech stack:** Python, FastAPI, LangChain, OpenAI LLMs, Qdrant (2025)

Built **Taxinument**, a Retrieval-Augmented Generation (RAG) system for intelligent querying of financial and tax documents, enabling natural language Q&A over large PDF corpora.

* Implemented the full data pipeline: PDF ingestion → text chunking → embedding generation → vector storage in Qdrant → semantic retrieval with re-ranking.
* Orchestrated multi-step LLM reasoning chains using LangChain (RetrievalQA, ConversationalRetrievalChain), achieving 90%+ retrieval accuracy on benchmark queries.
* Exposed the system as a production-grade REST API using FastAPI with async endpoints, Pydantic validation, and auto-generated Swagger/OpenAPI docs.
* Reduced query latency by 60% through caching and chunk optimization.
