# Portfolio Alignment Assessment

This assessment evaluates the maturity of Portfolio Alignment within a technology service.

The objective is portfolio coherence and dependency transparency, not internal service performance alone.

Score conservatively.  
Require evidence.  
Default to the lower level when uncertain.

---

# Domain Purpose

Portfolio Alignment ensures the service's decisions, dependencies, and trade-offs are made with awareness of the broader service portfolio, avoiding duplicated capability, unmanaged cross-service risk, and misalignment with enterprise priorities.

A service can be excellent in isolation and still be a liability in context.
Portfolio alignment is measured by what the service contributes to and costs the ecosystem around it.

---

# Level 1: Reactive

Dependencies are known informally and portfolio context is absent from service decisions.

Characteristics:

- Service dependencies undocumented or known only to specific individuals
- Shared capabilities not inventoried; duplication unknown
- Cross-service trade-offs made without involving affected teams
- No portfolio risk awareness; single points of failure and concentration risk invisible
- Service roadmap disconnected from enterprise portfolio priorities

Evidence Review:

- Are upstream and downstream dependencies documented with ownership?
- Is shared capability duplication known and tracked?
- Are cross-service trade-offs negotiated with affected teams?
- Is a portfolio risk log maintained?
- Is the service roadmap explicitly connected to enterprise priorities?

If most answers are "no," score Level 1.

---

# Level 2: Managed

Basic portfolio structure exists but dependency management and trade-off governance are limited.

Characteristics:

- Dependency map started with primary upstream and downstream relationships documented
- Shared capability inventory introduced with initial duplication identification
- Build-versus-reuse evaluation introduced for new capability development
- Portfolio risk log created with initial risk items documented
- Some awareness of enterprise priorities, though connection to roadmap is informal

Evidence Review:

- Dependency map exists and covers primary service relationships
- Shared capability inventory present with at least obvious duplication identified
- At least one build-versus-reuse evaluation documented in the past quarter
- Portfolio risk log exists with initial items
- Enterprise priority alignment referenced in at least one roadmap discussion

If portfolio structure exists but dependency management and trade-off governance are inconsistent, score Level 2.

---

# Level 3: Optimized

Portfolio alignment is actively governed, dependencies are transparent, and cross-service trade-offs are negotiated rather than imposed.

Characteristics:

- Dependency map current, reviewed monthly, and covering upstream, downstream, data flows, and shared infrastructure
- Shared capability inventory maintained with reuse tracked and duplication actively addressed
- Build-versus-reuse evaluation required before new capability development with documented rationale
- Portfolio risk log maintained with severity ratings and active remediation tracking
- Cross-service trade-offs negotiated transparently with affected stakeholders and outcomes logged
- Consolidation and rationalization opportunities evaluated on a quarterly cadence
- Service roadmap explicitly connected to enterprise portfolio priorities in documentation

Evidence Review:

- Dependency map reviewed in the last month with accuracy confirmed
- Shared capability reuse rate tracked with duplication reduction trend
- Build-versus-reuse evaluations documented for recent capability decisions
- Portfolio risk log shows severity ratings and remediation progress
- Cross-service trade-off decision log present with resolved and open items
- Consolidation opportunities evaluated in the last quarter with documented outcomes
- Enterprise alignment statement current and referenced in planning

If portfolio governance measurably reduces duplication and surfaces portfolio risk proactively, score Level 3.

---

# Level 4: Proactive

Portfolio trade-offs are modeled across services, consolidation is data-driven, and enterprise shifts are anticipated.

Characteristics:

- Portfolio-level trade-offs modeled and optimized across services rather than negotiated case by case
- Consolidation and rationalization decisions data-driven and proactive rather than reactive to incidents or pressure
- Enterprise priority shifts anticipated and incorporated into service planning early
- Portfolio risk trend declining with concentration risk actively reduced
- Dependency health monitored continuously with automated alerting for degradation

Evidence Review:

- Portfolio trade-off modeling documented and referenced in cross-service planning
- Data-driven consolidation decisions completed in the past year with documented rationale
- Enterprise priority integration evident in planning artifacts before shifts were announced
- Portfolio risk log trend declining with remediation outpacing new risk introduction
- Automated dependency health monitoring in place with alerting configured

If portfolio decisions are anticipatory and trade-offs are optimized across service boundaries, score Level 4.

---

# Scoring Summary

| Level | Posture |
|-------|---------|
| 1 | Isolated and dependency-blind |
| 2 | Structured but inconsistently governed |
| 3 | Actively aligned and trade-off transparent |
| 4 | Predictive and portfolio-optimized |

---

# Risk Considerations

Portfolio Alignment weaknesses often manifest as:

- Cross-service outages caused by undocumented dependencies nobody knew to monitor
- Duplicate capabilities consuming investment across multiple teams for the same function
- Cross-service trade-offs creating trust damage between teams when imposed without negotiation
- Portfolio-level concentration risk invisible until a shared dependency fails and takes multiple services with it
- Consolidation opportunities identified but never acted on, leaving redundancy permanently in place
- Service roadmap decisions creating enterprise misalignment that is discovered too late to correct

Low maturity in this domain creates systemic risk that individual service excellence cannot compensate for.

Portfolio dysfunction is often invisible inside the team and highly visible during incidents that cross service boundaries.

---

# Target Level & Improvement Plan

After scoring:

1. Document current level.
2. Define target level aligned to the service's portfolio interconnectedness and enterprise governance requirements.
3. Identify the dependency transparency and trade-off governance gaps with greatest portfolio risk.
4. Assign accountable owner.
5. Define timeline for reassessment.

Reassess quarterly during active improvement periods.

---

# Final Reminder

A service optimized in isolation can still be a liability at the portfolio level. Dependencies that are not mapped cannot be managed. Trade-offs that are not negotiated create resentment. Consolidation opportunities that are not evaluated create waste. Score honestly.
