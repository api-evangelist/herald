# Herald (herald)

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

Herald builds digital infrastructure for commercial insurance, providing a single unified REST API that lets software platforms quote and bind across many carriers and lines of business. Developers create applications, submit them to carriers, and receive normalized quotes, products, classifications, and files through one integration secured with OAuth2 client-credentials bearer tokens.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/herald/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/herald/refs/heads/main/apis.yml)

## Tags

- Insurance
- Insurtech
- Commercial Insurance
- Quoting
- Carriers

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Herald Applications API

Create and manage commercial-insurance applications for a set of products, supplying risk_values and coverage_values until the application is complete and ready to submit to carriers.

- **Human URL:** [https://docs.heraldapi.com/docs/heraldapi/5c69a421b6680-api-reference](https://docs.heraldapi.com/docs/heraldapi/5c69a421b6680-api-reference)
- **Base URL:** `https://api.heraldapi.com`

#### Tags

- Applications
- Risk Values
- Coverage Values

#### Properties

- [Documentation](https://www.heraldai.com/docs/application)
- [API Reference](https://docs.heraldapi.com/docs/heraldapi/5c69a421b6680-api-reference)
- [OpenAPI](openapi/herald-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/herald.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/herald.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Herald Quotes API

Submit completed applications to carriers via submissions and retrieve normalized quotes, polling individual quotes by quote_id until each quote and its files reach an available status.

- **Human URL:** [https://www.heraldapi.com/docs/quotes](https://www.heraldapi.com/docs/quotes)
- **Base URL:** `https://api.heraldapi.com`

#### Tags

- Quotes
- Submissions
- Binding

#### Properties

- [Documentation](https://www.heraldapi.com/docs/quotes)
- [OpenAPI](openapi/herald-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/herald.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/herald.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Herald Products API

List the insurance products a producer has access to, each identified by a unique product_id describing the carrier and line of business along with its appetite and underwriting question set.

- **Human URL:** [https://www.heraldai.com/docs/products](https://www.heraldai.com/docs/products)
- **Base URL:** `https://api.heraldapi.com`

#### Tags

- Products
- Producers
- Appetite

#### Properties

- [Documentation](https://www.heraldai.com/docs/products)
- [OpenAPI](openapi/herald-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/herald.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/herald.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Herald Classifications API

Look up Herald's normalized NAICS index-entry classifications, where each Herald Code maps to the corresponding carrier code for every supported product so risk can be classified consistently across carriers.

- **Human URL:** [https://www.heraldai.com/docs/classifications](https://www.heraldai.com/docs/classifications)
- **Base URL:** `https://api.heraldapi.com`

#### Tags

- Classifications
- NAICS
- Industry Codes

#### Properties

- [Documentation](https://www.heraldai.com/docs/classifications)
- [OpenAPI](openapi/herald-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/herald.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/herald.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Herald Distributors API

Create and manage distributors - the organizational layer above producers - then create and list the producers beneath each distributor that connect to products and submit applications.

- **Human URL:** [https://www.heraldai.com/docs/create-and-manage-distributors](https://www.heraldai.com/docs/create-and-manage-distributors)
- **Base URL:** `https://api.heraldapi.com`

#### Tags

- Distributors
- Producers
- Onboarding

#### Properties

- [Documentation](https://www.heraldai.com/docs/create-and-manage-distributors)
- [OpenAPI](openapi/herald-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/herald.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/herald.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Herald Files API

Retrieve file metadata by file_id and generate temporary download links for quote letters, applications, and policy documents once a file reaches an available status.

- **Human URL:** [https://www.heraldai.com/docs/getting-files](https://www.heraldai.com/docs/getting-files)
- **Base URL:** `https://api.heraldapi.com`

#### Tags

- Files
- Documents
- Downloads

#### Properties

- [Documentation](https://www.heraldai.com/docs/getting-files)
- [OpenAPI](openapi/herald-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/herald.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/herald.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Herald Webhooks API

Register webhook subscriptions and receive POST callbacks for status-change and creation events such as quote, file, and policy status updates and submission creation, retried on non-200 responses.

- **Human URL:** [https://www.heraldai.com/docs/webhooks](https://www.heraldai.com/docs/webhooks)
- **Base URL:** `https://api.heraldapi.com`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://www.heraldai.com/docs/webhooks)
- [OpenAPI](openapi/herald-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/herald.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/herald.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/heraldapi)
- [Website](https://www.heraldapi.com)
- [Documentation](https://docs.heraldapi.com)
- [Plans](plans/herald-plans-pricing.yml)
- [Rate Limits](rate-limits/herald-rate-limits.yml)
- [Fin Ops](finops/herald-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
