# Vertiv (vertiv)

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
