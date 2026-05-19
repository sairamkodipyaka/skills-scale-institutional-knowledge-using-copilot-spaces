# OctoAcme Project Management Docs

Welcome! This directory is the central hub for OctoAcme's project management process documentation.

## Project Management Process Summary

OctoAcme employs a structured, iterative project management approach designed around clear ownership, data-driven decisions, and psychological safety. The organization follows a five-phase lifecycle—**Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**—that moves work from problem statement to production and captures learnings for continuous improvement.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Key Roles & Responsibilities

**Project Managers (PM)** coordinate delivery activities, manage schedules, risks, and communications. They ensure consistent project documentation, facilitate key meetings, and maintain stakeholder alignment.

**Product Managers (PdM)** define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes through success metrics.

**Developers** design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and maintain high quality standards.

**QA/Testing** validates quality and acceptance criteria, ensuring features meet requirements before release.

### Execution Approach

The execution layer emphasizes iterative delivery through disciplined workflows and quality gates. Teams work in sprints using a GitHub Projects board organized into: Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require automated testing, linting, and at least one approval before merge.

**Communication Cadence:**
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly PM + PdM sync — alignment and decision-making
- Twice-weekly delivery standups — team coordination
- Weekly delivery sync — show progress, updates, and flagged risks
- Monthly stakeholder updates — keep executive sponsors informed

### Quality Assurance & Testing

Quality is integrated throughout the delivery cycle:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Risk Management & Communication

Risk management is treated as a continuous, integral activity. The organization maintains a **Risk Register** (capturing ID, description, impact, likelihood, owner, and mitigation plan) that is reviewed weekly. Escalation follows a clear three-level path: team-level triage in standups, PM escalation to Product Leads and dependent teams, and sponsor-level escalation for business-impacting issues.

### Continuous Improvement

OctoAcme closes the feedback loop through structured retrospectives held after each sprint, release, or milestone. These sessions assess what went well, identify improvements, and generate 2–3 prioritized action items with clear owners and due dates. Combined with metrics dashboards tracking velocity, burndown, and success indicators, this approach enables teams to deliver reliably and evolve their processes based on evidence.

---

## Documentation Index

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, core roles, key artifacts, and communication cadence.

### Project Phases

- **[Project Initiation Guide](octoacme-project-initiation.md)** — Define initial steps to validate work, align stakeholders, and create a lightweight plan. Includes the Project One-pager template and initiation checklist.

- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog. Covers kickoff, backlog prioritization, estimation, Definition of Done, and dependency management.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution, tracking progress toward milestones, quality standards, and blocker escalation.

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Explain how to identify, manage, and communicate risks, dependencies, and stakeholder updates. Includes the Risk Register template and escalation paths.

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production. Covers release types, pre-release requirements, deployment checklist, and rollback procedures.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements. Includes retrospective structure and action item tracking.

### Reference

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed definitions of typical roles (Developers, Product Managers, Project Managers) used in OctoAcme projects, including responsibilities, goals, and communication patterns.

---

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction.

2. **Starting a new project?** Follow the phase guides in order: Initiation → Planning → Execution → Release → Retrospective.

3. **Need a specific template?** Each phase doc includes templates and checklists (One-pager, Backlog Item, Risk Register, Release Notes, etc.).

4. **Want to contribute?** See the [Add/Update Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose improvements.

---

## Contributing

These docs are living artifacts that evolve with OctoAcme's practices. If you have suggestions, improvements, or want to add new content, please:

1. Create an issue using the **Add Content to Project Management Process Docs** template.
2. Describe the update, why it's needed, and propose content if available.
3. Collaborate with the team to refine and merge improvements.

Your feedback helps us maintain clear, up-to-date, and actionable process documentation for the entire team.
