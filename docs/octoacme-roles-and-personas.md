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

## QA / Testing

### Role Summary
QA and Testing engineers validate that features meet acceptance criteria and quality standards before release. They design test plans, execute tests, and report defects.

### Responsibilities
- Create and maintain test plans and test cases
- Execute manual and automated tests for new features and regression
- Report, triage, and track defects to resolution
- Define and uphold the Definition of Done from a quality perspective
- Collaborate with Developers on testability and CI/CD quality gates

### Goals
- Prevent defects from reaching production
- Increase automated test coverage over time
- Provide fast, reliable feedback to the delivery team

### Typical Communication
- Daily standups and sprint planning sessions
- Bug reports and test result summaries
- Release readiness sign-off before deployment

### Interactions
- Works closely with **Developers** to clarify acceptance criteria and reproduce defects
- Coordinates with **Project Managers** on release readiness and deployment checklists
- Provides sign-off to **Product Managers** and **Stakeholders** before major releases
- Participates in sprint planning, demos, and retrospectives

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project outcome. They provide business requirements, approve decisions, and receive regular updates on project progress.

### Responsibilities
- Provide business requirements and constraints
- Review and approve key deliverables (one-pager, release notes, major changes)
- Participate in milestone reviews and demos
- Escalate business-critical concerns to the project team

### Goals
- Ensure the project delivers expected business value
- Maintain visibility into progress and risks
- Enable timely decisions when trade-offs arise

### Typical Communication
- Monthly status updates and milestone reviews
- Release notes and announcements
- Escalation notifications for high-impact risks

### Interactions
- Receives status reports and risk updates from **Project Managers**
- Aligns on product direction with **Product Managers**
- Reviews demo outputs from **Developers** and **QA/Testing**
- Consulted during project initiation, planning gates, and release approvals

---

## UX Designer

### Role Summary
UX Designers are responsible for the user experience across OctoAcme products. They research user needs, create wireframes and prototypes, and work with Developers to deliver intuitive interfaces.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define user flows, interaction patterns, and visual standards
- Collaborate with Developers on implementation of designs
- Maintain and evolve the design system and component library

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce user friction and support adoption of new features
- Ensure designs are feasible within engineering constraints

### Typical Communication
- Design reviews and critiques with Developers and Product Managers
- Usability test findings shared in sprint reviews and planning
- Design handoff notes and annotated mockups

### Interactions
- Partners closely with **Developers** during sprint execution to answer design questions and review implementations
- Aligns on feature scope and priorities with **Product Managers** during planning and backlog refinement
- Presents prototypes and usability findings to **Stakeholders** at milestone reviews
- Collaborates with **QA/Testing** to define acceptance criteria covering UX quality
- Participates in sprint planning, standups, and retrospectives

---

## DevOps Engineer

### Role Summary
DevOps Engineers design and maintain the infrastructure, CI/CD pipelines, and operational processes that enable reliable, repeatable software delivery at OctoAcme.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage infrastructure-as-code (IaC) and cloud environments
- Monitor system health, availability, and performance
- Implement security controls and scanning in the delivery pipeline
- Support incident response and drive post-mortem improvements

### Goals
- Enable fast, reliable, and safe deployments
- Reduce mean time to recovery (MTTR) for production incidents
- Automate repetitive operational tasks to free up engineering time

### Typical Communication
- Deployment readiness updates and release checklists
- Incident reports and post-mortem summaries
- Infrastructure change notifications to the delivery team

### Interactions
- Works with **Developers** to configure CI/CD and ensure builds are reproducible
- Coordinates with **Project Managers** on deployment windows, rollback plans, and the risk register
- Provides release readiness confirmation to **Product Managers** and **Stakeholders** before major releases
- Collaborates with **QA/Testing** on environment setup and automated test pipelines
- Participates in release planning, standups, and retrospectives; leads deployment steps in the release checklist

---

## Data Analyst

### Role Summary
Data Analysts collect, analyze, and interpret project and product data to support decision-making at OctoAcme. They translate raw metrics into actionable insights for the team and stakeholders.

### Responsibilities
- Define and instrument success metrics identified in the Project One-pager
- Build and maintain dashboards and reports for key signals
- Analyze user behavior, product performance, and project velocity
- Identify trends, anomalies, and improvement opportunities
- Present findings in stakeholder updates and sprint reviews

### Goals
- Enable data-driven prioritization and decision-making
- Surface leading indicators of risk or quality issues early
- Provide clear, accessible metrics to all team members

### Typical Communication
- Dashboard links and metric summaries in weekly status updates
- Findings presented at sprint reviews and stakeholder briefings
- Ad-hoc analysis for specific decisions or escalations

### Interactions
- Partners with **Product Managers** to define and refine success metrics during planning
- Supports **Project Managers** with velocity data, burndown charts, and risk register insights
- Delivers insights to **Stakeholders** during monthly updates and release reviews
- Works with **Developers** and **DevOps Engineers** to instrument features and ensure data pipelines are reliable
- Participates in sprint planning, retrospectives, and release reviews

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical delivery at OctoAcme. They elicit and document requirements, model processes, and ensure the delivered solution meets business objectives.

### Responsibilities
- Elicit, document, and validate business requirements with stakeholders
- Create process models, user stories, and acceptance criteria
- Facilitate requirements workshops and backlog refinement sessions
- Analyze gaps between current and desired business processes
- Support UAT (User Acceptance Testing) and requirements sign-off

### Goals
- Ensure technical solutions align with business goals and user needs
- Reduce ambiguity in requirements to minimize rework
- Act as a liaison between business stakeholders and the delivery team

### Typical Communication
- Requirements documentation (user stories, process maps, use cases)
- Backlog refinement sessions with Developers and Product Managers
- UAT plans and sign-off reports for Stakeholders

### Interactions
- Works closely with **Stakeholders** to capture and validate business requirements
- Partners with **Product Managers** to translate requirements into a prioritized backlog
- Collaborates with **Developers** and **QA/Testing** to clarify acceptance criteria and support test case design
- Supports **Project Managers** with scope documentation and decision logs
- Participates in project initiation, planning, sprint planning, standups, and retrospectives

---

## Role-to-Lifecycle Phase Mapping

The table below shows which roles are **Primary** (core accountability) vs **Supporting** (contributing or consulted) at each lifecycle phase.

| Role | Initiation | Planning | Execution | Release | Retrospective |
|------|-----------|----------|-----------|---------|---------------|
| Project Manager | Primary | Primary | Primary | Primary | Primary |
| Product Manager | Primary | Primary | Supporting | Supporting | Supporting |
| Developers | Supporting | Supporting | Primary | Primary | Supporting |
| QA / Testing | Supporting | Supporting | Primary | Primary | Supporting |
| Stakeholders | Primary | Supporting | Supporting | Primary | Supporting |
| UX Designer | Supporting | Primary | Primary | Supporting | Supporting |
| DevOps Engineer | Supporting | Supporting | Primary | Primary | Supporting |
| Data Analyst | Supporting | Supporting | Supporting | Primary | Primary |
| Business Analyst | Primary | Primary | Supporting | Supporting | Supporting |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

