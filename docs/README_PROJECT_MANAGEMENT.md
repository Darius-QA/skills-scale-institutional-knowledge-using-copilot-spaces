# OctoAcme Project Management Docs

This README provides a concise entry point to OctoAcme's project management processes and direct links to the full process documents in the repository's docs/ folder. It is intended for onboarding, quick reference during delivery, and to make process artifacts easier to find.

OctoAcme follows a lightweight, lifecycle-driven approach: Initiation, Planning, Execution, Release, and Retrospective. Initiation focuses on validating the business problem and drafting a Project One‑pager to capture objectives, success metrics, stakeholders, and an initial timeline. Planning turns an approved initiative into an actionable backlog with estimates, a Definition of Done, and a release milestone plan. Execution is iterative — teams work in small, testable increments tracked on the project board, review work via pull requests, and surface blockers through an escalation path. Releases require pre-release checks, a rollback plan, staging verification, and post-deploy validation. Retrospectives capture learnings and convert them into action items tracked in the backlog.

Workflows emphasize clear ownership and small, reviewable changes. Use the project board with columns Backlog → Ready → In Progress → In Review → QA → Done. Follow the PR workflow: keep PRs small where possible, include the related issue and acceptance criteria in the PR description, and ensure automated tests and linting pass in CI before requesting review. Require reviews according to team policy before merging. Dependencies and risks are tracked in a Risk Register and escalated via defined paths (team → PM → Product Lead → Sponsor) when needed.

Roles and communication are explicit: each project has a named Project Manager (PM) and Product Lead (PdM), with Developers and QA responsible for delivery and testing. Team cadence includes daily standups, weekly delivery syncs, end-of-sprint demos/reviews, and monthly stakeholder updates. Quality assurance is embedded across the lifecycle: unit and integration tests, end-to-end smoke tests for critical flows, CI security scanners, and manual QA where required. Release checklists and rollback playbooks reduce production risk, and retrospective action items drive continuous improvement.

Docs and links
- Project management overview: docs/octoacme-project-management-overview.md
- Project initiation: docs/octoacme-project-initiation.md
- Project planning: docs/octoacme-project-planning.md
- Execution & tracking: docs/octoacme-execution-and-tracking.md
- Risks & communication: docs/octoacme-risks-and-communication.md
- Release & deployment: docs/octoacme-release-and-deployment.md
- Retrospective & continuous improvement: docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & personas: docs/octoacme-roles-and-personas.md

How to use this README
- Use these links as the first stop when onboarding new team members or starting a new project.
- Open the Project One‑pager template in the initiation doc when scoping a new initiative.
- Keep the Risk Register updated and surface major blockers in the weekly PM + PdM sync.
- Add process-specific documents into `.copilot/` if you want Copilot Spaces to use them as context.
