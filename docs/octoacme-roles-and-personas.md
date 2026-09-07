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

## QA / Testing Lead

### Role Summary
QA/Testing Leads define and execute quality assurance strategies, establish testing standards, and ensure that deliverables meet acceptance criteria and quality benchmarks.

### Responsibilities
- Define test strategy and QA approach for the project (automated + manual)
- Create and maintain test plans, test cases, and acceptance criteria
- Coordinate automated test pipelines and manual testing when needed
- Triage, prioritize, and track defects; maintain test coverage metrics
- Validate Definition of Done includes quality gates
- Provide quality reports and trend analysis to stakeholders

### Goals
- Detect and prevent defects before production
- Ensure acceptance criteria are validated for shipped work
- Reduce post-release incidents and rework
- Improve overall product quality and user satisfaction

### Typical Communication
- Planning meetings to define test approaches
- Backlog refinement to clarify acceptance criteria and testability
- Daily standups to report quality blockers and defects
- Release sign-off and post-release quality reports

### Interaction with Other Roles
- Works with Developers to ensure testability and to triage defects
- Partners with Product Managers to validate acceptance criteria and user-facing behavior
- Coordinates with Project Managers about schedule impact from quality risks
- Collaborates with DevOps/Release Engineer on test automation and CI execution

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide technical direction, ensure scalability and maintainability, and provide oversight on design decisions and technical risk management.

### Responsibilities
- Review and approve technical designs and architecture decisions
- Identify technical risks and propose mitigation strategies
- Establish coding standards, design patterns, and best practices
- Mentor developers, conduct architecture and code reviews
- Track and prioritize technical debt and refactoring work
- Advise on platform choices and cross-team integrations

### Goals
- Ensure systems are scalable, secure, and maintainable
- Reduce technical risk and unplanned rework
- Promote consistent engineering standards across the team
- Enable predictable, high-quality delivery

### Typical Communication
- Technical design reviews and architecture sessions
- Code review participation and mentoring conversations
- Risk assessments during planning and backlog grooming
- Cross-team technical alignment meetings

### Interaction with Other Roles
- Guides Developers on technical decisions and implementation approaches
- Advises Product Managers on feasibility and technical trade-offs
- Works with Project Managers to sequence tech work and refactors
- Coordinates with QA on testability and with DevOps on operational concerns

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders or Sponsors provide executive oversight, set strategic priorities, and authorize resources and key decisions for the project.

### Responsibilities
- Sponsor project funding and resource allocation
- Approve major scope, timeline, and budget decisions
- Provide strategic business context and acceptance of outcomes
- Act as escalation point for major risks and decisions

### Goals
- Ensure project aligns with organizational priorities
- Maximize business impact and return on investment
- Remove organizational blockers and provide necessary support

### Typical Communication
- High-level status updates and milestone reviews
- Periodic stakeholder briefings and decision checkpoints
- Escalation meetings for business-impacting risks

### Interaction with Other Roles
- Works with Product Managers on prioritization and success metrics
- Receives regular updates from Project Managers
- Engages with Product Leads and PMs for go/no-go decisions

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters or Agile Coaches facilitate team processes, remove impediments, and coach teams on agile practices to improve flow and delivery.

### Responsibilities
- Facilitate ceremonies (standups, planning, retrospectives)
- Remove impediments and protect the team from distractions
- Coach the team on agile practices and continuous improvement
- Help the team adopt effective estimation and delivery practices
- Track team health and process metrics

### Goals
- Improve team productivity and flow
- Foster a culture of continuous improvement and collaboration
- Reduce cycle time and increase predictability

### Typical Communication
- Daily facilitation in standups and planning sessions
- Retrospective facilitation and follow-up on action items
- Regular coaching sessions with team members and leads

### Interaction with Other Roles
- Works with Project Managers to coordinate timelines and impediments
- Supports Product Managers by helping refine backlog readiness
- Collaborates with Developers and QA to improve team practices

---

## Design / UX Lead

### Role Summary
Design/UX Leads define the user experience, produce design assets, and validate usability to ensure features meet user needs and expectations.

### Responsibilities
- Lead user research, wireframes, and high-fidelity designs
- Define interaction patterns and accessibility considerations
- Validate designs through usability testing and prototypes
- Provide design review and guidance to developers
- Maintain design system components and patterns

### Goals
- Deliver usable, accessible, and delightful user experiences
- Reduce rework due to usability issues
- Ensure consistency across product interfaces

### Typical Communication
- Design reviews and walkthroughs during planning
- Collaboration sessions with Product Managers and Developers
- Usability test findings and design decisions communicated to stakeholders

### Interaction with Other Roles
- Works with Product Managers to shape features and acceptance criteria
- Partners with Developers to implement designs and ensure fidelity
- Coordinates with QA to include usability checks in acceptance tests

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers manage deployment pipelines, infrastructure, and release processes to ensure reliable delivery and operation of the product.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage infrastructure as code and environment configurations
- Monitor deployment health, rollback processes, and post-deploy verification
- Ensure security scanning and operational checks run in pipeline
- Coordinate release windows and cutover activities

### Goals
- Enable reliable, repeatable, and fast releases
- Reduce manual release steps and deployment risk
- Improve observability and incident response readiness

### Typical Communication
- Release planning meetings and deployment runbooks
- Incident response handoffs with on-call and SRE teams
- Pipeline status reports and deployment notifications

### Interaction with Other Roles
- Works with Developers to automate build and test execution
- Collaborates with QA on automated test pipelines and smoke tests
- Coordinates with Project Managers and Product Managers on release timing and risk
- Escalates operational risks to Stakeholders as needed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When documenting projects, indicate which of these roles are assigned and who the primary contacts are.
