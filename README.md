# KU Leuven

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

KU Leuven (Katholieke Universiteit Leuven) is a Flemish public research university in Leuven, Belgium, founded in 1425 and ranked in the QS world top 50. Re-profiled on 2026-08-19 with operator attribution settled before anything was saved, it is one of the few universities in this cohort whose machine-readable surface is genuinely its own: every host below resolves inside KU Leuven's own 134.58.0.0/16 address space, and no Figshare, Elsevier Pure, Ex Libris or Symplectic contract is attributed here. Its central programmable surface is the ICTS Data Services gateway at dataservice.kuleuven.be — an unauthenticated OpenSearch query API over eight public index families covering the staff directory, academic CVs, the organisational chart, the programme guide, research projects, research teams, research infrastructure and job vacancies — documented in Dutch at admin.kuleuven.be and confirmed live returning real records. It also runs the Research Data Repository (RDR), a self-hosted Dataverse 6.7.1 installation at rdr.kuleuven.be that serves its own OpenAPI publicly, mints DOIs as DataCite repository client BRVZ.RDR, and exposes OAI-PMH; the Lirias institutional repository exposes a second OAI-PMH endpoint; and idp.kuleuven.be serves SAML 2.0 Shibboleth metadata registered in the Belnet federation with REFEDS SIRTFI and Research & Scholarship assurance. Honest caveats: the 36 RDR entries below are tag-splits of ONE Dataverse deployment, and that contract is upstream open-source Dataverse's work — KU Leuven operates the deployment and owns the data, it does not author the API. There is no unified developer portal, no self-serve credential anywhere in the estate, no versioning on the data services gateway, and the personal timetable API's production host does not resolve from the public internet.

**Areas:** University · Higher Education · Education · Belgium · Europe · Flanders · Research Data · Research Repository · Open Data · Course Catalog · Identity Federation · OAI-PMH

## KU Leuven on APIs.io

Everything profiled for KU Leuven is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ku-leuven/](https://apis.io/providers/ku-leuven/)** — or go straight to one of the APIs or properties below.

### APIs (56)

- [KU Leuven Person Information API](https://apis.io/apis/ku-leuven/person/) — ICTS Data Services REST API exposing public personnel / who-is-who person information. An expanded intranet variant requires a service account.
- [KU Leuven Educational Offering (Onderwijsaanbod) API](https://apis.io/apis/ku-leuven/program/) — ICTS Data Services REST API exposing public educational offering data, including programs (opleidingen) and course components.
- [KU Leuven Organizational Chart (Organigram) API](https://apis.io/apis/ku-leuven/organigram/) — ICTS Data Services REST API exposing public organizational-structure information matching the institutional organizational chart. An expanded intranet…
- [KU Leuven Vacancies (Vacatures) API](https://apis.io/apis/ku-leuven/vacancies/) — ICTS Data Services REST API exposing public job vacancy / job posting data.
- [KU Leuven Individual Timetable (Uurrooster) API](https://apis.io/apis/ku-leuven/timetable/) — ICTS Data Services API exposing an individual's personal timetable. Protected by OAuth 2.0 (authorization code grant) with SAML as a fallback; OAuth client…
- [KU Leuven Access API](https://apis.io/apis/ku-leuven/ku-leuven-access-api/) — The Access API from KU Leuven — 23 operation(s) for access.
- [KU Leuven Add Files To Dataset API](https://apis.io/apis/ku-leuven/ku-leuven-addfilestodataset-api/) — Uploads a set of files to a dataset
- [KU Leuven Add File To Dataset API](https://apis.io/apis/ku-leuven/ku-leuven-addfiletodataset-api/) — Uploads a file for a dataset
- [KU Leuven Add Globus Files To Dataset API](https://apis.io/apis/ku-leuven/ku-leuven-addglobusfilestodataset-api/) — Uploads a Globus file for a dataset
- [KU Leuven Admin API](https://apis.io/apis/ku-leuven/ku-leuven-admin-api/) — The Admin API from KU Leuven — 131 operation(s) for admin.
- [KU Leuven Batch API](https://apis.io/apis/ku-leuven/ku-leuven-batch-api/) — The Batch API from KU Leuven — 3 operation(s) for batch.
- [KU Leuven Builtin Users API](https://apis.io/apis/ku-leuven/ku-leuven-builtin-users-api/) — The Builtin Users API from KU Leuven — 4 operation(s) for builtin users.
- [KU Leuven Datasetfields API](https://apis.io/apis/ku-leuven/ku-leuven-datasetfields-api/) — The Datasetfields API from KU Leuven — 1 operation(s) for datasetfields.
- [KU Leuven Datasets API](https://apis.io/apis/ku-leuven/ku-leuven-datasets-api/) — The Datasets API from KU Leuven — 92 operation(s) for datasets.
- [KU Leuven Datatags API](https://apis.io/apis/ku-leuven/ku-leuven-datatags-api/) — The Datatags API from KU Leuven — 1 operation(s) for datatags.
- [KU Leuven DataverseFeaturedItems API](https://apis.io/apis/ku-leuven/ku-leuven-dataversefeatureditems-api/) — The DataverseFeaturedItems API from KU Leuven — 1 operation(s) for dataversefeatureditems.
- [KU Leuven Dataverses API](https://apis.io/apis/ku-leuven/ku-leuven-dataverses-api/) — The Dataverses API from KU Leuven — 39 operation(s) for dataverses.
- [KU Leuven Edit API](https://apis.io/apis/ku-leuven/ku-leuven-edit-api/) — The Edit API from KU Leuven — 1 operation(s) for edit.
- [KU Leuven Files API](https://apis.io/apis/ku-leuven/ku-leuven-files-api/) — The Files API from KU Leuven — 20 operation(s) for files.
- [KU Leuven Harvest API](https://apis.io/apis/ku-leuven/ku-leuven-harvest-api/) — The Harvest API from KU Leuven — 7 operation(s) for harvest.
- [KU Leuven Inbox API](https://apis.io/apis/ku-leuven/ku-leuven-inbox-api/) — The Inbox API from KU Leuven — 1 operation(s) for inbox.
- [KU Leuven Info API](https://apis.io/apis/ku-leuven/ku-leuven-info-api/) — The Info API from KU Leuven — 49 operation(s) for info.
- [KU Leuven Ingest API](https://apis.io/apis/ku-leuven/ku-leuven-ingest-api/) — The Ingest API from KU Leuven — 1 operation(s) for ingest.
- [KU Leuven Licenses API](https://apis.io/apis/ku-leuven/ku-leuven-licenses-api/) — The Licenses API from KU Leuven — 6 operation(s) for licenses.
- [KU Leuven Localcontexts API](https://apis.io/apis/ku-leuven/ku-leuven-localcontexts-api/) — The Localcontexts API from KU Leuven — 2 operation(s) for localcontexts.
- [KU Leuven Logout API](https://apis.io/apis/ku-leuven/ku-leuven-logout-api/) — The Logout API from KU Leuven — 1 operation(s) for logout.
- [KU Leuven Mail API](https://apis.io/apis/ku-leuven/ku-leuven-mail-api/) — The Mail API from KU Leuven — 1 operation(s) for mail.
- [KU Leuven Meta API](https://apis.io/apis/ku-leuven/ku-leuven-meta-api/) — The Meta API from KU Leuven — 2 operation(s) for meta.
- [KU Leuven Metadatablocks API](https://apis.io/apis/ku-leuven/ku-leuven-metadatablocks-api/) — The Metadatablocks API from KU Leuven — 2 operation(s) for metadatablocks.
- [KU Leuven Mydata API](https://apis.io/apis/ku-leuven/ku-leuven-mydata-api/) — The Mydata API from KU Leuven — 1 operation(s) for mydata.
- [KU Leuven Notifications API](https://apis.io/apis/ku-leuven/ku-leuven-notifications-api/) — The Notifications API from KU Leuven — 6 operation(s) for notifications.
- [KU Leuven Pids API](https://apis.io/apis/ku-leuven/ku-leuven-pids-api/) — The Pids API from KU Leuven — 6 operation(s) for pids.
- [KU Leuven Replace Files In Dataset API](https://apis.io/apis/ku-leuven/ku-leuven-replacefilesindataset-api/) — Replace a file to a dataset
- [KU Leuven Roles API](https://apis.io/apis/ku-leuven/ku-leuven-roles-api/) — The Roles API from KU Leuven — 3 operation(s) for roles.
- [KU Leuven Save Auxiliary File With Version API](https://apis.io/apis/ku-leuven/ku-leuven-saveauxiliaryfilewithversion-api/) — Save Auxiliary File With Version
- [KU Leuven Search API](https://apis.io/apis/ku-leuven/ku-leuven-search-api/) — The Search API from KU Leuven — 2 operation(s) for search.
- [KU Leuven Upload Dataset Logo API](https://apis.io/apis/ku-leuven/ku-leuven-uploaddatasetlogo-api/) — Uploads a logo for a dataset
- [KU Leuven Users API](https://apis.io/apis/ku-leuven/ku-leuven-users-api/) — The Users API from KU Leuven — 10 operation(s) for users.
- [KU Leuven Workflows API](https://apis.io/apis/ku-leuven/ku-leuven-workflows-api/) — The Workflows API from KU Leuven — 1 operation(s) for workflows.
- [KU Leuven Curriculum Information (Curriculuminformatie) API](https://apis.io/apis/ku-leuven/curriculum/) — ICTS Data Services index of academic curriculum and CV records — discipline codes, research topics and the researcher's ORCID iD in the `orcId` field.…
- [KU Leuven Research Projects (Onderzoeksprojecten) API](https://apis.io/apis/ku-leuven/research-projects/) — ICTS Data Services index over the KU Leuven research database, the richest surface in the estate. Beyond free search it publishes three stored search…
- [KU Leuven Research Teams (Onderzoeksteams) API](https://apis.io/apis/ku-leuven/research-teams/) — ICTS Data Services index of research groups, 740 records live on 2026-08-19, joined to projects and to the organisational chart by unit code. Supports…
- [KU Leuven Research Infrastructure (Onderzoeksinfrastructuur) API](https://apis.io/apis/ku-leuven/research-infrastructure/) — ICTS Data Services index of core facilities and shared research equipment, 379 records live on 2026-08-19. A machine-readable research-facility catalogue is…
- [KU Leuven RDR OAI-PMH Harvesting Interface](https://apis.io/apis/ku-leuven/rdr-oai-pmh/) — OAI-PMH 2.0 interface of the Research Data Repository, served from KU Leuven's own host. Identify returned repositoryName "KU Leuven RDR Dataverse OAI…
- [Lirias OAI-PMH Harvesting Interface](https://apis.io/apis/ku-leuven/lirias-oai-pmh/) — Lirias is the institutional publication repository of the KU Leuven Association, running on KU Leuven's own host and address space. Its OAI-PMH 2.0 Identify…
- [KU Leuven Shibboleth Identity Provider (SAML 2.0 metadata)](https://apis.io/apis/ku-leuven/identity-federation/) — KU Leuven serves its own SAML 2.0 federation metadata from idp.kuleuven.be, which resolves to 134.58.64.219 inside the university's own address space —…
- [KU Leuven Curriculum API](https://apis.io/apis/ku-leuven/ku-leuven-curriculum-api/) — Academic curriculum and CV information, including ORCID identifiers.
- [KU Leuven Organigram API](https://apis.io/apis/ku-leuven/ku-leuven-organigram-api/) — Institutional organisational chart units.
- [KU Leuven Person API](https://apis.io/apis/ku-leuven/ku-leuven-person-api/) — Public staff / who-is-who person information (wie-is-wie).
- [KU Leuven Programs API](https://apis.io/apis/ku-leuven/ku-leuven-programs-api/) — Educational offering — degree programmes in the programme guide (onderwijsaanbod).
- [KU Leuven Research Infrastructure API](https://apis.io/apis/ku-leuven/ku-leuven-researchinfrastructure-api/) — Research infrastructure and core facilities from the research database.
- [KU Leuven Research Projects API](https://apis.io/apis/ku-leuven/ku-leuven-researchprojects-api/) — Research projects from the KU Leuven research database (onderzoeksdatabank).
- [KU Leuven Research Teams API](https://apis.io/apis/ku-leuven/ku-leuven-researchteams-api/) — Research teams / groups from the research database.
- [KU Leuven Vacancies API](https://apis.io/apis/ku-leuven/ku-leuven-vacancies-api/) — Public job vacancies published on the KU Leuven job site.
- [KU Leuven External Tools API](https://apis.io/apis/ku-leuven/ku-leuven-external-tools-api/) — The External Tools API from KU Leuven — 2 operation(s) for external tools.
- [KU Leuven Send Feedback API](https://apis.io/apis/ku-leuven/ku-leuven-send-feedback-api/) — The Send Feedback API from KU Leuven — 1 operation(s) for send feedback.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ku Leuven Agentic Access](https://apis.io/agentic-access/ku-leuven/ku-leuven-agentic-access/)

#### JSON Schema (5)

The data models the API reads and writes.

- [KU Leuven ICTS Data Services Search Response](https://apis.io/schemas/ku-leuven/ku-leuven-data-services-search-response/)
- [KU Leuven RDR DataFile](https://apis.io/schemas/ku-leuven/ku-leuven-datafile/)
- [KU Leuven RDR Dataset](https://apis.io/schemas/ku-leuven/ku-leuven-dataset/)
- [KU Leuven RDR DatasetVersion](https://apis.io/schemas/ku-leuven/ku-leuven-datasetversion/)
- [KU Leuven RDR Info Version Response](https://apis.io/schemas/ku-leuven/ku-leuven-info-version/)

#### JSON Structure (3)

Data models expressed in JSON Structure.

- [Ku Leuven Datafile Structure](https://apis.io/json-structure/ku-leuven/ku-leuven-datafile-structure/)
- [Ku Leuven Dataset Structure](https://apis.io/json-structure/ku-leuven/ku-leuven-dataset-structure/)
- [Ku Leuven Datasetversion Structure](https://apis.io/json-structure/ku-leuven/ku-leuven-datasetversion-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ku Leuven Context](https://apis.io/jsonld/ku-leuven/ku-leuven-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [KU Leuven Research Data Repository (RDR) Vocabulary](https://apis.io/vocabularies/ku-leuven/ku-leuven-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Ku Leuven Data Services Error Example](https://apis.io/examples/ku-leuven/ku-leuven-data-services-error-example/)
- [Ku Leuven Data Services Search Example](https://apis.io/examples/ku-leuven/ku-leuven-data-services-search-example/)
- [Ku Leuven Dataset Example](https://apis.io/examples/ku-leuven/ku-leuven-dataset-example/)
- [Ku Leuven Info Version Example](https://apis.io/examples/ku-leuven/ku-leuven-info-version-example/)
- [Ku Leuven Organigram Unit Example](https://apis.io/examples/ku-leuven/ku-leuven-organigram-unit-example/)

#### Collections (36)

Postman and Open Collection request collections.

- [KU Leuven Research Data Repository (RDR) Access API](https://apis.io/collections/ku-leuven/open-ku-leuven-access-api/)
- [KU Leuven Research Data Repository (RDR) Access addFilesToDataset API](https://apis.io/collections/ku-leuven/open-ku-leuven-addfilestodataset-api/)
- [KU Leuven Research Data Repository (RDR) Access addFileToDataset API](https://apis.io/collections/ku-leuven/open-ku-leuven-addfiletodataset-api/)
- [KU Leuven Research Data Repository (RDR) Access addGlobusFilesToDataset API](https://apis.io/collections/ku-leuven/open-ku-leuven-addglobusfilestodataset-api/)
- [KU Leuven Research Data Repository (RDR) Access Admin API](https://apis.io/collections/ku-leuven/open-ku-leuven-admin-api/)
- [KU Leuven Research Data Repository (RDR) Access Batch API](https://apis.io/collections/ku-leuven/open-ku-leuven-batch-api/)
- [KU Leuven Research Data Repository (RDR) Access Builtin Users API](https://apis.io/collections/ku-leuven/open-ku-leuven-builtin-users-api/)
- [KU Leuven Research Data Repository (RDR) Access Datasetfields API](https://apis.io/collections/ku-leuven/open-ku-leuven-datasetfields-api/)
- [KU Leuven Research Data Repository (RDR) Access Datasets API](https://apis.io/collections/ku-leuven/open-ku-leuven-datasets-api/)
- [KU Leuven Research Data Repository (RDR) Access Datatags API](https://apis.io/collections/ku-leuven/open-ku-leuven-datatags-api/)
- [KU Leuven Research Data Repository (RDR) Access DataverseFeaturedItems API](https://apis.io/collections/ku-leuven/open-ku-leuven-dataversefeatureditems-api/)
- [KU Leuven Research Data Repository (RDR) Access Dataverses API](https://apis.io/collections/ku-leuven/open-ku-leuven-dataverses-api/)
- [KU Leuven Research Data Repository (RDR) Access Edit API](https://apis.io/collections/ku-leuven/open-ku-leuven-edit-api/)
- [KU Leuven Research Data Repository (RDR) Access ExternalTools API](https://apis.io/collections/ku-leuven/open-ku-leuven-externaltools-api/)
- [KU Leuven Research Data Repository (RDR) Access Files API](https://apis.io/collections/ku-leuven/open-ku-leuven-files-api/)
- [KU Leuven Research Data Repository (RDR) Access Harvest API](https://apis.io/collections/ku-leuven/open-ku-leuven-harvest-api/)
- [KU Leuven Research Data Repository (RDR) Access Inbox API](https://apis.io/collections/ku-leuven/open-ku-leuven-inbox-api/)
- [KU Leuven Research Data Repository (RDR) Access Info API](https://apis.io/collections/ku-leuven/open-ku-leuven-info-api/)
- [KU Leuven Research Data Repository (RDR) Access Ingest API](https://apis.io/collections/ku-leuven/open-ku-leuven-ingest-api/)
- [KU Leuven Research Data Repository (RDR) Access Licenses API](https://apis.io/collections/ku-leuven/open-ku-leuven-licenses-api/)
- [KU Leuven Research Data Repository (RDR) Access Localcontexts API](https://apis.io/collections/ku-leuven/open-ku-leuven-localcontexts-api/)
- [KU Leuven Research Data Repository (RDR) Access Logout API](https://apis.io/collections/ku-leuven/open-ku-leuven-logout-api/)
- [KU Leuven Research Data Repository (RDR) Access Mail API](https://apis.io/collections/ku-leuven/open-ku-leuven-mail-api/)
- [KU Leuven Research Data Repository (RDR) Access Meta API](https://apis.io/collections/ku-leuven/open-ku-leuven-meta-api/)
- [KU Leuven Research Data Repository (RDR) Access Metadatablocks API](https://apis.io/collections/ku-leuven/open-ku-leuven-metadatablocks-api/)
- …and 11 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [KU Leuven — jsonschema rules](https://apis.io/rules/ku-leuven/ku-leuven-jsonschema-spectral-rules/)
- [KU Leuven API Rules](https://apis.io/rules/ku-leuven/ku-leuven-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Ku Leuven Authentication](https://apis.io/security/ku-leuven/ku-leuven-authentication/)
- [Ku Leuven Domain Security](https://apis.io/security/ku-leuven/ku-leuven-domain-security/)
- [Ku Leuven Vulnerability Disclosure](https://apis.io/security/ku-leuven/ku-leuven-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Ku Leuven Scopes](https://apis.io/scopes/ku-leuven/ku-leuven-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ku Leuven Plans Pricing](https://apis.io/plans/ku-leuven/ku-leuven-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ku Leuven Rate Limits](https://apis.io/rate-limits/ku-leuven/ku-leuven-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ku Leuven Finops](https://apis.io/finops/ku-leuven/ku-leuven-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.kuleuven.be)
- [Documentation](https://www.kuleuven.be/rdm/en/rdr/api-documentation)
- [API reference](https://rdr.kuleuven.be/openapi)
- [Support](https://admin.kuleuven.be/icts/services/dataservices/data-service-vraag)
- [Blog](https://nieuws.kuleuven.be/en/)
- [Security](https://admin.kuleuven.be/icts/english/responsible-disclosure)
- [Terms of service](https://admin.kuleuven.be/icts/services/dataservices/gebruiksvoorwaarden.html)
- [Privacy policy](https://www.kuleuven.be/privacy)
- [GitHub](https://github.com/kuleuven)

## API Evangelist rating

**Kin Score 39.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 67.9 |
| Contract quality | 45.4 |
| Contract governance | 17.4 |
| Operational transparency | 18.4 |
| Developer ergonomics | 45.2 |
| Access clarity | 26.3 |

**Agent readiness 27.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 40.2** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ku-leuven/](https://apis.io/providers/ku-leuven/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for KU Leuven: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ku-leuven/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
