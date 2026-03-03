# CSAT Sentiment Analyzer Skill

**Category:** Change Management & Adoption
**Goal:** Automatically calculate the Customer Satisfaction score specifically for the AI feature using both numerical ratings and text sentiment.

## Prerequisites
- Survey results containing a 1-5 rating and open-text feedback.

## Required Tools/Integrations
- `sentiment_analyzer_api`
- `csv_parser`

## Execution Workflow
1. **Quantitative Calculation:** Calculate the average 1-5 score for the AI feature.
2. **Qualitative Ingestion:** Run the open-text feedback through an LLM sentiment analyzer.
3. **Discrepancy Check:** Flag any instances where a user gave a "5" but the text says something negative (or vice versa).
4. **Theme Extraction:** Group the negative sentiments into specific UI/UX or model performance buckets.
5. **Reporting:** Generate a monthly CSAT dashboard.

## Expected Output
A CSAT summary report correlating user sentiment directly to specific AI interactions.
