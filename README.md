# Soul Change — Claude Desktop Extension

Give your AI a soul. Browse 80+ AI personas and apply them to Claude with one click.

## Install

Download the latest `.mcpb` file from [Releases](https://github.com/clawsouls/soul-change-claude/releases) and double-click to install in Claude Desktop.

## Tools

| Tool | Description |
|------|-------------|
| `search_souls` | Search AI personas by keyword, category, or tag |
| `get_soul` | Get detailed info about a specific persona |
| `apply_persona` | Apply a persona to the current conversation |
| `preview_soul` | Preview a persona's CLAUDE.md before applying |
| `install_soul` | Download and save as CLAUDE.md |
| `list_categories` | List all persona categories |

## How It Works

1. Ask Claude to search for a persona (e.g., "find me a coder persona")
2. Browse results and pick one
3. Apply it — Claude's behavior changes immediately

Personas are sourced from [ClawSouls](https://clawsouls.ai), the open-spec AI persona registry.

## Build from Source

```bash
cd server && npm install && npx tsc
cd .. && mcpb pack
```

## Links

- [ClawSouls](https://clawsouls.ai) — Browse personas
- [Soul Spec](https://clawsouls.ai/en/spec) — Open persona specification
- [soul-spec-mcp](https://github.com/clawsouls/soul-spec-mcp) — Standalone MCP server

## License

MIT
