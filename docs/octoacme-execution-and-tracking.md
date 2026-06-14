# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

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
- Level 1 (0–24 h): Team-level triage in daily standup. Delivery Lead attempts to resolve.
- Level 2 (24–48 h): Delivery Lead escalates to PM. PM engages dependent teams or Product Lead.
- Level 3 (48 h+): PM escalates to Sponsor / Engineering Manager for business-impacting issues.
- Security blockers: escalate immediately to the Security / Compliance Representative and PM, regardless of level.

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests, lint, and security scanning
- [ ] Regular demos scheduled (end of each sprint or milestone)
- [ ] Risk register updated weekly by PM
- [ ] QA Lead has confirmed test coverage before sprint demos
- [ ] Technical Writer notified of completed features requiring doc updates
- [ ] Security scanning passing in CI; vulnerabilities triaged with Security Rep
