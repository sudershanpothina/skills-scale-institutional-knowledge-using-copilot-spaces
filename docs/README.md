```markdown
# OctoAcme Project Management Docs

This README provides an overview of the project management processes used by OctoAcme, a quick orientation for new contributors, and links to the detailed process documents in this folder. Use this as your starting point for onboarding and for navigating OctoAcme project practices.

## Project Management Processes (brief)

OctoAcme runs projects through an iterative, stage-gated approach focused on measurable customer value and predictable delivery. Projects proceed through Initiation, Planning, Execution, Release, and Continuous Improvement. Work is broken into small, testable increments with clear acceptance criteria and a shared Definition of Done.

- Key workflows: Start with a Project One-pager, create a prioritized backlog with acceptance criteria, and follow a team rhythm (standups, delivery syncs, demos). Track work on a project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull Requests should be small, reference the related issue and acceptance criteria, and pass CI and security checks before merging.
- Personas & roles: Product Managers (PdM) define outcomes and prioritize the backlog; Project Managers (PM) coordinate schedules, risks, and communications; Developers implement and test features; QA validates acceptance criteria and quality; Stakeholders provide inputs and approvals. Each role has defined responsibilities to ensure accountability and alignment.
- Communication strategies: Regular cadences include daily or twice-weekly standups, weekly PM–PdM syncs, and monthly stakeholder updates. Use templated weekly status and incident updates and maintain a single source of truth (project README or release doc) for current status and decisions.
- Quality assurance: Combine automated testing (unit, integration, CI security scans, smoke tests) with manual QA when required. Releases require pre-release gates (passing CI, release notes, rollback plan) and a deployment checklist with post-deploy verification. Retrospectives convert learnings into tracked action items.

## Lifecycle stages & links

1. Project Initiation — define the problem, stakeholders, and success metrics  
   (see: ./octoacme-project-initiation.md)
2. Project Planning — break down work, set timelines, and identify dependencies  
   (see: ./octoacme-project-planning.md)
3. Execution & Tracking — team rhythm, project board, PR workflow, QA  
   (see: ./octoacme-execution-and-tracking.md)
4. Risk Management & Communication — risk register, escalation, templates  
   (see: ./octoacme-risks-and-communication.md)
5. Release & Deployment — pre-release gates, deployment checklist, rollback  
   (see: ./octoacme-release-and-deployment.md)
6. Retrospective & Continuous Improvement — run retros, track action items  
   (see: ./octoacme-retrospective-and-continuous-improvement.md)

### Quick links
- Project Management Overview: ./octoacme-project-management-overview.md  
- Project Initiation: ./octoacme-project-initiation.md  
- Project Planning: ./octoacme-project-planning.md  
- Execution & Tracking: ./octoacme-execution-and-tracking.md  
- Risk & Communication: ./octoacme-risks-and-communication.md  
- Release & Deployment: ./octoacme-release-and-deployment.md  
- Retrospective & Continuous Improvement: ./octoacme-retrospective-and-continuous-improvement.md  
- Roles & Personas: ./octoacme-roles-and-personas.md
```