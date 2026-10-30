# Michigan State University

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

Michigan State University is a public land-grant research university in East Lansing, Michigan, and a founding member of the Big Ten and the AAU. It runs no central developer portal, issues no API keys, and operates no self-service onboarding of any kind, and this profile does not pretend otherwise. What it genuinely operates, on its own msu.edu hosts, is a small set of real machine surfaces run by MSU Libraries and MSU IT: a keyless VuFind 11.0.4 REST API for the library discovery index at catalog.lib.msu.edu/api/v1, whose OpenAPI 3.0.3 the university itself publishes live at /api/v1/?swagger; two OAI-PMH 2.0 providers, one over the catalog and one over the digital repository at d.lib.msu.edu, the latter running oai_repo — an OAI-PMH server library MSU Libraries wrote themselves and release Apache-2.0 on GitHub, which is real institutional engineering rather than a vendor deployment; and a Shibboleth SAML 2.0 identity provider registered in InCommon as urn:mace:incommon:msu.edu. MSU also publishes an llms.txt and a /.well-known/ai.txt naming three AI content endpoints, though the Imperva edge in front of msu.edu answers every non-browser client with a JavaScript challenge, so those declared endpoints are not actually reachable by the agents they are addressed to. Two vendor platforms are recorded as tenant relationships rather than as MSU contracts: D2L Brightspace (d2l.msu.edu, CNAME msu.brightspace.com) and Academic Analytics (Scholars @ MSU at scholars.msu.edu). Student records, registration, HR and finance are behind institutional SSO and are not public APIs.

**Areas:** Education · Higher Education · University · Public Research University · Land-Grant University · Big Ten · United States · Michigan · Library · Library Catalog · Digital Repository · Metadata

## Michigan State University on APIs.io

Everything profiled for Michigan State University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/michigan-state-university/](https://apis.io/providers/michigan-state-university/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [MSU Libraries Catalog Record API](https://apis.io/apis/michigan-state-university/michigan-state-university-record-api/) — Record-retrieval half of the MSU Libraries VuFind 11.0.4 REST API, served from the university's own host at catalog.lib.msu.edu/api/v1. Keyless and…
- [MSU Libraries Catalog Search API](https://apis.io/apis/michigan-state-university/michigan-state-university-search-api/) — Search half of the same MSU Libraries VuFind 11.0.4 REST API on catalog.lib.msu.edu/api/v1 — GET /search, /index2/search and /web/search return result sets…
- [MSU Libraries Catalog OAI-PMH](https://apis.io/apis/michigan-state-university/catalog-oai/) — OAI-PMH 2.0 metadata harvesting provider over the MSU Libraries catalog, on the university's own host. Verified live on 2026-08-30: verb=Identify returns…
- [MSU Libraries Digital Repository OAI-PMH](https://apis.io/apis/michigan-state-university/dlib-oai/) — OAI-PMH 2.0 provider over the MSU Libraries Digital Repository at d.lib.msu.edu. Verified live on 2026-08-30: verb=Identify returns repositoryName "MSU…
- [MSU Identity Provider (Shibboleth / SAML 2.0)](https://apis.io/apis/michigan-state-university/idp/) — MSU's federated single sign-on. The Shibboleth Identity Provider publishes SAML 2.0 metadata unauthenticated at idp.idm.msu.edu/idp/shibboleth — verified…
- [D2L Brightspace at MSU (tenant)](https://apis.io/apis/michigan-state-university/brightspace-lms/) — MSU's learning management system is D2L Brightspace, running as an MSU-branded tenant at d2l.msu.edu, which CNAMEs to msu.brightspace.com — confirmed by DNS…
- [Scholars @ MSU (Academic Analytics tenant)](https://apis.io/apis/michigan-state-university/scholars-msu/) — MSU's public research-expertise portal at scholars.msu.edu. The host is MSU-branded, but the application is an Angular single-page client whose compiled…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Michigan State University Agentic Access](https://apis.io/agentic-access/michigan-state-university/michigan-state-university-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [MSU Libraries Catalog Record](https://apis.io/schemas/michigan-state-university/michigan-state-university-record/)
- [MSU Libraries Catalog Search Response](https://apis.io/schemas/michigan-state-university/michigan-state-university-searchresponse/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Michigan State University Record Structure](https://apis.io/json-structure/michigan-state-university/michigan-state-university-record-structure/)
- [Michigan State University Searchresponse Structure](https://apis.io/json-structure/michigan-state-university/michigan-state-university-searchresponse-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Michigan State University Context](https://apis.io/jsonld/michigan-state-university/michigan-state-university-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [MSU Libraries Catalog API Vocabulary](https://apis.io/vocabularies/michigan-state-university/michigan-state-university-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Michigan State University Record Example](https://apis.io/examples/michigan-state-university/michigan-state-university-record-example/)
- [Michigan State University Search Example](https://apis.io/examples/michigan-state-university/michigan-state-university-search-example/)

#### Collections (2)

Postman and Open Collection request collections.

- [Library Catalog Record API](https://apis.io/collections/michigan-state-university/open-michigan-state-university-record-api/)
- [Library Catalog Record Search API](https://apis.io/collections/michigan-state-university/open-michigan-state-university-search-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Michigan State University — jsonschema rules](https://apis.io/rules/michigan-state-university/michigan-state-university-jsonschema-spectral-rules/)
- [Michigan State University API Rules](https://apis.io/rules/michigan-state-university/michigan-state-university-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Michigan State University Authentication](https://apis.io/security/michigan-state-university/michigan-state-university-authentication/)
- [Michigan State University Domain Security](https://apis.io/security/michigan-state-university/michigan-state-university-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Michigan State University Scopes](https://apis.io/scopes/michigan-state-university/michigan-state-university-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Michigan State University Plans Pricing](https://apis.io/plans/michigan-state-university/michigan-state-university-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Michigan State University Rate Limits](https://apis.io/rate-limits/michigan-state-university/michigan-state-university-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Michigan State University Finops](https://apis.io/finops/michigan-state-university/michigan-state-university-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.msu.edu)
- [Documentation](https://docs.icer.msu.edu/)
- [API reference](https://catalog.lib.msu.edu/api/v1/?swagger)
- [Support](https://msu.edu/contact)
- [Blog](https://msutoday.msu.edu)
- [Privacy policy](https://msu.edu/privacy)
- [GitHub](https://github.com/MSU-Libraries)

## API Evangelist rating

**Kin Score 30.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 48.8 |
| Contract governance | 9.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 31.0 |
| Access clarity | 5.3 |

**Agent readiness 20.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 26.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/michigan-state-university/](https://apis.io/providers/michigan-state-university/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Michigan State University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/michigan-state-university/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
