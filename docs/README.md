# OctoAcme Project Management Documentation

> Preface: This README is the entry point for OctoAcme's project management process docs. Use it to quickly orient new team members and jump to phase- or topic-specific guidance below.

## TL;DR
- Phases: Initiation → Planning → Execution → Release → Retrospective
- Roles: Project Manager, Product Manager, Developers, QA, Stakeholders
- Communication: Daily standups, weekly delivery syncs, milestone stakeholder updates
- Quality: Small PRs, CI checks (tests, linters, security), and a release checklist

## Overview

OctoAcme runs projects with a lightweight, stage-based workflow that moves work from initiation through planning, execution, release, and retrospective. Initiation captures the problem, stakeholders, success metrics, and a one‑pager to decide go/no‑go. Planning breaks approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release / milestone map. Execution is managed on a project board and emphasizes small, reviewable pull requests, CI checks, and regular demos; retrospectives capture learnings and convert them into action items.

Roles and responsibilities are clearly defined so ownership and handoffs are explicit. Core personas include a Project Manager (coordinates schedule, risks, and stakeholder communication), Product Manager (defines outcomes, prioritizes the backlog, and measures success), Developers (implement, test, document, and estimate work), QA/Testing (validate quality and acceptance), and Stakeholders (provide input and approvals). The docs encourage describing role interactions and accountability in project artifacts (one‑pager, risk register, acceptance criteria) so teams can trace decisions and responsibilities.

Communication is structured around short, frequent touchpoints and written single sources of truth. Teams run daily standups for progress and blockers, a weekly delivery sync for progress and risks, and cadence-based stakeholder updates (monthly or milestone-based). Templates (weekly status, release notes) and the project README act as canonical status sources; escalation paths (team → PM → Product Lead → Sponsor) are documented so blockers follow a known path. Demo/review sessions and documented decision logs support transparency and alignment.

Quality assurance and risk management are integrated into the flow rather than treated as afterthoughts. PRs should include issue links and acceptance criteria, run automated tests and linters in CI, and require at least one approval before merging. The QA approach calls for unit, integration, and end‑to‑end smoke tests where appropriate, plus manual QA for acceptance when needed; CI includes security scanning. Releases follow a checklist (pre‑release checks, staging smoke tests, rollback plans, post‑deploy verification), and a simple risk register is maintained and reviewed regularly.

---

## Process Documents

### Foundation & Overview
- [Project Management Overview](octoacme-project-management-overview.md) — Concise introduction to OctoAcme's principles, lifecycle, core roles, and key artifacts.

### Project Lifecycle Phases
- [Project Initiation](octoacme-project-initiation.md) — Templates and checklist to validate the business need, align stakeholders, and produce a one‑pager with success metrics.
- [Project Planning](octoacme-project-planning.md) — Guidance for breaking work into shippable increments, estimating, defining DoD, and managing dependencies and risks.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day‑to‑day workflows, project board conventions, PR guidelines, team rhythm, and blocker escalation.
- [Release & Deployment](octoacme-release-and-deployment.md) — Release types, pre‑release requirements, deployment checklist, and rollback/incident playbook.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure, action item tracking, and a culture of iterative improvements.

### Cross‑Cutting Concerns
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register format, lifecycle, stakeholder communication templates, and escalation paths.
- [Roles and Personas](octoacme-roles-and-personas.md) — Definitions of common roles (Developers, Product Managers, Project Managers) and guidance for using personas in exercises.

---

## How to use this documentation

- Start here to orient new team members and link into the specific phase doc you need.
- Keep the project README updated with status and links to project‑specific artifacts (one‑pager, risk register, release notes).
- Use the templates and checklists in each doc to standardize planning, execution, QA, and releases.
