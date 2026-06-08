# OctoAcme Project Management Docs

Welcome! This README provides a summary of how we manage projects at OctoAcme and links to all detailed process documentation.

## Overview of Project Management Processes

OctoAcme projects follow an iterative, customer-focused, risk-aware approach designed to deliver value consistently and safely.

### Core Principles
- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments to gather feedback and reduce risk
- **Clear ownership**: Each project has named roles and accountabilities
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Key Lifecycle Stages

1. **Initiation**: Define the problem statement, success metrics, identify stakeholders, and validate business need
2. **Planning**: Break work into shippable increments, estimate scope, define milestones, and identify dependencies and risks
3. **Execution**: Build, test, and review with regular standups, demos, and test-driven quality practices
4. **Release**: Deploy to production with emphasis on safety, verification, and observability
5. **Continuous Improvement**: Capture learnings through retrospectives and feed improvements back into processes

### Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic direction

### Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items
- Release notes and deployment runbooks

## Process Documents

Navigate to the detailed guides below to understand specific aspects of OctoAcme's project management approach:

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Concise introduction to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate business need, align stakeholders, and authorize work |
| [Project Planning](octoacme-project-planning.md) | Break work into shippable increments and create an actionable plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day execution and track progress toward milestones |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize release processes to reduce risk and improve observability |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [Roles & Personas](octoacme-roles-and-personas.md) | Define responsibilities and communication patterns for key project roles |

## Communication Cadence

OctoAcme maintains a structured communication rhythm to ensure alignment and transparency:

- **Daily standups**: 15-minute team sync focused on progress, blockers, and dependencies
- **Weekly PM sync**: Product Manager and Project Manager alignment on priorities and risks
- **Twice-weekly delivery standups**: Team-level status updates (or as agreed)
- **Weekly stakeholder updates**: High-level progress, risks, and decisions needed
- **Monthly stakeholder briefing**: Strategic updates and upcoming milestones
- **Sprint demos/reviews**: Regular demonstrations of completed work
- **Retrospectives**: Post-sprint or post-milestone learning sessions
- **Ad-hoc escalations**: Immediate communication for critical blockers or incidents

## Quick Start for New Team Members

1. **Start here**: Read the [Project Management Overview](octoacme-project-management-overview.md) for a 5-minute introduction
2. **Understand your role**: Review [Roles & Personas](octoacme-roles-and-personas.md) to see responsibilities for your position
3. **Dive deeper**: Use the table above to find process documentation relevant to your current phase (initiation, planning, execution, etc.)
4. **Stay current**: Reference the relevant guides during project execution and check them during retrospectives for continuous improvement

## Key Workflows

### Starting a New Project
1. Complete the Project One-pager template from the [Initiation Guide](octoacme-project-initiation.md)
2. Conduct stakeholder alignment meeting
3. Get sponsor approval to move into planning
4. Create project board and repository skeleton

### Day-to-Day Execution
1. Use project board with columns: Backlog, Ready, In Progress, In Review, QA, Done
2. Keep PRs small (≤400 lines when possible) with issue links and acceptance criteria
3. Run CI tests and linting before requesting review
4. Require at least one approval before merging
5. Track blockers and escalate in daily standups

### Managing Risks
1. Maintain a Risk Register with ID, description, impact, probability, owner, and mitigation
2. Review and update risks weekly during PM sync
3. Escalate high-impact risks immediately: Team → PM → Product Lead → Sponsor
4. For security incidents, follow security incident runbook and notify on-call

### Releasing Features
1. Ensure all acceptance criteria are met and PRs are merged
2. Verify passing CI and security scans
3. Deploy to staging and run smoke tests
4. Deploy to production using automated pipeline
5. Run post-deploy verifications
6. Announce release and capture feedback

## Templates & Checklists

Each process document includes checklists and templates to support consistent execution:

- **Initiation Checklist**: One-pager, stakeholder alignment, decision gate
- **Planning Checklist**: Kickoff, backlog, estimates, Definition of Done, test plan
- **Execution Checklist**: Branching conventions, CI configuration, demos, risk register updates
- **Deployment Checklist**: Pre-release requirements, backup/snapshot, staging verification, production deployment
- **Retrospective Template**: What went well, improvements, action items with owners and due dates

## Getting Help

- **Process questions**: Refer to the relevant document above or reach out to your Project Manager
- **Process improvements**: Create an issue using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
- **Escalations**: Follow the escalation path defined in [Risk Management & Communication](octoacme-risks-and-communication.md)

## Contributing to Process Docs

OctoAcme's processes are living documents. If you identify gaps, improvements, or better practices:

1. Create an issue using the "Add Content to Project Management Process Docs" template
2. Describe what's needed, why, and suggested content
3. Get team feedback and validation
4. Submit a pull request with the update
5. Have it reviewed and merged by the Project Lead

---

**Last updated**: June 2026
**Maintained by**: OctoAcme Project Management Team
