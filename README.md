# Clover (clover)

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
