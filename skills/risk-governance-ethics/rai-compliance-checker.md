# RAI Compliance Checker Skill

**Category:** Risk, Governance & Ethics
**Goal:** Audit an AI project against Responsible AI (RAI) frameworks like the EU AI Act or NIST AI RMF.

## Prerequisites
- Completed AI project specification.
- Access to current regulatory checklists.

## Required Tools/Integrations
- `compliance_database_search`

## Execution Workflow
1. **Risk Categorization:** Determine if the system is "Unacceptable," "High," "Limited," or "Minimal" risk based on EU AI Act definitions.
2. **Transparency Audit:** Check if the spec includes UI elements that explicitly inform the user they are interacting with an AI.
3. **Human Oversight Check:** Verify that a "Human-in-the-Loop" (HITL) step exists for any high-stakes decisions.
4. **Data Governance Check:** Confirm that training data collection complies with GDPR/CCPA.
5. **Gap Analysis:** List the specific legal requirements the current spec fails to meet.

## Expected Output
An "RAI Compliance Audit Report" prioritizing mandatory legal changes required before launch.
