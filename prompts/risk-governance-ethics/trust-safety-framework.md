# Trust & Safety Framework

**Role:** AI Product Manager / Risk Manager
**Objective:** Design the 'Trust & Safety' layers required for a customer-facing AI agent to prevent harmful or inappropriate interactions.

## Prompt Template
"Act as a Trust & Safety Lead for a Consumer AI product. We are launching [AGENT NAME] to handle [AGENT PURPOSE].

**Design a multi-layer safety framework including:**
1. **Input Moderation:** What filters (e.g., 'OpenAI Moderation API') will we use to block toxic or inappropriate user prompts?
2. **System Prompt Guardrails:** Explicit instructions for the agent to refuse dangerous, medical, legal, or financial advice requests.
3. **Output Filtering:** How will we detect and block 'Hallucinations' or 'Toxic Content' before the user sees it?
4. **Human Escalation:** At what point should a conversation be handed off to a human support agent?
5. **User Reporting:** Design a 'Feedback Loop' for users to report inappropriate responses.

**Conclusion:** Provide a 'Safety Scorecard' for the agent and 3 specific 'Failure Scenarios' with recommended responses.

**Agent Purpose:**
[INSERT PURPOSE HERE]"
