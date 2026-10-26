# Celigo (celigo)

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
