---
name: celigo-exports-crud
description: Create, view, update, list, and delete an export using the Celigo Exports API.
api: openapi/celigo-exports-api-openapi.yml
operations:
- createExport
- listExports
- getExport
- replaceExport
- deleteExport
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/celigo-exports-api-openapi.yml ; every operationId checked against the contract
---

# celigo-exports-crud

Create, view, update, list, and delete an export using the Celigo Exports API.

## Steps

1. 1. `createExport` – send required export body fields (as defined in the contract) with a Bearer Authorization header.
2. 2. `listExports` – retrieve exports using optional pagination query parameters `limit` and `after` with a Bearer Authorization header.
3. 3. `getExport` – fetch a specific export by its `_id` path parameter with a Bearer Authorization header.
4. 4. `replaceExport` – replace an existing export by its `_id` using the full export payload and a Bearer Authorization header.
5. 5. `deleteExport` – remove an export by its `_id` with a Bearer Authorization header.

## Rules

- Auth: Include an `Authorization: Bearer <token>` header for all requests.
- Pagination: Use `limit` and `after` query parameters on `listExports` to page through results.
