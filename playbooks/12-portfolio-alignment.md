# Portfolio Alignment Playbook

## Engineering Manager Guidance

------------------------------------------------------------------------

## 1. Domain Purpose

Ensure the service's decisions, dependencies, and trade-offs are made with awareness of the broader service portfolio, avoiding duplicated capability, unmanaged cross-service risk, and misalignment with enterprise priorities.

Portfolio Alignment is the discipline of managing the service as part of a system of services, not in isolation. A service can be excellent on every other dimension and still be a liability if it duplicates capability another team already built, or if its dependencies create fragility no one has mapped.

------------------------------------------------------------------------

## 2. What Success Looks Like (Level 3-4 Target State)

A well-aligned service demonstrates:

- Upstream and downstream dependencies mapped and actively managed
- Shared capabilities identified and leveraged rather than duplicated
- Cross-service trade-offs made transparently with affected stakeholders
- Consolidation and rationalization opportunities actively and honestly evaluated
- Service priorities explicitly connected to enterprise and portfolio priorities
- Portfolio-level risk, such as concentration or single points of failure shared across services, made visible rather than discovered during an outage

At Level 4 maturity:

- Portfolio-level trade-offs are modeled and optimized across services rather than negotiated case by case
- Consolidation and rationalization decisions are data-driven and proactive
- Enterprise priority shifts are anticipated and incorporated into service planning early, rather than absorbed as surprises

------------------------------------------------------------------------

## 3. Engineering Manager Responsibilities

- Maintain an accurate map of service dependencies, both upstream and downstream
- Identify shared capabilities the service could leverage, or should offer to others
- Represent the service in portfolio-level planning and prioritization discussions
- Evaluate consolidation and rationalization opportunities honestly, including for this service itself
- Ensure cross-service trade-offs are negotiated transparently rather than imposed unilaterally
- Escalate portfolio-level risk, such as fragile shared dependencies, proactively
- Connect service roadmap decisions explicitly to enterprise priorities, tying back to Strategic Stewardship

------------------------------------------------------------------------

## 4. Governance Model & Cadence

**Weekly:**
- Track active cross-service dependency issues and risks

**Monthly:**
- Review the dependency map for accuracy
- Review shared capability opportunities

**Quarterly:**
- Conduct a portfolio alignment review with adjacent service owners and enterprise stakeholders
- Evaluate consolidation and rationalization opportunities

**Annually:**
- Conduct a full portfolio strategy alignment review tied to the Strategic Stewardship lifecycle review

------------------------------------------------------------------------

## 5. Required Artifacts

- Service dependency map covering upstream/downstream relationships, data flows, and shared infrastructure
- Shared capability inventory documenting what exists, what's duplicated, and what's missing
- Portfolio risk log covering concentration risk and single points of failure across services
- Cross-service trade-off decision log
- Consolidation and rationalization evaluation record
- Enterprise priority alignment statement

------------------------------------------------------------------------

## 6. Operating Mechanisms

- Dependency mapping and review process that stays current rather than being a one-time exercise
- Build-vs-reuse evaluation required before building new capability
- Cross-service trade-off negotiation forum involving affected teams
- Consolidation and rationalization evaluation criteria applied on a regular cadence
- Portfolio risk escalation path for concentration and single-point-of-failure risk

------------------------------------------------------------------------

## 7. Common Failure Modes (Anti-Patterns)

- Service dependencies known informally but never documented or reviewed
- Duplicate capabilities built across teams because nobody checked what already existed
- Cross-service trade-offs imposed unilaterally, damaging trust between teams
- Consolidation opportunities identified but never acted on due to political friction
- Portfolio-level risk, such as everyone depending on one fragile shared service, invisible until it fails
- Service roadmap set without any awareness of enterprise portfolio priorities

------------------------------------------------------------------------

## 8. Maturity Advancement Roadmap

Level 1 → Reactive:
- Document currently known dependencies
- Identify obvious duplicated capabilities
- Establish basic awareness of enterprise priorities

Level 2 → Managed:
- Formalize and maintain the dependency map
- Establish a build-vs-reuse evaluation before new capability development
- Create a portfolio risk log

Level 3 → Optimized:
- Conduct regular portfolio alignment reviews with adjacent teams
- Actively evaluate consolidation and rationalization opportunities
- Negotiate cross-service trade-offs transparently

Level 4 → Predictive & Autonomous:
- Model portfolio-level trade-offs and optimize across services
- Drive data-driven consolidation proactively
- Anticipate and incorporate enterprise priority shifts early

------------------------------------------------------------------------

## 9. Monthly Metrics Dashboard

- Dependency map accuracy and freshness
- Shared capability reuse rate vs. duplication instances
- Portfolio risk log: open items by severity
- Cross-service trade-off decisions logged and resolved
- Consolidation and rationalization opportunities identified vs. acted on
- Alignment status against enterprise priorities

------------------------------------------------------------------------

## 10. 90-Day Action Plan for a New Manager

**Days 1-30:**
- Map current service dependencies, both upstream and downstream
- Identify shared capabilities and potential duplication
- Review enterprise portfolio priorities and how this service connects to them
- Identify obvious portfolio-level risks, such as concentration or fragile shared dependencies
- Meet with adjacent service owners to understand cross-service pain points

**Days 31-60:**
- Formalize and publish the dependency map
- Establish the build-vs-reuse evaluation process
- Create a portfolio risk log and begin tracking
- Initiate cross-service trade-off discussions on known friction points
- Evaluate at least one consolidation or rationalization opportunity

**Days 61-90:**
- Publish a portfolio alignment summary and review cadence
- Establish a quarterly portfolio review forum with adjacent teams
- Set measurable targets for dependency map accuracy and risk reduction
- Formalize the cross-service trade-off negotiation process
- Connect the service roadmap explicitly to enterprise priorities in documentation
