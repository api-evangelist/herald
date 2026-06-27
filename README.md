# Herald (herald)

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
