# Problem Solution Validator Skill

**Category:** Strategic Advisory
**Goal:** Critically evaluate an AI proposal to ensure it solves a real business problem rather than just being "AI for AI's sake."

## Prerequisites
- Problem statement.
- Proposed AI solution.

## Required Tools/Integrations
- `logical_reasoning_engine` (Internal LLM prompt constraint)

## Execution Workflow
1. **Root Cause Check:** Ask "Why" 3 times to ensure the stated problem is the root cause.
2. **Alternative Check:** Propose 2 non-AI solutions (e.g., simple rule-based automation, UI redesign).
3. **Complexity Comparison:** Compare the implementation effort of the AI solution vs. the non-AI alternatives.
4. **Value Check:** Estimate if the AI solution provides at least a 3x improvement over the alternatives to justify the complexity.
5. **Validation Decision:** Output a "Go/No-Go" recommendation based on the fit.

## Expected Output
A "Solution Validation Report" that either greenlights the AI project or pivots to a simpler, non-AI alternative.
