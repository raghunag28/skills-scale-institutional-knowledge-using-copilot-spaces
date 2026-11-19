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

## Technical Lead / Engineering Lead

### Role Summary
The Technical Lead guides engineering decisions and helps the team deliver a maintainable solution that meets product requirements and quality standards.

### Responsibilities
- Set or coordinate technical direction, architecture, and design decisions
- Support Developers with implementation choices, code quality, and technical reviews
- Help estimate work and identify technical risks, dependencies, and mitigations
- Ensure technical design supports testability, security, reliability, and observability
- Escalate material technical trade-offs and delivery risks

### Goals
- Deliver a sound, maintainable technical solution
- Surface technical risks and dependencies early
- Enable Developers to make consistent, well-informed decisions

### Typical Communication
- Design discussions and technical decision records
- Backlog refinement, estimation, and delivery planning
- Code reviews and risk updates with the Project Manager

### Interactions with Existing Roles
Partners with the Product Manager to assess feasibility and trade-offs, and with the Project Manager to communicate estimates, dependencies, and risks. Guides Developers without taking over their implementation ownership, and works with QA/Testing to make designs testable and acceptance criteria verifiable. Coordinates with the Security Lead and Release Manager when architecture or deployment decisions affect security or release readiness.

---

## Security Lead

### Role Summary
The Security Lead helps the team identify and address security requirements and risks throughout planning, development, and release.

### Responsibilities
- Advise on security requirements, threat considerations, and appropriate controls
- Review security risks and recommend mitigations or escalation
- Coordinate security reviews and scanning with engineering and QA
- Help ensure security findings are triaged and resolved or explicitly accepted by the appropriate decision-maker
- Support security incident escalation through the security incident process

### Goals
- Identify security concerns early and track them to resolution
- Make security expectations clear for the project and release
- Ensure security risks have an accountable owner and response

### Typical Communication
- Security requirements and review findings
- Risk register updates and mitigation tracking
- Security scan results and incident escalation channels

### Interactions with Existing Roles
Works with the Product Manager to understand product and data risks, and with the Project Manager to track security dependencies, gates, and escalations. Partners with the Technical Lead and Developers on secure design and implementation, and with QA/Testing on security test coverage. Coordinates with the Release Manager on release readiness and escalates security incidents through the established Security on-call process.

---

## Data / Analytics Lead

### Role Summary
The Data / Analytics Lead helps define how project outcomes will be measured and ensures the team can use trustworthy data to evaluate impact.

### Responsibilities
- Translate product goals into measurable outcomes and a measurement plan
- Advise on event instrumentation, data quality, and reporting needs
- Validate that dashboards and metrics represent the agreed success criteria
- Analyze results and communicate evidence, limitations, and trends
- Recommend follow-up questions or adjustments based on observed outcomes

### Goals
- Make success measures clear and useful for decision-making
- Improve confidence in outcome and usage data
- Help teams learn whether delivered changes achieved their intended impact

### Typical Communication
- Metric definitions and measurement plans
- Dashboard reviews and outcome summaries
- Product reviews and project status discussions

### Interactions with Existing Roles
Collaborates with the Product Manager to define success metrics and interpret outcomes, and with the Project Manager to report progress against agreed measures. Works with Developers and the Technical Lead on instrumentation and data quality, and with QA/Testing to validate that tracking and reporting behave as expected. Shares findings with stakeholders to inform prioritization and follow-up decisions.

---

## Customer / UX Researcher

### Role Summary
The Customer / UX Researcher gathers and synthesizes customer needs and usability evidence to help the team shape and validate solutions.

### Responsibilities
- Plan and conduct appropriate customer, user, or usability research
- Synthesize findings into actionable insights and communicate limitations
- Help validate problem statements, concepts, and user journeys
- Identify usability risks and opportunities for improvement
- Share relevant research evidence with the team while respecting privacy and consent requirements

### Goals
- Keep decisions grounded in customer needs and observed behavior
- Reduce the risk of delivering confusing or ineffective experiences
- Make research insights accessible to the delivery team

### Typical Communication
- Research plans, findings, and experience maps
- Product discovery and design reviews
- Usability feedback and acceptance discussions

### Interactions with Existing Roles
Partners with the Product Manager to clarify customer problems and validate concepts, and with the Project Manager to plan research activities and communicate dependencies. Shares findings with Developers and the Technical Lead so solutions account for user needs and technical constraints. Works with QA/Testing to include usability considerations in acceptance and validation; the Product Manager remains accountable for product priorities and decisions.

---

## Release Manager

### Role Summary
The Release Manager coordinates release readiness and deployment activities so changes can be delivered safely and communicated clearly.

### Responsibilities
- Coordinate release scope, schedule, readiness checks, and deployment windows
- Confirm that acceptance criteria, CI, security checks, smoke tests, and rollback or mitigation plans are addressed
- Coordinate deployment verification and post-release follow-up
- Communicate release status, known issues, and operational handoffs
- Escalate unresolved release risks or blockers to the appropriate owners

### Goals
- Make release readiness visible and decision ownership clear
- Reduce avoidable deployment risk and improve post-deploy verification
- Ensure stakeholders and support teams receive timely release information

### Typical Communication
- Release plans, readiness checklists, and release notes
- Deployment coordination and post-deploy verification updates
- Risk and incident communications with engineering and operations

### Interactions with Existing Roles
Works with the Product Manager to confirm release scope and customer impact, and with the Project Manager to align timing, dependencies, and status reporting. Coordinates with Developers and QA/Testing on merged work, test results, and smoke tests; checks security readiness with the Security Lead and technical readiness with the Technical Lead. Partners with the Support Lead on support materials and handoffs. The Release Manager coordinates readiness but does not replace the accountable owners for product scope, quality, security, or deployment operations.

---

## Support Lead

### Role Summary
The Support Lead prepares customer-facing support teams for changes and brings operational feedback into project and release decisions.

### Responsibilities
- Identify support impacts, training needs, and documentation requirements
- Prepare support guidance for changes, known issues, and customer questions
- Coordinate support readiness and escalation paths before release
- Share customer-reported issues and recurring themes with the delivery team
- Help coordinate incident communications and post-incident feedback

### Goals
- Enable support teams to assist customers confidently after changes
- Make customer-impacting issues visible and actionable
- Close the feedback loop between support, product, and engineering

### Typical Communication
- Support readiness reviews, knowledge articles, and release notes
- Known-issue and escalation updates
- Customer feedback summaries and incident follow-ups

### Interactions with Existing Roles
Works with the Product Manager to understand customer impact and communicate feedback, and with the Project Manager to plan readiness tasks and raise blockers. Coordinates with the Release Manager on release notes, timing, and handoffs; consults Developers, the Technical Lead, and QA/Testing on technical behavior and known issues. Escalates security concerns through the Security Lead and established incident process.

---

## Stakeholder Liaison / Executive Sponsor

### Role Summary
The Stakeholder Liaison / Executive Sponsor represents strategic interests, enables timely decisions, and helps resolve organizational constraints that exceed the delivery team's authority.

### Responsibilities
- Clarify strategic context, intended business outcomes, and sponsorship
- Make or obtain timely decisions on major scope, priority, or resource trade-offs
- Resolve cross-organizational constraints and escalate business-impacting risks
- Review concise progress, risk, and decision updates
- Support alignment among stakeholder groups without directing day-to-day delivery work

### Goals
- Maintain alignment between project outcomes and organizational priorities
- Remove barriers that the delivery team cannot resolve directly
- Ensure major decisions have clear ownership and rationale

### Typical Communication
- Milestone and sponsor updates
- Decision requests, escalations, and risk summaries
- Product and Project Manager alignment discussions

### Interactions with Existing Roles
Partners primarily with the Product Manager on strategic outcomes and prioritization, and with the Project Manager on delivery status, risks, dependencies, and decisions requiring escalation. Receives recommendations from technical, security, analytics, research, release, and support roles through the appropriate leads. The sponsor makes decisions within delegated authority; the Product Manager retains product prioritization ownership and the Project Manager coordinates delivery.

---

## Role Interaction Summary

| Role | Primary ownership | Key interactions |
| --- | --- | --- |
| Product Manager | Product outcomes, scope, and backlog priorities | Uses research and analytics to inform decisions; aligns trade-offs with the Technical Lead; partners with the Project Manager and stakeholders |
| Project Manager | Delivery coordination, schedule, risks, and communication | Tracks cross-role dependencies and escalations; coordinates with all leads and the sponsor |
| Technical Lead / Engineering Lead | Technical direction and engineering risks | Guides Developers; aligns with Product, Project, QA, Security, and Release roles |
| Security Lead | Security requirements, risks, and incident escalation | Advises engineering and QA; tracks mitigations with the Project Manager; checks release readiness |
| Data / Analytics Lead | Measurement plans and outcome evidence | Defines metrics with Product; works with engineering and QA on instrumentation and validation |
| Customer / UX Researcher | Customer and usability evidence | Informs Product decisions and shares findings with engineering and QA |
| Release Manager | Release coordination and readiness visibility | Aligns Product scope, Project timing, engineering/QA/security readiness, and Support handoffs |
| Support Lead | Support readiness and customer feedback | Prepares with Release; coordinates customer impact and follow-up with Product and engineering |
| Stakeholder Liaison / Executive Sponsor | Strategic alignment and decisions beyond team authority | Receives status and escalations from Product and Project Managers; resolves organizational constraints |
| QA / Testing | Validation against acceptance criteria and quality expectations | Partners with Product on acceptance criteria and with engineering, security, and release roles on test coverage and readiness |

These roles may be combined or shared in smaller teams. Assign named owners for responsibilities and decision points for each project; adding a persona does not imply a separate full-time position or transfer accountability away from existing role owners.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
