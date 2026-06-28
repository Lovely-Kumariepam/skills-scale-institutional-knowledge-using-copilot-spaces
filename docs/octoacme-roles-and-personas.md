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
- **Technical Lead**: Receive architectural guidance and design feedback
- **QA/Testing Lead**: Collaborate on test strategy and acceptance criteria
- **Product Managers**: Align on requirements and acceptance criteria
- **DevOps/Infrastructure**: Coordinate on deployment readiness

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Gather customer feedback and iterate based on outcomes

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Key Interactions
- **Project Managers**: Coordinate schedules and dependencies
- **Developers/Technical Lead**: Discuss feasibility and technical trade-offs
- **QA/Testing Lead**: Define acceptance criteria and quality standards
- **UX/Design Lead**: Align on user experience and interaction patterns
- **Sponsor/Stakeholder**: Validate business alignment and success metrics

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
- Escalate blockers and manage dependencies

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Key Interactions
- **Sponsor/Stakeholder**: Report progress and escalate risks
- **Product Managers**: Align on scope and priorities
- **Scrum Master/Delivery Coordinator**: Facilitate process and remove blockers
- **All team roles**: Daily coordination and communications

---

## Technical & Quality Roles

### Technical Lead / Architect

#### Role Summary
Technical Leads provide architectural guidance, review designs for technical soundness, and help the team navigate complex technical decisions. They own technical risks and ensure solutions are scalable, maintainable, and aligned with long-term strategy.

#### Responsibilities
- Review technical designs and architecture decisions
- Identify technical risks and propose mitigations
- Mentor developers on design patterns and best practices
- Guide technology choices and trade-offs
- Ensure code quality and system maintainability standards
- Facilitate technical spikes and proofs of concept
- Advise on performance, security, and scalability concerns
- Collaborate on system design and integration points

#### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and future rework
- Build team capability and shared ownership of quality
- Enable teams to make confident technical decisions

#### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and mentoring conversations
- Risk register updates for technical risks
- Technology decision logs

#### Key Interactions
- **Developers**: Provide guidance, review designs, mentor on best practices
- **Product Managers**: Advise on feasibility and technical trade-offs
- **Project Managers**: Flag technical risks and dependencies
- **DevOps/Infrastructure**: Collaborate on deployment and operational readiness
- **QA/Testing Lead**: Align on testability and technical testing approach

---

### QA / Testing Lead

#### Role Summary
QA/Testing Leads own quality assurance strategy, establish testing standards, and ensure features meet acceptance criteria before release. They work closely with Product Managers and Developers to define testable requirements and validate delivery.

#### Responsibilities
- Define QA strategy and test plans for projects
- Establish testing standards (unit, integration, end-to-end, acceptance)
- Create and maintain acceptance criteria templates
- Perform and coordinate quality testing activities
- Identify quality risks and escalate blockers
- Validate that features meet Definition of Done before handoff
- Collaborate on security and performance testing
- Define test coverage expectations and metrics

#### Goals
- Ensure reliable, defect-free features reach production
- Reduce post-release issues and customer impact
- Establish predictable quality standards across projects
- Enable developers to catch issues early

#### Typical Communication
- Sprint planning and review sessions
- Test plan reviews and walkthroughs
- Quality metrics dashboards
- Incident retrospectives and root cause analysis

#### Key Interactions
- **Product Managers**: Review acceptance criteria, define what "done" looks like
- **Developers**: Collaborate on test strategy, review test coverage, identify edge cases
- **Project Managers**: Report quality metrics, flag testing delays or risks
- **Technical Lead**: Align on testing architecture and technical test approach
- **DevOps/Infrastructure**: Set up test environments and production verification

---

## Leadership & Support Roles

### UX / Design Lead

#### Role Summary
UX/Design Leads define user experience, interaction patterns, and design consistency. They collaborate with Product Managers and Developers to ensure solutions are intuitive, accessible, and aligned with brand standards.

#### Responsibilities
- Define user experience and interaction patterns
- Create wireframes, prototypes, and design specifications
- Conduct user research and usability testing
- Establish and maintain design systems and style guides
- Review feature designs for usability and consistency
- Collaborate on accessibility and inclusive design
- Guide visual design and user experience best practices

#### Goals
- Deliver intuitive, user-centric solutions
- Ensure consistent design experience across products
- Minimize user confusion and support burden
- Build accessibility into every feature

#### Typical Communication
- Design reviews and feedback sessions
- User research findings and insights
- Design specifications and component documentation
- Usability testing and iteration discussions

#### Key Interactions
- **Product Managers**: Align on user needs and feature priorities
- **Developers**: Collaborate on design implementation and feasibility
- **Project Managers**: Coordinate design timelines and milestones
- **QA/Testing Lead**: Validate user experience in acceptance testing

---

### DevOps / Infrastructure Engineer

#### Role Summary
DevOps engineers manage deployment pipelines, infrastructure provisioning, and operational readiness. They ensure systems can be deployed reliably, monitored effectively, and recovered quickly from incidents.

#### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure and environment configurations
- Implement monitoring, logging, and alerting
- Establish deployment best practices and runbooks
- Coordinate releases and manage rollback procedures
- Advise on infrastructure and scalability needs
- Ensure security scanning and compliance in deployment process
- Optimize system performance and cost efficiency

#### Goals
- Enable fast, reliable deployments with minimal risk
- Maintain high system availability and observability
- Reduce time-to-recovery during incidents
- Automate repetitive operational tasks

#### Typical Communication
- Release coordination and deployment planning
- Infrastructure requirements and capacity planning
- Post-deployment verification and runbooks
- Incident response and post-incident reviews

#### Key Interactions
- **Developers**: Collaborate on CI/CD setup and deployment readiness
- **Project Managers**: Coordinate release timing and deployment windows
- **QA/Testing**: Set up test environments and production verification
- **Technical Lead**: Align on scalability and operational architecture

---

### Sponsor / Stakeholder

#### Role Summary
Sponsors are business stakeholders and decision-makers who own the strategic need for a project and provide business context, resources, and approval. They represent customer or business interests and ensure projects deliver intended value.

#### Responsibilities
- Define business objectives and success metrics
- Approve project scope, timeline, and resource allocation
- Provide business context and customer insights
- Make go/no-go decisions at key gates
- Escalate risks and manage stakeholder expectations
- Measure and communicate business impact
- Ensure resource availability and organizational alignment

#### Goals
- Ensure projects deliver measurable business value
- Align team efforts with strategic priorities
- Minimize scope creep and out-of-scope work
- Enable quick, informed decision-making

#### Typical Communication
- Project initiation and kickoff
- Monthly stakeholder briefings
- Go/no-go decision gates
- Risk escalations and critical decisions

#### Key Interactions
- **Product Managers**: Align on business objectives and success metrics
- **Project Managers**: Receive regular status updates and escalations
- **Developers/Technical Lead**: Provide business context for trade-offs

---

### Scrum Master / Delivery Coordinator

#### Role Summary
Scrum Masters and Delivery Coordinators facilitate delivery processes, remove blockers, and maintain team health. They ensure ceremonies are effective, impediments are escalated promptly, and the team maintains a sustainable pace.

#### Responsibilities
- Facilitate sprint ceremonies (planning, standup, review, retrospective)
- Identify and remove team blockers and impediments
- Coach team members on Agile practices and principles
- Maintain project board and track work status
- Identify process improvements and bottlenecks
- Support team morale and psychological safety
- Escalate risks and dependencies to Project Manager

#### Goals
- Maintain team velocity and predictability
- Create a high-performing, collaborative team environment
- Reduce cycle time and time-to-value
- Enable continuous process improvement

#### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching and support
- Process improvement discussions and retrospectives
- Blocker escalations to Project Manager

#### Key Interactions
- **Project Managers**: Escalate blockers and process issues
- **All team members**: Remove impediments and facilitate collaboration
- **Technical Lead**: Address technical blockers and design concerns
- **Developers/QA**: Support skill development and team dynamics

---

## Role Interaction Map

```
                    ┌─── Sponsor/Stakeholder ───┐
                    │ (Business decisions)      │
                    │                           │
                    ▼                           ▼
    ┌────────────────────────────┐    ┌─────────────────┐
    │  Product Manager           │    │  Project Manager│
    │  (What to build)           │◄──►│  (When & How)   │
    └────────────────────────────┘    └─────────────────┘
                    │                           │
         ┌──────────┼───────────┐              │
         │          │           │              │
         ▼          ▼           ▼              ▼
    ┌──────────┐ ┌──────────┐ ┌────────┐  ┌────────────────┐
    │Developer │ │UX/Design │ │Tech    │  │Scrum Master/   │
    │          │ │Lead      │ │Lead    │  │Delivery Coord. │
    └──────────┘ └──────────┘ └────────┘  └────────────────┘
         │                          │
         │      ┌──────────────┐    │
         └─────►│QA/Test Lead  │◄───┘
                │              │
                └──────────────┘
                       │
                       ▼
                ┌──────────────────┐
                │DevOps/Infra Eng. │
                │(Deploy & Monitor)│
                └──────────────────┘
```

---

## How These Personas Are Used

- **In Project Initiation**: Identify which personas are needed for your project and confirm availability
- **In Project Planning**: Assign persona-specific responsibilities and define hand-offs
- **In Execution**: Use personas to clarify decision-making authority and communication protocols
- **In Risk Management**: Identify risks owned by specific personas and escalate appropriately
- **In Retrospectives**: Gather feedback from each persona to understand cross-functional satisfaction
- **In Copilot Spaces**: Use persona definitions as context to provide role-specific guidance and recommendations

---

## Key Principles for Cross-Functional Collaboration

1. **Clear Ownership** — Each task and decision has a clear owner or responsible persona
2. **Effective Hand-offs** — Information flows smoothly between personas with defined inputs/outputs
3. **Overlapping Accountability** — Roles collaborate rather than throw work over a wall
4. **Communication Standards** — Each persona has defined communication touchpoints and frequency
5. **Shared Success Metrics** — All personas understand and own the project's success criteria
