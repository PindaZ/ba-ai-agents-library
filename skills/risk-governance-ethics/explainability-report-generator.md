# Explainability Report Generator Skill

**Category:** Risk, Governance & Ethics
**Goal:** Generate human-readable explanations (XAI) for why an AI model made a specific decision, ensuring transparency.

## Prerequisites
- A specific model prediction output.
- Feature importance scores (e.g., from SHAP or LIME).

## Required Tools/Integrations
- `data_visualizer`
- `llm_text_generator`

## Execution Workflow
1. **Data Ingestion:** Load the raw decision output and the weighted feature scores.
2. **Feature Translation:** Translate technical feature names into business language (e.g., `dti_ratio` -> "Debt-to-Income Ratio").
3. **Narrative Generation:** Use an LLM to write a 2-paragraph summary explaining the top 3 factors that influenced the decision.
4. **Counterfactual Generation:** State what would need to change for the decision to be different (e.g., "If income was 10% higher, the loan would be approved").
5. **Formatting:** Package this into a format suitable for the end-user or auditor.

## Expected Output
An "AI Decision Explanation Report" that non-technical users and regulators can easily understand.
