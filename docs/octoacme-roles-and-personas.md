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
- Collaborate with **Design Lead** on UI/UX specifications and technical feasibility
- Work with **QA/Testing** roles on test coverage and acceptance criteria verification
- Engage with **Release Manager** on deployment readiness and hotfix procedures
- Consult with **Technical Writer** on API documentation and code examples

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
- Partner with **Customer Success Manager** to surface user feedback and pain points
- Align with **Risk Lead** on market and product risks
- Coordinate with **Design Lead** on user research and design validation
- Work with **Project Manager** on timeline and resource planning

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
- Partner with **Risk Lead** on risk identification, tracking, and escalation
- Coordinate with **Release Manager** on deployment schedules and rollout planning
- Work with **Product Manager** on scope and prioritization decisions
- Engage all roles for status updates and dependency management

---

## Release Manager

### Role Summary
Release Managers coordinate all aspects of production releases, manage deployment processes, communicate timelines to stakeholders, and own rollback and incident response plans. They ensure releases are executed smoothly with minimal risk and disruption.

### Responsibilities
- Schedule releases and create deployment windows
- Coordinate QA signoff and readiness checks before deployment
- Ensure all pre-release checklists (from Release & Deployment guide) are complete
- Communicate release timelines, changes, and status to stakeholders and support teams
- Own rollback procedures and incident response during deployments
- Document post-deployment verifications and sign-off
- Manage communication during deployment issues or hotfixes
- Track release metrics and post-mortem action items

### Goals
- Execute releases with zero or minimal production impact
- Maintain clear communication and transparency with all stakeholders
- Reduce mean time to recovery (MTTR) in case of deployment issues
- Create repeatable, low-risk release processes

### Typical Communication
- Release readiness meetings with QA, developers, and product
- Pre-release and post-release stakeholder announcements
- Incident communication during deployments
- Weekly release calendar and status updates
- Post-release retrospectives and lessons learned

### Interactions with Other Roles
- Coordinate with **Developers** and **QA/Testing** on deployment readiness and smoke test execution
- Align with **Project Manager** on release scheduling and timeline changes
- Communicate with **Customer Success Manager** on user-facing changes and support readiness
- Work with **Technical Writer** on release notes and deployment documentation

---

## Risk Lead

### Role Summary
Risk Leads proactively identify, assess, and manage project and technical risks. They own the Risk Register, facilitate risk discussions, and drive mitigation strategies to prevent issues from becoming blockers or incidents.

### Responsibilities
- Facilitate risk identification sessions during planning and execution phases
- Create and maintain the Risk Register (ID, description, impact, probability, owner, mitigation)
- Assess risk impact and likelihood using a consistent framework
- Drive definition and execution of mitigation plans
- Escalate high-impact or high-probability risks to Project Manager and leadership
- Monitor risk status and update the register weekly
- Conduct post-incident or post-mortem analysis to identify systemic risks
- Share lessons learned and risk trends across projects

### Goals
- Prevent foreseeable risks from derailing projects
- Create a culture of risk awareness and early escalation
- Enable data-driven risk decisions
- Minimize unplanned work and crisis management

### Typical Communication
- Weekly risk register reviews in project syncs
- Risk escalation memos to Project Manager and sponsors
- Risk identification workshops and brainstorm sessions
- Post-incident retrospective facilitation
- Risk trend reports and lessons learned summaries

### Interactions with Other Roles
- Partner with **Project Manager** on escalation and risk governance
- Engage **Developers** and **Design Lead** on technical and design risks
- Work with **Release Manager** on deployment and operational risks
- Consult with **Product Manager** on market and product strategy risks
- Coordinate with **Customer Success Manager** on user adoption and support risks

---

## Customer Success Manager

### Role Summary
Customer Success Managers ensure that user feedback, customer pain points, and product adoption insights are continuously surfaced to the product and project teams. They act as the voice of the customer in project decisions and help validate that solutions meet real user needs.

### Responsibilities
- Gather and synthesize customer feedback from support tickets, user interviews, and product usage
- Identify recurring pain points and feature requests from customer interactions
- Communicate customer insights and priorities to Product Manager and project teams
- Validate proposed solutions against actual customer needs
- Coordinate user acceptance testing (UAT) and beta programs
- Create customer-focused documentation and help articles
- Facilitate customer advisory boards or feedback sessions
- Track customer satisfaction metrics (NPS, CSAT, churn)

### Goals
- Ensure product decisions are grounded in real customer needs
- Reduce customer churn and increase adoption
- Create a feedback loop that keeps product and project teams customer-focused
- Accelerate time-to-value for new features

### Typical Communication
- Customer feedback summaries in weekly product syncs
- Feature request prioritization discussions with Product Manager
- Customer advisory board meetings or user research sessions
- Help article and release note reviews
- Customer satisfaction dashboards and trend reports

### Interactions with Other Roles
- Partner with **Product Manager** on customer insights and prioritization
- Share feedback with **Developers** and **Design Lead** to inform implementation
- Validate solutions with **Project Manager** and QA for UAT planning
- Coordinate with **Release Manager** on customer communication and support readiness
- Work with **Technical Writer** on customer-facing documentation

---

## Design Lead

### Role Summary
Design Leads oversee user experience and design quality across projects. They define UX requirements, conduct design reviews, advocate for usability, and ensure solutions are intuitive and accessible. They bridge the gap between user needs and technical implementation.

### Responsibilities
- Conduct user research and define design requirements and specifications
- Create wireframes, mockups, and design prototypes
- Facilitate design reviews and provide feedback to developers
- Advocate for accessibility, usability, and design consistency
- Define design patterns and component libraries for the project
- Validate solutions against design specifications during development
- Conduct usability testing and iterate based on user feedback
- Document design decisions and design systems

### Goals
- Deliver intuitive, accessible, and visually consistent user experiences
- Reduce user friction and support burden through good design
- Establish reusable design patterns and systems
- Ensure design thinking is embedded in project decisions

### Typical Communication
- Design specification documents and user stories
- Design review sessions with developers and product
- Usability testing sessions and findings reports
- Design system documentation and component guidelines
- Accessibility audit reports and recommendations

### Interactions with Other Roles
- Collaborate with **Product Manager** on user research and requirements definition
- Work with **Developers** on technical feasibility and implementation feedback
- Engage **Customer Success Manager** on user research and validation
- Coordinate with **Project Manager** on design timelines and dependencies
- Consult with **Technical Writer** on help content and user education

---

## Technical Writer

### Role Summary
Technical Writers create, synthesize, and maintain clear, comprehensive documentation for processes, APIs, features, and systems. They ensure knowledge is captured, accessible, and understandable to diverse audiences—from developers to end-users.

### Responsibilities
- Document project processes, decision logs, and architecture decisions
- Create and maintain API documentation and developer guides
- Write user-facing documentation, help articles, and FAQs
- Maintain internal wikis and knowledge bases
- Review and edit technical content for clarity and accuracy
- Create release notes, migration guides, and deployment documentation
- Conduct documentation audits and update outdated content
- Establish documentation standards and templates

### Goals
- Reduce knowledge silos and single-person dependencies
- Enable self-service support and faster onboarding
- Capture institutional knowledge in searchable, versioned artifacts
- Improve knowledge reuse and consistency across projects

### Typical Communication
- Documentation pull requests and reviews
- Release notes and migration guide publication
- Documentation planning and prioritization in project syncs
- Knowledge base updates and search indexing
- Documentation feedback and improvement suggestions

### Interactions with Other Roles
- Partner with **Developers** on API and architecture documentation
- Collaborate with **Design Lead** on user-facing help content
- Work with **Product Manager** on feature documentation and user guides
- Coordinate with **Release Manager** on release notes and deployment docs
- Engage **Customer Success Manager** on FAQ and support article creation
- Support **Project Manager** in documenting processes and decision logs

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference interaction sections to understand cross-functional dependencies and collaboration patterns.
