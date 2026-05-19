# formbot-mcp

Online form creation and management for AI agents u2014 build Typeform-style surveys, collect responses with pagination, update forms with logic jumps, track completion analytics, and generate shareable links. Self-contained SQLite storage, zero external API dependencies.

## Quick Start

```bash
git clone https://github.com/marilynceo/formbot-mcp.git
cd formbot-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://formbot.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/formbot-mcp

# Or connect directly via MCP client
# Endpoint: https://formbot.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
