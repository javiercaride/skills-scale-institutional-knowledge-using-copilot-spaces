# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This folder contains the process documents, templates, and checklists that guide how we plan, execute, and improve projects across OctoAcme.

## Project Management Processes — Summary

OctoAcme runs projects through a clear, principle-driven lifecycle that emphasizes customer value, iterative delivery, and clear ownership. Projects move from Initiation (problem definition, stakeholder alignment, and a one‑pager) into Planning (kickoff, prioritized backlog, estimates, and a release plan), then Execution (build, test, review), followed by Release (deploy, verify, announce) and Close & Retrospective (capture learnings and convert them into action items). The program is guided by principles like customer-first decision‑making, data‑informed iteration, and psychological safety, and relies on a compact set of key artifacts—one‑pagers, roadmaps, backlogs, acceptance criteria, risk registers, and retrospective notes—to keep work aligned and discoverable.

Workflows are concretized in the project board and pull request practices. Teams use a columns-based board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined PR workflow that favors small, focused changes, links PRs to issues and acceptance criteria, and requires CI (tests, linting, security scans) plus at least one approval before merging. Planning activities break work into shippable increments, capture acceptance criteria and DoD for each backlog item, and maintain a risk register for dependencies and mitigations. The docs also provide practical checklists for execution, release, and deployment to reduce friction and support repeatable, low‑risk rollouts.

OctoAcme defines explicit personas and responsibilities to make accountability and collaboration predictable: Project Managers coordinate delivery, schedules, risks, and communications; Product Managers (PdMs) own outcomes, prioritize the backlog, and define success metrics; Developers implement features and maintain tests and docs; QA/Testing validates acceptance criteria and quality gates; and Stakeholders provide input and approvals. These role definitions are used to assign ownership of artifacts (e.g., Risk Register owners, action‑item owners from retrospectives) and to drive decisions at the appropriate level.

Communication and quality assurance are structured and recurring. Team rhythm includes daily standups for blockers, weekly delivery syncs for progress and risk review, sprint demos/reviews, and monthly stakeholder updates; escalation follows a tiered path (team → PM → Product Lead → Sponsor) for business‑impacting issues. QA practices blend automated and manual approaches: unit and integration tests, end‑to‑end smoke checks for critical flows, security scanning in CI, and manual QA where needed. Progress and health are monitored via velocity, burndown, and dashboards tied to project one‑pager metrics, while retrospectives convert learnings into tracked action items to continually improve the process.

## Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## How to use these docs

- To propose changes, open a new issue using the "Add Content to Project Management Process Docs" template located at .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml.
- Keep the Project One-pager and any project-specific artifacts in the project repo and link them here.
- If you want Copilot Spaces to use a process doc as context, add a copy to .copilot/ in the project.
