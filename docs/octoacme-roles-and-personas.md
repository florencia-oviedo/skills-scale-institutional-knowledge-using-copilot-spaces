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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas / Roles (Proposed Additions)

To improve clarity of ownership, handoffs, and cross-functional collaboration, add the following personas to the core list above. Each persona below includes responsibilities and how they typically interact with existing roles.

### UX Designer
- Responsibilities:
  - Lead user research activities (surveys, interviews, usability testing).
  - Create wireframes, high-fidelity mocks, and interactive prototypes.
  - Define usability acceptance criteria and provide design assets for implementation.
  - Validate designs against success metrics and iterate based on feedback.
- Interacts with:
  - Product Manager (PdM) — to clarify requirements and success criteria.
  - Developers — for design handoffs, accessibility guidance, and implementation reviews.
  - QA — to ensure UI/UX acceptance tests and regressions are covered.
  - Stakeholders/Customers — to surface research findings and align on UX tradeoffs.
- Typical Handoff Points:
  - From PdM to UX at discovery kickoff.
  - From UX to Developers upon completion of design artifacts and spec sign-off.
  - From UX to QA for test-case validation.

### Business Analyst (BA)
- Responsibilities:
  - Translate high-level business needs into detailed requirements and user stories.
  - Map workflows, processes, and data flows; document business logic.
  - Define and refine acceptance criteria and edge cases.
  - Support stakeholder interviews and clarify ambiguous requirements.
- Interacts with:
  - PM — for scope, prioritization, and planning.
  - PdM — for alignment on outcomes and success metrics.
  - Developers & QA — to provide context, clarify questions, and validate delivered functionality.
- Typical Handoff Points:
  - From PdM/Stakeholders to BA for requirements gathering.
  - From BA to engineering during refinement sessions.

### Scrum Master
- Responsibilities:
  - Facilitate agile ceremonies (standups, retrospectives, planning).
  - Remove team-level impediments and coach teams on agile best practices.
  - Track team health, velocity, and process improvements.
  - Protect the team from unnecessary interruptions and help enforce working agreements.
- Interacts with:
  - Delivery team members (Developers, QA, UX) — daily facilitation and coaching.
  - PM — escalate impediments and coordinate on cross-team dependencies.
  - Stakeholders — manage expectations and surface cadence-related updates.
- Typical Handoff Points:
  - Ongoing coordination during sprints and when process changes are needed.

### Support Lead (Operations / Support Representative)
- Responsibilities:
  - Act as the primary contact for production issues and support escalations.
  - Coordinate incident response and post-incident reviews.
  - Ensure runbooks, support documentation, and knowledge transfer are up to date.
  - Collect customer-reported issues and feed them back into the backlog.
- Interacts with:
  - Developers & QA — for troubleshooting and hotfix coordination.
  - PM — for post-release tracking and customer communication.
  - Stakeholders/Customers — for status updates and impact communications.
- Typical Handoff Points:
  - Pre-release: receive release notes and runbooks from engineering.
  - Post-release: manage incidents and create follow-up tasks.

### Release Engineer / CI-CD Owner (optional)
- Responsibilities:
  - Maintain CI/CD pipelines and deployment automation.
  - Define and run release validations and rollback procedures.
  - Ensure releases meet pre-release criteria and security hardening.
- Interacts with:
  - Developers — for pipeline integration and build issues.
  - PM/Support Lead — for release coordination and rollback decisions.
  - Security Liaison — for release-related security checks.
- Typical Handoff Points:
  - Prior to a release to ensure pipelines and automation are validated.

### Security Liaison (optional)
- Responsibilities:
  - Coordinate security reviews, threat modeling, and vulnerability triage.
  - Ensure security requirements and compliance checks are included in planning.
- Interacts with:
  - Developers/QA — to prioritize and remediate security findings.
  - PM/PdM — to communicate security impacts and timelines.
- Typical Handoff Points:
  - During planning for any security-sensitive features; before production deployment.

---

## Using these personas effectively

- Add persona ownership lines to relevant artifacts (e.g., story cards, the One-pager, release notes).
- Document handoffs clearly in the project README and in the “Personas & Handoffs” checklist (new doc).
- During kickoff, explicitly call out who will take each persona responsibility (especially for cross-team work).
- Revisit persona coverage during retrospectives to fill gaps or adjust responsibilities.
