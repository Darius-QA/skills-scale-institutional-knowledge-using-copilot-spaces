# OctoAcme Project Management Docs

This README provides a short summary of OctoAcme's project management processes and direct links to the full process documents in this repository's docs/ folder.

## Overview
OctoAcme runs projects with an iterative, customer-first approach and clear ownership. Work begins with a lightweight initiation gate (a Project One-pager) to capture the problem, goals, success metrics, stakeholders, initial timeline, and risks. Approved initiatives move into planning where the team breaks work into shippable increments, defines acceptance criteria and a Definition of Done, identifies dependencies, and creates a release plan with milestones.

Planning and execution emphasize small, testable increments and predictable delivery workflows. Teams use a project board with columns (Backlog → Ready → In Progress → In Review → QA → Done), timeboxed sprints or iterations, and a disciplined pull request workflow (small PRs when possible, link to the issue and acceptance criteria, automated CI checks, and at least one approval before merging). Regular cadences — daily standups, weekly delivery syncs, demos at the end of sprints/milestones, and monthly stakeholder updates — keep work aligned and make blockers visible.

## Roles & communication
Roles are explicit: Product Managers (PdM) define outcomes and prioritize the backlog, Project Managers (PM) coordinate schedules, risks, and communications, Developers implement and test features, and QA validates acceptance criteria and release readiness. Teams maintain a risk register with owners and mitigation plans and follow clear escalation paths (team → PM → Product Lead → Sponsor) for business-impacting issues. Communication templates (weekly status, incident summaries) and a single source of truth (project README / release doc) are recommended.

## Quality & release practices
Quality assurance includes unit and integration tests, smoke tests for critical flows, security scanning in CI, and manual QA as needed. Releases follow a checklisted flow: pre-release checks, staging smoke tests, automated deploy pipelines to production, post-deploy verifications, and a documented rollback/incident playbook. Retrospectives capture learnings and convert them into tracked action items.

## Docs and links
- Project management overview: docs/octoacme-project-management-overview.md
- Project initiation: docs/octoacme-project-initiation.md
- Project planning: docs/octoacme-project-planning.md
- Execution & tracking: docs/octoacme-execution-and-tracking.md
- Risks & communication: docs/octoacme-risks-and-communication.md
- Release & deployment: docs/octoacme-release-and-deployment.md
- Retrospective & improvement: docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & personas: docs/octoacme-roles-and-personas.md

## How to use this README
- Use this README as the entry point when onboarding new team members or starting a project.
- Open the Project One-pager template in the initiation doc when starting a new initiative.
- Keep the risk register updated and surface major blockers in the weekly PM+PdM sync.

## Issue reference
This change implements the README requested in issue #2.
