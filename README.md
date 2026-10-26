# Michigan State University (michigan-state-university)

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

Michigan State University (MSU) is a public land-grant research university in East Lansing, Michigan, United States, ranked #89 in the QS World University Rankings 2025. This repository catalogs MSU's confirmed public developer and API footprint as an [APIs.json](http://apisjson.org) provider profile. MSU has no single consolidated developer portal; its verified public machine interfaces are concentrated in the MSU Libraries platforms (VuFind catalog REST API and OAI-PMH endpoints), alongside a Shibboleth/SAML + OAuth 2.0 identity service.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/michigan-state-university/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=michigan-state-university-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Library, Open Data, Metadata, United States, Michigan

## APIs

- **MSU Libraries Catalog REST API (VuFind)** — VuFind REST API (OpenAPI 3.0.3, VuFind v11.0.4) for the library catalog search index. Docs: https://catalog.lib.msu.edu/api/v1 — OpenAPI: https://catalog.lib.msu.edu/api/v1/?swagger
- **MSU Libraries Catalog OAI-PMH** — OAI-PMH 2.0 metadata harvesting for the "Michigan State University Libraries Catalog" repository. Docs: https://catalog.lib.msu.edu/OAI/Server?verb=Identify
- **MSU Libraries Digital Repository OAI-PMH** — OAI-PMH 2.0 metadata harvesting for the "MSU Libraries Digital Repository". Docs: https://d.lib.msu.edu/oai?verb=Identify
- **MSU Identity Provider (Shibboleth / SAML / OAuth 2.0)** — Federated SSO; gated to registered institutional integrations. Docs: https://tech.msu.edu/network/authentication-authorization/

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/michigan-state-university-plans-pricing.yml](plans/michigan-state-university-plans-pricing.yml)
- Rate Limits: [rate-limits/michigan-state-university-rate-limits.yml](rate-limits/michigan-state-university-rate-limits.yml)
- FinOps: [finops/michigan-state-university-finops.yml](finops/michigan-state-university-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.msu.edu
- GitHub (university): https://github.com/Michigan-State-University
- Source Code (MSU Libraries): https://github.com/MSU-Libraries
- LinkedIn: https://www.linkedin.com/school/michigan-state-university/
- Developer Portal (auth docs): https://tech.msu.edu/network/authentication-authorization/
- Authentication: https://idp.idm.msu.edu/idp/shibboleth
- Review: [review.yml](review.yml)

## Notes

All URLs in this profile were probed directly on 2026-06-03. The VuFind catalog REST API and both OAI-PMH endpoints returned valid responses; the Shibboleth IdP and auth documentation resolve but the identity service is gated to registered service providers. The digital repository `/api` path requires authentication (HTTP 401) and no IIIF root was found. No `data.msu.edu` open-data API, central `api.msu.edu`/`developer.msu.edu` gateway, or public status page was found. The `scholars.msu.edu` research-profiles system runs on Symplectic Elements with no confirmed open public API. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
