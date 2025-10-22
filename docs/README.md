# OctoAcme Project Management Docs

Welcome — this folder contains OctoAcme's project management processes, templates, and playbooks. These documents describe how we initiate, plan, execute, release, and continuously improve cross-functional projects. The goal is a single source of truth so teams can move quickly with clear ownership, predictable delivery, and measurable outcomes.

OctoAcme follows a customer-first, iterative, and data-informed approach. Projects move through a lightweight lifecycle: Initiation (one-pager and stakeholder alignment), Planning (kickoff, prioritized backlog, estimates, Definition of Done), Execution (timeboxed sprints, PR and CI conventions, daily/weekly cadences), Release (staged verification, rollback plans, release notes), and Close (retrospectives and continuous improvement). Key artifacts include the Project One-pager, Roadmap and Release Plan, Backlog with acceptance criteria, Risk Register, and Retrospective action items.

Workflows emphasize small, testable increments and predictable handoffs. Planning uses backlog templates and sprint timeboxing, with acceptance criteria and a Definition of Done required before work is pulled into a sprint. The Pull Request workflow calls for small PRs, linked issues, CI-run tests and linting, and at least one approver before merging. Releases include staging smoke tests, rollback/mitigation plans, and a deployment checklist; release types (patch/minor/major) guide pre-release requirements and verification steps.

Roles and responsibilities are explicit: Product Managers own outcomes and prioritization, Project Managers coordinate schedule/risk/communication, Developers implement code and tests, and QA validates acceptance criteria and quality. Communication cadence includes daily standups, weekly delivery syncs, PM+PdM alignment, monthly stakeholder updates, and incident templates. Quality practices include unit/integration tests, end-to-end smoke tests for critical flows, CI security scanning, and manual QA when needed. Retrospective action items become tracked backlog work and are reviewed in regular syncs.

Docs index
- Project Management Overview: docs/octoacme-project-management-overview.md
- Project Initiation Guide: docs/octoacme-project-initiation.md
- Project Planning: docs/octoacme-project-planning.md
- Execution & Tracking: docs/octoacme-execution-and-tracking.md
- Risk Management & Communication: docs/octoacme-risks-and-communication.md
- Release & Deployment Guide: docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement: docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas: docs/octoacme-roles-and-personas.md

How to use
- Keep the Project One-pager and Risk Register up to date in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
- Use the weekly status and incident templates for consistent communications.
- Link the project README into your project board and release docs so stakeholders have one entry point.

Acceptance criteria
- Content aligns with the existing process docs in this folder.
- Provides a clear entry point and links to all core process documents.
- Improves discoverability and onboarding.
