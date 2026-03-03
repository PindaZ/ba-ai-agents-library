# ROI Calculator Skill

**Category:** Strategic Advisory
**Goal:** Calculate the Total Cost of Ownership (TCO) and Break-Even Point for a proposed AI initiative.

## Prerequisites
- Estimated monthly API token usage or compute hours.
- Developer salaries and estimated build time.
- Current manual process cost (hours * wage).

## Required Tools/Integrations
- `calculator` / `python_execution` (for financial modeling)
- `read_file` (for project specs)

## Execution Workflow
1. **CapEx Calculation:** Sum the initial build costs (Data Prep + Model Training/Prompting + UI/UX).
2. **OpEx Calculation:** Estimate monthly API costs, hosting, and human-in-the-loop maintenance.
3. **Savings Calculation:** Calculate the cost of the manual process minus the cost of the automated process.
4. **Break-Even Analysis:** Divide CapEx by monthly savings to find the payback period in months.
5. **Sensitivity Analysis:** Run the numbers with +/- 20% token usage to show risk.

## Expected Output
A financial breakdown table and a summary paragraph stating the Break-Even month and 1-Year ROI.
