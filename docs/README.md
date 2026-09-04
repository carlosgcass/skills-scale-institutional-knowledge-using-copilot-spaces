# OctoAcme Project Management Documentation

Welcome to OctoAcme's centralized project management knowledge base. This documentation standardizes how we run projects, coordinate teams, and deliver value to our customers.

## Quick Navigation

### Project Lifecycle
1. **[Project Initiation](./octoacme-project-initiation.md)** - Validate ideas and authorize work
2. **[Project Planning](./octoacme-project-planning.md)** - Turn approved initiatives into actionable plans
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - Manage day-to-day work and measure progress
4. **[Release & Deployment](./octoacme-release-and-deployment.md)** - Deploy features safely to production
5. **[Retrospective & Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings and iterate

### Key References
- **[Project Management Overview](./octoacme-project-management-overview.md)** - Core principles, roles, and artifacts
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - Identify, escalate, and communicate risks
- **[Roles & Personas](./octoacme-roles-and-personas.md)** - Role definitions and responsibilities

---

## OctoAcme Project Management Overview

### Lifecycle & Core Workflow

OctoAcme operates a structured five-phase project lifecycle designed to deliver customer value through iterative, testable increments. Projects begin with **Initiation**, where teams validate business needs, identify stakeholders, and create a lightweight Project One-pager defining problem statements, success metrics, and initial timelines. Once approved, teams move into **Planning**, breaking work into shippable increments with prioritized backlogs, clear acceptance criteria, and a Definition of Done. During **Execution & Tracking**, teams follow a daily standup cadence with weekly delivery syncs, manage work through GitHub Projects boards (Backlog → Ready → In Progress → In Review → QA → Done), and maintain a Risk Register updated weekly. **Release & Deployment** involves pre-release quality gates (passing CI/security scans, drafted release notes, smoke tests) and a structured deployment checklist to minimize production risk. Finally, **Retrospective & Continuous Improvement** happens after each sprint or milestone, capturing learnings and converting them into prioritized action items with clear owners and due dates.

### Roles & Responsibilities

OctoAcme defines three primary personas within cross-functional teams: **Project Managers (PMs)** coordinate delivery activities, manage schedules, risks, and communications—serving as the connective tissue between engineering and stakeholders; **Product Managers (PdMs)** own the product vision, prioritize backlogs, and measure outcomes through success metrics and user research; and **Developers** implement features, write tests, collaborate on design, and help identify technical risks. QA/Testing roles validate quality and acceptance criteria, while stakeholders provide inputs and approvals. This clear ownership model ensures each project has named accountability, with weekly syncs between PM and PdM to align on execution and weekly standups (or twice-weekly) for the delivery team to surface blockers and dependencies.

### Communication & Risk Management

OctoAcme emphasizes proactive communication through a structured cadence: weekly syncs between PM and PdM, twice-weekly standups for delivery teams, monthly stakeholder updates, and ad-hoc escalations as needed. Risk management follows a systematic lifecycle—teams identify risks during planning and ongoing execution, assess their impact (High/Med/Low) and likelihood, implement mitigation plans, and monitor status at weekly syncs. Blocker escalation follows a three-level path: Level 1 (team-level triage in daily standup), Level 2 (PM escalates to Product Lead and dependent teams), and Level 3 (Sponsor-level escalation for business-impacting issues). Teams maintain a single source of truth (project README or release doc) for status and use standardized communication templates for weekly updates and incident communications, ensuring transparency and reducing misalignment across the organization.

### Quality Assurance & Execution Standards

Quality is embedded throughout OctoAcme's delivery process through multiple gates and practices. Teams follow a Pull Request workflow with small PRs (≤400 lines when possible), issue links, clear acceptance criteria, automated CI testing/linting, and require at least one approval before merging. Testing includes unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and security scanning in CI pipelines. Manual QA validates feature acceptance when needed. Beyond code quality, teams track metrics like velocity, burndown, and success metrics identified in the Project One-pager, using dashboards to monitor key signals (errors, latency, usage). An Execution Checklist ensures branching conventions are documented, CI is configured, demos are scheduled regularly, and the Risk Register is maintained weekly. This multi-layered approach—combining process discipline, clear ownership, consistent communication, and quality gates—enables OctoAcme to deliver reliably while maintaining organizational transparency and reducing single-person dependency risk.

---

## Using These Docs in Copilot Spaces

These process documents are designed to be used as context in Copilot Spaces, enabling team members to:

- **Discover processes** - Search for guidance on specific workflows or decisions
- **Get role-specific guidance** - Find responsibilities and communication patterns for your role
- **Understand connections** - See how different phases and processes relate to each other
- **Onboard faster** - New team members can quickly learn OctoAcme's standards and best practices
- **Maintain consistency** - Reference these docs when establishing new projects or processes

Add these files to your Copilot Space context to leverage OctoAcme's institutional knowledge in your day-to-day work.

---

## Core Principles

OctoAcme's project management is built on five core principles:

- **Customer-first** - Prioritize customer value and usability in all decisions
- **Iterative delivery** - Deliver small, testable increments to gather feedback early
- **Clear ownership** - Each project has named Project Manager and Product Lead accountability
- **Data-informed decisions** - Measure impact and iterate based on evidence, not assumptions
- **Psychological safety** - Encourage feedback, learning, and continuous improvement

---

## Getting Help

If you have questions about a specific process or need clarification on how to apply these guidelines:

1. Review the relevant process document from the Quick Navigation section
2. Consult the [Roles & Personas](./octoacme-roles-and-personas.md) to identify who to reach out to
3. Use the [Risk Management & Communication](./octoacme-risks-and-communication.md) guide for escalation paths
