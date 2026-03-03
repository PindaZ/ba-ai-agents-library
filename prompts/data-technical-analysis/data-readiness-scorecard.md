# Data Readiness Scorecard

**Role:** AI Business Analyst / Data Auditor
**Objective:** Evaluate if a dataset is ready for an AI initiative (Fine-tuning, RAG, etc.).

## Prompt Template
"Act as a Data Quality Auditor for AI projects. Analyze the following dataset description for 'Readiness'. 

**Provide a scorecard (1-10) for each category:**
1. **Completeness:** Are there significant gaps, null values, or missing time periods?
2. **Accuracy:** How reliable is the source? Are there known issues with data entry?
3. **Consistency:** Is the data format standardized (e.g., date formats, currency, naming conventions)?
4. **Volume:** Is the dataset large enough for the intended task (e.g., fine-tuning vs. RAG)?
5. **Bias Detection:** Are there historical biases in the data that could lead to unfair model outcomes?

**Format your response as a Markdown table:**
| Category | Score | Findings | Risk Level | Mitigation |
|----------|-------|----------|------------|------------|

**Dataset Details:**
[INSERT DATASET DESCRIPTION HERE]"
