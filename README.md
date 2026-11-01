# University of British Columbia

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

The University of British Columbia is a public research university with campuses in Vancouver and Kelowna, British Columbia, and a member of Canada's U15 research group. Its programmable footprint is real but narrow, and almost all of it sits in UBC Library rather than in central IT. UBC Library operates the Open Collections API over the university's digitized archival and research collections, a IIIF Presentation endpoint over the same items, and the Abacus research-data repository — a Dataverse 5.9 deployment on UBC's own infrastructure that also serves a live OAI-PMH archive emitting DataCite kernel-4 and DDI Codebook metadata. Central IT publishes exactly one machine-readable artifact to the open internet: the SAML metadata for UBC's own Shibboleth identity provider at authentication.ubc.ca. Everything else the Office of the CIO runs is deliberately closed — the Integration Enablement Centre's MuleSoft gateway answers at api.ubc.ca with a flat 403, its API catalogue sits behind UBC's Confluence login, and entitlement is granted per-API through a Data Access Framework request rather than a developer portal. There is no public course, timetable or registrar API; course planning moved into Workday and the community projects that fill the gap are student-built and not endorsed by the university. UBC has no central developer portal, no API changelog and no deprecation policy, and every ubc.ca host sits behind a bot defence that answers automated clients with an HTML block page carrying HTTP 200.

**Areas:** Education · Higher Education · University · Public Research University · Canada · British Columbia · U15 · Library · Digital Collections · Research Data · Research Repository · Open Data

## University of British Columbia on APIs.io

Everything profiled for University of British Columbia is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ubc/](https://apis.io/providers/ubc/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [UBC Library Open Collections IIIF Presentation API](https://apis.io/apis/ubc/open-collections-iiif/) — IIIF Presentation manifests for Open Collections items, served from UBC Library's own host. Verified live 2026-08-19: a 10,560-byte JSON manifest returned…
- [UBC Library Abacus Dataverse API](https://apis.io/apis/ubc/abacus-dataverse/) — The REST API of Abacus, UBC Library's research-data repository, running Dataverse 5.9 on UBC's own infrastructure at abacus.library.ubc.ca. UBC operates the…
- [Abacus OAI-PMH Metadata Harvesting Endpoint](https://apis.io/apis/ubc/abacus-oai-pmh/) — A working OAI-PMH 2.0 archive on UBC Library's own host. Verified live 2026-08-19: verb=Identify returns repositoryName "Abacus Data Network Dataverse OAI…
- [UBC Shibboleth Identity Provider Metadata](https://apis.io/apis/ubc/shibboleth-idp/) — UBC's own SAML 2.0 identity provider metadata, entityID https://authentication.ubc.ca, asserting the ubc.ca scope. Institution-operated by definition — no…
- [UBC Integration Enablement Centre API Gateway](https://apis.io/apis/ubc/iec-api-gateway/) — UBC's enterprise API gateway, run by the Office of the CIO's Integration Enablement Centre against the University Data Model. The host is real and answers —…
- [UBC IT Service Status API](https://apis.io/apis/ubc/it-status/) — Machine-readable service status for UBC IT at status.it.ubc.ca, on UBC's own hostname but CNAMEd to stspg-customer.com — UBC's tenant of Atlassian…
- [University of British Columbia Collections API](https://apis.io/apis/ubc/ubc-collections-api/) — Collection-level metadata and item traversal.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ubc Agentic Access](https://apis.io/agentic-access/ubc/ubc-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [UBC Abacus Dataverse DataFile](https://apis.io/schemas/ubc/ubc-datafile/)
- [UBC Abacus Dataverse Dataset](https://apis.io/schemas/ubc/ubc-dataset/)
- [UBC Abacus Dataverse Collection](https://apis.io/schemas/ubc/ubc-dataverse/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Ubc Dataset Structure](https://apis.io/json-structure/ubc/ubc-dataset-structure/)
- [Ubc Dataverse Structure](https://apis.io/json-structure/ubc/ubc-dataverse-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ubc Context](https://apis.io/jsonld/ubc/ubc-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [UBC Abacus Dataverse Vocabulary](https://apis.io/vocabularies/ubc/ubc-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Ubc Get Dataverse Example](https://apis.io/examples/ubc/ubc-get-dataverse-example/)
- [Ubc Open Collections Collection Example](https://apis.io/examples/ubc/ubc-open-collections-collection-example/)
- [Ubc Open Collections Items Example](https://apis.io/examples/ubc/ubc-open-collections-items-example/)
- [Ubc Open Collections Search Example](https://apis.io/examples/ubc/ubc-open-collections-search-example/)
- [Ubc Search Datasets Example](https://apis.io/examples/ubc/ubc-search-datasets-example/)

#### Collections (22)

Postman and Open Collection request collections.

- [UBC Abacus Dataverse Access API](https://apis.io/collections/ubc/open-ubc-access-api/)
- [UBC Abacus Dataverse Access Admin API](https://apis.io/collections/ubc/open-ubc-admin-api/)
- [UBC Abacus Dataverse Access Batch API](https://apis.io/collections/ubc/open-ubc-batch-api/)
- [UBC Abacus Dataverse Access Builtin Users API](https://apis.io/collections/ubc/open-ubc-builtin-users-api/)
- [UBC Abacus Dataverse Access Datasets API](https://apis.io/collections/ubc/open-ubc-datasets-api/)
- [UBC Abacus Dataverse Access Datatags API](https://apis.io/collections/ubc/open-ubc-datatags-api/)
- [UBC Abacus Dataverse Access Dataverses API](https://apis.io/collections/ubc/open-ubc-dataverses-api/)
- [UBC Abacus Dataverse Access Edit API](https://apis.io/collections/ubc/open-ubc-edit-api/)
- [UBC Abacus Dataverse Access Files API](https://apis.io/collections/ubc/open-ubc-files-api/)
- [UBC Abacus Dataverse Access Harvest API](https://apis.io/collections/ubc/open-ubc-harvest-api/)
- [UBC Abacus Dataverse Access Info API](https://apis.io/collections/ubc/open-ubc-info-api/)
- [UBC Abacus Dataverse Access Ingest API](https://apis.io/collections/ubc/open-ubc-ingest-api/)
- [UBC Abacus Dataverse Access Mail API](https://apis.io/collections/ubc/open-ubc-mail-api/)
- [UBC Abacus Dataverse Access Meta API](https://apis.io/collections/ubc/open-ubc-meta-api/)
- [UBC Abacus Dataverse Access Metadatablocks API](https://apis.io/collections/ubc/open-ubc-metadatablocks-api/)
- [UBC Abacus Dataverse Access Mydata API](https://apis.io/collections/ubc/open-ubc-mydata-api/)
- [UBC Abacus Dataverse Access Notifications API](https://apis.io/collections/ubc/open-ubc-notifications-api/)
- [UBC Abacus Dataverse Access Pids API](https://apis.io/collections/ubc/open-ubc-pids-api/)
- [UBC Abacus Dataverse Access Roles API](https://apis.io/collections/ubc/open-ubc-roles-api/)
- [UBC Abacus Dataverse Access Search API](https://apis.io/collections/ubc/open-ubc-search-api/)
- [UBC Abacus Dataverse Access Users API](https://apis.io/collections/ubc/open-ubc-users-api/)
- [UBC Abacus Dataverse Access Workflows API](https://apis.io/collections/ubc/open-ubc-workflows-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [University of British Columbia — jsonschema rules](https://apis.io/rules/ubc/ubc-jsonschema-spectral-rules/)
- [University of British Columbia API Rules](https://apis.io/rules/ubc/ubc-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Ubc Authentication](https://apis.io/security/ubc/ubc-authentication/)
- [Ubc Domain Security](https://apis.io/security/ubc/ubc-domain-security/)
- [Ubc Vulnerability Disclosure](https://apis.io/security/ubc/ubc-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Ubc Scopes](https://apis.io/scopes/ubc/ubc-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ubc Plans Pricing](https://apis.io/plans/ubc/ubc-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ubc Rate Limits](https://apis.io/rate-limits/ubc/ubc-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ubc Finops](https://apis.io/finops/ubc/ubc-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ubc.ca/)
- [Documentation](https://open.library.ubc.ca/docs)
- [API reference](https://github.com/ubc-library/docs-open-collections-api)
- [Support](https://cio.ubc.ca/data-governance/data-governance-services/access-ubc-data)
- [Blog](https://news.ubc.ca/feed/)
- [Terms of service](https://www.ubc.ca/site/legal.html)
- [Privacy policy](https://privacymatters.ubc.ca/)
- [GitHub](https://github.com/ubc-library)

## API Evangelist rating

**Kin Score 45.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 55.0 |
| Contract governance | 17.4 |
| Operational transparency | 44.7 |
| Developer ergonomics | 35.7 |
| Access clarity | 39.5 |

**Agent readiness 28.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 40.2** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ubc/](https://apis.io/providers/ubc/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of British Columbia: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ubc/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
