# API Contract Drafter Skill

**Category:** Requirements Engineering
**Goal:** Bridge the gap between Business Analysts and Backend Developers by drafting REST/GraphQL API contracts for AI services.

## Prerequisites
- Functional requirements for the AI feature.
- Expected data inputs (from UI) and expected outputs (from LLM).

## Required Tools/Integrations
- `json_schema_generator`
- `swagger_openapi_formatter`

## Execution Workflow
1. **Endpoint Definition:** Propose RESTful endpoint names (e.g., `POST /api/v1/generate-summary`).
2. **Request Payload Design:** Define the required JSON payload, including parameters like `temperature`, `max_tokens`, and user inputs.
3. **Response Payload Design:** Define the success schema, ensuring fields for `content`, `metadata` (token usage), and `confidence_score`.
4. **Error Handling Design:** Map out standard HTTP status codes (400, 429, 500) with specific AI-related error messages.
5. **Format Export:** Wrap the design in standard OpenAPI/Swagger YAML or JSON format.

## Expected Output
A developer-ready API contract (OpenAPI spec) mapping the business requirements to technical endpoints.
