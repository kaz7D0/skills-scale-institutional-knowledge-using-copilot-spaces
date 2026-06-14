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
- Release notes drafted (Technical Writer)
- Rollback / mitigation plan documented (Release Engineer)
- Smoke tests prepared (QA Lead)
- QA sign-off obtained from QA Lead
- Security sign-off obtained from Security / Compliance Representative (for security-sensitive releases)

## Release Go / No-Go Gate
Before deploying to production, confirm all of the following with relevant owners:

| Check | Owner | Status |
|---|---|---|
| All acceptance criteria met | Delivery Lead | ☐ |
| CI/CD pipeline green | Release Engineer | ☐ |
| Security scan passed | Security Rep | ☐ |
| QA sign-off | QA Lead | ☐ |
| Release notes ready | Technical Writer | ☐ |
| Rollback plan documented | Release Engineer | ☐ |
| Stakeholder communication drafted | PM | ☐ |

If any check is blocked, the PM and Release Engineer must jointly decide whether to proceed, delay, or descope.

## Deployment Checklist
- [ ] Go / No-Go gate completed and approved
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] QA Lead confirms smoke tests passed
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (PM)

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
