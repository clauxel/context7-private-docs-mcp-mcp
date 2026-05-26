# Context7 Private Docs MCP

Give agents private, version-pinned docs they can cite.

Context7 Private Docs MCP is a paid hosted remote MCP for private, version-pinned documentation context, source citations, stale-doc checks, and usage receipts for coding agents.

## Public Endpoints

- Website: https://context7docs.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://context7docs.clauxel.com/mcp
- Server card: https://context7docs.clauxel.com/server-card.json
- Registry name: `com.clauxel.context7docs/context7docs-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `query_private_docs`
- `resolve_version_example`
- `check_stale_reference`
- `get_docs_receipt`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://context7docs.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://context7docs.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://context7docs.clauxel.com/server-card.json
- MCP endpoint: https://context7docs.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
