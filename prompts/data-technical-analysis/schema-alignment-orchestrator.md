# Schema Alignment Orchestrator

**Role:** AI Business Analyst / Data Architect
**Objective:** Define a mapping between disparate data sources and a unified target schema for AI consumption.

## Prompt Template
"Act as a Data Mapping Specialist. I have two (or more) different data schemas that need to be aligned for an AI project. 

**Your task is to:**
1. **Create a 'Mapping Matrix':** Show which fields from Source A and Source B correspond to our Target Schema.
2. **Identify Data Conflicts:** (e.g., 'Source A uses USD, Source B uses EUR' or 'Different date formats').
3. **Define Transformation Rules:** For each conflict, provide a specific instruction (e.g., 'Convert all currencies to USD using the daily exchange rate API').
4. **Propose a 'Unified ID' Strategy:** How will we link records across these sources (e.g., hashing emails or using a Master Data Management ID)?

**Source Schema A:** [INSERT SCHEMA]
**Source Schema B:** [INSERT SCHEMA]
**Target Schema:** [INSERT SCHEMA]"
