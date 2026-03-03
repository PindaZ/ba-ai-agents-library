# Incident Response Drafter Skill

**Category:** Risk, Governance & Ethics
**Goal:** Create a step-by-step playbook for how the organization should react if the AI system fails catastrophically in production.

## Prerequisites
- AI System Architecture.
- Contact list for the escalation matrix (DevOps, Legal, PR).

## Required Tools/Integrations
- `markdown_generator`

## Execution Workflow
1. **Scenario Definition:** Define 3 worst-case scenarios (e.g., "AI leaks PII," "AI gives dangerous advice," "AI goes offline").
2. **Containment Protocol:** Document the "Kill Switch" process (who has the authority to shut down the API, and how).
3. **Escalation Tree:** Map exactly who is called at Minute 1, Hour 1, and Day 1.
4. **Communication Templates:** Draft pre-approved PR and internal comms templates apologizing and explaining the downtime.
5. **Post-Mortem Requirements:** Define the required steps for the Root Cause Analysis (RCA) after containment.

## Expected Output
A comprehensive "AI Incident Response Playbook" ready for the SRE/DevOps and PR teams.
