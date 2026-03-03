# BA & AI Agents Library

A comprehensive repository for prompts, agent skills, and templates tailored for the Business Analyst and AI Business Advisor workflow.

## 📖 User Documentation
- **[How to Use Prompts](./docs/GUIDE-PROMPTS.md):** A guide to getting the most out of the prompt library.
- **[How to Use Skills](./docs/GUIDE-SKILLS.md):** A guide to following executable agent workflows.
- **[Functional Toolkits](#functional-toolkits):** An overview of the 6 core categories.

---

## 🛠 Functional Toolkits

### 1. [Strategic Advisory Toolkit](./prompts/strategic-advisory/)
Focus: C-Suite alignment, investment justification, and high-level direction.
- [Executive Visioning Mirror](./prompts/strategic-advisory/executive-visioning-mirror.md)
- [ROI & TCO Calculators](./prompts/strategic-advisory/roi-tco-calculator.md)
- [Market Intelligence Sentinel](./prompts/strategic-advisory/market-intelligence-sentinel.md)

### 2. [Requirements Engineering Toolkit](./prompts/requirements-engineering/)
Focus: Granular definitions, process flows, and developer-ready specs.
- [User Story Generator (INVEST)](./prompts/requirements-engineering/user-story-generator-invest.md)
- [Acceptance Criteria Writer](./prompts/requirements-engineering/acceptance-criteria-writer.md)
- [Multi-Agent Workflow Architect](./prompts/requirements-engineering/multi-agent-workflow-architect.md)

### 3. [Data & Technical Analysis Toolkit](./prompts/data-technical-analysis/)
Focus: Assessing the raw materials and technical constraints.
- [Data Readiness Scorecard](./prompts/data-technical-analysis/data-readiness-scorecard.md)
- [PII Discovery & Masking](./prompts/data-technical-analysis/pii-discovery-masking-auditor.md)
- [RAG Context Optimizer](./prompts/data-technical-analysis/rag-context-optimizer.md)

### 4. [Risk, Governance & Ethics Toolkit](./prompts/risk-governance-ethics/)
Focus: Compliance, safety, and organizational trust.
- [Ethical Bias Diagnostics](./prompts/risk-governance-ethics/ethical-bias-diagnostic-agent.md)
- [RAI Compliance Audit](./prompts/risk-governance-ethics/rai-compliance-audit-agent.md)
- [Incident Response Simulators](./prompts/risk-governance-ethics/incident-response-simulator.md)

### 5. [Change Management & Adoption Toolkit](./prompts/change-management-adoption/)
Focus: Implementation, reskilling, and stakeholder buy-in.
- [Stakeholder Empathy Mapping](./prompts/change-management-adoption/stakeholder-empathy-mapper.md)
- [AI Training Roadmaps](./prompts/change-management-adoption/ai-training-roadmap-architect.md)
- [Operational Readiness Checklists](./prompts/change-management-adoption/operational-readiness-checklist.md)

### 6. [Meta-BA Utilities Toolkit](./prompts/meta-ba-utilities/)
Focus: Speeding up your own BA work.
- [Meeting Summary to BRD](./prompts/meta-ba-utilities/meeting-summary-to-brd.md)
- [Interview Script Generators](./prompts/meta-ba-utilities/interview-script-generator.md)
- [Prompt Engineering Audits](./prompts/meta-ba-utilities/prompt-engineering-audit.md)

---

## 🛠 Required Tools
While most prompts work with any LLM, many **Skills** are optimized for use with:
- [Gemini CLI](https://github.com/google/gemini-cli)
- Python (Pandas, Scikit-learn)
- Mermaid.js (for visualization)
- JIRA / Confluence / Azure DevOps

---
Each toolkit directory contains its own `README.md` with detailed descriptions of available tools.
