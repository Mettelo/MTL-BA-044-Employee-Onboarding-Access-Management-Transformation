# Harrowgate — business context and People Director's initiation brief
**Mettelo Business Analyst Project Studio · MTL-BA-044 · aligned pathway edition · Stage 1**
Issued 6 July 2026 by Sarah Bennett, People Director. All local figures, organisations, people and employment records are synthetic.

## Organisation, growth and operating model
Harrowgate Professional Services Ltd is a fictional UK business employing approximately 2,400 people across London, Leeds, client sites and remote arrangements. Consulting delivery, operations, sales, Finance and shared services depend on company and client-controlled applications. A rapid hiring programme has increased joiner demand while client contracts and team changes create mover activity.

HR approves employment records and effective dates. Line managers define business role and client assignment. IT provisions company identity, equipment and some application access. Application owners approve entitlements; Security governs privileged access and exceptions. Facilities arranges passes, desks and some delivery coordination. Client-system owners may remain outside Harrowgate's direct technical control.

The service desk supports 360 joiner requests first raised in April–June in the constructed training population. Leaver evidence covers a separate 120 workers. These numbers do not describe a real employer or an audited workforce stock; other hires/movers and legacy activity may sit outside the selected service scope. The BA must not combine joiners and leavers to infer net headcount without the full population.

## Work environment and user groups
Office-based starters need a suitable desk/pass as well as technical access. Remote workers need controlled delivery information and a workable activation route. Client-site workers may need applications that IT cannot authorise alone. Managers want quick mobilisation; new starters need an accountable contact and a way to report that they cannot work. Departing workers and colleagues affected by role changes introduce different timing/control risks.

PeopleRecord holds HR dates/status, ServiceQueue holds tickets, the directory holds core identity, independent SaaS tools hold their own permissions, CourierDesk records deliveries and Facilities keeps a restricted local register. A daily HR export creates or updates service tasks, but corrections do not reliably reopen a closed ticket. Created account, delivered laptop, successful core login and all required access are separate events.

## Trigger and competing explanations
At the 29 June review, HR reported high ticket closure while starter feedback described day-one problems. Security highlighted an independent SaaS permission remaining after directory disable, and Facilities reported uncertainty about changed start dates. Sarah proposed a consolidated onboarding portal.

IT says managers submit late or omit application owners. HR says dates are corrected in the authoritative record but downstream teams use an older file. Managers say the form lacks their actual client applications. Facilities says it receives information it does not need while missing what affects a desk/pass. Security asks for stronger evidence and expiry; Operations fears that extra approvals will delay mobilisation.

The BA must investigate those accounts. The evidence does not establish that one team is the root cause, that a portal is necessary or that every closed ticket represents a ready worker.

## Management report at appointment
The workbook groups by first request month with events observed through 30 June. Some June requests concern starts after cutoff and should not automatically count as day-one failures.

| Request cohort | Joiner requests | Effective starts by cutoff | Tickets closed by cutoff | Core login recorded | Manager ready = yes | Date changed |
|---|---:|---:|---:|---:|---:|---:|
| April | 90 | 90 | 90 | 90 | 51 | 16 |
| May | 120 | 120 | 120 | 120 | 70 | 28 |
| June | 150 | 101 | 115 | 98 | 47 | 41 |

Closure and eventual login are not proof of readiness at start time. Manager-ready is an existing snapshot statement, not an independent whole-access test. No exact start-time field exists in the joiner extract. The participant must define useful timing and completeness measures.

Later source records include 1,000 application-access requests, 125 incidents and 215 voluntary feedback responses. There are also 120 separate leaver records. Incidents and feedback are not representative of every worker; a missing revocation confirmation is not proof of active access.

## Operational, worker and control impact
A starter may lose productive time, ask a colleague for help, miss induction or be unable to join a client assignment. Managers and service staff chase approvals and equipment. Unnecessary data sharing can expose worker information, while delayed or unverified revocation can create security/control uncertainty.

Planning capacity rates: HR £30/hour, service desk £32/hour, Security/application specialist £55/hour, Facilities £24/hour. The business uses £240 per starter day only as a provisional capacity/opportunity estimate; it is not proven lost revenue, cash cost or a universal billable rate. No complete lost-days study, incident-loss value or client-margin population is provided.

Doing nothing may preserve rework and uncertain access ownership during further hiring. A poorly designed portal might centralise unnecessary personal information, automate the wrong role or hide independent applications behind a reassuring complete flag. Both possibilities matter.


## Business need for this commission

Approved employment dates and access actions are distributed across HR exports, service tickets, the directory, applications and equipment delivery. A ticket may close before a worker can log in; a revised start date may not reopen work; directory disable does not prove every independent account has been revoked.

The central challenge is reliable information exchange and recoverable coordination across systems, not merely buying an onboarding portal. Engineering needs clear interface behaviour, data ownership and mapping rules before it can estimate or build a safe bounded integration.

## Illustrative business situation to investigate

HR approves a joiner and publishes a daily read-only export. A service ticket coordinates actions by IT, managers and application owners. The start date then changes after the ticket closes. Equipment and identity actions may now refer to different dates. In a separate leaver case, the directory accepts a disable request but an independent application owner has not confirmed revocation. The team must specify event handling, evidence and recovery without assuming all systems share an identifier or acknowledgement.

This is a source scenario. Your team must analyse it; it is not an approved process, detailed use case or designed solution.

## Sponsor commission and authority

Sarah Bennett, the commissioning sponsor commissions your team as technical business analysts. The decision is: **What bounded HR-to-service-to-identity interface behaviour, data mapping and recovery controls can engineering design and estimate, and which owner decisions or capabilities remain blockers?**

The requested handover is: **A technical BA handover containing interface requirements, mappings, event/failure models, measurable quality proposals and integration transition/assurance planning.**

HR wants authoritative dates respected, IT needs a feasible contract and support model, Security needs approved least-privilege access and revocation evidence, and managers want workers ready on day one. A technically accepted message is not necessarily a completed business outcome.

The sponsor can request analysis but cannot substitute for HR, identity/application, Security, privacy and funding owners. Identify material approvals and unknowns without fabricating named reviewers or sign-off.

## Scope and exclusions

**Included:** The approved employment-event hand-off between PeopleRecord, ServiceQueue and directory actions; date revisions, duplicates/missing data and reconciliation; bounded independent-application and privileged-expiry dependencies needed to test completeness of access evidence.

**Outside this assignment:** No working connector, live credentials/provisioning, complete entitlement catalogue, enterprise HR procurement, hiring-policy redesign or full organisational change programme. Specify interfaces and controls; do not implement them or invent an approved target mapping.

## Constraints and evidence limitations

The initial one-off envelope is £70,000 including £7,000 committed, with a £12,000 annual incremental ceiling. The current HR export is daily and read-only. Later interface/pilot constraints must be evaluated explicitly; future capability must not be described as already available.

The learning commission lasts 6 cohort weeks. Original dates in operational records remain source history; later operational ambitions do not extend the assessed scope. Staff availability is limited: plan proportionate elicitation using supplied interviews and record follow-up questions when real access is unavailable.

The dataset is constructed, observed at its stated cutoff and incomplete for some business questions. An absent event is not always proof an event did not happen. Do not claim representative research, causality, approved targets or realised outcomes merely from these records. Use [the data guide](../evidence/DATA_GUIDE.md) and [source provenance](../reference/OFFICIAL_REFERENCES_AND_SOURCE_PROVENANCE.md).

## How the evidence supports the work

| Evidence | Analytical purpose | Relevant tasks |
|---|---|---|
| Systems context and technical source bundle | Inspect observed CSV/JSON contract fragments, identifiers, constraints and failure probes. | T1–T5 |
| Joiners, access requests and independent leavers | Connect technical actions to dated business events and incomplete outcome evidence. | T1–T4 |
| Security, HR, manager and application-owner testimony | Identify authority, privacy and accountability questions behind interface design. | T1–T5 |
| Incidents, feedback and policies | Understand exception handling, privileged expiry and evidence gaps. | T4–T6 |
| Remote-work, control and pilot notices | Revisit integration boundaries, fallback and cutover feasibility under changed constraints. | T5–T7 |

## What leadership needs to receive

Engineering and system owners can distinguish observed contracts from proposed requirements, follow each mapping/sequence to a business need, and identify how failures would be detected and recovered. The handover makes unresolved crosswalks, service levels and approvals visible.

| Task | Required handover content | Assessment weight |
|---|---|---|
| T1 | System context/trust-boundary diagram; integration scope; ownership and unresolved contract questions. | 10% |
| T2 | Interface Requirements Specification covering producer/consumer, triggers, contract validation, acknowledgement and exception behaviour. | 20% |
| T3 | Source-to-target mapping; technical data dictionary; identifiers, types, null/transformation/rejection rules and ownership. | 20% |
| T4 | Sequence/event-flow diagrams for joiner, changed date, leaver and privileged expiry; failure/replay/reconciliation specification. | 20% |
| T5 | Non-functional and control requirements with measurable proposed verification and owner approval status. | 15% |
| T6 | Integration test scenarios; reconciliation approach; cutover/rollback plan with dependencies and entry/exit criteria. | 10% |
| T7 | Technical decision record; consistent specification index; trade-offs, blockers and engineering-review readiness recommendation. | 5% |

Use [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) for the four acceptance criteria per task and [the submission checklist](../submission/DELIVERABLES_CHECKLIST.md) for the exact handover package. These define the commission; historical stakeholder ambitions are inputs to evaluate, not extra mandatory portfolios.

No preferred solution or completed learner artefacts are provided.
