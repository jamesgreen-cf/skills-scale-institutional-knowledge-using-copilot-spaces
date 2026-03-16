# OctoAcme Project Management Docs

## Overview

OctoAcme runs cross-functional projects using a lightweight, repeatable lifecycle: **Initiation → Planning → Execution → Release → Close/Retrospective**. In initiation, the team validates the business need and measurable outcomes via a **Project One-pager** (problem, SMART goal/objective, success metrics), identifies stakeholders, captures initial risks/dependencies, and makes a clear **go/no-go** decision before investing in detailed planning. Once approved, planning converts the initiative into an actionable delivery plan: a prioritized backlog with explicit **acceptance criteria**, estimates (T‑shirt sizing or story points), an agreed **Definition of Done**, and a milestone/release map that highlights dependencies and integration points.

Roles and ownership are emphasized to keep delivery predictable. The **Project Manager (PM)** coordinates schedules, risk management, and stakeholder communications; the **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success; **Developers** design and implement solutions with tests and documentation; and **QA/Testing** validates quality and acceptance criteria, with stakeholders contributing inputs and approvals. Day-to-day execution is tracked on a project board (e.g., **Backlog, Ready, In Progress, In Review, QA, Done**) and reinforced by a PR workflow that favors **small pull requests**, links work to issues and acceptance criteria, and requires CI checks and at least one approval before merge (per team policy).

Communication follows a consistent cadence and clear escalation paths. Teams use short, regular touchpoints (standups and delivery syncs), periodic demos/reviews, and structured stakeholder updates using a standard weekly status format (progress, next steps, risks/blockers, asks/decisions). Risk management is handled through a simple **risk register** (impact/likelihood/owner/mitigation/status) that is reviewed regularly, with escalation moving from team triage to PM/Product Lead to sponsor-level when business impact warrants it; incident communications follow a concise template that supports fast alignment and post-incident learning.

Quality assurance is built into each phase, with expectations that new logic includes **unit tests**, broader changes use **integration tests** where appropriate, and critical flows get **end-to-end smoke tests** ahead of release. Releases also require acceptance criteria completion, passing CI and security scans, release notes, and a rollback/mitigation plan; deployments flow through staging verification and post-deploy checks with clear announcements to stakeholders/support. Finally, OctoAcme treats continuous improvement as part of the process: retrospectives after sprints/releases/incidents identify what went well, what to improve, and a small set of owned action items that are tracked like any other backlog work.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## How to Use These Docs

Start with the [Project Management Overview](octoacme-project-management-overview.md) for a full picture of OctoAcme's processes, then navigate to the relevant phase or topic doc as needed. Keep the Project Charter updated as the source of truth for each initiative. If you are using GitHub Copilot Spaces, add the process-specific docs most relevant to your current work into your `.copilot/` configuration so Copilot has the right context when assisting you.
