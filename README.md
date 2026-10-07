# Vibgrate Cloud MCP

Hosted MCP plugin for [Cursor](https://cursor.com) and other MCP clients.

- **Endpoint:** `https://mcp.vibgrate.com` (streamable HTTP)
- **Docs:** https://vibgrate.com/mcp
- **Trust:** https://vibgrate.com/trust
- **Registry id:** `com.vibgrate/mcp`

Your team's drift, vulnerability, and upgrade data, queryable from any AI assistant. **Vibgrate Cloud MCP** connects Cursor, Claude, ChatGPT, Windsurf, or VS Code to Vibgrate Cloud. The published surface is 14 read-only tools for drift scores, vulnerabilities and end-of-life runtimes, upgrade paths, and blast-radius analysis. OAuth 2.1 + PKCE with scoped, revocable tokens (`vibgrate:read`). Source code never leaves your environment — the server only exposes metadata collected by the Vibgrate CLI. Business units, environments, and applications are managed in Vibgrate Cloud, not through the assistant.

## Install in Cursor

Add via Cursor MCP settings, or use this repo's root `.mcp.json` (scanned by [cursor.directory](https://cursor.directory)).

Local companion (stdio / lockfile-matched docs + code map + drift): [vibgrate/cli](https://github.com/vibgrate/cli) → `vg serve` · https://vibgrate.com/library

## License

Apache-2.0. Product of [Vibgrate](https://vibgrate.com).