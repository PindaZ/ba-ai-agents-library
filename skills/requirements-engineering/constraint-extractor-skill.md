# Constraint Extractor Skill

**Category:** Requirements Engineering
**Goal:** Analyze a feature request and automatically extract the "Negative Requirements" (what the system MUST NOT do).

## Prerequisites
- Feature description.
- Corporate compliance policies.

## Required Tools/Integrations
- `policy_database_search`

## Execution Workflow
1. **Feature Analysis:** Analyze the core functionality of the proposed AI tool.
2. **Boundary Identification:** Ask "What happens if a user maliciously abuses this feature?"
3. **Policy Cross-Reference:** Check the feature against data privacy, copyright, and tone guidelines.
4. **Constraint Drafting:** Write explicit "Negative Stories" (e.g., "The agent MUST NOT provide financial advice").
5. **Guardrail Configuration:** Map these constraints to specific engineering tasks (e.g., System Prompt additions or Input Moderation layers).

## Expected Output
A "System Constraints and Guardrails" spec sheet to be attached to the main BRD.
