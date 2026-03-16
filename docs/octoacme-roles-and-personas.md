# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## How to Assign Roles Per Project

Not every project requires every role. Use the guidance below to identify which roles are needed based on project scope, and refer to the [Role Interactions Matrix](./octoacme-role-interactions-matrix.md) for a lifecycle-phase view of who does what.

### Role Assignment Guidelines

| Role | Required When | Optional When |
|---|---|---|
| Developer | Any engineering work is involved | Pure research or documentation-only projects |
| Product Manager | Customer-facing features are being built | Internal tooling with no user-facing impact |
| Project Manager | Cross-team coordination or formal milestones are needed | Small, single-team spikes |
| UX/UI Designer | User-facing UI is being designed or significantly changed | Backend-only or API-only changes |
| Quality Assurance Engineer | Formal test strategy, regression coverage, or compliance is needed | Trivial hotfixes with full automated coverage |
| Technical Writer | External docs, release notes, or onboarding guides are impacted | Internal-only changes with no user documentation impact |
| Customer Support / Customer Success | The change affects user workflows or support runbooks | Purely internal infrastructure changes |

### RACI-Lite Quick Reference

- **R — Responsible**: Does the work  
- **A — Accountable**: Owns the outcome and signs off  
- **C — Consulted**: Provides input before decisions are made  
- **I — Informed**: Kept up to date on progress or outcomes  

See the [Role Interactions Matrix](./octoacme-role-interactions-matrix.md) for a full phase-by-phase breakdown.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX/UI Designer

### Role Summary
UX/UI Designers create user interfaces, interaction flows, and visual designs that ensure features are intuitive and meet user needs. They bridge product intent and technical implementation.

### Responsibilities
- Design wireframes, prototypes, and high-fidelity mockups
- Conduct or synthesize user research and usability testing
- Define and maintain the design system and component library
- Review acceptance criteria for user experience impact
- Collaborate on responsive, accessible design standards

### Goals
- Ensure features are usable, accessible, and visually consistent
- Reduce rework by involving design early in the development cycle
- Advocate for the end user throughout the project lifecycle

### Typical Communication
- Design review sessions with Product Manager and Developers
- Handoff notes in design tools (e.g., Figma) linked to issues
- Participation in sprint planning and retrospectives

### Interactions
- **Project Initiation**: Contributes to team composition and flags UX risks; reviews the project one-pager for user-facing scope.
- **Planning**: Works with Product Manager to define UX acceptance criteria; attends kickoff to clarify design expectations.
- **Execution**: Shares designs with Developers for implementation; reviews PRs or staging builds for design fidelity; collaborates with QA on visual/interaction acceptance criteria.
- **Release**: Reviews release-candidate builds; confirms design-related acceptance criteria are met before sign-off.
- **Retrospective**: Provides feedback on how design handoff and review processes worked; proposes improvements to the design–development loop.

---

## Technical Writer / Documentation Specialist

### Role Summary
Technical Writers produce, maintain, and improve internal and external documentation. They ensure that process artifacts, user guides, release notes, and API docs are clear, accurate, and up to date.

### Responsibilities
- Author and maintain user-facing docs, runbooks, and API references
- Update internal process documents and templates as processes evolve
- Work with Developers and Product Managers to capture and document changes
- Produce release notes and changelogs for each release
- Review documentation for accuracy, completeness, and readability

### Goals
- Reduce support burden through clear, self-service documentation
- Ensure documentation stays in sync with product changes
- Improve onboarding speed for new team members and users

### Typical Communication
- Coordination with Product Manager on upcoming features that need docs
- Review cycles with Developers and QA for technical accuracy
- Release planning check-ins to capture what has changed

### Interactions
- **Project Initiation**: Flags documentation needs early; contributes a documentation plan to the project one-pager.
- **Planning**: Adds documentation tasks to the backlog; aligns with Product Manager on scope of user-facing content.
- **Execution**: Updates docs in parallel with development; reviews draft content with Developers for accuracy; coordinates with QA to verify documented steps match actual behavior.
- **Release**: Delivers release notes and updated docs as a release readiness criterion; reviews the [Release Readiness Checklist](./octoacme-release-readiness-checklist.md).
- **Retrospective**: Identifies gaps in documentation practices and proposes improvements to the documentation workflow.

---

## Customer Support / Customer Success

### Role Summary
Customer Support and Customer Success roles bring the voice of the customer into the project process. They surface user pain points, validate that releases meet real-world needs, and enable support teams to handle incoming queries effectively.

### Responsibilities
- Provide input on known user pain points and common support tickets
- Validate that acceptance criteria address real customer scenarios
- Review release notes and user-facing documentation for clarity
- Prepare support team with runbooks, FAQs, and training materials
- Track post-release user feedback and route it to the right teams

### Goals
- Reduce post-release support volume through proactive readiness
- Ensure users can successfully adopt new features
- Feed customer insights back into the roadmap and prioritization

### Typical Communication
- Periodic input sessions with Product Manager on top customer issues
- Release readiness reviews to confirm support materials are ready
- Post-release feedback summaries shared with Product and Project Managers

### Interactions
- **Project Initiation**: Contributes user pain points and use cases to the problem statement; helps define success metrics from a customer perspective.
- **Planning**: Reviews user stories and acceptance criteria for real-world coverage; flags edge cases from support history.
- **Execution**: Provides feedback on builds or demos that affect user workflows; drafts support runbooks and FAQs in parallel with development.
- **Release**: Confirms support materials (runbooks, FAQs, help articles) are ready; participates in the [Release Readiness Checklist](./octoacme-release-readiness-checklist.md) sign-off.
- **Retrospective**: Shares post-release support ticket trends and user feedback to inform process and product improvements.

---

## Quality Assurance Engineer

### Role Summary
Quality Assurance Engineers design and execute test strategies to ensure software meets functional, performance, and reliability standards. They go beyond manual spot-checks to build systematic, risk-based coverage.

### Responsibilities
- Define and maintain the test strategy (scope, types, tools, environments)
- Design, implement, and maintain automated test suites (unit, integration, end-to-end)
- Perform exploratory and regression testing before each release
- Own the Definition of Done criteria related to test coverage and quality gates
- Collaborate on risk assessment to prioritize testing effort
- Track and triage defects; communicate severity and impact clearly

### Goals
- Prevent regressions and critical defects from reaching production
- Reduce manual testing effort through meaningful automation
- Provide clear, evidence-based quality signals before each release

### Typical Communication
- Test plan and status updates shared with Project Manager and Developers
- Defect reports linked to issues on the project board
- QA sign-off confirmation as part of release readiness

### Interactions
- **Project Initiation**: Reviews the initial risk list for quality-related risks; advises on testability of proposed solutions.
- **Planning**: Drafts the test plan alongside the backlog; contributes QA-related acceptance criteria and Definition of Done items.
- **Execution**: Integrates automated tests into CI; runs regression suites; flags and triages defects; participates in design and code reviews to assess testability.
- **Release**: Signs off on QA readiness; confirms all critical defects are resolved or accepted; validates smoke tests pass on staging.
- **Retrospective**: Reports on defect trends, test coverage gaps, and quality-related action items for continuous improvement.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

