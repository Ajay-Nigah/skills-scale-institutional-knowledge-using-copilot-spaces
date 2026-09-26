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

### Interactions with Other Roles
- **With Product Managers**: Receive and clarify acceptance criteria, discuss prioritization and trade-offs
- **With Project Managers**: Participate in planning, report progress and blockers in standups
- **With QA/Test Lead**: Collaborate on test strategy, address quality findings before release
- **With Product Lead**: Escalate technical risks and major decisions requiring strategic input

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

### Interactions with Other Roles
- **With Developers**: Define acceptance criteria and prioritize work based on roadmap
- **With Project Managers**: Align on timelines, dependencies, and scope trade-offs
- **With Product Lead**: Escalate prioritization conflicts and strategic decisions
- **With Stakeholders**: Gather requirements and communicate product direction
- **With QA/Test Lead**: Define quality standards and acceptance criteria for validation

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

### Interactions with Other Roles
- **With Developers & Product Managers**: Facilitate planning and track progress against milestones
- **With Product Lead & Sponsor**: Escalate risks and seek approvals for major changes
- **With QA/Test Lead**: Coordinate testing schedules and release readiness
- **With Stakeholders**: Provide regular updates and manage expectations on timeline and scope

---

## Product Lead / Product Owner

### Role Summary
Product Leads provide strategic oversight and decision authority for product initiatives. They act as the primary escalation point for product-level decisions and bridge stakeholder needs with delivery capabilities. Product Leads participate in gate reviews and milestone approvals, ensuring alignment between business goals and execution.

### Responsibilities
- Set strategic product direction and business priorities
- Act as escalation point for prioritization conflicts and trade-off decisions
- Approve gate reviews at key milestones (initiation, planning, release)
- Ensure alignment between stakeholder expectations and delivery roadmap
- Review and validate business outcomes after release
- Mentor and guide Product Managers on strategy and vision

### Goals
- Maximize business value delivered through the product
- Ensure strategic alignment across all initiatives
- Reduce escalation cycles and decision latency
- Build sustainable, customer-centric product strategy

### Typical Communication
- Monthly stakeholder alignment reviews
- Gate approval meetings at project milestones
- Post-release outcome reviews with business stakeholders
- Strategic planning and roadmap refinement sessions
- Ad-hoc escalations from Product Managers and Project Managers

### Interactions with Other Roles
- **With Product Managers**: Review prioritization decisions, resolve conflicts, provide strategic context
- **With Project Managers**: Approve major scope changes, timelines, and resource allocation
- **With Sponsor**: Align on business case and strategic goals; escalate funding/resource decisions
- **With Stakeholders**: Communicate product strategy and manage expectations
- **With Developers**: Communicate strategic technical decisions and architectural direction when needed

---

## QA / Test Lead

### Role Summary
QA/Test Leads own quality standards and testing strategy for projects. They define acceptance criteria validation approaches, manage test coverage and automation, and participate in planning and retrospectives to continuously improve quality processes. QA/Test Leads ensure that deliverables meet defined quality gates before release.

### Responsibilities
- Define quality standards and acceptance criteria for features
- Develop and maintain test strategy (unit, integration, end-to-end, manual)
- Manage test coverage metrics and automation roadmap
- Conduct acceptance testing and validate against criteria
- Report quality issues, defects, and risk assessments
- Participate in planning to identify testability requirements early
- Contribute to retrospectives with quality learnings and improvements

### Goals
- Prevent defects from reaching production
- Reduce manual testing effort through automation
- Maintain high test coverage and observability
- Enable confident, low-risk releases

### Typical Communication
- Test plans and strategy documents during planning
- Daily standup updates on test progress and blockers
- Defect reports and quality metrics dashboards
- Sprint reviews demonstrating test coverage and validation
- Release readiness assessments pre-deployment

### Interactions with Other Roles
- **With Developers**: Collaborate on test strategy, provide early feedback on testability, review code for quality
- **With Product Managers**: Clarify acceptance criteria, discuss quality trade-offs
- **With Project Managers**: Coordinate testing schedules, flag quality risks, validate release readiness
- **With DevOps/Infrastructure**: Collaborate on test environment setup and smoke testing procedures
- **With Product Lead**: Escalate quality risks that impact go/no-go decisions

---

## Project Sponsor

### Role Summary
Project Sponsors are executive or senior stakeholders with budget and resource authority. They approve the business case and project charter, serve as the escalation point for business-level decisions, and review project outcomes to measure business impact. Sponsors provide organizational backing and remove barriers to project success.

### Responsibilities
- Approve project business case and resource allocation
- Review and authorize project charter at initiation gate
- Act as escalation point for business-level decisions and conflicts
- Remove organizational barriers and secure resources
- Review project outcomes and measure business impact post-release
- Communicate project status to senior leadership
- Make go/no-go decisions at major gates

### Goals
- Maximize return on investment (ROI) for approved projects
- Ensure business priorities are reflected in project execution
- Remove obstacles that could derail project success
- Measure and validate business outcomes

### Typical Communication
- Project charter review and approval (initiation phase)
- Gate approval meetings at major milestones
- Executive status reports and business impact reviews
- Escalation resolution for resource and priority conflicts
- Post-release outcome and ROI reviews

### Interactions with Other Roles
- **With Product Lead**: Review strategy, approve major changes to scope or timeline
- **With Project Manager**: Approve project plan, review status, remove escalated blockers
- **With Stakeholders**: Communicate project priority and expected outcomes
- **With Developers/QA**: Provide business context and impact assessment for critical decisions

---

## Stakeholder / Customer Representative

### Role Summary
Stakeholders or Customer Representatives represent user and business needs throughout the project lifecycle. They provide feedback on acceptance criteria, participate in demos and reviews, and help validate that the solution meets market and user needs. This role is essential for ensuring product-market fit and alignment with business objectives.

### Responsibilities
- Define and communicate user and business requirements
- Provide feedback on acceptance criteria and user experience
- Participate in demos and sprint reviews
- Validate that solutions address original problem statement
- Help prioritize features based on customer impact
- Contribute to retrospectives with customer feedback

### Goals
- Ensure solution meets user needs and business objectives
- Validate product-market fit and customer satisfaction
- Reduce rework by catching misalignments early
- Build products customers actually want to use

### Typical Communication
- Requirements workshops during planning
- Demo feedback and acceptance validation during execution
- User testing and feedback sessions
- Sprint reviews and release previews
- Post-release feedback and satisfaction surveys

### Interactions with Other Roles
- **With Product Managers**: Provide user feedback and requirements to inform prioritization
- **With Developers/QA**: Validate acceptance criteria and user experience
- **With Project Managers**: Participate in milestone reviews and provide status feedback
- **With Product Lead**: Contribute to strategic validation and roadmap feedback

---

## Security / Compliance Lead *(optional, as applicable)*

### Role Summary
Security/Compliance Leads ensure that projects meet security and compliance requirements. They review security architecture and design, validate security scanning in CI/CD pipelines, guide incident response procedures, and ensure alignment with organizational security and compliance policies.

### Responsibilities
- Review security requirements and threat models
- Validate secure coding practices and architecture design
- Ensure security scanning and testing in CI/CD pipeline
- Guide incident response procedures for security issues
- Maintain compliance with regulatory and organizational policies
- Conduct security assessments and penetration testing (as applicable)
- Provide security training and best practices guidance to teams

### Goals
- Prevent security vulnerabilities and data breaches
- Ensure regulatory and compliance alignment
- Build security into the development process
- Maintain organization's security posture

### Typical Communication
- Security requirements during planning phase
- Code review and security scanning feedback
- Incident response and triage meetings
- Compliance audit reports and remediation plans
- Security training and awareness sessions

### Interactions with Other Roles
- **With Developers**: Review code for security vulnerabilities, provide secure coding guidance
- **With Project Managers**: Flag security risks and compliance requirements
- **With DevOps/Infrastructure**: Validate secure deployment and infrastructure practices
- **With Product Lead/Sponsor**: Escalate security risks with business impact

---

## DevOps / Infrastructure Engineer *(optional, as applicable)*

### Role Summary
DevOps/Infrastructure Engineers manage deployment pipelines, infrastructure provisioning, and production monitoring. They own release readiness and rollback procedures, monitor production health, collaborate on incident response, and ensure systems are performant and scalable. They enable teams to deploy with confidence and maintain high availability.

### Responsibilities
- Design and maintain deployment pipelines (CI/CD)
- Provision and manage infrastructure (cloud, on-premises, hybrid)
- Implement monitoring, logging, and observability
- Manage release procedures and coordination
- Develop and maintain rollback and disaster recovery procedures
- Respond to and help resolve production incidents
- Collaborate on performance optimization and scalability planning

### Goals
- Enable fast, reliable, automated deployments
- Maintain high system availability and performance
- Reduce time-to-recovery (MTTR) during incidents
- Minimize manual intervention and human error

### Typical Communication
- Infrastructure requirements during planning
- Release readiness checks pre-deployment
- Incident response and status updates
- Performance metrics and monitoring dashboards
- Infrastructure documentation and runbooks

### Interactions with Other Roles
- **With Developers**: Provide deployment documentation and infrastructure requirements
- **With Project Managers**: Coordinate deployment windows and release schedules
- **With QA/Test Lead**: Support test environment provisioning and smoke testing
- **With Product Lead/Sponsor**: Escalate production incidents and impact assessments

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to interaction sections to understand how roles collaborate across the project lifecycle.
