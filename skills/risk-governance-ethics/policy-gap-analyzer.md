# Policy Gap Analyzer Skill

**Category:** Risk, Governance & Ethics
**Goal:** Compare a company's existing IT/Data policies against new AI-specific operational requirements.

## Prerequisites
- Current Employee IT Handbook or Data Policy.
- Draft AI Usage Policy requirements.

## Required Tools/Integrations
- `document_comparator`

## Execution Workflow
1. **Document Ingestion:** Read the existing corporate policies.
2. **AI Requirement Ingestion:** Read the new AI standards (e.g., "Employees must not input client data into public LLMs").
3. **Gap Identification:** Find where the current policy is silent or contradicts the new AI rules.
4. **Risk Scoring:** Assign a risk level to each gap based on the potential for data leakage or IP loss.
5. **Amendment Drafting:** Write the exact legal/corporate language needed to update the employee handbook.

## Expected Output
A "Policy Gap Analysis" table and a drafted addendum for the employee handbook regarding Generative AI usage.
