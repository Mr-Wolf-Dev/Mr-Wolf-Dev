# Mr. Wolf (`mr.wolf` on Apify)

**HTTP-only (256 MB RAM, zero headless browsers)** Apify Actors & **Streamable HTTP Standby MCP Servers** for AI Agents, B2B Lead Generation, Public Procurement, and Financial Intelligence.

---

## Live Actors & Standby MCP Servers

| Actor | Apify Store | Glama Score | Standby MCP Endpoint |
| --- | --- | --- | --- |
| **EU Public Tenders & Grants (TED Europa)** | [apify.com/mr.wolf/eu-tenders-mcp-server](https://apify.com/mr.wolf/eu-tenders-mcp-server) | [![Glama](https://glama.ai/mcp/servers/Mr-Wolf-Dev/eu-tenders-mcp-server/badges/score.svg)](https://glama.ai/mcp/servers/Mr-Wolf-Dev/eu-tenders-mcp-server) | `https://mr-wolf-1--eu-tenders-mcp-server.apify.actor/mcp` |
| **SAM.gov US Federal Contracts (Keyless)** | [apify.com/mr.wolf/us-sam-tenders-mcp-server](https://apify.com/mr.wolf/us-sam-tenders-mcp-server) | [![Glama](https://glama.ai/mcp/servers/Mr-Wolf-Dev/us-sam-tenders-mcp-server/badges/score.svg)](https://glama.ai/mcp/servers/Mr-Wolf-Dev/us-sam-tenders-mcp-server) | `https://mr-wolf-1--us-sam-tenders-mcp-server.apify.actor/mcp` |
| **Tech & Startup Jobs (4 ATS JSON APIs)** | [apify.com/mr.wolf/ats-jobs-mcp-server](https://apify.com/mr.wolf/ats-jobs-mcp-server) | [![Glama](https://glama.ai/mcp/servers/Mr-Wolf-Dev/ats-jobs-mcp-server/badges/score.svg)](https://glama.ai/mcp/servers/Mr-Wolf-Dev/ats-jobs-mcp-server) | `https://mr-wolf-1--ats-jobs-mcp-server.apify.actor/mcp` |
| **B2B Domain Intelligence & Email Verifier** | [apify.com/mr.wolf/domain-intel-mcp-server](https://apify.com/mr.wolf/domain-intel-mcp-server) | [![Glama](https://glama.ai/mcp/servers/Mr-Wolf-Dev/domain-intel-mcp-server/badges/score.svg)](https://glama.ai/mcp/servers/Mr-Wolf-Dev/domain-intel-mcp-server) | `https://mr-wolf-1--domain-intel-mcp-server.apify.actor/mcp` |
| **SEC EDGAR Filings & XBRL Financials** | [apify.com/mr.wolf/sec-edgar-mcp-server](https://apify.com/mr.wolf/sec-edgar-mcp-server) | [![Glama](https://glama.ai/mcp/servers/Mr-Wolf-Dev/sec-edgar-mcp-server/badges/score.svg)](https://glama.ai/mcp/servers/Mr-Wolf-Dev/sec-edgar-mcp-server) | `https://mr-wolf-1--sec-edgar-mcp-server.apify.actor/mcp` |

---

## Quick MCP Setup (Cursor / Claude Desktop)

```json
{
  "mcpServers": {
    "ats-jobs": {
      "url": "https://mr-wolf-1--ats-jobs-mcp-server.apify.actor/mcp",
      "headers": { "Authorization": "Bearer YOUR_APIFY_TOKEN" }
    },
    "domain-intel": {
      "url": "https://mr-wolf-1--domain-intel-mcp-server.apify.actor/mcp",
      "headers": { "Authorization": "Bearer YOUR_APIFY_TOKEN" }
    }
  }
}
```
