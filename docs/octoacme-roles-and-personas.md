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

## Release Manager

### Role Summary
Release Managers own the scheduling, coordination, and communication of software releases. They act as the bridge between engineering, product, and operations to ensure predictable and low-risk deployments.

### Responsibilities
- Maintain the release calendar and communicate schedules to all stakeholders
- Coordinate cutover and rollback plans with developers and operations
- Ensure release criteria are met before deployment (test sign-off, documentation, comms)
- Facilitate post-release reviews and capture lessons learned

### Goals
- Deliver releases on schedule with minimal disruption
- Maintain a clear audit trail of deployment decisions and approvals
- Reduce release-related incidents through proactive coordination

### Typical Communication
- Release readiness reviews and go/no-go calls
- Stakeholder announcements and release notes
- Coordination with Support/SRE Lead on cutover and monitoring

### Interaction Points
- **Developers**: Aligns on code freeze, merge readiness, and rollback procedures
- **Product Managers**: Confirms scope and acceptance criteria are met before release
- **Project Managers**: Coordinates release milestones and timeline impacts
- **Support/SRE Lead**: Shares deployment plans, monitoring thresholds, and incident escalation contacts

---

## Technical Writer

### Role Summary
Technical Writers ensure that users and internal teams have high-quality, accurate, and discoverable documentation. They partner with developers and product managers to translate complex features into clear content.

### Responsibilities
- Create and maintain user-facing docs, API references, and internal runbooks
- Review and edit feature specs and release notes for clarity
- Establish and enforce documentation standards and templates
- Identify documentation gaps during planning and delivery

### Goals
- Reduce support burden through self-service documentation
- Ensure docs are kept current with each release
- Improve onboarding speed for new team members and users

### Typical Communication
- Sync with developers and PMs during sprint reviews and release prep
- Pull request reviews for docs-impacting changes
- Documentation status updates in planning and retrospectives

### Interaction Points
- **Developers**: Reviews technical accuracy of documentation; embedded in PR review process for doc changes
- **Product Managers**: Translates product decisions and roadmap items into user-facing content
- **Project Managers**: Flags documentation as a delivery dependency; tracks doc tasks on the project board
- **Release Manager**: Ensures release notes and changelogs are complete before go/no-go

---

## Onboarding/Training Lead

### Role Summary
The Onboarding/Training Lead designs and delivers programs that ramp up new hires and enable cross-team adoption of products and processes. They partner with managers to reduce friction during transitions and handoffs.

### Responsibilities
- Develop onboarding plans and training materials for new team members
- Coordinate cross-team enablement sessions for new tools, processes, or features
- Gather feedback from new joiners and trainees to continuously improve programs
- Maintain a library of training resources and onboarding guides

### Goals
- Reduce time-to-productivity for new hires
- Ensure consistent understanding of processes across teams
- Build a culture of continuous learning and knowledge sharing

### Typical Communication
- Onboarding sessions and training workshops
- Check-ins with new joiners during their first 30/60/90 days
- Collaboration with Project/People Managers on capacity and ramp plans

### Interaction Points
- **Developers**: Provides technical onboarding and codebase orientation
- **Product Managers**: Shares product context and roadmap direction during onboarding
- **Project Managers**: Aligns on team capacity, new-hire timelines, and handoff schedules
- **Technical Writer**: Coordinates on keeping onboarding docs and guides up to date

---

## Support/SRE Lead

### Role Summary
The Support/SRE Lead represents the operational and customer support perspective in planning, delivery, and retrospectives. They bridge product, engineering, and support to ensure smooth launches and effective incident management.

### Responsibilities
- Represent support and operations in planning ceremonies and design reviews
- Define and monitor SLOs, alerting, and on-call rotations
- Lead incident response coordination and post-mortems
- Provide feedback from support escalations to improve product quality

### Goals
- Minimize production incidents and customer impact from releases
- Maintain healthy on-call burden and fast mean-time-to-recovery
- Feed operational insights back into product and engineering priorities

### Typical Communication
- Incident response channels and post-mortem reports
- Participation in release readiness reviews and retrospectives
- Escalation updates to stakeholders during and after incidents

### Interaction Points
- **Developers**: Collaborates on runbooks, observability, and incident response procedures
- **Product Managers**: Surfaces recurring support issues to inform backlog prioritization
- **Project Managers**: Flags operational risks and dependencies during project tracking
- **Release Manager**: Reviews deployment plans, monitoring setups, and rollback procedures before go/no-go

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

