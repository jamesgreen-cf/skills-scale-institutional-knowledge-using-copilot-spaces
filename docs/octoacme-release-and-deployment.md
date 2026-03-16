# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- **QA sign-off**: QA Engineer confirms all critical and high-severity defects are resolved or formally accepted; regression suite passes on staging
- Release notes drafted and reviewed by Technical Writer
- **Docs readiness**: Technical Writer confirms user-facing docs, API references, and runbooks are updated and published (or scheduled)
- **Support enablement**: Customer Support / CS confirms runbooks, FAQs, and training materials are ready; support team is briefed
- **Comms owner identified**: Product Manager or Project Manager designated to announce the release to stakeholders and customers
- Rollback / mitigation plan documented
- Smoke tests prepared

See the [Release Readiness Checklist](./octoacme-release-readiness-checklist.md) for a detailed pre-release sign-off list.

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] QA sign-off on staging confirmed
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (comms owner action)
- [ ] Confirm docs are live or scheduled to publish

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
