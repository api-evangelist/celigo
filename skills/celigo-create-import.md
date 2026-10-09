---
name: celigo-create-import
description: Create a new import and retrieve its details.
api: openapi/celigo-imports-api-openapi.yml
operations:
- createImport
- getImport
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/celigo-imports-api-openapi.yml ; every operationId checked against the contract
---

# celigo-create-import

Create a new import and retrieve its details.

## Steps

1. 1. Call `createImport` with the required request body for the import.
2. 2. Call `getImport` using the `_id` returned from `createImport` to fetch the import details.

## Rules

- Auth: Include a Bearer token in the `Authorization` header (bearerAuth).
- Pagination: Use `limit` and `after` query parameters where applicable.
