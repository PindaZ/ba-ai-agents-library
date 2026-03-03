# Model Card Assembler Skill

**Category:** Risk, Governance & Ethics
**Goal:** Automatically compile a standardized "Model Card" documenting a model's capabilities, limitations, and training data.

## Prerequisites
- Training data summary.
- Model performance metrics (Accuracy, F1, etc.).
- Intended use cases.

## Required Tools/Integrations
- `markdown_table_generator`

## Execution Workflow
1. **Metadata Collection:** Gather Model Name, Version, Developer, and Release Date.
2. **Intended Use Definition:** Explicitly list what the model should be used for, and what is strictly out-of-scope.
3. **Training Data Summary:** Document the size, source, and known biases of the training dataset.
4. **Performance Metric Formatting:** Create tables showing the model's performance across different demographic benchmarks.
5. **Ethical Considerations:** Add standard boilerplate regarding human oversight and potential risks.

## Expected Output
A standardized Markdown `MODEL_CARD.md` ready to be published alongside the AI release.
