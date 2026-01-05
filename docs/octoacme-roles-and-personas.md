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
- **Product Manager**: Collaborates on feature requirements, clarifies acceptance criteria, and provides technical feasibility input during backlog refinement.
- **Project Manager**: Provides estimates, reports on progress, and escalates technical risks or blockers that impact timelines.
- **Scrum Master**: Works with Scrum Master to identify and resolve impediments, participate in retrospectives, and improve team processes.
- **UX Designer**: Implements design specifications, provides feedback on technical constraints, and ensures responsive and accessible front-end implementation.
- **QA Lead**: Collaborates on test coverage, fixes reported bugs, and ensures code meets quality standards and acceptance criteria.
- **Technical Writer**: Reviews documentation for technical accuracy, provides input on API design, and ensures code is well-documented.

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
- **Developers**: Partners on feature scoping, prioritization, and trade-off decisions. Reviews technical designs and validates that implementations meet user needs.
- **Project Manager**: Aligns on roadmap timelines, milestone dependencies, and communicates priority changes or scope adjustments.
- **Scrum Master**: Works together on backlog refinement, sprint goals, and ensuring user stories are ready for development with clear acceptance criteria.
- **UX Designer**: Collaborates closely on user research, validates design solutions against product strategy, and ensures features deliver intended user value.
- **QA Lead**: Defines acceptance criteria together, reviews test coverage, and validates that quality metrics align with product success metrics.
- **Technical Writer**: Coordinates on feature documentation, release notes, and ensures user-facing content aligns with product positioning and messaging.

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
- **Product Manager**: Coordinates on roadmap delivery, manages timeline expectations, and facilitates trade-off discussions between scope, time, and resources.
- **Developers**: Tracks progress, manages dependencies, and removes organizational blockers that impact delivery.
- **Scrum Master**: Partners on process execution, shares responsibility for team health, and collaborates on retrospective action items. PM focuses on project-level coordination while Scrum Master focuses on team-level facilitation.
- **UX Designer**: Coordinates design milestones within project timeline and ensures design deliverables are sequenced appropriately with development.
- **QA Lead**: Manages quality risks, coordinates testing timelines, and ensures adequate testing time is allocated in project schedule.
- **Technical Writer**: Tracks documentation deliverables as part of release checklist and ensures documentation is ready for product launch.

---

## Scrum Master

### Role Summary
Scrum Masters facilitate Agile ceremonies, remove blockers, and drive continuous process improvements. They coach teams on Agile practices and ensure the team follows agreed-upon workflows while fostering a culture of transparency and collaboration.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Remove impediments and blockers that prevent the team from making progress
- Coach the team on Agile practices and self-organization
- Shield the team from external interruptions and scope changes
- Track and improve team velocity and sprint metrics
- Foster collaboration between Product Managers, Developers, and stakeholders
- Identify and drive process improvements based on retrospective feedback

### Goals
- Maximize team productivity and flow
- Ensure adherence to Agile principles and agreed-upon processes
- Create a psychologically safe environment for feedback and improvement
- Continuously reduce cycle time and improve predictability

### Typical Communication
- Facilitate daily standups and sprint ceremonies
- Weekly metrics reviews with Project Manager and Product Manager
- Regular one-on-ones with team members to identify blockers
- Document and track impediments in issue tracker

### Interactions with Other Roles
- **Project Manager**: Collaborates on risk management, timeline coordination, and stakeholder communication. Scrum Master focuses on team-level execution while PM handles broader project coordination and reporting.
- **Product Manager**: Works closely to ensure backlog clarity and prioritization. Helps PM refine user stories and acceptance criteria for sprint readiness.
- **Developers**: Coaches on Agile practices, facilitates technical discussions, and removes blockers to maintain steady delivery pace.
- **QA Lead**: Coordinates sprint testing activities and ensures quality gates are integrated into the Definition of Done.

---

## UX Designer

### Role Summary
UX Designers create user-centered designs, wireframes, and prototypes that translate product requirements into intuitive user experiences. They validate design decisions through user research and usability testing to ensure product-market fit.

### Responsibilities
- Design user flows, wireframes, and high-fidelity mockups
- Conduct user research, interviews, and usability testing
- Create and maintain design systems and component libraries
- Collaborate with Product Managers to translate requirements into design solutions
- Work with Developers to ensure design feasibility and implementation fidelity
- Validate designs through A/B testing and user feedback
- Advocate for accessibility and inclusive design practices

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and improve satisfaction metrics
- Ensure design consistency across product features
- Balance user needs with technical constraints and business goals

### Typical Communication
- Design review sessions with Product Manager and stakeholders
- Weekly sync with Developers on implementation progress
- User research findings and usability test results presentations
- Design specifications and handoff documentation

### Interactions with Other Roles
- **Product Manager**: Partners closely to understand user problems and success metrics. Translates product vision into tangible design solutions and validates through user research.
- **Developers**: Collaborates on design feasibility, component implementation, and responsive design. Provides design specs, assets, and participates in implementation reviews.
- **QA Lead**: Works together to define user acceptance criteria and validates that implemented features match design specifications and usability standards.
- **Project Manager**: Aligns on design milestones, dependencies, and timeline for design deliverables within project schedule.

---

## QA Lead

### Role Summary
QA Leads define and maintain quality standards, coordinate testing activities, and ensure that features meet acceptance criteria before release. They establish quality processes that integrate throughout the development lifecycle.

### Responsibilities
- Define quality standards and testing strategy for projects
- Create and maintain test plans, test cases, and automation frameworks
- Coordinate manual and automated testing activities across features
- Review acceptance criteria and Definition of Done with Product and Project Managers
- Manage bug triage, severity classification, and resolution tracking
- Integrate quality gates into CI/CD pipelines
- Conduct exploratory testing and regression testing before releases
- Provide quality metrics and testing status reports

### Goals
- Ensure features meet acceptance criteria and quality standards
- Reduce production defects and customer-reported issues
- Improve test coverage and automation effectiveness
- Minimize time between code complete and release

### Typical Communication
- Daily standup participation and testing status updates
- Test plan reviews with Product Manager and Developers
- Bug triage sessions and severity discussions
- Weekly quality metrics reports to Project Manager and stakeholders

### Interactions with Other Roles
- **Developers**: Collaborates on testability, reviews acceptance criteria, participates in code reviews for quality perspective. Partners on test automation and bug fixes.
- **Product Manager**: Works together to understand acceptance criteria, edge cases, and success metrics. Provides input on feature quality and readiness for release.
- **Project Manager**: Reports on testing progress, quality risks, and release readiness. Coordinates testing timelines and resource needs.
- **Scrum Master**: Partners on integrating quality practices into sprint workflow and Definition of Done. Escalates testing blockers and process improvements.
- **UX Designer**: Validates that implemented features match design specifications and provides feedback on usability issues discovered during testing.

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate documentation for products, APIs, and internal processes. They ensure documentation stays current, accessible, and useful for diverse audiences including developers, end-users, and stakeholders.

### Responsibilities
- Author and update product documentation, API references, and user guides
- Maintain process documentation and runbooks for team operations
- Collaborate with Developers to document new features and changes
- Review and edit technical content for clarity, accuracy, and consistency
- Manage documentation versioning and release notes
- Ensure documentation accessibility and searchability
- Gather feedback and iterate on documentation quality

### Goals
- Provide clear, accurate documentation that reduces support burden
- Ensure documentation stays synchronized with product changes
- Improve documentation discoverability and user self-service
- Maintain consistent voice, style, and terminology across all docs

### Typical Communication
- Weekly sync with Product Manager and Developers on upcoming features
- Documentation reviews with subject matter experts
- Release notes and changelog updates for each release
- Feedback collection from documentation users

### Interactions with Other Roles
- **Developers**: Works closely to understand technical changes, review code comments, and create accurate API documentation and integration guides.
- **Product Manager**: Collaborates on feature documentation, user guides, and release communications. Ensures documentation aligns with product positioning.
- **Project Manager**: Aligns on documentation deliverables, milestones, and ensures documentation is part of release checklists.
- **QA Lead**: Partners on test documentation, known issues, and validation of documentation accuracy through testing scenarios.
- **UX Designer**: Coordinates on user-facing help content, tooltips, and ensures documentation matches UI terminology and flows.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For collaboration scenarios and cross-functional accountability, refer to [Persona Collaboration Checklist](persona-collaboration-checklist.md).

