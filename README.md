# Mettelo Business Analyst Project Studio — MTL-BA-044

## Onboarding and access: technical integration analysis

**Role:** Technical Business Analyst · **Duration:** 6 cohort weeks · **Organisation:** Harrowgate Professional Services

This repository is the source library for a simulated business assignment. Your team acts as the BA team commissioned by Sarah Bennett, the commissioning sponsor. You investigate supplied evidence and create your own analysis in a separate delivery repository. All local organisations, people and operational records are fictional; clearly labelled official reference material remains external context.

## The business situation

Harrowgate Professional Services has commissioned this simulation. Approved employment dates and access actions are distributed across HR exports, service tickets, the directory, applications and equipment delivery. A ticket may close before a worker can log in; a revised start date may not reopen work; directory disable does not prove every independent account has been revoked.

### Example business situation

HR approves a joiner and publishes a daily read-only export. A service ticket coordinates actions by IT, managers and application owners. The start date then changes after the ticket closes. Equipment and identity actions may now refer to different dates. In a separate leaver case, the directory accepts a disable request but an independent application owner has not confirmed revocation. The team must specify event handling, evidence and recovery without assuming all systems share an identifier or acknowledgement.

### Why this work is needed

The central challenge is reliable information exchange and recoverable coordination across systems, not merely buying an onboarding portal. Engineering needs clear interface behaviour, data ownership and mapping rules before it can estimate or build a safe bounded integration.

### Perspectives you must reconcile

HR wants authoritative dates respected, IT needs a feasible contract and support model, Security needs approved least-privilege access and revocation evidence, and managers want workers ready on day one. A technically accepted message is not necessarily a completed business outcome.

## Your commission and the decision it supports

**Business question:** What bounded HR-to-service-to-identity interface behaviour, data mapping and recovery controls can engineering design and estimate, and which owner decisions or capabilities remain blockers?

**Your endpoint:** A technical BA handover containing interface requirements, mappings, event/failure models, measurable quality proposals and integration transition/assurance planning.

**What good work enables:** Engineering and system owners can distinguish observed contracts from proposed requirements, follow each mapping/sequence to a business need, and identify how failures would be detected and recovered. The handover makes unresolved crosswalks, service levels and approvals visible.

**Skills you will practise:** System context and trust boundaries, interface requirements, source-to-target mappings, event sequencing, error/replay handling, non-functional requirements and integration assurance.

## What your team will actually do

1. **T1 — Bound the integration.** Produce system context diagram, integration scope and ownership questions. Use it to inform the next task and keep unresolved decisions visible.
2. **T2 — Specify interface behaviour.** Produce interface Requirements Specification. Use it to inform the next task and keep unresolved decisions visible.
3. **T3 — Define data transformation.** Produce source-to-target mapping and technical data dictionary. Use it to inform the next task and keep unresolved decisions visible.
4. **T4 — Model event and failure paths.** Produce sequence/event-flow diagrams and recovery specification. Use it to inform the next task and keep unresolved decisions visible.
5. **T5 — Define quality and control requirements.** Produce non-functional and control requirements with measurable verification proposals. Use it to inform the next task and keep unresolved decisions visible.
6. **T6 — Plan integration assurance and transition.** Produce integration test scenarios, reconciliation approach and cutover/rollback plan. Use it to inform the next task and keep unresolved decisions visible.
7. **T7 — Handover for engineering review.** Produce technical decision record and indexed specification baseline. Use it to inform the next task and keep unresolved decisions visible.

Each task has four explicit assignment acceptance criteria in [TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md](project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md). They explain how the output is assessed. Where you must write solution acceptance criteria, those are your own proposed business/system/product behaviours, not supplied answers.

## Exactly what you submit

| Task | Required team handover content | Weight |
|---|---|---|
| T1 | System context/trust-boundary diagram; integration scope; ownership and unresolved contract questions. | 10% |
| T2 | Interface Requirements Specification covering producer/consumer, triggers, contract validation, acknowledgement and exception behaviour. | 20% |
| T3 | Source-to-target mapping; technical data dictionary; identifiers, types, null/transformation/rejection rules and ownership. | 20% |
| T4 | Sequence/event-flow diagrams for joiner, changed date, leaver and privileged expiry; failure/replay/reconciliation specification. | 20% |
| T5 | Non-functional and control requirements with measurable proposed verification and owner approval status. | 15% |
| T6 | Integration test scenarios; reconciliation approach; cutover/rollback plan with dependencies and entry/exit criteria. | 10% |
| T7 | Technical decision record; consistent specification index; trade-offs, blockers and engineering-review readiness recommendation. | 5% |

Use [the project-specific submission checklist](submission/DELIVERABLES_CHECKLIST.md) for package names, minimum content and final checks. You may combine related content if the final index links each task to the relevant section. A heading with no analysis is not a completed deliverable.

## Start here

1. Read [the business context and sponsor brief](business_context/BUSINESS_CONTEXT_AND_SPONSOR_BRIEF.md) to understand the organisation, observed problem and decision owners.
2. Read [the project brief](project/PROJECT_BRIEF.md) and [task acceptance criteria](project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) to understand the assignment boundary.
3. Follow [the delivery guide](project/DELIVERY_GUIDE.md), [timeline](project/PROJECT_TIMELINE.md) and [release manifest](project/RELEASE_MANIFEST.csv). In a controlled cohort, use only released evidence.
4. Create your separate team repository using [submission guidelines](submission/SUBMISSION_GUIDELINES.md). Confirm reviewer access before substantial work.
5. Build and review the required outputs; submit the tagged repository URL through Mettelo's cohort route.

## What the evidence is for

Open [the source catalogue](evidence/README.md) for direct links and release labels for each evidence file.

| Source group | Why you need it | Main tasks |
|---|---|---|
| Systems context and technical source bundle | Inspect observed CSV/JSON contract fragments, identifiers, constraints and failure probes. | T1–T5 |
| Joiners, access requests and independent leavers | Connect technical actions to dated business events and incomplete outcome evidence. | T1–T4 |
| Security, HR, manager and application-owner testimony | Identify authority, privacy and accountability questions behind interface design. | T1–T5 |
| Incidents, feedback and policies | Understand exception handling, privileged expiry and evidence gaps. | T4–T6 |
| Remote-work, control and pilot notices | Revisit integration boundaries, fallback and cutover feasibility under changed constraints. | T5–T7 |

The source packs deliberately contain disagreement, missing information and unapproved proposals. A stakeholder request is evidence of a need or preference, not automatically an agreed requirement. Preserve raw data, identify source rows/case IDs and distinguish facts, interpretation, assumptions and proposals. The task pack does not contain completed BA answers.

## Scope and practical boundaries

**Included:** The approved employment-event hand-off between PeopleRecord, ServiceQueue and directory actions; date revisions, duplicates/missing data and reconciliation; bounded independent-application and privileged-expiry dependencies needed to test completeness of access evidence.

**Outside this assignment:** No working connector, live credentials/provisioning, complete entitlement catalogue, enterprise HR procurement, hiring-policy redesign or full organisational change programme. Specify interfaces and controls; do not implement them or invent an approved target mapping.

**Planning constraints:** The initial one-off envelope is £70,000 including £7,000 committed, with a £12,000 annual incremental ceiling. The current HR export is daily and read-only. Later interface/pilot constraints must be evaluated explicitly; future capability must not be described as already available.

6 weeks describes your learning commission; any dated operational pilot in source testimony is a business ambition, not an instruction to deploy. Later pilot/experiment files are optional background. Do not claim you conducted the supplied interviews, executed tests or achieved live benefits. No paid tool is required; use readable documents, spreadsheets and diagram/prototype tools you can access.

## Why there are change scenarios

The notices introduce new facts, contested proposals or constraints that test your judgement. Apply them to this project's outputs and keep a revision trail. They do not make every project a change-management assignment and do not require a separate generic three-change report.

## Repository navigation

- **business_context:** organisation, problem, sponsor commission and decision boundaries.
- **stakeholders:** supplied testimony and conflicting perspectives.
- **evidence:** synthetic records, forms and the pathway-specific supplement.
- **policies / systems:** existing rules, capability claims and constraints.
- **reference:** external context and source provenance; observe retrieval limitations.
- **change_scenarios:** staged challenge evidence.
- **project:** tasks, acceptance criteria, assessment, releases and timeline.
- **submission:** instructions and the exact team handover checklist; no team answers.

Public GitHub exposes all stages. A facilitator must distribute releases separately if staged access matters. Never commit participant answers to this master; maintain your work, contribution history and final submission in your team's repository.
