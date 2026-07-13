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

## Engineering Manager

### Role Summary
Engineering Managers lead engineering teams, balancing technical delivery with people management. They bridge individual contributors and organizational goals, ensuring teams have clarity, resources, and an environment to succeed.

### Responsibilities
- Manage team health, hiring, and career development
- Translate organizational priorities into team-level goals
- Remove blockers and escalate risks across teams
- Oversee technical quality, architecture decisions, and delivery commitments
- Partner with Product and Project Managers on roadmap trade-offs

### Goals
- Build and retain high-performing, motivated engineering teams
- Maintain sustainable delivery pace and technical standards
- Align engineering capacity with business priorities

### Typical Communication
- 1:1s with direct reports and skip-levels
- Engineering leadership syncs and roadmap reviews
- Escalation and incident post-mortems

### How they interact with existing roles
- **Developers**: Direct people manager; sets expectations, unblocks work, and advocates for developer needs.
- **Product Managers**: Negotiates scope and timelines; surfaces engineering constraints and risks early.
- **Project Managers**: Partners on resource planning, risk management, and milestone tracking.

---

## UX/UI Designer

### Role Summary
UX/UI Designers ensure that products are intuitive, accessible, and visually consistent. They translate user needs and business requirements into designs that developers can implement.

### Responsibilities
- Conduct user research, usability testing, and competitive analysis
- Create wireframes, prototypes, and high-fidelity mockups
- Maintain and evolve design systems and component libraries
- Write interaction specs and annotate designs for engineering handoff
- Advocate for accessibility standards (WCAG compliance)

### Goals
- Deliver user experiences that are simple, delightful, and accessible
- Reduce engineering rework caused by unclear or incomplete designs
- Ensure design consistency across the product surface

### Typical Communication
- Design reviews and critique sessions
- Annotated Figma/design files shared with engineering
- Sprint demos to gather feedback on implemented UX

### How they interact with existing roles
- **Developers**: Provides detailed design specs and is available for questions during implementation; reviews built UI against designs.
- **Product Managers**: Translates product requirements into user flows; validates designs against user stories.
- **Project Managers**: Flags design dependencies and timeline risks for design delivery milestones.

---

## DevOps / SRE Engineer

### Role Summary
DevOps/SRE Engineers own the reliability, scalability, and deployment pipelines of the system. They automate infrastructure, improve CI/CD workflows, and define operational standards.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Define and track reliability targets (SLOs, SLAs, error budgets)
- Manage infrastructure-as-code, cloud resources, and monitoring
- Lead incident response, post-mortems, and on-call processes
- Drive improvements to system observability and alerting

### Goals
- Maximize system uptime and minimize mean time to recovery (MTTR)
- Reduce manual toil through automation
- Make deployments safe, fast, and reversible

### Typical Communication
- Incident channels and post-mortem write-ups
- Runbooks and operational playbooks
- Infrastructure review sessions with engineering leads

### How they interact with existing roles
- **Developers**: Provides deployment tooling and guidance; collaborates on production readiness reviews.
- **Product Managers**: Communicates reliability trade-offs that affect feature timelines or quality.
- **Project Managers**: Surfaces infrastructure dependencies and operational risks in project planning.

---

## Security / Compliance Lead

### Role Summary
Security/Compliance Leads protect the organization by identifying vulnerabilities, enforcing security standards, and ensuring regulatory requirements are met throughout the development lifecycle.

### Responsibilities
- Conduct threat modeling and security reviews for new features and architecture changes
- Define and enforce security policies and coding standards
- Manage vulnerability scanning, penetration testing, and remediation tracking
- Ensure compliance with relevant regulations (e.g., GDPR, SOC 2, HIPAA)
- Train teams on secure development practices

### Goals
- Prevent security incidents and data breaches
- Maintain regulatory compliance and audit readiness
- Shift security left so issues are caught before production

### Typical Communication
- Security review sign-offs on PRs and architecture docs
- Compliance status reports to leadership
- Vulnerability triage sessions with engineering teams

### How they interact with existing roles
- **Developers**: Reviews code for security issues; provides guidance on secure patterns and libraries.
- **Product Managers**: Advises on data privacy requirements and compliance constraints that affect feature design.
- **Project Managers**: Flags security remediation work that must be tracked and prioritized in project plans.

---

## Customer Support / Success Representative

### Role Summary
Customer Support/Success Representatives are the voice of the customer inside the organization. They surface real-world issues, gather feedback, and ensure customers get maximum value from the product.

### Responsibilities
- Handle customer inquiries, bug reports, and escalations
- Document recurring customer pain points and feature requests
- Collaborate with product and engineering on issue triage and resolution
- Track customer health metrics and churn risk signals
- Onboard and train customers on new features

### Goals
- Resolve customer issues quickly and effectively
- Feed customer insights back into the product roadmap
- Improve customer retention and satisfaction scores

### Typical Communication
- Ticket and escalation channels shared with engineering
- Weekly customer feedback summaries to Product Managers
- Feature request logs and customer sentiment reports

### How they interact with existing roles
- **Developers**: Reports reproducible bugs with context; validates fixes from the customer perspective.
- **Product Managers**: Provides quantified customer feedback to inform prioritization decisions.
- **Project Managers**: Highlights customer-impacting issues that may require expedited delivery or scheduling adjustments.

---

## Data Analyst

### Role Summary
Data Analysts transform raw data into actionable insights that guide product decisions, measure feature impact, and track business health.

### Responsibilities
- Build and maintain dashboards, reports, and data pipelines
- Define and track key product and business metrics
- Analyze experiment results (A/B tests) and user behavior data
- Surface anomalies and trends to relevant stakeholders
- Ensure data quality and governance standards are upheld

### Goals
- Enable data-driven decision-making across the organization
- Reduce time-to-insight for product and business questions
- Maintain trustworthy, well-documented data assets

### Typical Communication
- Weekly metrics reviews with Product and Engineering
- Experiment readouts and impact analyses
- Data quality incident reports

### How they interact with existing roles
- **Developers**: Collaborates on instrumentation and event tracking implementation; reviews analytics schemas.
- **Product Managers**: Partners on success metrics definition and experiment design; provides data to validate or challenge product hypotheses.
- **Project Managers**: Supplies data that informs project health checks, milestone reviews, and retrospective analysis.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

### Expanded personas improve project outcomes
Adding Engineering Managers, UX/UI Designers, DevOps/SRE Engineers, Security/Compliance Leads, Customer Support/Success Representatives, and Data Analysts to the exercise creates a more realistic cross-functional team model. This expansion:
- **Improves handoffs** by clarifying who owns each transition (design → development, development → operations, operations → support).
- **Increases risk visibility** by surfacing security, reliability, and compliance concerns earlier in the project lifecycle.
- **Strengthens accountability** by mapping clear responsibilities to named roles so gaps and overlaps are easier to spot and resolve.

