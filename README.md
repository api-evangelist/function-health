# Function Health (function-health)

Function Health is a consumer longevity and preventive-health membership that runs 100+ lab biomarkers twice a year through Quest Diagnostics, adds clinician review, a biological age calculation, and an AI health companion via a web and mobile dashboard. As of this catalog Function Health does not publish a public or partner developer API; member data is accessed through the member dashboard, PDF export, in-product Connected Apps (wearable sync), and an opt-in ChatGPT app that shares a high-level summary of results.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/function-health/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/function-health/refs/heads/main/apis.yml)

> Note: No public or developer API is documented by Function Health. The entries below describe member-facing data access surfaces (dashboard, export, connected apps, ChatGPT app). The OpenAPI document carries no paths because no programmatic endpoints are published. See [review.yml](review.yml) for the full assessment.

## Tags

- Health
- Longevity
- Lab Testing
- Biomarkers
- Preventive Health
- Consumer Health

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Function Health Member Dashboard

Authenticated member web and mobile dashboard for viewing 100+ lab biomarkers, trends across testing rounds, clinician notes, biological age, and a personalized action plan. There is no documented public API behind the dashboard; access is interactive only.

- **Human URL:** [https://my.functionhealth.com](https://my.functionhealth.com)

#### Tags

- Lab Results
- Biomarkers
- Dashboard
- Consumer Health

#### Properties

- [Website](https://www.functionhealth.com)
- [Sign Up](https://my.functionhealth.com/documents)
- [OpenAPI](openapi/function-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/function-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/function-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Function Health Results Export

Member-initiated PDF export of lab results from the documents area of the dashboard. This is a manual download for data portability, not a programmatic API; third-party trackers import the resulting PDF.

- **Human URL:** [https://my.functionhealth.com/documents](https://my.functionhealth.com/documents)

#### Tags

- Export
- PDF
- Lab Results
- Data Portability

#### Properties

- [Documentation](https://my.functionhealth.com/documents)
- [OpenAPI](openapi/function-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/function-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/function-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Function Health Connected Apps

In-product Connected Apps let members link supported consumer health services (e.g. wearables and Apple Health) to sync data into Function. These are pre-built, member-authorized integrations configured in the app, not a developer API that third parties can build against.

- **Human URL:** [https://www.functionhealth.com/faqs/does-function-integrate-with-oura-fitbit-apple-health-or-other-health-services](https://www.functionhealth.com/faqs/does-function-integrate-with-oura-fitbit-apple-health-or-other-health-services)

#### Tags

- Integrations
- Wearables
- Connected Apps
- Data Sync

#### Properties

- [Documentation](https://www.functionhealth.com/faqs/does-function-integrate-with-oura-fitbit-apple-health-or-other-health-services)
- [OpenAPI](openapi/function-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/function-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/function-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Function Health ChatGPT App

An opt-in app within ChatGPT through which a member can authorize secure access to a limited, high-level summary of their lab results, with the ability to revoke access at any time. Surfaced through the ChatGPT app ecosystem; Function does not document a standalone public API for it.

- **Human URL:** [https://www.functionhealth.com](https://www.functionhealth.com)

#### Tags

- ChatGPT
- AI
- Data Sharing
- Member Authorized

#### Properties

- [Documentation](https://clpmag.com/lab-essentials/information-technology/function-health-integrates-lab-data-chatgpt-app/)
- [OpenAPI](openapi/function-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/function-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/function-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/function-health)
- [Website](https://www.functionhealth.com)
- [Documentation](https://www.functionhealth.com/faqs)
- [Plans](plans/function-health-plans-pricing.yml)
- [Rate Limits](rate-limits/function-health-rate-limits.yml)
- [Fin Ops](finops/function-health-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
