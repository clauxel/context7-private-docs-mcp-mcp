# Quickstart

Context7 Private Docs MCP is a hosted remote MCP for Context7 MCP docs.

## Fast Path

1. Open Context7 Private Docs MCP and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://context7docs.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call query_private_docs with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://context7docs.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=context7docs_public_docs&utm_content=quickstart_home
- https://context7docs.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=context7docs_public_docs&utm_content=quickstart_pricing
- https://context7docs.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=context7docs_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://context7docs.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
