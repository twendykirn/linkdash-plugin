# Linkdash plugin

Connects AI agents to [Linkdash](https://linkdash.dev), a URL shortener built for people and agents, through its remote MCP server at `https://api.linkdash.dev/mcp`.

Create tracked short links, share files and text as links, split traffic between pages, route visitors by country or device, and read click analytics from Cursor, ChatGPT, or any client that supports [agent plugins](https://agent-plugins.org).

[![Add to Cursor](https://cursor.com/deeplink/mcp-install-dark.svg)](https://cursor.com/install-mcp?name=linkdash&config=eyJ1cmwiOiJodHRwczovL2FwaS5saW5rZGFzaC5kZXYvbWNwIn0%3D)

## Sign in

The server uses OAuth. On first use your client opens a Linkdash sign-in and a consent screen; allow it and you're connected. Disconnect at any time under [Dashboard → API keys](https://linkdash.dev/dashboard/keys). The Free plan includes 5,000 events a month.

## Contents

- `plugin.json`: plugin manifest and directory listing
- `mcp.json`: the remote MCP server
- `assets/`: icons and logos

Docs: [linkdash.dev/docs/mcp](https://linkdash.dev/docs/mcp). Support: support@linkdash.dev.
