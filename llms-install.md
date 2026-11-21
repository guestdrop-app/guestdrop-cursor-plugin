# Installing GuestDrop MCP

GuestDrop is a remote MCP server. There is nothing to clone, build or install.

1. Add this server to the MCP settings file:

```json
{
  "mcpServers": {
    "guestdrop": {
      "type": "streamableHttp",
      "url": "https://guestdrop.app/api/mcp"
    }
  }
}
```

2. On first use the server answers 401 with an OAuth challenge. Open the sign-in link it gives and sign in with Google at guestdrop.app. No API key or environment variable is needed.

3. Check it works by asking: "List my GuestDrop events."

Tools: create and update events, get QR and share links, list and moderate guest photos, export links, backup status, retention purchase options.

Docs: https://guestdrop.app/mcp · Support: support@guestdrop.app
