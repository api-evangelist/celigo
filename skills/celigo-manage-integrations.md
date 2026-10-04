---
name: celigo-manage-integrations
description: Create a new integration, retrieve its details, and optionally list integrations with pagination.
api: openapi/celigo-integrations-api-openapi.yml
operations:
- createIntegration
- getIntegration
- listIntegrations
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/celigo-integrations-api-openapi.yml ; every operationId checked against the contract
---

# celigo-manage-integrations

Create a new integration, retrieve its details, and optionally list integrations with pagination.

## Steps

1. 1. Call `createIntegration` with the required request body fields for the new integration.
2. 2. Call `getIntegration` using the `_id` returned from `createIntegration` to fetch the integration details.
3. 3. Call `listIntegrations` with optional query parameters `limit` and `after` to paginate through integrations.

## Rules

- Auth: Include a Bearer token in the `Authorization` header (scheme: bearerAuth).
- Pagination: Use `limit` to set page size and `after` as the cursor for the next page when calling `listIntegrations`.
