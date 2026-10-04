---
name: celigo-create-and-test-connection
description: Create a new connection, verify it by pinging, and retrieve its details.
api: openapi/celigo-connections-api-openapi.yml
operations:
- createConnection
- pingConnection
- getConnection
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/celigo-connections-api-openapi.yml ; every operationId checked against the contract
---

# celigo-create-and-test-connection

Create a new connection, verify it by pinging, and retrieve its details.

## Steps

1. 1. Use `createConnection` with the request body fields required to define the connection and include the `Authorization: Bearer <token>` header.
2. 2. Use `pingConnection` with the `_id` returned from step 1 in the path and include the `Authorization: Bearer <token>` header to test the connection.
3. 3. Use `getConnection` with the same `_id` to fetch the connection details, again providing the `Authorization: Bearer <token>` header.

## Rules

- Authentication: All requests must include a Bearer token in the `Authorization` header (bearerAuth).
- Pagination: When listing connections (`listConnections`), use the `limit` and `after` query parameters.
- Idempotency: `createConnection` is not idempotent; repeat calls may create duplicate connections.
- Error handling: On rate‑limit exhaustion the API returns no specific HTTP status code.
