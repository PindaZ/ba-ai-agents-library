# Strategic Roadmap Generator Skill

**Category:** Strategic Advisory
**Goal:** Automatically construct a phased timeline for AI adoption based on organizational goals and maturity.

## Prerequisites
- Strategic goals.
- AI maturity score.
- Resource availability (budget/team).

## Required Tools/Integrations
- `mermaid_generator` (for Gantt charts)

## Execution Workflow
1. **Phase Definition:** Split the roadmap into Foundation (0-6m), Experimentation (6-12m), and Scaling (12-24m).
2. **Initiative Placement:** Assign pre-approved AI use cases to phases based on their prerequisite needs (e.g., "Data Cleaning" must precede "Predictive Modeling").
3. **Milestone Creation:** Define 1 major success metric for the end of each phase.
4. **Chart Generation:** Generate a Mermaid.js Gantt chart visualizing the timeline.
5. **Risk Mapping:** Add a sub-section detailing the biggest risk for each phase.

## Expected Output
A detailed roadmap document including a visual Gantt chart and phase-by-phase objectives.
