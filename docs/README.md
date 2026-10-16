# OctoAcme Project Management Docs

This README centralizes OctoAcme's project management process documents. It provides a short summary of the core processes, direct links to each detailed document in this folder, and guidance on how to use these artifacts to run projects effectively.

## Brief overview of OctoAcme project management processes

OctoAcme runs projects through a clear stage-based lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiation focuses on validating ideas with a Project One-pager (problem, goal, success metrics), aligning stakeholders, and making a go/no‑go decision to enter planning. Planning converts approved initiatives into a prioritized and estimated backlog, defines a Definition of Done (DoD), identifies dependencies and risks, and maps releases and milestones.

Execution emphasizes iterative delivery and predictable team cadence. Teams use a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done), keep pull requests small and linked to issues and acceptance criteria, and run CI (tests, linting, security scans) before requesting reviews. Day-to-day communication includes daily standups for blockers and a weekly delivery sync to show progress and escalate risks; blockers follow a three-level escalation path from the team to PM, Product Lead, and Sponsor for business-impacting issues.

Release and quality practices require automated and manual checks: unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Pre-release checks include passing CI, drafted release notes, a rollback/mitigation plan, and smoke tests in staging before production deployment. After releases or sprints, OctoAcme runs retrospectives to capture learnings and turn them into a small number of prioritized action items tracked in the backlog to drive continuous improvement.

## Docs (links)

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## How to use this folder

- Keep each process doc updated in this folder.
- Link the most relevant docs from the repository root README to improve discoverability.
- Add templates and checklists into `docs/` or `.copilot/` so Copilot Spaces can use them as context.
