# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone
- **UX review sessions**: schedule a design review before implementation of user-facing features; UX Designer confirms fidelity on staging before QA sign-off
- **QA checkpoints**: QA Engineer attends sprint review to confirm acceptance criteria are met; critical defects block "Done" status
- **Documentation updates**: Technical Writer joins weekly sync to track scope changes; doc updates are included in sprint velocity
- **Support feedback loop**: Customer Support / CS attends monthly or milestone-based demo to share user feedback and flag usability issues

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled (include UX and Support where relevant)
- [ ] Risk register updated weekly
- [ ] UX design review completed before implementation of user-facing work
- [ ] QA checkpoints defined and enforced in Definition of Done
- [ ] Documentation tasks tracked on the project board
- [ ] Support runbook / FAQ draft in progress alongside development
