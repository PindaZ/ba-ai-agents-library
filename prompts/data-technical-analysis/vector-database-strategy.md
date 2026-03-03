# Vector Database Strategy

**Role:** AI Solution Architect / AI BA
**Objective:** Plan the storage, indexing, and search capabilities for high-dimensional vector data in a RAG system.

## Prompt Template
"Act as a Database Architect specializing in Vector Databases (e.g., Pinecone, Weaviate, Milvus). 

**Develop a strategy for our Vector DB including:**
1. **Index Type:** (e.g., HNSW vs. IVF-Flat). What is the trade-off between search speed and recall accuracy for our use case?
2. **Dimensionality:** Based on our chosen embedding model, what is the required vector size?
3. **Multi-Tenancy:** How should we separate data between different users or clients (e.g., 'Metadata filtering' or 'Namespace separation')?
4. **Backup & Persistence:** How will we handle data durability and disaster recovery?
5. **Scaling:** At what point (number of vectors) will we need to scale horizontally?

**Knowledge Base Context:**
[INSERT CONTEXT HERE]"
