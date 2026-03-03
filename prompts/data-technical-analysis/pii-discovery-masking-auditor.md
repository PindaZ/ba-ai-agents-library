# PII Discovery & Masking Auditor

**Role:** AI Business Analyst / Data Privacy Officer
**Objective:** Identify and suggest masking strategies for sensitive data (PII) within a dataset.

## Prompt Template
"Act as a Data Privacy Specialist. I have a sample of data or a schema description for an AI project. 

**Your task is to:**
1. **Identify PII/PHI:** List all fields that contain Personally Identifiable Information (e.g., names, emails, IP addresses) or Protected Health Information.
2. **Assign Sensitivity Levels:** (e.g., Public, Internal, Confidential, Restricted).
3. **Suggest Masking Techniques:** For each sensitive field, suggest a technique (e.g., Anonymization, Pseudonymization, Hashing, or Differential Privacy).
4. **Draft a 'Data Minimization' Plan:** Which fields can be completely removed without impacting the AI model's performance?

**Data Sample/Schema:**
[INSERT DATA HERE]"
