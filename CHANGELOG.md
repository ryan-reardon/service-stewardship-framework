# Changelog

All releases of the Service Stewardship Framework are documented here.

Versioning follows a domain-release model. Each minor version adds one or more complete domain packages (domain module, assessment module, and operational playbook). Patch versions address corrections and formatting improvements.

---
## [v1.5] — September 2026

### Added

- **Domain 06: Architectural Integrity** — full domain package:
  - Domain Module (`modules/06-architectural-integrity.md`)
  - Assessment Module (`assessments/modules/06-architectural-integrity-assessment.md`)
  - Operational Playbook (`playbooks/06-architectural-integrity.md`)

### Domain Summary

Architectural Integrity defines how engineering managers prevent complexity from becoming the default outcome of growth and change through explicit decision-making, ADR governance, debt management, and platform discipline.


- **Domain 07: Service Experience** — full domain package:
  - Domain Module (`modules/07-service-experience.md`)
  - Assessment Module (`assessments/modules/07-service-experience-assessment.md`)
  - Operational Playbook (`playbooks/07-service-experience.md`)

### Domain Summary

Service Experience defines how engineering managers build a service that earns customer trust through measured satisfaction, proactive communication, self-service capability, and a direct connection between user feedback and roadmap decisions.


- **Domain 08: Security & Risk Governance** — full domain package:
  - Domain Module (`modules/08-security-risk-governance.md`)
  - Assessment Module (`assessments/modules/08-security-risk-governance-assessment.md`)
  - Operational Playbook (`playbooks/08-security-risk-governance.md`)

### Domain Summary

Security & Risk Governance defines how engineering managers integrate security into daily delivery and operations, maintaining continuous audit readiness, enforcing remediation discipline, and governing vendor and access risk proactively rather than reactively.


- **Domain 09: Financial Stewardship** — full domain package:
  - Domain Module (`modules/09-financial-stewardship.md`)
  - Assessment Module (`assessments/modules/09-financial-stewardship-assessment.md`)
  - Operational Playbook (`playbooks/09-financial-stewardship.md`)

### Domain Summary

Financial Stewardship defines how engineering managers maintain transparent, defensible cost management and ensure investment in the service remains proportionate to the value it delivers through continuous TCO visibility, vendor governance, and cost optimization discipline.


- **Domain 10: Observability & Intelligence** — full domain package:
  - Domain Module (`modules/10-observability-intelligence.md`)
  - Assessment Module (`assessments/modules/10-observability-intelligence-assessment.md`)
  - Operational Playbook (`playbooks/10-observability-intelligence.md`)

### Domain Summary

Observability & Intelligence defines how engineering managers build the sensory system that makes every other domain measurable, converting telemetry into high-signal detection, audience-appropriate dashboards, and evidence-based decisions across reliability, cost, and strategy.


- **Domain 11: Innovation & Modernization** — full domain package:
  - Domain Module (`modules/11-innovation-modernization.md`)
  - Assessment Module (`assessments/modules/11-innovation-modernization-assessment.md`)
  - Operational Playbook (`playbooks/11-innovation-modernization.md`)

### Domain Summary

Innovation & Modernization defines how engineering managers protect modernization capacity, reduce legacy risk systematically, and govern experimentation so that technical evolution is planned and funded work rather than crisis response.


- **Domain 12: Portfolio Alignment** — full domain package:
  - Domain Module (`modules/12-portfolio-alignment.md`)
  - Assessment Module (`assessments/modules/12-portfolio-alignment-assessment.md`)
  - Operational Playbook (`playbooks/12-portfolio-alignment.md`)

### Domain Summary

Portfolio Alignment defines how engineering managers ensure the service operates as a coherent participant in the enterprise ecosystem, managing dependencies transparently, avoiding duplicated capability, and connecting service decisions to portfolio and enterprise priorities.


---
## [v1.4] — March 2026

### Added

- **Domain 05: Operational Reliability** — full domain package:
  - Domain Module (`modules/05-operational-reliability.md`)
  - Assessment Module (`assessments/modules/05-operational-reliability-assessment.md`)
  - Operational Playbook (`playbooks/05-operational-reliability.md`)

### Domain Summary

Operational Reliability defines how engineering managers build a service that runs predictably, responds to incidents with structure, and systematically prevents recurrence through error budget governance, blameless postmortems, and proactive capacity planning.

---

## [v1.3] — March 2026

### Added

- **Domain 04: Engineering Excellence** — full domain package:
  - Domain Module (`modules/04-engineering-excellence.md`)
  - Assessment Module (`assessments/modules/04-engineering-excellence-assessment.md`)
  - Operational Playbook (`playbooks/04-engineering-excellence.md`)

### Fixed
  - Minor link updates and file name corrections
  
### Domain Summary

Engineering Excellence defines how engineering managers build a delivery system that enforces quality, security, and operational readiness as default outputs rather than individual disciplines.

The domain module covers the full operational model including purpose, target state, core responsibilities, governance cadence, required artifacts, operating mechanisms, key metrics, leading risk indicators, maturity progression, and domain relationships.

The assessment module provides level-by-level maturity evaluation with characteristics and evidence review criteria at each level (Reactive through Proactive), a scoring summary, risk considerations, and improvement planning guidance.

The operational playbook provides engineering manager guidance across all 10 sections including a 90-day action plan for new managers.

---

## [v1.2] — March 2026

### Added

- **Domain 03: Value Execution** — full domain package:
  - Domain Module (`modules/03-value-execution.md`)
  - Assessment Module (`assessments/modules/03-value-execution-assessment.md`)
  - Operational Playbook (`playbooks/03-value-execution.md`)

### Domain Summary

Value Execution defines how engineering managers convert strategy into measurable outcomes through disciplined prioritization, flow management, and explicit trade-off governance.

The domain module covers the full operational model: purpose, target state, core responsibilities, governance cadence, required artifacts, operating mechanisms, key metrics, leading risk indicators, maturity progression, and domain relationships.

The assessment module provides a level-by-level maturity evaluation framework with characteristics and evidence review criteria at each level (Reactive through Proactive), a scoring summary, risk considerations, and improvement planning guidance.

The operational playbook provides engineering manager guidance across all 10 sections including a 90-day action plan for new managers.

---

## [v1.1] — March 2026

### Added

- **Domain 02: Organizational Capability** — full domain package:
  - Domain Module (`modules/02-organizational-capability.md`)
  - Assessment Module (`assessments/modules/02-organizational-capability-assessment.md`)
  - Operational Playbook (`playbooks/02-organizational-capability.md`)

### Fixed

- Minor formatting corrections across framework documentation
- Link corrections in `docs/README.md` and `docs/framework.md`
- Replaced `docs/toc.md` with `docs/README.md` for improved repository navigation
- Wording updates across multiple documents for consistency

---

## [v1.0.1] — March 2026

### Fixed

- Resolved broken links in `README.md` and framework documentation

---

## [v1.0] — March 2026

### Added

Initial public release of the Service Stewardship Framework.

- **Framework definition** (`docs/framework.md`) — all 12 domain definitions with core responsibilities and key metrics
- **Introduction** (`docs/introduction.md`) — leadership philosophy and intent
- **How to Use guide** (`docs/how-to-use.md`) — operationalization guidance
- **Maturity Model** (`maturity-model/README.md`) — four-level progression model
- **Scoring Guidance** (`maturity-model/scoring-guidance.md`) — evidence-based scoring principles
- **Maturity Scoring Template** (`maturity-model/Maturity_Scoring_Template.xlsx`)
- **Consolidated Assessment Questionnaire** (`assessments/service-maturity-assessment.md`) — baseline evaluation across all 12 domains
- **Domain 01: Strategic Stewardship** — full domain package:
  - Domain Module (`modules/01-strategic-stewardship.md`)
  - Assessment Module (`assessments/modules/01-strategic-stewardship-assessment.md`)
  - Operational Playbook (`playbooks/01-strategic-stewardship.md`)
- Framework diagram (`docs/assets/framework-diagram.png`)
