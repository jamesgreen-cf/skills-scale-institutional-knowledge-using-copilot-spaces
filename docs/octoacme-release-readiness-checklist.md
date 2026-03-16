# OctoAcme — Release Readiness Checklist

Use this checklist before every production release to confirm all teams have completed their pre-release responsibilities. Copy it into the release issue or PR description and assign sign-off owners.

---

## Engineering & CI

- [ ] All acceptance criteria met and PRs merged to the release branch
- [ ] CI pipeline passes (build, unit tests, integration tests, security scan)
- [ ] No open P0 / critical defects; all P1 / high defects resolved or formally accepted with mitigations
- [ ] Rollback / mitigation plan documented and reviewed

---

## QA Sign-off

- [ ] Test plan executed against the release candidate on staging
- [ ] Automated regression suite passes on staging environment
- [ ] Exploratory testing completed for high-risk areas
- [ ] All defects triaged; severity/risk of any accepted open defects documented
- [ ] **QA Engineer sign-off**: _[Name]_ — _[Date]_

---

## UX / Design Sign-off

- [ ] Release candidate reviewed by UX Designer on staging
- [ ] Design fidelity confirmed (responsive, accessible, consistent with design system)
- [ ] Any outstanding design debt documented and tracked in the backlog
- [ ] **UX Designer sign-off** *(if applicable)*: _[Name]_ — _[Date]_

---

## Documentation Readiness

- [ ] Release notes drafted, reviewed, and approved
- [ ] User-facing documentation updated (guides, API references, onboarding content)
- [ ] Internal runbooks and process docs updated if processes changed
- [ ] Changelog / version history entry added
- [ ] Docs publish date confirmed (live on release day or pre-staged)
- [ ] **Technical Writer sign-off**: _[Name]_ — _[Date]_

---

## Support Enablement

- [ ] Support runbook / FAQ updated to cover new or changed user workflows
- [ ] Support team briefed on changes (sync or written summary)
- [ ] Known issues and workarounds documented for the support team
- [ ] Escalation path confirmed for post-release incidents
- [ ] **Customer Support / CS sign-off**: _[Name]_ — _[Date]_

---

## Stakeholder Communications

- [ ] Release announcement drafted (internal and/or external)
- [ ] Comms owner identified: _[Name / Role]_
- [ ] Stakeholder briefing scheduled or sent
- [ ] Release date and deployment window confirmed with all impacted teams

---

## Deployment

- [ ] Deployment window scheduled (if required)
- [ ] Backup or snapshot taken (if applicable)
- [ ] Deployed to staging; smoke tests passed
- [ ] Deployed to production via automated pipeline
- [ ] Post-deploy verifications completed
- [ ] Monitoring dashboards checked; no anomalies detected

---

## Post-Release

- [ ] Release announcement sent to stakeholders and support
- [ ] Docs confirmed live / published
- [ ] Post-release retrospective or incident review scheduled if needed
- [ ] Release issue / ticket closed

---

*References: [Release & Deployment Guide](./octoacme-release-and-deployment.md) · [Roles & Personas](./octoacme-roles-and-personas.md) · [Role Interactions Matrix](./octoacme-role-interactions-matrix.md)*
