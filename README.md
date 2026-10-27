# Wikinews MCP plugin

Search the Wikinews archive from your AI assistant over MCP, with a skill that
teaches the assistant to search it well. A Miso product demo; content from
Wikinews under CC BY 2.5. Landing page and server details: https://wikinews.mcp.miso.ai/

One plugin directory (`plugin/`) carries the manifests for every client; two
marketplace files at the root point at it.

| File | Read by |
|---|---|
| `.claude-plugin/marketplace.json` | Claude Code |
| `.agents/plugins/marketplace.json` | Codex |
| `plugin/.claude-plugin/plugin.json`, `plugin/.mcp.json` | Claude Code |
| `plugin/.codex-plugin/plugin.json`, `plugin/mcp.codex.json` | Codex |
| `plugin/plugin.json`, `plugin/mcp_config.json` | Antigravity CLI |
| `plugin/skills/` | every client |

## Install

### Claude Code

```
/plugin marketplace add MisoAI/wikinews-mcp-plugin
/plugin install wikinews-mcp-plugin@wikinews
```

Then `/mcp`, pick `wikinews`, choose Authenticate and sign in with your email.
The same plugin is also served from https://wikinews.mcp.miso.ai/marketplace.json.

### Codex

```
codex plugin marketplace add MisoAI/wikinews-mcp-plugin
codex plugin add wikinews-mcp-plugin@wikinews
```

Sign in when Codex asks. Start a new session before using the skill.

### Other clients

See https://wikinews.mcp.miso.ai/ for Cursor, Antigravity CLI, Claude Desktop and ChatGPT.
