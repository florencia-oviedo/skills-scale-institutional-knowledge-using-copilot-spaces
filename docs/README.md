# OctoAcme — Project Management Processes

## Purpose
- Provide a concise, shareable summary of how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.
- Centralize process guidance used across initiation, planning, execution, release, and continuous improvement.

## Quick links to process docs
- Initiation: docs/octoacme-project-initiation.md
- Planning: docs/octoacme-project-planning.md
- Execution & Tracking: docs/octoacme-execution-and-tracking.md
- Risks & Communication: docs/octoacme-risks-and-communication.md
- Release & Deployment: docs/octoacme-release-and-deployment.md
- Retrospectives & CI: docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas: docs/octoacme-roles-and-personas.md

## Core principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate using evidence.
- Psychological safety: encourage feedback and learning.

## Lifecycle (high-level)
1. Initiation — Validate problem, stakeholders, success metrics, and create a one-pager.
2. Planning — Build backlog, estimates, definition of done, and a release plan.
3. Execution — Implement in small increments, use PRs and CI, track velocity and risks.
4. Release — Follow pre-release checks, deploy, verify, and communicate.
5. Close & Retrospective — Capture learnings and convert them into action items.

## Team rhythm & collaboration
- Daily standups (15 min) for progress, blockers, and dependencies.
- Weekly delivery sync to show progress and calibrate risks.
- Demo/Review at the end of each sprint or milestone.
- Weekly PM + Product Lead sync and monthly stakeholder updates.

## Workflows & quality
- Project board columns: Backlog, Ready, In Progress, In Review, QA, Done.
- PR guidance: small PRs when possible, include issue link and acceptance criteria, run CI and tests before review, require approvals per team policy.
- Testing: unit tests, integration tests as applicable, smoke tests before releases, security scanning in CI, and manual QA for acceptance.

## Risk & escalation
- Maintain a Risk Register with owner, impact, likelihood, mitigation, and status.
- Escalation path: Team → PM → Product Lead → Sponsor (security incidents follow security runbook).

## Reporting & metrics
- Track velocity, burndown, and success metrics in the Project One-pager.
- Use dashboards for key signals (errors, latency, usage).

## How to use these docs
- Keep the Project One-pager updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
- For changes to process docs, use the issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Contributing
- To propose additions or updates to these process docs, open an issue using the “Add Content to Project Management Process Docs” template and reference the relevant doc.
