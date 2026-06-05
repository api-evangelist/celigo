# Celigo (celigo)

Celigo is an intelligent automation platform (iPaaS) that enables organizations to integrate applications, automate business processes, and connect data across their technology stack with low-code tooling. Celigo offers a REST-based integrator.io Platform API, an API Management console, OAuth 2.0 and Bearer Token authentication, and more than one thousand pre-built connectors and integration applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/celigo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/celigo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- API Management
- Automation
- Data Integration
- Integration
- iPaaS
- Workflow

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-30

## APIs

### Celigo integrator.io Platform API

The integrator.io Platform API is a RESTful JSON API secured by Bearer Tokens. It provides programmatic access to integrations, connections, flows, imports, exports, iClients, and other integrator.io resources, with rate limiting via a leaky bucket algorithm of 1000 tokens and a fill rate of 300 tokens per second.

- **Human URL:** [https://docs.celigo.com/hc/en-us/categories/360001519091-Platform-API](https://docs.celigo.com/hc/en-us/categories/360001519091-Platform-API)

#### Tags

- Integration
- iPaaS
- REST
- Platform

#### Properties

- [Documentation](https://docs.celigo.com/hc/en-us/categories/360001519091-Platform-API)
- [Reference](https://github.com/celigo/integrator-api-docs)
- [Getting Started](https://docs.celigo.com/hc/en-us/articles/360042281231-Getting-started-with-standard-REST-API)
- [Connection](https://docs.celigo.com/hc/en-us/articles/360038520652-Set-up-a-connection-to-Celigo-integrator-io)
- [Postman Collection](collections/celigo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/celigo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Celigo OAuth Authentication

Celigo supports OAuth 2.0 and OAuth 1.0 authentication for HTTP connections, configured through iClient resources for reusable OAuth client credentials across integrations.

- **Human URL:** [https://docs.celigo.com/hc/en-us/articles/360039586072-Set-up-an-OAuth-2-0-HTTP-connection](https://docs.celigo.com/hc/en-us/articles/360039586072-Set-up-an-OAuth-2-0-HTTP-connection)

#### Tags

- Authentication
- OAuth 2.0
- OAuth 1.0
- Security

#### Properties

- [Documentation](https://docs.celigo.com/hc/en-us/articles/360039586072-Set-up-an-OAuth-2-0-HTTP-connection)
- [O Auth1](https://docs.celigo.com/hc/en-us/articles/10552671272219-Set-up-an-OAuth-1-0-HTTP-connection)
- [i Client](https://docs.celigo.com/hc/en-us/articles/11933835192859-Create-an-OAuth-2-0-iClient-resource)
- [Postman Collection](collections/celigo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/celigo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Celigo API Management

Celigo API Management allows organizations to build, publish, and govern APIs on top of Celigo-managed integrations and third-party systems with a dedicated API Management console.

- **Human URL:** [https://docs.celigo.com/hc/en-us/articles/21179125401755-The-API-Management-console-Features-and-concepts](https://docs.celigo.com/hc/en-us/articles/21179125401755-The-API-Management-console-Features-and-concepts)

#### Tags

- API Gateway
- API Management
- Publishing

#### Properties

- [Documentation](https://docs.celigo.com/hc/en-us/articles/21179125401755-The-API-Management-console-Features-and-concepts)
- [Overview](https://www.celigo.com/platform/api-management/)
- [Postman Collection](collections/celigo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/celigo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Celigo integrator.io Webhook Listeners

Inbound webhook listeners exposed by integrator.io. Each listener provides an auto-generated public HTTPS URL that accepts HTTP POST or PUT requests from a source application to trigger a real-time flow, with configurable Basic, Token, or HMAC verification, and provider templates for Shopify, HubSpot, and Slack alongside a generic webhook type. Successful deliveries return HTTP 204 by default.

- **Human URL:** [https://docs.celigo.com/hc/en-us/sections/360009906491-Trigger-real-time-flows-with-webhook-events](https://docs.celigo.com/hc/en-us/sections/360009906491-Trigger-real-time-flows-with-webhook-events)

#### Tags

- Webhooks
- Events
- AsyncAPI
- Real-Time
- Integration

#### Properties

- [Documentation](https://docs.celigo.com/hc/en-us/sections/360009906491-Trigger-real-time-flows-with-webhook-events)
- [Getting Started](https://docs.celigo.com/hc/en-us/articles/360015827372-Create-webhook-listeners)
- [Reference](https://docs.celigo.com/hc/en-us/articles/14737771807643-How-to-invoke-integrator-io-externally)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/celigo/refs/heads/main/asyncapi/celigo-webhook-listeners-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/celigo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/celigo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/celigo-inc)
- [Website](https://celigo.com/)
- [Portal](https://docs.celigo.com/)
- [Documentation](https://docs.celigo.com/hc/en-us/categories/360001519091-Platform-API)
- [Reference](https://github.com/celigo/integrator-api-docs)
- [Getting Started](https://docs.celigo.com/hc/en-us/articles/360042281231-Getting-started-with-standard-REST-API)
- [Authentication](https://docs.celigo.com/hc/en-us/articles/360039586072-Set-up-an-OAuth-2-0-HTTP-connection)
- [Privacy Policy](https://celigo.com/privacy-policy/)
- [Terms of Service](https://celigo.com/terms-of-service/)
- [Integrations](https://www.celigo.com/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
