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

## Release Manager

### Role Summary
Release Managers oversee the release lifecycle, ensuring cross-team readiness and coordinating go-live activities. They act as the central point of coordination for all release-related activities and ensure smooth deployments.

### Responsibilities
- Plan and schedule release windows across teams and environments
- Coordinate go/no-go decisions with stakeholders
- Ensure all pre-release requirements are met (tests, docs, approvals)
- Facilitate release readiness reviews and deployment activities
- Manage release communications and stakeholder notifications
- Coordinate rollback procedures when needed
- Maintain release documentation and post-deployment verification

### Goals
- Execute zero-downtime, predictable releases
- Minimize deployment risks through thorough preparation
- Ensure clear communication and alignment during releases
- Maintain release quality and compliance standards

### Typical Communication
- Release readiness meetings with Project Managers and Developers
- Go-live coordination with QA and operations teams
- Release status updates to Stakeholder Representatives
- Post-deployment reports and metrics
- Incident coordination during deployment issues

### Interactions with Other Roles
- **Project Manager**: Aligns on release timelines, dependencies, and risk mitigation
- **Developers**: Coordinates code freeze, deployment preparation, and technical readiness
- **QA/Testing**: Validates test completion and acceptance criteria before release
- **Stakeholder Representative**: Communicates release schedules, impacts, and status updates
- **Risk Coordinator**: Reviews release risks and ensures mitigation plans are in place

---

## Risk Coordinator

### Role Summary
Risk Coordinators monitor risk registers, facilitate risk discussions, and support mitigation planning with teams. They ensure risks are identified early, properly assessed, and actively managed throughout the project lifecycle.

### Responsibilities
- Maintain and update the project risk register
- Facilitate risk identification sessions during planning and execution
- Assess risk impact, likelihood, and priority
- Track mitigation actions and ownership
- Escalate high-priority risks to Project Managers and stakeholders
- Report on risk trends and emerging threats
- Support teams in developing contingency plans

### Goals
- Identify risks before they become issues
- Ensure all risks have clear owners and mitigation plans
- Maintain transparency around project uncertainties
- Reduce the impact of realized risks through proactive planning

### Typical Communication
- Weekly risk review sessions with Project Managers
- Risk assessment workshops during project initiation
- Escalation reports for high-priority risks
- Risk status updates in project dashboards
- Cross-team risk dependency discussions

### Interactions with Other Roles
- **Project Manager**: Provides risk insights to inform planning and decision-making
- **Developers**: Identifies technical risks and validates mitigation approaches
- **Product Manager**: Ensures business and market risks are considered
- **Release Manager**: Coordinates on deployment risks and go-live readiness
- **Stakeholder Representative**: Communicates risk exposure and mitigation progress

---

## Stakeholder Representative

### Role Summary
Stakeholder Representatives channel priorities and feedback from external stakeholders, ensuring alignment and transparency between the project team and business stakeholders. They act as the primary liaison for stakeholder engagement.

### Responsibilities
- Gather and communicate stakeholder requirements and priorities
- Facilitate stakeholder alignment and buy-in for project decisions
- Represent stakeholder interests in planning and prioritization
- Manage stakeholder expectations throughout the project lifecycle
- Coordinate stakeholder communications and updates
- Gather feedback and validate solution alignment
- Escalate stakeholder concerns to appropriate team members

### Goals
- Ensure stakeholder needs are understood and addressed
- Maintain stakeholder engagement and satisfaction
- Foster transparency and trust with external stakeholders
- Align project outcomes with business objectives

### Typical Communication
- Regular stakeholder updates and briefings
- Feedback sessions and requirements gathering meetings
- Status reports and milestone communications
- Escalation of stakeholder concerns to Project Managers
- Collaborative sessions with Product Managers on priorities

### Interactions with Other Roles
- **Product Manager**: Collaborates on prioritization and validates solutions against stakeholder needs
- **Project Manager**: Provides stakeholder insights for planning and risk management
- **Release Manager**: Receives release updates to communicate to stakeholders
- **Developers**: Channels feedback on technical solutions and user experience
- **Risk Coordinator**: Communicates stakeholder concerns related to risks

---

## Agile Coach

### Role Summary
Agile Coaches guide teams in applying agile practices, address process bottlenecks, and champion continuous improvement. They help teams maximize their effectiveness through better collaboration, ceremonies, and workflows.

### Responsibilities
- Facilitate agile ceremonies (standups, retrospectives, planning)
- Coach teams on agile principles and best practices
- Identify and remove process impediments
- Support teams in refining workflows and improving velocity
- Foster a culture of continuous improvement and learning
- Guide teams through agile transformations or process changes
- Measure team health and effectiveness metrics

### Goals
- Improve team velocity and predictability
- Enhance collaboration and communication within teams
- Build self-organizing, high-performing teams
- Embed continuous improvement as a team habit

### Typical Communication
- Daily facilitation of standups and team ceremonies
- One-on-one coaching sessions with team members
- Retrospective facilitation and action item tracking
- Process improvement workshops
- Team health assessments and feedback sessions

### Interactions with Other Roles
- **Project Manager**: Collaborates on process improvements and team effectiveness
- **Developers**: Coaches on technical practices and workflow optimization
- **Product Manager**: Ensures product planning aligns with team capacity and agile practices
- **QA/Testing**: Supports integration of testing into agile workflows
- **All Roles**: Facilitates cross-functional collaboration and removes blockers

---

## Cross-Role Collaboration Examples

### Release Coordination Scenario
The **Release Manager** works with **QA** to ensure all acceptance criteria are met and tests pass before deployment. They coordinate with the **Stakeholder Representative** to communicate release timing and potential impacts. The **Risk Coordinator** reviews the deployment risk assessment with the Release Manager to ensure mitigation plans are ready.

### Risk Management Scenario
The **Risk Coordinator** supports the **Project Manager** and team leads in identifying risks during sprint planning. When a high-priority technical risk is identified, the Risk Coordinator works with **Developers** to document mitigation options and tracks the action items. The **Stakeholder Representative** is kept informed of risks that may impact stakeholder commitments.

### Process Improvement Scenario
The **Agile Coach** facilitates a retrospective where the team identifies communication gaps during releases. They collaborate with the **Release Manager** to improve the release checklist and work with the **Project Manager** to adjust the communication cadence. Action items are tracked and reviewed in subsequent retrospectives.

### Stakeholder Alignment Scenario
The **Stakeholder Representative** gathers feedback from business stakeholders about a proposed feature change. They work with the **Product Manager** to validate whether the change aligns with the product vision and priorities. The **Project Manager** is consulted to assess schedule and resource impacts before the team commits to the change.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

