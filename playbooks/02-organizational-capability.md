# Organizational Capability Playbook

## Engineering Manager Guidance

------------------------------------------------------------------------

## 1. Domain Purpose

Build and sustain a resilient, high-performing engineering organization
that can deliver outcomes reliably **without heroics**.

Organizational Capability is the system of structures, roles, skills,
and development mechanisms that make performance repeatable across time,
turnover, and changing business demand.

------------------------------------------------------------------------

## 2. What Success Looks Like (Level 3--4 Target State)

A capable organization demonstrates:

-   Clear team mandate and service boundaries (who we serve, what we
    own, what we don't)
-   Explicit role clarity (accountabilities, expectations, decision
    rights)
-   A skills inventory mapped to the service roadmap and operational
    needs
-   Sufficient redundancy for critical operational functions (no single
    points of human failure)
-   Consistent performance management with coaching, feedback, and
    growth plans
-   Predictable on-call health and sustainable operational load
-   Effective collaboration mechanisms with upstream/downstream teams
-   Hiring and staffing plans based on forecasted demand, not
    crisis-driven reactions

At Level 4 maturity: - Workforce planning uses demand forecasting and
scenario modeling - Skills gaps are predicted and addressed before
delivery or operational impact - Org design and team topology are
iteratively optimized using performance and flow analytics

------------------------------------------------------------------------

## 3. Engineering Manager Responsibilities

-   Define and communicate the team's mandate, boundaries, and ownership
    model
-   Establish and maintain role clarity, including expectations for
    senior and staff engineers
-   Build and maintain a skills matrix aligned to:
    -   roadmap initiatives
    -   operational responsibilities (incident response, reliability
        work)
    -   security and compliance responsibilities
-   Identify capability gaps (skills, process, tooling, staffing) and
    build plans to close them
-   Run an explicit system for growth:
    -   career ladders / role expectations
    -   regular feedback loops
    -   growth plans for each team member
-   Create resiliency in people systems:
    -   reduce single points of knowledge
    -   enforce cross-training
    -   ensure rotation through critical domains (ops, delivery,
        architecture)
-   Maintain sustainable operational load:
    -   manage toil
    -   manage on-call health
    -   escalate resourcing gaps early
-   Build strong interfaces to partner teams (SRE, Security, Product,
    Support, Finance)

------------------------------------------------------------------------

## 4. Governance Model & Cadence

Weekly: - Staffing and operational load check (toil hotspots, on-call
stress indicators) - Hiring pipeline review (if actively hiring)

Monthly: - Skills and coverage review (current vs near-term roadmap
needs) - Team health pulse (engagement indicators, burnout signals) -
Performance calibration check (are expectations clear and consistent?)

Quarterly: - Succession and redundancy review for critical roles -
Skills strategy refresh tied to roadmap changes - Org design review
(team topology and boundaries)

Semi-annually: - Talent review and development planning (promotions,
growth plans, retention risks)

------------------------------------------------------------------------

## 5. Required Artifacts

-   Team charter / mandate statement
-   Ownership boundaries and RACI (including cross-team
    responsibilities)
-   Role definitions and expectations (including senior/staff scope)
-   Skills matrix mapped to roadmap and ops needs
-   On-call model and rotation documentation
-   Cross-training plan and tracking
-   Hiring plan (when applicable)
-   Succession plan for critical responsibilities
-   Team health action log (burnout/toil reduction actions)

------------------------------------------------------------------------

## 6. Operating Mechanisms

-   Skills-to-roadmap mapping: explicitly link roadmap initiatives to
    required competencies
-   Capacity protection: reserve capacity for:
    -   operations and reliability work
    -   security work
    -   modernization / debt reduction
-   Knowledge distribution mechanisms:
    -   paired ownership, rotation, internal tech talks
    -   "bus factor" reviews for critical areas
-   Coaching rhythm:
    -   recurring 1:1s
    -   regular feedback cycles
    -   quarterly growth planning
-   Sustainable operations mechanism:
    -   toil register
    -   work item taxonomy separating toil vs feature vs reliability vs
        security
-   Collaboration mechanisms:
    -   interface contracts with partner teams
    -   escalation expectations and response norms

------------------------------------------------------------------------

## 7. Common Failure Modes (Anti-Patterns)

-   "Everyone owns it" (meaning nobody owns it)
-   Role ambiguity leading to duplicated work or dropped
    responsibilities
-   Hiring only after incidents or delivery failure
-   One "go-to person" for every critical area (bus factor = 1)
-   On-call treated as punishment rather than an engineered
    responsibility
-   Performance management avoided until crisis (late feedback)
-   Skill silos ("only one person knows X")
-   Team capacity fully consumed by delivery, leaving no room for
    reliability/security/debt

------------------------------------------------------------------------

## 8. Maturity Advancement Roadmap

Level 1 → Reactive: - Establish team charter and ownership boundaries -
Document on-call model and critical responsibilities - Create initial
skills inventory and identify gaps

Level 2 → Managed: - Implement role expectations and consistent coaching
rhythm - Build cross-training plan for critical areas - Establish hiring
and resourcing plan tied to demand

Level 3 → Optimized: - Map skills to roadmap and operational needs -
Actively manage toil and on-call health - Formalize succession planning
and redundancy requirements

Level 4 → Predictive & Autonomous: - Use forecasting to plan staffing
and skill development - Continuously refine org design using flow,
reliability, and engagement analytics - Predict and prevent capability
gaps through early hiring/upskilling

------------------------------------------------------------------------

## 9. Monthly Metrics Dashboard

-   Skills coverage ratio (required vs available for roadmap + ops)
-   Bus factor for critical components/processes (target \> 2)
-   On-call health indicators (pages per person, after-hours load,
    burnout signals)
-   Toil ratio (toil hours / total engineering time)
-   Attrition (regrettable vs non-regrettable)
-   Engagement signal trend (pulse survey or proxy metrics)
-   Cross-training completion % for targeted areas
-   Hiring pipeline health (time-to-fill, stage conversion) when
    applicable

------------------------------------------------------------------------

## 10. 90-Day Action Plan for a New Manager

Days 1--30: - Map stakeholders and partner teams; clarify interfaces and
expectations - Confirm service ownership boundaries and document gaps -
Audit team structure, roles, and decision rights - Create or refresh
skills matrix (include ops/security/architecture expectations) - Review
operational load: - on-call rotation health - incident volume and toil
sources - Identify single points of failure (people, process,
knowledge) - Review performance health: - existing feedback cadence -
recent performance concerns - role expectation clarity

Days 31--60: - Define and publish team charter and RACI (or refine
existing) - Establish cross-training plan targeting highest-risk
knowledge gaps - Implement toil tracking and prioritize top toil
reduction items - Introduce role expectation scorecards and align with
1:1 coaching - Create staffing plan: - hiring needs - upskilling needs -
contractor/vendor dependency risks - Align with partner teams on
escalation norms and collaboration rituals

Days 61--90: - Execute key org resilience changes: - rotate ownership -
pair critical responsibilities - improve on-call playbooks and rotation
fairness - Establish quarterly talent review and succession planning
rhythm - Publish a capability improvement roadmap (skills, structure,
sustainability) - Set measurable targets for: - bus factor
improvements - toil reduction - cross-training completion - on-call
health
