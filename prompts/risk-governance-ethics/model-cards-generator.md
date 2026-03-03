# Model Cards Generator

**Role:** AI Business Analyst / Data Scientist
**Objective:** Create a 'Model Card'—a standardized document that provides transparency into an AI model's training, performance, and limitations.

## Prompt Template
"Act as an AI Documentation Specialist. I am deploying a new AI model [MODEL NAME]. 

**Create a 'Model Card' based on the Google/OpenAI standard, including:**
1. **Model Details:** Purpose, version, architecture, and date.
2. **Intended Use:** What is this model *for*? What are its 'out-of-scope' use cases?
3. **Training Data:** What data was used to train/fine-tune the model? What were its limitations or biases?
4. **Performance Metrics:** Accuracy, precision, recall, and F1-score on standard benchmarks.
5. **Ethical Considerations:** Potential risks, bias audit results, and mitigation strategies.
6. **Caveats & Recommendations:** What should developers and users keep in mind when using this model?

**Model Details:**
[INSERT MODEL DETAILS HERE]"
