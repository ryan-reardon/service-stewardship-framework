# Operational Reliability Assessment

This assessment evaluates the maturity of Operational Reliability within a technology service.

The objective is reliability system integrity, not optimistic scoring.

Score conservatively.  
Require evidence.  
Default to the lower level when uncertain.

---

# Domain Purpose

Operational Reliability ensures the service runs predictably, responds to incidents with structure, and systematically prevents recurrence.

Heroic incident response is not reliability.  
Systematic prevention is.

---

# Level 1: Reactive

Reliability is informal and incident-driven.

Characteristics:

- SLAs absent or defined informally with no measurement
- No SLOs or error budgets defined
- Incident response ad hoc and dependent on specific individuals
- Postmortems absent or inconsistently performed
- Monitoring and alerting incomplete or unreliable
- Capacity planning reactive to outages, not proactive
- Operational work unplanned and absorbed outside working hours

Evidence Review:

- Are SLAs documented and measured?
- Are SLOs and error budgets defined?
- Is incident response structured with clear roles and communications?
- Are postmortems performed and action items tracked?
- Is monitoring coverage sufficient for critical service paths?
- Is capacity proactively planned?

If most answers are "no," score Level 1.

---

# Level 2: Managed

Basic reliability structure exists but governance is limited.

Characteristics:

- SLAs documented with some measurement in place
- SLOs defined but error budgets not yet enforced
- Incident response roles established; postmortems performed inconsistently
- Postmortem actions tracked informally or incompletely
- Monitoring in place for primary components; gaps exist
- Capacity baselines established with informal review
- Toil present but not systematically measured or reduced

Evidence Review:

- SLA documentation exists and attainment is tracked
- SLOs defined for primary service outcomes
- Incident response runbook exists with role definitions
- Postmortems performed after significant incidents
- Basic monitoring and alerting in place for critical paths
- Capacity baselines documented

If reliability structure exists but does not consistently prevent recurrence or inform change decisions, score Level 2.

---

# Level 3: Optimized

Reliability is governed, measured, and actively improving.

Characteristics:

- SLAs, SLOs, and OLAs documented with owners and review cadence
- Error budgets defined, measured, and actively used to govern change velocity
- Structured, blameless incident management with tracked postmortem actions
- Root cause remediation prioritized and delivered, not just logged
- Monitoring and alerting high-signal and low-noise; blind spots actively closed
- Capacity forecasting proactive and integrated into planning
- Operational work explicitly planned and capacity-protected
- Toil register maintained and automation backlog actively worked

Evidence Review:

- SLO attainment and error budget dashboards exist and are reviewed on cadence
- Error budget policy documented with defined consequences
- Postmortem action log shows completion and recurrence checks
- Alert rationalization work documented with false positive reduction trend
- Capacity forecast updated regularly and reviewed in governance cadence
- Toil ratio tracked and automation coverage improving

If reliability governance measurably reduces incident frequency and improves recovery outcomes, score Level 3.

---

# Level 4: Proactive

Reliability risk is forecasted and failure classes are systematically eliminated.

Characteristics:

- SLA breach prediction and capacity models in active use
- Auto-remediation implemented for common failure classes
- Change governance dynamically adapts based on error budget state
- Reliability investments tied to forecasted risk reduction with measurable outcomes
- Operational work largely automated; on-call burden low and sustainable
- Reliability posture continuously trended and reviewed at leadership level

Evidence Review:

- Predictive models for capacity or SLA breach in use and validated
- Auto-remediation configured and operating for documented failure classes
- Change policy demonstrably adjusts based on error budget state
- Reliability investment roadmap tied to measurable risk reduction
- On-call metrics show sustainable load and low toil ratio
- Reliability trend data reviewed in quarterly governance cadence

If reliability decisions are anticipatory and failure classes are systematically eliminated, score Level 4.

---

# Scoring Summary

| Level | Posture |
|-------|---------|
| 1 | Reactive and hero-dependent |
| 2 | Structured but inconsistently governed |
| 3 | Measured and actively improving |
| 4 | Predictive and systematically self-improving |

---

# Risk Considerations

Operational Reliability weaknesses often manifest as:

- Recurring incidents from the same root causes
- On-call burnout from unplanned operational load
- SLAs breached without detection or consequence
- Change-induced outages from ungoverned deployment practices
- Capacity saturation causing avoidable performance degradation
- Postmortems completed but prevention work never prioritized

Low maturity in this domain creates direct customer impact and compounds risk across Service Experience, Financial Stewardship, and Portfolio Alignment.

Reliability debt is the most visible form of technical debt to customers.

---

# Target Level & Improvement Plan

After scoring:

1. Document current level.
2. Define target level (aligned to service criticality and customer commitments).
3. Identify the reliability governance gaps with greatest customer or operational risk.
4. Assign accountable owner.
5. Define timeline for reassessment.

Reassess quarterly during active improvement periods.

---

# Final Reminder

A service can survive incidents while failing at reliability. Surviving is not the same as being reliable. Operational Reliability determines whether the service can be trusted to perform consistently over time. Score honestly.
