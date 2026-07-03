# Neon One (neonone)

Neon One is a nonprofit technology company whose flagship product, Neon CRM, is a donor management and fundraising platform used by nonprofits and membership associations to manage constituents, donations, memberships, events, campaigns, and volunteers. Neon CRM API v2 is a RESTful, JSON-based rebuild of the legacy v1 API, authenticated with HTTP Basic Auth (org ID + API key) against a base URL of `https://api.neoncrm.com/v2`. Neon has scheduled the retirement of API v1 and its legacy webhook structure for July 11, 2026.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/neonone/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/neonone/refs/heads/main/apis.yml)

## Tags

- Nonprofit
- CRM
- Fundraising
- Donor Management
- Membership Management
- Events

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Neon One Accounts API

Individual and organization constituent records (accounts) - create, retrieve, update, and search accounts; manage linked contacts on organization accounts, mailing/shipping addresses, and account custom fields.

- **Human URL:** [https://developer.neoncrm.com/accounts/](https://developer.neoncrm.com/accounts/)
- **Base URL:** `https://api.neoncrm.com/v2`

#### Tags

- Accounts
- Constituents
- Addresses
- Contacts

#### Properties

- [Documentation](https://developer.neoncrm.com/accounts/)
- [API Reference](https://developer.neoncrm.com/api-v2/)
- [OpenAPI](openapi/neonone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/neonone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neonone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Neon One Households API

Group individual accounts into households, defining the relation type (e.g. spouse, child) each member holds within the household. Household endpoints shipped to API v2.10 on June 7, 2025.

- **Human URL:** [https://developer.neoncrm.com/2025/06/09/api-v2-10-update-households/](https://developer.neoncrm.com/2025/06/09/api-v2-10-update-households/)
- **Base URL:** `https://api.neoncrm.com/v2`

#### Tags

- Households
- Accounts
- Relationships

#### Properties

- [Documentation](https://developer.neoncrm.com/2025/06/09/api-v2-10-update-households/)
- [API Reference](https://developer.neoncrm.com/api-v2/)
- [OpenAPI](openapi/neonone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/neonone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neonone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Neon One Donations API

One-time donations, multi-payment pledges and pledge installments, recurring donation schedules, and soft credits (crediting a donation to an account other than the paying donor).

- **Human URL:** [https://developer.neoncrm.com/transactions/](https://developer.neoncrm.com/transactions/)
- **Base URL:** `https://api.neoncrm.com/v2`

#### Tags

- Donations
- Pledges
- Recurring Donations
- Soft Credits

#### Properties

- [Documentation](https://developer.neoncrm.com/transactions/)
- [API Reference](https://developer.neoncrm.com/api-v2/)
- [OpenAPI](openapi/neonone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/neonone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neonone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Neon One Campaigns API

Fundraising campaigns, including peer-to-peer/social fundraising configuration, that donations, pledges, and recurring donations are attributed to.

- **Human URL:** [https://developer.neoncrm.com/api-v2-resources/permissions/](https://developer.neoncrm.com/api-v2-resources/permissions/)
- **Base URL:** `https://api.neoncrm.com/v2`

#### Tags

- Campaigns
- Fundraising
- Peer-to-Peer

#### Properties

- [Documentation](https://developer.neoncrm.com/api-v2-resources/permissions/)
- [API Reference](https://developer.neoncrm.com/api-v2/)
- [OpenAPI](openapi/neonone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/neonone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neonone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Neon One Memberships API

Membership levels, terms, and sub-members held by an account, nested under the account resource - including active-status and primary-active-membership fields added in API v2.11.

- **Human URL:** [https://developer.neoncrm.com/2025/10/24/api-v2-11-release-notes/](https://developer.neoncrm.com/2025/10/24/api-v2-11-release-notes/)
- **Base URL:** `https://api.neoncrm.com/v2`

#### Tags

- Memberships
- Membership Terms

#### Properties

- [Documentation](https://developer.neoncrm.com/2025/10/24/api-v2-11-release-notes/)
- [API Reference](https://developer.neoncrm.com/api-v2/)
- [OpenAPI](openapi/neonone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/neonone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neonone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Neon One Events API

Events, event tickets, event registrations, and event attendees - create and manage events and process registrations against them.

- **Human URL:** [https://developer.neoncrm.com/api-v2-resources/rate-limits/](https://developer.neoncrm.com/api-v2-resources/rate-limits/)
- **Base URL:** `https://api.neoncrm.com/v2`

#### Tags

- Events
- Registrations
- Tickets
- Attendees

#### Properties

- [Documentation](https://developer.neoncrm.com/api-v2-resources/rate-limits/)
- [API Reference](https://developer.neoncrm.com/api-v2/)
- [OpenAPI](openapi/neonone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/neonone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neonone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Neon One Custom Fields API

Standard custom fields attached to accounts, donations, and events, plus the full Custom Objects framework (objects, fields, form/list layouts, relations, validators, and records) shipped to API v2.10 in April 2025 for modeling data that does not fit Neon CRM's built-in schema.

- **Human URL:** [https://developer.neoncrm.com/custom-objects/](https://developer.neoncrm.com/custom-objects/)
- **Base URL:** `https://api.neoncrm.com/v2`

#### Tags

- Custom Fields
- Custom Objects
- Configuration

#### Properties

- [Documentation](https://developer.neoncrm.com/custom-objects/)
- [Documentation](https://developer.neoncrm.com/2025/04/14/api-v2-10-update-custom-objects/)
- [API Reference](https://developer.neoncrm.com/api-v2/)
- [OpenAPI](openapi/neonone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/neonone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neonone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Neon One Orders & Store API

Orders that group multiple donations, memberships, and store purchases into a single transaction, plus the online store catalog - products, catalogs, categories, and checkout/shipping configuration.

- **Human URL:** [https://developer.neoncrm.com/2020/09/19/api-v2-1-release-notes/](https://developer.neoncrm.com/2020/09/19/api-v2-1-release-notes/)
- **Base URL:** `https://api.neoncrm.com/v2`

#### Tags

- Orders
- Store
- Products
- Shopping Cart

#### Properties

- [Documentation](https://developer.neoncrm.com/2020/09/19/api-v2-1-release-notes/)
- [Documentation](https://developer.neoncrm.com/api-v2-resources/rate-limits/)
- [API Reference](https://developer.neoncrm.com/api-v2/)
- [OpenAPI](openapi/neonone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/neonone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neonone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Neon One Volunteers API

Volunteer records, volunteer groups, volunteer opportunities and roles, opportunity shifts, and time sheets - added to API v2.9 in November 2024 and extended with role assignment during volunteer sign-up in v2.11.

- **Human URL:** [https://developer.neoncrm.com/2024/11/22/api-v2-9-updates-november-2024/](https://developer.neoncrm.com/2024/11/22/api-v2-9-updates-november-2024/)
- **Base URL:** `https://api.neoncrm.com/v2`

#### Tags

- Volunteers
- Opportunities
- Shifts
- Time Sheets

#### Properties

- [Documentation](https://developer.neoncrm.com/2024/11/22/api-v2-9-updates-november-2024/)
- [Documentation](https://developer.neoncrm.com/2025/10/24/api-v2-11-release-notes/)
- [API Reference](https://developer.neoncrm.com/api-v2/)
- [OpenAPI](openapi/neonone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/neonone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neonone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Neon One Webhooks API

Programmatically create, list, retrieve, update, and delete outbound webhook subscriptions that POST JSON notifications for create/update/delete actions on Accounts, Donations, Memberships, Event Registrations, Orders, and Activities, with automatic retry (up to 3 attempts, 2-second intervals) on failed deliveries.

- **Human URL:** [https://developer.neoncrm.com/webhooks/](https://developer.neoncrm.com/webhooks/)
- **Base URL:** `https://api.neoncrm.com/v2`

#### Tags

- Webhooks
- Notifications
- Events

#### Properties

- [Documentation](https://developer.neoncrm.com/webhooks/)
- [API Reference](https://developer.neoncrm.com/api-v2/)
- [OpenAPI](openapi/neonone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/neonone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neonone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/neoncrm)
- [LinkedIn](https://www.linkedin.com/company/neonone)
- [Website](https://neonone.com/)
- [Documentation](https://developer.neoncrm.com/)
- [Plans](plans/neonone-plans-pricing.yml)
- [Rate Limits](rate-limits/neonone-rate-limits.yml)
- [Fin Ops](finops/neonone-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
