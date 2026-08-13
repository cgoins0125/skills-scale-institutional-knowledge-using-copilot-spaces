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

## QA / Test Lead

### Role Summary
The QA / Test Lead defines the overall test strategy, coordinates validation efforts, and ensures that quality standards are met before releases. They act as the primary advocate for quality across the team.

### Responsibilities
- Define and maintain the test strategy, test plans, and acceptance criteria
- Coordinate functional, regression, and integration testing activities
- Triage defects and work with developers on resolution priorities
- Track test coverage and report quality metrics
- Participate in sprint planning to ensure testability of features

### Goals
- Prevent defects from reaching production
- Ensure acceptance criteria are clearly defined and validated
- Maintain a reliable, automated test suite

### Typical Communication
- Defect reports and test summary updates shared with Developers and Project Managers
- Collaboration with Product Managers on acceptance criteria and edge cases
- Test readiness sign-offs before deployments

### Interactions with Existing Roles
- **Developers**: Partners on writing testable code, reviewing test coverage, and resolving defects
- **Product Managers**: Clarifies acceptance criteria and validates feature completeness against requirements
- **Project Managers**: Reports test status and quality risks; flags blockers that may affect delivery timelines

---

## Release Manager

### Role Summary
The Release Manager coordinates deployment readiness and manages the end-to-end release process. They ensure releases are stable, well-documented, and communicated across teams and stakeholders.

### Responsibilities
- Coordinate release schedules, deployment windows, and go/no-go decisions
- Maintain release notes, changelogs, and deployment runbooks
- Plan and rehearse rollback procedures
- Ensure all pre-release checklists and approvals are completed
- Communicate release status and timelines to stakeholders

### Goals
- Deliver smooth, low-risk releases with minimal downtime
- Maintain a clear, auditable record of release activities
- Reduce time to recover from failed deployments

### Typical Communication
- Release readiness updates and go/no-go meeting facilitation
- Coordination emails or announcements to stakeholders and support teams
- Post-release retrospective notes

### Interactions with Existing Roles
- **Developers**: Confirms code freeze readiness, deployment steps, and rollback plans
- **Product Managers**: Aligns on release scope and communicates feature availability timelines
- **Project Managers**: Coordinates release milestones within the project plan and escalates deployment blockers

---

## Technical Lead / Architect

### Role Summary
The Technical Lead / Architect guides the technical direction of the project. They review solution designs, identify architectural risks, and ensure the system remains maintainable and scalable.

### Responsibilities
- Define and communicate the technical architecture and design standards
- Review and approve significant design and implementation decisions
- Identify technical risks, dependencies, and constraints
- Support developers with complex problem-solving and design guidance
- Participate in scope and trade-off discussions with Product and Project Managers

### Goals
- Maintain a coherent, scalable, and secure system architecture
- Reduce technical debt and long-term maintenance burden
- Ensure technical decisions align with business goals

### Typical Communication
- Architecture decision records (ADRs) and design review sessions
- Technical risk updates in project status meetings
- Code and design review feedback

### Interactions with Existing Roles
- **Developers**: Provides guidance, reviews designs and pull requests, and unblocks technical challenges
- **Product Managers**: Translates technical constraints into scope trade-off discussions and feasibility assessments
- **Project Managers**: Surfaces technical risks and dependencies that impact timelines or resource planning

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide strategic direction, funding, and organizational support for the project. They have a vested interest in project outcomes and hold final decision-making authority on priorities and trade-offs.

### Responsibilities
- Provide vision, priorities, and constraints at project initiation
- Review and approve major deliverables, milestones, and scope changes
- Remove organizational blockers and secure necessary resources
- Hold accountability for project outcomes within the business

### Goals
- Ensure the project delivers measurable business value
- Maintain alignment between project objectives and organizational strategy
- Enable the team to deliver by removing impediments above their authority

### Typical Communication
- Executive status briefings and milestone reviews
- Decision approvals on escalated scope or priority changes
- Sponsorship communications to the broader organization

### Interactions with Existing Roles
- **Product Managers**: Aligns on product vision, roadmap priorities, and success metrics
- **Project Managers**: Receives escalations, approves key decisions, and provides strategic guidance
- **Developers**: Indirect interaction; occasionally participates in demos or reviews of major deliverables

---

## Support / Operations Representative

### Role Summary
The Support / Operations Representative ensures the product is ready for production and that the team is prepared to sustain it. They surface operational concerns early and lead post-release monitoring and incident follow-up.

### Responsibilities
- Review production readiness criteria before releases
- Monitor post-release system health and surface emerging issues
- Coordinate incident response and post-mortem activities
- Provide input on operational requirements such as logging, alerting, and runbooks
- Represent customer-facing impact in planning and retrospective discussions

### Goals
- Minimize production incidents and customer disruption
- Ensure the team has the operational knowledge to support what is released
- Drive continuous improvement based on production learnings

### Typical Communication
- Production readiness checklists shared with Developers and Release Managers
- Incident reports and post-mortem summaries
- Operational feedback in sprint retrospectives

### Interactions with Existing Roles
- **Developers**: Collaborates on observability, runbook creation, and incident resolution
- **Product Managers**: Surfaces user-impacting issues and operational constraints that influence prioritization
- **Project Managers**: Reports operational risks and coordinates incident-related work within the project plan

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

