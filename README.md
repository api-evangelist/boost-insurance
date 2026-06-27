# Boost Insurance (boost-insurance)

Boost Insurance is an insurance-as-a-service / embedded-insurance infrastructure platform that packages compliance, capital, and technology into a turnkey, white-labeled program accessible through a modern RESTful API. The Boost Policy Admin System (PAS) lets partners quote, bind, issue, endorse, cancel, and manage claims for admitted and surplus-lines products using JSON over OAuth 2.0.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/boost-insurance/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/boost-insurance/refs/heads/main/apis.yml)

## Tags

- Insurance
- Embedded Insurance
- Insurance-as-a-Service
- Policy Administration
- Claims

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Boost Insurance Programs API

Insurance programs and products configured on the Boost Policy Admin System (Pet, Small Business Cyber, Renters, and partner programs) that define the forms, coverages, and rating used to generate quotes and policies.

- **Human URL:** [https://learn.boostinsurance.com/docs](https://learn.boostinsurance.com/docs)
- **Base URL:** `https://api.insurtech.dev`

#### Tags

- Programs
- Products
- Insurance

#### Properties

- [Documentation](https://learn.boostinsurance.com/docs)
- [OpenAPI](openapi/boost-insurance-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/boost-insurance.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/boost-insurance.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Boost Insurance Quotes API

Rate and quote insurance coverage by POSTing applicant and coverage data to the /quotes endpoint, then manage quote state, modifications, documents, and referral handling prior to binding.

- **Human URL:** [https://learn.boostinsurance.com/docs/policy-flow](https://learn.boostinsurance.com/docs/policy-flow)
- **Base URL:** `https://api.insurtech.dev`

#### Tags

- Quotes
- Rating
- Underwriting

#### Properties

- [Documentation](https://learn.boostinsurance.com/docs/policy-flow)
- [OpenAPI](openapi/boost-insurance-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/boost-insurance.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/boost-insurance.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Boost Insurance Policies API

Bind and issue a policy by POSTing a Quote ID to the /policies endpoint; Boost generates and delivers the policy with all coverages, dates, and entity information, and manages the lifecycle through cancellation.

- **Human URL:** [https://learn.boostinsurance.com/docs/policy-flow](https://learn.boostinsurance.com/docs/policy-flow)
- **Base URL:** `https://api.insurtech.dev`

#### Tags

- Policies
- Binding
- Issuance

#### Properties

- [Documentation](https://learn.boostinsurance.com/docs/policy-flow)
- [OpenAPI](openapi/boost-insurance-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/boost-insurance.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/boost-insurance.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Boost Insurance Claims API

First Notice of Loss (FNOL) and claims API that lets customers file claims tied to a policy; Boost handles adjudication in-house or via TPA partners and acts as the single source of truth for claim status.

- **Human URL:** [https://learn.boostinsurance.com/docs/claims-flow](https://learn.boostinsurance.com/docs/claims-flow)
- **Base URL:** `https://api.insurtech.dev`

#### Tags

- Claims
- FNOL
- Adjudication

#### Properties

- [Documentation](https://learn.boostinsurance.com/docs/claims-flow)
- [Documentation](https://learn.boostinsurance.com/docs/intro-to-claims)
- [OpenAPI](openapi/boost-insurance-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/boost-insurance.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/boost-insurance.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Boost Insurance Endorsements API

Midterm endorsements and policy modifications, including coverage changes, cancellations, and voids applied to an in-force policy.

- **Human URL:** [https://learn.boostinsurance.com/docs](https://learn.boostinsurance.com/docs)
- **Base URL:** `https://api.insurtech.dev`

#### Tags

- Endorsements
- Midterm Changes
- Cancellations

#### Properties

- [Documentation](https://learn.boostinsurance.com/docs)
- [OpenAPI](openapi/boost-insurance-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/boost-insurance.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/boost-insurance.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Boost Insurance Webhooks API

Outbound webhook notifications that alert partners when policies are delivered or when a claim is updated, so they can pull the latest information and stay in sync with Boost adjudications.

- **Human URL:** [https://learn.boostinsurance.com/docs/claims-flow](https://learn.boostinsurance.com/docs/claims-flow)
- **Base URL:** `https://api.insurtech.dev`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://learn.boostinsurance.com/docs/claims-flow)
- [OpenAPI](openapi/boost-insurance-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/boost-insurance.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/boost-insurance.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/boostinsurance)
- [Website](https://www.boostinsurance.com)
- [Documentation](https://learn.boostinsurance.com/docs)
- [Plans](plans/boost-insurance-plans-pricing.yml)
- [Rate Limits](rate-limits/boost-insurance-rate-limits.yml)
- [Fin Ops](finops/boost-insurance-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
