# Constraint Definition Engine

**Role:** AI Business Analyst / Risk Manager
**Objective:** Define and document the "Negative Requirements" and hard boundaries for an AI system.

## Prompt Template
"Act as an AI Safety and Governance Officer. I am defining the requirements for [AI AGENT NAME]. 

Beyond what the AI *should* do, I need to define what it **must never** do. Please generate a 'Constraint Specification' covering:
1. **Topic Boundaries:** List 5-10 specific topics or sensitive areas the agent must refuse to discuss.
2. **Action Boundaries:** What system actions (e.g., deleting data, making purchases >$X) require mandatory human approval?
3. **Data Boundaries:** Define rules for PII handling, internal-only data access, and data retention.
4. **Tone & Style Guardrails:** Explicitly forbid specific styles (e.g., sarcasm, clinical jargon, or overly emotional language).
5. **Hallucination Protocol:** Define the standard 'I don't know' response format to prevent guessing.

**Agent Context:**
[INSERT AGENT PURPOSE HERE]"
