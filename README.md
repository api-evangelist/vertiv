# Vertiv (vertiv)

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

Vertiv is a global provider of critical digital infrastructure and continuity solutions for data centers and communication networks. The company delivers power management, thermal management, IT management software (DCIM), and infrastructure monitoring solutions through brands including Geist (DCIM and PDU monitoring), Avocent (IT management and KVM), and Liebert (UPS and thermal). Vertiv's software platforms expose REST APIs for integrating with third-party systems, automation workflows, and data center management platforms.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Critical Infrastructure
- Data Center
- DCIM
- Infrastructure Monitoring
- Power Management
- UPS

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Vertiv Environet Alert REST API

The Vertiv Environet Alert Public REST API provides programmatic access to Vertiv's DCIM monitoring platform for data centers. The API enables retrieval of device data, sensor readings, environmental metrics, alerts, alarms, circuit information, rack details, and asset management data. Authentication uses HTTP Basic credentials (POST x-www-form-urlencoded). The API supports integration with third-party DCIM, ITSM, and automation platforms.

- **Human URL:** [https://www.vertiv.com/en-us/products-catalog/monitoring-control-and-management/software/vertiv-environet-alert/](https://www.vertiv.com/en-us/products-catalog/monitoring-control-and-management/software/vertiv-environet-alert/)

#### Tags

- Alerts
- Asset Management
- DCIM
- Environmental Monitoring
- Infrastructure Monitoring
- Sensors

#### Properties

- [Documentation](https://www.vertiv.com/48ea2d/globalassets/products/monitoring-control-and-management/software/vertiv-environet-alert-public-rest-api-v1-guide-sl-70596.pdf)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/openapi/vertiv-environet-alert-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/json-schema/vertiv-alarm-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Ruleset](https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/rules/vertiv-environet-rules.yml)
- [Postman Collection](collections/vertiv-environet-alert.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vertiv-environet-alert.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vertiv Avocent ADX Ecosystem API

The Vertiv Avocent ADX Ecosystem API provides REST API access for managing IT infrastructure through the Avocent ADX Management Platform. The API supports device management, KVM session management, user administration, and configuration of server management functions including the MP1000 Management Platform.

- **Human URL:** [https://www.vertiv.com/en-us/products-catalog/monitoring-control-and-management/digital-infrastructure-solutions/vertiv-avocent-mp1000-management-platform/](https://www.vertiv.com/en-us/products-catalog/monitoring-control-and-management/digital-infrastructure-solutions/vertiv-avocent-mp1000-management-platform/)

#### Tags

- Avocent
- IT Management
- KVM
- Server Management

#### Properties

- [Documentation](https://www.vertiv.com/4a648a/globalassets/shared/vertiv-avocent-adx-ecosystem-api-guide.pdf)
- [Postman Collection](collections/vertiv-environet-alert.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vertiv-environet-alert.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vertiv Avocent DSView API

The Vertiv Avocent DSView Solution REST API enables launching of KVM, serial, and virtual viewer sessions to managed devices. The API provides programmatic control of session management, device inventory, and user access workflows for the DSView centralized management platform.

- **Human URL:** [https://www.vertiv.com/en-us/products/monitoring-control--management/vertiv-avocent-dsview-solution/](https://www.vertiv.com/en-us/products/monitoring-control--management/vertiv-avocent-dsview-solution/)

#### Tags

- Avocent
- DSView
- IT Management
- KVM
- Session Management

#### Properties

- [Documentation](https://www.vertiv.com/48ee3b/globalassets/products/monitoring-control-and-management/digital-infrastructure-solutions/vertiv-avocent-dsview-solution/vertiv-avocent-dsview-api-tech-note_aug-2023.pdf)
- [Postman Collection](collections/vertiv-environet-alert.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vertiv-environet-alert.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vertiv Geist PDU REST API

The Vertiv Geist Power Distribution Unit (PDU) REST API provides programmatic control of Geist intelligent rack PDUs. The API supports outlet power control (on/off with delay), outlet configuration, device information retrieval, and energy monitoring. Authentication uses token- based auth via POST to the auth endpoint.

- **Human URL:** [https://www.geistglobal.com/open-api-and-software-integration](https://www.geistglobal.com/open-api-and-software-integration)

#### Tags

- Energy Monitoring
- Outlet Control
- PDU
- Power Distribution
- Power Management

#### Properties

- [Documentation](https://www.geistglobal.com/open-api-and-software-integration)
- [Postman Collection](collections/vertiv-environet-alert.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vertiv-environet-alert.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vertiv Avocent ACS800/8000 REST API

The Vertiv Avocent ACS800/8000 Advanced Console System native RESTful API provides programmatic access to serial console server management. The API supports device configuration, port management, user administration, and session management for out-of-band management of network infrastructure.

- **Human URL:** [https://www.vertiv.com/en-us/products/monitoring-control--management/avocent-embedded-management-systems/](https://www.vertiv.com/en-us/products/monitoring-control--management/avocent-embedded-management-systems/)

#### Tags

- Avocent
- Console Server
- Out-of-Band Management
- Serial Console

#### Properties

- [Documentation](https://www.vertiv.com/48ea81/globalassets/shared/avocent-acs8008000-application-programming-interface_0.pdf)
- [Postman Collection](collections/vertiv-environet-alert.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vertiv-environet-alert.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/vertiv)
- [Website](https://www.vertiv.com/)
- [Documentation](https://www.vertiv.com/en-us/products-catalog/monitoring-control-and-management/)
- [Website](https://www.geistglobal.com/)
- [Documentation](https://www.geistglobal.com/open-api-and-software-integration)
- [Downloads](https://www.vertiv.com/en-us/support/software-downloads/)
- [Support](https://www.vertiv.com/en-us/support/)
- [GitHub Organization](https://github.com/enp-isit)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
