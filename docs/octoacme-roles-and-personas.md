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

## Engineering Lead / Tech Lead

### Role Summary
Engineering Leads set technical direction, align design choices with delivery goals, and help the team manage implementation risk, sequencing, and engineering quality.

### Responsibilities
- Guide architecture, implementation approach, and technical trade-off decisions
- Break down delivery work with Developers and support realistic estimates
- Identify technical dependencies, risks, and mitigation plans early
- Partner with QA/Testing on quality strategy, automation priorities, and defect triage

### Interactions with Other Personas
- Work with Developers on design reviews, implementation sequencing, and technical mentoring
- Align with Product Managers on scope trade-offs, feasibility, and non-functional requirements
- Coordinate with Project Managers on technical risks, dependencies, and delivery plans
- Partner with QA/Testing on test strategy, release readiness, and defect prioritization
- Escalate major technical risks, constraints, or cross-team dependencies to Stakeholders when needed

### Decision Rights
- Recommends or approves implementation patterns, technical standards, and engineering sequencing
- Advises on technical feasibility and whether proposed scope fits team capacity and system constraints

### Project Lifecycle Participation
- Contributes during discovery, planning, implementation, stabilization, release readiness, and retrospectives

### Escalation and Approvals
- Escalates unresolved technical risks or design conflicts through the Project Manager and relevant Stakeholders
- Approves technical readiness for significant design changes, migrations, or production-impacting implementation plans

### Goals
- Maintain technical quality, delivery predictability, and sustainable engineering practices
- Reduce avoidable rework by making design and dependency decisions early

### Typical Communication
- Technical design reviews, backlog refinement, and sprint planning
- Architecture notes, implementation guidance, and risk discussions
- Readiness updates with Product Managers, Project Managers, and QA/Testing

---

## UX/UI or Product Designer

### Role Summary
UX/UI or Product Designers translate user and business needs into flows, wireframes, and interface decisions that improve usability, accessibility, and adoption.

### Responsibilities
- Create user flows, wireframes, visual designs, and interaction patterns
- Define design acceptance criteria, usability considerations, and accessibility expectations
- Validate concepts through reviews, prototypes, or user feedback
- Clarify design intent during implementation and testing

### Interactions with Other Personas
- Collaborate with Developers on design feasibility, implementation details, and design handoff
- Partner with Product Managers on user problems, priorities, and outcome-focused requirements
- Coordinate with Project Managers on review timing, dependencies, and design deliverables
- Work with QA/Testing to confirm the delivered experience matches design and accessibility expectations
- Review proposed experiences and adoption concerns with Stakeholders when user impact or branding is significant

### Decision Rights
- Recommends design direction, interaction patterns, and usability expectations
- Approves final design intent, accessibility expectations, and user-experience acceptance details before delivery sign-off

### Project Lifecycle Participation
- Participates in discovery, planning, implementation reviews, validation, release preparation, and retrospectives focused on user experience

### Escalation and Approvals
- Escalates unresolved usability, accessibility, or design consistency concerns to Product Managers and Project Managers
- Approves design-complete deliverables and communicates open design risks before release

### Goals
- Improve usability, consistency, and adoption of product changes
- Reduce ambiguity in design handoff and acceptance criteria

### Typical Communication
- Design reviews, annotated mockups, and prototype walkthroughs
- Backlog refinement with Product Managers and Developers
- Validation feedback with QA/Testing and Stakeholders

---

## Business Analyst / Requirements Lead

### Role Summary
Business Analysts translate business needs into clear requirements, workflows, and acceptance details so the team can plan, build, and validate the right solution.

### Responsibilities
- Elicit, document, and refine requirements, assumptions, and constraints
- Map business processes, edge cases, and workflow impacts
- Clarify acceptance criteria, dependencies, and scope changes
- Maintain requirement traceability across planning, implementation, and validation

### Interactions with Other Personas
- Work with Developers to clarify requirements, edge cases, and business rules
- Partner with Product Managers to align requirements with priorities, outcomes, and customer value
- Coordinate with Project Managers on scope, timeline impacts, and decision tracking
- Support QA/Testing with testable acceptance criteria, scenarios, and defect clarification
- Confirm requirements, approvals, and business-process impacts with Stakeholders

### Decision Rights
- Recommends requirement interpretations, process definitions, and acceptance details for business workflows
- Confirms whether documented requirements and scope changes reflect the agreed business need

### Project Lifecycle Participation
- Participates in initiation, discovery, planning, implementation support, validation, release readiness, and retrospective follow-up on requirement gaps

### Escalation and Approvals
- Escalates unresolved requirement conflicts, ambiguous scope, or process impacts through Product Managers and Project Managers
- Approves requirement baselines, acceptance detail updates, and documented scope clarifications before major delivery commitments

### Goals
- Reduce rework by making requirements complete, testable, and traceable
- Improve alignment between business intent and delivered functionality

### Typical Communication
- Requirement workshops, process maps, and acceptance-criteria reviews
- Scope clarification threads with Developers, Product Managers, and QA/Testing
- Decision logs and approval requests with Project Managers and Stakeholders

---

## Release Manager / Deployment Coordinator

### Role Summary
Release Managers coordinate release planning, readiness checks, deployment communications, and rollback preparation so changes move to production in a controlled way.

### Responsibilities
- Build release plans, cutover checklists, and release calendars
- Confirm readiness across code, testing, approvals, environments, and communications
- Coordinate deployment timing, rollback plans, and post-release verification
- Track release issues, actions, and follow-up items

### Interactions with Other Personas
- Coordinate with Developers on deployment steps, technical readiness, and rollback actions
- Align with Product Managers on release scope, launch timing, and customer-impact messaging
- Partner with Project Managers on dependencies, go-live milestones, and stakeholder communication
- Work with QA/Testing on final validation, defect disposition, and release sign-off inputs
- Communicate readiness, release windows, and incidents to Stakeholders

### Decision Rights
- Recommends release timing, release packaging, and readiness checkpoints
- Confirms whether required release inputs and approvals are complete before deployment starts

### Project Lifecycle Participation
- Supports planning for release milestones, participates in implementation readiness reviews, leads go-live coordination, and tracks post-release follow-up

### Escalation and Approvals
- Escalates readiness gaps, deployment blockers, and rollback decisions through Project Managers and operational Stakeholders
- Approves execution of the release checklist and confirms go/no-go inputs are collected before deployment

### Goals
- Reduce deployment risk and improve release predictability
- Keep teams and stakeholders aligned before, during, and after go-live

### Typical Communication
- Release plans, go/no-go meetings, and deployment checklists
- Launch and incident communications with Project Managers, Product Managers, and Stakeholders
- Post-release status updates with Developers and QA/Testing

---

## DevOps / Site Reliability / Operations Engineer

### Role Summary
DevOps, Site Reliability, and Operations Engineers manage environments, deployment automation, observability, reliability, and operational readiness for delivered changes.

### Responsibilities
- Maintain deployment pipelines, environments, and infrastructure readiness
- Define monitoring, alerting, backup, and recovery expectations
- Identify operational risks, capacity concerns, and reliability improvements
- Support incident response and production stabilization activities

### Interactions with Other Personas
- Partner with Developers on deployment automation, environment issues, and production support readiness
- Align with Product Managers on service-level expectations, operational constraints, and launch support needs
- Coordinate with Project Managers on environment dependencies, reliability risks, and operational milestones
- Work with QA/Testing on test environments, data needs, and release validation support
- Communicate operational health, incident impact, and recovery updates to Stakeholders

### Decision Rights
- Recommends infrastructure changes, reliability controls, and operational guardrails
- Approves environment readiness, deployment automation expectations, and operational monitoring baselines

### Project Lifecycle Participation
- Participates in planning, implementation, environment preparation, release readiness, production support, and retrospective follow-up on incidents or reliability risks

### Escalation and Approvals
- Escalates reliability risks, environment instability, or incident-response issues through Project Managers and operational Stakeholders
- Approves operational readiness inputs for releases affecting infrastructure, monitoring, or support coverage

### Goals
- Improve system reliability, deployment consistency, and operational visibility
- Reduce production incidents and shorten recovery times

### Typical Communication
- Runbooks, deployment pipeline updates, and incident channels
- Environment-readiness reviews with Developers, QA/Testing, and Release Managers
- Reliability and incident summaries with Project Managers and Stakeholders

---

## Security / Privacy / Compliance Partner

### Role Summary
Security, Privacy, and Compliance Partners review risks, define required controls, and ensure delivery decisions account for security, data handling, and regulatory obligations.

### Responsibilities
- Assess security, privacy, and compliance risks for planned changes
- Define required controls, reviews, and approval checkpoints
- Review incident, audit, or policy implications tied to delivery decisions
- Support teams with risk mitigation guidance and evidence expectations

### Interactions with Other Personas
- Work with Developers on secure design, implementation controls, and remediation priorities
- Align with Product Managers on data use, user impact, and compliance-driven scope decisions
- Coordinate with Project Managers on approval timing, risk tracking, and escalation paths
- Partner with QA/Testing on security, privacy, or compliance validation activities
- Advise Stakeholders on risk acceptance, audit concerns, and policy obligations

### Decision Rights
- Recommends required security, privacy, and compliance controls for the work
- Approves or blocks releases that are missing required controls, evidence, or risk acceptance decisions

### Project Lifecycle Participation
- Participates in discovery, planning, implementation reviews, validation, release readiness, and post-incident or retrospective follow-up

### Escalation and Approvals
- Escalates unresolved high-risk findings, policy exceptions, or regulatory concerns through Project Managers and executive Stakeholders
- Approves control completion or formal risk acceptance before regulated or high-risk changes proceed

### Goals
- Reduce security, privacy, and compliance risk without slowing delivery unnecessarily
- Make approval expectations and control ownership explicit

### Typical Communication
- Risk reviews, control checklists, and approval records
- Threat-model or compliance discussions with Developers, Product Managers, and QA/Testing
- Escalation updates with Project Managers and Stakeholders

---

## Customer or Support Representative

### Role Summary
Customer or Support Representatives bring frontline customer context into planning, release decisions, and follow-up so teams can better manage adoption, training, and support impact.

### Responsibilities
- Share customer pain points, support trends, and operational feedback
- Identify documentation, training, and launch communication needs
- Help prepare support teams for expected changes and known issues
- Feed post-release customer feedback into prioritization and improvement discussions

### Interactions with Other Personas
- Provide Developers with real customer scenarios, issue patterns, and supportability concerns
- Partner with Product Managers on customer value, launch readiness, and adoption feedback
- Coordinate with Project Managers on communication timing, enablement tasks, and customer-impact risks
- Work with QA/Testing on customer scenarios, support workflows, and known-issue validation
- Represent customer impact and readiness concerns to Stakeholders

### Decision Rights
- Recommends support readiness actions, communication timing, and customer-facing documentation needs
- Confirms whether support teams have the information needed to handle a release effectively

### Project Lifecycle Participation
- Participates in planning, implementation reviews for support impact, release readiness, launch communication, and retrospective follow-up on customer outcomes

### Escalation and Approvals
- Escalates significant customer-impact risks, training gaps, or support-readiness concerns through Product Managers and Project Managers
- Approves support enablement readiness and release communication needs before customer-facing launches

### Goals
- Reduce customer confusion, support disruption, and avoidable escalations
- Improve the team's awareness of real user and support outcomes

### Typical Communication
- Support trend summaries, launch-readiness reviews, and enablement notes
- Customer-impact discussions with Product Managers, Project Managers, and Stakeholders
- Feedback loops with Developers and QA/Testing after release

---

## Executive Sponsor

### Role Summary
Executive Sponsors provide strategic direction, resolve escalated cross-functional issues, and confirm the priorities, resources, and approvals needed for major delivery decisions.

### Responsibilities
- Set strategic context, success expectations, and funding or resource priorities
- Resolve escalated scope, dependency, or organizational trade-offs
- Confirm major milestones, business readiness, and high-impact decision support
- Champion the initiative with senior stakeholders and partner teams

### Interactions with Other Personas
- Rely on Developers and Engineering Leads for concise technical risk and feasibility summaries when major decisions are needed
- Align with Product Managers on strategic priorities, scope changes, and expected outcomes
- Work with Project Managers on escalations, delivery risk, and major milestone decisions
- Review critical quality, readiness, or customer-impact concerns raised by QA/Testing
- Provide direction, approvals, and escalation support across Stakeholders

### Decision Rights
- Approves strategic priority shifts, major scope changes, funding decisions, and formal risk acceptance at the executive level
- Resolves conflicts that exceed the authority of day-to-day delivery roles

### Project Lifecycle Participation
- Participates at kickoff, major planning checkpoints, escalation reviews, release or launch approval points, and retrospectives for strategic initiatives

### Escalation and Approvals
- Receives escalations for unresolved cross-functional blockers, major risks, and resource conflicts
- Approves significant scope changes, milestone resets, or launch decisions with broad business impact

### Goals
- Keep the initiative aligned with business strategy and available resources
- Remove organizational blockers that the delivery team cannot resolve alone

### Typical Communication
- Steering reviews, milestone approvals, and escalation meetings
- Strategic updates with Product Managers, Project Managers, and Stakeholders
- Decision and priority communications for broader leadership audiences

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
