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

## New/Additional Personas (proposed additions)

Each new persona below includes a short description, primary responsibilities, and how they typically interact with existing roles.

### Delivery Lead / Scrum Master
- Responsibilities:
  - Facilitate team ceremonies (standups, planning, retrospectives)
  - Remove team-level impediments and coordinate cross-functional availability
  - Help the team follow Agile practices and maintain cadence
- Interactions:
  - Works closely with the Project Manager (PM) to align on delivery cadence and scheduling
  - Collaborates with Developers and QA to unblock work and clarify scope
  - Coordinates with the Product Manager (PdM) to ensure backlog readiness and clarify acceptance criteria
  - Escalates unresolved impediments to PM

### Technical Lead / Engineering Lead
- Responsibilities:
  - Make architecture and design decisions for features
  - Own code quality, technical direction, and mentorship for the engineering team
  - Identify and drive technical debt remediation
- Interactions:
  - Collaborates with Developers on implementation and code reviews
  - Escalates technical risks and cross-team technical dependencies to the PM
  - Works with the Solution Architect for system-wide design alignment
  - Advises PdM on technical feasibility and effort estimates

### Solution Architect
- Responsibilities:
  - Define system-level architecture, integration patterns, and non-functional requirements (scalability, security, performance)
  - Provide design guidelines for feature implementations across teams
- Interactions:
  - Works with PdM and PM during planning to ensure feasibility and to identify integration impacts
  - Partners with Technical Lead to validate solutions and review critical designs
  - Engages with SRE/Release Engineer on operational concerns and deployment architecture

### Release / Build Engineer
- Responsibilities:
  - Maintain CI/CD pipelines and build systems
  - Manage release choreography, deployment automation, and rollback procedures
  - Ensure release reliability and enforce release hygiene (versioning, tagging, changelogs)
- Interactions:
  - Coordinates with Developers and Technical Lead for release readiness (builds, artifacts)
  - Works with QA for pre-release testing and smoke test automation
  - Collaborates with PM on release windows and communication
  - Engages SRE/Ops for production deployments and monitoring handoffs

### Security Engineer (Security SME)
- Responsibilities:
  - Assess designs and implementations for security risks
  - Run security scans and penetration tests, and provide remediation guidance
  - Maintain security standards and checklists for code and releases
- Interactions:
  - Reviews architecture and PRs with Technical Lead and Developers
  - Reports findings and risk impact to PM and PdM when security exposure affects releases or scope
  - Works with Release Engineer and SRE to ensure secure deployment practices

### Site Reliability Engineer (SRE) / Ops Lead
- Responsibilities:
  - Define monitoring, alerting, and runbooks
  - Support production incidents and reliability engineering efforts
  - Drive operational readiness and post-incident analysis
- Interactions:
  - Works with Release Engineer for deployment readiness and rollback planning
  - Partners with Developers for incident fixes and reliability improvements
  - Communicates incident status to PM and stakeholders during critical events

### Business Analyst / Product Owner Support
- Responsibilities:
  - Translate business requirements into detailed acceptance criteria and user stories
  - Maintain stakeholder-facing documentation (requirements, workflows)
  - Clarify edge cases and business rules during implementation
- Interactions:
  - Works directly with PdM to refine backlog and prioritize detailed requirements
  - Engages with Developers and QA to answer implementation questions and validate acceptance criteria
  - Coordinates with PM for stakeholder communications when requirements change

### Data Analyst / Metrics Owner
- Responsibilities:
  - Define and own success metrics and key performance indicators (KPIs)
  - Create dashboards and validate feature impact post-release
  - Provide data-driven recommendations for prioritization and optimizations
- Interactions:
  - Partners with PdM to define measurable success criteria
  - Works with Developers/Technical Lead to instrument metrics and telemetry
  - Collaborates with PM to ensure metrics tracking is included in release checklists

---

## How these personas should be used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Suggested next steps (for the repository/process update)
1. Add each persona as a clearly labeled section in docs/octoacme-roles-and-personas.md (this file).
2. Cross-reference personas in process docs (planning, release, risk, execution) where role handoffs or responsibilities are expected.
3. Review the proposed personas with PM, PdM, Technical Lead, Security, and SRE to ensure accuracy and alignment.
4. Link persona sections from relevant process docs (e.g., add a "Roles" reference in the release checklist and risk register templates).
