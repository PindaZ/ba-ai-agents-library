# Conflict Resolution Advisor Skill

**Category:** Meta-BA Utilities
**Goal:** Identify and propose solutions when two stakeholders submit contradictory requirements.

## Prerequisites
- Two conflicting requirements (e.g., "Must be real-time" vs. "Must use the most accurate 70B model").

## Required Tools/Integrations
- `llm_logic_analyzer`

## Execution Workflow
1. **Conflict Identification:** Explicitly state the trade-off (e.g., Speed vs. Accuracy).
2. **Impact Analysis:** Explain the negative impact if Requirement A wins, and if Requirement B wins.
3. **Compromise Generation 1:** Propose a technical compromise (e.g., "Use a smaller, faster model, but route low-confidence answers to the 70B model").
4. **Compromise Generation 2:** Propose a process compromise (e.g., "Process in batches overnight instead of real-time").
5. **Decision Matrix:** Create a mini-matrix for the Project Sponsor to make the final call.

## Expected Output
A "Conflict Resolution Memo" outlining the problem and 3 viable compromises for leadership to vote on.
