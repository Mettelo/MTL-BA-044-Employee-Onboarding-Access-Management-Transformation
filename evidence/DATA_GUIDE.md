# Joiner/access evidence — dictionary and extraction basis
**Mettelo BA-044 · Stage 3 · Snapshot 30 June 2026, 18:00 UK**
All worker-level records are fictional. There are no real names, addresses, salaries, health details or credentials.

## Population and observation
operational_data.csv contains 360 included joiner requests first raised in April (90), May (120) and June (150). access_request_records.csv contains 1,000 application requests; service_incidents.csv 125 incidents; new_starter_feedback.csv 215 voluntary responses. leaver_access_records.csv is a separate population of 120 leavers. These units are not additive headcount.

The board groups by request month and observes through the common cutoff. Some June requests have future July starts. They must not automatically count as failed day-one outcomes. Earlier cohorts have longer to progress. The dataset is a constructed training population, not an audited workforce census.

## Joiner fields
joiner_id is unique; employee_local_id is invented. department and work_mode are source groupings. request_date records first included request. original_start_date and effective_start_date retain the original and latest HR date at cutoff, not a complete change-event history. date_changed indicates a difference, not when every downstream team learned of it.

ticket_closed_date records existing closure, not evidence that equipment arrived or all access worked. laptop_delivered_date is a delivery record. first_core_login_date is core identity use only, not every application. manager_confirmed_ready is yes/no/unconfirmed at snapshot; it is a source statement, not an independently calculated whole-access test.

All joiner dates have calendar-day precision. No exact start time, full HR event acknowledgements or working-day calendar is supplied. Blank event dates mean not observed by cutoff. Future planned starts are allowed; future actual events are censored.

## Access requests
access_request_id is unique and joiner_id links the source. application identifies directory, expenses or client_portal work; it is not a complete entitlement inventory. access_type is standard/privileged. Manager approval, application-owner approval, provisioning and user verification are separate source events. A later missing event is not zero elapsed time.

source_approval_evidence describes where evidence was retained. expiry_date is blank where no expiry evidence was supplied. That does not prove active access forever or an appropriate exception; it is a question for investigation. The pack supplies no future role/access matrix or automatic grant rule.

## Incidents, feedback and leavers
Incidents are event records linked to joiners; logged/resolved dates and theme are observations, not validated causes. Feedback is voluntary and after a start; ratings are ordinal, not representative satisfaction or a monetary loss measure.

Leaver timestamps include BST offset. leaving_effective_at is distinct from directory, SaaS and physical-pass events. Blank revocation is unverified, not confirmation of active or revoked access. Source notes such as default_time are reported labels. The leavers are not the joiners and cannot be joined by similar names or row positions.

## Measures and financial limits
Distinguish request volume, people started, closure, delivery, login, required application readiness and control confirmation. No complete lost-days, client billing, security-loss or workforce-change population is provided. Capacity planning rates are not automatic cash savings.

Preserve raw sources and document joins, cutoffs, planned versus actual events, exclusions and assumptions. A clean analysis key does not prove production identity or integration is reliable.

## Later experiment
pilot_observations.csv has 80 observations from 40 historical joiners J0211–J0250, baseline replay 17 August and portal trial 19 August. paired_case_id links modes. task_seconds measures an operator task; visibility/expiry flags are observations, not acceptance or security certification. operator_assisted affects independence. Read the Stage 6 pack released 24 August before interpreting results.
