# Neon One (neonone)

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
