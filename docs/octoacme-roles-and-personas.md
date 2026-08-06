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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (proposed additions)

Below are proposed cross-functional and operational personas to add to the Project Management processes. Each includes a brief role summary, responsibilities, and key interactions with existing roles.

### Delivery Lead

#### Role Summary
Coordinates day-to-day delivery activities, ensures sprint commitments are met, and drives removal of operational blockers.

#### Responsibilities
- Manage sprint commitments and track delivery progress
- Track and surface dependencies and risks to the PM
- Facilitate flow across teams and remove blockers
- Coordinate handoffs between teams and external stakeholders

#### Key Interactions
- Works closely with the Project Manager for scheduling and risk reporting
- Aligns with Product Manager on priorities and scope
- Supports Developers and QA in resolving delivery issues
- Provides status to Stakeholders and escalates when needed

---

### Engineering Manager

#### Role Summary
Owns team health, staffing, and technical direction; responsible for technical risk management and capacity planning.

#### Responsibilities
- Team staffing, performance, and career development
- Drive technical direction and architecture decisions
- Oversee capacity planning and allocation
- Mitigate technical debt and operational risks

#### Key Interactions
- Reviews estimates and capacity with PM/Delivery Lead
- Supports Developers with architecture and design decisions
- Escalates cross-team technical risks to Project Manager

---

### UX Researcher / Designer

#### Role Summary
Leads user research, interaction design, and validation to ensure product usability and alignment with user needs.

#### Responsibilities
- Conduct user research and usability testing
- Create prototypes and design specifications
- Validate designs against acceptance criteria
- Handoff designs with clear UX requirements to Developers

#### Key Interactions
- Partners with Product Manager on user needs and priorities
- Collaborates with Developers during implementation
- Works with QA to validate UX-related acceptance criteria

---

### DevOps / Platform Engineer

#### Role Summary
Ensures reliable CI/CD, infrastructure-as-code, deployment reliability, and operational observability.

#### Responsibilities
- Maintain CI/CD pipelines and automation
- Manage infrastructure-as-code and production environment changes
- Maintain observability, alerts, and runbooks
- Support incident response and post-incident analysis

#### Key Interactions
- Coordinates with Developers for deployment and infra changes
- Works with Release Manager on release readiness and rollback plans
- Supports Support Owner during incidents

---

### Release Manager

#### Role Summary
Coordinates release activities across teams, owns release readiness, and communicates release plans to stakeholders.

#### Responsibilities
- Maintain release checklist and runbook
- Coordinate cross-team release windows and schedules
- Validate pre-release criteria (tests, security, docs)
- Coordinate stakeholder communication and post-release verification

#### Key Interactions
- Works with DevOps and Delivery Lead to validate readiness
- Communicates with PM, PdM, and Support on release timing and impact
- Ensures Technical Writer prepares release notes and documentation

---

### Support Owner (L2)

#### Role Summary
Owns triage and remediation of production issues, ensures lessons learned are fed back to the team.

#### Responsibilities
- Triage production incidents and categorize severity
- Maintain escalation logs and incident timelines
- Drive remediation with Developers and DevOps
- Contribute to post-incident reviews and action items

#### Key Interactions
- Notifies PM and Delivery Lead of production-impacting issues
- Works with Developers and DevOps to resolve incidents
- Provides input to Product Manager on priority of bug fixes

---

### Data Analyst

#### Role Summary
Defines metrics, builds dashboards, and validates success criteria to inform product decisions.

#### Responsibilities
- Define and maintain success metrics and dashboards
- Validate analytics around releases and experiments
- Support A/B testing and metric instrumentation
- Provide data-driven insights to PM and stakeholders

#### Key Interactions
- Works closely with Product Manager on metrics and experiments
- Shares dashboards and findings with PM, PdM, and stakeholders
- Supports QA/Engineers in validating telemetry and instrumentation

---

### Security Reviewer

#### Role Summary
Performs security reviews, threat modeling, and vulnerability triage to reduce security risk.

#### Responsibilities
- Conduct security reviews of designs and PRs
- Perform threat modeling for critical features
- Triage and track vulnerabilities
- Ensure security checks are integrated into CI

#### Key Interactions
- Reviews designs with UX and Developers for secure patterns
- Coordinates with Compliance Lead for audit-related controls
- Works with DevOps to address vulnerabilities in production

---

### Compliance Lead

#### Role Summary
Ensures regulatory and policy compliance, manages audit readiness, and maintains control documentation.

#### Responsibilities
- Interpret regulatory requirements and map to project controls
- Ensure documentation and evidence for audits
- Drive compliance-related requirements into the backlog
- Monitor ongoing compliance posture

#### Key Interactions
- Works with PM and Security Reviewer to surface compliance needs
- Communicates requirements to Developers and DevOps for implementation
- Engages stakeholders and legal as needed

---

### Technical Writer

#### Role Summary
Creates and maintains user-facing documentation, runbooks, and release notes to support users and operators.

#### Responsibilities
- Produce release notes, user guides, and runbooks
- Keep documentation up-to-date with releases
- Collaborate on onboarding and internal docs
- Ensure documentation meets quality and readability standards

#### Key Interactions
- Works with PdM and Developers to source accurate content
- Coordinates with Release Manager for release notes and announcements
- Supports Support Owner with runbooks and troubleshooting docs

---

## How to adopt these personas
- Add a short (1–2 line) summary for each persona in docs/octoacme-roles-and-personas.md
- Cross-reference related roles (PM, PdM, Developers) and indicate primary handoffs
- Use these persona definitions in onboarding, role prompts for Copilot Spaces, and when creating RACI/ownership tables

