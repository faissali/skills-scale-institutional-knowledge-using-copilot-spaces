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

## QA Lead / Test Engineer

### Role Summary
QA Leads own testing strategy and quality assurance for features. They collaborate with developers and product on acceptance criteria, automate regression tests, and validate readiness for release.

### Responsibilities
- Define test plans and validate acceptance criteria
- Write and maintain automated and manual test cases
- Perform exploratory testing and identify edge cases
- Report defects with clear, reproducible steps
- Coordinate with developers on test coverage and CI/CD validation

### Goals
- Prevent defects from reaching production
- Reduce manual testing overhead through automation
- Build confidence in release readiness

### Typical Communication
- Sprint planning and acceptance criteria reviews
- Code review comments on testability
- Bug reports and pre-release sign-off

### Interactions with Other Roles
- Partner with Product Managers to clarify acceptance criteria and expected behavior.
- Work with Developers to plan test coverage, reproduce defects, and verify fixes.
- Coordinate with Project Managers on test milestones, quality risks, and release readiness.

---

## Technical Architect

### Role Summary
Technical Architects design system-level solutions and guide technical decisions across projects. They ensure scalability, maintainability, and alignment with organizational standards.

### Responsibilities
- Review and approve high-level technical designs
- Identify technical risks and propose mitigation
- Guide teams on architectural patterns and technology choices
- Mentor developers on design best practices
- Conduct technical design reviews and maintain architecture documentation

### Goals
- Ensure solutions are scalable and maintainable
- Reduce technical debt
- Align projects with organizational technology strategy

### Typical Communication
- Design documents and technical reviews
- Architecture decision records (ADRs)
- Escalations for cross-system impacts

### Interactions with Other Roles
- Advise Developers on design choices, technical risks, and implementation trade-offs.
- Work with Product Managers to assess feasibility and clarify technical implications of priorities.
- Help Project Managers understand architectural dependencies, risks, and decision timelines.

---

## Stakeholder / Sponsor

### Role Summary
Sponsors provide business context, approve resource allocation, and ensure projects deliver on strategic objectives. They champion projects and remove organizational blockers.

### Responsibilities
- Define business requirements and success criteria
- Allocate budget and resources
- Approve go/no-go decisions at key gates
- Escalate external dependencies and blockers
- Communicate project value to leadership

### Goals
- Ensure business value is delivered
- Maintain executive alignment and support
- Remove organizational barriers to execution

### Typical Communication
- Initiation meetings and milestone reviews
- Executive summaries and decision gates
- Escalations on resources, dependencies, and blockers

### Interactions with Other Roles
- Align with Product Managers on business outcomes, requirements, and measures of success.
- Work with Project Managers on scope, funding, risks, milestones, and decisions requiring sponsorship.
- Consult Developers on delivery feasibility and technical constraints when making major trade-offs.

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team ceremonies, remove process blockers, and coach teams on iterative delivery practices.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and escalate process impediments
- Mentor the team on Agile practices and iterative delivery
- Maintain burndown and velocity tracking
- Drive continuous improvement from retrospectives

### Goals
- Improve team velocity and predictability
- Foster psychological safety and continuous learning
- Reduce cycle time

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospectives, sprint metrics, and impediment logs
- Continuous-improvement follow-ups

### Interactions with Other Roles
- Facilitate planning with Product Managers so priorities and acceptance criteria are understood by the team.
- Help Developers coordinate work, surface blockers, and improve team practices without directing technical decisions.
- Coordinate with Project Managers on dependencies, delivery forecasts, and escalated impediments.

---

## Support / Operations Lead

### Role Summary
Operations teams ensure deployed solutions run reliably, handle incidents, and provide feedback on production readiness and maintainability.

### Responsibilities
- Validate operational readiness before release, including runbooks, dashboards, and alerting
- Monitor production health and respond to incidents
- Provide feedback on observability and maintainability
- Coordinate with developers on post-deployment issues
- Document operational procedures

### Goals
- Maintain high availability and reliability
- Reduce mean time to resolution (MTTR) for incidents
- Improve observability

### Typical Communication
- Pre-release readiness reviews
- Incident response and post-incident follow-up
- Operational feedback and runbook documentation

### Interactions with Other Roles
- Work with Developers to ensure services are observable, supportable, and recoverable, and to resolve production issues.
- Advise Product Managers on operational impact and reliability needs that affect product priorities.
- Coordinate with Project Managers on release readiness, operational risks, and incident-related dependencies.

---

## How these roles work together in the project lifecycle

- **Initiation:** Stakeholders / Sponsors define business outcomes and provide support; Product Managers clarify the problem and success criteria; Project Managers coordinate scope, resources, and the initial plan. Technical Architects identify early design constraints.
- **Planning and design:** Product Managers prioritize requirements, Project Managers coordinate milestones and dependencies, and Developers and Technical Architects shape a feasible solution. QA Leads help make acceptance criteria testable, while Scrum Masters facilitate team planning.
- **Delivery:** Developers implement and test the work, QA Leads validate behavior and expand automated coverage, and Scrum Masters help the team address impediments and improve its process. Project Managers track risks and progress, with Product Managers resolving priority questions.
- **Release and operation:** QA Leads and Developers confirm quality, Technical Architects advise on significant technical risks, and Support / Operations Leads validate runbooks, monitoring, and operational readiness. Project Managers coordinate release decisions; Sponsors make go/no-go decisions at agreed gates.
- **Feedback and improvement:** Support / Operations Leads share production health and incident learnings; QA Leads report quality trends; Developers address follow-up work; Product Managers use outcomes to reprioritize; and Scrum Masters and Project Managers help the team turn lessons into process improvements. Sponsors review business outcomes and provide continued direction.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
