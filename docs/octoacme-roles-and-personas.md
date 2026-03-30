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

## UX Designer

### Role Summary
UX Designers craft user experiences that are intuitive, accessible, and aligned with product goals. They bridge the gap between user needs and technical implementation through research, prototyping, and iterative design.

### Responsibilities
- Design user experiences, wireframes, and interactive prototypes
- Conduct user research and usability testing to gather feedback
- Translate user insights into actionable design requirements
- Collaborate with Product Managers and Developers to refine feature requirements
- Ensure designs meet accessibility standards and usability acceptance criteria

### Goals
- Deliver intuitive and engaging user experiences
- Reduce user friction and support adoption of new features
- Ensure usability is validated before development begins

### Typical Communication
- Design reviews and usability walkthroughs with PdM and Developers
- Prototype demos and iteration feedback sessions
- Annotated design specs and style guides shared with engineering

### Interactions with Existing Roles
- **Product Manager (PdM):** Partners from feature ideation through delivery to align designs with product vision and success metrics
- **Developers:** Provides design specs, reviews implementations, and ensures designs are feasible and accurately built
- **Project Manager (PM):** Coordinates on timeline for design milestones and usability testing windows

---

## DevOps Engineer

### Role Summary
DevOps Engineers own the infrastructure, CI/CD pipelines, and deployment automation that enable reliable, fast, and repeatable software delivery. They act as the bridge between development and operations to ensure production stability.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure, monitoring, alerting, and logging tooling
- Establish and enforce release readiness criteria and deployment standards
- Own incident response tooling and on-call escalation processes
- Promote DevOps best practices across the development team

### Goals
- Enable fast, reliable, and automated software deployments
- Minimize deployment-related incidents and mean time to recovery
- Maintain high availability and observability in production

### Typical Communication
- Release readiness reviews with PM and Developers
- Incident postmortems and retrospectives
- Infrastructure and pipeline documentation and runbooks

### Interactions with Existing Roles
- **Developers:** Collaborates on deployment best practices, branch strategies, and pipeline integration requirements
- **Project Manager (PM):** Coordinates release windows, deployment schedules, and production stability reporting
- **Product Manager (PdM):** Advises on operational constraints and infrastructure capacity that may affect roadmap commitments

---

## Security Lead

### Role Summary
Security Leads define and enforce the security posture of projects, ensuring that products are built with security-by-design principles. They identify threats, manage compliance requirements, and act as the security authority across the team.

### Responsibilities
- Define security requirements and ensure they are reflected in acceptance criteria
- Conduct threat modeling and security reviews for new features and architecture changes
- Ensure compliance with relevant standards (e.g., GDPR, SOC 2, OWASP)
- Review code, infrastructure, and design artifacts for security vulnerabilities
- Own response coordination for security incidents and findings

### Goals
- Ensure products are secure and compliant before release
- Minimize the attack surface and reduce security-related incidents
- Build a security-aware culture across the development team

### Typical Communication
- Security review sessions during design and development phases
- Threat model documentation and security sign-off artifacts
- Incident reports and remediation tracking

### Interactions with Existing Roles
- **Developers:** Advises on secure coding practices, reviews pull requests for security issues, and validates mitigations
- **Project Manager (PM):** Informs on security risk timelines and compliance gates that may affect delivery schedules
- **Product Manager (PdM):** Collaborates on security requirements and ensures security trade-offs are factored into prioritization decisions

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams by translating complex business requirements into clear, actionable user stories and specifications. They ensure that what is built aligns with business objectives and stakeholder expectations.

### Responsibilities
- Elicit, analyze, and document business requirements from stakeholders
- Translate business needs into user stories, acceptance criteria, and process flows
- Validate delivered solutions against business requirements and stakeholder expectations
- Identify process gaps and recommend improvements
- Facilitate requirement clarification sessions between stakeholders and development teams

### Goals
- Ensure delivered solutions accurately address business needs
- Reduce ambiguity and rework caused by misunderstood requirements
- Improve alignment and communication between business and technical teams

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story documentation and acceptance criteria in the project backlog
- Requirement change logs and impact assessments

### Interactions with Existing Roles
- **Product Manager (PdM):** Collaborates closely to refine and validate user stories and ensure requirements align with the product roadmap
- **Developers:** Clarifies requirements during development, answers questions about edge cases, and validates implementations
- **Project Manager (PM):** Supports scope definition, change management processes, and timeline estimation
- **Stakeholders:** Serves as the primary point of contact for gathering, clarifying, and communicating requirements

---

## Stakeholder (Customer / End User)

### Role Summary
Stakeholders, including customers and end users, are the ultimate recipients of the product. Their input drives prioritization and validates that delivered solutions meet real-world needs. Engaging them throughout the project lifecycle ensures outcomes are aligned with actual expectations.

### Responsibilities
- Provide feedback on proposed solutions, prototypes, and delivered features
- Validate that delivered functionality meets their needs and expectations
- Prioritize needs and communicate business impact to inform roadmap decisions
- Participate in user research sessions, demos, and acceptance testing
- Escalate blockers or unmet needs to the appropriate team contacts

### Goals
- Receive solutions that solve real problems and deliver measurable value
- Have a clear and consistent channel for providing feedback and raising concerns
- Maintain confidence in the team's ability to deliver on commitments

### Typical Communication
- Demos and sprint reviews to provide feature feedback
- User research sessions and usability testing with UX Designers
- Periodic alignment meetings with PdM and PM on roadmap and delivery status

### Interactions with Existing Roles
- **Product Manager (PdM):** Primary relationship owner for stakeholder engagement; gathers input to shape the roadmap and validate prioritization
- **Project Manager (PM):** Communicates delivery timelines, risks, and status updates to maintain stakeholder confidence
- **UX Designer:** Participates in usability testing and prototype reviews to validate design decisions
- **Business Analyst:** Works directly to define and validate requirements, ensuring delivered solutions match business expectations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

