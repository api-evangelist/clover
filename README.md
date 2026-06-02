# Clover (clover)

Clover is a Fiserv-owned point-of-sale platform for small and mid-size merchants. The Clover developer platform exposes the Clover REST API for inventory/orders/customers/transactions, the Ecommerce API for online payments, an Android Payments API and Clover Android SDK for native apps on Clover devices, the REST Pay Display API for semi-integrated POS, the Remote Pay SDKs (cloud, Windows, iOS, Android), and the Clover Go SDK.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/clover/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, POS, Payments, Retail, SMB, Hardware

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-06-02

## APIs

### Clover REST API
Foundational REST API for merchant data: inventory, orders, customers, employees, line items, modifiers, payments, refunds, and more. OAuth-based auth with sandbox and production environments.

**Human URL:** [https://docs.clover.com/reference](https://docs.clover.com/reference)

#### Tags:

 - REST, Merchant, Inventory, Orders

#### Properties

- [Documentation](https://docs.clover.com/reference)
- [Sandbox](https://sandbox.dev.clover.com/)
- [OpenAPI](openapi/clover-platform-rest-api-openapi.yml)
- [NaftikoCapability — Inventory](capabilities/platform-rest-api-inventory.yaml)
- [NaftikoCapability — Orders](capabilities/platform-rest-api-orders.yaml)
- [NaftikoCapability — Payments](capabilities/platform-rest-api-payments.yaml)
- [NaftikoCapability — Customers](capabilities/platform-rest-api-customers.yaml)
- [NaftikoCapability — Employees](capabilities/platform-rest-api-employees.yaml)

### Clover Ecommerce API
Online payments API for charges, refunds, tokenization, recurring payments, and gift cards.

**Human URL:** [https://docs.clover.com/](https://docs.clover.com/)

#### Tags:

 - REST, Payments, Ecommerce

#### Properties

- [Documentation](https://docs.clover.com/)
- [OpenAPI](openapi/clover-ecommerce-api-openapi.yml)
- [NaftikoCapability — Charges](capabilities/ecommerce-api-charges.yaml)
- [NaftikoCapability — Refunds](capabilities/ecommerce-api-refunds.yaml)
- [NaftikoCapability — Tokens](capabilities/ecommerce-api-tokens.yaml)
- [NaftikoCapability — Checkout](capabilities/ecommerce-api-checkout.yaml)

### Clover Android SDK
Native SDK for Android apps running on Clover devices, with access to merchant data and device hardware.

**Human URL:** [https://docs.clover.com/](https://docs.clover.com/)

#### Tags:

 - SDK, Android, Hardware

#### Properties

- [Documentation](https://docs.clover.com/)
- [SDK — Android SDK (Maven)](https://search.maven.org/artifact/com.clover.sdk/clover-android-sdk)
- [SDK — GitHub Source](https://github.com/clover/clover-android-sdk)

### Clover Android Payments API
Payment-processing API for Android apps on Clover devices that abstracts device configuration.

**Human URL:** [https://docs.clover.com/](https://docs.clover.com/)

#### Tags:

 - SDK, Android, Payments

#### Properties

- [Documentation](https://docs.clover.com/)

### Clover REST Pay Display API
Semi-integrated POS API for merchant-facing Pay Display flows on Clover devices.

**Human URL:** [https://docs.clover.com/](https://docs.clover.com/)

#### Tags:

 - REST, Pay Display, Semi-Integrated

#### Properties

- [Documentation](https://docs.clover.com/)

### Clover Remote Pay SDKs
Remote Pay SDKs for Cloud, Windows, iOS, and Android integrations with Clover devices.

**Human URL:** [https://docs.clover.com/](https://docs.clover.com/)

#### Tags:

 - SDK, Remote Pay

#### Properties

- [Documentation](https://docs.clover.com/)
- [SDK — Cloud SDK (npm)](https://www.npmjs.com/package/remote-pay-cloud)
- [SDK — Windows SDK](https://github.com/clover/remote-pay-windows)
- [SDK — Android SDK](https://github.com/clover/remote-pay-android)
- [SDK — iOS SDK](https://github.com/clover/remote-pay-ios)

### Clover Go SDK
Mobile SDK (iOS, Android) for accepting card-present payments via Clover Go readers.

**Human URL:** [https://docs.clover.com/](https://docs.clover.com/)

#### Tags:

 - SDK, Mobile, Card Reader

#### Properties

- [Documentation](https://docs.clover.com/)
- [SDK — iOS Payment SDK](https://github.com/clover/clover-ios-payment-sdk)

## Common Properties

- [GitHubOrganization](https://github.com/clover)
- [LinkedIn](https://www.linkedin.com/company/clovernetwork)
- [Website](https://www.clover.com/)
- [Developer](https://docs.clover.com/)
- [Plans](plans/clover-plans-pricing.yml)
- [RateLimits](rate-limits/clover-rate-limits.yml)
- [FinOps](finops/clover-finops.yml)
- [Rules](rules/clover-spectral-rules.yml)
- [Vocabulary](vocabulary/clover-vocabulary.yaml)
- [JSONLD — Platform REST API Context](json-ld/clover-platform-rest-api-context.jsonld)
- [JSONLD — Ecommerce API Context](json-ld/clover-ecommerce-api-context.jsonld)
- [LLMsTxt](https://docs.clover.com/llms.txt)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Clover Platform REST API](openapi/clover-platform-rest-api-openapi.yml)
- [Clover Ecommerce API](openapi/clover-ecommerce-api-openapi.yml)

### JSON Schema

- [Platform — Item](json-schema/platform-rest-api-item-schema.json)
- [Platform — Order](json-schema/platform-rest-api-order-schema.json)
- [Platform — Customer](json-schema/platform-rest-api-customer-schema.json)
- [Platform — Payment](json-schema/platform-rest-api-payment-schema.json)
- [Platform — Employee](json-schema/platform-rest-api-employee-schema.json)
- [Platform — Category](json-schema/platform-rest-api-category-schema.json)
- [Ecommerce — Charge](json-schema/ecommerce-api-charge-schema.json)
- [Ecommerce — Refund](json-schema/ecommerce-api-refund-schema.json)

### JSON Structure

- [Platform — Item](json-structure/platform-rest-api-item-structure.json)
- [Platform — Order](json-structure/platform-rest-api-order-structure.json)
- [Platform — Customer](json-structure/platform-rest-api-customer-structure.json)
- [Platform — Payment](json-structure/platform-rest-api-payment-structure.json)
- [Platform — Employee](json-structure/platform-rest-api-employee-structure.json)
- [Platform — Category](json-structure/platform-rest-api-category-structure.json)
- [Ecommerce — Charge](json-structure/ecommerce-api-charge-structure.json)
- [Ecommerce — Refund](json-structure/ecommerce-api-refund-structure.json)

### JSON-LD

- [Platform REST API Context](json-ld/clover-platform-rest-api-context.jsonld)
- [Ecommerce API Context](json-ld/clover-ecommerce-api-context.jsonld)

### Examples

- [Platform — Item](examples/platform-rest-api-item-example.json)
- [Platform — Order](examples/platform-rest-api-order-example.json)
- [Platform — Customer](examples/platform-rest-api-customer-example.json)
- [Platform — Payment](examples/platform-rest-api-payment-example.json)
- [Platform — Employee](examples/platform-rest-api-employee-example.json)
- [Platform — Category](examples/platform-rest-api-category-example.json)
- [Ecommerce — Charge](examples/ecommerce-api-charge-example.json)
- [Ecommerce — Refund](examples/ecommerce-api-refund-example.json)

## Capabilities

Naftiko capabilities, one self-contained file per business surface (OpenAPI tag), each exposing both a REST and an MCP adapter.

### Clover Platform REST API

| Capability | Tools |
|------------|-------|
| [Inventory](capabilities/platform-rest-api-inventory.yaml) | 8 |
| [Orders](capabilities/platform-rest-api-orders.yaml) | 8 |
| [Payments](capabilities/platform-rest-api-payments.yaml) | 2 |
| [Customers](capabilities/platform-rest-api-customers.yaml) | 5 |
| [Employees](capabilities/platform-rest-api-employees.yaml) | 4 |

### Clover Ecommerce API

| Capability | Tools |
|------------|-------|
| [Charges](capabilities/ecommerce-api-charges.yaml) | 4 |
| [Refunds](capabilities/ecommerce-api-refunds.yaml) | 3 |
| [Tokens](capabilities/ecommerce-api-tokens.yaml) | 1 |
| [Checkout](capabilities/ecommerce-api-checkout.yaml) | 1 |

## Vocabulary

- [Clover Vocabulary](vocabulary/clover-vocabulary.yaml) — Unified taxonomy mapping 9 resources, 3 actions, 9 workflows, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Clover Spectral Rules](rules/clover-spectral-rules.yml) — 28 rules across info, servers, paths, operations, tags, parameters, responses, schemas, security, and HTTP-method categories enforcing Clover API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
