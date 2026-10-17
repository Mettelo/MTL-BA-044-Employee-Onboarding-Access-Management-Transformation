# MTL-BA-044 — required team deliverables

**Pathway:** Technical Business Analyst

**Business decision:** What bounded HR-to-service-to-identity interface behaviour, data mapping and recovery controls can engineering design and estimate, and which owner decisions or capabilities remain blockers?

**Final audience:** HR system owners, IT engineering, identity/application owners and Security.

The team submits its own analysis listed below. These are assignment instructions, not completed answers or a template containing a solution. Every required item must be easy for a reviewer to locate in the tagged version.

## Required analytical packages

### T1 — Bound the integration

**Suggested location:** `analysis/01-integration-scope/`. Equivalent files/sections are acceptable.

**Required content:** System context/trust-boundary diagram; integration scope; ownership and unresolved contract questions.

**Why the business needs it:** Agree which systems and owners the proposed integration actually connects.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every T1-AC1 to T1-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

### T2 — Specify interface behaviour

**Suggested location:** `analysis/02-interface-requirements/`. Equivalent files/sections are acceptable.

**Required content:** Interface Requirements Specification covering producer/consumer, triggers, contract validation, acknowledgement and exception behaviour.

**Why the business needs it:** Give engineering explicit interface behaviour rather than a vague request to synchronise systems.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every T2-AC1 to T2-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

### T3 — Define data transformation

**Suggested location:** `analysis/03-data-mapping/`. Equivalent files/sections are acceptable.

**Required content:** Source-to-target mapping; technical data dictionary; identifiers, types, null/transformation/rejection rules and ownership.

**Why the business needs it:** Prevent incorrect joins, silent field loss and ambiguous transformations between source and target.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every T3-AC1 to T3-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

### T4 — Model event and failure paths

**Suggested location:** `analysis/04-events-recovery/`. Equivalent files/sections are acceptable.

**Required content:** Sequence/event-flow diagrams for joiner, changed date, leaver and privileged expiry; failure/replay/reconciliation specification.

**Why the business needs it:** Explain how the integration behaves when events change, arrive twice or fail partway through.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every T4-AC1 to T4-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

### T5 — Define quality and control requirements

**Suggested location:** `analysis/05-quality-controls/`. Equivalent files/sections are acceptable.

**Required content:** Non-functional and control requirements with measurable proposed verification and owner approval status.

**Why the business needs it:** Make quality and control needs measurable enough for owners to review and engineering to estimate.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every T5-AC1 to T5-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

### T6 — Plan integration assurance and transition

**Suggested location:** `analysis/06-integration-transition/`. Equivalent files/sections are acceptable.

**Required content:** Integration test scenarios; reconciliation approach; cutover/rollback plan with dependencies and entry/exit criteria.

**Why the business needs it:** Provide a credible way to validate and introduce the integration without hiding recovery obligations.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every T6-AC1 to T6-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

### T7 — Handover for engineering review

**Suggested location:** `analysis/07-engineering-handover/`. Equivalent files/sections are acceptable.

**Required content:** Technical decision record; consistent specification index; trade-offs, blockers and engineering-review readiness recommendation.

**Why the business needs it:** Give engineers a consistent handover and a clear view of decisions that still block design.

**Completion checks:**

- [ ] All content named above is present and readable.
- [ ] Every T7-AC1 to T7-AC4 condition in [the task specification](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) is addressed.
- [ ] Material claims have source references or are labelled assumptions/proposals.
- [ ] The final index links the exact files/sections and notes unresolved limitations.

## Repository and submission records required from every team

- [ ] A separate repository named `MTL-BA-044-<team-name>`, following the cohort's ownership/access route.
- [ ] A README explaining this simulated commission, the business decision, navigation and how to reproduce calculations or open visual artefacts.
- [ ] CONTRIBUTIONS.md identifying each contributor, substantive work/review references and declared assistance.
- [ ] Preserved raw evidence and calculation/transformation notes for material numerical claims; external reference/provenance links where used.
- [ ] Meaningful issues, branches, commits and material PR/review history inside the team repository; solo work may use clearly labelled self-review.
- [ ] `submission/FINAL_SUBMISSION.md` containing team/lead details, repository URL, final branch, exact final commit/tag, a row for each task ID linking its outputs, unresolved decisions, limitations, reproduction/opening instructions, contribution links and reviewer-access confirmation.
- [ ] A tag or release named `v1.0-mettelo-submission` that resolves to the reviewed final version.
- [ ] Verified Mettelo reviewer access to files, history, issues and pull requests for that version.
- [ ] The repository URL, tag and final index submitted through the route supplied for the cohort; do not email project files or invent a submission portal.

## Accepted formats and completion standard

Use readable Markdown/PDF/documents, spreadsheets/CSV with clear calculations and diagram/prototype formats reviewers can open. Include a readable export if the authoring tool or sharing permission might block access. A working application is not required. Keep editable/source material where needed to check calculations and analysis.

Several outputs may share a document or workbook; link the specific sections from each task row. Do not omit one because its content overlaps another. Do not fill the portfolio with unrelated BA deliverables to compensate for missing required work.

No working connector, live credentials/provisioning, complete entitlement catalogue, enterprise HR procurement, hiring-policy redesign or full organisational change programme. Specify interfaces and controls; do not implement them or invent an approved target mapping.

Do not submit supplied interviews or source packs as your own research, simulated observations as tests you ran, or proposed approval as signed agreement. Record what remains unknown. The [weighted assessment](../project/ASSESSMENT_CRITERIA.md) applies to the tasks above.
