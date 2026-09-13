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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and acceptance validation. They ensure that all deliverables meet defined acceptance criteria and quality standards before release.

### Responsibilities
- Define test strategy and test plan for each sprint/release
- Create and maintain test cases and test scripts
- Execute manual testing when automated tests are insufficient
- Coordinate with Developers on CI/CD pipeline and test automation
- Validate acceptance criteria before marking items as Done
- Identify and log defects with clear reproduction steps
- Participate in UAT coordination with stakeholders

### Goals
- Prevent defects from reaching production
- Reduce time-to-quality through efficient testing practices
- Maintain test coverage above defined thresholds

### Interaction with Existing Roles
- **Developers**: Review PR test coverage, discuss testability concerns, execute smoke tests post-deployment
- **Product Managers**: Clarify acceptance criteria, validate feature behavior matches requirements
- **Project Managers**: Report quality metrics and blockers, coordinate testing timelines

### Typical Communication
- Sprint planning and test review meetings
- Defect reports and quality dashboards
- UAT coordination and test execution updates

---

## Technical Architect/Lead

### Role Summary
Technical Architects own the technical design, system integration, and technical feasibility analysis. They ensure solutions are scalable, maintainable, and align with organizational standards.

### Responsibilities
- Review and approve technical designs and architecture decisions
- Assess technical feasibility of proposed features
- Identify integration points and dependencies with other systems
- Define coding standards and architectural patterns
- Mentor developers on technical best practices
- Participate in technical risk assessment and mitigation
- Ensure compliance with security and performance requirements

### Goals
- Deliver technically sound solutions that scale with the business
- Reduce technical debt and maintainability issues
- Enable faster feature delivery through clear architectural guidance

### Interaction with Existing Roles
- **Developers**: Review technical designs, conduct architecture reviews, provide guidance on implementation
- **Product Managers**: Communicate technical constraints affecting scope and timeline
- **Project Managers**: Escalate technical risks and dependencies

### Typical Communication
- Architecture review meetings and design discussions
- Technical documentation and design decision records
- Technical spike assessments and feasibility studies

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors represent business interests and provide approval authority. They define success criteria and ensure the project aligns with business objectives.

### Responsibilities
- Define business objectives and success metrics
- Provide approval at key decision gates
- Allocate budget and resources
- Escalate business-level risks and blockers
- Communicate project status to executive leadership
- Validate that deliverables meet business requirements

### Goals
- Ensure project delivers expected business value
- Maintain stakeholder alignment and satisfaction
- Reduce scope creep and unmanaged changes

### Interaction with Existing Roles
- **Project Managers**: Provide business context, approvals, and escalation path
- **Product Managers**: Align on business strategy and success metrics
- **Developers**: Provide business context for design decisions

### Typical Communication
- Monthly stakeholder updates and steering committee meetings
- Go/no-go decision gates
- Executive dashboards and business impact reporting

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on agile practices. They ensure the team operates effectively within the defined process.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and help resolve team impediments
- Protect the team from external distractions
- Coach team members on agile principles and practices
- Track sprint velocity and help team improve predictability
- Update and maintain sprint backlog and burndown charts

### Goals
- Enable the team to work efficiently and collaboratively
- Improve sprint predictability and velocity over time
- Foster psychological safety and continuous improvement

### Interaction with Existing Roles
- **Project Managers**: Coordinate on scheduling and escalations
- **Developers**: Remove blocking issues, facilitate collaboration
- **Product Managers**: Coordinate sprint content and prioritization

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item tracking
- Velocity reporting and process improvement discussions

---

## Security Lead

### Role Summary
Security Leads ensure that security requirements, threat assessments, and compliance obligations are integrated throughout the project lifecycle. They partner with the team to build security into the solution.

### Responsibilities
- Conduct security threat assessment and identify requirements
- Define security acceptance criteria and testing requirements
- Review code and architecture for security vulnerabilities
- Coordinate security scanning and penetration testing
- Ensure compliance with organizational security policies
- Participate in incident response and post-incident reviews
- Maintain security documentation and lessons learned

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure compliance with regulatory and organizational requirements
- Build security awareness across the team

### Interaction with Existing Roles
- **Developers**: Review code changes, provide security guidance, discuss vulnerability remediation
- **Technical Architects**: Review architectural security decisions and threat models
- **Project Managers**: Escalate security blockers and risks
- **QA/Testing Leads**: Coordinate on security test cases and validation

### Typical Communication
- Security design reviews and threat modeling sessions
- Vulnerability reports and remediation tracking
- Security audit participation and compliance reporting

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional projects typically involve multiple personas; refer to "Interaction with Existing Roles" to understand collaboration patterns.
