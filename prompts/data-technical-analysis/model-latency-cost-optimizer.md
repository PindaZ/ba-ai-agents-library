# Model Latency-Cost Optimizer

**Role:** AI Business Analyst / Technical BA
**Objective:** Analyze the financial and user-experience trade-offs between different AI models.

## Prompt Template
"Act as an AI Infrastructure Architect. I need to decide which model to use for [PROJECT NAME]. 

**Compare 3 models (e.g., GPT-4o, GPT-4o-mini, Llama-3-70B) across:**
1. **Estimated Latency:** How long will a typical 500-token response take?
2. **Cost per 1M Tokens:** (Input vs. Output).
3. **Accuracy/Capability:** Is the smaller/cheaper model 'good enough' for this specific task?
4. **Throughput:** How many concurrent users can we support before hitting rate limits?

**Conclusion:** Provide a 'Cost-Efficiency Score' for each model and a final recommendation based on our budget of $[X] per month and a max latency of [Y] seconds.

**Task Description:**
[INSERT TASK DESCRIPTION HERE]"
