# Chase (chase)

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

JPMorgan Chase Bank, N.A. is a leading US financial institution providing consumer and commercial banking, credit cards, mortgages, and merchant services. The Chase Developer Portal exposes APIs for FDX-aligned account aggregation, customer consent, rewards balances, and the Loyalty Pay with Points platform that lets enrolled merchants and partners enable customers to redeem Ultimate Rewards points at checkout.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Account Aggregation
- Banking
- Consent
- Credit Cards
- FDX
- Financial Services
- Loyalty
- Open Banking
- Pay with Points
- Rewards

## Timestamps

- **Created:** 2025-02-21
- **Modified:** 2026-05-19

## APIs

### Chase Account and Customer Information API

FDX-aligned API that allows authorized data recipients to securely retrieve account and customer information for Chase customers. Supports account profiles, balances, transactions, statements, and customer details using OAuth 2.0 with FDX consent flows.

- **Human URL:** [https://developer.chase.com/products/aggregation-fdx/](https://developer.chase.com/products/aggregation-fdx/)
- **Base URL:** `https://api.chase.com/aggregation/fdx`

#### Tags

- Account Aggregation
- FDX
- Open Banking

#### Properties

- [Documentation](https://developer.chase.com/products/aggregation-fdx/guides/using-the-account-and-customer-information-api/)
- [OpenAPI](openapi/chase-account-and-customer-information-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chase-account-and-customer-information-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chase-account-and-customer-information-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chase Account Aggregation User Consent API

Consent management API used to obtain, store, and revoke customer consent for sharing account information with authorized third-party data recipients. Implements the FDX consent model.

- **Human URL:** [https://developer.chase.com/products/aggregation-consent/](https://developer.chase.com/products/aggregation-consent/)
- **Base URL:** `https://api.chase.com/aggregation/consent`

#### Tags

- Consent
- FDX
- Open Banking

#### Properties

- [Documentation](https://developer.chase.com/products/aggregation-consent/)
- [OpenAPI](openapi/chase-account-aggregation-user-consent-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chase-account-aggregation-user-consent-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chase-account-aggregation-user-consent-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chase Rewards Balance API

API that allows merchant and partner systems to retrieve a Chase cardholder's current rewards points balance for use in loyalty experiences and Pay with Points checkouts.

- **Human URL:** [https://developer.chase.com/products/rewards-balance-api/](https://developer.chase.com/products/rewards-balance-api/)
- **Base URL:** `https://api.chase.com/loyalty/rewards-balance`

#### Tags

- Loyalty
- Rewards

#### Properties

- [Documentation](https://developer.chase.com/products/rewards-balance-api/specification)
- [OpenAPI](openapi/chase-rewards-balance-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chase-rewards-balance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chase-rewards-balance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chase Loyalty Pay with Points Order Service API

API that lets merchants accept Chase Ultimate Rewards points as payment at checkout. Supports order creation, redemption, capture, refund, and reversal flows for the Pay with Points program.

- **Human URL:** [https://developer.chase.com/products/loyalty-pay-with-points-order-service/](https://developer.chase.com/products/loyalty-pay-with-points-order-service/)
- **Base URL:** `https://api.chase.com/loyalty/pay-with-points/orders`

#### Tags

- Loyalty
- Payments
- Rewards

#### Properties

- [Documentation](https://developer.chase.com/products/loyalty-pay-with-points-order-service/)
- [OpenAPI](openapi/chase-loyalty-pay-with-points-order-service-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chase-loyalty-pay-with-points-order-service-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chase-loyalty-pay-with-points-order-service-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chase Loyalty Pay with Points Enrollment Service API

API that allows merchants and partners to enroll customer payment cards in the Chase Pay with Points program so points can be redeemed against future purchases.

- **Human URL:** [https://developer.chase.com/products/loyalty-pay-with-points-enrollment-service/](https://developer.chase.com/products/loyalty-pay-with-points-enrollment-service/)
- **Base URL:** `https://api.chase.com/loyalty/pay-with-points/enrollment`

#### Tags

- Loyalty
- Payments
- Rewards

#### Properties

- [Documentation](https://developer.chase.com/products/loyalty-pay-with-points-enrollment-service/)
- [OpenAPI](openapi/chase-loyalty-pay-with-points-enrollment-service-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chase-loyalty-pay-with-points-enrollment-service-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chase-loyalty-pay-with-points-enrollment-service-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chase Loyalty PCI Merchant Relationship Manager API

API for managing PCI-compliant merchant relationships for the Chase loyalty platform, supporting onboarding, profile updates, and configuration of merchant integrations.

- **Human URL:** [https://developer.chase.com/products/loyalty-pci-merchant-relation-manager/](https://developer.chase.com/products/loyalty-pci-merchant-relation-manager/)
- **Base URL:** `https://api.chase.com/loyalty/merchant-relationship-manager`

#### Tags

- Loyalty
- Merchants
- PCI

#### Properties

- [Documentation](https://developer.chase.com/products/loyalty-pci-merchant-relation-manager/)
- [OpenAPI](openapi/chase-loyalty-pci-merchant-relationship-manager-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chase-loyalty-pci-merchant-relationship-manager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chase-loyalty-pci-merchant-relationship-manager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/jpmorganchase)
- [LinkedIn](https://www.linkedin.com/company/chase)
- [Website](https://www.chase.com/)
- [Developer Portal](https://developer.chase.com/)
- [Portal](https://developer.chase.com/)
- [Demo](https://apidemo.chase.com/)
- [F A Q](https://developer.chase.com/support/faqs)
- [Glossary](https://developer.chase.com/support/glossary/)
- [Support](https://developer.chase.com/support)
- [Terms of Service](https://developer.chase.com/terms)
- [Privacy Policy](https://www.chase.com/digital/resources/privacy-security)
- [JSON-LD](json-ld/chase-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/chase-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chase-rewards-balance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](spectral/chase-spectral.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
