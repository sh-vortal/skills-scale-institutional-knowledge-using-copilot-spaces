# OctoAcme Project Management — README

This repository holds OctoAcme's project management process documents. This README links to each document in the docs/ folder and provides a short summary of the project management processes and how to use the docs.

## Quick links

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## Summary of OctoAcme project management processes

OctoAcme runs projects with a lightweight, iterative approach focused on delivering customer value and learning quickly. Our process is grounded in clear role ownership, data-informed decisions, and psychological safety across the team.

### Core Principles
- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments to gather feedback early
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead with defined responsibilities
- **Data-informed**: Measure impact and iterate based on evidence and metrics
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

### Project Lifecycle

**1. Initiation**
- Capture problem statement and business need
- Identify stakeholders and champions
- Define success metrics and high-level timeline
- Create a lightweight Project One-pager to validate and authorize work
- Decision gate: Move to planning only when success metrics are clear and stakeholders align

**2. Planning**
- Break work into shippable increments with prioritized backlog
- Define acceptance criteria and Definition of Done
- Estimate scope using T-shirt sizing or story points
- Identify dependencies, risks, and integration points
- Map milestones and release timeline
- Conduct project kickoff with stakeholders and delivery team

**3. Execution**
- Run short iterations or sprints with regular cadence
- Use project board workflow: Backlog → Ready → In Progress → In Review → QA → Done
- Follow PR conventions (small PRs ≤400 lines, clear descriptions, automated CI)
- Require at least one approval before merging
- Conduct daily standups (15 min focus on progress, blockers, dependencies)
- Run weekly delivery syncs and end-of-sprint demos
- Track velocity, burndown, and success metrics

**4. Release**
- Verify all acceptance criteria met and PRs merged
- Confirm passing CI and security scans
- Draft release notes and document rollback plans
- Prepare smoke tests for critical flows
- Deploy to staging and verify pre-release checklist
- Deploy to production (automated pipeline preferred)
- Run post-deploy verifications and announce to stakeholders
- Have incident playbook and rollback procedure ready

**5. Continuous Improvement**
- Run retrospectives after each sprint, release, or milestone
- Capture what went well, what could improve, and action items
- Track improvements in the project backlog with clear owners and timelines
- Review outstanding actions in weekly PM syncs
- Measure impact of improvements and iterate

### Supporting Practices

**Roles & Responsibilities**
- **Project Manager**: Coordinates delivery, manages schedules, risks, and communications; ensures consistent documentation
- **Product Manager**: Defines outcomes, prioritizes backlog, measures success, and validates solutions
- **Developers**: Implement features, write tests, collaborate on design, and identify technical risks
- **QA/Testing**: Validate quality and acceptance criteria; ensure Definition of Done is met
- **Stakeholders**: Provide inputs, approvals, and regular feedback on progress

**Risk Management**
- Maintain a Risk Register with ID, description, impact, likelihood, owner, and mitigation plan
- Identify risks during planning and ongoing execution
- Review and update status at weekly syncs
- Follow escalation path: Team-level → PM → Product Lead → Sponsor

**Communication & Transparency**
- Weekly status updates between PM and Product Lead
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates with progress, risks, and decisions
- Single source of truth for project status (project README or release doc)
- Ad-hoc escalations as needed using defined escalation paths

## How to use and update these docs

1. **Getting started**: Start with [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to our approach, roles, and key artifacts.

2. **Implementing a project**: Follow the documents in order:
   - [Project Initiation Guide](octoacme-project-initiation.md) — validate and authorize the work
   - [Project Planning](octoacme-project-planning.md) — create your actionable plan
   - [Execution & Tracking](octoacme-execution-and-tracking.md) — manage day-to-day delivery
   - [Risk Management & Communication](octoacme-risks-and-communication.md) — identify and communicate risks
   - [Release & Deployment](octoacme-release-and-deployment.md) — prepare and ship to production
   - [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — capture learnings

3. **Understanding roles**: See [Roles & Personas](octoacme-roles-and-personas.md) for detailed responsibilities and communication patterns for each role.

4. **Proposing updates**: To suggest changes or add a new process document, use the issue template at `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`. Select "new document" for new files or choose an existing document to update.

5. **Keeping docs in sync**: When documents change, update this README with new links and summaries. Use the Copilot Space context to ground team knowledge and gather feedback for continuous improvement.

## Project artifacts template locations

Key artifacts referenced throughout these docs:
- **Project Charter / One-pager**: Store in your project repo root or `docs/` folder
- **Risk Register**: Maintain in project board, GitHub Issues, or shared tracking doc
- **Sprint/Iteration Backlog**: Use GitHub Projects or Issues with clear acceptance criteria
- **Definition of Done**: Document in project README or wiki
- **Retrospective notes**: Store in `docs/` with date and action items linked to issues
- **Release notes**: Include in release tag or dedicated release doc

---

**Questions or feedback?** Open an issue using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
