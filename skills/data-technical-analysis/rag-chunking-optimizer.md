# RAG Chunking Optimizer Skill

**Category:** Data & Technical Analysis
**Goal:** Determine the optimal text chunking strategy to maximize the retrieval accuracy of a RAG system.

## Prerequisites
- Sample of the unstructured documents (e.g., PDFs, manuals).
- Chosen embedding model (e.g., text-embedding-3-small).

## Required Tools/Integrations
- `token_counter`
- `semantic_chunker`

## Execution Workflow
1. **Document Analysis:** Analyze the document structure (headings, paragraphs, bullet points).
2. **Strategy Evaluation:** Compare Fixed-Size Chunking (e.g., 500 tokens) vs. Semantic Chunking (splitting by markdown headers).
3. **Overlap Calculation:** Determine the ideal token overlap (e.g., 10%) to prevent cutting off context midway through a sentence.
4. **Metadata Extraction:** Define rules to extract and attach metadata (Document Title, Page Number) to each chunk.
5. **Configuration Export:** Output the final chunking parameters for the data pipeline.

## Expected Output
A "RAG Ingestion Spec" detailing the exact token size, overlap, semantic rules, and metadata schema.
