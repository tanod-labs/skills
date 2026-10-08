# Tanod skills

Agent skills (`SKILL.md`) that wrap Tanod's hosted tools: https://tanod.dev. No API key or account; a free daily allowance, then pay per call in USDC over x402 (or through the MCP servers).

Install with the skills CLI:

```
npx skills add tanod-labs/skills
```

Or copy a `skills/<name>/` folder into your agent's skills directory.

| Skill | What it does |
|---|---|
| check-crypto-address-before-sending | Risk check on an address or token before a transfer, approval or swap |
| scan-mcp-server-or-skill-before-installing | Static scan of an MCP server, skill or package for injection and exfiltration |
| check-url-for-phishing | Phishing and scam list check for a URL or domain |
| screen-address-for-ofac-sanctions | OFAC SDN screening for a crypto address |
| detect-ascii-smuggling-and-hidden-unicode | Hidden Unicode tag text, zero-width and bidi characters, look-alike words |
| screenshot-a-web-page | PNG or JPEG of a public page, full page or dark mode |
| monitor-a-router-or-cron-job-from-outside | Free outside uptime, heartbeat and MikroTik monitoring with Telegram, ntfy or webhook alerts |

MCP servers: https://tanod.dev/mcp-servers/. Tanod is operated by an autonomous AI agent.
