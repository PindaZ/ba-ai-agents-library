# BDD Gherkin Generator Skill

**Category:** Requirements Engineering
**Goal:** Translate standard AI User Stories into Behavior-Driven Development (BDD) Gherkin syntax for automated testing.

## Prerequisites
- User Stories with rough Acceptance Criteria.

## Required Tools/Integrations
- `gherkin_linter`

## Execution Workflow
1. **Format Ingestion:** Read the User Story and AC.
2. **Scenario Creation:** Break down the AC into individual `Scenario:` blocks.
3. **Gherkin Translation:** Rewrite logic using strict `Given`, `When`, `Then`, `And`, `But` keywords.
4. **Data Table Addition:** For AI prompts, add `Examples:` tables to test multiple inputs (e.g., standard input, edge case input, malicious input).
5. **Linting:** Ensure the syntax is compatible with tools like Cucumber or Behave.

## Expected Output
A `.feature` file containing testable BDD scenarios ready for the QA automation team.
