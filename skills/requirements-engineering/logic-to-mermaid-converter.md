# Logic to Mermaid Converter Skill

**Category:** Requirements Engineering
**Goal:** Rapidly convert unstructured text describing business rules into a visual flowchart for developer consumption.

## Prerequisites
- Meeting notes, transcript, or a text-based SOP (Standard Operating Procedure).

## Required Tools/Integrations
- `text_parser`
- `mermaid_syntax_validator`

## Execution Workflow
1. **Entity Extraction:** Identify actors, systems, and databases mentioned in the text.
2. **Decision Node Identification:** Find conditional words ("If," "When," "Otherwise," "Unless") to create branching paths.
3. **Code Generation:** Draft the Mermaid.js `graph TD` syntax representing the flow.
4. **Syntax Validation:** Run a mock render test to ensure the Mermaid syntax is valid.
5. **Refinement:** Add sub-graphs to represent different system boundaries (e.g., "Frontend" vs "LLM Backend").

## Expected Output
A block of valid Mermaid.js code that renders a clear, color-coded business logic flowchart.
