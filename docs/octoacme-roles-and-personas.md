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
Release Managers coordinate the end-to-end release process, ensuring all release criteria are met before deployment. They work closely with development, QA, and operations teams to execute safe, repeatable releases.

### Responsibilities
- Plan and schedule releases across environments
- Maintain and execute release checklists
- Coordinate deployment activities and communications
- Verify release readiness criteria (tests, approvals, documentation)
- Manage rollback procedures if issues arise
- Document release processes and post-release metrics

### Goals
- Execute zero-downtime deployments
- Minimize release-related incidents
- Ensure all stakeholders are informed and prepared
- Continuously improve release automation and reliability

### Typical Communication
- Pre-release readiness meetings with PM, QA, and stakeholders
- Release announcements and status updates
- Post-release verification reports
- Incident coordination if rollback needed

### Interactions with Other Roles
- Partners with [Project Managers](#project-managers) and QA/Testing teams to verify release criteria
- Coordinates with [Developers](#developers) on deployment procedures and rollback plans
- Works with [SRE/On-call](#sreor-call-engineer) to monitor production health
- Briefs [Support Engineers](#support-engineercustomer-success-liaison) on new features and known issues

---

## SRE/On-call Engineer

### Role Summary
Site Reliability Engineers (SREs) and On-call Engineers ensure system reliability, performance, and availability. They monitor production, respond to incidents, and implement practices that improve operational resilience.

### Responsibilities
- Monitor system health, performance, and error rates
- Respond to and resolve production incidents
- Maintain runbooks and incident response procedures
- Implement observability and alerting systems
- Conduct post-incident reviews and drive improvements
- Collaborate on capacity planning and disaster recovery

### Goals
- Maximize system uptime and reliability
- Reduce mean time to detection (MTTD) and resolution (MTTR)
- Build automation to eliminate toil
- Foster a culture of reliability and operational excellence

### Typical Communication
- Incident alerts and status updates during outages
- Post-mortem reports with root cause analysis
- Weekly reliability metrics and SLO reviews
- Recommendations for architecture and operational improvements

### Interactions with Other Roles
- Escalates critical incidents to [Project Managers](#project-managers) and stakeholders
- Collaborates with [Developers](#developers) to troubleshoot issues and improve code reliability
- Partners with [Release Managers](#release-manager) during deployments
- Works with [Security Lead](#security-lead) on security incidents and vulnerabilities

---

## Security Lead

### Role Summary
Security Leads ensure that security is built into every phase of the project lifecycle. They conduct security reviews, threat assessments, and vulnerability management, and ensure compliance with security standards.

### Responsibilities
- Review designs and code for security vulnerabilities
- Conduct threat modeling and risk assessments
- Ensure security scanning is integrated into CI/CD
- Respond to security incidents and coordinate remediation
- Maintain security documentation and compliance artifacts
- Train teams on secure coding and security best practices

### Goals
- Minimize security vulnerabilities and exposure
- Ensure compliance with security policies and regulations
- Build security awareness across teams
- Respond rapidly to security incidents

### Typical Communication
- Security review feedback during design and code review
- Vulnerability reports and remediation plans
- Incident response coordination during security events
- Compliance and audit reports

### Interactions with Other Roles
- Reviews designs with [Product Managers](#product-managers) and [Developers](#developers)
- Coordinates with [Project Managers](#project-managers) to track security work in backlog
- Partners with [SRE/On-call](#sreor-call-engineer) on incident response
- Collaborates with [Legal & Compliance Advisor](#legal--compliance-advisor) on regulatory requirements

---

## UX Researcher/Product Designer

### Role Summary
UX Researchers and Product Designers advocate for users by designing intuitive, accessible experiences. They create wireframes, prototypes, and conduct user research to validate that products meet user needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define user flows and interaction patterns
- Ensure accessibility and inclusive design standards
- Collaborate with product and engineering on feasibility
- Validate designs with users and iterate based on feedback

### Goals
- Deliver experiences that are intuitive and delightful
- Reduce user friction and support tickets
- Ensure accessibility for all users
- Make data-informed design decisions

### Typical Communication
- Design reviews with product and engineering teams
- User research findings and recommendations
- Prototype demos and usability test results
- Design specs and component documentation

### Interactions with Other Roles
- Receives requirements from [Product Managers](#product-managers) and validates with users
- Works with [Developers](#developers) to ensure technical feasibility and implementation accuracy
- Collaborates with [Data Analysts](#data-analyst) to measure design effectiveness
- Partners with [Support Engineers](#support-engineer) to understand user pain points

---

## Data Analyst/Analytics Engineer

### Role Summary
Data Analysts and Analytics Engineers design and maintain data pipelines, reports, and dashboards that inform product and process decisions. They ensure that success metrics are measurable and actionable.

### Responsibilities
- Design and implement analytics instrumentation
- Build and maintain dashboards and reports
- Analyze product usage and performance data
- Collaborate with PM and Product to define metrics
- Ensure data quality and accuracy
- Provide insights to inform prioritization and retrospectives

### Goals
- Enable data-driven decision-making
- Make success metrics visible and actionable
- Improve data quality and reliability
- Reduce time to insight

### Typical Communication
- Weekly metrics reviews with PM and Product teams
- Ad-hoc analysis requests and recommendations
- Dashboard demos and data quality reports
- Insights shared in retrospectives and planning sessions

### Interactions with Other Roles
- Works with [Product Managers](#product-managers) to define and track success metrics
- Partners with [Developers](#developers) to instrument tracking and ensure data accuracy
- Supports [Project Managers](#project-managers) with velocity and delivery metrics
- Provides insights to [UX Researchers/Product Designers](#ux-researcherproduct-designer) on user behavior patterns

---

## Technical Program Manager/Delivery Lead

### Role Summary
Technical Program Managers (TPMs) and Delivery Leads coordinate complex, cross-functional initiatives that span multiple teams. They drive alignment, manage dependencies, and ensure programs deliver on strategic objectives.

### Responsibilities
- Define program goals, scope, and success criteria
- Coordinate work across multiple teams and projects
- Manage dependencies, risks, and resource allocation
- Facilitate cross-team communication and decision-making
- Track program-level metrics and report to leadership
- Remove blockers and escalate issues as needed

### Goals
- Deliver strategic initiatives on time and within scope
- Maintain alignment across teams and stakeholders
- Minimize cross-team dependencies and conflicts
- Ensure programs achieve intended business outcomes

### Typical Communication
- Weekly program sync meetings with team leads
- Dependency maps and risk registers
- Leadership updates on program status and milestones
- Cross-team coordination and conflict resolution

### Interactions with Other Roles
- Coordinates with [Project Managers](#project-managers) on individual project delivery
- Aligns with [Product Managers](#product-managers) on strategic priorities
- Works with [Developers](#developers) and other specialists across teams
- Escalates issues to sponsors and stakeholders as needed

---

## Support Engineer/Customer Success Liaison

### Role Summary
Support Engineers and Customer Success Liaisons act as the bridge between customers and product teams. They triage customer issues, gather feedback, and ensure that user-reported problems are resolved quickly.

### Responsibilities
- Triage and resolve customer-reported issues
- Escalate bugs and feature requests to engineering
- Document common issues and create knowledge base articles
- Gather customer feedback to inform product decisions
- Monitor support metrics and identify trends
- Provide product training and onboarding to customers

### Goals
- Maximize customer satisfaction and retention
- Reduce time to resolution for customer issues
- Minimize recurring support requests through documentation and fixes
- Surface customer insights to inform product roadmap

### Typical Communication
- Daily triage of support tickets and escalations
- Weekly summaries of support trends and top issues
- Feedback reports to product and engineering teams
- Customer-facing updates and workarounds

### Interactions with Other Roles
- Escalates issues to [Developers](#developers) and QA teams
- Provides customer feedback to [Product Managers](#product-managers)
- Coordinates with [Release Managers](#release-manager) on release communications
- Works with [UX Researchers/Product Designers](#ux-researcherproduct-designer) to identify usability issues

---

## Legal & Compliance Advisor

### Role Summary
Legal and Compliance Advisors ensure that products and processes comply with applicable laws, regulations, and organizational policies. They review contracts, data practices, and product features for legal risk.

### Responsibilities
- Review product features for legal and regulatory compliance
- Advise on data privacy, security, and user consent requirements
- Review contracts, terms of service, and licensing agreements
- Ensure compliance with industry regulations (e.g., GDPR, HIPAA)
- Coordinate audits and compliance reporting
- Provide training on legal and compliance topics

### Goals
- Minimize legal and regulatory risk
- Ensure products meet all compliance requirements
- Maintain organizational reputation and customer trust
- Facilitate timely legal reviews without blocking delivery

### Typical Communication
- Legal and compliance review requests and feedback
- Risk assessments for new features or partnerships
- Compliance audit reports and recommendations
- Training sessions on regulatory requirements

### Interactions with Other Roles
- Reviews features with [Product Managers](#product-managers) for compliance risk
- Advises [Security Lead](#security-lead) on data protection requirements
- Coordinates with [Project Managers](#project-managers) on compliance milestones
- Partners with [Support Engineers](#support-engineer) on customer data handling

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, coach teams on agile practices, and remove process impediments. They enable teams to self-organize and deliver iteratively with high quality.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Coach the team on agile principles and practices
- Remove process blockers and impediments
- Shield the team from distractions and interruptions
- Track team velocity and help improve predictability
- Foster a culture of continuous improvement

### Goals
- Maximize team productivity and flow
- Improve team collaboration and morale
- Reduce cycle time and increase predictability
- Build a culture of transparency and learning

### Typical Communication
- Daily facilitation of standup meetings
- Sprint planning and retrospective facilitation
- Blocker escalation and resolution coordination
- Process improvement suggestions and experiments

### Interactions with Other Roles
- Works closely with [Project Managers](#project-managers) and [Product Managers](#product-managers) to align on priorities
- Supports [Developers](#developers) in self-organizing and removing blockers
- Coordinates with [Technical Program Managers](#technical-program-managerdelivery-lead) on cross-team dependencies
- Partners with all roles to foster agile mindset and practices

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

