# University of Waikato (university-of-waikato)

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
