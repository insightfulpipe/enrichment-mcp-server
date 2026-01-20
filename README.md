# Enrichment MCP Server

[![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-blue)](https://insightfulpipe.com/mcp-servers/enrichment)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **Enrich company and contact data with AI-powered data discovery through MCP.**

The Enrichment MCP server enables Claude, ChatGPT, Cursor, and other AI assistants to enrich business data. Get company profiles, funding data, tech stacks, and leadership information from email addresses and domains.

![Enrichment MCP Server](https://insightfulpipe.com/images/ip-logo.png)

## MCP Server URL

```
https://enrichment.insightfulmcp.com/
```

## What is Enrichment MCP?

Enrichment MCP is a **remote Model Context Protocol server** that provides AI-powered data enrichment capabilities. This data intelligence integration allows you to:

- Enrich company data from email addresses
- Get detailed company profiles and metrics
- Discover tech stacks and tools used
- Find leadership and decision-maker information
- Access funding history and company size data

## Installation

### Claude

1. Copy the MCP Server URL: `https://enrichment.insightfulmcp.com/`
2. Open [Claude Connectors Settings](https://claude.ai/settings/connectors)
3. Scroll to the bottom and click **Add custom connector**
4. Paste the URL and click **Add**
5. Click **Connect** on the connector to start authorization
6. Click **Authorize access** in the browser to complete the connection

### ChatGPT

1. Copy the MCP Server URL: `https://enrichment.insightfulmcp.com/`
2. Open ChatGPT Settings → **Connections**
3. Click **Add Connection** and paste the URL
4. Authorize with your InsightfulPipe account

### Claude Code

```bash
claude mcp add enrichment https://enrichment.insightfulmcp.com/
```

### Cursor

1. Open Cursor Settings → **MCP Servers**
2. Add new server with URL: `https://enrichment.insightfulmcp.com/`
3. Authorize the connection

## Available Actions

| Action | Description |
|--------|-------------|
| `discovery-crawler` | Identify company name, website, and description from email |
| `profile-crawler` | Gather company profile (industry, headquarters, year founded) |
| `metrics-crawler` | Gather company metrics (employee count, revenue, growth) |
| `funding-crawler` | Gather funding and investment data (rounds, investors, valuation) |
| `tech-stack-crawler` | Detect technologies, languages, and frameworks used |
| `leadership-crawler` | Gather leadership and executive information |

## Usage Examples

### Company Discovery

```
"Identify the company for this email: john@acme.com"
```

### Company Profile

```
"Get the company profile for stripe.com"
```

### Tech Stack Discovery

```
"What technologies does notion.so use?"
```

### Leadership Lookup

```
"Who are the executives at anthropic.com?"
```

### Funding Data

```
"What's the funding history of openai.com?"
```

### Company Metrics

```
"Get employee count and revenue estimates for salesforce.com"
```

## Available Data Points

| Data Point | Description |
|------------|-------------|
| Company Name | Official company name |
| Industry | Business sector classification |
| Employee Count | Company size |
| Revenue Range | Estimated revenue |
| Funding Total | Total funding raised |
| Tech Stack | Technologies used |
| Headquarters | Location and address |
| Leadership | Key executives and founders |
| Year Founded | Company founding year |
| Website | Company website URL |

## Why Enrichment MCP?

### For Sales Teams
- **Lead qualification** - Instant company insights
- **Contact discovery** - Find decision makers
- **Account research** - Comprehensive profiles

### For Marketing Teams
- **List enrichment** - Enhance contact databases
- **Segmentation** - Better audience targeting
- **Personalization** - Relevant outreach

### For Analysts
- **Market research** - Company and industry data
- **Competitive analysis** - Competitor insights
- **Investment research** - Funding and growth data

## Enrichment Workflows

### Lead Scoring
Enrich leads with company size and funding to prioritize outreach.

### ABM Campaigns
Build comprehensive account profiles for account-based marketing.

### CRM Enhancement
Automatically enrich CRM records with fresh data.

### Competitive Intelligence
Monitor competitor tech stacks and hiring trends.

## Security & Privacy

- **GDPR compliant** - Privacy-first approach
- **Data encryption** - Secure transmission
- **Audit logging** - Track all enrichment requests
- **Access controls** - Role-based permissions

## Related MCP Servers

- [LinkedIn Ads MCP](https://insightfulpipe.com/mcp-servers/linkedin-ads) - B2B advertising
- [Web Crawler MCP](https://insightfulpipe.com/mcp-servers/crawler) - Web scraping
- [Google Analytics MCP](https://insightfulpipe.com/mcp-servers/google-analytics) - Visitor analytics

## Resources

- [Documentation](https://insightfulpipe.com/docs/enrichment)
- [Video Tutorial](https://www.youtube.com/playlist?list=PLJNzvjxzI5Xwe__BJJLAelSF0ewO3mEFk)
- [InsightfulPipe Blog](https://insightfulpipe.com/blogs)

## Support

- **Documentation**: [insightfulpipe.com/docs](https://insightfulpipe.com/docs)
- **Email**: support@insightfulpipe.com

## License

MIT License - see [LICENSE](LICENSE) for details.
