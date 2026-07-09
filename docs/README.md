# OctoAcme Project Management - README

Purpose: A single landing page that summarizes OctoAcme's project management approach and links to the full process documents in this repository's docs/ folder.

Overview

OctoAcme follows an iterative, outcome-driven project lifecycle that starts with a lightweight initiation (a Project One-pager and stakeholder alignment) and progresses through planning, execution, release, and retrospective stages. Work is organized into small, shippable increments with clear acceptance criteria and a Definition of Done to ensure items are ready for delivery. The project board (Backlog → Ready → In Progress → In Review → QA → Done) and timeboxed iterations help the team maintain focus, manage scope, and measure progress.

Key workflows & roles

Product Managers (PdM) define outcomes and success metrics; Project Managers (PM) coordinate timelines, risks, and stakeholder communication; Developers implement features and maintain tests; QA validates acceptance criteria and performs testing. The planning process produces a prioritized backlog with estimates, a release plan, and a risk register. Pull requests should be small, include linked issues and acceptance criteria, and run CI and security scans before review.

Communication & quality

The team operates a regular cadence: daily standups for progress and blockers, weekly delivery syncs for status and risk review, and demos at the end of sprints or milestones. Stakeholder updates use a single source of truth (project README or release doc). Quality practices include automated unit/integration tests, CI-based security scanning, staging smoke tests, and manual QA when needed. Retrospectives after each sprint or release produce tracked action items that feed back into the backlog for continuous improvement.

Links to process documents

- docs/octoacme-project-management-overview.md — Overview, principles, roles, and key artifacts.
- docs/octoacme-project-initiation.md — Project initiation guide and one-pager template.
- docs/octoacme-project-planning.md — Planning activities, backlog template, and risk management.
- docs/octoacme-execution-and-tracking.md — Team rhythm, workflows, QA, and tracking guidance.
- docs/octoacme-release-and-deployment.md — Release types, deployment checklist, and rollback playbook.
- docs/octoacme-risks-and-communication.md — Risk register, communication templates, and escalation paths.
- docs/octoacme-retrospective-and-continuous-improvement.md — Retrospective structure and follow-up tracking.
- docs/octoacme-roles-and-personas.md — Role summaries and responsibilities used in OctoAcme.

Notes

- Suggested filename: docs/README-octoacme-project-management.md
- This README can be added to .copilot/ or referenced in project templates so Copilot Spaces uses it as context.
