# OctoAcme — Handoffs & Phase Checklists

## Purpose
Define the explicit handoffs between project phases and provide ready-to-use checklists that keep every team member accountable at phase transitions.

---

## Phase Handoff Map

```
Initiation → Planning → Execution → Release → Retrospective
```

Each arrow represents a handoff where a named owner passes a defined set of artifacts to the next phase owner.

---

## Initiation → Planning Handoff

**From:** PM + PdM  
**To:** Delivery Lead + Engineering Team

| Artifact | Owner | Ready? |
|---|---|---|
| Approved Project One-pager | PdM | ☐ |
| Stakeholder list and communication plan | PM | ☐ |
| High-level milestones and timeline | PM | ☐ |
| Initial risk list | PM | ☐ |
| Proposed team roster and roles | PM + Engineering Manager | ☐ |

**Gate:** All artifacts above are present before kickoff meeting is scheduled.

---

## Planning → Execution Handoff

**From:** PM + PdM + Delivery Lead  
**To:** Delivery Team (Developers, QA Lead, UX Designer)

| Artifact | Owner | Ready? |
|---|---|---|
| Prioritized backlog with acceptance criteria | PdM | ☐ |
| UX designs and specs | UX Designer | ☐ |
| Definition of Done documented | PM + Delivery Lead | ☐ |
| Risk register initialized | PM | ☐ |
| Sprint entry/exit criteria | QA Lead | ☐ |
| Security requirements communicated | Security Rep | ☐ |
| Docs plan confirmed | Technical Writer | ☐ |

**Gate:** All items confirmed in kickoff meeting before the first sprint begins.

---

## Execution → Release Handoff

**From:** Delivery Team  
**To:** Release Engineer + PM

| Artifact | Owner | Ready? |
|---|---|---|
| All PRs merged and CI green | Developers | ☐ |
| QA sign-off on acceptance criteria | QA Lead | ☐ |
| Security scan passed | Security Rep | ☐ |
| Release notes drafted | Technical Writer | ☐ |
| Rollback plan documented | Release Engineer | ☐ |
| Feature documentation updated | Technical Writer | ☐ |
| Stakeholder communication drafted | PM | ☐ |

**Gate:** Go / No-Go meeting completed (see [Release & Deployment Guide](octoacme-release-and-deployment.md)).

---

## Release → Retrospective Handoff

**From:** PM + Release Engineer  
**To:** Full Team

| Artifact | Owner | Ready? |
|---|---|---|
| Release announced to stakeholders | PM | ☐ |
| Post-deploy verification completed | Release Engineer | ☐ |
| Incidents or issues captured | PM | ☐ |
| Retrospective scheduled (within 5 business days) | PM | ☐ |

---

## Sprint Retrospective Checklist

Use this checklist to run a consistent, actionable retrospective.

### Before the Retrospective
- [ ] Facilitator confirmed (PM or Delivery Lead)
- [ ] Attendees invited (full delivery team)
- [ ] Previous retrospective action items reviewed for closure

### During the Retrospective
- [ ] What went well — capture positives (do more of this)
- [ ] What could be improved — identify specific process or tooling gaps
- [ ] Root causes identified for recurring issues
- [ ] Action items defined: each has a title, owner, and due date
- [ ] Prioritize 2–3 top action items (avoid overload)

### After the Retrospective
- [ ] Action items added to the project backlog with owners
- [ ] Action items reviewed in the next weekly PM sync
- [ ] Retrospective notes stored in the project repo

---

## Risk Register Template

| ID | Description | Impact | Likelihood | Owner | Mitigation | Status |
|---|---|---|---|---|---|---|
| R-001 | | High / Med / Low | High / Med / Low | | | Open / Mitigated / Closed |

**Review cadence:** Update status at every weekly PM sync.

---

## Weekly Status Report Template

```
**Project:** [Name]
**Date:** [YYYY-MM-DD]
**Reporter:** [PM Name]

**Progress this week:**
- [Completed item 1]
- [Completed item 2]

**Next steps:**
- [Planned item 1]
- [Planned item 2]

**Risks & blockers:**
- [Risk / blocker description] — Owner: [Name] — ETA for resolution: [Date]

**Asks / decisions needed:**
- [Decision or action needed from stakeholders]

**Key metrics:**
- Velocity: [X story points]
- Open bugs: [N]
- Test coverage: [%]
```
