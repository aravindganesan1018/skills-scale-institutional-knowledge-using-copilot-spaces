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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and execute testing strategies, validate acceptance criteria, and ensure quality standards are met before release. They collaborate with developers and product managers to define testability requirements and prevent defects.

### Responsibilities
- Define test strategy and QA approach for each release
- Create test plans aligned with acceptance criteria
- Execute manual and automated testing; coordinate CI/CD test coverage
- Triage and track defects; own defect resolution workflow
- Validate Definition of Done before PR merge and release
- Participate in release readiness reviews and smoke testing

### Goals
- Ensure high quality and reliability of deliverables
- Catch defects early in the development cycle
- Reduce post-release issues and customer impact

### Typical Communication
- Sprint planning and design review participation
- Defect triage and status reports
- PR review comments on testability
- Release readiness sign-offs

### Cross-functional Interactions
- **With Developers**: Review PRs for testability; provide defect feedback; collaborate on test coverage
- **With Product Managers**: Validate acceptance criteria clarity; participate in backlog refinement
- **With Project Managers**: Report quality metrics and release readiness; escalate critical defects
- **With Technical Leads**: Advise on test automation architecture and CI/CD integration

---

## Technical Lead

### Role Summary
Technical Leads make architectural decisions, oversee code quality, and guide technical strategy aligned with business goals. They mentor developers and manage technical debt.

### Responsibilities
- Design technical architecture and API contracts
- Review and approve architectural changes
- Oversee code quality, performance, and security standards
- Identify and prioritize technical debt
- Mentor developers and support capability building
- Participate in risk identification for technical dependencies

### Goals
- Maintain scalable, maintainable technical architecture
- Reduce technical risk and unplanned rework
- Build team technical capabilities

### Typical Communication
- Architecture and design reviews
- Code review comments on critical changes
- Technical risk registers and mitigation plans
- Knowledge-sharing sessions and mentoring

### Cross-functional Interactions
- **With Developers**: Guide design; review architecture and critical PRs; unblock technical decisions; mentor
- **With Product Managers**: Advise on technical feasibility and trade-offs; propose optimization opportunities
- **With Project Managers**: Escalate technical risks and dependency issues
- **With QA/Testing**: Collaborate on test automation strategy and performance testing
- **With Security/Compliance Officer**: Participate in threat modeling and secure architecture design

---

## Business Analyst

### Role Summary
Business Analysts gather and refine requirements from stakeholders, translate business needs into acceptance criteria, and validate solutions align with business objectives.

### Responsibilities
- Conduct stakeholder interviews and requirements discovery
- Document and prioritize business requirements
- Refine acceptance criteria with product and development teams
- Validate solutions meet business objectives
- Create process flows and requirement traceability documents
- Identify gaps or ambiguities in requirements before execution

### Goals
- Ensure clear understanding of business needs across the team
- Reduce rework due to unclear or missed requirements
- Improve solution alignment with business objectives

### Typical Communication
- Requirements documentation and specification
- Stakeholder interviews and feedback sessions
- Acceptance criteria refinement in backlog grooming
- Process flow diagrams and decision trees

### Cross-functional Interactions
- **With Product Managers**: Align on requirements and success metrics; validate business objectives
- **With Developers**: Clarify acceptance criteria; answer requirement questions; document technical constraints
- **With Stakeholders**: Gather inputs and validate understanding; facilitate requirements workshops
- **With Project Managers**: Report requirements clarity and blockers; support acceptance testing
- **With QA/Testing**: Ensure test plans cover all acceptance criteria

---

## Delivery/Scrum Master

### Role Summary
Delivery/Scrum Masters remove impediments, facilitate ceremonies, enforce process discipline, and keep teams aligned to sprint commitments.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and remove impediments blocking the team
- Track sprint metrics (velocity, burndown)
- Enforce team agreements on branching, PR, and Definition of Done
- Shield team from scope creep and mid-sprint disruptions
- Coach team on agile practices and continuous improvement

### Goals
- Maintain consistent sprint cadence and predictability
- Maximize team productivity and flow
- Foster continuous improvement culture

### Typical Communication
- Sprint ceremony facilitation (standups, planning, reviews, retros)
- Impediment escalation and tracking
- Velocity and burndown reporting
- Retrospective action item follow-up

### Cross-functional Interactions
- **With Development Team**: Support ceremony facilitation and process coaching; unblock impediments
- **With Project Managers**: Escalate process risks and team impediments; provide velocity trends
- **With Product Managers**: Protect backlog prioritization discipline; facilitate acceptance and refinement

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure projects incorporate security best practices, meet regulatory requirements, and have risk governance built in from inception.

### Responsibilities
- Review project scope for security and compliance implications
- Define security and compliance acceptance criteria
- Conduct security architecture reviews and threat modeling
- Oversee security scanning in CI and code review
- Validate compliance with regulatory and internal security policies
- Investigate and respond to security incidents

### Goals
- Prevent security vulnerabilities and compliance violations
- Build security awareness across the team
- Reduce risk of breaches, data loss, and regulatory penalties

### Typical Communication
- Security architecture reviews and threat models
- Compliance checklists and acceptance criteria
- Security incident response and post-mortems
- Security training and awareness sessions

### Cross-functional Interactions
- **With Project Managers**: Identify security/compliance risks early; escalate issues; participate in risk register
- **With Developers**: Review design and PRs for security concerns; guide secure coding practices
- **With Technical Leads**: Collaborate on threat modeling and architecture security; define security standards
- **With QA/Testing**: Coordinate security testing and penetration testing activities
- **With Stakeholders**: Report compliance posture and risk status

---

## Release Manager

### Role Summary
Release Managers coordinate deployment activities, ensure release readiness, manage rollout timelines, and facilitate post-release validation.

### Responsibilities
- Develop and maintain release schedule and deployment plan
- Coordinate release readiness checks across teams
- Oversee deployment to staging and production environments
- Execute release runbooks; manage rollback if needed
- Coordinate release communications and stakeholder updates
- Validate production readiness and post-deploy metrics

### Goals
- Execute reliable, predictable releases with minimal disruption
- Reduce deployment risk and post-release incidents
- Maintain stakeholder confidence in release quality

### Typical Communication
- Release planning and readiness meetings
- Deployment runbooks and procedures
- Release notes and stakeholder announcements
- Post-deployment status and metrics

### Cross-functional Interactions
- **With Project Managers**: Align on release timing and go/no-go decisions; coordinate stakeholder communications
- **With QA/Testing**: Coordinate smoke testing and release validation; confirm quality gates
- **With Developers**: Coordinate code freeze and release branch management
- **With Technical Leads**: Validate architecture and performance readiness; coordinate rollback procedures
- **With Operations/DevOps**: Coordinate deployment infrastructure, runbooks, and monitoring
- **With Stakeholders**: Communicate release status, timelines, and post-release metrics

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference specific cross-functional interactions to illustrate collaboration patterns and dependencies.
- Map personas to project lifecycle phases (initiation, planning, execution, release, retrospective) to clarify involvement and responsibilities.
