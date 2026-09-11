# Architectural Integrity Assessment

This assessment evaluates the maturity of Architectural Integrity within a technology service.

The objective is architecture system health, not optimistic scoring.

Score conservatively.  
Require evidence.  
Default to the lower level when uncertain.

---

# Domain Purpose

Architectural Integrity ensures the service architecture remains scalable, maintainable, secure, and cost-efficient through explicit decision-making and active debt management.

Undocumented architecture is not a minor gap.  
It is risk distributed invisibly across every change the team makes.

---

# Level 1: Reactive

Architecture is informal, undocumented, or known only to specific individuals.

Characteristics:

- Architecture exists primarily in people's heads
- No ADR practice; decisions made without documented rationale
- Coupling is unmanaged and boundaries are unclear
- Non-functional requirements absent from delivery work
- Architectural debt untracked and not prioritized
- Platform and tooling choices made without governance
- Design reviews absent or informal

Evidence Review:

- Are architecture diagrams current and trusted by the team?
- Is there an ADR repository or equivalent decision log?
- Are ownership boundaries and interface contracts documented?
- Are NFRs included in delivery planning?
- Is architectural debt tracked as a backlog item?

If most answers are "no," score Level 1.

---

# Level 2: Managed

Basic architecture documentation and governance exist but are inconsistently maintained.

Characteristics:

- Architecture diagrams exist but may be outdated or incomplete
- ADR practice introduced for major decisions; coverage inconsistent
- Some ownership boundaries defined; interface contracts informal
- NFRs present in some delivery work but not consistently required
- Architectural debt identified but not formally scored or prioritized
- Platform and tooling choices governed informally

Evidence Review:

- Architecture diagrams exist and broadly reflect the current system
- ADRs present for recent major decisions
- Design review process exists with at least informal coverage of NFRs
- Architectural debt items present in backlog
- Dependency map exists, even if partially complete

If architecture structure exists but is not consistently maintained or enforced, score Level 2.

---

# Level 3: Optimized

Architecture is actively governed, debt is managed, and decisions are explicit.

Characteristics:

- Architecture diagrams current, trusted, and updated as changes are made
- ADR practice enforced for all material decisions with options and rationale documented
- Ownership boundaries and interface contracts defined and maintained
- NFRs explicitly required in delivery work and definitions of done
- Architectural debt register maintained with scoring, prioritization, and allocated capacity
- Platform and tooling choices governed; sprawl actively managed
- Design review checklist covers NFRs, coupling, operability, security, and cost

Evidence Review:

- Architecture diagrams reviewed on cadence and updated after material changes
- ADR repository indexed and populated for recent decisions
- Debt register shows scoring and active reduction work
- NFR coverage visible in delivery planning and done criteria
- Coupling hotspots identified and reduction work in progress
- Tooling and platform inventory maintained with consolidation targets

If architecture governance measurably reduces delivery friction and debt risk, score Level 3.

---

# Level 4: Proactive

Architecture health is continuously measured and complexity is actively governed as a resource.

Characteristics:

- Architecture health measured continuously using objective signals
- Risk propagation modeled; blast radius understood and actively reduced
- Performance, cost, and resilience optimization continuous rather than episodic
- Complexity treated as a managed resource with explicit budget and governance
- Interface contract versioning and deprecation governance fully operational
- Debt elimination systematic and measurably improving architecture health over time

Evidence Review:

- Architecture health metrics tracked and reviewed on governance cadence
- Blast radius analysis documented for critical components
- Continuous optimization work visible in roadmap and delivery allocation
- Complexity reduction measurable across debt index and coupling trends
- Deprecation and versioning governance operating without exceptions

If architecture risk is forecasted and complexity is governed as a first-class constraint, score Level 4.

---

# Scoring Summary

| Level | Posture |
|-------|---------|
| 1 | Undocumented and informally governed |
| 2 | Documented but inconsistently maintained |
| 3 | Actively governed and debt-managed |
| 4 | Continuously measured and complexity-governed |

---

# Risk Considerations

Architectural Integrity weaknesses often manifest as:

- Delivery slowdowns caused by tight coupling requiring broad coordination for narrow changes
- Incidents with large blast radius due to unmodeled risk propagation
- NFR failures discovered in production rather than during design
- Scaling events exposing unplanned capacity constraints
- Platform and tooling sprawl increasing operational burden and onboarding cost
- Interface changes breaking consumers without warning

Low maturity in this domain creates compounding risk across Operational Reliability, Value Execution, Security & Risk Governance, and Innovation & Modernization.

Architecture debt is uniquely expensive because it taxes every change made to the system.

---

# Target Level & Improvement Plan

After scoring:

1. Document current level.
2. Define target level (typically +1 from current).
3. Identify the architecture governance gaps with greatest delivery or reliability impact.
4. Assign accountable owner.
5. Define timeline for reassessment.

Reassess quarterly during active improvement periods.

---

# Final Reminder

A service can function for years on undocumented architecture. Functioning is not the same as being maintainable. Architectural Integrity determines whether the team controls the system or the system controls the team. Score honestly.