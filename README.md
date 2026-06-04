# University of Waikato (university-of-waikato)

The University of Waikato (Te Whare Wananga o Waikato) is a public research university in Hamilton, New Zealand, founded in 1964 and ranked #235 in the QS World University Rankings 2025. This repository catalogs the institution's publicly observable developer and API footprint as an [APIs.json](https://apisjson.org) profile. There is no single consolidated developer portal; the footprint is spread across the Research Commons institutional repository, IT Services operational APIs, and research-software APIs from the Computing and Mathematical Sciences faculty.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-waikato/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-waikato-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Institutional Repository, Open Access, New Zealand

## APIs

- **Research Commons REST API** — DSpace 7.6.5 REST API over the open access institutional repository. [Docs](https://researchcommons.waikato.ac.nz/server/api)
- **Research Commons OAI-PMH** — OAI-PMH 2.0 metadata harvesting endpoint (repositoryName "Research Commons"). [Docs](https://researchcommons.waikato.ac.nz/server/oai/request?verb=Identify)
- **One-Time Secret (OTS) API** — IT Services API for securely sharing one-time secrets; JSON over HTTPS, HTTP Basic auth. [Docs](https://otis.its.waikato.ac.nz/docs/api)
- **User-friendly Deep Learning (UFDL) API** — JSON REST API for the CMS faculty's deep learning framework. [Docs](https://ufdl.cms.waikato.ac.nz/ufdl-api/)
- **Identity Provider (uowidp)** — Campus SSO / identity sign-in endpoint (account-gated). [Docs](https://api.svc.waikato.ac.nz/uowidp/v1/login)

## Plans

[plans/university-of-waikato-plans-pricing.yml](plans/university-of-waikato-plans-pricing.yml)

## Rate Limits

[rate-limits/university-of-waikato-rate-limits.yml](rate-limits/university-of-waikato-rate-limits.yml)

## FinOps

[finops/university-of-waikato-finops.yml](finops/university-of-waikato-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.waikato.ac.nz/
- GitHub: https://github.com/Waikato
- LinkedIn: https://www.linkedin.com/school/universityofwaikato/
- Twitter: https://twitter.com/waikato
- Source Code: https://github.com/Waikato/waikato-repositories

## Notes

All APIs and URLs were probed live on 2026-06-03 and statuses recorded in `review.yml`. The Research Commons REST and OAI-PMH endpoints, OTS API docs, UFDL docs, and the uowidp identity endpoint all resolved (HTTP 200). The OTS and identity APIs are gated to institutional accounts. The LinkedIn page returns HTTP 999 (LinkedIn bot-block) but exists. No endpoints were fabricated; only confirmed, publicly observable resources are cataloged.

## Maintainers

- Kin Lane — kin@apievangelist.com
