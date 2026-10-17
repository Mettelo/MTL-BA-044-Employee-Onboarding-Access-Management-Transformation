# MTL-BA-044 — tasks, deliverables and acceptance criteria

**Pathway: Technical Business Analyst**

An integration analysis and assurance handover for a bounded HR-to-service-to-identity capability. No working connector, live provisioning or full organisational change programme.

These are assignment acceptance criteria used by the assessor. When an output asks you to author solution acceptance criteria, those are your proposed conditions for the business/system/product; they are not supplied answers.

## T1 — Bound the integration

**Task:** Bound the integration to inform the commissioning decision.

**Submit:** System context diagram, integration scope and ownership questions.

**Use:** Systems pack and technical source bundle. Locate primary records through the release manifest; participant outputs named as inputs are your own work.

**Acceptance criteria (10% of assessment):**

- **T1-AC1:** Distinguish authoritative HR data, task status, identity and independent applications.
- **T1-AC2:** Identify trust boundaries and business owners.
- **T1-AC3:** Separate access approval from technical provisioning.
- **T1-AC4:** State unavailable interfaces and out-of-scope applications.

**Review:** Check the output against every criterion, record unresolved questions and cross-reference related outputs rather than duplicating inconsistent versions.

## T2 — Specify interface behaviour

**Task:** Specify interface behaviour to inform the commissioning decision.

**Submit:** Interface Requirements Specification.

**Use:** Interface fragments and stakeholder constraints. Locate primary records through the release manifest; participant outputs named as inputs are your own work.

**Acceptance criteria (20% of assessment):**

- **T2-AC1:** Define purpose, producer/consumer, triggers, contract fields, validation and acknowledgement needs.
- **T2-AC2:** Cover daily read-only export and prospective interface separately.
- **T2-AC3:** Specify duplicate/out-of-order/missing-event handling.
- **T2-AC4:** Identify unresolved service levels and approval dependencies.

**Review:** Check the output against every criterion, record unresolved questions and cross-reference related outputs rather than duplicating inconsistent versions.

## T3 — Define data transformation

**Task:** Define data transformation to inform the commissioning decision.

**Submit:** Source-to-target mapping and technical data dictionary.

**Use:** Raw schemas and sample payloads. Locate primary records through the release manifest; participant outputs named as inputs are your own work.

**Acceptance criteria (20% of assessment):**

- **T3-AC1:** Identify source/target fields, keys, types, transformation/null/rejection rules and owners.
- **T3-AC2:** Distinguish observed schemas from proposed mappings.
- **T3-AC3:** Avoid joining on names.
- **T3-AC4:** Address time zone, date revision and evidence minimisation.

**Review:** Check the output against every criterion, record unresolved questions and cross-reference related outputs rather than duplicating inconsistent versions.

## T4 — Model event and failure paths

**Task:** Model event and failure paths to inform the commissioning decision.

**Submit:** Sequence/event-flow diagrams and recovery specification.

**Use:** Operational cases and failure log. Locate primary records through the release manifest; participant outputs named as inputs are your own work.

**Acceptance criteria (20% of assessment):**

- **T4-AC1:** Cover new joiner, revised start date after task closure, leaver and privileged-expiry paths.
- **T4-AC2:** Include timeout/duplicate/replay and partial failure.
- **T4-AC3:** Specify reconciliation and manual recovery ownership.
- **T4-AC4:** Distinguish directory disable from independent-app revocation.

**Review:** Check the output against every criterion, record unresolved questions and cross-reference related outputs rather than duplicating inconsistent versions.

## T5 — Define quality and control requirements

**Task:** Define quality and control requirements to inform the commissioning decision.

**Submit:** Non-functional and control requirements with measurable verification proposals.

**Use:** Security interviews, source bundle and constraints. Locate primary records through the release manifest; participant outputs named as inputs are your own work.

**Acceptance criteria (15% of assessment):**

- **T5-AC1:** Cover security, privacy, availability, audit, latency and recoverability.
- **T5-AC2:** Make targets explicit proposals pending owner agreement.
- **T5-AC3:** Justify thresholds from needs.
- **T5-AC4:** Avoid exposing credentials or assuming blanket access.

**Review:** Check the output against every criterion, record unresolved questions and cross-reference related outputs rather than duplicating inconsistent versions.

## T6 — Plan integration assurance and transition

**Task:** Plan integration assurance and transition to inform the commissioning decision.

**Submit:** Integration test scenarios, reconciliation approach and cutover/rollback plan.

**Use:** All three notices and optional experiment observations. Locate primary records through the release manifest; participant outputs named as inputs are your own work.

**Acceptance criteria (10% of assessment):**

- **T6-AC1:** Link scenarios to interface requirements and mappings.
- **T6-AC2:** Include missed file, malformed row, late change, duplicate event and partial revoke.
- **T6-AC3:** Distinguish simulated observations from executed tests.
- **T6-AC4:** Evaluate early pilot and unavailable writeback with entry/exit and rollback conditions.

**Review:** Check the output against every criterion, record unresolved questions and cross-reference related outputs rather than duplicating inconsistent versions.

## T7 — Handover for engineering review

**Task:** Handover for engineering review to inform the commissioning decision.

**Submit:** Technical decision record and indexed specification baseline.

**Use:** Participant technical analysis. Locate primary records through the release manifest; participant outputs named as inputs are your own work.

**Acceptance criteria (5% of assessment):**

- **T7-AC1:** Document trade-offs and unresolved contracts/owners.
- **T7-AC2:** Identify what engineering can estimate and what requires discovery.
- **T7-AC3:** Reconcile models and specifications.
- **T7-AC4:** Recommend readiness with explicit conditions rather than claiming deployment approval.

**Review:** Check the output against every criterion, record unresolved questions and cross-reference related outputs rather than duplicating inconsistent versions.

## Portfolio-wide conditions
All material conclusions must have evidence references or be labelled proposals/assumptions. Preserve raw data, explain transformations and report limitations. Keep diagrams readable and terms/identifiers consistent. Supply an index to every task and identify contributors and AI assistance. Additional documents earn no credit merely for their volume. No completed participant deliverables are provided in the master.


## Team handover check

Use [the project-specific deliverables checklist](../submission/DELIVERABLES_CHECKLIST.md) to verify every required component and final submission record. The checklist specifies packaging; the task acceptance criteria define analytical quality.
