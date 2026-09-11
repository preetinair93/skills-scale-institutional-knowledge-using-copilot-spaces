# OctoAcme Project Management Processes

Welcome to the OctoAcme project management documentation. This README provides an overview of how OctoAcme runs projects and links to detailed process guides.

## Purpose

These documents centralize project management knowledge to ensure consistent, repeatable project execution across the organization. They serve as a searchable, versioned reference for all team members and help accelerate onboarding.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow a structured five-phase lifecycle:

1. **Initiation** — Define the problem, align stakeholders, and validate the business need
2. **Planning** — Break work into shippable increments, identify dependencies, and establish timelines
3. **Execution** — Build, test, review, and iterate with regular progress tracking
4. **Release** — Deploy to production with verified quality and stakeholder communication
5. **Close & Retrospective** — Capture learnings and convert them into actionable improvements

## Key Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Process Documents

### [Project Management Overview](octoacme-project-management-overview.md)
A concise introduction to OctoAcme's approach, roles, and key artifacts. Start here if you're new to the team.

### [Project Initiation Guide](octoacme-project-initiation.md)
Guidance for validating and authorizing work, aligning stakeholders, and creating a lightweight plan. Use this when starting a new project.

**Key Deliverables:**
- Project One-pager (Problem, Goal, Success Metrics)
- Stakeholder list & communication plan
- High-level timeline and key milestones

### [Project Planning](octoacme-project-planning.md)
Turn an approved initiative into an actionable plan and backlog for delivery. Covers backlog creation, estimation, Definition of Done, and risk management.

**Key Activities:**
- Project kickoff with stakeholders and delivery team
- Create prioritized backlog with acceptance criteria
- Define Definition of Done (DoD)
- Identify dependencies and create release plan

### [Execution & Tracking](octoacme-execution-and-tracking.md)
Guidance for managing day-to-day execution and tracking progress toward milestones. Covers team rhythm, workflows, quality standards, and blocker escalation.

**Key Practices:**
- Daily standups (15 min) and weekly delivery syncs
- GitHub Projects with standard columns: Backlog, Ready, In Progress, In Review, QA, Done
- Small PRs (≤400 lines) with issue links and acceptance criteria
- Automated testing, linting, and security scanning in CI

### [Risk Management & Communication](octoacme-risks-and-communication.md)
How to identify, assess, and manage risks and dependencies. Covers risk registers, stakeholder communication, and escalation paths.

**Key Components:**
- Risk Register with ID, Description, Impact, Likelihood, Owner, and Mitigation
- Weekly status updates and stakeholder communication templates
- Three-level escalation path for blocker resolution

### [Release & Deployment Guide](octoacme-release-and-deployment.md)
Standardize how OctoAcme releases features to production. Covers release types, pre-release requirements, deployment checklists, and rollback procedures.

**Release Types:**
- Patch: hotfixes for critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

### [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
Capture learnings and convert them into actionable improvements. Conducted after each sprint, release, or important milestone.

**Structure:**
- What went well
- What could be improved
- Action items with owners and due dates
- Follow-up on previous action items

### [Roles & Personas](octoacme-roles-and-personas.md)
Detailed definitions of typical roles (Developers, Product Managers, Project Managers) used throughout OctoAcme documentation, including responsibilities, goals, and communication patterns.

## Communication Cadence

- **Daily**: Team standups (15 min)
- **Weekly**: PM + PdM sync, twice-weekly delivery team standups
- **Monthly**: Stakeholder updates
- **As-needed**: Ad-hoc escalations and incident communications

## Key Artifacts

Every project maintains:
- **Project Charter / One-pager** — Problem, goal, success metrics
- **Roadmap & Release Plan** — Timeline and key milestones
- **Sprint/Iteration Backlog** — Prioritized work with acceptance criteria
- **Risk Register** — Identified risks, impacts, and mitigation plans
- **Retrospective Notes** — Learnings and action items

## Getting Started

1. **New to the team?** Start with [Project Management Overview](octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
3. **Planning your first sprint?** Use [Project Planning](octoacme-project-planning.md)
4. **Day-to-day questions?** Check [Execution & Tracking](octoacme-execution-and-tracking.md)
5. **Preparing for release?** Review [Release & Deployment Guide](octoacme-release-and-deployment.md)
6. **Wrapping up a project?** Conduct a [Retrospective](octoacme-retrospective-and-continuous-improvement.md)

## Contributing to Process Docs

We continuously improve our processes based on team feedback and lessons learned. To propose updates or new content:

1. Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
2. Describe the gap, rationale, and suggested content
3. The team will review and incorporate improvements

## Questions?

If you have questions about any process or need clarification, reach out to your Project Manager or Product Lead. Process improvements are always welcome!
