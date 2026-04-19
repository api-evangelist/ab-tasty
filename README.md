# AB Tasty (ab-tasty)
At AB Tasty, we are your partner for pushing great ideas even further through optimization. We achieve this by empowering brands to build better experiences using personalization, experimentation, recommendations, merchandising, and the market's only emotions-based segmentation solution.

**URL:** [https://www.abtasty.com/](https://www.abtasty.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ab-tasty-api-evangelist&utm_content=repo)

## Tags:

 - Aggregation, Experimentation, Feature Flags, Personalization, A/B Testing

## Timestamps

- **Created:** 2025-06-05
- **Modified:** 2026-04-19

## APIs

### AB Tasty Decision API
The AB Tasty Decision API is a server-side service that evaluates a visitors context against your active experiments, personalizations, and feature flags, then returns a deterministic decision: which campaigns the user qualifies for, the selected variation, and any variables or content to render.

**Human URL:** [https://docs.abtasty.com/server-side/decision-api/decision-api](https://docs.abtasty.com/server-side/decision-api/decision-api)

#### Tags:

 - Decision, Experimentation, Feature Flags, Server Side

#### Properties

- [Documentation](https://docs.abtasty.com/server-side/decision-api/decision-api)
- [OpenAPI](openapi/decision-api-openapi.yml)
- [JSONSchema - Campaign Request](json-schema/decision-api-campaign-request-schema.json)
- [JSONSchema - Campaign](json-schema/decision-api-campaign-schema.json)
- [JSONSchema - Flag](json-schema/decision-api-flag-schema.json)
- [JSONSchema - Flags Response](json-schema/decision-api-flags-response-schema.json)
- [JSONSchema - Activation Request](json-schema/decision-api-activation-request-schema.json)
- [JSONSchema - Flag Metadata](json-schema/decision-api-flag-metadata-schema.json)
- [JSONSchema - Campaign Response Normal](json-schema/decision-api-campaign-response-normal-schema.json)
- [JSONSchema - Campaign Response Simple](json-schema/decision-api-campaign-response-simple-schema.json)
- [JSONSchema - Campaign Response Full](json-schema/decision-api-campaign-response-full-schema.json)
- [JSONSchema - Batch Activation Request](json-schema/decision-api-batch-activation-request-schema.json)
- [JSONSchema - Batch Activation Item](json-schema/decision-api-batch-activation-item-schema.json)
- [JSONSchema - Campaign Variation](json-schema/decision-api-campaign-variation-schema.json)
- [JSONSchema - Single Campaign Request](json-schema/decision-api-single-campaign-request-schema.json)
- [SDK - TypeScript SDK](https://github.com/flagship-io/flagship-ts-sdk)
- [SDK - React SDK](https://github.com/flagship-io/flagship-react-sdk)
- [SDK - React Native SDK](https://github.com/flagship-io/flagship-react-native-sdk)
- [SDK - Flutter SDK](https://github.com/flagship-io/flagship-flutter-sdk)
- [SDK - PHP SDK](https://github.com/flagship-io/flagship-php-sdk)
- [SDK - .NET SDK](https://github.com/flagship-io/flagship-dotnet-sdk)
- [SDK - Android SDK](https://github.com/flagship-io/flagship-android)
- [SDK - iOS SDK](https://github.com/flagship-io/flagship-ios)
- [SDK - Python SDK](https://github.com/flagship-io/flagship-python-sdk)
- [SDK - Java SDK](https://github.com/flagship-io/flagship-java)
- [SDK - Go SDK](https://github.com/flagship-io/flagship-go-sdk)
- [CodeExamples - Code Samples](https://github.com/flagship-io/code-samples)

### AB Tasty Remote Control API
AB Tastys Remote Control API is a developer and QA tool that lets you programmatically drive the AB Tasty SDK from outside your app or page, so you can precisely control and observe experiments without changing production targeting.

**Human URL:** [https://docs.abtasty.com/server-side/remote-control-api](https://docs.abtasty.com/server-side/remote-control-api)

#### Tags:

 - Remote Control, Campaigns, Experimentation

#### Properties

- [Documentation](https://docs.abtasty.com/server-side/remote-control-api)

### AB Tasty Public API
The AB Tasty Public API provides programmatic access to manage campaigns, monitor and control experiments, manage account users, and integrate AB Tasty with third-party tools.

**Human URL:** [https://docs.abtasty.com/integrations/custom-integrations/ab-tasty-public-api](https://docs.abtasty.com/integrations/custom-integrations/ab-tasty-public-api)

#### Tags:

 - Campaigns, Integrations, Management

#### Properties

- [Documentation](https://docs.abtasty.com/integrations/custom-integrations/ab-tasty-public-api)

## Common Properties

- [Website](https://www.abtasty.com/)
- [Portal](https://developers.abtasty.com/)
- [Documentation](https://docs.abtasty.com/)
- [Pricing](https://www.abtasty.com/pricing/)
- [Support](https://support.abtasty.com/hc/en-us)
- [Legal](https://www.abtasty.com/legal-notices/)
- [PrivacyPolicy](https://www.abtasty.com/privacy-policy/)
- [GitHubOrganization](https://github.com/flagship-io)
- [CLI](https://github.com/flagship-io/abtasty-cli)
- [Tools - MCP Server](https://github.com/flagship-io/mcp-server)
- [SpectralRules](rules/ab-tasty-spectral-rules.yml)
- [Vocabulary](vocabulary/ab-tasty-vocabulary.yaml)
- [NaftikoCapability](capabilities/feature-experimentation.yaml)
- [JSONLD](json-ld/ab-tasty-decision-api-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| A/B Testing | Advanced A/B testing with conversion safety mechanisms and unlimited variations |
| Feature Flags | Server-side feature flags with targeting and gradual rollouts |
| Personalization | Experience customization based on emotional needs and engagement segmentation |
| E-Merchandising | Unified search, recommendations, and product visibility control |
| Progressive Rollouts | Progressive feature release with automatic KPI-triggered rollbacks |
| AI Visual Editor | AI-powered prompt-based visual modifications for experiments |
| AdaptiveCX | Real-time predictive AI for anonymous visitor personalization targeting 90% of visitors |
| Multivariate Testing | Test multiple variables simultaneously across web and mobile |

## Use Cases

| Name | Description |
|------|-------------|
| Web Experimentation | Run A/B tests and multivariate experiments on websites to optimize conversion rates |
| Feature Experimentation | Multi-channel feature testing across devices via API or SDK implementation |
| Server-Side Testing | Backend and edge worker experiments using the Decision API |
| E-commerce Optimization | Merchandising, recommendations, and personalized product experiences |
| Progressive Deployment | Gradual feature rollouts with automated rollback based on KPI monitoring |
| Anonymous Personalization | AI-driven real-time personalization for anonymous visitors |

## Integrations

| Name | Description |
|------|-------------|
| Google Cloud | Partnership with Google Cloud for infrastructure and analytics integration |
| Analytics Tools | Connect with analytics platforms via the integration hub for data sharing |
| CDPs | Customer Data Platform integrations for enhanced visitor profiling |
| OpenFeature | OpenFeature provider integration for standardized feature flag management |
| Vercel | Edge function integration with Vercel for server-side experimentation |
| Cloudflare | Cloudflare Worker integration for edge-based feature experimentation |
| AWS Lambda | AWS Lambda integration for serverless feature experimentation |
| Fastly | Fastly worker integration for CDN-level feature experimentation |
| Akamai | Akamai worker integration for CDN-level feature experimentation |
| Shopify Hydrogen | Shopify Hydrogen framework integration for headless commerce experimentation |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AB Tasty Decision API](openapi/decision-api-openapi.yml)

### JSON Schema

- [decision-api-campaign-request-schema.json](json-schema/decision-api-campaign-request-schema.json)
- [decision-api-single-campaign-request-schema.json](json-schema/decision-api-single-campaign-request-schema.json)
- [decision-api-campaign-schema.json](json-schema/decision-api-campaign-schema.json)
- [decision-api-campaign-response-normal-schema.json](json-schema/decision-api-campaign-response-normal-schema.json)
- [decision-api-campaign-variation-schema.json](json-schema/decision-api-campaign-variation-schema.json)
- [decision-api-campaign-response-simple-schema.json](json-schema/decision-api-campaign-response-simple-schema.json)
- [decision-api-campaign-response-full-schema.json](json-schema/decision-api-campaign-response-full-schema.json)
- [decision-api-flag-metadata-schema.json](json-schema/decision-api-flag-metadata-schema.json)
- [decision-api-flag-schema.json](json-schema/decision-api-flag-schema.json)
- [decision-api-flags-response-schema.json](json-schema/decision-api-flags-response-schema.json)
- [decision-api-activation-request-schema.json](json-schema/decision-api-activation-request-schema.json)
- [decision-api-batch-activation-item-schema.json](json-schema/decision-api-batch-activation-item-schema.json)
- [decision-api-batch-activation-request-schema.json](json-schema/decision-api-batch-activation-request-schema.json)

### JSON Structure

- [decision-api-campaign-request-structure.json](json-structure/decision-api-campaign-request-structure.json)
- [decision-api-single-campaign-request-structure.json](json-structure/decision-api-single-campaign-request-structure.json)
- [decision-api-campaign-structure.json](json-structure/decision-api-campaign-structure.json)
- [decision-api-campaign-response-normal-structure.json](json-structure/decision-api-campaign-response-normal-structure.json)
- [decision-api-campaign-variation-structure.json](json-structure/decision-api-campaign-variation-structure.json)
- [decision-api-campaign-response-simple-structure.json](json-structure/decision-api-campaign-response-simple-structure.json)
- [decision-api-campaign-response-full-structure.json](json-structure/decision-api-campaign-response-full-structure.json)
- [decision-api-flag-metadata-structure.json](json-structure/decision-api-flag-metadata-structure.json)
- [decision-api-flag-structure.json](json-structure/decision-api-flag-structure.json)
- [decision-api-flags-response-structure.json](json-structure/decision-api-flags-response-structure.json)
- [decision-api-activation-request-structure.json](json-structure/decision-api-activation-request-structure.json)
- [decision-api-batch-activation-item-structure.json](json-structure/decision-api-batch-activation-item-structure.json)
- [decision-api-batch-activation-request-structure.json](json-structure/decision-api-batch-activation-request-structure.json)

### JSON-LD

- [ab-tasty-decision-api-context.jsonld](json-ld/ab-tasty-decision-api-context.jsonld)

### Examples

- [decision-api-campaign-request-example.json](examples/decision-api-campaign-request-example.json)
- [decision-api-campaign-example.json](examples/decision-api-campaign-example.json)
- [decision-api-flag-example.json](examples/decision-api-flag-example.json)
- [decision-api-activation-request-example.json](examples/decision-api-activation-request-example.json)
- [decision-api-flags-response-example.json](examples/decision-api-flags-response-example.json)
- [decision-api-campaign-variation-example.json](examples/decision-api-campaign-variation-example.json)
- [decision-api-campaign-response-normal-example.json](examples/decision-api-campaign-response-normal-example.json)
- [decision-api-flag-metadata-example.json](examples/decision-api-flag-metadata-example.json)
- [decision-api-campaign-response-simple-example.json](examples/decision-api-campaign-response-simple-example.json)
- [decision-api-campaign-response-full-example.json](examples/decision-api-campaign-response-full-example.json)
- [decision-api-batch-activation-item-example.json](examples/decision-api-batch-activation-item-example.json)
- [decision-api-batch-activation-request-example.json](examples/decision-api-batch-activation-request-example.json)
- [decision-api-single-campaign-request-example.json](examples/decision-api-single-campaign-request-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Decision API](capabilities/shared/decision-api.yaml) — 4 operations for visitor campaign and feature flag evaluation

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Feature Experimentation](capabilities/feature-experimentation.yaml) | Decision API | 4 | Developer, Product Manager |

## Vocabulary

- [AB Tasty Vocabulary](vocabulary/ab-tasty-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 10 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [AB Tasty Spectral Rules](rules/ab-tasty-spectral-rules.yml) — 40 rules across 13 categories enforcing AB Tasty API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
