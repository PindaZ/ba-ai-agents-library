# Prompt Version Controller Skill

**Category:** Requirements Engineering
**Goal:** Establish a Git-like version control and testing workflow for System Prompts used in production.

## Prerequisites
- Current System Prompt.
- Set of 5-10 standard testing queries (Golden Dataset).

## Required Tools/Integrations
- `git_cli`
- `llm_api_runner` (for regression testing)

## Execution Workflow
1. **Prompt Ingestion:** Save the new system prompt to a `.prompt` or `.md` file.
2. **Change Documentation:** Require the engineer/BA to write a "Prompt Commit Message" explaining *why* the change was made.
3. **Regression Test:** Run the Golden Dataset against the new prompt and compare outputs with the previous version.
4. **Diff Analysis:** Highlight significant semantic drifts in the output.
5. **Approval Routing:** If output quality degrades, reject the commit; if it improves, tag it as `vX.X` and approve for staging.

## Expected Output
A version-controlled prompt repository with automated regression test reports for every change.
