# Security & Risk Governance

Security & Risk Governance ensures the service maintains an appropriate security posture and that risk is identified, assessed, and governed proactively rather than discovered through incidents or audits.

It is the discipline of continuously validating:

- Are security requirements integrated into how the service is built and changed, not retrofitted after incidents?
- Is risk visible, owned, and tracked to closure rather than logged and forgotten?
- Are access controls enforced and reviewed, not accumulated and inherited?
- Is compliance maintained continuously, or assembled in a panic before each audit?

Security & Risk Governance transforms security from a periodic compliance event into an always-on engineering discipline.

---

# 1. Domain Purpose

To ensure that:

- Security requirements are integrated into the SDLC and architecture decisions, not added after the fact.
- A formal risk register exists with owners, severity, and remediation timelines that are tracked to closure.
- Vulnerability scanning is continuous with defined and enforced remediation SLAs by severity.
- Access controls follow least privilege and are reviewed on a defined cadence.
- Compliance obligations are mapped to specific controls with evidence maintained continuously.
- Security incident response is distinct from general operational response and rehearsed.
- Third-party and vendor risk is assessed before onboarding and monitored on an ongoing basis.

Without Security & Risk Governance, security is discovered through incidents and compliance is assembled through audits rather than maintained through discipline.

---

# 2. Target State (Level 3–4 Characteristics)

A secure and governed service demonstrates:

- Security requirements integrated into Definition of Ready and Definition of Done
- Formal risk register with owners, severity classifications, and remediation timelines reviewed on cadence
- Continuous vulnerability scanning with remediation SLAs enforced by severity tier
- Access controls following least privilege with access reviews completed on a defined schedule
- Compliance obligations mapped to specific controls with evidence maintained continuously, not assembled at audit time
- Security-specific incident response playbooks distinct from general operational incident response
- Third-party and vendor risk assessed before adoption and monitored ongoing

At higher maturity levels:

- Threat modeling is continuous and actively informs architecture decisions rather than following them
- Security posture is measured and forecasted: attack surface trend, control effectiveness over time
- Compliance evidence collection and control monitoring are automated rather than manually assembled

---

# 3. Core Responsibilities

Security & Risk Governance requires the Engineering Manager or Service Owner to:

- Maintain the risk register and ensure remediation is tracked to closure, not just logged
- Ensure security requirements are part of Definition of Ready and Definition of Done
- Own audit readiness for applicable compliance frameworks
- Ensure access reviews occur on a defined cadence with real follow-through, not just reminders
- Escalate unremediated high-severity vulnerabilities and risk exceptions rather than letting them age silently
- Partner with Security, Compliance, and Legal on obligations and control design
- Ensure vendor and third-party risk assessments occur before adoption, not after

Ownership is measured by remediation closure rates and audit readiness, not scan completion alone.

---

# 4. Governance Model & Cadence

Security & Risk Governance operates on a defined cadence.

**Weekly**
- Review open vulnerabilities and remediation SLA status
- Review any active security incidents

**Monthly**
- Review the risk register: open items, severity distribution, overdue remediations
- Review access review completion status
- Review compliance control status and evidence gaps

**Quarterly**
- Refresh the formal risk assessment
- Review third-party and vendor risk
- Check audit readiness for applicable frameworks

**Annually**
- Run the full compliance audit cycle where applicable
- Refresh the threat model for critical components
- Review overall security strategy and control effectiveness

Security governance that only activates before audits is not governance. It is audit preparation.

---

# 5. Required Artifacts

The following artifacts must exist and remain current:

- Risk register with owners, severity, remediation timelines, and current status
- Vulnerability management dashboard and remediation SLA policy by severity tier
- Access control matrix and access review log with completion history
- Compliance control mapping from framework obligations to controls to evidence
- Security incident response playbook distinct from general operational response
- Vendor and third-party risk assessment records
- Threat model documentation for critical components

Artifacts must be actively maintained, not assembled at audit time.

---

# 6. Operating Mechanisms

Security & Risk Governance relies on structured mechanisms:

- Vulnerability scanning with remediation SLA enforcement and escalation paths for breached SLAs by severity tier
- Risk scoring rubric using likelihood and impact with defined escalation thresholds for unacceptable exposure
- Access review cadence with attestation and follow-through, not reminders that get ignored
- Security requirements gate built into SDLC and change management as a Definition of Done criterion
- Vendor risk intake process required before procurement or adoption, not after
- Compliance evidence collection process, automated where feasible rather than assembled reactively

These mechanisms keep security integrated into delivery rather than bolted on at the end.

---

# 7. Key Metrics

Security & Risk Governance must be measurable.

Representative metrics include:

- Open vulnerabilities by severity and age
- Remediation SLA compliance rate by severity tier
- Access review completion rate
- Risk register: open items by severity, overdue remediations, and closure trend
- Compliance control coverage and evidence completeness
- Security incidents: count, severity, and time to contain
- Vendor and third-party risk assessments completed versus pending

Metrics should drive remediation prioritization and control improvement, not just posture reporting.

---

# 8. Leading Risk Indicators

Watch for:

- Vulnerabilities identified but remediation never tracked to closure
- Security treated as a gate at the end of development instead of a design constraint from the start
- Access grants accumulating without periodic review, creating permission creep
- Compliance treated as a once-a-year audit scramble rather than a continuous discipline
- A risk register that exists but is never reviewed or acted upon
- Vendor risk left unassessed until a breach or audit finding forces the question
- Security incidents handled ad hoc without a dedicated playbook

Security debt accumulates silently and surfaces through incidents and audit findings, not through internal reviews.

---

# 9. Maturity Progression Model

Security & Risk Governance evolves through staged progression:

**Level 1: Reactive**
- Basic risk register established
- Vulnerability scanning implemented
- Current access control baseline documented

**Level 2: Managed**
- Remediation SLAs enforced by severity tier
- Periodic access reviews established with completion tracking
- Compliance obligations mapped to specific controls

**Level 3: Optimized**
- Security requirements integrated into SDLC gates
- Vendor and third-party risk assessment formalized before adoption
- Consistent, evidenced audit readiness maintained continuously

**Level 4: Predictive**
- Continuous threat modeling informing architecture decisions
- Compliance evidence collection and control monitoring automated
- Risk posture measured and forecasted based on trend analysis

Progression should be intentional and evidence-based.

---

# 10. Relationship to Other Domains

Security & Risk Governance depends on:

- Engineering Excellence (secure SDLC controls, dependency scanning, and secrets management are engineering delivery requirements)
- Architectural Integrity (architecture decisions determine attack surface and blast radius)
- Observability & Intelligence (detecting security incidents requires instrumented systems with appropriate alerting)

Security & Risk Governance enables:

- Operational Reliability (security incident response is a reliability domain that requires its own playbooks and preparation)
- Value Execution (security requirements in Definition of Done prevent post-delivery remediation that erodes delivery predictability)
- Portfolio Alignment (vendor and third-party risk and compliance obligations extend across service boundaries)

Without Security & Risk Governance, security risk accumulates invisibly until an incident or audit makes it visible.

---

# Summary

Security & Risk Governance determines whether the service can be trusted with the data and access it holds. Periodic audits are not a substitute for continuous discipline. Durable security posture is built on risk registers that drive closure, access controls that are reviewed and enforced, compliance evidence that is maintained rather than assembled, and security requirements that are integrated into delivery rather than appended to it.
