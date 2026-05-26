# Context7 Private Docs MCP

Context7 Private Docs MCP is a hosted remote MCP for Context7 MCP docs.

This repository is a public documentation project for Context7 Private Docs MCP. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://context7docs.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=context7docs_public_docs&utm_content=readme_home
- Pricing: https://context7docs.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=context7docs_public_docs&utm_content=readme_pricing
- Checkout: https://context7docs.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=context7docs_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://context7docs.clauxel.com/mcp
- Server card: https://context7docs.clauxel.com/server-card.json
- Registry name: `com.clauxel.context7docs/context7docs-mcp`
- Tools: `query_private_docs`, `resolve_version_example`, `check_stale_reference`, `get_docs_receipt`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: query_private_docs
- MCP tool: resolve_version_example
- MCP tool: check_stale_reference
- MCP tool: get_docs_receipt

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
