# Michigan State University (michigan-state-university)

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
