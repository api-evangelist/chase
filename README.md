# Chase (chase)

JPMorgan Chase Bank, N.A. is a leading US financial institution providing consumer and commercial banking, credit cards, mortgages, and merchant services. The Chase Developer Portal exposes APIs for FDX-aligned account aggregation, customer consent, rewards balances, and the Loyalty Pay with Points platform that lets enrolled merchants and partners enable customers to redeem Ultimate Rewards points at checkout.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Account Aggregation, Banking, Consent, Credit Cards, FDX, Financial Services, Loyalty, Open Banking, Pay with Points, Rewards

## Timestamps

- **Created:** 2025-02-21
- **Modified:** 2026-04-23

## APIs

### Chase Account and Customer Information API

FDX-aligned API for retrieving Chase customer accounts, balances, transactions, statements, and tax forms with explicit customer consent.

- **Human URL:** [https://developer.chase.com/products/aggregation-fdx/](https://developer.chase.com/products/aggregation-fdx/)
- **Base URL:** `https://api.chase.com/aggregation/fdx`
- **OpenAPI:** [openapi/chase-account-and-customer-information-api-openapi.yml](openapi/chase-account-and-customer-information-api-openapi.yml)

### Chase Account Aggregation User Consent API

Consent management API implementing the FDX consent model for managing access to Chase customer data by authorized data recipients.

- **Human URL:** [https://developer.chase.com/products/aggregation-consent/](https://developer.chase.com/products/aggregation-consent/)
- **Base URL:** `https://api.chase.com/aggregation/consent`
- **OpenAPI:** [openapi/chase-account-aggregation-user-consent-api-openapi.yml](openapi/chase-account-aggregation-user-consent-api-openapi.yml)

### Chase Rewards Balance API

Retrieves a Chase cardholder's Ultimate Rewards points balance for use in loyalty experiences and Pay with Points checkouts.

- **Human URL:** [https://developer.chase.com/products/rewards-balance-api/](https://developer.chase.com/products/rewards-balance-api/)
- **Base URL:** `https://api.chase.com/loyalty/rewards-balance`
- **OpenAPI:** [openapi/chase-rewards-balance-api-openapi.yml](openapi/chase-rewards-balance-api-openapi.yml)

### Chase Loyalty Pay with Points Order Service API

Order service for redeeming Chase Ultimate Rewards points against purchases. Supports order creation, capture, refund, and reversal flows.

- **Human URL:** [https://developer.chase.com/products/loyalty-pay-with-points-order-service/](https://developer.chase.com/products/loyalty-pay-with-points-order-service/)
- **Base URL:** `https://api.chase.com/loyalty/pay-with-points/orders`
- **OpenAPI:** [openapi/chase-loyalty-pay-with-points-order-service-api-openapi.yml](openapi/chase-loyalty-pay-with-points-order-service-api-openapi.yml)

### Chase Loyalty Pay with Points Enrollment Service API

Enrolls customer payment cards in the Chase Pay with Points program so points can be redeemed against future purchases.

- **Human URL:** [https://developer.chase.com/products/loyalty-pay-with-points-enrollment-service/](https://developer.chase.com/products/loyalty-pay-with-points-enrollment-service/)
- **Base URL:** `https://api.chase.com/loyalty/pay-with-points/enrollment`
- **OpenAPI:** [openapi/chase-loyalty-pay-with-points-enrollment-service-api-openapi.yml](openapi/chase-loyalty-pay-with-points-enrollment-service-api-openapi.yml)

### Chase Loyalty PCI Merchant Relationship Manager API

PCI-compliant merchant management for the Chase loyalty platform. Used to onboard merchants, update merchant profiles, and configure integration settings.

- **Human URL:** [https://developer.chase.com/products/loyalty-pci-merchant-relation-manager/](https://developer.chase.com/products/loyalty-pci-merchant-relation-manager/)
- **Base URL:** `https://api.chase.com/loyalty/merchant-relationship-manager`
- **OpenAPI:** [openapi/chase-loyalty-pci-merchant-relationship-manager-api-openapi.yml](openapi/chase-loyalty-pci-merchant-relationship-manager-api-openapi.yml)

## Common Properties

- [Website](https://www.chase.com/)
- [Developer Portal](https://developer.chase.com/)
- [Demo](https://apidemo.chase.com/)
- [FAQ](https://developer.chase.com/support/faqs)
- [Glossary](https://developer.chase.com/support/glossary/)
- [Support](https://developer.chase.com/support)
- [Terms of Service](https://developer.chase.com/terms)
- [Privacy Policy](https://www.chase.com/digital/resources/privacy-security)
- [JSON-LD Context](json-ld/chase-context.jsonld)
- [Account JSON Schema](json-schema/chase-account-schema.json)
- [Rewards Balance JSON Schema](json-schema/chase-rewards-balance-schema.json)
- [Spectral Rules](spectral/chase-spectral.yml)
- [Naftiko Capabilities](naftiko/chase-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
