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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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

University, Higher Education, Education, Belgium, Europe, Flanders, Research Data, Research Repository, Open Data, Course Catalog, Identity Federation, OAI-PMH, Dataverse, OpenSearch, Public Research University

## APIs

Every surface below is `x-operator: institution` — KU Leuven's own host, inside its own
134.58.0.0/16 address space. No vendor contract (Figshare, Elsevier Pure, Ex Libris, Symplectic,
Dataverse.org hosted) is attributed to this institution.

- **ICTS Data Services API (OpenSearch gateway)** — `https://dataservice.kuleuven.be`. Eight public,
  unauthenticated index families: staff directory, academic CVs (with ORCID iDs), organisational
  chart, programme guide, research projects, research teams, research infrastructure, vacancies —
  each in a Dutch and an English index. Docs (Dutch):
  https://admin.kuleuven.be/icts/services/dataservices ·
  Contract: [openapi/ku-leuven-data-services-api-openapi.yml](openapi/ku-leuven-data-services-api-openapi.yml)
  (derived by API Evangelist from KU Leuven's documentation and verified live — KU Leuven publishes
  no machine-readable description of this surface itself).
- **Research Data Repository (RDR)** — `https://rdr.kuleuven.be/api`. Self-hosted Dataverse 6.7.1,
  830 published datasets, DataCite repository client BRVZ.RDR, prefix 10.48804. It serves its own
  OpenAPI publicly at https://rdr.kuleuven.be/openapi. The 36 RDR entries in `apis.yml` are
  tag-splits of this **one** deployment, and the contract is upstream open-source Dataverse's work:
  KU Leuven operates the deployment and owns the data, it does not author the API.
- **RDR OAI-PMH** — `https://rdr.kuleuven.be/oai`. "KU Leuven RDR Dataverse OAI Archive".
- **Lirias OAI-PMH** — `https://lirias.kuleuven.be/oai`. The KU Leuven Association institutional
  publication repository. Previously uncatalogued.
- **Shibboleth Identity Provider (SAML 2.0 metadata)** — `https://idp.kuleuven.be/idp/shibboleth`.
  entityID `urn:mace:kuleuven.be:kulassoc:kuleuven.be`, registered by the Belnet federation,
  asserting REFEDS SIRTFI and Research & Scholarship. Previously uncatalogued.
- **Individual Timetable (Uurrooster) API** — SAP OData, OAuth 2.0 authorization-code grant with
  SAML fallback, credentials issued by KU Leuven on request. The production host did not resolve
  from the public internet on 2026-08-19, so no contract is recorded for it.

## Education-regime conformance

Five of the twelve `education` regime domain standards are met, all by institution-operated
surfaces: **oai-pmh** (two endpoints), **datacite** (repository client BRVZ.RDR), **shibboleth** and
**saml** (own IdP metadata), **orcid** (carried in the cv index and required for RDR deposit).
Not found: scim, lti, oneroster, ed-fi, caliper, qti, crossref. See
[conformance/ku-leuven-education-standards.yml](conformance/ku-leuven-education-standards.yml).

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/ku-leuven-plans-pricing.yml](plans/ku-leuven-plans-pricing.yml)
- Rate Limits: [rate-limits/ku-leuven-rate-limits.yml](rate-limits/ku-leuven-rate-limits.yml)
- FinOps: [finops/ku-leuven-finops.yml](finops/ku-leuven-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.kuleuven.be
- Developer Portal (ICTS Data Services): https://admin.kuleuven.be/icts/services/dataservices
- GitHub: https://github.com/kuleuven
- LinkedIn: https://www.linkedin.com/school/ku-leuven/
- Source Code (KU Leuven Libraries): https://github.com/KU-Leuven-Libraries

## Notes

Re-profiled on 2026-08-19 under the API Evangelist university pipeline, which settles **who operates
each surface** before saving anything. Every external pointer in `apis.yml` was probed on that date
and returned HTTP 200.

Corrections to the June 2026 profile:

- The RDR OpenAPI is **not** IP-restricted. `https://rdr.kuleuven.be/openapi` returns 200 publicly
  with 425 paths. Its `info.title` is "Dataverse API" and it carries no `servers` block — the copy
  in `openapi/_original/` was retitled and given a server at harvest time and is therefore not
  byte-pristine; see `lifecycle/ku-leuven-lifecycle.yml`.
- The ICTS APIs are not documentation-only. They are served by a live OpenSearch gateway at
  `dataservice.kuleuven.be` that answers unauthenticated queries; the earlier profile recorded the
  documentation pages but never the gateway.
- Three surfaces were missing entirely: the curriculum, research-project, research-team and
  research-infrastructure indices; both OAI-PMH endpoints; and the Shibboleth IdP metadata.

Open findings:

- An unpublished index name on `dataservice.kuleuven.be` returns an HTML **503** from the front
  proxy rather than a 404, so a typo is indistinguishable from an outage.
- Snapshot index names reveal data staleness: the research-project index had not been rebuilt in
  over sixteen months as of 2026-08-19.
- `https://www.kuleuven.be/.well-known/security.txt` exists but its `Expires` value (2026-04-16) is
  both malformed and in the past.
- No versioning, changelog, deprecation policy, status page, published scopes or self-serve
  credential exists anywhere in the estate.
- The directory, CV and organigram indices publish staff names, work addresses and work telephone
  numbers openly. This is deliberate who-is-who publication by KU Leuven; personal values are
  redacted from the examples in this repository under the API Evangelist PII guardrail.

No endpoints or properties were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
