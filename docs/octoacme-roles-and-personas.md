# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## Additional Personas

### Delivery Lead

#### Role Summary
Delivery Leads own sprint-level execution. They translate roadmap priorities into sprint scope and keep the team moving at a sustainable pace.

#### Responsibilities
- Coordinate sprint delivery, remove cross-team impediments
- Maintain sprint commitments and delivery calendar
- Ensure acceptance criteria are ready before sprint start
- Facilitate daily standups and sprint reviews

#### Goals
- Protect sprint scope from unplanned interruptions
- Ensure the team consistently meets sprint goals
- Surface impediments early so the PM can escalate

#### Interactions
- Works with PM and PdM to translate roadmap priorities into sprint scope
- Coordinates with Engineering Manager and QA Lead on capacity and test plans
- Escalates unresolved blockers to PM after 24 hours

---

### Engineering Manager

#### Role Summary
Engineering Managers provide people leadership and technical oversight for the engineering team.

#### Responsibilities
- Team staffing and capacity planning
- Technical debt prioritization and architecture decisions
- Performance management and career growth for engineers
- Participate in design and code reviews

#### Goals
- Maintain a healthy, high-performing engineering team
- Balance feature delivery with technical sustainability

#### Interactions
- Partners with PM and Delivery Lead on resourcing and capacity
- Supports Developers on design and code reviews
- Surfaces technical risks to PM and PdM during planning

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers ensure features meet user needs and are usable, accessible, and consistent with product standards.

#### Responsibilities
- Conduct user research and usability studies
- Define UX acceptance criteria and design prototypes
- Deliver design assets (wireframes, specs, prototypes) to developers
- Participate in usability validation after implementation

#### Goals
- Ensure features solve real user problems
- Reduce rework caused by late UX feedback

#### Interactions
- Collaborates with PdM on success metrics and acceptance criteria
- Hands off designs to Developers with documented specs
- Reviews implementations against design criteria before QA sign-off

---

### Technical Writer / Docs Owner

#### Role Summary
Technical Writers maintain user-facing and developer-facing documentation to ensure it stays accurate as features ship.

#### Responsibilities
- Write and maintain user docs, developer docs, runbooks, and release notes
- Ensure docs are updated before or alongside each release
- Capture migration notes and breaking changes from Developers and the Release Engineer

#### Goals
- Ensure no feature ships without accurate, up-to-date documentation
- Reduce support burden by making docs self-service

#### Interactions
- Works with Developers to capture implementation details and migration notes
- Coordinates with PM and Release Engineer for release note deadlines
- Reviews and publishes docs as part of the release checklist

---

### Release / Platform Engineer

#### Role Summary
Release / Platform Engineers manage deployment pipelines, infrastructure configuration, and release verifications.

#### Responsibilities
- Manage CI/CD pipelines, deployment automation, and rollback procedures
- Schedule and coordinate release windows
- Perform pre-release environment checks and post-deploy smoke tests
- Document rollback procedures for each release

#### Goals
- Ensure safe, repeatable, zero-downtime deployments
- Minimize time-to-recovery in case of deployment failures

#### Interactions
- Coordinates with QA Lead for pre-release checks and smoke test sign-off
- Works with PM for release window scheduling and stakeholder communication
- Notifies Developers and Security Rep of deployment outcomes

---

### QA Lead / Test Engineer

#### Role Summary
QA Leads own the test strategy, automation coverage, and quality gate for releases.

#### Responsibilities
- Define and maintain the test strategy and automation suite
- Coordinate manual acceptance testing with the delivery team
- Gate releases via QA sign-off
- Maintain entry and exit criteria for each phase

#### Goals
- Prevent regressions from reaching production
- Reduce manual testing effort through automation
- Provide clear, timely quality status for release decisions

#### Interactions
- Works with Developers on testability and test coverage
- Collaborates with Delivery Lead on sprint entry/exit criteria
- Coordinates with Release Engineer for smoke tests and release readiness

---

### Security / Compliance Representative

#### Role Summary
Security / Compliance Representatives ensure features and infrastructure meet security and regulatory requirements.

#### Responsibilities
- Conduct threat modeling and security design reviews
- Triage and prioritize security vulnerabilities
- Maintain compliance checklists and audit records
- Review PRs and designs when security-sensitive changes are involved

#### Goals
- Prevent security incidents by catching risks early in the lifecycle
- Ensure compliance requirements are met before each release

#### Interactions
- Reviews designs and PRs when security-sensitive changes occur
- Coordinates with Developers and Release Engineer on remediation timelines
- Escalates unresolved security issues to the Engineering Manager and PM

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

