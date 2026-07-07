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

## QA / Test Engineer

### Role Summary
QA / Test Engineers define and execute test strategies to validate quality, surface risks before release, and ensure that acceptance criteria are met consistently across the delivery lifecycle.

### Responsibilities
- Define test strategies, test plans, and coverage targets
- Validate acceptance criteria and definition of done
- Coordinate regression and integration test coverage
- Identify, document, and track defects through resolution
- Communicate quality readiness and release risks to the team

### Goals
- Prevent defects from reaching production
- Maintain confidence in release quality through consistent coverage
- Surface risk early enough to influence delivery decisions

### Typical Communication
- Test plans and coverage reports shared before major releases
- Defect triage sessions with Developers and Project Managers
- Quality sign-off summaries before deployment windows

### Interaction with Existing Roles
- **Developers**: Partners on testability, reproduces defects, and aligns on test coverage expectations.
- **Product Managers**: Works from acceptance criteria and feature specs; flags gaps that could affect release readiness.
- **Project Managers**: Provides quality status updates, flags risks to timelines when critical defects are unresolved.

---

## Engineering Manager / Engineering Lead

### Role Summary
Engineering Managers and Engineering Leads provide technical leadership, staffing guidance, and delivery oversight. They balance execution commitments with long-term technical health and unblock the team when escalation is needed.

### Responsibilities
- Provide staffing guidance and resource allocation input
- Unblock delivery execution by resolving escalations or removing obstacles
- Balance technical debt reduction with delivery commitments
- Support architectural and implementation decisions
- Ensure team capacity and skill alignment with project needs

### Goals
- Sustain delivery velocity while maintaining technical quality
- Grow team capability and reduce single points of failure
- Align engineering execution with product and project goals

### Typical Communication
- Regular 1:1s and team standups
- Escalation and decision-making forums with Project and Product Managers
- Technical direction and architecture review sessions

### Interaction with Existing Roles
- **Developers**: Supports through prioritization, removes blockers, and provides guidance on complex technical decisions.
- **Product Managers**: Aligns on scope trade-offs and communicates constraints affecting delivery timelines.
- **Project Managers**: Collaborates on resource planning, timeline feasibility, and staffing dependencies.

---

## Designer / UX Researcher

### Role Summary
Designers and UX Researchers define user flows, validate usability assumptions, and create design artifacts that guide implementation. They surface experience risks and ensure solutions meet user needs before and during development.

### Responsibilities
- Define user flows, wireframes, and interaction patterns
- Conduct user research and usability validation
- Prepare design artifacts and handoff specifications for Developers
- Identify experience risks and assumptions early in the process
- Collaborate on problem framing and solution discovery

### Goals
- Ensure that features are usable, accessible, and aligned with user needs
- Reduce rework caused by late-stage experience changes
- Make design intent explicit and actionable for engineering

### Typical Communication
- Design reviews and prototype walkthroughs with the delivery team
- Research findings and usability feedback shared with Product Managers
- Design handoff documentation and annotations for Developers

### Interaction with Existing Roles
- **Product Managers**: Collaborates on problem framing, research synthesis, and prioritization of experience improvements.
- **Developers**: Provides implementation guidance through design specs, prototypes, and handoff reviews.
- **Project Managers**: Helps identify design dependencies and flags when design work could impact delivery schedules.

---

## Release Manager / Delivery Coordinator

### Role Summary
Release Managers and Delivery Coordinators oversee release readiness, verify deployment prerequisites, track launch checklists, and ensure cross-team communication during rollouts. They are the coordination hub for go-live activities.

### Responsibilities
- Coordinate release readiness across engineering, QA, and operations
- Verify that deployment prerequisites and rollback plans are in place
- Track and close items on launch checklists before each release
- Communicate release status, timelines, and go/no-go decisions to stakeholders
- Manage release calendars and coordinate deployment windows

### Goals
- Ensure each release is well-coordinated, low-risk, and clearly communicated
- Minimize release-day surprises through thorough pre-release validation
- Maintain visibility into release health for all stakeholders

### Typical Communication
- Launch readiness checklists and go/no-go summaries
- Release notes and deployment status updates
- Cross-team coordination emails and Slack threads during rollout windows

### Interaction with Existing Roles
- **Project Managers**: Aligns on milestone dates, coordinates cross-team dependencies, and escalates readiness blockers.
- **Developers and QA**: Verifies release readiness criteria are met and confirms rollback procedures are documented.
- **Stakeholders**: Provides launch communication, release notes, and post-release status summaries.

---

## Support / Customer Success Representative

### Role Summary
Support and Customer Success Representatives bring the voice of the customer into planning, prepare support readiness materials, monitor post-release issues, and feed back adoption and incident trends to the delivery team.

### Responsibilities
- Surface customer pain points, feature requests, and adoption friction to the delivery team
- Prepare support readiness materials, FAQs, and runbooks before releases
- Monitor post-release incidents and customer-reported issues
- Communicate adoption trends and recurring issues back to Product and Engineering
- Coordinate on customer-facing communication during major changes or incidents

### Goals
- Ensure customers can successfully adopt new features with minimal friction
- Reduce escalation volume through proactive support readiness
- Close the feedback loop between customer experience and product planning

### Typical Communication
- Pre-release support readiness briefs and FAQ documentation
- Post-release issue reports and adoption metrics shared with Product Managers
- Incident coordination communications during service disruptions

### Interaction with Existing Roles
- **Product Managers**: Informs prioritization with customer impact data, recurring issues, and feature adoption feedback.
- **Project Managers**: Coordinates on customer-facing communications tied to release timelines.
- **Developers**: Shares production feedback, reproduction steps for bugs, and customer-reported edge cases.

---

## Security / Compliance Reviewer

### Role Summary
Security and Compliance Reviewers assess security-sensitive changes, advise on regulatory or policy requirements, and identify control gaps or risks that could affect release readiness or organizational compliance.

### Responsibilities
- Review security-sensitive changes during development and pre-release
- Advise teams on compliance requirements and applicable controls
- Identify control gaps, vulnerabilities, and gating risks
- Maintain security review checklists and compliance documentation
- Coordinate remediation of findings with Developers and Engineering Leads

### Goals
- Prevent security vulnerabilities and compliance violations from reaching production
- Embed security review into delivery processes without creating unnecessary friction
- Ensure that compliance requirements are understood and met consistently

### Typical Communication
- Security review findings and remediation guidance shared with engineering teams
- Compliance status updates included in release readiness reviews
- Risk registers updated with security or compliance findings

### Interaction with Existing Roles
- **Developers and Engineering Leads**: Partners on remediation, advises on secure implementation patterns, and validates fixes.
- **Project Managers**: Flags gating risks and communicates when security or compliance issues could affect release timelines.
- **Product Managers**: Advises when compliance constraints affect scope, timelines, or prioritization decisions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

