# OctoAcme Project Management Docs

Central index for OctoAcme's project management process documentation. OctoAcme runs projects with a customer-first, iterative, data-informed approach, delivering small testable increments with clear ownership.

## Process Documents

| Document | Description |
| --- | --- |
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, scope, and key artifacts |
| [Project Initiation](octoacme-project-initiation.md) | Validating and authorizing new work |
| [Project Planning](octoacme-project-planning.md) | Backlog, estimation, and Definition of Done |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Team rhythm, boards, PR workflow, and QA |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register, cadence, and escalation |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types and pre-release requirements |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and actions |
| [Roles & Personas](octoacme-roles-and-personas.md) | Responsibilities of PMs, Product Managers, and Developers |

## Summary

### Project Lifecycle
Projects move through **Initiation → Planning → Execution → Release → Retrospective**. Initiation validates the business need with a lightweight one-pager; planning breaks work into shippable increments with a prioritized backlog, acceptance criteria, and a Definition of Done; execution delivers and tracks the work; release ships it safely; the retrospective feeds learnings back.

### Key Roles
- **Project Managers** coordinate schedules, risks, and communications.
- **Product Managers** define outcomes and prioritize the backlog.
- **Developers** implement features and collaborate on design and testability.

### Communication
Daily standups (15 min), weekly PM–Product Manager syncs, and monthly stakeholder updates. Escalations flow from team to PM to Product Lead to Sponsor.

### Quality Assurance & Execution
Work is tracked on a project board (Backlog, Ready, In Progress, In Review, QA, Done). Small PRs (≤ 400 lines) link issues and acceptance criteria, run CI tests and linting, and need at least one approval. Unit, integration, and smoke tests plus security scanning gate releases.

### Risk Management & Continuous Improvement
A risk register is reviewed weekly. Releases (Patch, Minor, Major) require passing CI, security scans, and a rollback plan. Retrospectives after sprints, releases, and incidents produce 2–3 actionable improvements, supported by blameless post-mortems.
