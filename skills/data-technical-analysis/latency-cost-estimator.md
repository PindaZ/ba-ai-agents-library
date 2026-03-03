# Latency Cost Estimator Skill

**Category:** Data & Technical Analysis
**Goal:** Compare the trade-offs between model size, response latency, and cost for a specific use case.

## Prerequisites
- Expected monthly queries.
- Average input/output token counts.

## Required Tools/Integrations
- `calculator`
- `pricing_api` (or static list of model prices)

## Execution Workflow
1. **Input Normalization:** Calculate the total monthly input and output tokens.
2. **Cost Calculation:** Apply the pricing formula for 3 different models (e.g., GPT-4o, Claude 3.5 Haiku, Llama 3 8B).
3. **Latency Estimation:** Map the average "Tokens per second" speed for each model.
4. **Trade-off Analysis:** Calculate the cost per 1,000 queries vs. the average wait time for the user.
5. **Recommendation:** Suggest the most efficient model that meets the user's maximum wait time threshold.

## Expected Output
A comparative table and a final architectural recommendation balancing UX (speed) and budget (cost).
