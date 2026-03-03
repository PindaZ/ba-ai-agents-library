# Token Budgeting Advisor

**Role:** AI Business Analyst / Technical BA
**Objective:** Estimate the 'Monthly Operational Cost' (API tokens) for an AI system at various scales.

## Prompt Template
"Act as an AI Financial Planner. I need to estimate our monthly API costs for [AI SYSTEM NAME]. 

**I will provide the following variables:**
- **Daily Active Users (DAU):** [X]
- **Average Queries per User per Day:** [Y]
- **Average Tokens per Input:** [Z]
- **Average Tokens per Output:** [W]
- **Chosen Model:** (e.g., 'GPT-4o,' 'Llama-3-70B').
- **Pricing Tier:** (e.g., 'Standard' or 'Enterprise').

**Please provide:**
- An estimated 'Daily Cost' and 'Monthly Cost'.
- A 'Cost Breakdown' for 10x and 100x scale.
- 3 specific 'Cost Optimization Strategies' (e.g., 'Caching,' 'Model Switching,' or 'Prompt Compression').

**System Details:**
[INSERT SYSTEM DETAILS HERE]"
