# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Key Interactions
- **Product Managers** — clarify requirements and acceptance criteria
- **Project Managers** — provide estimates and status updates
- **QA/Testing** — collaborate on testability and quality gates
- **Release Engineer** — ensure code is deployment-ready
- **Security Champion** — address security concerns in code reviews

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Key Interactions
- **Project Managers** — align on priorities, timelines, and risks
- **Developers** — define requirements and acceptance criteria
- **UX Researchers** — leverage user insights for prioritization
- **Data Analysts** — track success metrics and outcomes
- **Support Liaisons** — incorporate customer feedback into the backlog

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

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Key Interactions
- **Product Managers** — align on priorities and success metrics
- **Developers** — track progress and remove blockers
- **Release Engineer** — coordinate deployment windows and rollout plans
- **Support Liaisons** — manage customer communication during incidents
- **All Roles** — escalation point for cross-functional coordination

---

## Specialist & Cross-Functional Roles

### Release Engineer

#### Role Summary
Release Engineers own CI/CD pipelines, deployment automation, release orchestration, rollback procedures, and production readiness. They ensure reliable, repeatable deployments and minimize deployment risk.

#### Responsibilities
- Design and maintain CI/CD pipelines and infrastructure
- Automate testing, building, and deployment workflows
- Orchestrate releases and manage rollback procedures
- Validate post-deployment health checks and monitoring
- Create and maintain release runbooks and playbooks
- Coordinate with Ops/SRE for production changes and incidents

#### Goals
- Enable fast, safe, and repeatable deployments
- Reduce mean time to recovery (MTTR) for incidents
- Maintain deployment reliability and observability

#### Typical Communication
- Release coordination meetings
- Deployment status updates and incident postmortems
- Technical runbooks and automation documentation

#### Key Interactions
- **Developers** — ensure code is buildable and testable; validate build artifacts
- **QA/Testing** — run pre-release verification and smoke tests
- **Project Managers** — schedule releases and communicate deployment windows
- **Security Champion** — integrate security scanning into the pipeline
- **Support Liaisons** — handoff incident context and coordinate customer communication
- **Data Analysts** — track deployment metrics and success rates

#### When to Involve
- During planning phase to assess deployment feasibility
- Before each sprint to validate pipeline readiness
- Pre-release for go/no-go decision and deployment coordination
- During incidents requiring rollback or emergency deployment

---

### Technical Writer

#### Role Summary
Technical Writers produce and maintain user-facing and internal documentation, release notes, and runbooks. They ensure accuracy, clarity, and consistency across all project artifacts.

#### Responsibilities
- Draft and maintain user-facing documentation (guides, FAQs, troubleshooting)
- Write clear, accurate release notes and migration guides
- Create and update internal runbooks, playbooks, and process documentation
- Conduct documentation reviews with Developers and QA for accuracy
- Maintain documentation consistency and version control

#### Goals
- Reduce support burden through clear, comprehensive documentation
- Enable users to self-serve and troubleshoot independently
- Ensure institutional knowledge is captured and accessible

#### Typical Communication
- Documentation review cycles with engineering teams
- Release note coordination
- Documentation maintenance and updates

#### Key Interactions
- **Developers** — validate technical accuracy and implementation details
- **QA/Testing** — ensure documentation matches actual behavior and edge cases
- **Product Managers** — align on messaging and feature highlights
- **Release Engineer** — document deployment procedures and runbooks
- **Support Liaisons** — incorporate common support questions and troubleshooting steps
- **UX Researchers** — validate documentation usability with user research

#### When to Involve
- During planning to identify documentation needs
- During feature development for technical review
- Before release for release notes and migration guides
- Ongoing for documentation maintenance and updates

---

### UX Researcher

#### Role Summary
UX Researchers lead user research, usability testing, and user insights synthesis. They inform product decisions and acceptance criteria through evidence-based findings and user feedback.

#### Responsibilities
- Plan and conduct user research studies (interviews, surveys, usability tests)
- Synthesize and communicate user insights and findings
- Validate product assumptions and design decisions
- Help define and refine acceptance criteria based on user needs
- Advocate for user needs across the team

#### Goals
- Ensure products meet real user needs and are easy to use
- Reduce risk through evidence-based design decisions
- Maximize user satisfaction and adoption

#### Typical Communication
- Research findings presentations and reports
- Design review and feedback sessions
- Acceptance criteria and user story refinement

#### Key Interactions
- **Product Managers** — shape priorities and roadmap based on research insights
- **Developers** — validate technical feasibility against user research
- **QA/Testing** — design test scenarios based on user behaviors and edge cases
- **Technical Writers** — validate documentation usability with user testing
- **Support Liaisons** — incorporate support trends and user pain points into research

#### When to Involve
- During project initiation to validate problem statement and market fit
- During planning to define user scenarios and acceptance criteria
- During development for usability testing and feedback cycles
- Post-release to measure user satisfaction and identify improvements

---

### Support Liaison (Customer Advocate)

#### Role Summary
Support Liaisons are the first point of contact for escalated customer issues and context owners for recurring support trends. They bridge the gap between customers and the delivery team.

#### Responsibilities
- Triage and manage escalated customer issues
- Create reproducible issue reports with supporting documentation
- Prioritize bugs and features with Product and Development teams
- Feed customer insights and recurring issues back into the backlog
- Communicate status and resolutions to customers
- Identify product gaps and usability pain points from customer feedback

#### Goals
- Resolve customer issues quickly and thoroughly
- Prevent recurring issues through systemic fixes
- Improve product quality based on customer feedback
- Maintain positive customer relationships and satisfaction

#### Typical Communication
- Customer escalation coordination
- Issue tracking and status updates
- Weekly customer trend reports and insights

#### Key Interactions
- **Support Team** — primary customer interface; escalation triage point
- **Product Managers** — prioritize customer-reported bugs and feature requests
- **Developers** — communicate issue details and work with reproducible cases
- **QA/Testing** — validate fixes before returning to customers
- **Project Managers** — escalate critical customer-impacting issues
- **Technical Writers** — update documentation based on support trends

#### When to Involve
- During triage to assess impact and prioritization
- For critical customer-impacting issues or incidents
- During planning to incorporate customer feedback into backlog
- Post-resolution for customer communication and follow-up

---

### Security Champion

#### Role Summary
Security Champions are embedded engineering members who advocate for secure development practices and coordinate with security teams. They integrate security into every phase of development.

#### Responsibilities
- Conduct threat modeling and security architecture reviews
- Review pull requests for security concerns and vulnerabilities
- Run security checklists and maintain security standards
- Escalate vulnerabilities to the Security on-call team
- Coordinate with Security to remediate findings
- Train and coach team on secure coding practices

#### Goals
- Prevent security vulnerabilities from reaching production
- Build a security-conscious engineering culture
- Maintain compliance and reduce security risk

#### Typical Communication
- Security review comments in pull requests
- Threat modeling sessions and security design reviews
- Security incident coordination and postmortems

#### Key Interactions
- **Developers** — provide security feedback and guidance in code reviews
- **Release Engineer** — integrate security scanning and gates into the pipeline
- **QA/Testing** — coordinate security testing and penetration testing
- **Project Managers** — escalate critical security findings
- **Product Managers** — assess security impact on feature prioritization
- **Security Team** — coordinate vulnerability disclosure and remediation

#### When to Involve
- During design phase for threat modeling and architecture review
- In pull request reviews for security validation
- During sprint planning to assess security requirements
- For critical vulnerabilities or security incidents

---

### Data Analyst

#### Role Summary
Data Analysts own instrumentation, dashboards, and measurement of success metrics for projects. They provide data-driven insights to inform decision-making across the organization.

#### Responsibilities
- Define tracking requirements and instrumentation strategy
- Build and maintain dashboards and analytics pipelines
- Analyze outcomes and measure success metrics
- Report on project performance and impact
- Identify trends, anomalies, and opportunities for improvement
- Collaborate with teams to ensure metrics align with business goals

#### Goals
- Enable data-driven decision-making across the organization
- Measure and communicate project impact
- Identify opportunities to optimize product and processes

#### Typical Communication
- Weekly/monthly metric reports and dashboards
- Analysis and insights presentations
- Success metric reviews and retrospectives

#### Key Interactions
- **Product Managers** — define success metrics and measure business impact
- **Developers** — implement instrumentation and tracking code
- **Project Managers** — track project velocity and delivery metrics
- **Technical Writers** — measure documentation effectiveness and user engagement
- **Support Liaisons** — analyze support trends and customer satisfaction metrics
- **All Roles** — provide insights and recommendations for continuous improvement

#### When to Involve
- During project initiation to define success metrics
- During planning to establish baseline and targets
- During execution for weekly/milestone metric reviews
- Post-release to measure impact and identify next improvements

---

## How These Personas Work Together

### Project Initiation
- **Product Manager** defines the problem and success metrics
- **UX Researcher** validates user needs and assumptions
- **Project Manager** coordinates stakeholder alignment
- **Data Analyst** establishes baseline metrics and targets

### Planning & Design
- **Product Manager** prioritizes and scopes the work
- **Developers** estimate feasibility and identify risks
- **UX Researcher** refines acceptance criteria based on user research
- **Security Champion** conducts threat modeling
- **Data Analyst** defines instrumentation strategy

### Development & Review
- **Developers** implement features with quality and security in mind
- **Security Champion** reviews code for vulnerabilities
- **Technical Writer** documents changes and updates docs
- **QA/Testing** validates quality and acceptance criteria
- **Data Analyst** instruments code for metrics collection

### Release & Deployment
- **Release Engineer** orchestrates deployment
- **Technical Writer** prepares release notes and guides
- **QA/Testing** runs smoke tests and validation
- **Support Liaison** prepares for customer communication
- **Project Manager** coordinates deployment window and communications

### Post-Release & Continuous Improvement
- **Data Analyst** measures impact and success metrics
- **Support Liaison** captures customer feedback and issues
- **Product Manager** prioritizes improvements based on data and feedback
- **UX Researcher** conducts post-release user research
- **All Roles** participate in retrospectives and action items

---

## Onboarding Checklist Per Role

Use these checklists to onboard new team members into each role:

### Developers
- [ ] GitHub repository access and code review process
- [ ] Local dev environment setup and build instructions
- [ ] Testing framework and CI/CD pipeline overview
- [ ] Definition of Done and acceptance criteria standards
- [ ] Key technical contacts and code owners
- [ ] Security and compliance requirements

### Product Managers
- [ ] Product roadmap and strategy documents
- [ ] Stakeholder map and communication plans
- [ ] Success metrics and analytics dashboards
- [ ] Customer feedback and support channels
- [ ] Backlog management tools and prioritization framework
- [ ] Weekly sync with PM and engineering leads schedule

### Project Managers
- [ ] Project charter and scope documentation
- [ ] Project board and tracking tools setup
- [ ] Risk register and escalation procedures
- [ ] Stakeholder communication plan and cadence
- [ ] Meeting facilitation responsibilities and schedules
- [ ] Key metrics and reporting templates

### Release Engineer
- [ ] CI/CD pipeline architecture and configuration
- [ ] Deployment procedures and runbooks
- [ ] Monitoring and alerting setup
- [ ] Rollback procedures and incident response
- [ ] Release calendar and change management process
- [ ] Key infrastructure and ops contacts

### Technical Writer
- [ ] Documentation structure and templates
- [ ] Publishing and review process
- [ ] Release notes and changelog procedures
- [ ] Key technical contacts and SMEs
- [ ] Documentation tools and platforms
- [ ] Accessibility and formatting standards

### UX Researcher
- [ ] Research methodologies and tools
- [ ] User testing and recruitment process
- [ ] Insights repository and findings documentation
- [ ] Stakeholder engagement and presentation skills
- [ ] Analytics and user behavior data access
- [ ] Research ethics and privacy requirements

### Support Liaison
- [ ] Support ticketing system and escalation procedures
- [ ] Customer communication standards and templates
- [ ] Issue prioritization and triage process
- [ ] Key customer contacts and account teams
- [ ] Product knowledge and troubleshooting guides
- [ ] Weekly trend analysis and reporting

### Security Champion
- [ ] Security policies, standards, and compliance requirements
- [ ] Threat modeling and architecture review process
- [ ] Vulnerability assessment and remediation procedures
- [ ] Security scanning tools and gates in the pipeline
- [ ] Incident response and escalation procedures
- [ ] Key security team contacts and on-call procedures

### Data Analyst
- [ ] Analytics platform and dashboard tools
- [ ] Success metrics and KPI definitions
- [ ] Data collection and instrumentation strategy
- [ ] Reporting schedule and stakeholder distribution
- [ ] Data privacy and compliance requirements
- [ ] Key analytics contacts and data science team

---

## How to Use These Personas in the Exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Key Interactions" section to understand cross-functional dependencies and communication patterns.
- Use the "When to Involve" guidance to know when to engage specific roles in project activities.
- Reference the "Onboarding Checklist" when bringing new team members into specific roles.
