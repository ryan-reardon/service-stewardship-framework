# The Service Stewardship Framework
**Version:** v1.5  
**Last Updated:** September 2026  

This framework defines the capabilities required for a technology
service to operate as a durable, scalable, secure, and value-generating
enterprise asset.


## Domain Table of Contents
Each domain represents a measurable management system.

1. [Strategic Stewardship](#1-strategic-stewardship) 
2. [Organizational Capability](#2-organizational-capability)
3. [Value Execution](#3-value-execution)
4. [Engineering Excellence](#4-engineering-excellence)
5. [Operational Reliability](#5-operational-reliability)
6. [Architectural Integrity](#6-architectural-integrity)
7. [Service Experience](#7-service-experience)
8. [Security & Risk Governance](#8-security--risk-governance)
9. [Financial Stewardship](#9-financial-stewardship)
10. [Observability & Intelligence](#10-observability--intelligence)
11. [Innovation & Modernization](#11-innovation--modernization)
12. [Portfolio Alignment](#12-portfolio-alignment)
---

## How to Use This Framework

The Service Stewardship Framework consists of five integrated components:

1. The 12 Domain Definitions (this document)
2. The 12 Playbooks (one for each domain)
3. The Domain Modules (deep operational guides)
4. The Maturity Model
5. The Assessment Questionnaire


### Recommended Usage Flow

1. Complete the consolidated assessment questionnaire.
2. Identify lowest-maturity or highest-risk domains.
3. Use the corresponding domain module to perform a deep-dive review.
4. Define improvement actions and target maturity.
5. Reassess quarterly.

See:
- [Maturity Model Overview](../maturity-model/README.md)
- [Assessment Questionnaire](../assessments/service-maturity-assessment.md)
- [How to Use Guide](../docs/how-to-use.md)

---

# 1. Strategic Stewardship

Purpose: Ensure the service exists for the right reasons, delivers
measurable value, and evolves intentionally across its lifecycle.

## Core Responsibilities

- Single accountable Service Executive for lifecycle health
- Documented 3-5 year roadmap aligned to enterprise objectives
- Defined customer segments and validated use cases
- Quantified business outcomes (revenue, risk, efficiency)
- Lifecycle stage classification (growth, scale, sustain, sunset)
- Annual strategic review and recalibration
- Explicit technical debt and modernization governance

## Key Metrics

- Adoption growth rate
- Customer satisfaction trend
- Roadmap execution percentage
- Capacity allocation (run/grow/modernize distribution)
- Cost-to-value ratio
- Technical debt trend
- Forecast vs actual delivery variance
- Investment mix distribution

**Domain Resources**

- [Domain Module](../modules/01-strategic-stewardship.md)
- [Assessment Module](../assessments/modules/01-strategic-stewardship-assessment.md)
- [Operational Playbook](../playbooks/01-strategic-stewardship.md)
------------------------------------------------------------------------

# 2. Organizational Capability

Purpose: Ensure sustainable team structure, skills, and accountability.

## Core Responsibilities

- Explicit RACI model
- Skills inventory mapped to roadmap
- Proactive skill gap management
- Succession planning for critical roles
- Role-based performance scorecards
- Cross-functional collaboration model

## Key Metrics

- Capacity allocation ratio (operate / improve / modernize)
- Single-threaded knowledge risk count
- Cross-training coverage percentage
- Role clarity survey index
- Incident resolution dependency concentration
- Attrition impact recovery time
- Skill gap closure rate
- Modernization velocity vs planned capacity

**Domain Resources**

- [Domain Module](../modules/02-organizational-capability.md)
- [Assessment Module](../assessments/modules/02-organizational-capability-assessment.md)
- [Operational Playbook](../playbooks/02-organizational-capability.md)
------------------------------------------------------------------------

# 3. Value Execution

Purpose: Deliver business value predictably and efficiently.

## Core Responsibilities

- Measurable outcomes defined pre-execution
- Prioritized backlog tied to business value
- Flow metrics actively managed
- Structured retrospectives with systemic fixes
- Capacity forecast model

## Key Metrics

- Lead time (idea to production)
- Cycle time (in-progress to done)
- Throughput (delivered items per sprint or month)
- Delivery predictability (percentage of commitments met)
- WIP and queue age health indicators
- Escaped scope rate (changes after commitment)
- Outcome realization rate (percentage of initiatives meeting success metrics)
- Dependency risk indicators (open dependencies, overdue handoffs)

**Domain Resources**

- [Domain Module](../modules/03-value-execution.md)
- [Assessment Module](../assessments/modules/03-value-execution-assessment.md)
- [Operational Playbook](../playbooks/03-value-execution.md)


------------------------------------------------------------------------

# 4. Engineering Excellence

Purpose: Build secure, automated, maintainable systems.

## Core Responsibilities

- Mandatory version control and peer review
- CI/CD with quality gates (coverage, static analysis, security scans)
- Infrastructure as Code enforcement
- Automated deployments and testing
- Secure SDLC adherence

## Key Metrics

- Deployment frequency
- Change failure rate
- Mean time to restore after a failed change
- Code coverage and test reliability trends
- Static analysis and security scan pass rate
- Vulnerability backlog age distribution
- Toil ratio and automation coverage ratio
- PR review latency and pipeline bypass rate

**Domain Resources**

- [Domain Module](../modules/04-engineering-excellence.md)
- [Assessment Module](../assessments/modules/04-engineering-excellence-assessment.md)
- [Operational Playbook](../playbooks/04-engineering-excellence.md)

------------------------------------------------------------------------

# 5. Operational Reliability

Purpose: Maintain availability and minimize operational risk.

## Core Responsibilities

- Defined SLAs and OLAs
- Error budgets enforced
- Blameless incident postmortems
- Change velocity tied to reliability posture
- Capacity forecasting and stress testing
- Automated remediation of recurring issues

## Key Metrics

- SLA and SLO attainment and variance trends
- Error budget remaining and burn rate
- Incident frequency and severity distribution
- Mean time to detect (MTTD) and mean time to restore (MTTR)
- Change failure rate and rollback rate
- Alert noise metrics: pages per incident and false positive rate
- Toil ratio and automation coverage
- Capacity utilization and headroom
- Top recurring incident classes and recurrence rate

**Domain Resources**

- [Domain Module](../modules/05-operational-reliability.md)
- [Assessment Module](../assessments/modules/05-operational-reliability-assessment.md)
- [Operational Playbook](../playbooks/05-operational-reliability.md)


------------------------------------------------------------------------

# 6. Architectural Integrity

Purpose: Optimize system design across functional and non-functional
criteria.

## Core Responsibilities

- Documented architecture and ADRs
- Explicit trade-off documentation
- Complexity minimization
- Modular, loosely coupled systems
- Scalability and resilience planning

## Key Metrics

- Architectural debt index and trend over time
- Coupling hotspots identified through qualitative and quantitative signals
- Service dependency risk indicators for critical upstream and downstream health
- Performance vs SLOs and available scaling headroom
- Change lead time attributable to architecture bottlenecks
- Platform and tool sprawl indicators: number of runtimes, frameworks, and data stores
- Incident blast radius indicators: scope of impact when failures occur

**Domain Resources**

- [Domain Module](../modules/06-architectural-integrity.md)
- [Assessment Module](../assessments/modules/06-architectural-integrity-assessment.md)
- [Operational Playbook](../playbooks/06-architectural-integrity.md)


------------------------------------------------------------------------

# 7. Service Experience

Purpose: Deliver professional and predictable customer interaction.

## Core Responsibilities

- Structured ticketing and escalation workflows
- Defined response and resolution targets
- Transparent communication standards
- Knowledge base and training materials
- Customer friction monitoring

## Key Metrics

- CSAT and NPS trend over time
- First response time by severity
- Time to resolution by severity
- Ticket backlog age distribution
- Ticket root-cause distribution: recurring versus novel issues
- Repeat issue rate: same root cause recurring across tickets
- Escalation rate and escalation aging
- Self-service deflection rate and knowledge base usage
- Documentation coverage and freshness indicators
- Incident and change communication timeliness
- Feedback-to-roadmap conversion rate
- Percentage of tickets with complete intake information


**Domain Resources**

- [Domain Module](../modules/07-service-experience.md)
- [Assessment Module](../assessments/modules/07-service-experience-assessment.md)
- [Operational Playbook](../playbooks/07-service-experience.md)


------------------------------------------------------------------------

# 8. Security & Risk Governance

Purpose: Reduce and govern security and compliance risk.

## Core Responsibilities

- Comprehensive dependency inventory
- Patch cadence enforcement
- Continuous vulnerability scanning
- Compliance documentation automation
- Supply chain surface minimization
- Segregation of duties enforcement

## Key Metrics

- Open vulnerabilities by severity and age
- Remediation SLA compliance rate by severity tier
- Access review completion rate
- Risk register: open items by severity, overdue remediations, and closure trend
- Compliance control coverage and evidence completeness
- Security incidents: count, severity, and time to contain
- Vendor and third-party risk assessments completed versus pending

**Domain Resources**

- [Domain Module](../modules/08-security-risk-governance.md)
- [Assessment Module](../assessments/modules/08-security-risk-governance-assessment.md)
- [Operational Playbook](../playbooks/08-security-risk-governance.md)


------------------------------------------------------------------------

# 9. Financial Stewardship

Purpose: Optimize total cost of ownership relative to delivered value.

## Core Responsibilities

- Full TCO model (infrastructure, labor, licensing, compliance)
- Cost per service unit tracking
- Run vs grow vs transform spend analysis
- Capacity-based cost forecasting
- Scenario modeling (growth, stress, decline)
- Infrastructure rightsizing and vendor optimization
- Lifecycle-aligned financial governance

## Key Metrics

- TCO trend, total and by category
- Budget versus actual variance with documented explanations
- Cost-to-value ratio trend
- Vendor and license utilization rate
- Cost optimization savings realized, cumulative
- Cost per unit where applicable: per transaction, user, or request
- Upcoming contract renewals and associated risk flags


**Domain Resources**

- [Domain Module](../modules/09-financial-stewardship.md)
- [Assessment Module](../assessments/modules/09-financial-stewardship-assessment.md)
- [Operational Playbook](../playbooks/09-financial-stewardship.md)


------------------------------------------------------------------------

# 10. Observability & Intelligence

Purpose: Convert telemetry into predictive operational and strategic
insight.

## Core Responsibilities

- Unified logs, metrics, and traces
- Standardized tagging and telemetry schema
- Business KPI alignment with technical metrics
- Alert governance and rationalization
- Capacity and SLA breach forecasting
- Executive dashboards with trend analysis

## Key Metrics

- Instrumentation coverage percentage across critical paths
- Alert volume and actionability rate
- Alert noise ratio: false positive rate
- Synthetic monitoring pass rate and detected issues count
- Dashboard usage and adoption by audience
- Leading indicator trend summary
- Mean time to detect trend over time

**Domain Resources**

- [Domain Module](../modules/10-observability-intelligence.md)
- [Assessment Module](../assessments/modules/10-observability-intelligence-assessment.md)
- [Operational Playbook](../playbooks/10-observability-intelligence.md)

------------------------------------------------------------------------

# 11. Innovation & Modernization

Purpose: Sustain long-term viability and prevent stagnation.

## Core Responsibilities

- Categorized technical debt register
- Dedicated modernization capacity allocation
- Structured experimentation framework
- Industry benchmarking reviews
- Legacy system retirement governance
- Obsolescence risk monitoring

## Key Metrics

- Modernization capacity allocated versus planned
- Legacy and aging component count and risk trend over time
- Modernization backlog age and throughput
- Experimentation and proof-of-concept count with outcomes: adopted, rejected, or ongoing
- Technology radar changes per quarter
- Modernization progress versus roadmap commitments

**Domain Resources**

- [Domain Module](../modules/11-innovation-modernization.md)
- [Assessment Module](../assessments/modules/11-innovation-modernization-assessment.md)
- [Operational Playbook](../playbooks/11-innovation-modernization.md)

------------------------------------------------------------------------

# 12. Portfolio Alignment

Purpose: Ensure coherence within the enterprise ecosystem.

## Core Responsibilities

- Enterprise architecture conformance tracking
- Dependency and integration mapping
- Cross-service SLA governance
- Redundancy avoidance and capability reuse promotion
- Systemic risk propagation modeling
- Portfolio-level reporting contribution

## Key Metrics

- Dependency map accuracy and freshness
- Shared capability reuse rate versus duplication instances
- Portfolio risk log: open items by severity
- Cross-service trade-off decisions logged and resolved
- Consolidation and rationalization opportunities identified versus acted on
- Alignment status against enterprise priorities

**Domain Resources**

- [Domain Module](../modules/12-portfolio-alignment.md)
- [Assessment Module](../assessments/modules/12-portfolio-alignment-assessment.md)
- [Operational Playbook](../playbooks/12-portfolio-alignment.md)


## Domain Interdependence

These domains operate as an integrated system:

 1. Strategic Stewardship sets direction.
 2. Organizational Capability enables execution.
 3. Value Execution delivers outcomes.
 4. Engineering Excellence builds quality.
 5. Operational Reliability sustains availability.
 6. Architectural Integrity ensures durability.
 7. Service Experience builds customer trust.
 8. Security & Risk Governance protects.
 9. Financial Stewardship sustains investment.
 10. Observability & Intelligence enables predictive maturity.
 11. Innovation & Modernization prevents stagnation.
 12. Portfolio Alignment prevents fragmentation.
 
