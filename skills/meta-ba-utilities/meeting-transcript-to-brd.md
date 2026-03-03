# Meeting Transcript to BRD Skill

**Category:** Meta-BA Utilities
**Goal:** Convert raw, unstructured meeting transcripts into a formally structured draft of a Business Requirements Document.

## Prerequisites
- Raw audio transcript from a requirements gathering session.

## Required Tools/Integrations
- `text_summarizer`
- `brd_template_mapper`

## Execution Workflow
1. **Noise Filtering:** Remove conversational filler and off-topic chat from the transcript.
2. **Entity Extraction:** Identify the "Actors," "Actions," and "Systems" mentioned.
3. **Goal Summarization:** Write the Executive Summary based on the project sponsor's opening remarks.
4. **Requirement Categorization:** Sort extracted actions into "Functional" and "Non-Functional" requirements.
5. **Constraint Mapping:** Extract any limitations or deadlines mentioned and place them in the Assumptions section.

## Expected Output
A formatted Markdown BRD draft that simply requires the Business Analyst's final review and polish.
