# 🔍 AMLOracle

**AML / KYC MCP Server** — 12 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-12-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/aml/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "amloracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/aml/mcp/"]
    }
  }
}
```

## Tools (12)

| Tool | Description |
|------|-------------|
| `sanctions_screen` | Screen any name against EU FSF (14k), OFAC SDN (69k), UN SC (3k), Interpol (13k) |
| `sanctions_detail` | Full entity record for sanctions hit. Returns UN XML detail, aliases, nationalit |
| `pep_check` | PEP (Politically Exposed Person) check via Wikidata. AMLR Art. 22 enhanced CDD f |
| `adverse_media` | Negative news screening: fraud, money laundering, corruption, sanctions. AMLR Ar |
| `country_risk` | Country risk assessment: FATF Blacklist, Greylist, EU High-Risk. AMLR Art. 16+18 |
| `ubo_lookup` | Ultimate Beneficial Owner (UBO) identification via GLEIF LEI ownership register. |
| `kyc_bundle` | Full KYC in one call: Sanctions + PEP + Adverse Media + Country Risk. Returns ov |
| `transaction_risk` | AML transaction risk scoring: amount, corridor, sender screening. AMLR Art. 35+8 |
| `aml_news` | AMLR / AMLA / AMLD6 regulatory news. Topics: general, amla, amlr, sanctions, cry |
| `amlr_calendar` | AMLR compliance milestones. Key: 1 July 2026 full application, €10k cash limit,  |
| `watchlist_update` | Check watchlist freshness and reload from OpenSanctions. Use force_reload=true t |
| `health_check` | AMLOracle server status, backend checks, and watchlist cache status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

AMLOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.



**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/aml/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
