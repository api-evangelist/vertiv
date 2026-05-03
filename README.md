# Vertiv

Vertiv is a global provider of critical digital infrastructure and continuity solutions for data centers and communication networks. The company delivers power management, thermal management, IT management software (DCIM), and infrastructure monitoring solutions through brands including Geist (DCIM and PDU monitoring), Avocent (IT management and KVM), and Liebert (UPS and thermal).

**URL:** [https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/apis.yml)

## Tags

- Critical Infrastructure
- Data Center
- DCIM
- Infrastructure Monitoring
- Power Management
- UPS

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

### Vertiv Environet Alert REST API

The Vertiv Environet Alert Public REST API provides programmatic access to Vertiv's DCIM monitoring platform. The API enables retrieval of device data, sensor readings, environmental metrics, alerts, alarms, circuit information, rack details, and asset management data.

- **Documentation:** [REST API Guide (PDF)](https://www.vertiv.com/48ea2d/globalassets/products/monitoring-control-and-management/software/vertiv-environet-alert-public-rest-api-v1-guide-sl-70596.pdf)
- **OpenAPI Spec:** [vertiv-environet-alert-openapi.yml](openapi/vertiv-environet-alert-openapi.yml)

### Vertiv Avocent ADX Ecosystem API

The Vertiv Avocent ADX Ecosystem API provides REST API access for managing IT infrastructure through the Avocent ADX Management Platform. Supports device management, KVM session management, and user administration.

- **API Guide (PDF):** [Avocent ADX Ecosystem API Guide](https://www.vertiv.com/4a648a/globalassets/shared/vertiv-avocent-adx-ecosystem-api-guide.pdf)

### Vertiv Avocent DSView API

REST API for launching KVM, serial, and virtual viewer sessions to managed devices via the DSView centralized management platform.

- **Documentation:** [DSView API Technical Note (PDF)](https://www.vertiv.com/48ee3b/globalassets/products/monitoring-control-and-management/digital-infrastructure-solutions/vertiv-avocent-dsview-solution/vertiv-avocent-dsview-api-tech-note_aug-2023.pdf)

### Vertiv Geist PDU REST API

REST API for programmatic control of Geist intelligent rack PDUs including outlet power control, configuration, and energy monitoring.

- **Documentation:** [Geist Open API Integration](https://www.geistglobal.com/open-api-and-software-integration)

### Vertiv Avocent ACS800/8000 REST API

Native RESTful API for the Avocent Advanced Console System providing serial console server management.

- **Documentation:** [ACS API Guide (PDF)](https://www.vertiv.com/48ea81/globalassets/shared/avocent-acs8008000-application-programming-interface_0.pdf)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [vertiv-environet-alert-openapi.yml](openapi/vertiv-environet-alert-openapi.yml) | Vertiv Environet Alert REST API — devices, alarms, sensors, racks, circuits, assets |

### Capabilities (Naftiko)

| File | Description |
|------|-------------|
| [capabilities/dcim-monitoring.yaml](capabilities/dcim-monitoring.yaml) | Unified DCIM monitoring workflow — REST and MCP interfaces for data center ops |
| [capabilities/shared/environet-alert.yaml](capabilities/shared/environet-alert.yaml) | Shared Environet Alert API consumed definition |

### Spectral Rules

| File | Description |
|------|-------------|
| [rules/vertiv-environet-rules.yml](rules/vertiv-environet-rules.yml) | Spectral ruleset enforcing Vertiv Environet API conventions |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [json-schema/vertiv-alarm-schema.json](json-schema/vertiv-alarm-schema.json) | Alarm entity schema |
| [json-schema/vertiv-device-schema.json](json-schema/vertiv-device-schema.json) | Device entity schema |
| [json-schema/vertiv-sensor-schema.json](json-schema/vertiv-sensor-schema.json) | Sensor data point schema |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [json-structure/vertiv-alarm-structure.json](json-structure/vertiv-alarm-structure.json) | Alarm field structure documentation |
| [json-structure/vertiv-device-structure.json](json-structure/vertiv-device-structure.json) | Device field structure documentation |

### JSON-LD

| File | Description |
|------|-------------|
| [json-ld/vertiv-context.jsonld](json-ld/vertiv-context.jsonld) | JSON-LD context mapping Vertiv vocabulary to schema.org |

### Examples

| Example | Description |
|---------|-------------|
| [examples/vertiv-authenticate-example.json](examples/vertiv-authenticate-example.json) | Authentication request/response |
| [examples/vertiv-list-alarms-example.json](examples/vertiv-list-alarms-example.json) | List active alarms |
| [examples/vertiv-list-devices-example.json](examples/vertiv-list-devices-example.json) | List DCIM devices |
| [examples/vertiv-list-sensors-example.json](examples/vertiv-list-sensors-example.json) | List environmental sensors |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/vertiv-vocabulary.yml](vocabulary/vertiv-vocabulary.yml) | DCIM and power management domain vocabulary |

## Common Properties

- [Website](https://www.vertiv.com/)
- [Monitoring & Management Products](https://www.vertiv.com/en-us/products-catalog/monitoring-control-and-management/)
- [Geist Brand](https://www.geistglobal.com/)
- [Geist Open API Integration](https://www.geistglobal.com/open-api-and-software-integration)
- [Software Downloads](https://www.vertiv.com/en-us/support/software-downloads/)
- [Support](https://www.vertiv.com/en-us/support/)
- [Vertiv IS/IT GitHub](https://github.com/enp-isit)

## Maintainers

**Kin Lane** — kin@apievangelist.com
