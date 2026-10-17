# Mettelo BA-044 — pathway-specific source evidence

**Release 2 · fictional source material, not an approved solution**

## Current export contract fragment — observed, not a target mapping
PeopleRecord produces a UTF-8 CSV at 06:00 UK daily. The interface below is an illustrative teaching sample separate from operational_data.csv; sample IDs do not add workers to the operational cohort. There is no acknowledged writeback before 28 September. No guarantee of delivery, ordering or complete history is recorded.

```csv
worker_ref,employment_status,effective_start_date,planned_end_date,manager_ref,work_location,source_updated_at
SYN-W-01,approved_joiner,2026-09-14,,SYN-M-08,remote,2026-09-03T16:35:00+01:00
SYN-W-02,leaver,2026-04-06,2026-09-03,SYN-M-12,office,2026-09-03T17:10:00+01:00
```

## ServiceQueue observed fields
The current ticket export exposes ticket_id (text), employee_local_id (text), ticket_status (open/closed), planned_start (date), assignee_team (text), last_modified (timestamp). A closed ticket is not guaranteed to reopen when planned_start changes. Source_updated_at is not an event sequence. The system owner has not confirmed whether worker_ref and employee_local_id share a complete crosswalk.

## Directory audit fragment
```json
{"operation_id":"SYN-OP-17","subject_id":"SYN-D-92","operation":"disable","recorded_at":"2026-09-03T17:12:00+01:00","result":"accepted"}
```
Accepted means the directory recorded the request; it does not establish revocation of every active session or independent application. IT has not confirmed retention or idempotency semantics.

## Fault notebook — synthetic technical probes
PROBE-01: the 06:00 export was not visible to ServiceQueue until 11:40; HR saw a successful file creation. No transport acknowledgement was available.
PROBE-02: the same filename was delivered twice; the receiving operator cannot establish whether it contained identical bytes.
PROBE-03: a date revision arrived after a joiner ticket was closed; the directory action and courier booking had different effective dates.
PROBE-04: directory disable was accepted; one independent application owner was unavailable.
PROBE-05: a row had a blank manager_ref and valid worker_ref; the receiver placed it in a generic queue. No authority for granting access was documented.
These are deliberately incomplete observations, not expected behaviour or completed test cases.

## Engineering questions
IT proposes polling; Security asks how replay is authorised and audited. HR rejects unnecessary disclosure of medical or salary data. Operations asks who owns rejected rows overnight. App owners question whether the pilot can include every SaaS product. Participants must propose contracts, mappings, failure handling and measurable acceptance conditions; none is supplied as an answer.
