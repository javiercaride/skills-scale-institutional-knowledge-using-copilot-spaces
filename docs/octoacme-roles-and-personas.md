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

## QA/Testing

### Role Summary
QA/Testing validates quality and acceptance criteria through manual and automated testing. They ensure features meet specifications, catch regressions, and maintain product reliability.

### Responsibilities
- Execute test plans and document test cases
- Validate acceptance criteria for backlog items
- Report and track bugs through resolution
- Maintain automated test suites where applicable
- Support developers in reproducibility and root cause analysis

### Goals
- Ensure features meet quality standards before release
- Catch defects early in the development cycle
- Maintain comprehensive test coverage
- Reduce customer-reported issues

### Typical Communication
- Sprint planning for test scope and acceptance criteria
- Daily updates on test progress and blockers
- Bug reports and regression testing coordination
- QA sign-off before releases

---

## Stakeholders

### Role Summary
Stakeholders provide input, requirements, and approvals for projects. They represent business units, customers, or leadership perspectives and help align project outcomes with organizational goals.

### Responsibilities
- Provide business context and constraints
- Review and approve project charters and milestones
- Participate in key decision points and reviews
- Communicate organizational priorities and changes

### Goals
- Ensure projects align with business objectives
- Provide timely input and approvals
- Stay informed of project status and risks
- Support successful adoption of delivered solutions

### Typical Communication
- Monthly stakeholder updates and reviews
- Milestone approvals and decision gates
- Ad-hoc consultations on scope or priority changes
- Steering committee meetings for major initiatives

---

## UX/UI Designer

### Role Summary
UX/UI Designers ensure user-centric design and usability across product features. They create wireframes, prototypes, and design specifications that guide implementation and enhance user experience.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define design systems and UI component standards
- Validate design feasibility with developers
- Collaborate on accessibility and responsive design

### Goals
- Deliver intuitive, accessible user experiences
- Maintain design consistency across the product
- Reduce friction in user workflows
- Ensure designs are technically feasible

### Typical Communication
- Design reviews with Product Managers and developers
- Handoff documentation and design specifications
- Usability testing sessions and feedback synthesis
- Collaboration on acceptance criteria for UI features

### Key Interactions
- **Product Managers:** Collaborate on feature definition, user stories, and prioritization of UX improvements
- **Developers:** Provide design specifications, validate implementation, and iterate on technical constraints
- **QA/Testing:** Partner on usability validation and acceptance testing for design requirements

---

## DevOps Engineer

### Role Summary
DevOps Engineers own CI/CD pipelines, infrastructure management, and deployment automation. They enable reliable, repeatable releases and maintain the environments that support development and production systems.

### Responsibilities
- Build and maintain CI/CD pipelines
- Manage infrastructure-as-code and cloud resources
- Monitor deployments and system health
- Support automated testing environments
- Implement security best practices in deployment processes
- Respond to infrastructure incidents and performance issues

### Goals
- Minimize deployment friction and time-to-production
- Maintain high availability and reliability
- Automate repetitive operational tasks
- Ensure scalable, secure infrastructure

### Typical Communication
- Sprint planning for infrastructure and tooling needs
- Release coordination and deployment windows
- Incident response and post-mortem reviews
- Technical documentation for deployment processes

### Key Interactions
- **Developers:** Collaborate on environment requirements, build configurations, and deployment needs
- **QA/Testing:** Support test automation infrastructure and staging environment parity
- **Project Managers:** Coordinate release schedules and communicate infrastructure constraints
- **Security Lead:** Implement secure deployment practices and vulnerability remediation

---

## Security Lead

### Role Summary
Security Leads oversee security requirements, threat modeling, and vulnerability management. They ensure secure coding practices, guide incident response, and maintain the security posture of products and systems.

### Responsibilities
- Conduct threat modeling and security assessments
- Review code and dependencies for vulnerabilities
- Define security requirements and acceptance criteria
- Lead security incident response and remediation
- Provide security training and guidance to teams
- Maintain compliance with security policies and standards

### Goals
- Prevent security vulnerabilities from reaching production
- Minimize time-to-remediation for identified risks
- Foster security awareness across the team
- Ensure compliance with regulatory and organizational requirements

### Typical Communication
- Security reviews during planning and design phases
- Vulnerability reports and remediation tracking
- Incident response coordination and post-mortems
- Security training sessions and awareness updates

### Key Interactions
- **Developers:** Guide secure coding practices, review code for vulnerabilities, and support remediation
- **DevOps Engineer:** Coordinate secure deployment practices, infrastructure hardening, and monitoring
- **Project Managers:** Communicate critical security risks, timelines for remediation, and compliance requirements
- **QA/Testing:** Collaborate on security test scenarios and penetration testing

---

## Support/Customer Success

### Role Summary
Support/Customer Success representatives communicate with customers, gather feedback, and assist in resolving issues impacting users. They bridge the gap between customer needs and product development.

### Responsibilities
- Communicate release changes and new features to customers
- Gather and synthesize customer feedback
- Assist in reproducing and escalating customer-reported issues
- Track support trends and high-impact customer concerns
- Support customer onboarding and adoption

### Goals
- Ensure positive customer experience and satisfaction
- Reduce time-to-resolution for customer issues
- Provide actionable feedback to improve the product
- Support successful customer adoption of new features

### Typical Communication
- Customer-facing release notes and announcements
- Support ticket tracking and escalation
- Feedback synthesis for product planning
- Coordination with QA on field issue reproduction

### Key Interactions
- **Product Managers:** Relay customer feedback into roadmap prioritization and feature requests
- **QA/Testing:** Collaborate on reproducing field issues and validating fixes
- **Project Managers:** Inform of high-impact support trends and customer-facing release readiness
- **Developers:** Provide detailed bug reports and assist in issue reproduction

---

## Business Analyst

### Role Summary
Business Analysts analyze business needs, document requirements, and validate that solutions meet organizational goals. They support backlog grooming, requirement gathering, and bridge communication between business and technical teams.

### Responsibilities
- Analyze and document business requirements
- Support backlog grooming and requirement clarification
- Create process flows, use cases, and requirement specifications
- Validate solutions against business goals
- Facilitate workshops and requirement gathering sessions
- Track requirement changes and dependencies

### Goals
- Ensure clear, complete requirements for development
- Bridge communication between business and technical teams
- Validate solutions deliver intended business value
- Reduce rework from unclear or incomplete requirements

### Typical Communication
- Requirement workshops and stakeholder interviews
- Backlog refinement sessions
- Acceptance criteria definition and validation
- Business process documentation and change management

### Key Interactions
- **Product Managers:** Partner on requirement gathering, backlog prioritization, and success metrics
- **Project Managers:** Assist with prioritization, dependency analysis, and scope management
- **Developers:** Provide requirement clarifications, answer business logic questions, and validate implementations
- **Stakeholders:** Facilitate requirement elicitation and ensure alignment with business objectives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded set of personas ensures comprehensive cross-functional coverage and clarifies handoff points between teams.

