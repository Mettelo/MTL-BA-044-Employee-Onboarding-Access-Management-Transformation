# MTL-BA-044 — commissioned assignment

**Mettelo Business Analyst Project Studio · distinct pathway edition**

## Business problem and reason for commissioning the team

Approved employment dates and access actions are distributed across HR exports, service tickets, the directory, applications and equipment delivery. A ticket may close before a worker can log in; a revised start date may not reopen work; directory disable does not prove every independent account has been revoked.

The central challenge is reliable information exchange and recoverable coordination across systems, not merely buying an onboarding portal. Engineering needs clear interface behaviour, data ownership and mapping rules before it can estimate or build a safe bounded integration.

Read the [organisation and sponsor context](../business_context/BUSINESS_CONTEXT_AND_SPONSOR_BRIEF.md) for the observed operating environment.

## Role and business decision
You are the Technical Business Analyst. How should approved employment events move between HR, service management and identity systems reliably, with accountable access decisions and recoverable failures?

An integration analysis and assurance handover for a bounded HR-to-service-to-identity capability. No working connector, live provisioning or full organisational change programme.

## Business situation and intended value

HR approves a joiner and publishes a daily read-only export. A service ticket coordinates actions by IT, managers and application owners. The start date then changes after the ticket closes. Equipment and identity actions may now refer to different dates. In a separate leaver case, the directory accepts a disable request but an independent application owner has not confirmed revocation. The team must specify event handling, evidence and recovery without assuming all systems share an identifier or acknowledgement.

Engineering and system owners can distinguish observed contracts from proposed requirements, follow each mapping/sequence to a business need, and identify how failures would be detected and recovered. The handover makes unresolved crosswalks, service levels and approvals visible.

## Scope

The approved employment-event hand-off between PeopleRecord, ServiceQueue and directory actions; date revisions, duplicates/missing data and reconciliation; bounded independent-application and privileged-expiry dependencies needed to test completeness of access evidence.

No working connector, live credentials/provisioning, complete entitlement catalogue, enterprise HR procurement, hiring-policy redesign or full organisational change programme. Specify interfaces and controls; do not implement them or invent an approved target mapping.

## Required work
| ID | Task | Required output | Assessment weight |
|---|---|---|---|
| T1 | Bound the integration | System context diagram, integration scope and ownership questions | 10% |
| T2 | Specify interface behaviour | Interface Requirements Specification | 20% |
| T3 | Define data transformation | Source-to-target mapping and technical data dictionary | 20% |
| T4 | Model event and failure paths | Sequence/event-flow diagrams and recovery specification | 20% |
| T5 | Define quality and control requirements | Non-functional and control requirements with measurable verification proposals | 15% |
| T6 | Plan integration assurance and transition | Integration test scenarios, reconciliation approach and cutover/rollback plan | 10% |
| T7 | Handover for engineering review | Technical decision record and indexed specification baseline | 5% |

The [task specification](TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) defines evidence and pass conditions for every output. Equivalent document formats are acceptable; omissions of analytical content are not. This is a 6-week learning commission, not a requirement to deliver a live business implementation.

## Working agreement
Use supplied facts, conflicting stakeholder accounts and synthetic source records. Make calculations reproducible; distinguish evidence, interpretation, proposal and unresolved approval. Reference actual source paths and row/case IDs. Do not invent stakeholder sign-off, real research, executed tests or realised benefits. External references supply context, not automatic approval of your proposals.

## Commission precedence
This brief, task criteria, assessment, timeline and release manifest supersede earlier generic end-to-end assignment instructions. Source packs retain historical requests and evolving assumptions to analyse. They are not additional deliverable lists. Record material contradictions and decide how they affect this commission.

## Evidence-to-deliverable connection

| Evidence | What you use it to establish | Tasks |
|---|---|---|
| Systems context and technical source bundle | Inspect observed CSV/JSON contract fragments, identifiers, constraints and failure probes. | T1–T5 |
| Joiners, access requests and independent leavers | Connect technical actions to dated business events and incomplete outcome evidence. | T1–T4 |
| Security, HR, manager and application-owner testimony | Identify authority, privacy and accountability questions behind interface design. | T1–T5 |
| Incidents, feedback and policies | Understand exception handling, privileged expiry and evidence gaps. | T4–T6 |
| Remote-work, control and pilot notices | Revisit integration boundaries, fallback and cutover feasibility under changed constraints. | T5–T7 |

## Submission
Submit the indexed outputs above in your own delivery repository using [Mettelo's submission model](../submission/SUBMISSION_GUIDELINES.md).


The [team deliverables checklist](../submission/DELIVERABLES_CHECKLIST.md) specifies the required handover content, suggested package paths and completion checks.
