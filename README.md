# KU Leuven (ku-leuven)

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
