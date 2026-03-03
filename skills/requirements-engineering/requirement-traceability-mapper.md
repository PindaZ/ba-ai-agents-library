# Requirement Traceability Mapper Skill

**Category:** Requirements Engineering
**Goal:** Ensure every technical AI feature and prompt instruction maps directly back to an approved business requirement.

## Prerequisites
- Business Requirements Document (BRD).
- System Architecture Document or System Prompts.

## Required Tools/Integrations
- `document_comparator`

## Execution Workflow
1. **ID Tagging:** Assign a unique ID (e.g., BRD-001) to every business requirement.
2. **Technical Extraction:** Parse the System Prompts and API contracts for specific rules or behaviors.
3. **Mapping Generation:** Create a matrix mapping [Technical Behavior] -> [BRD-ID].
4. **Orphan Check:** Identify any technical features that do not map to a business requirement (Scope Creep).
5. **Gap Check:** Identify any business requirements that have not been implemented in the technical spec.

## Expected Output
A "Requirements Traceability Matrix (RTM)" ensuring alignment between business goals and the deployed AI system.
