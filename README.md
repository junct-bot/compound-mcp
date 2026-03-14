# Compound MCP Server

MCP server for Compound. Agent-ready API for Compound.

Hosted at [compound.mcp.junct.dev/mcp](https://compound.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for the crypto stack.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "compound": {
      "url": "https://compound.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Compound API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints, no phantom tools.

- **Protocol:** Compound
- **Endpoint:** `https://compound.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [compound.mcp.junct.dev/llms.txt](https://compound.mcp.junct.dev/llms.txt)
- **Server card:** [compound.mcp.junct.dev/.well-known/mcp/server.json](https://compound.mcp.junct.dev/.well-known/mcp/server.json)

## Links

- [Junct Dashboard](https://junct.dev/servers/compound)
- [llms.txt](https://compound.mcp.junct.dev/llms.txt)
- [agents.md](https://compound.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://compound.mcp.junct.dev/openapi.json)

## Keywords

Compound, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol, hosted MCP
