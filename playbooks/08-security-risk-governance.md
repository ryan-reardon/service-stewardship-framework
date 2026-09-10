# Security & Risk Governance Playbook

## Engineering Manager Guidance

------------------------------------------------------------------------

## 1. Domain Purpose

Ensure the service maintains an appropriate security posture and that risk is identified, assessed, and governed proactively rather than discovered through incidents or audits.

Security & Risk Governance keeps security integrated into how the service is run day to day. It is not a separate compliance exercise performed once a year, and it is not something owned solely by a central security team while engineering treats it as someone else's problem.

------------------------------------------------------------------------

## 2. What Success Looks Like (Level 3-4 Target State)

A service with mature security and risk governance demonstrates:

- Security requirements integrated into the SDLC and architecture decisions, not retrofitted after the fact
- A formal risk register with owners, severity, and remediation timelines
- Regular vulnerability scanning with defined remediation SLAs by severity
- Access controls that follow least privilege and are reviewed on a defined cadence
- Compliance obligations (for example SOX, SOC 2, GDPR, or FINRA where applicable) mapped to specific controls with evidence maintained continuously
- Security-specific incident response playbooks (breach, data exposure) distinct from general operational incident response
- Third-party and vendor risk assessed before onboarding and monitored on an ongoing basis

At Level 4 maturity:

- Threat modeling is continuous and actively informs architecture decisions rather than following them
- Security posture is measured and forecasted (attack surface trend, control effectiveness over time)
- Compliance evidence collection and control monitoring are automated rather than manually assembled before an audit

------------------------------------------------------------------------

## 3. Engineering Manager Responsibilities

- Maintain the risk register and ensure remediation is tracked through to closure, not just logged
- Ensure security requirements are part of Definition of Ready and Definition of Done (tie to Engineering Excellence)
- Own audit readiness for whichever compliance frameworks apply to the service
- Ensure access reviews occur on a defined cadence with real follow-through
- Escalate unremediated high-severity vulnerabilities and risk exceptions rather than letting them age silently
- Partner with Security, Compliance, and Legal on obligations and control design
- Ensure vendor and third-party risk assessments happen before adoption, not after

------------------------------------------------------------------------

## 4. Governance Model & Cadence

**Weekly:**
- Review open vulnerabilities and remediation SLA status
- Review any active security incidents

**Monthly:**
- Review the risk register
- Review access review completion status
- Review compliance control status

**Quarterly:**
- Refresh the formal risk assessment
- Review third-party and vendor risk
- Check audit readiness for applicable frameworks

**Annually:**
- Run the full compliance audit cycle where applicable
- Refresh the threat model
- Review overall security strategy

------------------------------------------------------------------------

## 5. Required Artifacts

- Risk register with owners, severity, remediation timelines, and status
- Vulnerability management dashboard and remediation SLA policy
- Access control matrix and review log
- Compliance control mapping (framework to control to evidence)
- Security incident response playbook
- Vendor and third-party risk assessment records
- Threat model documentation for critical components

------------------------------------------------------------------------

## 6. Operating Mechanisms

- Vulnerability scanning with remediation SLA enforcement by severity tier
- Risk scoring rubric (likelihood x impact) with defined escalation thresholds
- Access review cadence with attestation, not just a reminder that gets ignored
- Security requirements gate built into SDLC and change management
- Vendor risk intake process required before procurement or adoption
- Compliance evidence collection process, ideally automated rather than assembled reactively

------------------------------------------------------------------------

## 7. Common Failure Modes (Anti-Patterns)

- Vulnerabilities identified but remediation never tracked to closure
- Security treated as a gate at the end of development instead of a design constraint from the start
- Access grants accumulate without periodic review, creating permission creep
- Compliance treated as a once-a-year audit scramble rather than a continuous discipline
- A risk register that exists but is never reviewed or acted on
- Vendor risk left unassessed until a breach or audit finding forces the question
- Security incidents handled ad hoc without a dedicated playbook

------------------------------------------------------------------------

## 8. Maturity Advancement Roadmap

Level 1 → Reactive:
- Establish a basic risk register
- Implement vulnerability scanning
- Document the current access control baseline

Level 2 → Managed:
- Enforce remediation SLAs by severity
- Establish periodic access reviews
- Map compliance obligations to specific controls

Level 3 → Optimized:
- Integrate security requirements into SDLC gates
- Formalize vendor and third-party risk assessment
- Achieve consistent, evidenced audit readiness

Level 4 → Predictive & Autonomous:
- Run continuous threat modeling that informs architecture
- Automate compliance evidence collection and control monitoring
- Score risk predictively based on posture trends

------------------------------------------------------------------------

## 9. Monthly Metrics Dashboard

- Open vulnerabilities by severity and age
- Remediation SLA compliance rate
- Access review completion rate
- Risk register: open items by severity, overdue remediations
- Compliance control coverage and evidence completeness
- Security incidents (count, severity, time to contain)
- Vendor and third-party risk assessments completed vs. pending

------------------------------------------------------------------------

## 10. 90-Day Action Plan for a New Manager

**Days 1-30:**
- Inventory the current risk register, vulnerability backlog, and access controls
- Review compliance obligations applicable to the service
- Review vendor and third-party dependencies and any existing risk assessments
- Assess security incident response readiness
- Identify the highest-severity unremediated risks

**Days 31-60:**
- Establish or refresh the remediation SLA policy by severity
- Implement an access review cadence
- Close or create remediation plans for the top-severity risks
- Map compliance controls to evidence and identify gaps
- Draft or refresh the security incident response playbook

**Days 61-90:**
- Integrate security requirements into SDLC and change gates
- Formalize the vendor risk intake process
- Publish a risk and compliance scorecard
- Establish a quarterly risk review forum
- Set measurable targets for remediation SLA compliance and access review completion
