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
Release Managers coordinate and oversee the release process from planning through deployment. They ensure releases are well-planned, properly communicated, and executed with minimal risk to production environments.

### Responsibilities
- Create and maintain release schedules and roadmaps
- Coordinate cross-team dependencies for releases
- Ensure all pre-release requirements are met (testing, documentation, approvals)
- Manage deployment execution and post-release verification
- Facilitate release planning meetings and go/no-go decisions
- Maintain release documentation and retrospectives

### Goals
- Achieve predictable, low-risk releases
- Minimize production incidents and rollbacks
- Improve release velocity and automation
- Maintain clear release visibility across stakeholders

### Interactions with Other Roles
- **Product Managers**: Align release content with product roadmap and priorities
- **Project Managers**: Coordinate timelines, dependencies, and resource allocation
- **Developers**: Collaborate on release readiness, feature flags, and rollback plans
- **QA Lead**: Ensure testing is complete and quality gates are met
- **Communications Liaison**: Coordinate release announcements and stakeholder updates

### Communication Channels
- Release planning meetings (bi-weekly or as needed)
- Release status updates via project boards and email
- Go/no-go meetings before major releases
- Post-release retrospectives

### Escalation Paths
- Technical issues → Lead Developer or Engineering Manager
- Schedule conflicts → Project Manager → Product Lead
- Quality concerns → QA Lead → Engineering Manager
- Production incidents → Incident Commander → Engineering on-call

---

## QA Lead

### Role Summary
QA Leads define and implement quality assurance strategies, ensuring that features meet acceptance criteria and maintain high quality standards before release. They lead testing efforts and advocate for quality throughout the development lifecycle.

### Responsibilities
- Define testing strategy and quality standards
- Create and maintain test plans and test cases
- Lead QA team activities and prioritize testing efforts
- Coordinate integration, regression, and acceptance testing
- Report on quality metrics and testing coverage
- Identify and track defects through resolution
- Advocate for testability and automation improvements

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and quality metrics
- Reduce cycle time for testing activities
- Foster a culture of quality across the team

### Interactions with Other Roles
- **Developers**: Collaborate on testability, automation, and defect resolution
- **Product Managers**: Validate acceptance criteria and feature completeness
- **Project Managers**: Report testing status and flag quality risks
- **Release Manager**: Provide go/no-go recommendations based on quality gates
- **Metrics Analyst**: Share quality metrics and testing data

### Communication Channels
- Daily standups for test status updates
- Weekly quality reports and metrics reviews
- Test plan reviews during sprint planning
- Defect triage meetings as needed

### Escalation Paths
- Critical defects → Development Lead → Engineering Manager
- Quality risks blocking release → Release Manager → Product Lead
- Resource constraints → Project Manager → Engineering Manager

---

## Communications Liaison

### Role Summary
Communications Liaisons manage internal and external communications for projects, ensuring consistent messaging, timely updates, and effective stakeholder engagement. They bridge the gap between technical teams and various audiences.

### Responsibilities
- Develop and execute communications plans for projects
- Craft and distribute project updates, announcements, and release notes
- Coordinate stakeholder communications and manage expectations
- Ensure consistent messaging across channels and audiences
- Gather and communicate feedback from stakeholders
- Maintain communication templates and documentation
- Facilitate information sharing across teams

### Goals
- Ensure all stakeholders are informed and aligned
- Reduce communication gaps and misunderstandings
- Increase transparency and trust
- Streamline information flow across the organization

### Interactions with Other Roles
- **Project Managers**: Collaborate on status updates and stakeholder management
- **Product Managers**: Align messaging with product vision and value proposition
- **Release Manager**: Coordinate release announcements and deployment communications
- **All team members**: Gather updates and translate technical details for various audiences
- **External stakeholders**: Manage expectations and provide regular updates

### Communication Channels
- Weekly stakeholder update emails
- Project status dashboards and reports
- Release announcements via email, chat, and documentation
- Regular sync meetings with PM and PdM

### Escalation Paths
- Sensitive communications → Product Manager → Executive Sponsor
- Crisis communications → Incident Commander → PR/Communications team
- Stakeholder concerns → Project Manager → Product Lead

---

## Onboarding Coordinator

### Role Summary
Onboarding Coordinators design and facilitate the onboarding experience for new team members, ensuring they quickly become productive contributors. They maintain onboarding materials, coordinate training, and track onboarding progress.

### Responsibilities
- Develop and maintain onboarding documentation and checklists
- Coordinate orientation sessions and training activities
- Assign mentors and facilitate buddy systems
- Track onboarding progress and gather feedback
- Ensure new hires have necessary access, tools, and resources
- Continuously improve the onboarding process based on feedback
- Maintain knowledge base and learning resources

### Goals
- Reduce time-to-productivity for new team members
- Ensure consistent, high-quality onboarding experiences
- Build strong connections between new hires and the team
- Capture and scale institutional knowledge

### Interactions with Other Roles
- **Project Managers**: Coordinate project-specific onboarding and context
- **Developers**: Arrange technical onboarding and code base orientation
- **Product Managers**: Provide product vision and customer context
- **All team members**: Coordinate shadowing, mentoring, and knowledge sharing
- **HR/Recruiting**: Align on hiring and onboarding timelines

### Communication Channels
- One-on-one check-ins with new hires (first week, first month, 90 days)
- Onboarding feedback surveys
- Monthly onboarding retrospectives
- Documentation via wiki or knowledge base

### Escalation Paths
- Access or tooling issues → IT/Operations team
- Training gaps → Team Lead or Manager
- Culture or team fit concerns → Manager → HR

---

## Metrics Analyst

### Role Summary
Metrics Analysts collect, analyze, and communicate data about project performance, team velocity, and product outcomes. They enable data-driven decision-making and help teams measure progress toward goals.

### Responsibilities
- Define key performance indicators (KPIs) and success metrics
- Collect and aggregate data from various sources
- Create dashboards and visualizations for stakeholders
- Analyze trends and provide insights to inform decisions
- Report on team velocity, quality metrics, and delivery performance
- Identify opportunities for process improvement based on data
- Ensure data accuracy and consistency

### Goals
- Enable evidence-based decision-making
- Increase visibility into project health and team performance
- Identify bottlenecks and improvement opportunities
- Track progress toward business and product goals

### Interactions with Other Roles
- **Product Managers**: Provide product metrics, user analytics, and outcome data
- **Project Managers**: Share velocity, timeline, and resource metrics
- **QA Lead**: Analyze quality metrics, defect trends, and test coverage
- **Release Manager**: Provide deployment frequency, lead time, and incident metrics
- **All team members**: Gather data inputs and share insights

### Communication Channels
- Weekly metrics reports and dashboards
- Monthly metrics reviews with leadership
- Sprint retrospectives (sharing velocity and quality data)
- Ad-hoc analysis requests

### Escalation Paths
- Data access issues → Engineering Manager → IT/Data team
- Conflicting metrics or reporting needs → Project Manager → Product Lead
- Privacy or security concerns → Security team

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

