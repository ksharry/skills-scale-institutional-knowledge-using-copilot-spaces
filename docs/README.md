# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management documentation. These guides provide a comprehensive framework for managing cross-functional projects at OctoAcme, from initial concept through delivery and continuous improvement. Our approach is built on principles of customer-first thinking, iterative delivery, clear ownership, data-informed decisions, and psychological safety.

OctoAcme's project management process follows a structured lifecycle: **Initiation** (validating business need and stakeholder alignment), **Planning** (defining scope, resources, and milestones), **Execution** (building, testing, and iterating with regular standups and demos), **Release** (deploying with quality gates and verification), and **Retrospective** (capturing learnings for continuous improvement). Projects are tracked using GitHub project boards with a clear PR workflow that emphasizes small, testable increments, automated CI checks, and code review before merging.

Our **key personas** include Project Managers (coordinating delivery, schedules, and risk), Product Managers (defining outcomes and prioritizing backlog), Developers (implementing features with quality and testability), and QA/Testing (validating acceptance criteria). **Communication cadences** ensure alignment through twice-weekly standups for delivery teams, weekly PM + PdM syncs, and monthly stakeholder updates. Escalation paths are clearly defined from team-level triage through PM and Product Lead to Sponsor-level for business-impacting issues.

Quality assurance is central to our process, with requirements for unit tests, integration tests, security scanning in CI, and a clear Definition of Done. Each release follows pre-deployment checklists including passing tests, security scans, smoke tests on staging, rollback plans, and post-deploy verification. Risk management is ongoing through weekly risk register reviews and proactive stakeholder communication.

## Docs Index

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to principles, roles, artifacts, and lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) — Steps to validate and authorize new projects with one-pager template
- [Project Planning](octoacme-project-planning.md) — Detailed planning guidance for scope, resources, and milestones
- [Execution and Tracking](octoacme-execution-and-tracking.md) — Day-to-day execution workflows, PR conventions, quality practices, and reporting
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register, stakeholder communication, and escalation paths
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Release types, pre-release requirements, deployment checklists, and rollback procedures
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Post-project reviews and learning capture
- [Roles and Personas](octoacme-roles-and-personas.md) — Detailed role definitions for Developers, Product Managers, and Project Managers

## How to Use These Docs

These process documents are living resources that evolve with team feedback and best practices. When you identify opportunities to improve clarity, close gaps, or add new guidance, please:

1. Keep the project README and relevant docs updated as processes change
2. Use the issue template at [`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) when proposing changes
3. Ensure proposed updates align with existing documentation and have been reviewed with stakeholders when needed

For project-specific artifacts like Project Charters or One-pagers, maintain them in your project repository and consider adding process docs to `.copilot/` for Copilot Spaces context.
