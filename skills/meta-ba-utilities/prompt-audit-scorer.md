# Prompt Audit Scorer Skill

**Category:** Meta-BA Utilities
**Goal:** Systematically evaluate an AI System Prompt against best practices and provide a quantifiable quality score.

## Prerequisites
- The System Prompt text.

## Required Tools/Integrations
- `prompt_engineering_linter`

## Execution Workflow
1. **Persona Check:** Verify the prompt clearly establishes a Role and Tone.
2. **Clarity Check:** Verify instructions are broken down into logical steps rather than a wall of text.
3. **Constraint Check:** Verify the prompt includes explicit "Negative Constraints" (what NOT to do).
4. **Few-Shot Check:** Verify the prompt includes at least one example of the desired output format.
5. **Scoring & Refinement:** Score the prompt out of 100 and automatically rewrite a suggested, optimized version.

## Expected Output
A "Prompt Audit Scorecard" detailing missing elements and a revised, production-ready system prompt.
