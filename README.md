# Cisco Control Hub (cisco-control-hub)

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

Cisco Control Hub is the administration console for Webex services. Programmatic access is delivered through the Webex Admin and adjacent REST APIs at webexapis.com — covering people, organizations, locations, workspaces, devices, licenses, calling configuration, audit events, and analytics reports. Authentication uses OAuth 2.0 access tokens or service-app tokens scoped to the organization.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cisco-control-hub/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cisco-control-hub/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Administration
- Calling
- Collaboration
- Communications
- Device Management
- Identity Management
- Licenses
- Reporting
- Webex

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-23

## APIs

### Webex Admin API

Manage users, licenses, organization settings, and admin audit events for a Webex organization.

- **Human URL:** [https://developer.webex.com/docs/api/v1/admin-audit-events](https://developer.webex.com/docs/api/v1/admin-audit-events)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Administration
- Audit
- Organizations
- Users

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/admin-audit-events)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.webex.com/docs/getting-started#accounts-and-authentication)
- [Postman Collection](collections/cisco-control-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-control-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Calling API

Manage Webex Calling features, phone numbers, dial plans, voice portals, and other organization-wide voice settings.

- **Human URL:** [https://developer.webex.com/docs/api/v1/webex-calling-organization-settings](https://developer.webex.com/docs/api/v1/webex-calling-organization-settings)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Calling
- Phone Numbers
- Telephony
- Voice

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/webex-calling-organization-settings)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-control-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-control-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Devices API

Manage Webex Room and Desk Devices, MPP phones, and headsets; query device status and push configuration.

- **Human URL:** [https://developer.webex.com/docs/api/v1/devices](https://developer.webex.com/docs/api/v1/devices)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Configuration
- Devices
- Endpoints
- Room Systems

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/devices)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-control-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-control-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Workspaces API

Manage physical and virtual workspaces, meeting rooms, and shared-mode devices.

- **Human URL:** [https://developer.webex.com/docs/api/v1/workspaces](https://developer.webex.com/docs/api/v1/workspaces)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Locations
- Meeting Rooms
- Workspaces

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/workspaces)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-control-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-control-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex People API

Manage user profiles, status, presence, and directory information.

- **Human URL:** [https://developer.webex.com/docs/api/v1/people](https://developer.webex.com/docs/api/v1/people)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Directory
- People
- Profiles
- Users

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/people)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-control-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-control-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Organizations API

Inspect and manage Webex organization metadata and global settings.

- **Human URL:** [https://developer.webex.com/docs/api/v1/organizations](https://developer.webex.com/docs/api/v1/organizations)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Configuration
- Organizations
- Settings

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/organizations)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-control-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-control-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Licenses API

List and assign Webex licenses and subscription entitlements to users.

- **Human URL:** [https://developer.webex.com/docs/api/v1/licenses](https://developer.webex.com/docs/api/v1/licenses)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Entitlements
- Licenses
- Subscriptions

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/licenses)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-control-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-control-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Locations API

Manage geographic locations used by Webex Calling for emergency services routing, time zones, and number assignments.

- **Human URL:** [https://developer.webex.com/docs/api/v1/locations](https://developer.webex.com/docs/api/v1/locations)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Calling
- Geography
- Locations

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/locations)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-control-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-control-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Reports API

Generate and download analytics and usage reports for Webex services.

- **Human URL:** [https://developer.webex.com/docs/api/v1/reports](https://developer.webex.com/docs/api/v1/reports)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Analytics
- Metrics
- Reports
- Usage

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/reports)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-control-hub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-control-hub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.webex.com)
- [Console](https://admin.webex.com)
- [Authentication](https://developer.webex.com/docs/getting-started#accounts-and-authentication)
- [Rate Limits](https://developer.webex.com/docs/api-guidelines#rate-limiting)
- [Status Page](https://status.webex.com)
- [Support](https://developer.webex.com/support)
- [Changelog](https://developer.webex.com/changelog)
- [GitHub Organization](https://github.com/WebexSamples)
- [Terms of Service](https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end-user-license-agreement.html)
- [Privacy Policy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [JSON-LD](json-ld/cisco-control-hub-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/cisco-control-hub-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
