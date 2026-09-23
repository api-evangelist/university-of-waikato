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

The University of Waikato (Te Whare Wananga o Waikato) is a public research university in Hamilton and Tauranga, Aotearoa New Zealand, founded in 1964. This repository catalogs the institution's publicly observable developer and API footprint as an [APIs.json](https://apisjson.org) profile.

A university is a federation of buyers, not a producer, so this profile records **who operates** each surface as well as what it is. Every entry in `apis.yml` carries an `x-operator` — `institution` (the university's own host and deployment), `federation` (its identity in a shared federation), `registry` (a membership in a shared identifier registry), or `tenant` (its account on somebody else's platform). Vendor contracts are never saved under this institution; the relationship is recorded instead.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-waikato/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-waikato-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- Internal
- University · Public Research University

## Tags

Education, Higher Education, University, New Zealand, Research, Research Repository, Open Access, OAI-PMH, Identity Federation, SAML, OpenID Connect, Learning Management, Machine Learning

## Institution-operated surfaces

- **University of Waikato Identity Provider (uowidp)** — the institution's own OpenID Connect provider on its API gateway, publishing a live discovery document and JWKS. The one machine-readable contract in this repository. [Discovery](https://api.svc.waikato.ac.nz/uowidp/v1/.well-known/openid-configuration) · [OpenAPI](openapi/university-of-waikato-uowidp-openapi.yml)
- **Research Commons OAI-PMH** — OAI-PMH 2.0 harvesting on the university's DSpace 7.6.5 repository; twelve metadata formats, earliest datestamp 1972. [Identify](https://researchcommons.waikato.ac.nz/server/oai/request?verb=Identify)
- **Research Commons DSpace REST API** — DSpace 7.6.5 REST over communities, collections, items and discovery. The contract is DSpace's; the deployment and content are the university's. [Root](https://researchcommons.waikato.ac.nz/server/api)
- **eLearn LTI 1.3 Platform (Moodle)** — the university's LMS acts as an LTI 1.3 platform and serves live platform keys. [JWKS](https://elearn.waikato.ac.nz/mod/lti/certs.php)
- **One-Time Secret (OTS) API** — IT Services API for one-time secret sharing; JSON over HTTPS, HTTP Basic against a Stella account. [Docs](https://otis.its.waikato.ac.nz/docs/api)
- **User-friendly Deep Learning (UFDL) API** — the Computing and Mathematical Sciences faculty's deep-learning framework API. [Docs](https://ufdl.cms.waikato.ac.nz/ufdl-api/)

## Identity federation

- **Waikato SAML 2.0 Identity Provider in Tuakiri** — entityID `https://idp.waikato.ac.nz/idp/shibboleth`, registered since 2012-10-15, REFEDS Research & Scholarship + Sirtfi, exported to eduGAIN. The entity is the university's; the deployment runs on REANNZ's Tuakiri Hosted IdP. [Metadata](https://directory.tuakiri.ac.nz/metadata/tuakiri-metadata-signed.xml)
- **Microsoft Entra ID tenant** `220f5dc3-9452-48e5-9b4f-888df42f7a2d` — the identity source behind uowidp and the live SAML issuer for eLearn.

## Registry memberships

- **Crossref** — member 6347, DOI prefix `10.15663`.
- **ROR** — [ror.org/013fsnh78](https://ror.org/013fsnh78).
- **DataCite** — no provider or repository record; recorded as a negative probe.

## Tenancies (recorded as relationships, not as Waikato contracts)

- **Symplectic Discovery** — `profiles.waikato.ac.nz` CNAMEs to `waikato.discovery.symplectic.org`.
- **Ex Libris Primo VE** — named view `64WAIKATO_INST:64WAIKATO`.
- **Springshare LibGuides** — `libraryguides.waikato.ac.nz` CNAMEs to `region-au.libguides.com`.
- **Figshare** — `waikato.figshare.com`, live behind a bot challenge.

## Artifacts

- [openapi/university-of-waikato-uowidp-openapi.yml](openapi/university-of-waikato-uowidp-openapi.yml) (+ [`_original/`](openapi/_original/))
- [conformance/university-of-waikato-conformance.yml](conformance/university-of-waikato-conformance.yml)
- [authentication/university-of-waikato-authentication.yml](authentication/university-of-waikato-authentication.yml)
- [scopes/university-of-waikato-scopes.yml](scopes/university-of-waikato-scopes.yml)
- [errors/university-of-waikato-errors.yml](errors/university-of-waikato-errors.yml)
- [vocabulary/university-of-waikato-vocabulary.yml](vocabulary/university-of-waikato-vocabulary.yml)
- [json-schema/](json-schema/) · [examples/](examples/) · [json-ld/](json-ld/)
- [plans/university-of-waikato-plans-pricing.yml](plans/university-of-waikato-plans-pricing.yml) · [rate-limits/university-of-waikato-rate-limits.yml](rate-limits/university-of-waikato-rate-limits.yml) · [finops/university-of-waikato-finops.yml](finops/university-of-waikato-finops.yml) · [security/university-of-waikato-domain-security.yml](security/university-of-waikato-domain-security.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://www.waikato.ac.nz/
- GitHub: https://github.com/Waikato (also `waikato-ufdl`, `waikato-datamining`, `waikato-llm`)
- LinkedIn: https://www.linkedin.com/school/universityofwaikato/
- Twitter: https://twitter.com/waikato
- Source Code: https://github.com/Waikato/waikato-repositories
- llms.txt: https://www.waikato.ac.nz/llms.txt
- AI policy: https://www.waikato.ac.nz/students/student-assessment-handbook/gen-ai/

## Notes

Every URL in this profile was probed live on 2026-09-01 and the statuses are recorded in `review.yml` and in `x-coverage` in `apis.yml`. Confirmed absences: no `data.`, `opendata.`, `api.`, `developer.` or `apis.waikato.ac.nz` (NXDOMAIN), no `/.well-known/security.txt` (404), no status page, no research-computing allocation surface, no ORCID endpoints on the DSpace deployment, and no public route on the API gateway other than `/uowidp/v1`. The LinkedIn page returns HTTP 999 (LinkedIn bot-block) but exists. Nothing here is fabricated, and no vendor's contract is attributed to this institution.

## Maintainers

- Kin Lane — kin@apievangelist.com
