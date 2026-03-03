# Edge Case Scenario Runner Skill

**Category:** Data & Technical Analysis
**Goal:** Automatically generate and run malicious or corrupted data inputs against the model to test resilience.

## Prerequisites
- An API endpoint for the AI model.
- List of expected data formats.

## Required Tools/Integrations
- `python_requests`
- `synthetic_data_generator`

## Execution Workflow
1. **Scenario Generation:** Create 10 specific edge cases (e.g., empty strings, 1MB of text, SQL injection strings, emojis-only).
2. **Batch Execution:** Send these inputs to the AI endpoint asynchronously.
3. **Response Logging:** Record the HTTP status code, response time, and the model's output.
4. **Failure Analysis:** Identify any inputs that caused a 500 Error, a timeout, or a hallucination.
5. **Report Generation:** Summarize the vulnerabilities.

## Expected Output
An "Edge Case Resilience Report" highlighting breaking points and suggesting input validation rules.
