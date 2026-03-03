# Unstructured Extraction Skill

**Category:** Data & Technical Analysis
**Goal:** Design a pipeline to reliably extract structured JSON data from messy, unstructured files (PDFs/Emails).

## Prerequisites
- Sample unstructured files.
- Target JSON schema.

## Required Tools/Integrations
- `ocr_engine` (Optional for images)
- `llm_json_mode`

## Execution Workflow
1. **Preprocessing:** Define how the file is converted to raw text (e.g., PyPDF2, Tesseract).
2. **Prompt Engineering:** Write a specific prompt enforcing `response_format: { "type": "json_object" }`.
3. **Extraction Mapping:** Explicitly map target JSON keys to descriptions of where to find them in the text.
4. **Validation Logic:** Write Python logic (e.g., Pydantic) to validate that the LLM output matches the required data types.
5. **Fallback Route:** Define what happens if the LLM fails to return valid JSON.

## Expected Output
A complete extraction pipeline specification, including the OCR tool choice, the extraction prompt, and the Pydantic validation schema.
