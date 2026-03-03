# Data Readiness Auditor Skill

**Category:** Data & Technical Analysis
**Goal:** Automatically assess a dataset for completeness, bias, and suitability for AI training or RAG.

## Prerequisites
- Data dictionary or a 100-row sample CSV.
- AI use case description.

## Required Tools/Integrations
- `python_execution` (pandas profiling)
- `llm_analyzer`

## Execution Workflow
1. **Schema Ingestion:** Read the data dictionary and map data types.
2. **Missing Value Check:** Calculate the percentage of nulls in critical fields.
3. **Cardinality Analysis:** Check for low-cardinality fields that might indicate lack of diversity.
4. **Bias Flagging:** Identify columns representing protected classes (e.g., age, gender, race) that could skew the model.
5. **Score Generation:** Calculate a readiness score (0-100) based on data density and cleanliness.

## Expected Output
A "Data Readiness Scorecard" detailing missing values, potential biases, and recommended cleaning steps.
