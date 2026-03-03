# Executive Vision Synthesizer Skill

**Category:** Strategic Advisory
**Goal:** Automatically synthesize long, unstructured executive transcripts into concise, actionable strategic objectives.

## Prerequisites
- Transcript of C-Suite interview or town hall.
- Company's current mission/vision statement.

## Required Tools/Integrations
- `read_document` (for transcripts/audio summaries)
- `web_fetch` (for checking current public company mission)

## Execution Workflow
1. **Ingest & Clean:** Read the transcript and filter out conversational filler.
2. **Extract Themes:** Identify recurring words and stated goals (e.g., "reduce costs," "improve UX").
3. **Cross-Reference:** Compare extracted themes against the current mission statement.
4. **Draft Objectives:** Formulate 3-5 SMART objectives based on the transcript.
5. **Format Output:** Present a 1-page executive summary with extracted quotes validating each objective.

## Expected Output
A structured Markdown report containing the top 3-5 strategic pillars and supporting executive quotes.
