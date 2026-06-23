# OctoAcme Project Management Docs

This README provides a comprehensive overview of OctoAcme's project management processes and quick links to the detailed process documents in this folder.

## Project Management Processes Overview

OctoAcme operates a structured, lifecycle-based project management approach designed around five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. The process emphasizes customer-first principles, iterative delivery, and clear ownership through defined roles.

### Key Phases

**Initiation** validates business need through a lightweight Project One-pager that captures the problem statement, success metrics, stakeholder alignment, and resource requirements. This gates the decision to move into **Planning**, where the initiative is broken down into a prioritized, estimated backlog with clear acceptance criteria and a release plan.

Throughout **Execution**, teams maintain a structured rhythm of daily 15-minute standups, weekly delivery syncs, and sprint-based iterations using GitHub Projects with columns spanning from Backlog through Done. Quality is embedded throughout via unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA as needed—all before a pull request can be merged.

**Release & Deployment** follows pre-release requirements including passing CI and security scans, drafted release notes, and a documented rollback plan. After each sprint, release, or milestone, teams run a structured **Retrospective** to capture what went well, what could improve, and generate 2–3 prioritized action items with clear owners and due dates—closing the feedback loop and driving continuous improvement.

### Roles & Communication

The project structure relies on clear role differentiation and regular communication touchpoints. **Project Managers** coordinate delivery schedules, manage risks and dependencies, and ensure transparent status reporting. **Product Managers** define outcomes, prioritize the backlog, and measure success against established metrics. **Developers** implement features, collaborate on design, and maintain tests. **QA/Testing** validates quality and acceptance criteria. Weekly syncs between PM and Product Manager, twice-weekly standups, and monthly stakeholder updates create predictable touchpoints for alignment.

### Risk & Dependency Management

Risk and dependency management are woven into every phase. Teams maintain a Risk Register that tracks ID, description, impact, likelihood, owner, and mitigation plans—reviewed and updated during weekly syncs. A three-tiered escalation path (Team → PM → Product Lead → Sponsor) ensures blockers and risks surface quickly. Weekly status templates standardize communication around progress, next steps, risks, and blockers.

## Documentation

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, principles, roles, and key artifacts
- [Project Initiation Guide](octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning](octoacme-project-planning.md) — Break approved work into actionable backlog items, identify dependencies, and create release plans
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Guidance for day-to-day execution, team rhythm, workflows, and quality assurance
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks, dependencies, and stakeholder updates
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize releases to production, reduce risk, and improve observability
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — Define typical roles and responsibilities used in OctoAcme projects

## How to Use

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our approach, then reference specific phase docs as your project progresses.
- **Starting a project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) to validate your work and get stakeholder alignment.
- **Executing a project?** Use the [Execution & Tracking](octoacme-execution-and-tracking.md) guide for day-to-day workflows and [Risk Management & Communication](octoacme-risks-and-communication.md) to manage risks.
- **Shipping a release?** Consult the [Release & Deployment Guide](octoacme-release-and-deployment.md) to ensure all pre-release checks and deployment steps are completed.
- **Completing a project?** Run a retrospective using the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide to capture learnings.

Keep these docs up to date as processes evolve, and use them as the single source of truth for project management practices across OctoAcme.
