# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Roles describe responsibilities, not required headcount: one person may hold multiple roles. For each project, name the people accountable for decisions and approvals; contributors and reviewers do not automatically own those decisions.

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

## Executive Sponsor / Project Sponsor

### Role Summary
Provides strategic direction and organizational support, and is accountable for the business case and escalated decisions.

### Responsibilities
- Confirm the initiative's strategic fit and expected business value
- Secure or escalate resource needs and resolve cross-team barriers
- Decide escalated scope or priority trade-offs within delegated authority
- Review status, major risks, and decisions requiring sponsorship

### Decision Boundaries
- Owns sponsorship, resource commitments, and escalated business decisions
- Does not replace the Product Manager's ongoing product prioritization or the Project Manager's day-to-day coordination

### Goals
- Ensure the project remains aligned with organizational priorities
- Enable timely decisions and remove barriers to delivery

### Typical Communication
- Milestone and monthly stakeholder updates
- Escalation summaries, decision requests, and business-case reviews

### Interactions and Handoffs
- Partners with the Product Manager to align outcomes and resolve strategic priority conflicts
- Receives project status, risk, dependency, and escalation updates from the Project Manager
- Consults Stakeholders and Subject-Matter Experts for domain impact before major decisions

---

## Business Analyst / Requirements Lead

### Role Summary
Turns stakeholder needs and business processes into clear, traceable requirements for planning and delivery.

### Responsibilities
- Elicit and document needs, workflows, assumptions, and constraints
- Map requirements to backlog items, acceptance criteria, and validation evidence
- Identify gaps, dependencies, and approval needs as requirements evolve

### Decision Boundaries
- Owns requirements clarity and traceability, not product priority or final scope decisions
- Escalates conflicts in needs or interpretation to the Product Manager and relevant decision-maker

### Goals
- Make requirements understandable, testable, and connected to intended outcomes
- Reduce ambiguity and avoid preventable rework

### Typical Communication
- Discovery workshops and stakeholder interviews
- Requirements notes, process maps, backlog refinement, and acceptance-criteria reviews

### Interactions and Handoffs
- Works with the Product Manager to refine needs and prepare items for prioritization
- Clarifies feasibility and edge cases with Developers
- Coordinates with QA/Test Engineers to make requirements verifiable
- Shares dependencies, open questions, and approval needs with the Project Manager for planning and tracking

---

## UX / Accessibility Researcher or Designer

### Role Summary
Researches user needs and shapes usable, accessible workflows and interfaces.

### Responsibilities
- Plan and conduct user research appropriate to the project
- Create and validate user flows, interaction designs, and accessibility considerations
- Document design decisions, usability findings, and unresolved experience risks

### Decision Boundaries
- Recommends and validates experience design; product scope and priority remain with the Product Manager
- Works with Developers on implementation trade-offs and escalates unresolved accessibility risks to the accountable project authority

### Goals
- Make delivered workflows useful, understandable, and accessible to intended users
- Validate important assumptions before they become costly to change

### Typical Communication
- Research readouts, design reviews, prototypes, and accessibility findings
- Design specifications and discussions with product, engineering, and QA

### Interactions and Handoffs
- Aligns research goals and user outcomes with the Product Manager
- Hands off designs, interaction states, and constraints to Developers
- Partners with QA/Test Engineers on usability and accessibility validation
- Shares findings, design dependencies, and readiness needs with the Project Manager for scheduling and tracking

---

## QA / Test Engineer

### Role Summary
Plans and performs quality validation so the team can assess whether delivered work meets expectations and release criteria.

### Responsibilities
- Define a risk-based test approach and maintain appropriate test coverage
- Verify acceptance criteria and report defects, quality risks, and test results
- Coordinate regression, integration, and release-readiness testing

### Decision Boundaries
- Reports evidence and quality risks; does not unilaterally change product acceptance criteria
- Release approval belongs to the designated accountable authority for the project

### Goals
- Find important issues early and provide clear evidence of product quality
- Make test readiness and remaining risks visible before release

### Typical Communication
- Test plans, defect reports, test results, and readiness reviews
- Ongoing coordination with Developers during implementation and remediation

### Interactions and Handoffs
- Works with Developers to design testable changes, prevent defects, and verify fixes
- Clarifies expected behavior and acceptance criteria with the Product Manager and Business Analyst
- Reports test progress, defects, and schedule impacts to the Project Manager
- Provides release evidence and unresolved quality risks to the Release / Operations Owner and designated approver

---

## Security / Privacy / Compliance Reviewer

### Role Summary
Identifies applicable security, privacy, and regulatory obligations and reviews risks and supporting evidence.

### Responsibilities
- Identify relevant requirements, threat or privacy concerns, and review checkpoints
- Advise on controls, evidence, mitigations, and unresolved risks
- Review project artifacts or implementation within the reviewer's assigned scope

### Decision Boundaries
- Provides specialist findings and recommendations; approval authority depends on the organization and context
- Name the accountable approver for each required security, privacy, or compliance decision rather than assuming the reviewer owns approval

### Goals
- Surface obligations and risks early enough to address them
- Ensure required reviews and decisions are documented before release

### Typical Communication
- Risk assessments, review comments, control evidence, and approval or exception records
- Escalations for high-impact findings or missed review gates

### Interactions and Handoffs
- Advises the Product Manager on constraints and trade-offs affecting scope or user outcomes
- Works with Developers on controls, secure implementation, and remediation evidence
- Coordinates review gates, dependencies, and escalations with the Project Manager
- Shares findings and approval status with the named accountable authority and Release / Operations Owner

---

## Release / Operations Owner

### Role Summary
Coordinates deployment and operational readiness, including rollback, monitoring, and support handoff.

### Responsibilities
- Define deployment, rollback, monitoring, and support-readiness needs
- Confirm operational dependencies and ownership before release
- Coordinate post-deployment verification and communicate operational issues

### Decision Boundaries
- Owns or coordinates operational readiness within the assigned service scope
- Product launch and scope decisions remain with the Product Manager; project schedule coordination remains with the Project Manager

### Goals
- Make releases supportable, observable, and recoverable
- Ensure service ownership and support are clear after deployment

### Typical Communication
- Release checklists, deployment plans, runbooks, and readiness reviews
- Monitoring updates, incident communications, and support handoff notes

### Interactions and Handoffs
- Coordinates deployment and rollback requirements with Developers
- Uses QA/Test Engineer results and the designated approver's release decision to assess readiness
- Aligns launch outcomes and customer communication with the Product Manager
- Shares release dependencies, timing, and readiness risks with the Project Manager
- Hands operational ownership and support guidance to the named service or support team

---

## Stakeholder / Subject-Matter Expert

### Role Summary
Contributes domain knowledge and validates assumptions, impacts, and outcomes within an agreed area of expertise.

### Responsibilities
- Explain domain processes, constraints, and affected stakeholder needs
- Review requirements or deliverables within an agreed scope and provide timely feedback
- Identify process impacts, dependencies, and risks from the stakeholder perspective

### Decision Boundaries
- Provides input and approvals only when explicitly assigned authority for the decision
- Does not assume product prioritization or project coordination responsibilities by virtue of being a stakeholder

### Goals
- Ensure domain realities and affected users are represented in project decisions
- Provide clear, actionable feedback at planned review points

### Typical Communication
- Discovery sessions, requirements reviews, milestone updates, and decision records
- Escalations through the agreed Product Manager or Project Manager contact

### Interactions and Handoffs
- Shares user and domain needs with the Product Manager and Business Analyst for discovery and backlog refinement
- Provides domain validation and acceptance feedback to the Product Manager and QA/Test Engineer
- Works with the Project Manager on review timing, dependencies, and escalations
- Raises material operational or compliance concerns to the appropriate specialist reviewer or accountable authority

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
