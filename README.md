# University of British Columbia (ubc)

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

The University of British Columbia (UBC) is a public research university in Vancouver and Kelowna, British Columbia, Canada, ranked #33 in the QS World University Rankings 2025. This repository catalogs UBC's public developer and API footprint as an [APIs.json](https://apisjson.org) profile. UBC's public APIs are led by UBC Library — the Open Collections API and the Abacus Dataverse research-data repository — while enterprise/institutional data is gated behind the Office of the CIO's Integration Enablement Centre.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ubc/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ubc-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Canada, Library, Open Data, Research Data, Digital Collections

## APIs

- **UBC Library Open Collections API** — Public ElasticSearch-backed REST/JSON API over UBC's digitized collections; no key required for reads. Docs: https://open.library.ubc.ca/docs · Base: `https://oc-index.library.ubc.ca` · GitHub: https://github.com/ubc-library/docs-open-collections-api
- **UBC Abacus Dataverse API** — Standard Dataverse 5.9 REST API for the UBC research-data repository (search, data access, UBC Open Data). Docs: https://abacus.library.ubc.ca/ · Base: `https://abacus.library.ubc.ca/api`
- **UBC Library OAI-PMH Endpoint** — Open Archives Initiative metadata-harvesting endpoint for collection metadata. Docs: https://open.library.ubc.ca/docs · Base: `https://open.library.ubc.ca/oai/request`
- **UBC Integration Enablement Centre APIs (MuleSoft / DAF)** — Gated enterprise/institutional APIs delivered via MuleSoft and a Data Access Framework; access by formal request only. Docs: https://cio.ubc.ca/data-governance/integration-enablement-centre

## Plans, Rate Limits & FinOps

- Plans & Pricing: [plans/ubc-plans-pricing.yml](plans/ubc-plans-pricing.yml)
- Rate Limits: [rate-limits/ubc-rate-limits.yml](rate-limits/ubc-rate-limits.yml)
- FinOps: [finops/ubc-finops.yml](finops/ubc-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ubc.ca/
- GitHub: https://github.com/ubc-library
- LinkedIn: https://www.linkedin.com/school/ubc/
- Developer Portal: https://open.library.ubc.ca/docs

## Notes

All API endpoints in this profile were live-probed on 2026-06-03; no endpoints were fabricated. The Open Collections API (`/search/8.5/`, `/collections`), the Abacus Dataverse API (`/api/info/version`, Dataverse 5.9), and the OAI-PMH endpoint all returned valid responses. The Open Collections human docs page intermittently serves a bot-block page to automated clients, so its contents were cross-confirmed via the official `ubc-library` GitHub docs repo. UBC's institutional MuleSoft/DAF APIs are gated behind a data access request and are not self-service. No official UBC course/timetable/SIS API was found (only third-party community projects). The LinkedIn page returns HTTP 999 to automated requests (LinkedIn's standard block) but exists in a browser.

## Maintainers

- Kin Lane — kin@apievangelist.com
