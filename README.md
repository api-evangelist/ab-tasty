# AB Tasty (ab-tasty)

At AB Tasty, we are your partner for pushing great ideas even further through optimization. We achieve this by empowering brands to build better experiences using personalization, experimentation, recommendations, merchandising, and the market's only emotions-based segmentation solution.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Aggregation
- Experimentation
- Feature Flags
- Personalization
- A/B Testing

## Timestamps

- **Created:** 2025-06-05
- **Modified:** 2026-05-19

## APIs

### AB Tasty Decision API

The AB Tasty Decision API is a server-side service that evaluates a visitors context against your active experiments, personalizations, and feature flags, then returns a deterministic decision: which campaigns the user qualifies for, the selected variation, and any variables or content to render.

- **Human URL:** [https://docs.abtasty.com/server-side/decision-api/decision-api](https://docs.abtasty.com/server-side/decision-api/decision-api)

#### Tags

- Decision
- Experimentation
- Feature Flags
- Server Side

#### Properties

- [Documentation](https://docs.abtasty.com/server-side/decision-api/decision-api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/openapi/decision-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-campaign-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-campaign-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-flag-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-flags-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-activation-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-flag-metadata-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-campaign-response-normal-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-campaign-response-simple-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-campaign-response-full-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-batch-activation-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-batch-activation-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-campaign-variation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-single-campaign-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [SDK](https://github.com/flagship-io/flagship-ts-sdk)
- [SDK](https://github.com/flagship-io/flagship-react-sdk)
- [SDK](https://github.com/flagship-io/flagship-react-native-sdk)
- [SDK](https://github.com/flagship-io/flagship-flutter-sdk)
- [SDK](https://github.com/flagship-io/flagship-php-sdk)
- [SDK](https://github.com/flagship-io/flagship-dotnet-sdk)
- [SDK](https://github.com/flagship-io/flagship-android)
- [SDK](https://github.com/flagship-io/flagship-ios)
- [SDK](https://github.com/flagship-io/flagship-python-sdk)
- [SDK](https://github.com/flagship-io/flagship-java)
- [SDK](https://github.com/flagship-io/flagship-go-sdk)
- [Code Examples](https://github.com/flagship-io/code-samples)
- [Postman Collection](collections/decision-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/decision-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AB Tasty Remote Control API

AB Tastys Remote Control API is a developer and QA tool that lets you programmatically drive the AB Tasty SDK from outside your app or page, so you can precisely control and observe experiments without changing production targeting. With it, you can preview or force specific campaigns and variations for a visitor, toggle or pause experiences, set visitor/context attributes, trigger goals and custom events, refresh decisions, and clear caches to reproduce clean states.

- **Human URL:** [https://docs.abtasty.com/server-side/remote-control-api](https://docs.abtasty.com/server-side/remote-control-api)

#### Tags

- Remote Control
- Campaigns
- Experimentation

#### Properties

- [Documentation](https://docs.abtasty.com/server-side/remote-control-api)
- [Postman Collection](collections/decision-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/decision-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AB Tasty Public API

The AB Tasty Public API provides programmatic access to manage campaigns, monitor and control experiments, manage account users, and integrate AB Tasty with third-party tools. It uses OAuth-style credentials (ClientID and ClientSecret) to generate access tokens for authentication.

- **Human URL:** [https://docs.abtasty.com/integrations/custom-integrations/ab-tasty-public-api](https://docs.abtasty.com/integrations/custom-integrations/ab-tasty-public-api)

#### Tags

- Campaigns
- Integrations
- Management

#### Properties

- [Documentation](https://docs.abtasty.com/integrations/custom-integrations/ab-tasty-public-api)
- [Postman Collection](collections/decision-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/decision-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/ab-tasty)
- [Website](https://www.abtasty.com/)
- [Portal](https://developers.abtasty.com/)
- [Documentation](https://docs.abtasty.com/)
- [Pricing](https://www.abtasty.com/pricing/)
- [Support](https://support.abtasty.com/hc/en-us)
- [Legal](https://www.abtasty.com/legal-notices/)
- [Privacy Policy](https://www.abtasty.com/privacy-policy/)
- [GitHub Organization](https://github.com/flagship-io)
- [C L I](https://github.com/flagship-io/abtasty-cli)
- [Tools](https://github.com/flagship-io/mcp-server)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/rules/ab-tasty-spectral-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/vocabulary/ab-tasty-vocabulary.yaml)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-ld/ab-tasty-decision-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [L L Ms Txt](https://docs.abtasty.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
