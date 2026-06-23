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

## Additional Personas

The following personas represent specialized roles that enhance accountability, reduce handoff delays, and ensure critical responsibilities are explicitly owned in OctoAcme projects.

### Tech Lead / Architect

#### Role Summary
Tech Leads guide technical strategy, system design, and architectural decisions. They mentor developers, own major technical risks, and ensure solutions are scalable and maintainable.

#### Responsibilities
- Define system architecture and technical approach
- Guide technical decisions and code review standards
- Review designs for scalability, maintainability, and security
- Own and mitigate major technical risks
- Mentor developers and conduct technical design reviews
- Identify and propose technical debt remediation

#### Interaction with Other Roles
- **With Developers**: Provide architectural guidance, review technical designs, and support implementation decisions
- **With Product Manager**: Assess technical feasibility and timeline impact of feature requests
- **With Project Manager**: Help identify technical dependencies and risks for planning
- **With QA/Testing**: Ensure new features are designed for testability

#### Goals
- Deliver scalable, maintainable systems that reduce future technical debt
- Accelerate team capability through mentoring and clear architecture
- Minimize unplanned rework due to technical oversights

#### Typical Communication
- Design review sessions and architecture discussions
- Technical spike documentation and recommendations
- Code review comments and mentoring feedback
- Escalations on technical trade-offs to Product Lead or PM

---

### UX Designer

#### Role Summary
UX Designers lead user research, define interaction patterns, and ensure products are intuitive and accessible. They work closely with Product Managers to translate business goals into user-centered designs.

#### Responsibilities
- Conduct user research and validate design assumptions
- Create wireframes, prototypes, and detailed UI specifications
- Define acceptance criteria for usability and accessibility
- Validate designs through user testing and feedback
- Ensure consistency with design systems and brand guidelines
- Collaborate on experience strategy and user flows

#### Interaction with Other Roles
- **With Product Manager**: Translate product goals into user experiences; prioritize design work
- **With Developers**: Provide detailed specs and design assets; discuss implementation tradeoffs
- **With QA/Testing**: Define usability acceptance criteria and validate UX during testing
- **With Project Manager**: Communicate design timelines and dependencies

#### Goals
- Deliver intuitive, accessible user experiences that drive adoption
- Reduce support costs through better UX design
- Build products users love and recommend

#### Typical Communication
- Design reviews and user testing sessions
- Specification documents and design handoffs
- Accessibility audits and improvement recommendations
- User research findings and insights

---

### Data Analyst / Insights Owner

#### Role Summary
Data Analysts / Insights Owners define success metrics, instrument features for tracking, analyze outcomes, and provide data-driven insights to inform iterations and strategic decisions.

#### Responsibilities
- Define measurable success metrics aligned with business goals
- Instrument features and track user behavior data
- Analyze feature adoption, usage patterns, and impact metrics
- Report outcomes and insights to stakeholders
- Identify data-driven improvement opportunities
- Build dashboards and monitoring for key signals

#### Interaction with Other Roles
- **With Product Manager**: Align on success metrics and data-driven prioritization
- **With Project Manager**: Report on delivery metrics and outcome tracking
- **With Developers/Platform Engineers**: Collaborate on instrumentation and data pipeline
- **With Tech Lead**: Ensure data quality and technical approach to analytics

#### Goals
- Enable data-driven decisions across the organization
- Measure and communicate product impact and ROI
- Identify patterns and opportunities for continuous improvement

#### Typical Communication
- Weekly metric dashboards and trend analysis
- Post-release outcome reports and insights
- Data-driven recommendations in planning sessions
- Retrospective analysis and learnings documentation

---

### Release Manager / Product Operations

#### Role Summary
Release Managers coordinate release windows, deployment processes, rollback procedures, and stakeholder communications. They ensure smooth, predictable releases with minimal disruption.

#### Responsibilities
- Coordinate release windows and deployment schedules
- Document release notes and migration steps
- Execute deployment procedures and verify post-deploy health
- Manage rollback and incident response during deployments
- Coordinate communications with Support, Marketing, and Stakeholders
- Maintain release runbooks and process documentation
- Track release metrics and dependencies

#### Interaction with Other Roles
- **With Project Manager**: Align on release timeline and stakeholder communications
- **With DevOps/Platform Engineer**: Execute deployment and monitor infrastructure health
- **With QA/Testing**: Ensure smoke tests pass before production deployment
- **With Support/Success Teams**: Coordinate customer communication and onboarding
- **With Tech Lead**: Understand technical implications and rollback procedures

#### Goals
- Deliver predictable, low-risk releases to production
- Minimize deployment-related incidents and rollbacks
- Enable customers and teams to adopt new features smoothly

#### Typical Communication
- Release calendar and deployment checklists
- Release notes and customer/stakeholder communications
- Post-deployment verification reports
- Incident response coordination during deployments

---

### Security / Compliance Lead

#### Role Summary
Security and Compliance Leads evaluate security and compliance implications of features, conduct threat reviews, and ensure projects meet risk and regulatory requirements.

#### Responsibilities
- Conduct threat reviews and security assessments
- Ensure compliance with relevant regulations and standards
- Review and approve security-sensitive implementations
- Provide security guidance and best practices
- Sign off on releases that affect risk posture
- Coordinate incident response for security issues
- Maintain security documentation and compliance artifacts

#### Interaction with Other Roles
- **With Tech Lead / Architects**: Review technical designs for security implications
- **With Developers**: Provide remediation guidance and security code review
- **With Project Manager / Product Manager**: Escalate security risks and compliance requirements
- **With QA/Testing**: Define security test cases and validation procedures
- **With DevOps/Platform Engineer**: Collaborate on infrastructure security and monitoring

#### Goals
- Protect customer data and company assets
- Ensure compliance with regulations and standards
- Enable secure, fast development without sacrificing speed

#### Typical Communication
- Threat review and security assessment reports
- Security remediation guidance and code review comments
- Compliance checklists and audit documentation
- Incident response coordination and post-mortems

---

### DevOps / Platform Engineer

#### Role Summary
DevOps and Platform Engineers maintain deployment infrastructure, CI/CD pipelines, and environment stability. They enable developers to ship code safely and developers to focus on features.

#### Responsibilities
- Maintain and optimize deployment pipelines and infrastructure-as-code
- Ensure environment stability and high availability
- Implement observability, monitoring, and alerting
- Support developers with deployment and environment issues
- Manage secrets, access control, and security tooling
- Document operational procedures and runbooks
- Collaborate on scaling and performance optimization

#### Interaction with Other Roles
- **With Developers**: Support deployment issues and provide environment documentation
- **With Release Manager**: Execute deployments and monitor infrastructure health
- **With Tech Lead**: Discuss infrastructure trade-offs and scalability requirements
- **With QA/Testing**: Ensure staging environments are stable and representative
- **With Security Lead**: Implement security controls and access policies

#### Goals
- Enable fast, reliable deployments and reduce deployment failures
- Maintain high availability and performance of production systems
- Accelerate developer productivity through self-service automation

#### Typical Communication
- Infrastructure documentation and runbooks
- Deployment support and troubleshooting
- Monitoring dashboards and incident alerts
- Planning sessions on scalability and reliability

---

### Support / Customer Success Liaison

#### Role Summary
Support and Customer Success teams capture customer feedback, triage operational issues, and coordinate on documentation and onboarding. They represent the voice of the customer in product and technical decisions.

#### Responsibilities
- Gather and prioritize customer feedback and pain points
- Triage and escalate operational issues and bugs
- Coordinate customer onboarding and training
- Create and maintain user-facing documentation
- Identify trends in customer issues and escalate patterns
- Collaborate on support readiness before releases
- Advocate for customer needs in product and technical discussions

#### Interaction with Other Roles
- **With Product Manager**: Share customer insights to inform prioritization
- **With Project Manager**: Communicate customer urgency and impact of delays
- **With Developers / QA**: Reproduce issues and provide customer context
- **With Tech Lead**: Help prioritize technical debt impacting customers
- **With Release Manager**: Prepare customer communication for releases

#### Goals
- Maximize customer satisfaction and retention
- Reduce support burden through better product design and documentation
- Enable the team to prioritize work that solves real customer problems

#### Typical Communication
- Customer feedback summaries and issue escalations
- Support readiness checklists before releases
- User documentation and onboarding guides
- Retrospective insights on customer impact

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning projects, assign clear owners for each persona to reduce ambiguity and handoff delays.
- Use interaction patterns to identify dependencies and escalation paths during risk identification.
