# University of British Columbia (ubc)

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
