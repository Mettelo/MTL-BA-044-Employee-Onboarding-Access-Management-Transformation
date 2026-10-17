# Mettelo BA-044 — team submission

Your team is completing **Onboarding and access: technical integration analysis** for **Harrowgate Professional Services**.

**Business question:** What bounded HR-to-service-to-identity interface behaviour, data mapping and recovery controls can engineering design and estimate, and which owner decisions or capabilities remain blockers?

Start with [the exact deliverables checklist](DELIVERABLES_CHECKLIST.md), then follow [the submission guidelines](SUBMISSION_GUIDELINES.md) for repository naming, review access, history and the final tag.

| Task | Required handover content | Weight |
|---|---|---|
| T1 | System context/trust-boundary diagram; integration scope; ownership and unresolved contract questions. | 10% |
| T2 | Interface Requirements Specification covering producer/consumer, triggers, contract validation, acknowledgement and exception behaviour. | 20% |
| T3 | Source-to-target mapping; technical data dictionary; identifiers, types, null/transformation/rejection rules and ownership. | 20% |
| T4 | Sequence/event-flow diagrams for joiner, changed date, leaver and privileged expiry; failure/replay/reconciliation specification. | 20% |
| T5 | Non-functional and control requirements with measurable proposed verification and owner approval status. | 15% |
| T6 | Integration test scenarios; reconciliation approach; cutover/rollback plan with dependencies and entry/exit criteria. | 10% |
| T7 | Technical decision record; consistent specification index; trade-offs, blockers and engineering-review readiness recommendation. | 5% |

Every task must appear in your own `submission/FINAL_SUBMISSION.md` with links to the submitted files/sections and any limitations. Keep answers in a separate delivery repository, never this master.
