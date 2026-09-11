# Engineering Excellence Assessment

This assessment evaluates the maturity of Engineering Excellence within a technology service.

The objective is delivery system integrity, not aspirational scoring.

Score conservatively.  
Require evidence.  
Default to the lower level when uncertain.

---

# Domain Purpose

Engineering Excellence ensures the service is built, tested, deployed, and operated with consistent quality, security, and automation.

Standards without enforcement are aspirations.  
Engineering Excellence is what makes quality a system property rather than an individual habit.

---

# Level 1: Reactive

Engineering practices are informal or inconsistently applied.

Characteristics:

- Version control in use but peer review inconsistent or optional
- CI pipeline absent or rarely enforced
- Deployments manual, undocumented, or dependent on specific individuals
- Security reviews occur at the end of projects, if at all
- Infrastructure managed through consoles or ad hoc scripts
- Runbooks absent, outdated, or undiscoverable
- Toil accepted as a normal operational condition

Evidence Review:

- Is peer review mandatory and enforced by branch protections?
- Is a CI pipeline in place with quality gates?
- Are deployments documented and executable by anyone on the team?
- Is security scanning integrated into the pipeline?
- Is infrastructure managed as code?
- Do runbooks exist for critical operational procedures?

If most answers are "no," score Level 1.

---

# Level 2: Managed

Core engineering practices exist but enforcement and coverage are incomplete.

Characteristics:

- Version control and peer review required
- CI pipeline in place with basic tests and linting
- Deployment procedures documented but not fully automated
- Security scanning present but findings inconsistently remediated
- Some infrastructure managed as code; gaps remain
- Runbooks exist for major procedures but maintenance is uneven
- Toil identified but not systematically reduced

Evidence Review:

- Branch protections configured and enforced
- CI pipeline runs on all changes with test and lint gates
- Deployment runbook exists and is current
- Vulnerability scanner integrated; findings routed to owners
- IaC used for primary infrastructure components
- Runbook coverage exists for top operational scenarios

If engineering structure exists but does not consistently prevent failures or enforce quality, score Level 2.

---

# Level 3: Optimized

Engineering practices are enforced systematically and quality outcomes are measured.

Characteristics:

- Mandatory peer review with enforced branch protections and required approvals
- CI/CD pipelines enforce quality gates: coverage thresholds, static analysis, dependency and security scanning
- Deployments are automated with rollback readiness and post-deploy verification
- Secure SDLC controls integrated into pipeline and definition of done
- Infrastructure and configuration managed as code across all environments
- Toil register maintained; automation backlog actively worked
- Runbooks complete, current, and validated during incidents

Evidence Review:

- Pipeline configuration shows enforced quality gates with thresholds
- Change failure rate and deployment frequency tracked and reviewed
- Security scan results routed to owners with remediation SLAs
- IaC coverage extends to all primary environments
- Toil ratio tracked and automation coverage improving
- Runbook completeness verified post-incident or on cadence

If engineering discipline measurably improves deployment reliability and quality outcomes, score Level 3.

---

# Level 4: Proactive

Engineering posture is continuously measured, enforced by policy, and self-improving.

Characteristics:

- Policy-as-code enforces compliance before merge across all pipelines
- Self-healing automation handles common failure classes without human intervention
- Engineering quality and security posture continuously trended and forecasted
- Regression risk detected and blocked before production
- Toil effectively eliminated for routine operational classes
- Deployment safety is a system guarantee, not a team discipline

Evidence Review:

- Policy-as-code configurations active and audited
- Self-healing or auto-remediation in place for documented failure classes
- Quality and security trend data reviewed on governance cadence
- Toil ratio demonstrably low and stable
- Change failure rate consistently near zero
- Deployment frequency high relative to team size and service complexity

If engineering quality is enforced autonomously and posture is continuously improving, score Level 4.

---

# Scoring Summary

| Level | Posture |
|-------|---------|
| 1 | Informal and inconsistently applied |
| 2 | Structured but incompletely enforced |
| 3 | Systematically enforced and measured |
| 4 | Autonomous and continuously improving |

---

# Risk Considerations

Engineering Excellence weaknesses often manifest as:

- High change failure rates normalized over time
- Security vulnerabilities introduced through unscanned dependencies
- Deployments that only key individuals can safely execute
- Incident diagnosis hampered by missing or outdated runbooks
- Operational toil consuming capacity that should fund modernization
- Infrastructure drift between environments causing unreproducible failures

Low maturity in this domain creates compounding risk across Operational Reliability, Security & Risk Governance, and Innovation & Modernization.

Engineering debt accumulates silently and surfaces during incidents, not audits.

---

# Target Level & Improvement Plan

After scoring:

1. Document current level.
2. Define target level (typically +1 from current).
3. Identify the enforcement and automation gaps with greatest risk exposure.
4. Assign accountable owner.
5. Define timeline for reassessment.

Reassess quarterly during active improvement periods.

---

# Final Reminder

A team can follow good practices individually while the delivery system enforces nothing. Engineering Excellence determines whether quality and security are guaranteed by the system or dependent on individual discipline. Score honestly.
