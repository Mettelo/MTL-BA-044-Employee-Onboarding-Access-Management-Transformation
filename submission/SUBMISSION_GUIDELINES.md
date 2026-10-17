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

## 3. Establish a professional structure

The participant's repository should separate original evidence from their analysis and make the decision trail easy to follow. One suitable arrangement is:

```text
README.md
CONTRIBUTIONS.md
data/raw/                  supplied evidence, unchanged
data/analysis/             calculations and transformation notes
docs/initiation/
docs/discovery/
docs/current-state/
docs/requirements/
docs/options-and-future-state/
docs/change/
docs/assurance/
docs/recommendation-and-benefits/
submission/FINAL_SUBMISSION.md
```

This is a delivery organisation example, not a set of pre-completed templates. Equivalent structures are acceptable if reviewers can locate the work and its history. Use an index rather than duplicating the same content in multiple documents. Retain only sources the cohort has released; do not copy future stages early for a controlled exercise.

Your README must explain the fictional engagement, your role and scope, repository navigation, evidence/release version, how to reproduce calculations, the recommendation and its limitations. Label it a **Mettelo simulated Business Analyst engagement** and identify individual/team contributions and AI assistance honestly.

## 4. Work through issues, branches and pull requests

Create issues for meaningful analysis questions and delivery work. Link each to the business decision or outcome it supports. Use a branch for a substantial change, such as discovery synthesis, a process model, requirements baseline or change impact. Make descriptive commits throughout the engagement, with messages explaining the substantive change.

Open pull requests **inside the delivery repository** for material merges. Explain the change, source evidence, validation and decisions still needed. Link relevant issues and participant-owned requirement/decision/test IDs. Review important changes before merging where a peer is available. A solo participant should record a structured self-review and identify it as self-review; do not invent a second reviewer.

Do not upload the entire portfolio in one final commit. Reviewers need to see how the participant responded to evidence and changed their judgement. Do not manufacture earlier work dates or rewrite history to imply that later evidence was known at initiation.

## 5. Keep individual contribution evidence

Each contributor uses their own GitHub account. Keep CONTRIBUTIONS.md current with responsibilities, substantive contributions, issue/PR/commit references and review activity. Avoid presenting the same team output as every person's independent work. A coordinator can assemble the final portfolio, but the history should show who developed, checked and changed the analysis.

For individual delivery, identify your own work, source material, external assistance and any simulated/unavailable validation. A stakeholder interview supplied by Mettelo is source evidence, not an interview you personally conducted with a real client.

## 6. BA-specific portfolio coverage

Provide your own:

- Business need, scope, assumptions and stakeholder analysis, supported by an elicitation record and unresolved questions.
- Current-state and proposed process models, with exception paths and evidence-based distinction between symptoms and plausible causes.
- Business, functional, non-functional and transition requirements; business-rule proposals; appropriate use cases or user stories; and testable acceptance criteria.
- Prioritisation and options analysis with cost completeness, uncertainty, operational effort and control implications.
- Traceability connecting material sources, needs, requirements, decisions, changes, acceptance evidence and intended outcomes.
- RAID, response to all three change notices, and versioned baseline decisions.
- UAT approach and participant-created scenarios, analysis of supplied observations, defect/issue decisions and a readiness recommendation.
- Final recommendation, communication/playback material, change/adoption implications and benefits evaluation.

The assessor rewards quality and coherence, not one document per bullet. Do not submit the supplied sources or supplier notebook as though they were your analysis. Do not fabricate stakeholder approval where the simulation cannot provide it.

## 7. Reproduce and review

Preserve raw CSVs. Explain joins, filters, cohorts, cutoff dates, formulas, units and exclusions for every material calculation. Keep diagrams readable, source references accessible and versions consistent. Describe validation checks in plain language. No paid tool, executable system or production deployment is required.

Before handover, check names/dates/numbers, link targets, open-case treatment, payment retries, traceability, requirement testability, unresolved conflicts, change impacts, UAT independence and cost assumptions. Remove real personal data and credentials. Include limitations that could change the decision.

## 8. Final submission record and freeze

Create `submission/FINAL_SUBMISSION.md` **in your delivery repository**, containing team/participant name, Team Lead where relevant, repository URL, final branch, final commit/tag, indexed deliverable links, contribution evidence, reproduction instructions, access confirmation, known limitations and outstanding decisions.

Create a tag or release named:

`v1.0-mettelo-submission`

State any later correction explicitly rather than silently moving the reviewed baseline. Mettelo reviews the tagged version unless the cohort agrees otherwise. Ensure the tag resolves to the intended final commit and that linked files are present there.

## 9. Submit the repository URL

The official submission is your **delivery repository URL**, through the submission route supplied by Mettelo for the cohort. Include the tag and final submission record as requested by that route. Do not submit project files by email.

A submission is incomplete until naming, review access, version, contribution history and final outputs can be verified. Keep the master resource library distinct from your delivery work throughout.

## Mandatory D01–D12 submission index

Use the [task/deliverable/acceptance contract](../project/TASKS_DELIVERABLES_AND_ACCEPTANCE_CRITERIA.md) to see precisely what to submit. Create its outputs in your **own delivery repository**. Include one final index row for every task D01–D12, pointing to the actual path or section, final version/commit, acceptance self-review status, known gap and available review evidence.

D04 includes your requirements and **solution acceptance criteria**; D05 contains this project's domain-specific models; D09 includes your own UAT expectations; D10 assesses evidence without inventing execution; D08 contains the three change responses. The contract's 48 checks are Mettelo's assignment criteria, not answers to those tasks.

Equivalent accessible formats or combined substantial documents are allowed only if the index makes every required task and check independently reviewable. Do not submit empty files, supplied source packs relabelled as analysis, or invented approvals. Keep the existing repository naming, access, Git workflow, contribution, final tag and URL-handover rules above.
