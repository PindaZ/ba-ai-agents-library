# Multi-Agent Orchestrator Skill

**Category:** Requirements Engineering
**Goal:** Design the interaction rules, data hand-offs, and sequence for a system utilizing multiple AI agents.

## Prerequisites
- Overarching workflow goal (e.g., "Automated Blog Publishing").
- List of specialized agents (e.g., Researcher, Writer, Editor).

## Required Tools/Integrations
- `mermaid_generator`
- `schema_definer`

## Execution Workflow
1. **Agent Definition:** Define the exact Persona and System Prompt constraints for each sub-agent.
2. **Input/Output Mapping:** Define the JSON schema that Agent A outputs and Agent B ingests.
3. **State Management Logic:** Determine where the shared context (memory) is stored between turns.
4. **Routing Logic:** Define the conditional logic for the "Supervisor Agent" to decide which sub-agent goes next.
5. **Diagram Generation:** Create a sequence diagram showing the flow of data.

## Expected Output
A technical specification document for the multi-agent workflow, including JSON schemas and a Mermaid.js sequence diagram.
