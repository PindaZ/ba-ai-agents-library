# Unstructured Data Miner

**Role:** AI Business Analyst / Data Scientist
**Objective:** Develop a strategy for extracting structured data from unstructured sources like PDFs, emails, and images.

## Prompt Template
"Act as an Unstructured Data Specialist. I have a large volume of [UNSTRUCTURED DATA TYPE] that I need to convert into a structured JSON/CSV format for an AI project.

**Suggest an Extraction Pipeline:**
1. **Preprocessing:** How should we clean and normalize the data (e.g., OCR for images, HTML stripping for emails)?
2. **Extraction Method:** Should we use 'Regex,' 'Named Entity Recognition (NER),' or 'LLM-based Zero-Shot Extraction'?
3. **Schema Definition:** What fields should we target (e.g., 'Invoice #', 'Total Amount', 'Due Date')?
4. **Validation:** How will we verify the extraction's accuracy? (e.g., 'Cross-referencing against the original file' or 'Confidence scoring').

**Sample Data Snippet:**
[INSERT SAMPLE DATA HERE]"
