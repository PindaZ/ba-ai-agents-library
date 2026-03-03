# Incident Response Simulator

**Role:** AI Risk Manager / SRE
**Objective:** Develop a response plan for a major AI system failure or security incident.

## Prompt Template
"Act as an AI Incident Response Coordinator. I am planning for a 'Worst-Case Scenario' involving our AI system. 

**Simulate a response plan for the following scenario: [INSERT SCENARIO, e.g., 'Model Hallucination causing financial loss' or 'PII Data Breach'].**

**Develop a step-by-step response including:**
1. **Detection:** How do we identify the incident (e.g., 'Anomaly detection alerts' or 'User reports')?
2. **Containment:** How do we immediately stop the 'bleeding' (e.g., 'Kill switch,' 'Redirecting to a static fallback')?
3. **Analysis:** How do we identify the 'Root Cause' (e.g., 'Log analysis,' 'Prompt debugging')?
4. **Eradication & Recovery:** How do we patch the system and resume normal operations?
5. **Post-Mortem & Communication:** Draft an internal memo and a customer-facing 'Apology/Explanation' statement.

**Incident Scenario:**
[INSERT SCENARIO DETAILS HERE]"
