# Clover (clover)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Clover is a Fiserv-owned point-of-sale platform for small and mid-size merchants. The Clover developer platform exposes the Clover REST API for inventory/orders/customers/transactions, the Ecommerce API for online payments, an Android Payments API and Clover Android SDK for native apps on Clover devices, the REST Pay Display API for semi-integrated POS, the Remote Pay SDKs (cloud, Windows, iOS, Android), and the Clover Go SDK.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/clover/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/clover/refs/heads/main/apis.yml)

## Tags

- Restaurant
- POS
- Payments
- Retail
- SMB
- Hardware

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-06-02

## APIs

### Clover REST API

Foundational REST API for merchant data: inventory, orders, customers, employees, line items, modifiers, payments, refunds, and more. OAuth-based auth with sandbox and production environments.

- **Human URL:** [https://docs.clover.com/reference](https://docs.clover.com/reference)
- **Base URL:** `https://api.clover.com`

#### Tags

- REST
- Merchant
- Inventory
- Orders

#### Properties

- [Documentation](https://docs.clover.com/reference)
- [Sandbox](https://sandbox.dev.clover.com/)
- [OpenAPI](openapi/clover-platform-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clover-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clover-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clover Ecommerce API

Online payments API for charges, refunds, tokenization, recurring payments, and gift cards.

- **Human URL:** [https://docs.clover.com/](https://docs.clover.com/)
- **Base URL:** `https://api.clover.com`

#### Tags

- REST
- Payments
- Ecommerce

#### Properties

- [Documentation](https://docs.clover.com/)
- [OpenAPI](openapi/clover-ecommerce-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clover-ecommerce-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clover-ecommerce-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clover Android SDK

Native SDK for Android apps running on Clover devices, with access to merchant data and device hardware.

- **Human URL:** [https://docs.clover.com/](https://docs.clover.com/)

#### Tags

- SDK
- Android
- Hardware

#### Properties

- [Documentation](https://docs.clover.com/)
- [SDK](https://search.maven.org/artifact/com.clover.sdk/clover-android-sdk)
- [SDK](https://github.com/clover/clover-android-sdk)
- [Postman Collection](collections/clover-ecommerce-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clover-ecommerce-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/clover-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clover-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clover Android Payments API

Payment-processing API for Android apps on Clover devices that abstracts device configuration.

- **Human URL:** [https://docs.clover.com/](https://docs.clover.com/)

#### Tags

- SDK
- Android
- Payments

#### Properties

- [Documentation](https://docs.clover.com/)
- [Postman Collection](collections/clover-ecommerce-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clover-ecommerce-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/clover-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clover-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clover REST Pay Display API

Semi-integrated POS API for merchant-facing Pay Display flows on Clover devices.

- **Human URL:** [https://docs.clover.com/](https://docs.clover.com/)

#### Tags

- REST
- Pay Display
- Semi-Integrated

#### Properties

- [Documentation](https://docs.clover.com/)
- [Postman Collection](collections/clover-ecommerce-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clover-ecommerce-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/clover-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clover-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clover Remote Pay SDKs

Remote Pay SDKs for Cloud, Windows, iOS, and Android integrations with Clover devices.

- **Human URL:** [https://docs.clover.com/](https://docs.clover.com/)

#### Tags

- SDK
- Remote Pay

#### Properties

- [Documentation](https://docs.clover.com/)
- [SDK](https://www.npmjs.com/package/remote-pay-cloud)
- [SDK](https://github.com/clover/remote-pay-windows)
- [SDK](https://github.com/clover/remote-pay-android)
- [SDK](https://github.com/clover/remote-pay-ios)
- [Postman Collection](collections/clover-ecommerce-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clover-ecommerce-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/clover-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clover-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clover Go SDK

Mobile SDK (iOS, Android) for accepting card-present payments via Clover Go readers.

- **Human URL:** [https://docs.clover.com/](https://docs.clover.com/)

#### Tags

- SDK
- Mobile
- Card Reader

#### Properties

- [Documentation](https://docs.clover.com/)
- [SDK](https://github.com/clover/clover-ios-payment-sdk)
- [Postman Collection](collections/clover-ecommerce-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clover-ecommerce-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/clover-platform-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clover-platform-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/clover)
- [LinkedIn](https://www.linkedin.com/company/clovernetwork)
- [Website](https://www.clover.com/)
- [Developer](https://docs.clover.com/)
- [Plans](plans/clover-plans-pricing.yml)
- [Rate Limits](rate-limits/clover-rate-limits.yml)
- [Fin Ops](finops/clover-finops.yml)
- [Rules](rules/clover-spectral-rules.yml)
- [Vocabulary](vocabulary/clover-vocabulary.yaml)
- [JSON-LD](json-ld/clover-platform-rest-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/clover-ecommerce-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [L L Ms Txt](https://docs.clover.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
