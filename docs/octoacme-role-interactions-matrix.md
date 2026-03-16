# OctoAcme — Role Interactions Matrix

This matrix provides a RACI-lite view of how each role participates across the project lifecycle phases. Use it during project initiation to assign roles and set expectations for involvement.

**Legend**: R = Responsible · A = Accountable · C = Consulted · I = Informed · — = Not typically involved

| Role | Initiation | Planning | Execution | Release | Retrospective |
|---|---|---|---|---|---|
| **Product Manager** | A | A | C | A | C |
| **Project Manager** | R | R | A | R | A |
| **Developer** | C | R | R | R | R |
| **UX/UI Designer** | C | C | R | C | R |
| **QA Engineer** | C | C | R | R | R |
| **Technical Writer** | C | C | R | R | R |
| **Customer Support / CS** | C | C | I | C | R |

---

## Phase-by-Phase Notes

### Initiation
- **Product Manager** owns the problem statement and success metrics (A).
- **Project Manager** assembles the team, documents stakeholders, and facilitates the go/no-go decision (R).
- **Developers**, **UX**, **QA**, and **Tech Writer** are consulted to flag feasibility, UX risks, test complexity, and documentation scope early.
- **Customer Support / CS** is consulted for known user pain points that should inform success criteria.

### Planning
- **Product Manager** is accountable for backlog prioritisation and acceptance criteria (A).
- **Project Manager** owns the release plan, milestone map, and risk register (R).
- **Developers** estimate and break down work (R); **UX** finalises designs and signs off on acceptance criteria (C); **QA** drafts the test plan (C); **Tech Writer** identifies documentation tasks (C).
- **Customer Support / CS** reviews user stories for real-world coverage (C).

### Execution
- **Project Manager** is accountable for day-to-day delivery progress and blocker escalation (A).
- **Developers** implement features and fixes (R); **UX** reviews in-progress builds for design fidelity (R); **QA** runs tests and flags defects (R); **Tech Writer** drafts and updates documentation in parallel (R).
- **Customer Support / CS** is kept informed via sprint demos and may provide feedback on user-facing changes (I).

### Release
- **Product Manager** is accountable for the release decision (A).
- **Project Manager** coordinates the release window and stakeholder communication (R).
- **Developers** merge, deploy, and verify (R); **QA** provides sign-off on staging (R); **Tech Writer** confirms docs are live or scheduled (R).
- **UX** and **Customer Support / CS** are consulted to confirm readiness from their perspectives (C).

### Retrospective
- **Project Manager** is accountable for running the session and tracking action items (A).
- All roles participate (R) — including extended roles (UX, QA, Tech Writer, Support/CS) when their work was part of the sprint or release.

---

## Role Assignment Quick Guide

Refer to the [Roles & Personas](./octoacme-roles-and-personas.md) document for full role descriptions and the scope-based guidance on when each role is optional vs. required.
