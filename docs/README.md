# OctoAcme Project Management Docs

This README provides a comprehensive overview of OctoAcme's project management processes and direct links to the full process documents in the docs/ folder. Whether you're onboarding to a new project or looking for guidance on a specific phase, start here.

## Quick Links to Process Docs

- [Project Management Overview](octoacme-project-management-overview.md) — Concise introduction to OctoAcme's approach, core roles, principles, and key artifacts.
- [Project Initiation Guide](octoacme-project-initiation.md) — Steps and templates for validating and authorizing new projects.
- [Project Planning](octoacme-project-planning.md) — Planning activities, backlog templates, risk capture, and dependency management.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day rhythm, workflows, team cadence, quality practices, and reporting.
- [Risks & Communication](octoacme-risks-and-communication.md) — Risk register guidance, communication templates, and escalation paths.
- [Release & Deployment](octoacme-release-and-deployment.md) — Release types, deployment checklist, and rollback playbook.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Running retros, tracking action items, and measuring improvements.
- [Roles & Personas](octoacme-roles-and-personas.md) — Role definitions and responsibilities used across OctoAcme project docs.

---

## OctoAcme Project Management Processes Overview

### Lifecycle & Core Phases

OctoAcme follows a structured five-phase lifecycle: **Initiation, Planning, Execution, Release, and Close & Retrospective**. This approach emphasizes customer-first delivery, iterative increments, and clear ownership at every stage.

**Initiation** begins with problem validation through a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and initial risks. This gate ensures business alignment before moving forward. **Planning** breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. Teams estimate scope using T-shirt sizing or story points and create a release plan that identifies dependencies and integration points. **Execution** leverages a project board (GitHub Projects) organized with columns from Backlog through Done, supported by daily standups (15 min), weekly delivery syncs, and end-of-sprint demos. Pull requests are kept small (≤400 lines), include issue links and acceptance criteria, and require at least one approval before merging.

### Quality, Testing & Release

Quality and testing are embedded throughout execution rather than deferred to the end. OctoAcme requires unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. All code runs through automated CI testing and security scanning before peer review. The **Release phase** standardizes deployment through pre-release checklists, smoke tests in staging, and a documented rollback plan to minimize production risk. Post-deployment verifications and stakeholder announcements ensure transparency. Finally, **Retrospectives** are conducted after sprints and releases to capture learnings, identify improvements, and assign action items with clear owners and due dates.

### Roles, Communication & Risk Management

The organizational structure defines three core delivery personas: **Developers** who implement features and maintain quality; **Product Managers** who prioritize the roadmap and define success metrics; and **Project Managers** who coordinate schedules, risks, and communications. Communication follows a structured cadence with weekly PM/PdM syncs, twice-weekly team standups, and monthly stakeholder updates. Risk management is formalized through a **Risk Register** tracking ID, description, impact/likelihood, owner, mitigation, and status—reviewed weekly and escalated through clear paths (Team → PM → Product Lead → Sponsor). Status updates use a consistent template covering progress, next steps, risks/blockers, and decisions needed, ensuring stakeholders remain informed and risks are surfaced early.

### Continuous Improvement Culture

OctoAcme's approach ties process rigor to learning and adaptation. By capturing retrospective action items in the backlog with owners and success criteria, measuring their impact, and celebrating improvements, the organization creates a culture of psychological safety and iterative enhancement. This balance between structured governance and learning-focused iteration enables consistent delivery while remaining responsive to feedback and changing conditions.

---

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md).
- **Starting a new project?** Follow the path: [Initiation](octoacme-project-initiation.md) → [Planning](octoacme-project-planning.md) → [Execution & Tracking](octoacme-execution-and-tracking.md).
- **Unsure about your role?** Review [Roles & Personas](octoacme-roles-and-personas.md).
- **Need to escalate a risk or blocker?** See [Risks & Communication](octoacme-risks-and-communication.md).
- **Preparing a release?** Reference [Release & Deployment](octoacme-release-and-deployment.md).
- **Wrapping up and reflecting?** Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

Each document is self-contained and includes checklists, templates, and practical guidance for that phase. Links between docs help you navigate the full lifecycle.
