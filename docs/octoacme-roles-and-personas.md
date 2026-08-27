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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy and acceptance validation. They ensure that features meet acceptance criteria, perform end-to-end testing, and manage the quality gates for releases.

### Responsibilities
- Define and maintain test strategy and test plans
- Create and execute acceptance criteria validation
- Coordinate manual and automated testing efforts
- Identify and triage quality-related blockers
- Participate in release readiness assessment
- Report quality metrics and trends

### Goals
- Catch defects early in the development cycle
- Ensure features meet acceptance criteria before release
- Build confidence in release quality through comprehensive testing
- Reduce production incidents through thorough validation

### Typical Communication
- Sprint planning and definition of done reviews
- Acceptance criteria discussions with Product Managers and Developers
- Quality reports in weekly syncs
- Pre-release readiness assessments

### Interaction with Existing Roles
- **With Developers**: Collaborate on test strategy and accept completed work that meets acceptance criteria
- **With Product Managers**: Validate that user stories meet acceptance criteria and business requirements
- **With Project Managers**: Provide quality metrics and highlight quality-related risks to the plan
- **With Tech Leads**: Review test architecture and technical approach to testing

---

## Tech Lead / Architect

### Role Summary
Tech Leads provide technical direction, design guidance, and identify technical risks. They ensure solutions are scalable, maintainable, and aligned with system architecture.

### Responsibilities
- Review technical designs and architectural decisions
- Identify technical risks and propose mitigations
- Guide developers on implementation approaches
- Conduct architecture and design reviews
- Contribute to system scalability and maintainability
- Mentor developers on technical best practices

### Goals
- Ensure solutions follow established technical standards
- Reduce technical debt and rework
- Build scalable, maintainable systems
- Accelerate team velocity through design guidance

### Typical Communication
- Design review sessions with development team
- Technical risk assessments in planning and weekly syncs
- Code review guidance and architectural decisions
- Mentoring and pairing with developers

### Interaction with Existing Roles
- **With Developers**: Provide design direction and review code to ensure architectural alignment
- **With Project Managers**: Identify and communicate technical risks and dependencies that affect the timeline
- **With Product Managers**: Discuss technical trade-offs and feasibility of product requirements
- **With QA/Testing Lead**: Review test architecture and coordinate testing strategy for complex technical changes

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove blockers, and drive continuous process improvement. They coach teams on agile practices and help maintain a healthy, productive delivery cadence.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove organizational and process blockers
- Coach team members on agile practices and principles
- Track team metrics (velocity, burndown, cycle time)
- Drive continuous improvement from retrospectives
- Protect the team from external distractions and scope creep

### Goals
- Enable predictable, consistent delivery
- Build team cohesion and psychological safety
- Continuously improve team processes and velocity
- Create transparency around progress and impediments

### Typical Communication
- Daily standup facilitation and blocker resolution
- Retrospective meetings and action item tracking
- Metrics reviews and team coaching
- Process improvement discussions with leadership

### Interaction with Existing Roles
- **With Project Managers**: Work together on timeline and risk management, with PM owning stakeholder communication and Scrum Master owning team process
- **With Developers**: Remove blockers and facilitate smooth workflow
- **With Product Managers**: Help maintain backlog clarity and prioritization discipline
- **With All Roles**: Foster psychological safety and encourage continuous learning

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide strategic authority, funding, and business-level oversight. They resolve high-level conflicts, approve major changes, and maintain stakeholder alignment to ensure projects deliver business value.

### Responsibilities
- Approve project charter and key strategic decisions
- Provide funding and resource authorization
- Resolve Level 3 escalations and conflicts
- Ensure business alignment with strategic goals
- Sponsor stakeholder communication and engagement
- Review release readiness from business perspective
- Remove high-level organizational blockers

### Goals
- Ensure project delivers business value
- Minimize risk to organizational goals
- Maintain stakeholder confidence and engagement
- Enable efficient decision-making through clear authority

### Typical Communication
- Monthly stakeholder reviews and status updates
- Escalation reviews for high-impact decisions
- Release announcements and milestone celebrations
- Risk and dependency reviews when needed

### Interaction with Existing Roles
- **With Project Managers**: Provide strategic direction and resolve escalations that PM cannot resolve at team level
- **With Product Managers**: Align on business goals and competitive priorities
- **With All Roles**: Communicate vision and strategic context to keep teams motivated and aligned

---

## Customer / User Representative

### Role Summary
Customer/User Representatives advocate for end-user needs and ensure solutions are built with user value and usability in mind. They validate solutions through direct user feedback and help the team stay customer-focused.

### Responsibilities
- Participate in user research and discovery activities
- Provide customer perspective during planning and design discussions
- Validate features and usability with real users
- Communicate user feedback and pain points to the team
- Help define success criteria from a user perspective
- Advocate for user experience and accessibility

### Goals
- Ensure solutions address real user needs and pain points
- Build products with high usability and adoption
- Reduce post-release rework due to user experience issues
- Maintain customer empathy across the team

### Typical Communication
- User research sessions and feedback synthesis
- Design review participation with user perspective
- Acceptance criteria discussions focused on user value
- User feedback sharing in sprint reviews and retrospectives

### Interaction with Existing Roles
- **With Product Managers**: Provide customer insights to inform prioritization and acceptance criteria
- **With Developers**: Help clarify user intent behind requirements
- **With QA/Testing Leads**: Participate in user acceptance testing and validation
- **With Tech Leads**: Advocate for user experience and usability considerations in technical decisions

---

## Release Manager

### Role Summary
Release Managers coordinate deployments, manage release documentation, and oversee production rollouts. They ensure releases are well-planned, communicated, and executed with minimal risk.

### Responsibilities
- Create and maintain release plans and schedules
- Coordinate release activities across teams
- Prepare and review release notes and documentation
- Communicate release information to stakeholders and support teams
- Coordinate pre-release testing and smoke test execution
- Monitor release deployments and coordinate rollback if needed
- Maintain release calendars and deployment windows

### Goals
- Execute releases with zero unplanned downtime
- Ensure clear stakeholder and customer communication
- Reduce release-related incidents and rework
- Build team confidence in deployment processes

### Typical Communication
- Release planning meetings with cross-functional teams
- Release notes and deployment documentation
- Stakeholder communications about release timing and content
- Post-release verification and incident management

### Interaction with Existing Roles
- **With Project Managers**: Coordinate release scheduling and stakeholder communication
- **With Developers**: Validate release readiness and coordinate deployment activities
- **With QA/Testing Leads**: Coordinate pre-release testing and smoke test execution
- **With Product Managers**: Ensure release communications align with product strategy
- **With Sponsors**: Provide release status updates and manage production incidents

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
