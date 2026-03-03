# Prompt Versioning Logic

**Role:** AI Business Analyst / Prompt Engineer
**Objective:** Establish a structured methodology for tracking, testing, and versioning system prompts.

## Prompt Template
"Act as a Prompt Operations (PromptOps) Manager. I need to document a change to our core System Prompt. 

**Structure the version entry as follows:**
1. **Version ID:** (e.g., v2.1.0)
2. **Change Description:** What specific instruction was added, removed, or modified?
3. **Rationale:** What was the business or technical reason for this change (e.g., 'Reducing verbosity' or 'Fixing a recurring hallucination')?
4. **Test Results:** Compare the 'Before' and 'After' output quality on 3-5 standard test cases.
5. **Regression Check:** Ensure the new prompt hasn't broken previously working functionality.
6. **Deployment Status:** Is this in Sandbox, Staging, or Production?

**Current Prompt:** [INSERT OLD PROMPT]
**Proposed Change:** [INSERT NEW PROMPT]"
