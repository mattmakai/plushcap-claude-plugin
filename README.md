# Plushcap for Claude

Research developer and AI trends and compare competitor content with Plushcap.
This plugin combines the hosted Plushcap MCP connection with a research skill
for company discovery, competitive analysis, leaderboards, and developer trends.
Its read-only tools query indexed engineering blog posts, YouTube videos, X
posts, LinkedIn activity, Hacker News attention, and historical trend metrics.
Coverage can be incomplete or delayed; check source dates and metric calculation
timestamps when interpreting results.

## Install and connect

Upload this plugin's ZIP in Claude's **Customize > Plugins** area using the
personal plugin upload option. Enable the plugin, then connect its Plushcap
connector when prompted. Sign in to Plushcap in the browser, review the access
request and return hostname, and authorize the connection. A Plushcap account is
required; available data, history, and usage limits depend on your plan. Claude
manages OAuth tokens and refresh automatically. No API key or client secret is
included in this bundle or required in its configuration.

For a local Claude Code test, start a session with:

```bash
claude --plugin-dir /path/to/plushcap
```

Use `/mcp` to authenticate the plugin's Plushcap server through the browser.
The server configuration uses HTTP at `https://mcp.plushcap.com/mcp`.

## Try it

- "Use Plushcap to get Cloudflare's company profile and recent engineering posts."
- "Use Plushcap to compare Cloudflare and Vercel's content activity over the last three months."
- "Use Plushcap to research AI agent trends. Show the periods and calculation dates behind the metrics."

The research skill is available as `/plushcap:plushcap-consumer` in Claude Code
and can also be selected automatically for relevant research requests.

## License and support

The configuration, skill, and documentation are licensed under the
[MIT License](LICENSE). The Plushcap icon and trademarks are excluded; see
[the asset notice](assets/NOTICE). This package license does not grant rights to
Plushcap's service or retrieved data, which remain subject to
[Plushcap's terms](https://www.plushcap.com/terms-of-service) and applicable
third-party rights.

- [Setup documentation](https://www.plushcap.com/docs/mcp)
- [Support](https://www.plushcap.com/support)
- [Privacy policy](https://www.plushcap.com/privacy-policy)
