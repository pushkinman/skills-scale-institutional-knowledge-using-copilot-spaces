# OctoAcme Project Management Docs

## Purpose

This repository is the central home for OctoAcme's project management knowledge base. It is designed to work as a **GitHub Copilot Space**, making all process documentation searchable, versioned, and available as AI context. The goals of this space are to:

- Provide a single source of truth for PM processes and artifacts.
- Improve onboarding for new team members by surfacing the right guidance quickly.
- Keep processes versioned and collaborative through pull requests and issues.
- Enable Copilot to give role-specific, context-aware answers grounded in real OctoAcme practices.

---

## What's in `docs/`

| Document | Description |
|---|---|
| [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) | High-level principles, core roles, key artifacts, and lifecycle summary |
| [octoacme-project-initiation.md](./octoacme-project-initiation.md) | How to validate and authorize new projects; one-pager template and initiation checklist |
| [octoacme-project-planning.md](./octoacme-project-planning.md) | Turning an approved initiative into a backlog, release plan, and milestone map |
| [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) | Day-to-day team rhythm, PR workflow, quality practices, and blocker escalation |
| [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) | Risk register format, risk lifecycle, stakeholder communication, and escalation paths |
| [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, and rollback playbook |
| [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action-item tracking, and continuous improvement culture |
| [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) | Responsibilities, goals, and communication patterns for Developers, Product Managers, and Project Managers |

---

## OctoAcme PM Process Overview

OctoAcme uses a customer-first, iterative, and data-informed approach for all cross-functional projects. Every project follows a clear lifecycle: **Initiation** (problem statement, stakeholder alignment, go/no-go decision), **Planning** (prioritized backlog, release plan, Definition of Done), **Execution** (incremental delivery with CI/CD guardrails), **Release** (staged deployment with smoke tests and rollback plans), and **Close & Retrospective** (capturing learnings and driving continuous improvement).

Three core roles drive delivery: the **Project Manager (PM)** coordinates schedules, risks, and cross-team communications; the **Product Manager (PdM)** owns the product vision, backlog prioritization, and success metrics; and **Developers** implement features collaboratively, maintain test coverage, and participate in design and code reviews. QA and stakeholders round out the team, validating acceptance criteria and providing strategic inputs.

Communication runs on a structured cadence—twice-weekly team standups, a weekly PM + PdM sync, and monthly stakeholder updates—with ad-hoc escalation paths (team → PM → Product Lead → Sponsor) for blockers and incidents. Risks are tracked in a living Risk Register, reviewed each week, and escalated early to prevent surprises.

Quality and release practices are built into every stage: CI enforces automated tests, linting, and security scanning before any merge; staged deployments (staging → production) are paired with smoke tests and a documented rollback plan; and post-release retrospectives close the loop by converting learnings into backlog action items with clear owners and due dates.

---

## How to Contribute or Update Docs

1. **Open an issue** describing the process gap or update you want to make.
2. **Create a branch** and edit (or add) the relevant file in `docs/`.
3. **Open a pull request** that links to the issue and summarizes the change.
4. **Request review** from a PM or team lead before merging.

Keep documents concise and use the existing heading/template conventions so Copilot can surface them accurately as context.
