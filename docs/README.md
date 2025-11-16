# OctoAcme Project Management Overview

This document provides a high-level overview of OctoAcme's project management processes, roles, and communication practices. It is designed to help new team members and stakeholders quickly understand how OctoAcme delivers projects from idea to production. For detailed guidance on each process area, refer to the linked documents in this folder.

OctoAcme follows a lightweight, stage-gated lifecycle—Initiation → Planning → Execution → Release → Close & Retrospective—focused on delivering small, testable increments. Projects begin with a Project One-pager to define the problem, success metrics, stakeholders, and a high-level timeline. Planning breaks approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release/milestone map; risks and cross-team dependencies are captured in a Risk Register and surfaced during weekly syncs. Work items use a standard backlog item template and a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done), with pull requests expected to be small, include issue links and acceptance criteria, run automated CI (tests, linting, security scans), and have at least one approval before merging.

Roles are explicit to ensure clear ownership: Product Managers own outcomes and prioritize the backlog, Project Managers coordinate delivery and communication, Developers implement and test, QA validates acceptance, and stakeholders provide input and approvals. This clear separation of concerns enables efficient collaboration and accountability throughout the project lifecycle.

Communication is cadence-driven: daily standups focus on progress and blockers, weekly delivery syncs cover progress/risks/dependencies, sprint demos show completed work, and monthly stakeholder updates summarize status. Escalation paths are defined (team → PM → Product Lead → Sponsor) and incident communications follow a structured triage and post-incident blameless retrospective. A single source of truth (project README or release doc) is used for status and release notes.

Quality assurance is integrated into the flow: unit and integration tests are required where applicable, end-to-end smoke tests cover critical flows, CI includes security scanning, and manual QA is used when necessary. Pre-release gates require passing CI, security scans, release notes, and a rollback/mitigation plan; retrospectives capture learnings and convert them into backlog action items tracked and reviewed in the weekly PM sync to drive continuous improvement.

## See also

- [octoacme-project-initiation.md](octoacme-project-initiation.md) — Project initiation and one-pager template
- [octoacme-project-planning.md](octoacme-project-planning.md) — Planning, backlog creation, and risk management
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) — Execution workflow, project boards, and PR practices
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) — Release process, deployment gates, and rollback procedures
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) — Retrospectives and continuous improvement practices
- [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) — Risk management and communication protocols
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) — Role definitions and responsibilities
