# How to Use the Skills Library

The `skills/` directory contains structured, executable workflows designed for agent-like behavior. Each skill defines how to perform a complex Business Analysis or AI Advisor task.

## What is a "Skill" in this Library?

Unlike simple prompts, a **Skill** is a multi-step workflow. Each skill file contains:
1. **Prerequisites:** What information you need to have *before* you start.
2. **Required Tools/Integrations:** Which external tools or APIs (e.g., Python, Web Search, OCR) are needed.
3. **Execution Workflow:** A step-by-step logic for completing the task.
4. **Expected Output:** What the final artifact should look like.

## How to Follow a Skill Workflow

1. **Pick a Skill:** Choose a file in the `skills/` directory (e.g., `data-readiness-auditor.md`).
2. **Check Prerequisites:** Ensure you have the required inputs (e.g., a sample dataset).
3. **Gather Tools:** Identify the tools you'll use (e.g., Python for data profiling).
4. **Execute Step-by-Step:** Follow the `Execution Workflow` logic sequentially.
5. **Verify Output:** Compare your final result with the `Expected Output` section.

## Implementing as a Manual Process
If you are performing these tasks manually, treat the **Execution Workflow** as a checklist of steps to ensure professional-grade results.

## Implementing with Agents
If you are building an AI agent (e.g., using Gemini CLI, LangChain, or Autogen), use the **Execution Workflow** and **Required Tools** to define the agent's logic and available functions.
