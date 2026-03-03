# Fallback Logic Mapper Skill

**Category:** Requirements Engineering
**Goal:** Design the UX and technical fallback mechanisms for when an AI model fails, times out, or hallucinates.

## Prerequisites
- Core user journey flow.
- Identification of AI touchpoints.

## Required Tools/Integrations
- `ux_flow_mapper`

## Execution Workflow
1. **Failure Point Identification:** Map every API call to the LLM in the user journey.
2. **Timeout Strategy:** Define what the UI shows if the API takes >X seconds (e.g., loading skeletons, then static error message).
3. **Low-Confidence Strategy:** Define the action if the model returns a score below threshold (e.g., route to a human agent).
4. **Guardrail Strategy:** Define the canned response if a user triggers a safety filter.
5. **Documentation:** Compile these into a "Graceful Degradation" matrix.

## Expected Output
A matrix mapping every possible AI failure state to a specific UI response and backend action.
