# Data Lineage Tracer Skill

**Category:** Data & Technical Analysis
**Goal:** Document the flow of data from its raw source, through transformations, to the final AI model.

## Prerequisites
- Access to data engineering scripts or ETL documentation.
- Enterprise architecture diagrams.

## Required Tools/Integrations
- `mermaid_generator`

## Execution Workflow
1. **Source Identification:** List all origin databases (e.g., Postgres, S3 buckets).
2. **Transformation Mapping:** Document every step where data is cleaned, joined, or embedded.
3. **Storage Mapping:** Document where the processed data rests (e.g., Feature Store, Vector DB).
4. **Consumption Mapping:** Show how the AI model or API consumes this data.
5. **Visual Drafting:** Write a Mermaid.js flowchart mapping Source -> Pipeline -> DB -> Model -> User.

## Expected Output
A comprehensive Data Lineage Diagram ensuring compliance and transparency in how AI uses company data.
