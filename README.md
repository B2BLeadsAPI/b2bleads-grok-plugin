# B2BLeads Grok Build Plugin

Search and enrich B2B business contacts (name, address, phone, website, email) by industry, location, and company size — directly from Grok Build.

## Install

```
/marketplace
```

Search for `b2bleads` and press `i` to install, or add this repo directly via the xAI plugin marketplace.

## Tools

- `search_leads` — find business leads by industry, location, and company size
- `list_industries` — list supported industry values
- `find_email` — look up a best-effort contact email for a single business website (Business/Premium plan required)

## Authentication

The B2BLeads MCP server uses OAuth 2.1 (PKCE). On first use, Grok Build will prompt you to sign in with your B2BLeadsAPI account. Get an account at [b2bleadsapi.com](https://b2bleadsapi.com).

## Links

- [B2BLeadsAPI](https://b2bleadsapi.com)
- [MCP server source](https://github.com/gtovtya/b2bleads-mcp)
