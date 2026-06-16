# OctoAcme Project Management Docs

This README provides a navigable entry point to OctoAcme's project management processes and direct links to the process documents stored in the `docs/` folder.

## OctoAcme Project Management Overview

OctoAcme operates a structured, five-phase project lifecycle designed to deliver customer value while maintaining clear ownership, transparency, and continuous improvement. The approach begins with **Initiation** to validate business need and align stakeholders around clear success metrics, progresses through **Planning** to break work into shippable increments with acceptance criteria, moves into **Execution** with iterative delivery and continuous progress tracking, culminates in **Release** with standardized deployment protocols and rollback playbooks, and concludes with **Retrospectives** to capture learnings and drive continuous improvement.

The organization defines clear role ownership across primary personas: **Product Managers** who own the product vision and prioritize the backlog based on customer value; **Project Managers** who coordinate delivery, manage risks, dependencies, and stakeholder communications; and **Developers** who design, implement, and test features while collaborating on estimation, design reviews, and technical risk mitigation. This separation of concerns ensures focused accountability while maintaining cross-functional collaboration through structured communication rhythms including daily standups, weekly delivery syncs, and regular stakeholder updates.

Quality and risk management are embedded throughout the execution cycle. Teams enforce a rigorous pull request workflow with small PRs (≤400 lines when possible), automated CI testing and linting before review, and required approvals. Testing is comprehensive—unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI. Risk management follows a structured escalation path (team-level triage → PM escalation → sponsor escalation) with a maintained Risk Register tracking impact, likelihood, ownership, and mitigation plans. Teams also track velocity, burndown, and success metrics to make evidence-based decisions and continuously improve processes through sprint retrospectives.

The foundation of OctoAcme's approach rests on clear artifacts and single sources of truth: a **Project One-pager** capturing problem statement, goals, and success metrics; a **prioritized backlog** with acceptance criteria and estimates; a **Definition of Done** ensuring consistent quality; a **Risk Register** maintained and reviewed weekly; and **release notes** documenting changes, migration steps, and known issues. This documentation discipline, combined with the organization's commitment to iterative delivery, data-informed decisions, and continuous learning, enables consistent, repeatable project execution while reducing single-person dependency risk and accelerating team onboarding.

---

## Process Phases at a Glance

- **Initiation**: Capture problem statement, stakeholders, one-pager, and initial decision gate for planning.
- **Planning**: Create prioritized backlog, estimates, release plan, and Definition of Done.
- **Execution & Tracking**: Use project boards, PR conventions, CI checks, daily standups, and weekly delivery syncs to track progress.
- **Release & Deployment**: Follow pre-release checks, automated deployment pipelines, smoke tests, and rollback plans.
- **Risk & Communication**: Maintain a risk register, weekly status updates, and defined escalation paths.
- **Retrospective & Continuous Improvement**: Run retrospectives, track action items, and measure improvements.
- **Roles & Personas**: Define responsibilities for PM, PdM, Developers, and QA to ensure clear ownership.

---

## Process Documents Index

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Concise introduction to OctoAcme's project management approach, core roles, and lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | Initial steps to validate work, align stakeholders, and create a lightweight plan |
| [Project Planning](octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and prioritized backlog |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Guidance for managing day-to-day execution and tracking progress toward milestones |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardized processes to release features to production with reduced risk |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | How to identify, manage, and communicate risks and dependencies |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [Roles & Personas](octoacme-roles-and-personas.md) | Define typical roles and responsibilities (PM, PdM, Developers, QA) |

---

## How to Use These Docs

### For Project Leads & PMs
- Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand the full lifecycle
- Follow the phase-specific guides (Initiation → Planning → Execution → Release) in sequence for new projects
- Reference the [Risk Management & Communication](octoacme-risks-and-communication.md) guide regularly to maintain stakeholder alignment

### For Developers & Team Members
- Review [Roles & Personas](octoacme-roles-and-personas.md) to understand your responsibilities
- Check [Execution & Tracking](octoacme-execution-and-tracking.md) for PR conventions, testing requirements, and quality standards
- Reference [Release & Deployment Guide](octoacme-release-and-deployment.md) before shipping to production

### For Copilot Spaces & Contributors
- Link this README from project READMEs and project boards as the single source of truth for process guidance
- Use the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` template to request additions or updates to these docs
- Keep process docs up-to-date as team practices evolve

---

## Contributing to Process Docs

To propose updates or additions to these process documents:

1. Create an issue using the **"Add Content to Project Management Process Docs"** template (available in `.github/ISSUE_TEMPLATE/`)
2. Provide a summary of the new content or update, and explain why it's needed
3. Include suggested content and acceptance criteria
4. A PM or team lead will review, integrate, and merge your contribution

---

## Questions?

If you have questions about OctoAcme's project management processes, start here:
- Review the relevant process document for your phase or role
- Check the associated checklists and templates
- Reach out to your Project Manager or Product Lead for guidance on your specific project
