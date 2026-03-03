# Feedback Loop Orchestrator

**Role:** AI Business Analyst / UX Designer
**Objective:** Design a systematic process for gathering, labeling, and integrating user feedback into model improvements.

## Prompt Template
"Act as an AI Product Manager. I am designing the 'Feedback Loop' for our [AI AGENT NAME]. 

**Develop a strategy covering:**
1. **Implicit Feedback:** What user actions (e.g., 'Copying the AI output' or 'Ignoring it') should we track to measure success?
2. **Explicit Feedback:** Design the UI for user ratings (e.g., 'Thumbs Up/Down,' 'Star Rating,' or 'Edit Response').
3. **Negative Feedback Protocol:** If a user flags a 'Hallucination' or 'Harmful Output,' what happens immediately (e.g., 'Flagging for human review')?
4. **Closing the Loop:** How do we tell the user their feedback was used to improve the system?
5. **Data Pipeline:** How do we feed this labeled data back into the model's fine-tuning or RAG process?

**Product Context:**
[INSERT PRODUCT CONTEXT HERE]"
