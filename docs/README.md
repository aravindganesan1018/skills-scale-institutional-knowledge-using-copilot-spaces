# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme Project Management documentation hub. This folder contains comprehensive guides for managing projects from initiation through retrospective and continuous improvement.

## Our Approach

OctoAcme follows an iterative, stakeholder-focused project management methodology built on five core principles:
- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments to reduce risk and accelerate feedback
- **Clear ownership**: Each project has named leads with explicit responsibilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

Our project lifecycle spans five phases: **Initiation → Planning → Execution → Release → Retrospective**. Each phase has dedicated guidance, templates, and checklists to ensure consistency and quality.

## OctoAcme Project Management Framework Overview

OctoAcme operates through a **lifecycle-driven, role-based approach** that emphasizes customer value, iterative delivery, and clear ownership. The framework moves projects through five structured phases with clear decision gates to ensure business alignment before significant effort is invested.

**Initiation & Planning** focuses on validation: teams develop a lightweight Project One-pager defining the problem statement, goals, success metrics, and stakeholder alignment, moving to planning only when success criteria are clear and sponsor approval is confirmed. During planning, work is broken into prioritized backlog items with acceptance criteria, dependencies are mapped, and a release timeline is established.

**Execution, Release, and Retrospective** phases embed quality and learning. Delivery teams follow a structured workflow with small PRs (≤400 lines), automated CI/testing, and defined approval gates. Before any release, comprehensive pre-flight checks are required: passing security scans, documented rollback plans, and smoke tests. After each sprint, release, or incident, retrospectives capture learnings and convert them into 2–3 prioritized action items, creating a continuous improvement culture.

**Clear roles and communication cadences** keep teams aligned: Product Managers define what to build and own success metrics; Project Managers coordinate schedules, risks, and communications; Developers implement with quality focus; and QA/Testing validates acceptance criteria. Weekly PM/PdM syncs, twice-weekly standups, monthly stakeholder updates, and structured risk escalation (team → PM → Product Lead → Sponsor) ensure transparent decision-making and rapid issue surfacing.

## Documentation Index

| Document | Purpose | Best For |
|----------|---------|----------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme PM approach, roles, and key artifacts | New team members, stakeholders seeking big picture |
| [Project Initiation](octoacme-project-initiation.md) | Validating and authorizing work; stakeholder alignment | Starting new projects or features |
| [Project Planning](octoacme-project-planning.md) | Breaking work into actionable backlog with acceptance criteria | Planning phase; sprint and release planning |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day delivery, quality standards, and blocker escalation | Delivery teams; daily standups and syncs |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Managing risks, dependencies, and stakeholder communication | All roles; especially PM and Product Lead |
| [Release & Deployment](octoacme-release-and-deployment.md) | Standardizing releases to production; rollback procedures | Release leads; deployment planning |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and converting to improvements | Project close-out; sprint retros |
| [Roles and Personas](octoacme-roles-and-personas.md) | Defining responsibilities for Developers, Product Managers, and Project Managers | Understanding team structure |

## Quick Start

**New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md).

**Starting a new project?** Follow this sequence:
1. [Project Initiation](octoacme-project-initiation.md) — Get your project approved
2. [Project Planning](octoacme-project-planning.md) — Build your plan
3. [Execution & Tracking](octoacme-execution-and-tracking.md) — Deliver your work
4. [Release & Deployment](octoacme-release-and-deployment.md) — Ship to production
5. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Learn and improve

**Need help with a specific challenge?** Refer to [Risk Management & Communication](octoacme-risks-and-communication.md) for escalation and communication guidance.

## Target Audience

These documents are designed for:
- **New team members** seeking to understand OctoAcme's PM approach and get up to speed quickly
- **Project Managers** executing projects and needing templates, checklists, and guidance
- **Product Managers** defining scope, success metrics, and prioritization
- **Delivery teams** (Developers, QA, Engineers) understanding workflows, quality standards, and communication expectations
- **Stakeholders and Sponsors** seeking visibility into project status and governance
- **Leadership** establishing consistent, repeatable project execution across the organization

## Using These Docs with Copilot Spaces

These process documents are optimized for use within Copilot Spaces, allowing teams to:
- **Ground Copilot's knowledge** in OctoAcme-specific practices and terminology
- **Provide context-specific guidance** tailored to your organization's approach
- **Accelerate onboarding** by making institutional knowledge searchable and versioned
- **Enable consistent execution** by having Copilot reference authoritative, up-to-date processes

Add these docs to your Copilot Space context to benefit from role-specific guidance and scenario-aware recommendations aligned with OctoAcme's proven approach.
