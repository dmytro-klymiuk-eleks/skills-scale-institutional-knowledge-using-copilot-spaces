# OctoAcme Roles and Personas (Expanded)

Purpose: Clarify accountability and collaboration by expanding personas/roles with responsibilities, deliverables, and key interactions.

## New Persona: Product Owner (PO)
- Responsibilities:
  - Owns product vision and backlog; defines and prioritizes backlog items and acceptance criteria.
  - Ensures the team builds the right thing; gathers and synthesizes feedback from stakeholders and users.
  - Accepts/declines increments; drives roadmap and release goals with PM.
- Key deliverables:
  - Product vision and roadmap, prioritized backlog, release goals, acceptance criteria.
- Interactions:
  - Works daily with Project Manager, Scrum Master, Tech Lead, Developers, QA Lead.
  - Aligns with business Stakeholders and Customers; coordinates with Change Manager for scope changes.

## New Persona: Solution Architect
- Responsibilities:
  - Defines solution architecture and non-functional requirements; ensures technical alignment to business goals.
  - Guides technical decisions, patterns, and guardrails; reviews high-risk designs and spikes.
  - Mitigates technical risk and ensures scalability, security, and operability.
- Key deliverables:
  - Architecture Decision Records (ADRs), diagrams, NFR catalogue, standards/guardrails.
- Interactions:
  - Partners with Tech Lead and Developers, DevOps/SRE, Security; collaborates with PO/PM on trade-offs; supports Change Manager on impact of changes.

## New Persona: QA Lead
- Responsibilities:
  - Owns test strategy, levels of testing, coverage, and quality gates across the lifecycle.
  - Establishes automation strategy and CI/CD quality checks; leads defect triage with the team.
  - Ensures traceability from requirements to tests and results.
- Key deliverables:
  - Test strategy and plan, traceability matrix, test reports, dashboards on quality metrics.
- Interactions:
  - Collaborates with Developers, PO, PM, Release Manager/DevOps; informs Change Manager of test impacts.

## New Persona: Change Manager
- Responsibilities:
  - Operates the change process: intake, impact assessment, approvals/CCB, scheduling, comms, and readiness.
  - Maintains change log and rollback/mitigation plans; ensures cross-team alignment on changes.
- Key deliverables:
  - Change requests and impact assessments, updated schedule, communications plan, rollout and rollback plans.
- Interactions:
  - Coordinates with PM, PO, Architect, QA Lead, Release/DevOps, Support Lead; communicates to Stakeholders.

## New Persona: Support Lead
- Responsibilities:
  - Owns post-release support, incident/problem management, SLA adherence, and customer comms.
  - Curates runbooks/KB; drives feedback loop from production back into backlog.
- Key deliverables:
  - Runbooks, KB articles, incident reports/postmortems, problem records and RCA.
- Interactions:
  - Works with Developers, QA Lead, PM, Change Manager; communicates with Customers/Support teams.

---

How this improves outcomes:
- Clarifies ownership across phases (planning, build, release, operate) to reduce gaps and handoff friction.
- Improves decision velocity via defined authorities and engagement points.
- Raises quality and change readiness with formal roles and supporting checklists.

References: See supporting checklists in docs/checklists/ and templates in docs/templates/.

