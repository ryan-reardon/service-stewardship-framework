# The Service Stewardship Framework

![Service Stewardship Framework](docs/assets/framework-diagram.png)
**Version:** v1.5  
**Last Updated:** September 2026  


---
## Who This Is For

- Engineering Managers responsible for long-lived services
- Platform and SRE leaders
- Technology executives governing reliability-critical systems

## Overview

The Service Stewardship Framework defines what it truly means to own and evolve a technology service responsibly.

In many organizations, service ownership is implied but rarely defined. Engineering managers are expected to “own the service,” yet ownership often defaults to uptime, incident response, and backlog management.

This framework expands that definition.

It establishes a structured, multidimensional model for stewarding services across strategy, delivery, reliability, architecture, security, finance, and organizational capability.

The goal is practical leadership, not theory.

## What Makes This Different

This framework is:
- Multidimensional, not uptime-focused
- Governance-oriented, not documentation-driven
- Evidence-based, not aspirational
- Designed for long-lived enterprise services

---

## Start Here

If you are new to the framework, follow this recommended reading order:

1. [Introduction](docs/introduction.md)  
   Understand the leadership philosophy and intent behind the model.

2. [Framework Definition](docs/framework.md)  
   Review the 12 domains and their core responsibilities.

3. [Maturity Model](maturity-model/README.md)  
   Understand the four-level progression model.

4. [Assessment Questionnaire](assessments/service-maturity-assessment.md)  
   Establish your baseline maturity score.

5. [How to Use Guide](docs/how-to-use.md)  
   Learn how to operationalize the framework in practice.

6. [Operational Playbooks](playbooks/)  
   Apply domain-level practices and governance cadence.

---

## The 12 Domains of Service Stewardship

The framework organizes service ownership into twelve interconnected domains:

| # | Domain | Definition | Module | Assessment | Playbook |
|---|--------|------------|--------|------------|----------|
| 1 | Strategic Stewardship | [Definition](docs/framework.md#1-strategic-stewardship) | [Module](modules/01-strategic-stewardship.md) | [Assessment](assessments/modules/01-strategic-stewardship-assessment.md) | [Playbook](playbooks/01-strategic-stewardship.md) |
| 2 | Organizational Capability | [Definition](docs/framework.md#2-organizational-capability) | [Module](modules/02-organizational-capability.md) | [Assessment](assessments/modules/02-organizational-capability-assessment.md) | [Playbook](playbooks/02-organizational-capability.md) |
| 3 | Value Execution | [Definition](docs/framework.md#3-value-execution) | [Module](modules/03-value-execution.md) | [Assessment](assessments/modules/03-value-execution-assessment.md) | [Playbook](playbooks/03-value-execution.md) |
| 4 | Engineering Excellence | [Definition](docs/framework.md#4-engineering-excellence) | [Module](modules/04-engineering-excellence.md) | [Assessment](assessments/modules/04-engineering-excellence-assessment.md) | [Playbook](playbooks/04-engineering-excellence.md) |
| 5 | Operational Reliability | [Definition](docs/framework.md#5-operational-reliability) | [Module](modules/05-operational-reliability.md) | [Assessment](assessments/modules/05-operational-reliability-assessment.md) | [Playbook](playbooks/05-operational-reliability.md) |
| 6 | Architectural Integrity | [Definition](docs/framework.md#6-architectural-integrity) | [Module](modules/06-architectural-integrity.md) | [Assessment](assessments/modules/06-architectural-integrity-assessment.md) | [Playbook](playbooks/06-architectural-integrity.md) |
| 7 | Service Experience | [Definition](docs/framework.md#7-service-experience) | [Module](modules/07-service-experience.md) | [Assessment](assessments/modules/07-service-experience-assessment.md) | [Playbook](playbooks/07-service-experience.md) |
| 8 | Security & Risk Governance | [Definition](docs/framework.md#8-security--risk-governance) | [Module](modules/08-security-risk-governance.md) | [Assessment](assessments/modules/08-security-risk-governance-assessment.md) | [Playbook](playbooks/08-security-risk-governance.md) |
| 9 | Financial Stewardship | [Definition](docs/framework.md#9-financial-stewardship) | [Module](modules/09-financial-stewardship.md) | [Assessment](assessments/modules/09-financial-stewardship-assessment.md) | [Playbook](playbooks/09-financial-stewardship.md) |
| 10 | Observability & Intelligence | [Definition](docs/framework.md#10-observability--intelligence) | [Module](modules/10-observability-intelligence.md) | [Assessment](assessments/modules/10-observability-intelligence-assessment.md) | [Playbook](playbooks/10-observability-intelligence.md) |
| 11 | Innovation & Modernization | [Definition](docs/framework.md#11-innovation--modernization) | [Module](modules/11-innovation-modernization.md) | [Assessment](assessments/modules/11-innovation-modernization-assessment.md) | [Playbook](playbooks/11-innovation-modernization.md) |
| 12 | Portfolio Alignment | [Definition](docs/framework.md#12-portfolio-alignment) | [Module](modules/12-portfolio-alignment.md) | [Assessment](assessments/modules/12-portfolio-alignment-assessment.md) | [Playbook](playbooks/12-portfolio-alignment.md) |

Each domain defines:

- Core responsibilities  
- Key metrics  
- Governance expectations  
- Required artifacts  
- Maturity progression  

Together, they form a complete operating model for durable service ownership.

See full definitions here:\
[Framework Definition](docs/framework.md)

---

## Maturity Model

The framework embeds a four-level maturity progression:

- **Level 1: Reactive**
- **Level 2: Managed**
- **Level 3: Optimized**
- **Level 4: Proactive**

Progression is evidence-based and staged.  

The maturity model allows leaders to:

- Diagnose current state honestly  
- Identify structural gaps  
- Prioritize investment intentionally  
- Track measurable improvement over time  

See full details here:
[Maturity Model Overview](maturity-model/README.md)

---

## Assessment & Domain Modules

The framework includes structured instruments for evaluation and improvement.

### Assessment

Use the consolidated questionnaire to baseline maturity across all domains:

[Service Maturity Assessment](assessments/service-maturity-assessment.md)

### Domain Modules

Each domain includes a deep-dive operational guide that provides:

- Detailed expectations  
- Governance cadence  
- Implementation guidance  
- Evidence requirements  
- Improvement pathways  

Explore domain modules in:

[Modules Directory](modules/)

### Operational Playbooks

Each domain also has a playbook translating expectations into governance cadence and recurring practice:

[Playbooks Directory](playbooks/)

---

## How to Operationalize the Framework

This framework is designed to be applied, not archived.

Use it to:

- Conduct structured service reviews  
- Identify systemic risk exposure  
- Align roadmap investment to value  
- Improve cross-functional governance  
- Strengthen organizational capability  

Step-by-step guidance is available here:

[How to Use the Framework](docs/how-to-use.md)

## Repository Navigation

- Framework overview: [docs/framework.md](docs/framework.md)
- Documentation index: [docs/README.md](docs/README.md)
- Domain modules: [modules/](modules/)
- Operational playbooks: [playbooks/](playbooks/)
- Consolidated assessment: [assessments/service-maturity-assessment.md](assessments/service-maturity-assessment.md)
- Assessment modules: [assessments/modules/](assessments/modules/)
- Maturity model: [maturity-model/](maturity-model/)
- Scoring guidance: [maturity-model/scoring-guidance.md](maturity-model/scoring-guidance.md)
- Change history: [CHANGELOG.md](CHANGELOG.md)