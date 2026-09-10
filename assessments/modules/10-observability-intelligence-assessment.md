# Observability & Intelligence Assessment

This assessment evaluates the maturity of Observability & Intelligence within a technology service.

The objective is signal quality and decision support, not dashboard count.

Score conservatively.
Require evidence.
Default to the lower level when uncertain.

---

# Domain Purpose

Observability & Intelligence ensures the service has sufficient telemetry, monitoring, and alerting to understand its behavior, detect issues early, and support evidence-based decisions across every other domain.

A dashboard that nobody trusts is not observability.
Observability is the ability to explain what the service is doing and why.

---

# Level 1: Reactive

Instrumentation is reactive and observability is driven by incidents rather than design.

Characteristics:

- Monitoring covers only known failure modes discovered through past incidents
- Alerts configured but noisy, with low actionability and unclear ownership
- Dashboards exist but may be outdated, inaccurate, or unused
- No synthetic monitoring; user impact discovered through complaints
- Leading indicators absent; only lagging signals available
- Instrumentation added reactively after blind spots are exposed

Evidence Review:

- Does instrumentation coverage extend to critical paths proactively?
- Are alerts owned, actionable, and low-noise?
- Are dashboards current and used in operational decision-making?
- Is synthetic monitoring in place for key user journeys?
- Are leading indicators tracked?

If most answers are "no," score Level 1.

---

# Level 2: Managed

Basic observability structure exists but coverage, signal quality, and audience alignment are limited.

Characteristics:

- Monitoring covers primary components with some coverage of critical paths
- Alert rationalization begun: ownership assigned and top noise sources addressed
- Dashboards present and roughly accurate, though not audience-differentiated
- Synthetic monitoring introduced for at least top critical journeys
- Some leading indicators identified, though not formally tracked

Evidence Review:

- Instrumentation covers primary service components and critical paths
- Alert ownership documented for major alerts
- At least one active alert rationalization initiative
- Synthetic monitoring configured for top user journeys
- At least one leading indicator actively tracked

If observability structure exists but does not yet consistently support early detection or cross-domain decisions, score Level 2.

---

# Level 3: Optimized

Observability is proactively governed, signal quality is high, and telemetry actively informs decisions across domains.

Characteristics:

- Instrumentation coverage across critical paths for metrics, logs, and traces maintained as a delivery requirement
- Alerts high-signal, actionable, tied to real impact, and owned by named individuals
- Dashboards audience-differentiated for engineering, leadership, and business stakeholders with usage tracked
- Synthetic monitoring covering critical user journeys running independently of production traffic
- Leading indicators formally defined, tracked, and reviewed in governance cadence
- Instrumentation included in Definition of Done for new services and features
- Observability data informing decisions in Operational Reliability, Financial Stewardship, and Strategic Stewardship reviews

Evidence Review:

- Instrumentation coverage map current and reviewed on cadence
- Alert inventory maintained with actionability ratings and false positive rate tracked
- Dashboard catalog organized by audience with usage metrics
- Synthetic monitoring pass rate reviewed weekly
- Leading indicator trends presented in monthly and quarterly reviews
- Definition of Done includes instrumentation requirement with enforcement evidence

If observability governance measurably improves detection speed and informs cross-domain decisions, score Level 3.

---

# Level 4: Proactive

Observability is predictive, platform-agnostic, and continuously self-improving.

Characteristics:

- Anomaly detection and predictive alerting reducing time to detection ahead of user-visible impact
- Observability data feeding forecasting models for capacity, reliability, and adoption
- Instrumentation coverage and alert quality continuously measured and improved
- Platform-agnostic instrumentation design enforced with no critical signal lock-in to a single vendor
- Observability strategy reviewed on a defined cadence and aligned to evolving risk profile

Evidence Review:

- Predictive alerting or anomaly detection in active use with detection lead time tracked
- Forecasting models referencing observability data in capacity and reliability planning
- Alert quality trend improving continuously with false positive rate declining
- Instrumentation portability documented and verified
- Observability strategy reviewed quarterly with adjustments documented

If observability decisions are anticipatory and telemetry is continuously connected to decisions, score Level 4.

---

# Scoring Summary

| Level | Posture |
|-------|---------|
| 1 | Reactive and blind-spot-driven |
| 2 | Structured but coverage and quality limited |
| 3 | Proactively governed and decision-informing |
| 4 | Predictive and continuously self-improving |

---

# Risk Considerations

Observability & Intelligence weaknesses often manifest as:

- Incidents diagnosed through log archaeology and tribal knowledge rather than instrumented signals
- Alert fatigue causing real issues to be missed or deprioritized
- Dashboards that show green while production is degraded
- User impact discovered through customer complaints rather than synthetic monitoring
- Decisions in other domains made on opinion rather than evidence because telemetry is absent or untrustworthy
- Vendor lock-in for critical observability signal creating migration risk

Low maturity in this domain creates compounding risk across Operational Reliability, Financial Stewardship, and Strategic Stewardship.

Observability debt is invisible until an incident exposes a gap that should have been instrumented long before.

---

# Target Level & Improvement Plan

After scoring:

1. Document current level.
2. Define target level aligned to the service's criticality and decision support requirements.
3. Identify the coverage and signal quality gaps with greatest operational or strategic impact.
4. Assign accountable owner.
5. Define timeline for reassessment.

Reassess quarterly during active improvement periods.

---

# Final Reminder

A service can have many dashboards and still be unobservable. Observability is not measured by dashboard count or alert volume. It is measured by the ability to explain what the service is doing and why, and to detect issues before users report them. Score honestly.
