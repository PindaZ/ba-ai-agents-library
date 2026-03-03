# Bias Detection Scanner Skill

**Category:** Risk, Governance & Ethics
**Goal:** Automatically scan AI outputs or datasets to flag potential demographic, linguistic, or historical bias.

## Prerequisites
- A dataset sample or a log of 100+ recent AI outputs.
- Corporate ethics and inclusion guidelines.

## Required Tools/Integrations
- `nlp_sentiment_analyzer`
- `bias_detection_api` (e.g., Fairlearn)

## Execution Workflow
1. **Data Ingestion:** Load the sample data.
2. **Keyword Flagging:** Scan for sensitive keywords related to protected classes (gender, race, age, religion).
3. **Sentiment Disparity Analysis:** Compare the average sentiment score when referring to Group A vs. Group B.
4. **Representation Check:** Calculate the frequency of different demographics in the dataset.
5. **Report Generation:** Highlight the highest areas of disparity and assign a "Bias Risk Score".

## Expected Output
A "Bias Diagnostic Report" with specific examples of skewed outputs and recommendations for mitigation (e.g., data re-balancing).
