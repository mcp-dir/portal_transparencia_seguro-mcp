# Instalação detalhada

Portal da Transparência: Seguro Defeso é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_portal_transparencia_seguro`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_portal_transparencia_seguro` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_portal_transparencia_seguro` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_portal_transparencia_seguro` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.portal_transparencia_seguro` (ou `servers.portal_transparencia_seguro` no VS Code) do config do cliente e reinicie.
