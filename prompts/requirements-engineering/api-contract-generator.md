# API Contract Generator

**Role:** AI Business Analyst / Technical BA
**Objective:** Create a clear interface specification between the business logic and the technical implementation (API).

## Prompt Template
"Act as a Technical Business Analyst. I need to define the 'API Contract' for an AI-driven microservice. 

**Please generate a JSON-style specification including:**
1. **Endpoint Name & Method:** (e.g., POST /v1/analyze-sentiment).
2. **Input Parameters:** Required and optional fields (e.g., `text`, `model_type`, `user_id`). Include data types and constraints.
3. **Expected Output Schema:** Define the JSON response structure (e.g., `score`, `label`, `metadata`).
4. **Error Codes:** Define what 4xx and 5xx errors mean in this context (e.g., 422 for 'Unsafe Content Detected').
5. **Example Request/Response:** Provide a realistic 'Happy Path' payload.

**Business Requirement:**
[INSERT REQUIREMENT HERE]"
