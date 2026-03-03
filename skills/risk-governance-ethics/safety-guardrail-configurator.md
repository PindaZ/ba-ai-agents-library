# Safety Guardrail Configurator Skill

**Category:** Risk, Governance & Ethics
**Goal:** Design the multi-layered technical filters that prevent an AI from processing or generating harmful content.

## Prerequisites
- Corporate risk tolerance guidelines.
- Target user persona (e.g., Children, Medical Patients, Enterprise Workers).

## Required Tools/Integrations
- `json_schema_generator`

## Execution Workflow
1. **Input Filter Design:** Define the rules for the pre-LLM filter (e.g., blocking toxic keywords or blocking inputs > 1000 tokens).
2. **System Prompt Guardrails:** Write the explicit negative constraints to be injected into the system prompt.
3. **Output Filter Design:** Define the rules for the post-LLM filter (e.g., running the output through an OpenAI Moderation endpoint before showing the user).
4. **Refusal Logic:** Script the exact, polite language the bot must use when refusing a prompt.
5. **Logging Spec:** Define how these blocked interactions are logged for the security team without saving PII.

## Expected Output
A "Trust & Safety Architecture" spec detailing the exact input, prompt, and output filters to be implemented by engineering.
