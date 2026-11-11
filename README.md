# TVFoodMaps plugin for Claude

[TVFoodMaps](https://www.tvfoodmaps.com) maps restaurants featured on food television. This plugin connects Claude to TVFoodMaps' free, read-only MCP server and adds a skill for finding TV food stops by city, show or cuisine, with the recorded episodes behind each place.

## Install

Claude Code:

```bash
claude plugin marketplace add apsquared/tvfoodmaps-plugin
claude plugin install tvfoodmaps@tvfoodmaps
```

No sign-in is needed. Prefer the server on its own? Add `https://www.tvfoodmaps.com/claude/mcp` as a custom connector. Setup guide: https://www.tvfoodmaps.com/mcp/setup#free

## What's in this repository

```
.claude-plugin/marketplace.json   Claude Code marketplace "tvfoodmaps"
plugins/tvfoodmaps/               the plugin: one skill + one remote MCP server
```

See [plugins/tvfoodmaps/README.md](plugins/tvfoodmaps/README.md) for the tools and what data they handle.

## Support

- Setup guide: https://www.tvfoodmaps.com/mcp/setup#free
- Contact: https://www.tvfoodmaps.com/contact-us
- Privacy: https://www.tvfoodmaps.com/privacy-policy
- Terms: https://www.tvfoodmaps.com/tos
