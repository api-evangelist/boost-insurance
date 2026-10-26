# Boost Insurance (boost-insurance)

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
