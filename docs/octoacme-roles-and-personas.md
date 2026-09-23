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

## Security/Compliance Leads

### Role Summary
Security/Compliance Leads ensure that project delivery meets security, privacy, regulatory, and organizational requirements. They identify control gaps early and advise the team on acceptable risk before release.

### Responsibilities
- Define required security, privacy, and compliance reviews for the project
- Assess threats, data handling, access controls, and regulatory obligations
- Document findings, required mitigations, and residual risk
- Coordinate security testing, reviews, and evidence collection
- Escalate unresolved high-impact findings through the established risk and incident paths

### Decision Rights
- Set security and compliance approval criteria within their area of responsibility
- Require mitigation, compensating controls, or additional review before launch when material risks remain
- Recommend blocking a release when mandatory controls or approvals are incomplete; business-risk acceptance remains with the designated sponsor or accountable product leadership

### Interactions with Existing Roles
- Partner with Developers on secure design, implementation, testing, and remediation
- Work with the Product Manager to balance customer outcomes and compliance requirements
- Coordinate with the Project Manager to track findings, dependencies, decisions, and escalation dates
- Advise Stakeholders and sponsors on risk acceptance and launch readiness
- Coordinate with the QA Lead and Release Manager so security checks are included in quality gates and deployment plans

---

## QA Leads

### Role Summary
QA Leads establish the testing strategy and quality gates that demonstrate whether a release meets acceptance criteria and the Definition of Done.

### Responsibilities
- Define test strategy, coverage expectations, environments, and entry/exit criteria
- Partner with the team to make acceptance criteria testable
- Coordinate functional, integration, regression, accessibility, and relevant end-to-end testing
- Lead defect triage, prioritization, and retest decisions
- Report quality risks, test results, and unresolved defects

### Decision Rights
- Define quality evidence required for work to be considered complete
- Recommend withholding approval when critical tests fail or unresolved defects exceed agreed thresholds
- Confirm whether defects are release blockers, while product and project leadership decide whether to accept residual business risk

### Interactions with Existing Roles
- Collaborate with Developers on testability, automated tests, defect investigation, and fixes
- Work with the Product Manager to confirm acceptance criteria and severity priorities
- Provide the Project Manager with quality status, risks, and schedule impacts
- Coordinate with the Release Manager on smoke tests, verification, and go/no-go readiness
- Keep Stakeholders informed about product quality, known issues, and acceptance status

---

## Release Managers / Deployment Leads

### Role Summary
Release Managers / Deployment Leads coordinate the safe movement of approved changes through staging and production, including readiness, communications, rollback, and post-deployment verification.

### Responsibilities
- Maintain the release plan, deployment schedule, and release checklist
- Confirm that acceptance criteria, CI, security scans, approvals, release notes, and rollback plans are complete
- Coordinate deployment activities, owners, change windows, and operational support
- Lead go/no-go coordination and post-deployment verification
- Record release outcomes, incidents, follow-up actions, and lessons learned

### Decision Rights
- Coordinate the operational go/no-go recommendation based on documented readiness and rollback capability
- Pause or roll back a deployment when agreed safety checks fail or production impact requires it
- Escalate unresolved readiness or business-impact decisions to the Project Manager, Product Manager, sponsor, or relevant technical owner

### Interactions with Existing Roles
- Coordinate with Developers on build artifacts, migrations, observability, and rollback steps
- Work with the QA Lead to confirm test evidence and smoke-test coverage
- Partner with the Security/Compliance Lead to verify required approvals and controls
- Keep the Project Manager informed about schedule, dependencies, risks, and deployment status
- Align with the Product Manager and Stakeholders on release scope, timing, communications, and customer impact

---

## Customer Success / Stakeholder Managers

### Role Summary
Customer Success / Stakeholder Managers represent customer and stakeholder needs throughout delivery. They monitor sentiment and adoption, coordinate feedback, and ensure that important concerns are reflected in project decisions and communications.

### Responsibilities
- Identify stakeholder groups, customer needs, communication preferences, and potential adoption barriers
- Collect and synthesize feedback, sentiment, support themes, and early usage signals
- Translate customer concerns into actionable backlog input, risks, and decisions
- Coordinate stakeholder updates, enablement, launch communications, and feedback loops
- Track adoption outcomes and escalate material dissatisfaction or business impact

### Decision Rights
- Define stakeholder communication and feedback requirements in partnership with the Project Manager and Product Manager
- Recommend priority changes or adoption mitigations based on validated customer evidence
- Escalate unresolved stakeholder-impacting issues; product prioritization and scope decisions remain with the Product Manager and accountable leadership

### Interactions with Existing Roles
- Partner with the Product Manager to turn customer feedback into outcomes, requirements, and backlog priorities
- Coordinate with the Project Manager on stakeholder mapping, status updates, risks, decisions, and escalation
- Work with Developers and the QA Lead to clarify user scenarios, acceptance expectations, and feedback from validation
- Coordinate with the Release Manager on launch timing, release notes, enablement, and post-release monitoring
- Keep Sponsors and other Stakeholders aligned on impact, adoption, sentiment, and follow-up actions

---

## Cross-functional Decision and Collaboration Model

- The Project Manager coordinates delivery, dependencies, risk tracking, and communication; they do not replace the functional decision rights of product, quality, security, or release owners.
- The Product Manager owns product outcomes, prioritization, and acceptance of product or customer trade-offs.
- Developers own technical implementation decisions within agreed architecture, security, and quality constraints.
- The QA Lead owns quality evidence and release-quality recommendations.
- The Security/Compliance Lead owns security and compliance guidance and approval criteria within their remit.
- The Release Manager / Deployment Lead owns deployment coordination and operational safety recommendations.
- The Customer Success / Stakeholder Manager owns the stakeholder feedback loop and adoption visibility.
- Sponsors or accountable leadership make explicit business-risk acceptance decisions when a concern cannot be fully mitigated.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
