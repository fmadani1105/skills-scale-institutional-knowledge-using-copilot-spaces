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

## Stakeholders

### Role Summary
Stakeholders are internal or external parties with a vested interest in the project outcome. They provide requirements, approvals, and feedback throughout the project lifecycle.

### Responsibilities
- Provide business requirements and success criteria
- Review and approve key deliverables and milestones
- Raise concerns or changes in priority as needed
- Participate in demos and sign-off reviews

### Goals
- Ensure the project delivers measurable business or customer value
- Stay informed on progress, risks, and blockers
- Champion the project within the organization

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Ad-hoc escalations and approval requests
- Demo sessions and release announcements

---

## UX Designer

### Role Summary
Designs user experiences and interfaces, ensuring usability and accessibility standards are met across all product touchpoints.

### Responsibilities
- Conducts user research and usability testing
- Develops wireframes, prototypes, and visual assets
- Ensures design consistency across features
- Advocates for user-centered approaches
- Maintains a design system and style guide

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce usability issues before development begins
- Bridge the gap between user needs and technical implementation

### Typical Communication
- Design reviews and critique sessions
- Handoff documentation and annotated mockups
- Usability test reports shared with PdMs and Developers

### Interactions
- Collaborates with Product Managers to clarify user needs and acceptance criteria
- Works with Developers to implement designs faithfully
- Engages Stakeholders for feedback and design validation

---

## QA Lead

### Role Summary
Plans, coordinates, and ensures the quality of project deliveries by defining test strategies, overseeing test execution, and enforcing quality gates.

### Responsibilities
- Defines testing strategies and coverage requirements
- Manages manual and automated test execution
- Tracks and reports defects and their resolution
- Supports release readiness reviews
- Maintains test plans, test cases, and traceability matrices

### Goals
- Prevent defects from reaching production
- Ensure acceptance criteria are verifiable and verified
- Provide clear quality status at each milestone

### Typical Communication
- Test summary reports before releases
- Defect triage meetings with Developers
- Release readiness sign-off with Project Managers

### Interactions
- Coordinates with Developers for testable code and timely fixes
- Informs Project Managers on release quality status
- Helps Product Managers refine acceptance criteria

---

## DevOps Engineer

### Role Summary
Automates deployment, manages infrastructure, and ensures the reliability and security of development and production environments.

### Responsibilities
- Designs and maintains CI/CD pipelines
- Monitors and troubleshoots system health and performance
- Implements infrastructure-as-code
- Leads incident response and recovery procedures
- Manages cloud resources and access controls

### Goals
- Minimize deployment friction and time-to-production
- Maintain high availability and system reliability
- Enable the team with fast, safe deployment capabilities

### Typical Communication
- Infrastructure runbooks and deployment guides
- Incident reports and post-mortems
- Pipeline health dashboards and alerts

### Interactions
- Partners with Developers on deployment automation and environment setup
- Supports QA Lead with stable testing environments
- Communicates with Stakeholders during incidents and outages

---

## Data Analyst

### Role Summary
Provides data-driven insights to inform product decisions, track performance against goals, and validate outcomes post-release.

### Responsibilities
- Analyzes usage metrics and builds reports
- Advises on instrumentation, event tagging, and tracking plans
- Validates progress against KPIs and success metrics
- Summarizes learnings post-release and recommends next steps

### Goals
- Enable data-informed prioritization and decision-making
- Ensure success metrics are measurable and tracked
- Surface actionable insights to the broader team

### Typical Communication
- Weekly or milestone-based analytics reports
- KPI dashboards shared with PdMs and Stakeholders
- Ad-hoc analyses in response to product questions

### Interactions
- Works with Product Managers to define and track success metrics
- Supports Developers in implementing analytics and telemetry
- Shares insights with Stakeholders to demonstrate value and impact

---

## Role Interaction Table

The following table summarizes key interactions between all roles in an OctoAcme project.

| Role | Interacts With | Primary Touchpoints |
|---|---|---|
| Project Manager | All roles | Planning sessions, status updates, risk reviews, retrospectives |
| Product Manager | PM, Developers, UX Designer, Data Analyst, Stakeholders | Roadmap reviews, backlog grooming, acceptance criteria, KPI tracking |
| Developers | PM, PdM, QA Lead, DevOps Engineer, UX Designer | Sprint planning, code reviews, CI/CD pipelines, design handoffs |
| Stakeholders | PM, PdM, Data Analyst | Milestone reviews, demos, escalations, approvals |
| UX Designer | PdM, Developers, Stakeholders | Design reviews, prototype feedback, usability test results |
| QA Lead | PM, PdM, Developers, DevOps Engineer | Test planning, defect triage, release readiness reviews |
| DevOps Engineer | Developers, QA Lead, Stakeholders | Deployments, environment setup, incident response, pipeline health |
| Data Analyst | PdM, Developers, Stakeholders | Metric definition, instrumentation, post-release reports, KPI reviews |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When scoping a new project, use the Role Interaction Table to confirm all needed roles are assigned and handoffs are clear.

