# HR, service and identity technology context
**Mettelo BA-044 · Stage 3 · IT source note, 20 July**

## Current systems
PeopleRecord holds approved employment dates/status. Its read-only export runs daily at 06:00 UK. ServiceQueue maintains tasks and closure. The directory handles core identity. Expenses and client applications have separate owners and some independent administration. CourierDesk records dispatch/delivery. Facilities maintains a restricted local register.

Stable local employee IDs exist in the teaching extract. They do not prove every production application uses the same identifier or that names are safe join keys. The export has no version-sequence acknowledgement or guaranteed closed-ticket reopening.

## Current capability claims
IT believes ServiceQueue could support controlled fields, ownership and date-change tasks. Indicative effort: 12 analyst days at £450/day plus 8 integration days at £650/day; annual additional support £4,000–£6,000. No resource booking, access model, audit coverage or recovery demonstration is approved.

Directory disable does not demonstrate revocation of independent SaaS, active sessions, client accounts or physical passes. Courier dispatch is not delivery. A combined view still requires authoritative events, owners, evidence and correction/fallback.

## Unscored commercial inputs
JoinerHub quote: £35,000 setup plus £10,000/year, two-year minimum. Excludes courier interface, client/SaaS connectors, data cleansing, Security/worker-data review, training/backfill and VAT. Indicative HR acknowledgement interface £12,000, with no committed delivery date at discovery.

WorkforceSuite quote: from £60,000 setup plus £18,000/year, three-year term. Claims broader HR workflows; excludes some identity/client integration. The annual figure exceeds the initial ceiling. It has not been selected or assessed against approved needs.

No total-cost comparison or preferred option is supplied. Existing-tool/process improvement or a sequenced narrow capability may be considered, but neither is assumed sufficient or free.

## Operational and governance concerns
A new portal must not give everyone access to all employment information. Role/purpose, audit, retention and supplier handling need owner review. Technical provisioning and business authority are different. A changed assignment or start date can alter outstanding work after a ticket closes.

IT asks for representative date-change, approval-missing, remote delivery, privileged expiry, independent leaver and missed-file scenarios. Those concerns are not a complete requirements or test catalogue. The BA should establish needs and define independent acceptance evidence.

## Unknowns
Complete application/session inventory, client owner commitments, final licence coverage, peak workload, exact integration scope, latency/recovery criteria, record retention and committed capacity remain unavailable. No real worker data, credentials or live provisioning are provided. The later prototype is isolated, not proof of contracted capability or security sign-off.
