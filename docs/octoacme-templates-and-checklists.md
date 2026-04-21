# OctoAcme — Templates & Checklists

A single reference for the reusable templates and checklists referenced across OctoAcme project management docs.

---

## Weekly Status Update Template

Use in weekly syncs and stakeholder communications (see [Risk Management & Communication](octoacme-risks-and-communication.md)).

```
Project: <name>
Week ending: <date>
Status: 🟢 On track / 🟡 At risk / 🔴 Off track

## Progress this week
- <bullet: completed work or milestone reached>

## Next steps
- <bullet: planned work for next week>

## Risks & blockers
- <risk or blocker, owner, mitigation>

## Asks / decisions needed
- <decision required, from whom, by when>
```

---

## Risk Register Template

Maintain in the project repo or wiki. Review and update at weekly syncs (see [Risk Management & Communication](octoacme-risks-and-communication.md) and [Project Planning](octoacme-project-planning.md)).

| ID | Description | Impact | Likelihood | Owner | Mitigation Plan | Status |
|----|-------------|--------|-----------|-------|-----------------|--------|
| R-01 | Example: third-party API deprecation | High | Low | DevOps Engineer | Pin to current version; schedule migration spike | Open |
| R-02 | | | | | | |

**Impact / Likelihood scale:** High · Med · Low  
**Status values:** Open · Mitigated · Accepted · Closed

---

## Decision Log Template

Record significant decisions with context so future team members can understand the rationale.

| ID | Date | Decision | Alternatives Considered | Rationale | Owner | Status |
|----|------|----------|------------------------|-----------|-------|--------|
| D-01 | 2026-01-15 | Adopt GitHub Projects for task tracking | Jira, Linear | Already used by engineering; no additional licensing cost | Project Manager | Approved |
| D-02 | | | | | | |

---

## Definition of Ready (Checklist)

A backlog item is ready to be pulled into a sprint when all of the following are true:

- [ ] User story or task title is clear and concise
- [ ] Acceptance criteria are written and agreed by Product Manager and Developers
- [ ] Dependencies identified and either resolved or scheduled
- [ ] Effort estimated (story points or T-shirt size)
- [ ] Linked to the relevant epic or milestone
- [ ] UX designs or mockups attached (if UI-facing)
- [ ] Any required data / analytics instrumentation identified

---

## Definition of Done (Checklist)

A backlog item is done when all of the following are true:

- [ ] All acceptance criteria met and verified
- [ ] Code reviewed and approved (minimum one approval per team policy)
- [ ] Automated tests written and passing in CI
- [ ] No new high/critical security scan findings introduced
- [ ] Documentation updated (README, API docs, release notes as applicable)
- [ ] Feature flagged or merged to the release branch
- [ ] QA/Testing sign-off obtained
- [ ] Product Manager has accepted the deliverable

---

## Retro Action Items Tracker

Add action items here after each retrospective. Review outstanding items in the next retro and in weekly PM syncs (see [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)).

| # | Action Item | Owner | Due Date | Success Criteria | Status |
|---|-------------|-------|----------|-----------------|--------|
| 1 | Example: add end-to-end smoke tests to CI pipeline | DevOps Engineer | 2026-02-01 | Pipeline runs smoke tests on every PR to `main` | Open |
| 2 | | | | | |

**Status values:** Open · In Progress · Done · Deferred

---

## Release Notes Template

Aligns with the release process in [Release & Deployment Guide](octoacme-release-and-deployment.md).

```
# Release Notes — <Product/Service Name> v<version>

**Date:** <YYYY-MM-DD>
**Release type:** Patch / Minor / Major

## Summary
<One-paragraph overview of what changed and why.>

## Notable Changes
- <Feature or fix 1>: <brief description>
- <Feature or fix 2>: <brief description>

## Migration Steps
> Include only if breaking changes or data migrations are required.
- <Step 1>
- <Step 2>

## Known Issues
- <Issue description, workaround if available>

## Rollback Instructions
- <Steps to revert if needed; reference the Rollback & Incident Playbook>
```
