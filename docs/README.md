```markdown
# OctoAcme — Project Management Overview

OctoAcme runs projects through a lightweight, outcome-focused lifecycle: Initiation, Planning, Execution, Release, and Close & Retrospective. New initiatives begin with a Project One-pager that captures the problem, goals, success metrics, stakeholders, and a high-level timeline. Approved initiatives move into planning to create a prioritized backlog, agree on the Definition of Done, estimate work, and map releases and milestones.

Day-to-day delivery follows explicit workflows to keep work visible and small. The project board tracks items through Backlog → Ready → In Progress → In Review → QA → Done. Pull requests are kept small, reference linked issues and acceptance criteria, and must pass CI (tests, linters, security scans) before review and at least one approval prior to merge. Releases use a standard checklist (staging verification, smoke tests, rollback plan) and include release notes and post-deploy verification.

Roles and responsibilities are explicit: a named Project Manager (PM) coordinates schedule, risks, and communications; a Product Manager (PdM) owns outcomes and backlog prioritization; Developers build and test; QA validates acceptance criteria; Stakeholders provide inputs and approvals. Communication cadence includes daily standups, weekly delivery syncs, sprint demos/reviews, and monthly stakeholder updates. Templates and escalation paths help keep status transparent and accelerate response to blockers or incidents.

Quality assurance is layered: unit and integration tests, end-to-end smoke tests for critical flows, CI security scanning, and manual QA for feature acceptance as needed. Retrospectives after sprints, releases, or incidents capture what went well and what to improve; action items are tracked in the backlog and reviewed regularly to drive continuous improvement.
```
