# Security & Risk Governance Assessment

This assessment evaluates the maturity of Security & Risk Governance within a technology service.

The objective is security posture integrity, not compliance theater.

Score conservatively.  
Require evidence.  
Default to the lower level when uncertain.  

---

# Domain Purpose

Security & Risk Governance ensures the service maintains an appropriate security posture and that risk is identified, assessed, and governed proactively rather than discovered through incidents or audits.

A risk register that exists but is never reviewed is not governance.
Security discipline is measured by closure rates, not scan frequency.

---

# Level 1: Reactive

Security is informal and risk is discovered rather than managed.

Characteristics:

- No formal risk register, or one that exists but is not reviewed
- Vulnerability scanning absent or findings not tracked to closure
- Access controls undocumented and not periodically reviewed
- Compliance obligations mapped informally, if at all
- No dedicated security incident response playbook
- Vendor and third-party risk not formally assessed

Evidence Review:

- Does a risk register exist with owners and remediation timelines?
- Is vulnerability scanning in place with findings tracked to closure?
- Are access controls documented and reviewed on a defined cadence?
- Are compliance obligations mapped to specific controls?
- Does a security incident response playbook exist?

If most answers are "no," score Level 1.

---

# Level 2: Managed

Basic security structure exists but enforcement and coverage are incomplete.

Characteristics:

- Risk register exists with basic severity classification
- Vulnerability scanning in place; remediation SLAs defined but inconsistently enforced
- Access controls documented; periodic reviews introduced but not consistently completed
- Compliance obligations mapped to controls, though evidence is assembled reactively
- Security incident response playbook drafted
- Vendor risk assessment process introduced but not consistently applied

Evidence Review:

- Risk register reviewed on at least a monthly cadence
- Vulnerability scanning active with findings routed to owners
- Access review cadence defined and at least partially completed
- Compliance control mapping exists for primary obligations
- Security incident playbook present and accessible

If security structure exists but does not consistently drive remediation or prevent permission creep, score Level 2.

---

# Level 3: Optimized

Security is continuously governed, risk is tracked to closure, and compliance is maintained rather than assembled.

Characteristics:

- Risk register maintained with owners, severity, remediation timelines, and closure tracking
- Vulnerability scanning continuous with remediation SLAs enforced and escalation paths for breached SLAs
- Access reviews completed on a defined cadence with documented attestation and follow-through
- Compliance control mapping current with evidence maintained continuously
- Security requirements integrated into SDLC as Definition of Done criteria
- Vendor and third-party risk assessed before adoption and monitored ongoing
- Security incident response playbook tested and distinct from general operational response

Evidence Review:

- Risk register shows closure trend and current open items by severity
- Remediation SLA compliance rate tracked and reviewed monthly
- Access review completion rate documented with evidence of follow-through
- Compliance evidence accessible and current, not assembled before audits
- Security gate present in SDLC with enforcement evidence
- Vendor risk assessments completed for active third parties

If security governance measurably reduces exposure duration and maintains continuous audit readiness, score Level 3.

---

# Level 4: Proactive

Security posture is forecasted, threat modeling is continuous, and compliance is automated.

Characteristics:

- Continuous threat modeling actively informing architecture decisions
- Security posture measured and forecasted: attack surface trend, control effectiveness over time
- Compliance evidence collection and control monitoring automated
- Risk posture modeled under different threat scenarios
- Vendor risk monitored ongoing with automated alerting for posture changes

Evidence Review:

- Threat model updated on a continuous cadence and referenced in architecture decisions
- Security posture trend data reviewed in quarterly governance cadence
- Automated compliance evidence collection in place for primary controls
- Risk forecasting data available and reviewed by leadership
- Vendor risk monitoring automated with defined alert thresholds

If security decisions are anticipatory and posture is continuously measured and improved, score Level 4.

---

# Scoring Summary

| Level | Posture |
|-------|---------|
| 1 | Informal and discovery-driven |
| 2 | Structured but incompletely enforced |
| 3 | Continuously governed and audit-ready |
| 4 | Predictive and automated |

---

# Risk Considerations

Security & Risk Governance weaknesses often manifest as:

- Vulnerabilities aging without remediation while the risk register grows longer
- Permission creep creating excessive access that is never reviewed or revoked
- Compliance evidence assembled in a panic before each audit rather than maintained continuously
- Vendor and third-party risk introduced without assessment
- Security incidents handled ad hoc because no playbook exists
- Security debt accumulating silently until an incident forces visibility

Low maturity in this domain creates liability risk across Engineering Excellence, Portfolio Alignment, and Service Experience.

Security debt is uniquely expensive because it often surfaces through incidents and regulatory findings rather than internal reviews.

---

# Target Level & Improvement Plan

After scoring:

1. Document current level.
2. Define target level aligned to the service's data sensitivity, regulatory obligations, and risk exposure.
3. Identify the governance gaps with greatest risk or compliance exposure.
4. Assign accountable owner.
5. Define timeline for reassessment.

Reassess quarterly during active improvement periods.

---

# Final Reminder

A service can pass a point-in-time audit while maintaining poor security posture between audits. Compliance is not the same as security, and a scan is not the same as a remediation. Score honestly.
