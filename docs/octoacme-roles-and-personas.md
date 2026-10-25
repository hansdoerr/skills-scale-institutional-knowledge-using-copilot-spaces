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

## Engineering Managers

### Role Summary
Engineering Managers align delivery with the product roadmap, support team capacity planning, and help remove operational and execution blockers so engineering can deliver effectively.

### Responsibilities
- Support team planning, staffing, and workload balancing
- Partner with Product and Project Managers on roadmap and milestone feasibility
- Remove blockers, resolve cross-team dependencies, and escalate risks early
- Coach engineering leadership practices and support healthy delivery rhythms
- Help maintain team health, focus, and execution quality

### Goals
- Improve delivery predictability and team effectiveness
- Ensure engineering priorities align with approved plans and stakeholder needs
- Reduce friction between execution, quality, and roadmap commitments

### Typical Communication
- Weekly engineering planning and delivery reviews
- Capacity and resourcing discussions with PM and Product leadership
- Escalation updates for blockers, staffing constraints, and cross-team dependencies

### Interaction with Existing Roles
- Works closely with Project Managers to align sprint commitments and resource availability.
- Partners with Product Managers to translate roadmap priorities into feasible delivery plans.
- Supports Developers by removing impediments and clarifying ownership during execution.
- Shares progress and risk signals with stakeholders when delivery impacts scope, timelines, or resourcing.

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects own the technical direction, design quality, and decision-making needed to keep delivery coherent across systems, dependencies, and future scalability.

### Responsibilities
- Define technical standards, architecture patterns, and design trade-offs
- Review system design, integration points, and major technical dependencies
- Guide implementation decisions and help resolve technical ambiguity
- Support engineering quality, maintainability, and operational readiness
- Coordinate with cross-functional teams on platform, API, and data interoperability

### Goals
- Deliver sustainable, scalable solutions that fit the target architecture
- Reduce rework caused by unclear technical decisions or design drift
- Maintain alignment between business goals and technical execution

### Typical Communication
- Architecture reviews and design discussions
- Technical dependency planning with engineering and PM stakeholders
- Guidance in design discussions, PR reviews, and issue triage

### Interaction with Existing Roles
- Works with Developers to make technical trade-offs and review implementation choices.
- Helps Product Managers and Project Managers understand technical risks, dependencies, and delivery implications.
- Coordinates with Security and QA partners to ensure architecture decisions align with quality and compliance needs.
- Provides the technical foundation for planning decisions, especially around major integrations or platform changes.

---

## QA / Test Lead

### Role Summary
QA / Test Leads define validation strategy, quality gates, and release-readiness checks to make sure features meet customer and operational expectations before release.

### Responsibilities
- Define test strategy, regression coverage, and acceptance validation plans
- Partner with engineering on manual and automated test design
- Review quality risks, defects, and release readiness signals
- Support reproducible validation for critical workflows and customer journeys
- Help maintain confidence that changes meet agreed Definition of Done

### Goals
- Catch defects early and reduce production risk
- Balance speed of delivery with confidence in release quality
- Make quality expectations clear to cross-functional teams

### Typical Communication
- Test plans, quality reviews, and release-readiness check-ins
- Defect triage and validation updates with developers and PMs
- Feedback loops with stakeholders on user-facing quality and readiness

### Interaction with Existing Roles
- Collaborates with Developers to define acceptance criteria and regression coverage.
- Provides Product Managers and PMs with evidence of quality readiness and risk areas.
- Works with Release Manager / Ops Partner to define post-deployment validation and rollback signals.
- Helps Security and Compliance partners confirm that risk and compliance requirements are validated in practice.

---

## Security / Compliance Partner

### Role Summary
Security and Compliance Partners review project risks, controls, and policy adherence so teams can deliver safely without creating avoidable regulatory, privacy, or security exposure.

### Responsibilities
- Assess security requirements, privacy considerations, and compliance obligations
- Review architecture, workflows, and data handling practices for risk exposure
- Support secure design patterns, vulnerability triage, and mitigation planning
- Validate controls for release readiness and operational compliance
- Coordinate with stakeholders on remediation and ongoing governance

### Goals
- Reduce security and compliance risk while enabling delivery progress
- Ensure sensitive data, access controls, and policy requirements are addressed early
- Build trust with customers, regulators, and internal stakeholders

### Typical Communication
- Security review checkpoints and risk assessments
- Policy and control discussions with Product, Engineering, and PM leads
- Escalation of high-impact issues or compliance concerns during planning and release

### Interaction with Existing Roles
- Reviews technical decisions with the Technical Lead / Architect and Developers.
- Works with Product Managers and PMs to assess risk trade-offs and delivery impact.
- Provides required controls and review checkpoints before release or major deployments.
- Partners with Customer Success and Release teams to ensure the launch plan reflects security and adoption readiness.

---

## Customer Success / Adoption Lead

### Role Summary
Customer Success and Adoption Leads connect delivery work to customer outcomes by translating user feedback, adoption patterns, and stakeholder needs into actionable priorities and rollout guidance.

### Responsibilities
- Gather and synthesize customer feedback, usage issues, and adoption blockers
- Support stakeholder communication around rollout plans, training, and readiness
- Identify feature gaps and success risks that influence backlog decisions
- Help validate whether a release is ready from a user-impact perspective
- Coordinate with product and delivery teams on customer-facing communication

### Goals
- Improve adoption, satisfaction, and customer retention
- Ensure customer needs remain visible in planning and release decisions
- Turn feedback into practical product and rollout improvements

### Typical Communication
- Feedback reviews with Product Managers and delivery leads
- Customer-facing updates, launch readiness check-ins, and support coordination
- Stakeholder briefings on release impact, adoption trends, and risks

### Interaction with Existing Roles
- Delivers customer insight to Product Managers for prioritization and backlog refinement.
- Partners with PMs to align rollout timing, stakeholder communication plans, and adoption milestones.
- Supports Developers and QA teams by clarifying expected user workflows and acceptance conditions.
- Coordinates with Release Manager / Ops Partner to ensure operational readiness matches customer expectations.

---

## Release Manager / Ops Partner

### Role Summary
Release Managers and Ops Partners coordinate deployment readiness, operational checks, and post-release validation to reduce risk and improve reliability during rollout.

### Responsibilities
- Coordinate release windows, deployment readiness, and launch communications
- Maintain rollback, contingency, and incident-response readiness
- Validate staging and production checks before and after deployment
- Support observability, monitoring, and quick issue detection during rollout
- Capture launch outcomes and lessons learned for future releases

### Goals
- Reduce deployment risk and improve release confidence
- Ensure smooth production changes with clear operational ownership
- Make post-release validation and recovery plans visible to the team

### Typical Communication
- Release checklists, deployment readiness reviews, and go-live updates
- Incident or rollback coordination with engineering and leadership stakeholders
- Post-release reporting and operational follow-up with PM and Product leads

### Interaction with Existing Roles
- Works with QA and Engineering to confirm launch readiness and smoke-test coverage.
- Coordinates with Project Managers and Product Managers on release timing, stakeholder updates, and communication planning.
- Partners with Security and Compliance teams to ensure deployment controls and governance are in place.
- Supports Developers by clarifying operational readiness and rollback requirements for production changes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these role definitions reinforce accountability across planning, delivery, quality, security, and release activities.

