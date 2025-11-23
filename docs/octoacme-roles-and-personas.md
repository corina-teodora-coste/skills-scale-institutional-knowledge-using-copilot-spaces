```markdown
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

## Additional Personas (proposed additions)

### DevOps / SRE

#### Role Summary
Manage production readiness, CI/CD, deployments, and system reliability.

#### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Operate monitoring, alerting, and runbooks
- Ensure infrastructure-as-code and environment parity
- Participate in incident response and post-incident reviews
- Optimize operational cost and performance

#### Goals
- Keep services reliable and observable
- Reduce mean time to recovery (MTTR)
- Automate repeatable operational tasks

#### Typical Communication / Interactions
- Works with Developers to onboard services and pipelines
- Coordinates with Project Manager/Release Manager for deployment windows
- Collaborates with QA on staging verification
- Escalates production incidents to PM and Product Lead

---

### Security Engineer

#### Role Summary
Ensure secure design and operations across the project lifecycle.

#### Responsibilities
- Conduct threat modeling and security reviews
- Implement and maintain automated security scans in CI
- Triage and advise on vulnerabilities
- Define security acceptance criteria for features
- Provide guidance on authentication, authorization, and data protection

#### Goals
- Reduce security risk and exposure
- Ensure secure-by-default design decisions

#### Typical Communication / Interactions
- Reviews designs with Developers and Product Manager
- Works with DevOps to integrate security gates into CI/CD
- Notifies PM and stakeholders of security risks and mitigation plans

---

### UX Researcher / Product Designer

#### Role Summary
Validate product decisions through research and design; ensure usability and accessibility.

#### Responsibilities
- Conduct user research and usability testing
- Create journey maps, wireframes, and prototypes
- Define UX acceptance criteria
- Provide design specs and accessibility guidance

#### Goals
- Improve usability and user satisfaction
- Ensure designs meet accessibility and business goals

#### Typical Communication / Interactions
- Partners with Product Manager on user needs and success metrics
- Hands off designs to Developers and collaborates on feasibility
- Works with QA on usability testing and acceptance

---

### Data Analyst / BI

#### Role Summary
Define measurement strategy, instrument events, and analyze outcomes to inform decisions.

#### Responsibilities
- Define key metrics and tracking plans
- Implement or validate analytics instrumentation
- Create dashboards and reports
- Analyze release impact and user behavior

#### Goals
- Ensure data-driven decision making
- Measure and communicate outcomes against success criteria

#### Typical Communication / Interactions
- Partners with Product Manager to define success metrics
- Works with Developers and DevOps to implement instrumentation
- Shares findings with stakeholders and integrates learnings into planning

---

### Technical Writer / Documentation Owner

#### Role Summary
Produce and maintain user-facing and operational documentation.

#### Responsibilities
- Write release notes, API docs, runbooks, and onboarding guides
- Ensure documentation is updated prior to release
- Maintain a documentation review process

#### Goals
- Reduce user and support friction with clear documentation
- Keep runbooks current for on-call responders

#### Typical Communication / Interactions
- Receives feature summaries from Product Manager and Developers
- Works with Release Manager on release notes
- Coordinates with Support for knowledge-base updates

---

### Release Manager

#### Role Summary
Coordinate the release process end-to-end to ensure predictable, low-risk deployments.

#### Responsibilities
- Maintain release checklist and schedule
- Confirm pre-release requirements (tests, docs, rollback plans)
- Coordinate cross-team deployment activities
- Communicate release status to stakeholders

#### Goals
- Reduce deployment-related incidents
- Ensure coordinated, observable releases

#### Typical Communication / Interactions
- Works with DevOps/SRE to run staged deployments
- Confirms readiness with QA, Product, and Technical Writer
- Notifies PM and stakeholders of release outcomes

---

### Customer Success / Support Lead

#### Role Summary
Represent customer operational needs and handle post-release support.

#### Responsibilities
- Prepare support playbooks and triage guides
- Triage and escalate customer issues
- Feed customer feedback into the backlog

#### Goals
- Increase customer satisfaction and reduce time-to-resolution
- Ensure customer-impacting issues are prioritized appropriately

#### Typical Communication / Interactions
- Engages with Product Manager for priority fixes
- Works with Technical Writer to update KB articles
- Coordinates with Developers for hotfixes and workarounds

---

### Legal / Compliance Advisor

#### Role Summary
Ensure features and processes comply with legal, regulatory, and contractual obligations.

#### Responsibilities
- Review features for compliance risk (PII, data residency, contracts)
- Provide sign-off where required
- Advise on retention, consent, and data-sharing policies

#### Goals
- Avoid legal and regulatory exposure
- Ensure contractual commitments are met

#### Typical Communication / Interactions
- Consulted by Product Manager/PM during planning for compliance-impacting features
- Coordinates with Security Engineer for technical controls

---

### Accessibility Specialist

#### Role Summary
Help ensure that features meet accessibility standards and are testable.

#### Responsibilities
- Run accessibility reviews and provide remediation guidance
- Create accessibility acceptance criteria and tests
- Provide training and best practices for designers and developers

#### Goals
- Deliver inclusive products that meet required standards (e.g., WCAG)
- Reduce accessibility regressions in releases

#### Typical Communication / Interactions
- Works with Designers and Developers during design and implementation
- Partners with QA to include accessibility checks in test plans

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
```
