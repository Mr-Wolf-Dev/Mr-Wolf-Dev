# Mr. Wolf (`mr.wolf` on Apify)

**HTTP-only (256 MB RAM, zero headless browsers)** Apify Actors & **Streamable HTTP Standby MCP Servers** for AI Agents, B2B Lead Generation, E-Commerce, KYB Compliance, Pharma Regulatory, Public Procurement, and Financial Intelligence.

---

## Live Actors & Standby MCP Servers

| Actor | Apify Store | Glama Score | Standby MCP Endpoint |
| --- | --- | --- | --- |
| **EU Public Tenders & Grants (TED Europa)** | [apify.com/mr.wolf/eu-tenders-mcp-server](https://apify.com/mr.wolf/eu-tenders-mcp-server) | [![Glama](https://glama.ai/mcp/servers/Mr-Wolf-Dev/eu-tenders-mcp-server/badges/score.svg)](https://glama.ai/mcp/servers/Mr-Wolf-Dev/eu-tenders-mcp-server) | `https://mr-wolf-1--eu-tenders-mcp-server.apify.actor/mcp` |
| **SAM.gov US Federal Contracts (Keyless)** | [apify.com/mr.wolf/us-sam-tenders-mcp-server](https://apify.com/mr.wolf/us-sam-tenders-mcp-server) | [![Glama](https://glama.ai/mcp/servers/Mr-Wolf-Dev/us-sam-tenders-mcp-server/badges/score.svg)](https://glama.ai/mcp/servers/Mr-Wolf-Dev/us-sam-tenders-mcp-server) | `https://mr-wolf-1--us-sam-tenders-mcp-server.apify.actor/mcp` |
| **Tech & Startup Jobs (4 ATS JSON APIs)** | [apify.com/mr.wolf/ats-jobs-mcp-server](https://apify.com/mr.wolf/ats-jobs-mcp-server) | [![Glama](https://glama.ai/mcp/servers/Mr-Wolf-Dev/ats-jobs-mcp-server/badges/score.svg)](https://glama.ai/mcp/servers/Mr-Wolf-Dev/ats-jobs-mcp-server) | `https://mr-wolf-1--ats-jobs-mcp-server.apify.actor/mcp` |
| **B2B Domain Intelligence & Email Verifier** | [apify.com/mr.wolf/domain-intel-mcp-server](https://apify.com/mr.wolf/domain-intel-mcp-server) | [![Glama](https://glama.ai/mcp/servers/Mr-Wolf-Dev/domain-intel-mcp-server/badges/score.svg)](https://glama.ai/mcp/servers/Mr-Wolf-Dev/domain-intel-mcp-server) | `https://mr-wolf-1--domain-intel-mcp-server.apify.actor/mcp` |
| **SEC EDGAR Filings & XBRL Financials** | [apify.com/mr.wolf/sec-edgar-mcp-server](https://apify.com/mr.wolf/sec-edgar-mcp-server) | [![Glama](https://glama.ai/mcp/servers/Mr-Wolf-Dev/sec-edgar-mcp-server/badges/score.svg)](https://glama.ai/mcp/servers/Mr-Wolf-Dev/sec-edgar-mcp-server) | `https://mr-wolf-1--sec-edgar-mcp-server.apify.actor/mcp` |
| **Shopify Store Intelligence, Apps & Catalog** | [apify.com/mr.wolf/shopify-store-intel-mcp-server](https://apify.com/mr.wolf/shopify-store-intel-mcp-server) | [Repo](https://github.com/Mr-Wolf-Dev/shopify-store-intel-mcp-server) | `https://mr-wolf-1--shopify-store-intel-mcp-server.apify.actor/mcp` |
| **Global KYB Entity, LEI & EU VAT Registry** | [apify.com/mr.wolf/global-kyb-entity-mcp-server](https://apify.com/mr.wolf/global-kyb-entity-mcp-server) | [Repo](https://github.com/Mr-Wolf-Dev/global-kyb-entity-mcp-server) | `https://mr-wolf-1--global-kyb-entity-mcp-server.apify.actor/mcp` |
| **FDA Recalls, 510(k) & Clinical Trials Intel** | [apify.com/mr.wolf/pharma-regulatory-mcp-server](https://apify.com/mr.wolf/pharma-regulatory-mcp-server) | [Repo](https://github.com/Mr-Wolf-Dev/pharma-regulatory-mcp-server) | `https://mr-wolf-1--pharma-regulatory-mcp-server.apify.actor/mcp` |

---

## Quick MCP Setup (Cursor / Claude Desktop)

```json
{
  "mcpServers": {
    "shopify-store-intel": {
      "url": "https://mr-wolf-1--shopify-store-intel-mcp-server.apify.actor/mcp",
      "headers": { "Authorization": "Bearer YOUR_APIFY_TOKEN" }
    },
    "global-kyb-entity": {
      "url": "https://mr-wolf-1--global-kyb-entity-mcp-server.apify.actor/mcp",
      "headers": { "Authorization": "Bearer YOUR_APIFY_TOKEN" }
    }
  }
}
```
