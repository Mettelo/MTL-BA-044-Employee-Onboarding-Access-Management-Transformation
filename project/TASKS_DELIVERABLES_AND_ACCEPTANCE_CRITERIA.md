# What you must do, deliver and demonstrate
**Mettelo Business Analyst Project Studio · MTL-BA-044 · Participant delivery contract**
This is the task checklist for your own work. Read it at Stage 1. Mettelo supplies sources; you create the outputs below in your separate delivery repository.

## Project identity
**Primary BA work:** Internal business systems and access-control process analysis.  
**Business scope:** Joiner readiness, HR date changes, appropriate application access and leaver/mover dependencies.  
**Decision to support:** which operational/system changes can improve verified readiness and access control with credible ownership and timing.

These are practical learning emphases, not an exhaustive industry taxonomy. BA work can also focus on products/software, data/reporting, integrations/migrations, compliance or strategic/business-model questions. The five studio projects share BA practices but have different domain models, decisions and controls.

A mid-project change notice introduces a new constraint or piece of evidence. Your D08 response practises requirements/scope impact analysis. It does not make this an organisational change-management assignment. People/adoption considerations are part of D11 where relevant; you are not being asked to run an organisation-wide communications/training programme.

For broader professional context see [IIBA's description of business analysis](https://www.iiba.org/professional-development/career-centre/what-is-business-analysis/), checked 17 October 2026. The tasks below are Mettelo assignment requirements, not an IIBA-mandated document list.

## Two meanings of acceptance criteria
**Assignment acceptance criteria:** the numbered checks under D01–D12 below tell you and the assessor what makes each submitted deliverable reviewable and acceptable. Mettelo supplies these.

**Solution acceptance criteria:** in D04 you must author observable conditions for your proposed requirements/user goals. In D09 you turn them into tests, then in D10 assess what evidence exists. Mettelo does not pre-write the solution requirements, expected business rules or correct test outcomes for you.

A deliverable is ready for review when its checks are addressed and open questions are explicit. Mark reviewer approval only if it actually occurred. Content acceptance is separate from the weighted score in [assessment criteria](ASSESSMENT_CRITERIA.md).

## Required task/output map
| Task | What you do | When | Files you create in your delivery repository |
|---|---|---|---|
| D01 | Initiation and problem framing | Stage 1; Week 1 | `docs/initiation/INITIATION_BRIEF.md`<br>`docs/initiation/RAID.csv` |
| D02 | Stakeholder analysis and elicitation | Stage 2; Week 2 | `docs/discovery/STAKEHOLDER_AND_ELICITATION_REPORT.md` |
| D03 | Current state, evidence and causes | Stage 3; Week 3 | `docs/current-state/CURRENT_STATE_AND_EVIDENCE_REPORT.md`<br>`docs/current-state/AS_IS_PROCESS.pdf`<br>`data/analysis/ANALYSIS_WORKBOOK.xlsx` |
| D04 | Requirements and solution acceptance criteria | Stages 3–4; Weeks 3–4 | `docs/requirements/REQUIREMENTS_AND_ACCEPTANCE_CRITERIA.xlsx`<br>`docs/requirements/USE_CASES_OR_USER_STORIES.md` |
| D05 | Proposed role/access responsibility and identity information models | Stage 4; Week 4 | `docs/domain-models/PROPOSED_ROLE_ACCESS_AND_CONTROL_MATRIX.md`<br>`docs/domain-models/JML_INFORMATION_MODEL.md` |
| D06 | Future state and options appraisal | Stage 4; Week 4 | `docs/options-and-future-state/FUTURE_STATE_AND_OPTIONS.md`<br>`docs/options-and-future-state/TO_BE_PROCESS.pdf` |
| D07 | Prioritisation, traceability and saved baseline | Stage 4 before any change notice | `docs/requirements/PRIORITISED_BASELINE.md`<br>`docs/requirements/TRACEABILITY.csv` |
| D08 | Respond to changing constraints | Stage 5; after each notice | `docs/change/CHANGE_IMPACT_01.md`<br>`docs/change/CHANGE_IMPACT_02.md`<br>`docs/change/CHANGE_IMPACT_03.md` |
| D09 | Prepare UAT independently | Stage 6; before experiment results | `docs/assurance/UAT_PLAN.md`<br>`docs/assurance/UAT_SCENARIOS.csv` |
| D10 | Assess observations, issues and readiness | Stage 6; after 24 August evidence | `docs/assurance/OBSERVATION_AND_DEFECT_ASSESSMENT.csv`<br>`docs/assurance/READINESS_RECOMMENDATION.md` |
| D11 | Value evaluation and operational transition | Stage 7; Week 8 | `docs/recommendation-and-benefits/BENEFITS_AND_TRANSITION_PLAN.md` |
| D12 | Executive playback and professional submission | Stage 7; Week 8 | `docs/recommendation-and-benefits/EXECUTIVE_PLAYBACK.pdf`<br>`README.md`<br>`CONTRIBUTIONS.md`<br>`submission/FINAL_SUBMISSION.md` |

The paths are the expected delivery layout, not files supplied in this master. For working registers/workbooks, a documented CSV/Markdown alternative is acceptable if it preserves the required fields, formulas/reproduction and navigation. Diagrams/playback may use SVG, PDF or another accessible export with editable source retained. If you combine artefacts into one substantial document, FINAL_SUBMISSION.md must link the exact sections for every task. Do not create empty documents just to satisfy filenames.

## Project-specific coverage
**Current-state and requirements coverage:** office/remote/client-site starts; late or changed dates; delivery/activation; missing owner approval; privileged/emergency access; mover/client dependencies; noon/immediate leavers; unverified independent revocation. Investigate these situations; the list does not prescribe their correct future handling.

**Measurement distinctions:** requests versus people actually started, ticket closure versus delivery/login/required access, optional feedback, verified versus unverified revocation. Define missing measures rather than invent facts or quietly use another denominator.

**Non-functional/control investigation:** worker-data minimisation/role access, appropriate audit, expiry/review, date-change acknowledgement, interface recovery and support. Establish values and acceptance evidence from the need/source, with assumptions and owner validation status explicit.

**UAT scope to consider:** date change after closure; remote delivery; incomplete owner approval; privileged expiry/review; client dependency; noon leaver; independent access/session evidence; restricted worker data; missed HR file. Derive actual scenarios/expected outcomes from your own requirements; this is coverage guidance, not a completed test set.

**Relevant validators/decision owners:** sponsor, HR, IT, managers, Security, application/client owners and Facilities. A source role does not imply blanket approval.

## D01 — Initiation and problem framing
**When:** Stage 1; Week 1  
**Required outputs:** `docs/initiation/INITIATION_BRIEF.md`, `docs/initiation/RAID.csv`

**Work:** State the business need, impact, decision sought, proposed objectives, boundaries, assumptions and discovery approach. Start the RAID and maintain it throughout.

**Acceptance criteria**
- **D01.A1** — Identify the commissioned decision and distinguish the sponsor solution hypothesis from an agreed business need.
- **D01.A2** — Support the claimed impact and starting performance with source references, units, time period and limitations.
- **D01.A3** — State in-scope/out-of-scope work, dependencies and unresolved assumptions with proposed owner/next action.
- **D01.A4** — Give observable proposed success measures and validation status; do not invent approved targets or risk decisions.

## D02 — Stakeholder analysis and elicitation
**When:** Stage 2; Week 2  
**Required outputs:** `docs/discovery/STAKEHOLDER_AND_ELICITATION_REPORT.md`

**Work:** Create your own stakeholder register/analysis, appropriate influence/interest view, engagement approach, elicitation synthesis and follow-up/conflict log.

**Acceptance criteria**
- **D02.A1** — Cover relevant supplied roles and identify additional missing voices/decision owners, with reasoning for engagement priorities.
- **D02.A2** — Separate sourced facts, preferences, ambiguous needs, constraints and assumptions; cite the interview/workshop section.
- **D02.A3** — For each material contradiction or unclear need, identify a purposeful follow-up, appropriate owner and unresolved/validated status.
- **D02.A4** — Keep supplied simulated interviews separate from your own questions; never invent completed meetings, responses or approval.

## D03 — Current state, evidence and causes
**When:** Stage 3; Week 3  
**Required outputs:** `docs/current-state/CURRENT_STATE_AND_EVIDENCE_REPORT.md`, `docs/current-state/AS_IS_PROCESS.pdf`, `data/analysis/ANALYSIS_WORKBOOK.xlsx`

**Work:** Build your own end-to-end current-state model and reproducible analysis. Investigate possible causes and exceptions rather than merely repeat complaints.

**Acceptance criteria**
- **D03.A1** — Show actors, hand-offs, decisions, inputs/outputs, waits and relevant exceptions; make source gaps explicit.
- **D03.A2** — Provide calculations with input IDs/files, joins, formulas, denominators, cutoff, units and exclusions so another reviewer can reproduce material figures.
- **D03.A3** — Distinguish symptoms, observed facts and causal hypotheses; state supporting/contradicting evidence and what would test a hypothesis.
- **D03.A4** — Address the project-specific paths and measurement distinctions listed below; do not remove open/failed/repeated work to improve a result.

## D04 — Requirements and solution acceptance criteria
**When:** Stages 3–4; Weeks 3–4  
**Required outputs:** `docs/requirements/REQUIREMENTS_AND_ACCEPTANCE_CRITERIA.xlsx`, `docs/requirements/USE_CASES_OR_USER_STORIES.md`

**Work:** Elicit and write your own business, stakeholder, functional, non-functional and transition needs. Use use cases or user stories to express relevant user goals; include their exceptions and acceptance criteria.

**Acceptance criteria**
- **D04.A1** — Each catalogue entry has a stable ID, type, need statement, rationale, source, proposed validating owner, priority, status and related acceptance evidence.
- **D04.A2** — Each functional outcome has observable acceptance criteria stating condition/input or trigger, expected outcome and relevant failure/exception behaviour. Do not substitute vague words such as fast or user-friendly.
- **D04.A3** — Each applicable non-functional need states a metric/condition, target or explicitly proposed assumption, units and verification method; transition/control needs have objective completion evidence.
- **D04.A4** — Cover material goals and critical exceptions, distinguish needs from unvalidated supplier designs, and record unresolved conflicts/approval rather than silently resolving them.

## D05 — Proposed role/access responsibility and identity information models
**When:** Stage 4; Week 4  
**Required outputs:** `docs/domain-models/PROPOSED_ROLE_ACCESS_AND_CONTROL_MATRIX.md`, `docs/domain-models/JML_INFORMATION_MODEL.md`

**Work:** Create your own proposed role/access/control matrix and JML information model. Record business purpose, authority, review/expiry and unresolved entitlements; do not invent a pre-approved permission catalogue.

**Acceptance criteria**
- **D05.A1** — Separate HR date/status authority, manager need, application-owner approval, Security exception, technical provisioning and user verification.
- **D05.A2** — Show required role/application decisions with purpose, approver/owner, privilege, expiry/review and validation status; unknown entitlements stay explicitly unresolved.
- **D05.A3** — Model original/effective dates, correction/acknowledgement, equipment events, access evidence and independent revocation relationships.
- **D05.A4** — Distinguish directory disable, application/session revocation and physical passes; reflect client-owner dependencies without claiming authority to grant them.

## D06 — Future state and options appraisal
**When:** Stage 4; Week 4  
**Required outputs:** `docs/options-and-future-state/FUTURE_STATE_AND_OPTIONS.md`, `docs/options-and-future-state/TO_BE_PROCESS.pdf`

**Work:** Show the proposed readiness/access workflow and its joiner/mover/leaver dependencies, including independent owners and controlled exceptions. Do not prescribe shared credentials or blanket access. Compare the do-minimum baseline and at least two materially different credible interventions; explain ruled-out options rather than inventing feasibility.

**Acceptance criteria**
- **D06.A1** — Proposed future-state models show roles, decisions, hand-offs, exceptions and control implications and link material changes to participant requirements.
- **D06.A2** — Compare options on consistent scope, one-off/recurring/internal costs, time, dependencies, usability/adoption, control and value assumptions; retain source exclusions.
- **D06.A3** — If scores/weights are used, justify them and show sensitivity or uncertainty; distinguish source prices/claims from your evaluation.
- **D06.A4** — Recommend a provisional option/sequence with reasons, trade-offs and decisions needed; do not claim purchase or owner sign-off.

## D07 — Prioritisation, traceability and saved baseline
**When:** Stage 4 before any change notice  
**Required outputs:** `docs/requirements/PRIORITISED_BASELINE.md`, `docs/requirements/TRACEABILITY.csv`

**Work:** Create a feasible scope/priority baseline and keep the source-to-value chain visible. Save this version before Stage 5.

**Acceptance criteria**
- **D07.A1** — Priorities have rationale tied to need, control, dependency, value and delivery constraints; explain trade-offs rather than mark everything essential.
- **D07.A2** — Treat each material requirement as retained/deferred/rejected or unresolved with a reason and source/decision link.
- **D07.A3** — Trace material sources/needs to requirements, rule/design/option, user-goal acceptance criteria, later tests and intended measures; identify coverage gaps.
- **D07.A4** — Reproduce the pre-notice version through a dated commit/tag/PR and maintain RAID; do not manufacture earlier history after reading changes.

## D08 — Respond to changing constraints
**When:** Stage 5; after each notice  
**Required outputs:** `docs/change/CHANGE_IMPACT_01.md`, `docs/change/CHANGE_IMPACT_02.md`, `docs/change/CHANGE_IMPACT_03.md`

**Work:** For each of the three supplied notices, assess the effect on your saved baseline and request a decision. This is requirements/scope impact analysis, not the whole project.

**Acceptance criteria**
- **D08.A1** — Identify the notice, changed fact/assumption and affected or reasoned-unaffected participant requirements, processes, models and options.
- **D08.A2** — Show before/after scope/priority/cost/time/control/data/test/value implications and explain alternatives, risk and dependencies.
- **D08.A3** — Identify who must decide, the requested decision, evidence, status and residual uncertainty; do not present a request as approval.
- **D08.A4** — Retain the original and each response/re-baseline version, with traceability and RAID updates; address all three notices sequentially.

## D09 — Prepare UAT independently
**When:** Stage 6; before experiment results  
**Required outputs:** `docs/assurance/UAT_PLAN.md`, `docs/assurance/UAT_SCENARIOS.csv`

**Work:** Define acceptance coverage and your own test scenarios from your own baseline before reviewing supplier observations.

**Acceptance criteria**
- **D09.A1** — Plan states scope, roles, environment/data, entry/exit/readiness conditions, execution approach and evidence/defect handling.
- **D09.A2** — Each scenario has an ID, linked requirement/acceptance criterion, actor/preconditions, test data, action/steps and observable expected result.
- **D09.A3** — Cover positive, negative/exception, control/access and failure/recovery behaviour relevant to this project; justify omitted/blocked tests.
- **D09.A4** — Keep expected results independently derived. Mark tests not executed when no execution evidence exists; do not fabricate results.

## D10 — Assess observations, issues and readiness
**When:** Stage 6; after 24 August evidence  
**Required outputs:** `docs/assurance/OBSERVATION_AND_DEFECT_ASSESSMENT.csv`, `docs/assurance/READINESS_RECOMMENDATION.md`

**Work:** Assess the supplied prototype evidence against your needs. The prototype may differ from your option; explain that difference rather than changing your baseline to pass it.

**Acceptance criteria**
- **D10.A1** — Cite source observation/case IDs and distinguish an observed fact, an inferred issue, a proposed defect and an actual test outcome.
- **D10.A2** — For material issues, record affected need/test, impact/severity rationale, owner/next action, proposed disposition and retest evidence needed.
- **D10.A3** — Identify acceptance gaps and limits of operator samples, assistance, timing and causal claims; no unsupported clinical/security/legal or production approval.
- **D10.A4** — Give a proceed/conditional/defer recommendation with explicit readiness conditions, residual risks and decision owners.

## D11 — Value evaluation and operational transition
**When:** Stage 7; Week 8  
**Required outputs:** `docs/recommendation-and-benefits/BENEFITS_AND_TRANSITION_PLAN.md`

**Work:** Evaluate what the supplied evidence can support and propose how the selected intervention would be introduced and measured. Address adoption only to the extent needed for the BA recommendation.

**Acceptance criteria**
- **D11.A1** — Each material proposed benefit/measure has a definition/formula, baseline/source or missing-data status, target/assumption, owner, collection method and review period.
- **D11.A2** — Distinguish observed result, forecast benefit, capacity value and cash; state confounding, attribution and data gaps.
- **D11.A3** — Cover affected roles, training/communication needs, open-case/data treatment, support, cutover/rollback dependencies and appropriate approvals for the proposed scope.
- **D11.A4** — Identify what would confirm value or trigger correction/deferment. A full organisational change-management campaign or live deployment is not required.

## D12 — Executive playback and professional submission
**When:** Stage 7; Week 8  
**Required outputs:** `docs/recommendation-and-benefits/EXECUTIVE_PLAYBACK.pdf`, `README.md`, `CONTRIBUTIONS.md`, `submission/FINAL_SUBMISSION.md`

**Work:** Deliver a concise decision-focused playback and a navigable final portfolio in your separate Mettelo delivery repository.

**Acceptance criteria**
- **D12.A1** — Playback explains need/evidence, option decision, costs/value assumptions, control/readiness conditions, remaining uncertainty and requested next decisions.
- **D12.A2** — Final index maps D01–D12 to actual deliverable paths and final versions; disclose justified unresolved/blocked items rather than hide them.
- **D12.A3** — Reproduction instructions, meaningful issues/branches/commits/material PRs, individual contribution and honest review/AI-assistance evidence are accessible.
- **D12.A4** — Verified designated Mettelo access, final commit and v1.0-mettelo-submission tag resolve to the submitted outputs; hand over the delivery repository URL through the cohort route.


## How review works
Use the matching task ID, source IDs and acceptance-check IDs in issues/PR reviews. The participant produces the work; a facilitator/assessor reviews it against these checks and the weighted rubric. Functional/clinical/security/legal/data approval remains with the appropriate simulated owner and must be marked unavailable where it cannot be obtained.

The timeline and release gates control when evidence is opened. Prepare D09 before receiving Stage 6 results. Retain the D07 pre-change baseline and each D08 response. The required final handover is a separate repository URL and tag, not answer files pushed to the Mettelo master.

At submission, include one index row per D01–D12 with output path/section, final version, self-review status, known gap and approval/review evidence if available. All twelve tasks need a substantive response; a blocked item needs evidence, impact and next action, not an empty file or invented result. Assessment rewards reasoning and coverage rather than document count.
