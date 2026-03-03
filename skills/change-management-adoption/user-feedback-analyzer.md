# User Feedback Analyzer Skill

**Category:** Change Management & Adoption
**Goal:** Aggregate and analyze qualitative user feedback to identify common AI failure points and UX frustrations.

## Prerequisites
- Export of user feedback logs (e.g., Zendesk tickets, thumbs down comments).

## Required Tools/Integrations
- `sentiment_analyzer`
- `topic_cluster_algorithm`

## Execution Workflow
1. **Data Cleaning:** Remove PII and irrelevant boilerplate text from the feedback logs.
2. **Sentiment Tagging:** Tag each comment as Positive, Neutral, or Negative.
3. **Thematic Clustering:** Group negative feedback into themes (e.g., "Hallucinations," "Too Slow," "Confusing UI").
4. **Frequency Counting:** Calculate which theme occurs most frequently.
5. **Actionable Summary:** Translate the top 3 complaints into specific Jira tickets for the engineering team.

## Expected Output
A "User Sentiment Dashboard" report and a list of actionable bug/feature tickets based on user feedback.
