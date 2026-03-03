# Vector DB Indexer Skill

**Category:** Data & Technical Analysis
**Goal:** Design the index structure, dimensionality, and search algorithm for a high-performance Vector Database.

## Prerequisites
- Volume of data to be indexed (e.g., 1 million chunks).
- Embedding model dimensions (e.g., 1536).

## Required Tools/Integrations
- `architecture_diagrammer`

## Execution Workflow
1. **Dimensionality Mapping:** Ensure the DB index dimensions match the chosen embedding model exactly.
2. **Algorithm Selection:** Choose between exact KNN (K-Nearest Neighbors) or approximate ANN (e.g., HNSW) based on the speed vs. recall requirement.
3. **Filtering Strategy:** Define the metadata fields that will be used for pre-filtering before the vector search (e.g., `department_id`, `date_range`).
4. **Multi-Tenancy Design:** Decide whether to use Namespaces or Metadata filtering to keep customer data separate.
5. **Documentation:** Write the creation script for the index.

## Expected Output
A technical configuration spec and the initial DDL/script to provision the Vector Database index.
