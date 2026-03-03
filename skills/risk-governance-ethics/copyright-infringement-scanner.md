# Copyright Infringement Scanner Skill

**Category:** Risk, Governance & Ethics
**Goal:** Audit training datasets and AI outputs for potential violations of intellectual property or copyright.

## Prerequisites
- Sample of training data or typical RAG knowledge base.
- List of known proprietary/copyrighted sources in the industry.

## Required Tools/Integrations
- `plagiarism_checker_api`
- `web_fetch`

## Execution Workflow
1. **Data Sampling:** Take a random 5% sample of the data.
2. **String Matching:** Run exact string matches against known copyrighted databases or public web data.
3. **Output Auditing:** Test the AI model by asking it to reproduce known copyrighted works (e.g., "Write the first chapter of Harry Potter").
4. **License Verification:** Check the licenses of any open-source models being used (e.g., ensuring no commercial use on a non-commercial license).
5. **Risk Assessment:** Flag any high-risk data sources that need to be purged.

## Expected Output
An "IP & Copyright Risk Audit" highlighting specific datasets or model behaviors that expose the company to legal liability.
