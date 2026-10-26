# Function Health (function-health)

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
