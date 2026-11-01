# University of Waikato

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

The University of Waikato (Te Whare Wananga o Waikato) is a public research university in Hamilton and Tauranga, Aotearoa New Zealand, founded in 1964. It runs no developer programme, no developer portal and no self-serve public API, and this profile says so plainly. What it does operate itself is narrow but real and unusually well evidenced for this cohort: an OpenID Connect provider of its own on api.svc.waikato.ac.nz/uowidp/v1, publishing a live discovery document and JWKS and used by the university's own Blazor timetable and its MyWaikato student portal; Research Commons, a DSpace 7.6.5 institutional repository on its own host serving a DSpace REST API and an OAI-PMH 2.0 interface with twelve metadata formats back to 1972; a One-Time Secret API run by IT Services with documented endpoints under HTTP Basic against a Stella account; a Moodle LMS acting as an LTI 1.3 platform with live platform keys; and the UFDL deep-learning framework API from the Computing and Mathematical Sciences faculty, alongside four active GitHub organisations (Waikato, waikato-ufdl, waikato-datamining, waikato-llm) that include WEKA. Its identity is federated twice over — a Shibboleth IdP entity registered in Tuakiri since 2012 with REFEDS Research & Scholarship and Sirtfi, exported to eduGAIN, and a Microsoft Entra ID tenant that is the live SAML issuer for eLearn. The university also publishes an llms.txt with explicit attribution and generative-model usage terms, which almost no institution in this cohort does. Everything else that looks like a Waikato API is a tenancy on somebody else's platform — Symplectic Discovery behind profiles.waikato.ac.nz, Ex Libris Primo VE, Springshare LibGuides behind libraryguides.waikato.ac.nz, and waikato.figshare.com — and is recorded here as a relationship, never as a University of Waikato contract.

**Areas:** Education · Higher Education · University · New Zealand · Research · Research Repository · Open Access · OAI-PMH · Identity Federation · SAML · LMS · Machine Learning

## University of Waikato on APIs.io

Everything profiled for University of Waikato is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-waikato/](https://apis.io/providers/university-of-waikato/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [Research Commons OAI-PMH](https://apis.io/apis/university-of-waikato/research-commons-oai/) — OAI-PMH 2.0 metadata harvesting interface for Research Commons, the university's open-access institutional repository, on the institution's own host.…
- [Research Commons DSpace REST API](https://apis.io/apis/university-of-waikato/research-commons-rest/) — DSpace 7.6.5 REST API backing Research Commons, giving programmatic access to communities, collections, items, bitstreams and discovery search over the…
- [eLearn LTI 1.3 Platform (Moodle)](https://apis.io/apis/university-of-waikato/elearn-lti/) — eLearn, the university's Moodle learning management system on its own registrable domain, acts as an LTI 1.3 platform. Verified live 2026-09-01:…
- [One-Time Secret (OTS) API](https://apis.io/apis/university-of-waikato/ots/) — A One-Time Secret service run by University of Waikato IT Services on its own host, for sharing a secret that can be retrieved exactly once. The published…
- [User-friendly Deep Learning (UFDL) API](https://apis.io/apis/university-of-waikato/ufdl/) — JSON REST API for the User-friendly Deep Learning framework built by the University of Waikato's Faculty of Computing and Mathematical Sciences to make deep…
- [Waikato SAML 2.0 Identity Provider in Tuakiri](https://apis.io/apis/university-of-waikato/tuakiri-idp/) — The University of Waikato's Shibboleth Identity Provider, entityID https://idp.waikato.ac.nz/idp/shibboleth, registered in the signed Tuakiri (New Zealand…
- [University of Waikato Microsoft Entra ID Tenant](https://apis.io/apis/university-of-waikato/entra-tenant/) — The university's Microsoft Entra ID tenant, 220f5dc3-9452-48e5-9b4f-888df42f7a2d, is the identity source behind both the uowidp OpenID Connect provider and…
- [Crossref Membership (member 6347)](https://apis.io/apis/university-of-waikato/crossref-member/) — The University of Waikato is a Crossref member — member id 6347, primary name "University of Waikato", DOI prefix 10.15663. Verified 2026-09-01 against…
- [ROR Registration (ror.org/013fsnh78)](https://apis.io/apis/university-of-waikato/ror/) — The University of Waikato is registered in the Research Organization Registry as https://ror.org/013fsnh78, with names "University of Waikato" and "Te Whare…
- [Waikato Research Profiles on Symplectic Discovery (tenant)](https://apis.io/apis/university-of-waikato/symplectic-discovery/) — profiles.waikato.ac.nz is the university's researcher-profile and research-information service, and it is a tenancy: the host CNAMEs to…
- [Waikato Library Discovery on Ex Libris Primo VE (tenant)](https://apis.io/apis/university-of-waikato/primo-discovery/) — The University of Waikato Library's discovery layer is a named tenancy on Ex Libris's shared Primo VE platform — waikato.primo.exlibrisgroup.com with view…
- [Waikato Figshare Research Data Repository (tenant)](https://apis.io/apis/university-of-waikato/figshare-tenant/) — waikato.figshare.com resolves (CNAME to figshare.com) and answers HTTP 202 with an empty body — a bot-management challenge, so the tenancy is live but not…
- [Waikato Library Guides on Springshare LibGuides (tenant)](https://apis.io/apis/university-of-waikato/libguides/) — libraryguides.waikato.ac.nz, which hosts the library's subject guides including its "Using Generative AI in Academic Study" guide, CNAMEs to…
- [University of Waikato Authentication API](https://apis.io/apis/university-of-waikato/university-of-waikato-authentication-api/) — Authorization Code and hybrid flows against the university identity provider.
- [University of Waikato Discovery API](https://apis.io/apis/university-of-waikato/university-of-waikato-discovery-api/) — OpenID Provider metadata and signing keys.
- [University of Waikato Session API](https://apis.io/apis/university-of-waikato/university-of-waikato-session-api/) — Front-channel session termination.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (2)

The data models the API reads and writes.

- [University of Waikato uowidp JSON Web Key Set](https://apis.io/schemas/university-of-waikato/university-of-waikato-uowidp-jwks/)
- [University of Waikato uowidp OpenID Provider Metadata](https://apis.io/schemas/university-of-waikato/university-of-waikato-uowidp-provider-metadata/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Waikato Context](https://apis.io/jsonld/university-of-waikato/university-of-waikato-context/)

#### Examples (2)

Example requests and responses.

- [University Of Waikato Protocol Endpoints Example](https://apis.io/examples/university-of-waikato/university-of-waikato-protocol-endpoints-example/)
- [University Of Waikato Uowidp Discovery Example](https://apis.io/examples/university-of-waikato/university-of-waikato-uowidp-discovery-example/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Waikato Authentication](https://apis.io/security/university-of-waikato/university-of-waikato-authentication/)
- [University Of Waikato Domain Security](https://apis.io/security/university-of-waikato/university-of-waikato-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [University Of Waikato Scopes](https://apis.io/scopes/university-of-waikato/university-of-waikato-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Waikato Plans Pricing](https://apis.io/plans/university-of-waikato/university-of-waikato-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Waikato Rate Limits](https://apis.io/rate-limits/university-of-waikato/university-of-waikato-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Waikato Finops](https://apis.io/finops/university-of-waikato/university-of-waikato-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.waikato.ac.nz/)
- [Support](https://www.waikato.ac.nz/students/it-services/)
- [Blog](https://www.waikato.ac.nz/news-events/news/)
- [Terms of service](https://www.waikato.ac.nz/copyright-and-disclaimer/)
- [Privacy policy](https://www.waikato.ac.nz/privacy/)
- [GitHub](https://github.com/Waikato)

## API Evangelist rating

**Kin Score 24.4** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 24.1 |
| Contract governance | 3.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 26.2 |
| Access clarity | 21.1 |

**Agent readiness 29.4** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.0** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-waikato/](https://apis.io/providers/university-of-waikato/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Waikato: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-waikato/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
