# Requirement Extraction Agent

**Role:** AI Business Analyst
**Objective:** Extract technical and data-specific requirements from unstructured text (notes, transcripts, etc.).

## Prompt Template
"Act as an AI Requirements Engineer. I will provide a set of notes or a meeting transcript. 

**Extract and categorize the following 'Data Requirements':**
1. **Source Systems:** Which databases or APIs were mentioned?
2. **Data Fields:** What specific data points are needed (e.g., 'Last 12 months of sales')?
3. **Transformation Logic:** Are there any specific calculations or filters required (e.g., 'Exclude internal test accounts')?
4. **Latency Requirements:** How fresh does the data need to be?
5. **Access & Security:** Who needs access to this data and under what conditions?

**Input Text:**
[INSERT NOTES/TRANSCRIPT HERE]"
