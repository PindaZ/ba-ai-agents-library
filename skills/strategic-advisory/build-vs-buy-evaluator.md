# Build vs Buy Evaluator Skill

**Category:** Strategic Advisory
**Goal:** Systematically evaluate whether to build a custom AI solution or purchase a SaaS platform.

## Prerequisites
- Business requirement document (BRD).
- Budget constraints and timeline.

## Required Tools/Integrations
- `google_web_search` (to find SaaS vendors)
- `calculator` (for TCO comparison)

## Execution Workflow
1. **Requirement Mapping:** Extract core requirements from the BRD.
2. **Vendor Discovery:** Search for top 3 SaaS vendors that meet >80% of requirements.
3. **Build Estimation:** Estimate time/cost for internal engineering to build the MVP.
4. **TCO Comparison:** Compare 3-year SaaS licensing fees vs. 3-year internal build + maintenance costs.
5. **Risk Assessment:** Evaluate data privacy risks of using the vendor vs. internal hosting.

## Expected Output
A decision matrix comparing "Custom Build" vs. "Vendor A" vs. "Vendor B" with a final recommendation.
