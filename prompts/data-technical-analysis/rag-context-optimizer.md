# RAG Context Optimizer

**Role:** AI Solution Architect / AI BA
**Objective:** Design the optimal strategy for "chunking," "retrieving," and "ranking" context for RAG (Retrieval-Augmented Generation) systems.

## Prompt Template
"Act as a RAG System Optimizer. I am building a knowledge base for [USE CASE]. Help me design the context retrieval strategy.

**Provide recommendations for:**
1. **Chunking Strategy:** (e.g., Fixed-size vs. Semantic-based chunking. What is the ideal character/token count per chunk?).
2. **Embedding Model:** Which embedding model is best suited for this type of data (e.g., text-embedding-3-small, Ada-002, or specialized industry models)?
3. **Retrieval Method:** Suggest a hybrid approach (e.g., Keyword Search + Semantic Vector Search).
4. **Context Ranking (Reranking):** Do we need a 'Reranker' model (e.g., Cohere Rerank) to filter the top K results?
5. **Metadata Tagging:** What metadata should be stored alongside chunks to improve retrieval accuracy (e.g., 'Author,' 'Date,' 'Topic')?

**Knowledge Base Description:**
[INSERT KB DESCRIPTION HERE]"
