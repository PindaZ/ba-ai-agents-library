# Synthetic Data Generator Skill

**Category:** Data & Technical Analysis
**Goal:** Generate high-quality, privacy-safe synthetic datasets for testing AI models and edge cases.

## Prerequisites
- Target data schema.
- Description of the required edge cases.

## Required Tools/Integrations
- `faker_library`
- `llm_data_generator`

## Execution Workflow
1. **Schema Definition:** Define the exact JSON/CSV structure required.
2. **Distribution Rules:** Define rules for the data (e.g., 80% standard transactions, 10% high-value, 10% corrupted data).
3. **Data Generation:** Use a data generation tool or an LLM to create 500+ rows matching the rules.
4. **Validation:** Run a script to ensure the synthetic data strictly adheres to data types and referential integrity.
5. **Export:** Save the output as a downloadable CSV or JSON file.

## Expected Output
A ready-to-use synthetic dataset that accurately mimics production complexity without exposing real user data.
