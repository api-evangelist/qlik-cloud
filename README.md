# Qlik Cloud (qlik-cloud)

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

Collection of APIs for Qlik Cloud platform, providing data integration, analytics, and visualization capabilities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/qlik-cloud/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/qlik-cloud/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Analytics
- Business Intelligence
- Cloud
- Data Integration
- SaaS
- Visualization

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Qlik Cloud REST API

Main REST API for Qlik Cloud providing access to apps, spaces, users, and resources.

- **Human URL:** [https://qlik.dev/apis/rest](https://qlik.dev/apis/rest)

#### Tags

- Analytics
- Data

#### Properties

- [Documentation](https://qlik.dev/apis/rest)
- [Authentication](https://qlik.dev/authenticate)
- [OpenAPI](openapi/qlik-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/qlik-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qlik Engine JSON API

WebSocket-based JSON-RPC API for direct interaction with the Qlik Associative Engine.

- **Human URL:** [https://qlik.dev/apis/json-rpc](https://qlik.dev/apis/json-rpc)

#### Tags

- Engine
- WebSocket

#### Properties

- [Documentation](https://qlik.dev/apis/json-rpc)
- [SDK](https://github.com/qlik-oss/enigma.js)
- [Postman Collection](collections/qlik-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qlik Data Integration

APIs for data integration, ETL processes, and data pipeline management.

- **Human URL:** [https://qlik.dev/apis/rest/data-integration](https://qlik.dev/apis/rest/data-integration)

#### Tags

- Data Integration
- ETL

#### Properties

- [Documentation](https://qlik.dev/apis/rest/data-integration)
- [Postman Collection](collections/qlik-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qlik Reload

API for managing app reloads and data refresh operations.

- **Human URL:** [https://qlik.dev/apis/rest/reloads](https://qlik.dev/apis/rest/reloads)

#### Tags

- Reload
- Automation

#### Properties

- [Documentation](https://qlik.dev/apis/rest/reloads)
- [Postman Collection](collections/qlik-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qlik Users and Groups

Manage users, groups, and access control in Qlik Cloud.

- **Human URL:** [https://qlik.dev/apis/rest/users](https://qlik.dev/apis/rest/users)

#### Tags

- Users
- IAM

#### Properties

- [Documentation](https://qlik.dev/apis/rest/users)
- [Postman Collection](collections/qlik-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qlik Spaces

Manage shared and personal spaces for organizing Qlik content.

- **Human URL:** [https://qlik.dev/apis/rest/spaces](https://qlik.dev/apis/rest/spaces)

#### Tags

- Spaces
- Content Management

#### Properties

- [Documentation](https://qlik.dev/apis/rest/spaces)
- [Postman Collection](collections/qlik-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qlik Apps

Create, manage, and interact with Qlik Sense applications.

- **Human URL:** [https://qlik.dev/apis/rest/apps](https://qlik.dev/apis/rest/apps)

#### Tags

- Applications
- Analytics

#### Properties

- [Documentation](https://qlik.dev/apis/rest/apps)
- [Postman Collection](collections/qlik-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qlik Automations

Create and manage automated workflows in Qlik Cloud.

- **Human URL:** [https://qlik.dev/apis/rest/automations](https://qlik.dev/apis/rest/automations)

#### Tags

- Automation
- Workflows

#### Properties

- [Documentation](https://qlik.dev/apis/rest/automations)
- [Postman Collection](collections/qlik-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qlik-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/qlik)
- [Getting Started](https://qlik.dev/get-started)
- [Authentication](https://qlik.dev/authenticate)
- [Portal](https://qlik.dev)
- [Community](https://community.qlik.com)
- [GitHub Organization](https://github.com/qlik-oss)
- [Status Page](https://status.qlik.com)
- [Terms of Service](https://www.qlik.com/us/legal/terms-of-use)
- [Privacy Policy](https://www.qlik.com/us/legal/privacy)
- [Website](https://www.qlik.com)
- [Integrations](https://www.qlik.com/us/partners)
- [M C P Server](https://github.com/qlik-oss/qlik-mcp-registry)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
