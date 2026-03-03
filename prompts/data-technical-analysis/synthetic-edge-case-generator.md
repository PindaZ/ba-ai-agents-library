# Synthetic Edge Case Generator

**Role:** AI Business Analyst / QA Engineer
**Objective:** Generate a diverse set of "unlikely but possible" data scenarios to stress-test an AI model.

## Prompt Template
"Act as a QA Edge Case Generator. I am testing an AI model designed for [MODEL PURPOSE]. 

**Please generate 10 synthetic 'Edge Case' scenarios that could cause the model to fail or behave unexpectedly. Categories to include:**
1. **Extreme Values:** (e.g., 'A transaction of $0.01' or '$1,000,000,000' in a consumer app).
2. **Missing/Corrupt Data:** (e.g., 'A user profile with only a birthdate and no name').
3. **Ambiguous Inputs:** (e.g., 'A customer feedback comment that is 50% positive and 50% negative').
4. **Adversarial/Jailbreak Attempts:** (e.g., 'A user asking the model to ignore its instructions').
5. **Format Anomalies:** (e.g., 'An email address with 500 characters').

**For each scenario, provide:**
- The input data.
- The 'Expected Behavior' vs. the 'Potential Failure Mode'.

**Model Purpose:**
[INSERT MODEL PURPOSE HERE]"
