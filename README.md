# KU Leuven (ku-leuven)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

KU Leuven (Katholieke Universiteit Leuven) is a research university in Leuven, Belgium, founded in 1425 and ranked #45 in the QS World University Rankings 2025. This repository catalogs its public developer and API footprint as an [APIs.json](https://apisjson.org) profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ku-leuven/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ku-leuven-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Open Data, Belgium, Europe

## APIs

- **Research Data Repository (RDR) API** — Dataverse-based institutional research data repository; public info endpoints reachable, writes gated by token/ORCID/role. Docs: https://www.kuleuven.be/rdm/en/rdr/api-documentation
- **Person Information API** — Public personnel / who-is-who data. Docs: https://admin.kuleuven.be/icts/services/dataservices/api/person
- **Educational Offering (Onderwijsaanbod) API** — Programs and course components. Docs: https://admin.kuleuven.be/icts/services/dataservices/api/program-opleiding
- **Organizational Chart (Organigram) API** — Institutional organizational structure. Docs: https://admin.kuleuven.be/icts/services/dataservices/apiorganigraminformatie
- **Vacancies (Vacatures) API** — Job postings. Docs: https://admin.kuleuven.be/icts/services/dataservices/apivacatures
- **Individual Timetable (Uurrooster) API** — Personal timetable, OAuth 2.0 / SAML protected. Docs: https://admin.kuleuven.be/icts/services/dataservices/api/uurrooster

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/ku-leuven-plans-pricing.yml](plans/ku-leuven-plans-pricing.yml)
- Rate Limits: [rate-limits/ku-leuven-rate-limits.yml](rate-limits/ku-leuven-rate-limits.yml)
- FinOps: [finops/ku-leuven-finops.yml](finops/ku-leuven-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.kuleuven.be
- Developer Portal (ICTS Data Services): https://admin.kuleuven.be/icts/services/dataservices
- GitHub: https://github.com/kuleuven
- LinkedIn: https://www.linkedin.com/school/ku-leuven/
- Source Code (KU Leuven Libraries): https://github.com/KU-Leuven-Libraries

## Notes

All documentation and portal URLs above were probed and returned HTTP 200 on 2026-06-03. The RDR public API endpoint (`https://rdr.kuleuven.be/api/info/version`) was verified live and returned Dataverse version 6.7.1. RDR write operations and the intranet variants of the ICTS APIs are gated (API token, registered ORCID, Dataset Creator role, or service accounts). The RDR OpenAPI document at rdm.libis.kuleuven.be/apidoc/ is restricted to KU Leuven IP ranges and could not be verified externally. The LinkedIn school page returns HTTP 999 to automated clients (anti-scraping) but resolves in a browser. No endpoints or properties were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
