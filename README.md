# Weather.gov (weather-gov)
Weather.gov is the official website of the National Weather Service (NWS), operated by NOAA within the US Department of Commerce. The NWS provides weather, hydrologic, and climate forecasts and warnings for the United States, its territories, adjacent waters, and ocean areas. The Weather.gov API provides free, open access to forecasts, alerts, observations, radar data, aviation weather, and geographic zone information across all 50 states and territories.

**URL:** [https://www.weather.gov/documentation/services-web-api](https://www.weather.gov/documentation/services-web-api)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Weather, Government, United States, Forecasting, Alerts, Open Data

## Timestamps

- **Created:** 2024-07-02T00:00:00.000Z
- **Modified:** 2026-05-03

## APIs

### Weather.gov API Web Service
The National Weather Service API provides access to real-time weather data including forecasts, alerts, observations, radar, aviation weather, and zone information for the United States. The API is free, open, and requires only a User-Agent header for identification.

**Human URL:** [https://www.weather.gov/documentation/services-web-api](https://www.weather.gov/documentation/services-web-api)

#### Tags:

 - Weather, Forecasting, Alerts, Observations, Radar, United States, Government

#### Properties

- [Weather.gov OpenAPI](openapi/openapi.yml)
- [Documentation](https://www.weather.gov/documentation/services-web-api)
- [API Reference](https://api.weather.gov/openapi.json)

## Common Properties

- [Documentation](https://www.weather.gov/documentation/services-web-api)
- [GitHub Repository](https://github.com/weather-gov/api)
- [API Reference](https://api.weather.gov/openapi.json)
- [Portal](https://www.weather.gov)
- [Contact](https://www.weather.gov/contact)
- [Glossary](https://api.weather.gov/glossary)

## Features

| Name | Description |
|------|-------------|
| Free and Open | No API key required (only a User-Agent header); completely free for any use. |
| Forecast Gridpoints | 12-hour and hourly forecasts for 2.5km grid cells across the US. |
| Real-Time Alerts | Live weather alerts and warnings including active counts by area, zone, and region. |
| Observation Data | Latest and historical observations from thousands of weather stations across the US. |
| Radar Data | Radar station metadata, alarms, queues, and wind profiler data. |
| Aviation Weather | SIGMETs, AIRMETs, Center Weather Advisories, and Terminal Aerodrome Forecasts for pilots. |
| GeoJSON Responses | All responses return GeoJSON or JSON-LD by default, suitable for mapping and linked data. |
| Multiple Output Formats | Supports GeoJSON, JSON-LD, DWML, OXML, CAP, and ATOM formats. |

## Use Cases

| Name | Description |
|------|-------------|
| Emergency Management | Monitor active weather alerts and warnings for emergency response and public safety decisions. |
| Application Development | Integrate NWS weather data into mobile apps, websites, and IoT devices. |
| Aviation Planning | Access SIGMETs, AIRMETs, and TAFs for flight planning and aviation safety. |
| Agricultural Monitoring | Use zone forecasts and observation data for crop management and agricultural planning. |
| Research and Education | Access historical observation data and forecast products for climate research and educational purposes. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Weather.gov OpenAPI v3.8.1](openapi/openapi.yml)

### JSON Schema

107 JSON Schema files extracted from the OpenAPI specification covering all resource types including alerts, forecasts, observations, zones, and radar data.

### JSON Structure

107 JSON Structure files (json-structure.org) converted from JSON Schema.

### JSON-LD

- [Weather.gov JSON-LD Context](json-ld/weather-gov-context.jsonld) — 38 type declarations and 189 property mappings

### Examples

107 example JSON files generated from schemas.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Weather.gov API](capabilities/shared/weather-gov-api.yaml) — 22 operations covering alerts, forecasts, observations, stations, zones, radar, products, aviation, and offices

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Weather Monitoring](capabilities/weather-monitoring.yaml) | Weather.gov API | 17 | Emergency Manager, Developer, Weather Enthusiast, Aviation Professional |

## Vocabulary

- [Weather.gov Vocabulary](vocabulary/weather-gov-vocabulary.yml) — Unified taxonomy mapping 10 resources, 5 actions, 1 workflow, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Weather.gov Spectral Rules](rules/weather-gov-spectral-rules.yml) — 23 rules across 9 categories enforcing Weather.gov API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
