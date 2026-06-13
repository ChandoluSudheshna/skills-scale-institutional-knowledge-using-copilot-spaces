# OctoAcme Project Management Process Docs

Welcome to OctoAcme's centralized project management documentation. This folder contains all program and project management process guides that enable consistent, repeatable project execution across teams.

## Quick Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The methodology spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business needs by creating a lightweight Project One-pager that captures the problem statement, objectives, success metrics, and stakeholder alignment—serving as the decision gate to move into planning. The Planning phase transforms approved initiatives into actionable backlogs by breaking work into shippable increments, estimating scope, defining acceptance criteria and a Definition of Done, and identifying dependencies and risks. This structured approach ensures that all stakeholders share a common understanding before development begins and reduces unplanned work later.

Execution and delivery are managed through a team rhythm that includes daily standups (15 minutes focused on progress and blockers), weekly delivery syncs, and sprint-based iteration cycles. Teams use GitHub Projects or similar tools to visualize workflow stages—Backlog, Ready, In Progress, In Review, QA, and Done—and maintain small pull requests (≤400 lines) with clear issue links and acceptance criteria. Quality is embedded throughout the process via unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI/CD pipelines, and manual QA for feature acceptance when needed. This multi-layered quality approach is reinforced by a requirement for at least one code review approval before merging and automated testing in CI before review requests.

OctoAcme defines clear roles and responsibilities across three primary personas: **Developers** implement features and maintain tests; **Product Managers** define what should be built and prioritize the backlog based on customer and business value; and **Project Managers** coordinate delivery, manage risks and dependencies, and ensure transparent communication. Risk and dependency management are central to the process, with a Risk Register updated weekly that tracks ID, description, impact, likelihood, owner, and mitigation plans. Communication follows a structured cadence—weekly PM/PdM syncs, twice-weekly team standups, and monthly stakeholder updates—supported by templates for status updates and incident communication. Escalation paths are clearly defined (Team-level → PM → Product Lead → Sponsor), enabling rapid response to blockers while maintaining appropriate governance levels.

After each sprint, release, or milestone, teams conduct retrospectives to capture learnings and convert them into actionable improvements. The process emphasizes psychological safety and data-informed decisions, with impact measurement for action items and celebration of improvements. This continuous improvement cycle, combined with pre-release checklists covering acceptance criteria, CI/security scans, rollback plans, and smoke tests, ensures that OctoAcme delivers reliable, maintainable software while learning and adapting throughout the project lifecycle.

## Process Docs Index

Start with the **Project Management Overview** for a concise introduction, then use the other docs as needed for detailed procedures and checklists.

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Concise intro to OctoAcme roles, key artifacts, and the high-level project lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to validate and authorize new work; includes one-pager template and initiation checklist |
| [Project Planning](octoacme-project-planning.md) | Break approved initiatives into actionable backlogs; includes backlog templates, sprint planning, and risk capture |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution; team rhythm, PR workflows, CI conventions, quality gates, and blocker escalation |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register, stakeholder communication, status templates, and escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release checklists, deployment steps, rollback playbook, and release notes template |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | How to run retrospectives, track improvements, and foster a culture of continuous learning |
| [Roles & Personas](octoacme-roles-and-personas.md) | Definitions of Developers, Product Managers, and Project Managers; responsibilities and typical communications |

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md), then explore docs that match your role or current phase.
- **Running a project?** Refer to each phase doc (Initiation → Planning → Execution → Release → Retrospective) in order.
- **Need a checklist or template?** Each doc includes practical checklists and templates ready to adapt for your project.
- **Proposing updates?** Use the `Add Content to Project Management Process Docs` issue template in `.github/ISSUE_TEMPLATE/` to request changes or additions.

## Key Principles

OctoAcme's approach is built on these core principles:

- **Customer-first:** Prioritize customer value and usability.
- **Iterative delivery:** Deliver small, testable increments.
- **Clear ownership:** Each project has named owners (PM and Product Lead).
- **Data-informed:** Measure impact and iterate based on evidence.
- **Psychological safety:** Encourage feedback, learning, and blameless retrospectives.

## Contributing to Process Docs

Help us improve and maintain these documents:

1. **Spot a gap or unclear section?** Open an issue using the `Add Content to Project Management Process Docs` template.
2. **Have a suggestion for a new doc or section?** Describe the need and propose content.
3. **Found an error?** Submit a PR with the correction.

Changes to process docs should align with existing materials and be reviewed for clarity and consistency.
