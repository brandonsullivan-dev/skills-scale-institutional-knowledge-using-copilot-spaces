# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Major Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Typical Interactions
- Partner with Product Managers and Business Analysts to clarify acceptance criteria
- Collaborate with UX/UI Designers on implementation details and design feasibility
- Work with DevOps Engineers and Release Managers for deployment readiness
- Coordinate with QA Leads on test strategy and defect triage

### Communication Touchpoints
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Major Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Typical Interactions
- Align scope and delivery sequencing with Project Managers
- Partner with Business Analysts to refine requirements
- Collaborate with UX/UI Designers on user outcomes and usability
- Review delivery quality and readiness with QA Leads and Release Managers

### Communication Touchpoints
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Major Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Typical Interactions
- Align priorities and milestones with Product Managers
- Coordinate execution and blockers with Developers and QA Leads
- Partner with Release Managers for release readiness and handoffs
- Escalate risks with stakeholders using the risk communication process

### Communication Touchpoints
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Business Analysts

### Summary
Business Analysts translate business goals into clear requirements and acceptance criteria. They help ensure delivered solutions match intended outcomes.

### Major Responsibilities
- Elicit and document business and process requirements
- Refine acceptance criteria with Product Managers and delivery teams
- Maintain requirement traceability from scope to release outcomes
- Support impact analysis for scope changes and dependency decisions

### Typical Interactions
- Partner with Product Managers on problem framing and scope definition
- Work with Developers and QA Leads to clarify expected behavior
- Coordinate with Support/Customer Success to incorporate recurring customer issues
- Support Project Managers with change impact and dependency context

### Communication Touchpoints
- Backlog refinement sessions
- Requirement and acceptance criteria reviews
- Scope change and impact discussions

---

## UX/UI Designers

### Summary
UX/UI Designers define user flows and interfaces that support customer outcomes, usability, and accessibility expectations.

### Major Responsibilities
- Create user flows, wireframes, and interaction designs
- Validate design decisions through feedback and lightweight usability testing
- Maintain design specifications for delivery and QA alignment
- Partner on accessibility and consistency standards

### Typical Interactions
- Collaborate with Product Managers and Business Analysts on user needs
- Partner with Developers on implementation feasibility and detail handoffs
- Work with QA Leads to define design-related acceptance checks
- Share known UX risks or trade-offs with Project Managers

### Communication Touchpoints
- Design reviews and walkthroughs
- Prototyping feedback sessions
- Delivery handoff notes and annotated mockups

---

## Release Managers

### Summary
Release Managers coordinate release readiness, deployment execution, and post-release communication across teams.

### Major Responsibilities
- Own release calendar, release scope confirmation, and go/no-go facilitation
- Ensure pre-release and deployment checklists are completed
- Coordinate rollback readiness and incident communication handoffs
- Publish release notes with links to known issues and support guidance

### Typical Interactions
- Coordinate with DevOps Engineers on pipeline and environment readiness
- Align with QA Leads and Developers on test status and release risks
- Partner with Project Managers for milestone and dependency handoffs
- Coordinate with Support/Customer Success on customer-facing messaging

### Communication Touchpoints
- Release readiness checkpoints
- Go/no-go decisions and deployment announcements
- Post-release status updates and incident follow-ups

---

## DevOps Engineers

### Summary
DevOps Engineers own deployment automation, environment reliability, and operational readiness across staging and production.

### Major Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Manage infrastructure, observability, and reliability guardrails
- Support rollback execution and incident mitigation
- Document operational prerequisites and runbooks

### Typical Interactions
- Work with Developers on build, deployment, and observability requirements
- Partner with Release Managers for release windows and deployment sequencing
- Coordinate with QA Leads on environment parity and test reliability
- Escalate operational risks through Project Managers and on-call channels

### Communication Touchpoints
- Deployment runbooks and pipeline status updates
- Incident response channels and post-incident reviews
- Environment change notices

---

## QA Leads

### Summary
QA Leads define and coordinate quality strategy to ensure releases meet acceptance criteria and risk thresholds.

### Major Responsibilities
- Define test strategy and quality gates for planned scope
- Coordinate functional, integration, and smoke test coverage
- Lead defect triage and recommend release quality status
- Maintain traceability between acceptance criteria and test evidence

### Typical Interactions
- Work with Product Managers and Business Analysts on testable requirements
- Partner with Developers on testability and defect resolution
- Align with Release Managers on go/no-go quality criteria
- Coordinate with Support/Customer Success on known issues and mitigation messaging

### Communication Touchpoints
- Test plan reviews and quality status reports
- Defect triage sessions
- Release readiness sign-off discussions

---

## Support / Customer Success

### Summary
Support/Customer Success represents customer impact by surfacing issues, coordinating escalation, and validating readiness of customer-facing guidance.

### Major Responsibilities
- Share customer trends, pain points, and high-impact issues with delivery teams
- Validate support readiness for upcoming releases and known issues
- Coordinate escalation routing for production incidents affecting customers
- Maintain support playbook inputs tied to release notes and incident outcomes

### Typical Interactions
- Partner with Product Managers and Business Analysts on customer feedback patterns
- Coordinate with Release Managers before and after releases
- Work with QA Leads and Developers to clarify customer-reported defects
- Escalate critical issues via Project Managers and incident channels

### Communication Touchpoints
- Customer issue summaries and escalation updates
- Release readiness and support enablement updates
- Post-release and post-incident feedback loops

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use alongside the [Project Planning](./octoacme-project-planning.md), [Release & Deployment Guide](./octoacme-release-and-deployment.md), and [Risk Management & Communication](./octoacme-risks-and-communication.md) docs when clarifying handoffs, escalation, and accountability.
