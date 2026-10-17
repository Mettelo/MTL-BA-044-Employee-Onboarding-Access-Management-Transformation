# Mettelo BA-044 — separate delivery repository and submission guidelines

**Mettelo Business Analyst Project Studio · MTL-BA-044 · v2.0**  
This guide adapts the established Mettelo submission and team-repository standards linked in [source provenance](../reference/OFFICIAL_REFERENCES_AND_SOURCE_PROVENANCE.md). The master is a resource library, not a place to submit participant answers.

## 1. Create the delivery repository

Use one **separate** repository for the participant/team's work, named:

`MTL-BA-044-<team-name>`

For individual participation, replace team-name with the individual identifier agreed with the cohort coordinator. Use a readable, professional identifier. Do not use the full master resource repository name.

Where cohort permissions allow, create the delivery repository inside the Mettelo GitHub organisation. This remains a distinct participant/team repository controlled for delivery and review. If it is under a personal account or another organisation, follow the cohort's Mettelo access route before submission. GitHub does not normally let a personal repository invite an entire organisation directly.

**Never commit participant answers to this master, open answer pull requests against it or treat a local master submission folder as your submission.** The only files in this master's submission directory are instructions.

## 2. Verify Mettelo access early

The established Mettelo model requires access to files, branches, commit history, issues, pull requests/reviews, contribution evidence, validation and final outputs. Follow the designated cohort route: transfer to Mettelo where instructed or grant access to the specific reviewer account/team supplied for your cohort.

No reviewer account, portal URL or form link is invented in this guide. Use the route Mettelo provides. Confirm the reviewer can actually open the repository and the submitted version; a copied URL alone is not verification. Keep access active until review and verification are complete. A private repository is not a completed submission if the reviewer cannot inspect it.

## 3. Organise the pathway portfolio

Use a README, CONTRIBUTIONS.md, preserved raw evidence, your own analysis folder and submission/FINAL_SUBMISSION.md. Organise analysis around this project's task IDs. There is no mandatory common lifecycle folder structure.

Your README identifies the simulated Mettelo commission, role, scope, source versions, navigation, calculation instructions and authorship/AI assistance.

## 4. Work through issues, branches and pull requests

Create issues for meaningful analysis questions and delivery work. Link each to the business decision or outcome it supports. Use a branch for a substantial change, such as discovery synthesis, a process model, requirements baseline or change impact. Make descriptive commits throughout the engagement, with messages explaining the substantive change.

Open pull requests **inside the delivery repository** for material merges. Explain the change, source evidence, validation and decisions still needed. Link relevant issues and participant-owned requirement/decision/test IDs. Review important changes before merging where a peer is available. A solo participant should record a structured self-review and identify it as self-review; do not invent a second reviewer.

Do not upload the entire portfolio in one final commit. Reviewers need to see how the participant responded to evidence and changed their judgement. Do not manufacture earlier work dates or rewrite history to imply that later evidence was known at initiation.

## 5. Keep individual contribution evidence

Each contributor uses their own GitHub account. Keep CONTRIBUTIONS.md current with responsibilities, substantive contributions, issue/PR/commit references and review activity. Avoid presenting the same team output as every person's independent work. A coordinator can assemble the final portfolio, but the history should show who developed, checked and changed the analysis.

For individual delivery, identify your own work, source material, external assistance and any simulated/unavailable validation. A stakeholder interview supplied by Mettelo is source evidence, not an interview you personally conducted with a real client.

## 6. Required pathway outputs

- **T1:** System context diagram, integration scope and ownership questions.
- **T2:** Interface Requirements Specification.
- **T3:** Source-to-target mapping and technical data dictionary.
- **T4:** Sequence/event-flow diagrams and recovery specification.
- **T5:** Non-functional and control requirements with measurable verification proposals.
- **T6:** Integration test scenarios, reconciliation approach and cutover/rollback plan.
- **T7:** Technical decision record and indexed specification baseline.

Index each task and its acceptance criteria in FINAL_SUBMISSION.md. These replace generic end-to-end portfolio requirements. The endpoint is: An integration analysis and assurance handover for a bounded HR-to-service-to-identity capability. No working connector, live provisioning or full organisational change programme.

## 7. Reproduce and review

Preserve raw CSVs. Explain joins, filters, cohorts, cutoff dates, formulas, units and exclusions for every material calculation. Keep diagrams readable, source references accessible and versions consistent. Describe validation checks in plain language. No paid tool, executable system or production deployment is required.

Before handover, check evidence references, dates, numbers, terminology, diagram readability, consistency between outputs and every task acceptance criterion. Include limitations that could change the decision.

## 8. Final submission record and freeze

Create `submission/FINAL_SUBMISSION.md` **in your delivery repository**, containing team/participant name, Team Lead where relevant, repository URL, final branch, final commit/tag, indexed deliverable links, contribution evidence, reproduction instructions, access confirmation, known limitations and outstanding decisions.

Create a tag or release named:

`v1.0-mettelo-submission`

State any later correction explicitly rather than silently moving the reviewed baseline. Mettelo reviews the tagged version unless the cohort agrees otherwise. Ensure the tag resolves to the intended final commit and that linked files are present there.

## 9. Submit the repository URL

The official submission is your **delivery repository URL**, through the submission route supplied by Mettelo for the cohort. Include the tag and final submission record as requested by that route. Do not submit project files by email.

A submission is incomplete until naming, review access, version, contribution history and final outputs can be verified. Keep the master resource library distinct from your delivery work throughout.
