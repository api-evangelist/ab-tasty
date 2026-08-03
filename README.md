# AB Tasty (ab-tasty)

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
