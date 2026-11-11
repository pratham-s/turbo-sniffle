# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be combined or adapted to fit a team's size and project needs; when they are combined, decision ownership and handoffs should remain explicit.

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

## Product Lead or Sponsor

### Role Summary
The Product Lead or Sponsor provides strategic direction, confirms the business need, and supports major priority and investment decisions. In some teams, this role may be held by a senior stakeholder or combined with another product leadership role.

### Responsibilities
- Set or confirm strategic objectives and expected business outcomes
- Resolve priority or scope trade-offs that exceed the Product Manager's decision authority
- Secure stakeholder alignment and help obtain needed resources
- Participate in key go/no-go, milestone, and escalation decisions

### Interaction with Existing Roles
- Partners with the Product Manager to align the product vision, outcomes, and prioritization authority
- Works with the Project Manager on decision deadlines, resource constraints, milestone changes, and escalations
- Gives Developers and other delivery contributors context for significant business or scope decisions through the Product Manager and Project Manager

---

## UX/UI Designer or User Researcher

### Role Summary
The UX/UI Designer or User Researcher investigates user needs and shapes accessible, usable experiences, translating findings into design guidance the team can validate and implement.

### Responsibilities
- Plan and conduct user research, and share evidence and findings
- Create user journeys, interaction designs, prototypes, and design specifications as needed
- Validate usability and accessibility with representative users
- Identify experience risks and keep design decisions and assumptions documented

### Interaction with Existing Roles
- Collaborates with the Product Manager to connect user needs, research evidence, and product outcomes to requirements and acceptance criteria
- Works with Developers and the Engineering/Technical Lead to assess feasibility and resolve implementation questions
- Coordinates with the QA/Testing Lead so usability and accessibility needs are covered in validation
- Shares research plans and findings with the Project Manager so related work, dependencies, and review points can be planned

---

## Engineering or Technical Lead

### Role Summary
The Engineering or Technical Lead guides technical design and engineering execution, helping the team make maintainable decisions and understand technical risks. This role may be filled by a senior Developer on smaller teams.

### Responsibilities
- Guide architecture, technical design, and engineering standards
- Support estimation and identify technical dependencies, constraints, and risks
- Facilitate technical reviews and promote maintainability, security, and operability
- Help Developers resolve complex implementation issues and coordinate technical work

### Interaction with Existing Roles
- Supports Developers with implementation guidance, reviews, and technical decisions while preserving shared team ownership of delivery
- Partners with the Product Manager to explain technical options and trade-offs in terms of scope, value, and risk
- Coordinates with the Project Manager on dependencies, sequencing, estimates, and technical risks that affect delivery commitments
- Works with the QA/Testing Lead and Operations/SRE or Release Manager to ensure testability and operational requirements are considered early

---

## QA or Testing Lead

### Role Summary
The QA or Testing Lead coordinates quality strategy and validation, making quality status and release risks visible. The role may be performed by Developers or shared across the team when there is no dedicated lead.

### Responsibilities
- Define a risk-based test approach and identify required test coverage
- Coordinate validation against acceptance criteria, including integration and regression testing as appropriate
- Track and communicate defects, quality risks, and unresolved issues
- Advise on quality readiness and evidence needed for release decisions

### Interaction with Existing Roles
- Works with the Product Manager to clarify acceptance criteria and expected behavior
- Partners with Developers and the Engineering/Technical Lead on testability, automation, defect triage, and fixes
- Shares quality status and risks with the Project Manager for plans, reports, and escalation
- Coordinates with the Operations/SRE or Release Manager on release verification and monitoring expectations

---

## Operations/SRE or Release Manager

### Role Summary
The Operations/SRE or Release Manager helps ensure that changes can be deployed and supported safely. Depending on the team's structure, this role may be a dedicated operations specialist or shared by the delivery team.

### Responsibilities
- Define operational readiness needs, including monitoring, alerting, support ownership, and runbooks
- Coordinate deployment plans, release checks, and rollback or recovery preparations
- Monitor service health during and after releases and coordinate incident response when needed
- Capture operational risks and feed reliability improvements back into planning

### Interaction with Existing Roles
- Works with Developers and the Engineering/Technical Lead to design for operability and prepare deployment and recovery steps
- Coordinates with the QA/Testing Lead on release verification and test evidence
- Aligns with the Product Manager on the impact and timing of changes that affect users
- Works with the Project Manager on release schedules, dependencies, readiness status, and stakeholder communications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign only the roles needed for a project, but make decision ownership, responsibilities, and collaboration points clear.
