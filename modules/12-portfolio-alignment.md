# Portfolio Alignment

Portfolio Alignment ensures the service's decisions, dependencies, and trade-offs are made with awareness of the broader service portfolio, avoiding duplicated capability, unmanaged cross-service risk, and misalignment with enterprise priorities.

It is the discipline of continuously validating:

- Are upstream and downstream dependencies mapped, owned, and actively managed?
- Are shared capabilities leveraged rather than duplicated?
- Are cross-service trade-offs negotiated transparently, or imposed unilaterally?
- Is the service roadmap explicitly connected to enterprise portfolio priorities?

Portfolio Alignment transforms service ownership from isolated optimization into coherent participation in the enterprise ecosystem.

---

# 1. Domain Purpose

To ensure that:

- Upstream and downstream dependencies are mapped and actively managed.
- Shared capabilities are identified and leveraged rather than rebuilt.
- Cross-service trade-offs are made transparently with affected stakeholders.
- Consolidation and rationalization opportunities are actively and honestly evaluated.
- Service priorities are explicitly connected to enterprise and portfolio priorities.
- Portfolio-level risk, such as concentration risk and single points of failure shared across services, is made visible rather than discovered during outages.

Without Portfolio Alignment, a service can be excellent on every other dimension and still be a liability if it duplicates capability another team built, or if its dependencies create fragility no one has mapped.

---

# 2. Target State (Level 3–4 Characteristics)

A well-aligned service demonstrates:

- Upstream and downstream dependencies mapped and actively managed with ownership defined
- Shared capabilities identified and leveraged rather than duplicated across teams
- Cross-service trade-offs made transparently with affected stakeholders rather than imposed unilaterally
- Consolidation and rationalization opportunities actively and honestly evaluated, including for this service itself
- Service priorities explicitly connected to enterprise and portfolio priorities
- Portfolio-level risk made visible: concentration risk, single points of failure, and fragile shared dependencies

At higher maturity levels:

- Portfolio-level trade-offs are modeled and optimized across services rather than negotiated case by case
- Consolidation and rationalization decisions are data-driven and proactive
- Enterprise priority shifts are anticipated and incorporated into service planning early rather than absorbed as surprises

---

# 3. Core Responsibilities

Portfolio Alignment requires the Engineering Manager or Service Owner to:

- Maintain an accurate map of service dependencies, both upstream and downstream
- Identify shared capabilities the service could leverage, or should offer to others
- Represent the service in portfolio-level planning and prioritization discussions
- Evaluate consolidation and rationalization opportunities honestly, including for this service itself
- Ensure cross-service trade-offs are negotiated transparently rather than imposed unilaterally
- Escalate portfolio-level risk such as fragile shared dependencies proactively, not after they fail
- Connect service roadmap decisions explicitly to enterprise priorities

Ownership is measured by dependency transparency and portfolio risk reduction, not internal service performance alone.

---

# 4. Governance Model & Cadence

Portfolio Alignment operates on a defined cadence.

**Weekly**
- Track active cross-service dependency issues and risks

**Monthly**
- Review the dependency map for accuracy and completeness
- Review shared capability opportunities and current duplication

**Quarterly**
- Conduct a portfolio alignment review with adjacent service owners and enterprise stakeholders
- Evaluate consolidation and rationalization opportunities formally

**Annually**
- Conduct a full portfolio strategy alignment review tied to the Strategic Stewardship lifecycle review

Portfolio alignment that only occurs during major incidents or reorgs is coordination by crisis, not governance.

---

# 5. Required Artifacts

The following artifacts must exist and remain current:

- Service dependency map covering upstream and downstream relationships, data flows, and shared infrastructure
- Shared capability inventory documenting what exists, what is duplicated, and what is missing
- Portfolio risk log covering concentration risk and single points of failure across services
- Cross-service trade-off decision log with outcomes and affected stakeholders
- Consolidation and rationalization evaluation record with decisions and rationale
- Enterprise priority alignment statement connecting service roadmap to portfolio and enterprise priorities

Artifacts must reflect the current state of dependencies and portfolio relationships, not a snapshot from the last major planning cycle.

---

# 6. Operating Mechanisms

Portfolio Alignment relies on structured mechanisms:

- Dependency mapping and review process that stays current rather than being a one-time exercise
- Build-versus-reuse evaluation required before building new capability, with documented rationale when reuse is rejected
- Cross-service trade-off negotiation forum involving affected teams rather than unilateral decisions
- Consolidation and rationalization evaluation criteria applied on a regular cadence with documented outcomes
- Portfolio risk escalation path for concentration risk and single-point-of-failure risk before they materialize

These mechanisms keep the service from operating as an isolated system in an interconnected portfolio.

---

# 7. Key Metrics

Portfolio Alignment must be measurable.

Representative metrics include:

- Dependency map accuracy and freshness
- Shared capability reuse rate versus duplication instances
- Portfolio risk log: open items by severity
- Cross-service trade-off decisions logged and resolved
- Consolidation and rationalization opportunities identified versus acted on
- Alignment status against enterprise priorities

Metrics should surface portfolio risk and duplication before they create incidents or investment waste.

---

# 8. Leading Risk Indicators

Watch for:

- Service dependencies known informally but never documented or reviewed
- Duplicate capabilities built across teams because nobody checked what already existed
- Cross-service trade-offs imposed unilaterally, damaging trust between teams
- Consolidation opportunities identified but never acted on due to avoidance or political friction
- Portfolio-level risk, such as everyone depending on one fragile shared service, invisible until it fails
- Service roadmap set without any awareness of enterprise portfolio priorities

Portfolio dysfunction is often invisible inside the team and highly visible during incidents that cross service boundaries.

---

# 9. Maturity Progression Model

Portfolio Alignment evolves through staged progression:

**Level 1: Reactive**
- Currently known dependencies documented
- Obvious duplicated capabilities identified
- Basic awareness of enterprise priorities established

**Level 2: Managed**
- Dependency map formalized and maintained
- Build-versus-reuse evaluation established before new capability development
- Portfolio risk log created

**Level 3: Optimized**
- Regular portfolio alignment reviews conducted with adjacent teams
- Consolidation and rationalization opportunities actively evaluated
- Cross-service trade-offs negotiated transparently with affected stakeholders
- Portfolio risk log maintained with active remediation tracking

**Level 4: Proactive**
- Portfolio-level trade-offs modeled and optimized across services
- Data-driven consolidation driven proactively
- Enterprise priority shifts anticipated and incorporated early

Progression should be intentional and evidence-based.

---

# 10. Relationship to Other Domains

Portfolio Alignment depends on:

- Strategic Stewardship (enterprise priority alignment requires a clear service strategy to connect to portfolio priorities)
- Architectural Integrity (dependency mapping and interface contracts are architectural artifacts that Portfolio Alignment relies on)
- Observability & Intelligence (portfolio-level risk monitoring requires visibility into shared dependency health)

Portfolio Alignment enables:

- Operational Reliability (cross-service OLAs and dependency health reviews reduce systemic incident risk)
- Financial Stewardship (consolidation and rationalization decisions have financial implications that Portfolio Alignment surfaces)
- Security & Risk Governance (vendor and third-party risk and compliance obligations often extend across service boundaries)

Without Portfolio Alignment, services optimize locally while creating fragility and waste at the portfolio level.

---

# Summary

Portfolio Alignment determines whether the service contributes to or fragments the enterprise ecosystem. Local excellence does not compensate for portfolio-level fragility or redundancy. Durable alignment is built on current dependency maps, transparent trade-off negotiation, honest evaluation of consolidation opportunities, and a consistent commitment to connecting service decisions to the broader portfolio they operate within.
