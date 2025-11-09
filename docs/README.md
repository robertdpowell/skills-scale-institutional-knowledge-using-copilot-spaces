# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation repository. This collection of documents provides comprehensive guidance on how OctoAcme plans, executes, and delivers projects using a structured, lightweight approach designed for predictability and continuous improvement.

## Overview

OctoAcme runs projects through a lightweight, stage-based lifecycle that moves from Initiation to Planning, Execution, Release, and Close/Retrospective. Initiation captures the problem, stakeholders, success metrics, and a one‑pager to decide go/no-go. Planning breaks approved initiatives into prioritized, estimable backlog items with a Definition of Done, identified dependencies, and a release/milestone map. Execution is managed on a project board (Backlog → Ready → In Progress → In Review → QA → Done) with small, focused pull requests, CI gating, and an escalation path for blockers. Releases follow a standard checklist (pre‑release checks, smoke tests, rollback plans, and release notes) and post‑release verification before stakeholder announcement.

Roles and ownership are explicit: Project Managers coordinate schedules, risks, and communications; Product Managers define outcomes, prioritize work, and measure success; Developers implement and test features; QA validates acceptance criteria; and Stakeholders provide input and approvals. These personas are used to assign accountability for artifacts like the Project One‑pager, Risk Register, acceptance criteria, and retrospective action items. Clear role responsibilities reduce ambiguity during handoffs and ensure each deliverable has an owner, improving predictability and traceability across the project.

Communication is structured and routine: daily standups for team-level triage, weekly delivery syncs to show progress and surface risks, demos at the end of sprints or milestones, and monthly stakeholder updates. The docs provide templates for weekly status and incident communications and recommend a single source of truth (project README or release doc) for status. Blockers escalate in levels—from team triage in standup, to PM escalation to Product Lead and dependent teams, up to sponsor-level escalation for business‑impacting issues—ensuring rapid visibility and appropriate involvement.

Quality assurance combines automated and manual practices: unit and integration tests, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA for acceptance where needed. PR process expectations include linking issues and acceptance criteria, keeping PRs small, and requiring approvals and passing CI before merge. Projects track velocity, burndown, and outcome metrics defined in the Project One‑pager using dashboards for key signals (errors, latency, usage). Continuous improvement is enforced via regular retrospectives that produce prioritized action items tracked in the backlog, closing the loop between execution learnings and process updates.

## Process Docs

The following documents provide detailed guidance on each phase of the OctoAcme project lifecycle:

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme Project Initiation](octoacme-project-initiation.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
- [OctoAcme Execution and Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme Risks and Communication](octoacme-risks-and-communication.md)
- [OctoAcme Release and Deployment](octoacme-release-and-deployment.md)
- [OctoAcme Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)

## How to Use These Docs

Project teams should maintain their Project One-pager and release notes directly in their project repository to keep them versioned and accessible alongside code. For enhanced integration with GitHub Copilot Spaces, consider adding process-specific documentation to the `.copilot/` directory in your repository. This enables Copilot Spaces to use these documents as contextual reference when assisting with project planning, execution, and code development tasks.
