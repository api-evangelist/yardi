# Yardi (yardi)

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

Yardi develops and supports industry-leading investment and property management software for all types and sizes of real estate companies. The platform includes solutions for residential, commercial, public housing, affordable housing, and military housing management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/yardi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/yardi/refs/heads/main/apis.yml)

## Tags

- Accounting
- Commercial Real Estate
- Coworking
- Investment Management
- Multifamily
- Property Management
- Real Estate
- Residential
- Self Storage
- Senior Living

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Yardi Voyager API

Core property management platform API providing access to accounting, operations, and reporting functionality for real estate portfolios. Yardi Voyager uses SOAP-based web services defined via WSDL, with interfaces for billing and payments, common data, service requests, vendor invoicing, job cost, and commercial data export.

- **Human URL:** [https://www.yardi.com/products/voyager/](https://www.yardi.com/products/voyager/)
- **Base URL:** `https://api.yardi.com`

#### Tags

- Accounting
- Commercial
- Property Management
- Real Estate
- Residential

#### Properties

- [Documentation](https://www.yardi.com/platform/api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/yardi/refs/heads/main/openapi/yardi-voyager-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://www.yardi.com/platform/api/authentication/)
- [Getting Started](https://www.yardi.com/company/become-an-interface-partner/)
- [Reference](https://www.yardi.com/services/interfaces/standard-interface-options/)
- [Postman Collection](collections/yardi-voyager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yardi-voyager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yardi Voyager Commercial Data API

Web service interface that provides the ability to export commercial data from Yardi Voyager databases, including property, unit, lease, and rent roll information. Built on the OSCRE standard with Yardi-specific extensions, this API expands existing services geared towards financial transactions and facilities management.

- **Human URL:** [https://www.yardi.com/news/press-releases/yardi-adds-commercial-data-interface-to-voyager-standard-interface-partnership-program/](https://www.yardi.com/news/press-releases/yardi-adds-commercial-data-interface-to-voyager-standard-interface-partnership-program/)
- **Base URL:** `https://api.yardi.com`

#### Tags

- Commercial
- Data Export
- Leasing
- OSCRE

#### Properties

- [Documentation](https://www.yardi.com/services/interfaces/standard-interface-options/)
- [Getting Started](https://www.yardi.com/company/become-an-interface-partner/)
- [Postman Collection](collections/yardi-voyager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yardi-voyager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yardi RENTCafe API

API for online rental applications, payments, and resident portal functionality for multifamily properties. RENTCafe APIv2 provides transaction-based pricing with an annual price cap, enabling vendors to integrate leasing, marketing, and resident services into their applications.

- **Human URL:** [https://www.rentcafe.com/](https://www.rentcafe.com/)
- **Base URL:** `https://api.rentcafe.com`

#### Tags

- Applications
- Multifamily
- Payments
- Portal
- Residents

#### Properties

- [Documentation](https://www.rentcafe.com/api/)
- [Terms of Service](https://resources.yardi.com/legal/rc-api-tou/)
- [Getting Started](https://www.yardi.com/company/become-an-interface-partner/)
- [Postman Collection](collections/yardi-voyager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yardi-voyager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yardi Maintenance IQ API

Maintenance and work order management API enabling integration with maintenance operations, service requests, and vendor management. Part of the Voyager Standard Interface Partnership Program, this API supports creating and updating work orders between Yardi and third-party systems.

- **Human URL:** [https://www.yardi.com/products/maintenance-iq/](https://www.yardi.com/products/maintenance-iq/)
- **Base URL:** `https://api.yardi.com/maintenance`

#### Tags

- Facilities
- Maintenance
- Vendors
- Work Orders

#### Properties

- [Documentation](https://www.yardi.com/platform/api/maintenance/)
- [Getting Started](https://www.yardi.com/company/become-an-interface-partner/)
- [Postman Collection](collections/yardi-voyager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yardi-voyager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yardi Investment Manager API

API for investment and asset management functions including deal tracking, investor reporting, and portfolio analytics. Provides programmatic access to investment management data within the Yardi Voyager platform.

- **Human URL:** [https://www.yardi.com/products/investment-manager/](https://www.yardi.com/products/investment-manager/)
- **Base URL:** `https://api.yardi.com/investment`

#### Tags

- Analytics
- Asset Management
- Investment
- Reporting

#### Properties

- [Documentation](https://www.yardi.com/platform/api/investment/)
- [Getting Started](https://www.yardi.com/company/become-an-interface-partner/)
- [Postman Collection](collections/yardi-voyager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yardi-voyager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yardi Store Web Services API

SOAP-based API for Yardi's self-storage management platform, formerly known as CenterShift. The SWS2 API provides tokenized authentication and access to store management methods for creating custom applications and websites that interact with Yardi Store Enterprise and Store Advantage systems.

- **Human URL:** [https://centershiftdevx.com/](https://centershiftdevx.com/)
- **Base URL:** `https://api.yardi.com`

#### Tags

- Reservations
- Self Storage
- SOAP
- Store Management

#### Properties

- [Documentation](https://centershiftdevx.com/2015/01/22/sws2-api-documentation/)
- [Reference](https://centershiftdevx.com/2017/01/23/end-points/)
- [Getting Started](https://centershiftdevx.com/2017/04/16/overview-using-yardi-store-web-services-sws/)
- [Support](https://centershiftdevx.com/2011/06/20/contacting-centershift/)
- [Postman Collection](collections/yardi-voyager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yardi-voyager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yardi Kube API

API and webhook integration for Yardi Kube, the coworking and flexible workspace management platform. Enables connecting third-party applications with Yardi Kube for member management, billing, space booking, access control, and CRM integrations.

- **Human URL:** [https://www.yardikube.com/integrations-api/](https://www.yardikube.com/integrations-api/)
- **Base URL:** `https://api.yardikube.com`

#### Tags

- Booking
- Coworking
- Flexible Workspace
- Webhooks

#### Properties

- [Documentation](https://www.yardikube.com/integrations-api/)
- [Postman Collection](collections/yardi-voyager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yardi-voyager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yardi Senior Living EHR API

Interface API for Yardi's Electronic Health Records platform designed for senior living communities. Supports secure data exchange with pharmacy networks, laboratory systems, and other healthcare partners through standardized interfaces including NCPDP 10.6 SCRIPT compliance.

- **Human URL:** [https://www.yardi.com/product/ehr/](https://www.yardi.com/product/ehr/)
- **Base URL:** `https://api.yardi.com`

#### Tags

- EHR
- Healthcare
- Pharmacy
- Senior Living

#### Properties

- [Documentation](https://www.yardi.com/product/ehr/)
- [Postman Collection](collections/yardi-voyager-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yardi-voyager-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/yardi-systems)
- [Portal](https://www.yardi.com/platform/)
- [Developer  Resources](https://www.yardi.com/platform/api/)
- [Support](https://www.yardi.com/support/)
- [Contact](https://www.yardi.com/contact-us/)
- [Privacy Policy](https://resources.yardi.com/legal/privacy-statement/)
- [Terms of Service](https://www.yardi.com/about-us/legal/terms-of-use/)
- [Status Page](https://status.yardi.com)
- [Website](https://www.yardi.com)
- [Blog](https://www.yardi.com/blog/)
- [Getting Started](https://www.yardi.com/company/become-an-interface-partner/)
- [Sign Up](https://www.yardi.com/company/become-an-interface-partner/)
- [Documentation](https://www.yardi.com/services/interfaces/standard-interface-options/)
- [GitHub Organization](https://github.com/YardiSystems)
- [Training](https://www.yardi.com/company/training/)
- [Login](https://www.yardi.com/company/technical-support/)
- [Integrations](https://www.yardi.com/product/marketplace/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
