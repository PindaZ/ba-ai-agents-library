# PII Masking Script Generator Skill

**Category:** Data & Technical Analysis
**Goal:** Identify Personally Identifiable Information (PII) in a schema and generate scripts to mask it before it reaches an LLM.

## Prerequisites
- Database schema or JSON payload structure.
- Corporate data privacy policy.

## Required Tools/Integrations
- `regex_generator`
- `python_script_writer`

## Execution Workflow
1. **Field Scanning:** Scan the schema for field names matching PII patterns (email, SSN, phone, address, name).
2. **Value Scanning:** Scan sample data using Regex to catch hidden PII in free-text fields.
3. **Masking Strategy Selection:** Decide between Hashing (for IDs), Pseudonymization (fake names), or Redaction (replacing with `[REDACTED]`).
4. **Code Generation:** Write a Python/Node.js middleware script that intercepts the payload and applies the masks.
5. **Testing:** Run a sample payload through the script to verify no PII leaks.

## Expected Output
A reusable middleware script (Python/JS) that automatically redacts PII from data before it is sent to the LLM API.
