# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This directory contains comprehensive guidance on how OctoAcme runs projects, from initiation through retrospectives. Use this README as your entry point to understand our approach, navigate the docs, and find guidance for your role.

## OctoAcme Project Management Approach

OctoAcme follows a customer-first, iterative project management methodology grounded in these core principles:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver work in small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, experimentation, and learning

## Project Lifecycle Overview

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation**: Validate business need, align stakeholders, create initial plan
2. **Planning**: Break work into shippable increments, identify risks and dependencies
3. **Execution**: Build, test, review, and iterate toward milestones
4. **Release**: Deploy to production, verify, and announce
5. **Retrospective**: Capture learnings and drive continuous improvement

## Documentation Index

### Core References
- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction, core roles, key artifacts, and communication cadence
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of Developers, Product Managers, and Project Managers

### Lifecycle Phase Guides
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — How to validate, authorize, and kick off new work
- **[Project Planning](./octoacme-project-planning.md)** — How to turn initiatives into actionable plans and backlogs
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, and progress tracking
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized release process and deployment checklist
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — How to capture learnings and drive improvements

### Cross-cutting Concerns
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk identification, escalation paths, and stakeholder communication templates

## Workflows & Execution

OctoAcme maintains consistent workflows across all projects:

- **Team Rhythm**: Daily standups (15 min), weekly delivery syncs, and sprint/milestone reviews
- **Pull Request Workflow**: Small PRs (≤ 400 lines), with issue links and acceptance criteria; automated CI checks required before review; minimum one approval before merge
- **Quality Gates**: Unit and integration tests, security scanning, manual QA for acceptance, smoke tests before release
- **Project Boards**: GitHub Projects with standard columns (Backlog, Ready, In Progress, In Review, QA, Done)

## Roles & Responsibilities

| Role | Focus | Key Responsibilities |
|------|-------|----------------------|
| **Project Manager** | Coordination & delivery | Schedule, risks, communications, stakeholder alignment |
| **Product Manager** | Vision & prioritization | Success metrics, roadmap, acceptance criteria |
| **Developers** | Implementation | Build features, testing, quality, technical risk identification |
| **QA/Testing** | Quality assurance | Validate acceptance criteria, smoke tests |

See [Roles & Personas](./octoacme-roles-and-personas.md) for detailed role descriptions.

## Communication & Escalation

- **Weekly Sync**: PM + Product Manager alignment on delivery and risks
- **Standups**: Twice-weekly delivery team meetings (or as agreed)
- **Monthly Updates**: Stakeholder briefings on progress and milestones
- **Escalation Path**: Team-level triage → PM → Product Lead → Sponsor
- **Status Template**: Use weekly status updates covering progress, next steps, risks & blockers, and decisions needed

For incident communication and security escalations, refer to [Risk Management & Communication](./octoacme-risks-and-communication.md).

## Acceptance Criteria & Definition of Done

Every backlog item must include:
- Clear acceptance criteria tied to user value
- Definition of Done (DoD) covering code quality, testing, documentation, and review
- Estimate using consistent sizing (T-shirt or story points)
- Clear owner and related documentation links

See [Project Planning](./octoacme-project-planning.md) for detailed planning guidance.

## How to Use These Docs

- **For new team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md) and [Roles & Personas](./octoacme-roles-and-personas.md) to understand OctoAcme's approach and your role
- **For project kickoff**: Use the [Project Initiation Guide](./octoacme-project-initiation.md) to create your Project One-pager and validate stakeholder alignment
- **For day-to-day delivery**: Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) for team rhythm, workflow, and blocker escalation
- **For planning sprints or releases**: See [Project Planning](./octoacme-project-planning.md) for backlog definition and [Release & Deployment](./octoacme-release-and-deployment.md) for deployment checklists
- **For managing risks**: Consult [Risk Management & Communication](./octoacme-risks-and-communication.md) for risk registers, escalation, and stakeholder communication templates
- **For continuous improvement**: Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive action items
- **In Copilot Spaces**: Add process-specific docs to `.copilot/` for context-aware guidance tailored to your project

## Contributing to This Documentation

To update or add content to OctoAcme's process docs:

1. Use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
2. Describe the new content, why it's needed, and provide suggested text
3. Ensure updates align with existing documentation and core principles
4. Have proposed content reviewed with stakeholders if it affects workflows or roles

### Acceptance Criteria for Doc Updates

- Content aligns with existing process docs and OctoAcme principles
- Update improves clarity, closes a documented gap, or incorporates team feedback
- Proposed content has been reviewed with relevant stakeholders (if applicable)

---

**Closes #2**
