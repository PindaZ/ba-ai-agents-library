# Fallback Logic Designer

**Role:** AI Business Analyst / UX Designer
**Objective:** Design the 'Graceful Degradation' paths for when an AI model fails or returns low-confidence results.

## Prompt Template
"Act as an AI UX Architect. I am designing a user flow for [AI FEATURE]. I need a 'Fallback & Recovery' strategy.

**Define the logic for the following scenarios:**
1. **Low Confidence Score:** If the model returns a confidence below [X%], what is the secondary action (e.g., human-in-the-loop, asking clarifying questions, or simplified response)?
2. **Model Timeout/Error:** What is the 'Static Fallback' if the LLM API is unreachable?
3. **Out-of-Distribution Input:** How should the system handle a user request that is valid but beyond the model's current training or context?
4. **Refusal/Guardrail Trigger:** How do we explain a refusal to the user without being frustrating?

**Provide:**
- A 'Decision Tree' for error handling.
- Sample 'Recovery Copy' for the UI.
- Instructions for logging these failures for the engineering team.

**Feature Flow:**
[INSERT FEATURE FLOW HERE]"
