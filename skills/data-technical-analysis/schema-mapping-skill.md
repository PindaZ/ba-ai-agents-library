# Schema Mapping Skill

**Category:** Data & Technical Analysis
**Goal:** Create a mapping document to translate disparate legacy data sources into a unified structure for AI consumption.

## Prerequisites
- Source schemas (A, B, C).
- Target schema for the AI model/Vector DB.

## Required Tools/Integrations
- `data_mapper_tool`

## Execution Workflow
1. **Source Ingestion:** Load schemas for Source A (e.g., Salesforce) and Source B (e.g., Zendesk).
2. **Target Ingestion:** Load the unified Target Schema.
3. **Fuzzy Matching:** Use semantic matching to align source fields to target fields (e.g., `sfdc.AccountName` -> `target.CompanyName`).
4. **Conflict Resolution:** Identify type mismatches (e.g., String vs Int, Date format differences) and write transformation logic.
5. **Matrix Output:** Generate a tabular mapping matrix.

## Expected Output
A detailed "Data Mapping Matrix" including transformation logic (ETL rules) for data engineers.
