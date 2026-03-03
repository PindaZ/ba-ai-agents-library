# User Story Generator Skill

**Category:** Requirements Engineering
**Goal:** Automatically convert a high-level AI feature request into granular, INVEST-compliant User Stories.

## Prerequisites
- Feature brief or BRD section.
- Target user personas.

## Required Tools/Integrations
- `jira_integration` (Optional: for direct ticket creation)
- `agile_framework_prompt`

## Execution Workflow
1. **Persona Mapping:** Identify all users (human or system) interacting with the feature.
2. **Action Extraction:** Break down the feature into single, atomic actions.
3. **Value Definition:** Determine the "Why" (business value) for each action.
4. **Formatting:** Structure each as "As a [Persona], I want to [Action], so that [Value]."
5. **INVEST Audit:** Evaluate each story to ensure it is Independent, Negotiable, Valuable, Estimable, Small, and Testable.

## Expected Output
A prioritized backlog of User Stories formatted for immediate import into an Agile tool.
