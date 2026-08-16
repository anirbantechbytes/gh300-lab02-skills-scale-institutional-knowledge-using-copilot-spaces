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
- **Technical Architect**: Receives design guidance and architecture standards; participates in design reviews
- **QA/Testing Lead**: Collaborates on test coverage and acceptance criteria clarity
- **DevOps/Release Engineer**: Coordinates on deployment and infrastructure concerns
- **Product Managers**: Receives requirements and acceptance criteria
- **Project Managers**: Participates in sprint planning and risk identification

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
- **Technical Architect**: Discusses trade-offs between features and technical constraints
- **QA/Testing Lead**: Aligns on acceptance criteria and quality standards
- **Business Analyst**: Collaborates on requirement clarity and stakeholder inputs
- **Stakeholder/Sponsor**: Communicates on strategic alignment and priority decisions
- **Project Managers**: Works closely on planning, scope, and timeline management

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
- **Scrum Master/Agile Coach**: Coordinates on sprint ceremonies and team process improvements
- **DevOps/Release Engineer**: Coordinates release timelines and deployment planning
- **Stakeholder/Sponsor**: Escalates risks and provides progress updates
- **Technical Architect**: Identifies technical dependencies and architectural risks
- **Business Analyst**: Clarifies scope and gathers requirement changes

---

## Technical Architect

### Role Summary
The Technical Architect leads technical design and system-level decisions, ensuring that solutions are scalable, maintainable, and aligned with organizational standards. They collaborate with Product Managers, Developers, and DevOps to make trade-off decisions that balance technical debt, feature velocity, and system reliability.

### Responsibilities
- Design system architecture and technical approaches for significant initiatives
- Review technical designs and PRs for architectural consistency
- Assess technical risks and propose mitigation strategies
- Define technical standards and best practices for the team
- Support sprint planning by identifying architectural dependencies
- Mentor developers on architectural patterns and design principles
- Collaborate with Security Lead on architecture security reviews

### Goals
- Maintain system integrity and long-term maintainability
- Enable rapid feature delivery without accumulating technical debt
- Ensure scalability and reliability of critical systems
- Reduce rework due to architectural misalignment

### Typical Communication
- Technical design reviews during sprint planning
- Architecture decision records (ADRs) and design docs
- Weekly sync with PM and Dev leads on trade-off decisions
- Code review comments on architectural concerns

### Interactions with Other Roles
- **Developers**: Provides architectural guidance and reviews implementations
- **Product Managers**: Discusses feasibility and trade-offs between features and technical constraints
- **DevOps/Release Engineer**: Ensures architecture supports deployment and infrastructure requirements
- **Security Lead**: Collaborates on security-by-design and threat assessment
- **Project Managers**: Identifies architectural dependencies and integration risks
- **QA/Testing Lead**: Discusses testability and architectural validation strategies

---

## QA/Testing Lead

### Role Summary
The QA/Testing Lead defines and executes the testing strategy, ensuring quality standards are met before release. They collaborate with Product Managers on acceptance criteria clarity and with Developers on testability, and own end-to-end QA coordination.

### Responsibilities
- Define testing strategy and test plans for each release
- Create and maintain test cases aligned with acceptance criteria
- Lead manual and automated testing activities
- Identify quality gaps and propose improvements
- Collaborate on acceptance criteria clarity with Product Managers
- Manage bug triage and severity assessment
- Ensure smoke tests and critical path validation before release
- Coordinate with DevOps on test environment setup and deployment validation

### Goals
- Deliver quality features that meet acceptance criteria
- Reduce production defects and post-release rework
- Enable confident, low-risk releases
- Build testing culture and shared quality ownership

### Typical Communication
- QA checkpoints in weekly delivery syncs
- Test plans and bug reports in project tracking systems
- Pre-release QA readiness assessments
- Acceptance criteria refinement sessions with Product Managers

### Interactions with Other Roles
- **Developers**: Collaborates on test coverage, testability, and bug fixes
- **Product Managers**: Aligns on acceptance criteria clarity and quality expectations
- **Technical Architect**: Discusses testing strategy for complex architectural components
- **DevOps/Release Engineer**: Coordinates on test environment setup and release validation
- **Project Managers**: Updates on quality risks and release readiness
- **Business Analyst**: Clarifies user stories and acceptance criteria for testing

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master (or Agile Coach) facilitates team ceremonies, removes blockers, and coaches the team on agile practices and continuous improvement. They act as a servant leader, enabling the team to self-organize and deliver value incrementally.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove impediments and blockers that prevent team progress
- Coach the team on agile principles and practices
- Monitor team velocity and sprint health
- Support continuous improvement and retrospective action items
- Maintain and optimize the development workflow
- Help teams manage scope creep and prioritize effectively

### Goals
- Enable high-performing, self-organizing teams
- Maximize team velocity and delivery consistency
- Foster psychological safety and continuous learning
- Reduce time-to-delivery through process optimization

### Typical Communication
- Daily standups (15 min timebox)
- Sprint planning and retrospective facilitation
- One-on-ones with team members to support coaching
- Process improvement discussions and action item tracking

### Interactions with Other Roles
- **Project Managers**: Coordinates on sprint planning and risk escalation
- **Developers**: Coaches on agile practices; removes technical blockers
- **Product Managers**: Facilitates backlog refinement and prioritization sessions
- **QA/Testing Lead**: Ensures quality practices are integrated into sprint definition of done
- **Technical Architect**: Facilitates technical design discussions and architecture reviews
- **Team Members**: Provides coaching and removes interpersonal or process blockers

---

## Business Analyst

### Role Summary
The Business Analyst bridges stakeholder requirements with technical implementation. They clarify needs, document acceptance criteria, and ensure that solutions solve the actual business problem. They collaborate closely with Product Managers, Developers, and stakeholders to align on scope and outcomes.

### Responsibilities
- Gather and document business requirements from stakeholders
- Clarify ambiguous requirements and identify gaps
- Write detailed acceptance criteria for user stories
- Create requirement traceability matrices and impact assessments
- Identify dependencies and integration points with other systems
- Validate solutions against original business needs
- Support scope management and change control

### Goals
- Ensure solutions address actual business problems
- Reduce rework due to unclear or misaligned requirements
- Enable early identification of scope and integration risks
- Build strong shared understanding between business and technical teams

### Typical Communication
- Stakeholder interviews and requirement elicitation sessions
- User story and acceptance criteria documentation
- Requirement review and sign-off with stakeholders
- Scope and change control discussions with Project Managers

### Interactions with Other Roles
- **Product Managers**: Collaborates on priority and acceptance criteria; validates strategic fit
- **Developers**: Clarifies requirements and acceptance criteria during sprint planning
- **Project Managers**: Identifies scope changes and integration risks
- **Stakeholders/Sponsors**: Gathers requirements and validates solutions
- **QA/Testing Lead**: Works on test case design and acceptance criteria verification
- **Technical Architect**: Discusses feasibility and technical constraints

---

## DevOps / Release Engineer

### Role Summary
The DevOps/Release Engineer owns deployment pipelines, infrastructure, and release coordination. They work with Developers, QA, and Project Managers to ensure smooth, reliable releases and maintain production systems. They enable fast, safe deployments and support incident response.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Coordinate production deployments and rollbacks
- Maintain infrastructure, monitoring, and observability
- Document deployment procedures and runbooks
- Support incident response and post-mortems
- Advise on security, compliance, and operational concerns in the design phase
- Manage test environments and infrastructure provisioning
- Implement infrastructure-as-code and deployment best practices

### Goals
- Enable fast, safe deployments with minimal risk
- Maintain high system availability and performance
- Reduce time-to-resolution for production issues
- Support continuous delivery and frequent releases

### Typical Communication
- Release coordination meetings
- Deployment readiness checklists and runbooks
- Incident response and post-mortems
- Infrastructure and operational health reviews

### Interactions with Other Roles
- **Developers**: Supports deployment troubleshooting and infrastructure requirements
- **QA/Testing Lead**: Coordinates test environment setup and release validation
- **Project Managers**: Coordinates release timelines and deployment planning
- **Technical Architect**: Aligns on infrastructure and scalability requirements
- **Security Lead**: Implements security controls and compliance requirements
- **Stakeholders/Sponsors**: Provides deployment readiness and incident updates

---

## Security Lead / InfoSec Representative

### Role Summary
The Security Lead ensures that OctoAcme projects follow security best practices, conduct threat assessments, and maintain compliance with security and regulatory standards. They collaborate with the Technical Architect, Developers, and DevOps to build security into the product from the start, rather than as an afterthought.

### Responsibilities
- Conduct threat assessments and risk analysis for new features or systems
- Review architectural designs and code for security vulnerabilities
- Define security requirements and acceptance criteria
- Advise on authentication, authorization, and data protection strategies
- Support security scanning in CI/CD pipelines
- Review third-party dependencies and compliance requirements
- Conduct security training and build security culture
- Lead incident response for security-related events

### Goals
- Build security into the design and development process
- Reduce security vulnerabilities and data breach risks
- Maintain compliance with regulatory and organizational standards
- Enable the team to ship secure, trustworthy software

### Typical Communication
- Security architecture reviews during design phase
- Security acceptance criteria in user stories
- Vulnerability assessments and remediation guidance
- Security incident response and post-mortems
- Regular security training and awareness sessions

### Interactions with Other Roles
- **Technical Architect**: Collaborates on security-by-design and threat modeling
- **Developers**: Reviews code for security vulnerabilities; provides secure coding guidance
- **Product Managers**: Discusses security requirements and compliance implications
- **DevOps/Release Engineer**: Ensures security controls in CI/CD and infrastructure
- **QA/Testing Lead**: Coordinates on security testing and penetration testing
- **Project Managers**: Escalates security risks and compliance deadlines

---

## Stakeholder / Sponsor

### Role Summary
The Stakeholder or Project Sponsor provides executive oversight, strategic alignment, and decision authority on project trade-offs. They represent business interests, ensure alignment with organizational strategy, and have the authority to approve scope, budget, and timeline changes.

### Responsibilities
- Define strategic business objectives and success metrics
- Approve project charter and business case
- Make trade-off decisions between scope, schedule, and resources
- Remove escalated blockers and organizational impediments
- Approve major scope changes and accept project risks
- Communicate project importance to the broader organization
- Review progress and provide strategic direction

### Goals
- Ensure projects deliver business value aligned with strategy
- Remove organizational barriers to project success
- Make timely, informed decisions to keep projects on track
- Maximize return on investment and stakeholder satisfaction

### Typical Communication
- Monthly or milestone-based executive status updates
- Major decision approvals and trade-off discussions
- Risk escalation and issue resolution
- Project review and strategic alignment meetings
- Budget and resource allocation decisions

### Interactions with Other Roles
- **Project Managers**: Receives status updates; escalates risks and major decisions
- **Product Managers**: Aligns on strategic priorities and business outcomes
- **Developers/Technical Leads**: Reviews technical feasibility for scope trade-offs
- **Business Analyst**: Validates business requirements and success metrics
- **Other Stakeholders**: Communicates with peers on cross-project impacts and dependencies

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When running projects, map your actual team members to these personas and use the defined responsibilities and interaction patterns to clarify expectations and communication.
