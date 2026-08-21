# Agger

### Agger for Claude, ChatGPT and AI agents

Agger, multi-quote and management platform for insurance brokers. Connect your account with your Aggilizador login e-mail and password to bring your brokerage into the assistant.

- 📊 **1 tool**
- 🔒 **Read-only**
- 💬 **Works with any MCP client**: Claude Desktop, Cursor, VS Code, Cline, Continue
- 🔑 **Magic-link login (no password)**

[Portuguese version](README.md) · [Full docs (PT-BR)](docs/)

---

## One-click install

### Claude (Web and Desktop)

[➕ Open in Claude and connect](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

Manual: [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Add custom connector** → name `Agger`, URL `https://api.mcp.ai/p_agger`.

### Cursor

[➕ Install in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=agger&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF9hZ2dlciJ9)

### VS Code (Copilot Chat)

[➕ Install in VS Code](vscode:mcp/install?name=agger&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_agger%22%7D)

### Any other MCP-over-HTTP client

```
https://api.mcp.ai/p_agger
```

---

## 1 tool

| Tool | Description |
|---|---|
| `agger_list_accounts` | Conta Agger conectada: e-mail do corretor. |

---

## Pricing

Free.

---

## License

MIT — see [LICENSE](LICENSE). The MCP server at `api.mcp.ai/p_agger` is proprietary (hosted); this repo (manifests, docs, skills) is MIT.
