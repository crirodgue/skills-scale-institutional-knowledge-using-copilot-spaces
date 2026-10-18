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

## Product Managers (PdM)

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

## Project Managers (PM)

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

## QA / Testing

### Role Summary
QA and Test engineers validate that features meet acceptance criteria and maintain product quality through test plans and verification.

### Responsibilities
- Define and execute test plans (unit/integration/e2e)
- Maintain test infrastructure and automation
- Validate fixes and regression coverage
- Report and track defects

### Typical Communication
- Test reports, CI results, and QA sign-off in PRs
- Work with Developers to reproduce and resolve issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional / Suggested Personas (new)

The following personas are proposed additions to improve clarity around operational responsibilities, decision handoffs, and cross-functional coordination. Each entry includes responsibilities and how the persona typically interacts with existing roles.

### Engineering Manager

Role Summary
- Oversees engineering staffing, team structure, and engineering practices. Focuses on people management, career growth, and technical quality within teams.

Responsibilities
- Technical staffing and capacity planning
- Coaching and performance support for engineers
- Ensuring code quality and mentoring on best practices
- Owning team-level technical debt and engineering improvements

How they interact with existing roles
- Coordinates with PM/TPM on resourcing and delivery trade-offs
- Works with Developers on implementation and reviews technical escalations
- Escalates cross-team technical risks to the Product Lead or PM when needed

---

### Technical Program Manager (TPM)

Role Summary
- Manages cross-team programs, tracks milestone-level dependencies and risks, and translates roadmap commitments into tracked delivery plans.

Responsibilities
- Identify and manage cross-team dependencies and integration points
- Maintain program timelines, milestone tracking, and status reporting
- Facilitate cross-functional planning and cadence for multi-team work
- Track and escalate risks that threaten milestones

How they interact with existing roles
- Works with PM to translate product roadmaps into implementation milestones
- Coordinates with Engineering Managers, SRE, and Release Manager to ensure alignment
- Communicates status and blockers to stakeholders and PMs

---

### Design Lead

Role Summary
- Owns UX strategy, design quality, and accessibility for product features.

Responsibilities
- Produce and maintain design artifacts and UX acceptance criteria
- Review designs for accessibility, usability, and consistency with product vision
- Provide timely design feedback during planning and reviews

How they interact with existing roles
- Collaborates with PdM to define customer-facing acceptance criteria
- Works with Developers to ensure feasibility and hands-off implementation details
- Signs off on UX acceptance criteria before QA/Release

---

### Data Analyst / Product Analyst

Role Summary
- Defines, instruments, and analyzes success metrics; supports data-driven decisions before and after releases.

Responsibilities
- Define key success metrics and instrumentation requirements
- Build dashboards and run post-release analyses
- Support A/B testing and performance measurement
- Provide data to inform prioritization and retrospectives

How they interact with existing roles
- Works with PdM to define metric definitions and success criteria
- Partners with Developers on instrumentation implementation
- Shares analysis with PM/PdM and stakeholders to inform decisions and retrospectives

---

### Release Manager

Role Summary
- Coordinates releases across teams, ensures release readiness, and manages deployment windows and rollback plans.

Responsibilities
- Maintain release calendar and coordinate release windows
- Ensure runbooks, rollback plans, and post-deploy verifications are in place
- Coordinate with SRE, Security, and Developers for deployment readiness
- Lead release-related communications to stakeholders and support teams

How they interact with existing roles
- Works with PM and TPM to determine release contents and timing
- Coordinates with SRE and Developers during deployment and incident response
- Notifies Business Stakeholder Representatives and Support of release plans

---

### SRE / On-call / Operations

Role Summary
- Owns production reliability, monitoring, and operational playbooks. Responds to incidents and drives post-incident action items.

Responsibilities
- Maintain production monitoring, alerts, and runbooks
- Lead incident response and post-incident analysis
- Provide guidance on reliability and scalability during planning
- Own operational readiness and performance SLIs/SLOs

How they interact with existing roles
- Works with Developers on instrumentation and troubleshooting
- Coordinates with Release Manager and PM on deployment and rollback decisions
- Escalates critical production issues to PM and Product Lead as needed

---

### Security & Compliance Representative

Role Summary
- Ensures changes meet required security and compliance controls and reduces risk exposure.

Responsibilities
- Review features for security, privacy, and compliance requirements
- Approve security checklists and perform threat modeling when required
- Escalate compliance concerns and required mitigations

How they interact with existing roles
- Engages early with PdM and Developers during planning for control and compliance needs
- Works with Release Manager and SRE to verify security readiness before release
- Provides guidance to Engineering Managers on fixing security-related issues

---

### Business Stakeholder Representative

Role Summary
- Represents business units or product sponsors and provides decisions on priorities, trade-offs, and acceptance of outcomes.

Responsibilities
- Advocate for customer/business priorities and outcomes
- Provide timely decisions for scope and rollout acceptances
- Support communication and adoption strategies for releases

How they interact with existing roles
- Works with PdM and PM to align stakeholders on priorities and timelines
- Available to approve trade-offs and accept business impact decisions
- Engages in milestone reviews and major release communications

---

## How adding these personas improves outcomes

- Clearer handoffs and decision ownership reduce ambiguity and rework
- Faster resolution of cross-team dependencies and clearer escalation paths
- More complete acceptance criteria (design, security, metrics) reduce post-release issues
- Improved release coordination and operational readiness reduce incidents and rollback frequency
- Stronger alignment between business priorities and delivery decisions

---
