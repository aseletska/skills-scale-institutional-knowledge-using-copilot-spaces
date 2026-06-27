# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Decision Authority
- Technical implementation approach (within approved architecture)
- Code quality and test coverage standards
- Technical debt trade-offs (escalate to Technical Lead if significant)

#### Typical Handoffs
- Works with: Product Manager (acceptance criteria), Technical Lead (design review), QA/Test Lead (test planning), DevOps/SRE (deployment requirements)
- Deliverables: Feature code, tests, code review approvals, technical design docs

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Sign off on acceptance criteria and feature completion

#### Decision Authority
- Feature prioritization and roadmap direction
- Acceptance criteria and definition of done
- Trade-offs between scope, schedule, and quality (escalate to Product Lead for strategic conflicts)

#### Typical Handoffs
- Works with: Project Manager (planning and scheduling), Developers (requirements and acceptance criteria), Business Analyst (requirement clarity), Stakeholders (alignment and feedback)
- Deliverables: Prioritized backlog, acceptance criteria, success metrics, release notes

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Track progress and escalate blockers

#### Decision Authority
- Sprint/iteration planning and capacity allocation
- Risk mitigation strategies (escalate to Sponsor for strategic risks)
- Meeting facilitation and decision documentation

#### Typical Handoffs
- Works with: Product Manager (prioritization), Developers (capacity and blocking issues), Technical Lead (technical risks), Release Manager (deployment coordination), Stakeholders (status updates)
- Deliverables: Project plan, risk register, status reports, meeting notes, escalation summaries

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Additional Personas and Roles

### Project Sponsor

#### Role Summary
Senior leader who owns the business outcome, secures funding, and champions the project. Approves major decisions, resolves escalations, and supports execution by clearing organizational roadblocks and aligning the project to strategic priorities.

#### Responsibilities
- Champion the project and secure executive alignment and resources
- Approve major scope changes and risk mitigations
- Escalate and resolve organizational blockers
- Review milestone achievements and provide strategic guidance
- Communicate project outcomes to leadership

#### Decision Authority
- Strategic direction and scope changes
- Major resource re-allocation
- Escalation resolution and trade-off decisions at executive level
- Go/no-go decisions at key gates

#### Typical Handoffs
- Works with: Project Manager (escalations and status), Product Manager (strategic alignment), Stakeholders (executive communication)
- Deliverables: Approval of project charter, milestone reviews, escalation decisions

#### Success Metrics
- Project delivers defined business outcomes
- Stakeholder and executive alignment maintained
- Organizational obstacles cleared on time

---

### Product Owner

#### Role Summary
Defines the product vision and prioritizes the backlog. Responsible for acceptance criteria, stakeholder alignment on scope, and signing off on deliverables. Supports execution by ensuring the team builds the highest-value work.

#### Responsibilities
- Own the product vision and roadmap
- Prioritize and groom the backlog with clear acceptance criteria
- Align stakeholders on scope and trade-offs
- Sign off on feature completion and quality gates
- Incorporate user feedback and market insights

#### Decision Authority
- Product direction and feature prioritization
- Acceptance criteria sign-off
- Backlog grooming and refinement
- Trade-offs between features and quality (escalate conflicts to Sponsor)

#### Typical Handoffs
- Works with: Developers (feature specs), QA/Test Lead (acceptance validation), UX/Design Lead (user experience), Business Analyst (requirement clarity), Stakeholders (scope alignment)
- Deliverables: Feature specs, prioritized backlog, acceptance criteria, sign-off on completed work

#### Success Metrics
- Features meet user needs and success metrics
- Backlog is well-prioritized and minimal rework
- Stakeholder satisfaction with product direction

---

### Technical Lead / Architect

#### Role Summary
Sets the technical direction, reviews designs, and owns technical quality. Coordinates cross-team technical decisions and integrations to ensure feasible implementation.

#### Responsibilities
- Define technical architecture and technology choices
- Review technical designs for feasibility and quality
- Own technical quality standards and code review process
- Coordinate cross-team technical integrations and dependencies
- Identify and mitigate technical risks
- Mentor developers and promote best practices

#### Decision Authority
- Technical architecture and design approach
- Technology selection and tool choices
- Code quality standards and refactoring priorities
- Technical risk assessment and mitigation

#### Typical Handoffs
- Works with: Developers (design review and guidance), DevOps/SRE (infrastructure requirements), Security & Compliance Owner (security architecture), Data Lead (data architecture)
- Deliverables: Technical design docs, architecture diagrams, code review feedback, risk assessments

#### Success Metrics
- Technical solutions are scalable, maintainable, and secure
- Team follows consistent architectural patterns
- Technical risks are identified and mitigated early

---

### Delivery Manager

#### Role Summary
Focuses on day-to-day delivery: sprint planning, tracking progress, removing impediments, and maintaining team cadence. Ensures commitments are realistic and delivery risks are visible.

#### Responsibilities
- Facilitate sprint/iteration planning and retrospectives
- Track daily progress and identify blockers
- Remove impediments and escalate risks promptly
- Maintain team velocity and commit reliability
- Coordinate dependencies with other teams
- Coach team on process improvements and agile practices

#### Decision Authority
- Sprint scope and capacity allocation
- Backlog order within sprints (subject to Product Manager priority)
- Process improvements and team retrospectives
- Escalation of delivery risks

#### Typical Handoffs
- Works with: Product Manager (backlog order and priorities), Developers (impediment removal), Project Manager (cross-team coordination), QA/Test Lead (test planning)
- Deliverables: Sprint plans, daily progress tracking, retrospective notes, impediment logs

#### Success Metrics
- Sprint commitments are met consistently
- Team velocity is stable and predictable
- Blockers are resolved quickly

---

### Release Manager

#### Role Summary
Plans and coordinates releases, manages release checklists, rollback plans, and deployment windows. Ensures releases meet operational requirements and compliance checks.

#### Responsibilities
- Plan release schedule and coordinate deployment windows
- Maintain release checklists and validation procedures
- Coordinate pre-release testing and approval gates
- Document rollback procedures and incident response plans
- Track and communicate release status to stakeholders
- Manage release notes and deployment documentation

#### Decision Authority
- Release timing and deployment window selection
- Release readiness sign-off
- Rollback decisions in case of critical issues
- Release communication and announcement timing

#### Typical Handoffs
- Works with: Product Manager (release timing and notes), Developers (deployment readiness), QA/Test Lead (release validation), DevOps/SRE (deployment execution), Project Manager (stakeholder communication)
- Deliverables: Release plan, deployment checklist, release notes, rollback plan, post-deployment verification

#### Success Metrics
- Releases deploy on schedule with no critical issues
- Rollback procedures are clear and effective
- Stakeholder communication is timely and clear

---

### Business Analyst

#### Role Summary
Elicits and clarifies business requirements, creates user stories and acceptance criteria, and facilitates stakeholder workshops. Helps execution by reducing rework and clarifying scope.

#### Responsibilities
- Conduct stakeholder interviews and workshops to gather requirements
- Translate business needs into clear, testable user stories
- Define acceptance criteria that reflect business intent
- Identify scope ambiguities and resolve them early
- Validate that delivered features meet original business needs
- Document business rules and processes

#### Decision Authority
- Requirement clarity and acceptance criteria definition (subject to Product Manager approval)
- Scope clarification and trade-off recommendations
- Stakeholder coordination on requirement changes

#### Typical Handoffs
- Works with: Product Manager (requirement prioritization), Developers (user story refinement), QA/Test Lead (test case development), Stakeholders (requirement validation)
- Deliverables: User stories, acceptance criteria, business requirement docs, clarification summaries

#### Success Metrics
- Requirements are clear and reduce rework
- Scope creep is minimized through early clarification
- Stakeholder satisfaction with delivery

---

### QA / Test Lead

#### Role Summary
Defines test strategy, coordinates test execution, and owns quality gates. Works with the team to automate or systematize testing to reduce production issues.

#### Responsibilities
- Define test strategy and acceptance test approach
- Coordinate test planning and test case development
- Own quality gates and acceptance criteria validation
- Identify and report defects with clear reproduction steps
- Drive test automation and improve testing efficiency
- Coordinate post-release validation and smoke tests

#### Decision Authority
- Test strategy and approach (e.g., manual vs. automated)
- Quality standards and acceptance test requirements
- Release readiness from quality perspective
- Defect severity and blocking vs. non-blocking classification

#### Typical Handoffs
- Works with: Product Manager (acceptance criteria), Developers (test planning and bug reproduction), Business Analyst (test case development), Release Manager (release validation)
- Deliverables: Test plans, test cases, defect reports, quality metrics, acceptance test results

#### Success Metrics
- Defects are caught before production
- Test coverage is comprehensive and automated
- Quality gates are clear and consistently applied

---

### DevOps / SRE Engineer

#### Role Summary
Owns CI/CD pipelines, environments, and operational readiness. Ensures deployments are repeatable and monitors production health to support stable operations.

#### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Provision and manage environments (dev, staging, production)
- Ensure deployment processes are repeatable and documented
- Monitor production health and performance
- Respond to incidents and coordinate incident response
- Optimize infrastructure and deployment efficiency

#### Decision Authority
- CI/CD tooling and pipeline design
- Infrastructure and environment configuration
- Deployment process and approval workflow
- Incident response and rollback decisions (coordinate with Release Manager)

#### Typical Handoffs
- Works with: Developers (deployment requirements and testing), Release Manager (deployment execution), Technical Lead (infrastructure architecture)
- Deliverables: CI/CD pipelines, deployment procedures, monitoring dashboards, incident postmortems

#### Success Metrics
- Deployments are reliable and repeatable
- Production systems are stable and performant
- Incident response time is minimized

---

### Security & Compliance Owner

#### Role Summary
Reviews designs for security and regulatory requirements, coordinates audits, and defines mitigation controls. Ensures the project meets organization security standards.

#### Responsibilities
- Review designs and requirements for security implications
- Coordinate security assessments and penetration testing
- Define security controls and mitigation strategies
- Ensure compliance with relevant regulations and policies
- Conduct security training and awareness
- Respond to security incidents and vulnerabilities

#### Decision Authority
- Security architecture and control requirements
- Security review and approval for releases
- Incident severity classification and response
- Policy and compliance exceptions (escalate to Sponsor if needed)

#### Typical Handoffs
- Works with: Technical Lead (security architecture), Developers (secure coding practices), DevOps/SRE (infrastructure security), Release Manager (security validation before release)
- Deliverables: Security review findings, compliance attestations, incident response, security policies

#### Success Metrics
- Security risks are identified and mitigated early
- Compliance requirements are met
- Security incidents are responded to promptly

---

### UX / Design Lead

#### Role Summary
Owns user research, design decisions, and accessibility considerations. Ensures the product meets user needs and usability standards.

#### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Ensure accessibility and inclusive design principles
- Review implementations for consistency with design
- Iterate designs based on user feedback
- Document design systems and patterns

#### Decision Authority
- Design direction and user experience approach
- Accessibility standards and compliance
- Design review and implementation validation
- User experience trade-offs (escalate conflicts to Product Manager)

#### Typical Handoffs
- Works with: Product Manager (user needs and priorities), Developers (design implementation), Business Analyst (user workflow clarification)
- Deliverables: User research insights, wireframes, design specs, accessibility checklist, design system documentation

#### Success Metrics
- Users find the product intuitive and easy to use
- Accessibility standards are met
- Design is consistent and follows established patterns

---

### Data Lead

#### Role Summary
Ensures data requirements, schema changes, and analytics tracking are defined and implemented; supports data quality and reporting needs.

#### Responsibilities
- Define data requirements and schema design
- Plan data migrations and schema changes
- Define analytics tracking and success metrics
- Ensure data quality and validation rules
- Coordinate data pipeline implementation
- Support reporting and analytics needs

#### Decision Authority
- Data architecture and schema design
- Analytics approach and metric definitions
- Data quality standards and validation rules
- Data privacy and retention policies

#### Typical Handoffs
- Works with: Technical Lead (data architecture), Developers (schema implementation), Product Manager (analytics requirements), DevOps/SRE (data pipeline infrastructure)
- Deliverables: Data schema docs, analytics specification, data quality reports, migration plans

#### Success Metrics
- Data is accurate, complete, and accessible for analytics
- Metrics align with business objectives
- Data pipelines are reliable and efficient

---

### Change Manager / Communications Lead

#### Role Summary
Coordinates stakeholder communications, rollout plans, and training materials to ensure adoption and minimize disruption.

#### Responsibilities
- Develop stakeholder communication and rollout plans
- Create training materials and documentation for end users
- Coordinate launch activities and announcements
- Gather feedback and address adoption concerns
- Plan change impact mitigation strategies
- Track adoption metrics and readiness

#### Decision Authority
- Communication timing and content
- Rollout approach and staging (subject to Release Manager approval)
- Training and support strategy
- Adoption metrics and success criteria

#### Typical Handoffs
- Works with: Product Manager (feature communications), Project Manager (stakeholder coordination), Release Manager (release announcement), Support teams (training and documentation)
- Deliverables: Communication plans, training materials, rollout schedules, adoption metrics

#### Success Metrics
- Stakeholders understand and adopt changes quickly
- Disruption is minimized
- User feedback is positive and adoption is high

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## RACI Matrix: Common Project Activities

This matrix clarifies decision authority and responsibilities for typical project activities.

| Activity | Project Sponsor | Product Manager | Project Manager | Technical Lead | Developers | QA/Test Lead | Release Manager | DevOps/SRE |
|----------|-----------------|-----------------|-----------------|----------------|------------|--------------|-----------------|------------|
| **Scope Definition** | A | R | C | C | I | I | I | I |
| **Acceptance Criteria** | I | R | C | C | C | C | I | I |
| **Technical Design Review** | I | I | A | R | R | C | I | C |
| **Release Readiness** | A | R | R | C | I | R | R | C |
| **Deployment Approval** | A | R | R | I | I | I | R | R |
| **Post-Incident Review** | I | C | R | C | R | C | C | R |

**Legend:**
- **R (Responsible)**: Directly performs the work
- **A (Accountable)**: Final approval authority; ensures completion
- **C (Consulted)**: Provides input and expertise
- **I (Informed)**: Kept in the loop but not directly involved

---

## Decision Authority Hierarchy

When conflicts or escalations arise, use this hierarchy to determine who has authority:

1. **Functional Owner** (role responsible for that area)
2. **Project Manager or Delivery Manager** (for process/delivery issues)
3. **Product Manager or Technical Lead** (for feature/technical trade-offs)
4. **Project Sponsor** (for strategic or scope conflicts)
5. **Executive Leadership** (for organizational or resource conflicts beyond sponsor authority)

---

## Communication Best Practices by Role

### For Project Manager
- Share status updates weekly; escalate risks promptly
- Use RACI matrix to clarify decisions and prevent bottlenecks

### For Product Manager
- Prioritize backlog clearly; provide rationale for trade-offs
- Communicate acceptance criteria in writing (not just in meetings)

### For Technical Lead
- Document architectural decisions and trade-offs
- Review designs early to catch technical risks

### For Developers
- Ask clarifying questions in sprint planning if acceptance criteria are ambiguous
- Raise technical risks early and propose mitigations

### For QA/Test Lead
- Define acceptance tests before development begins
- Report defects with clear steps to reproduce

### For Release Manager
- Plan releases with a minimum 2-week notice
- Communicate rollback procedures before deployment

---
