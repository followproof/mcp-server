# Influencer audience check by Followproof

Influencer audit and influencer vetting in your AI assistant: check audience quality and engagement rate for
Instagram, TikTok and YouTube creators, compare finalists and find new creators by niche, for creator due
diligence before an influencer marketing spend.

`followproof-mcp` is the desktop (stdio) connector for the [Followproof](https://followproof.com) MCP server. It bridges to the
remote server `https://followproof.com/mcp` with [`mcp-remote`](https://www.npmjs.com/package/mcp-remote);
your browser opens once to sign in and approve access.

Clients that support remote servers can use `https://followproof.com/mcp` directly instead.

```json
{ "mcpServers": { "followproof": { "command": "npx", "args": ["-y", "followproof-mcp"] } } }
```

Tools: check a creator's audience quality, open full reports, compare creators, search by niche, and manage
saved lists, on your Followproof plan's allowance. Docs: https://followproof.com/developers/
