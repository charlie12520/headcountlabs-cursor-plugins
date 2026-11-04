# Headcount Labs plugins for Cursor

Eight plugins: one per index, plus one that connects to all of them. All read-only, built on public data, no account or API key.

| Plugin | MCP server |
|---|---|
| [Headcount Labs: All Indexes](headcountlabs-all/README.md) | `https://mcp.theinternetindex.org/mcp` (all indexes in one server) |
| [Headcount Labs Job Search](headcountlabs-job-search/README.md) | `https://api.headcountlabs.com/mcp/public` |
| [Headcount Labs Companies](headcountlabs-companies/README.md) | `https://companies-mcp.headcountlabs.com/mcp/public/companies` |
| [Headcount Labs Public Services](headcountlabs-public-services/README.md) | `https://public-services-mcp.headcountlabs.com/mcp/public/public-services` |
| [Headcount Labs Prices](headcountlabs-prices/README.md) | `https://products-mcp.headcountlabs.com/mcp/public/products` |
| [Headcount Labs Places](headcountlabs-places/README.md) | `https://places-mcp.headcountlabs.com/mcp/public/places` |
| [Headcount Labs Events](headcountlabs-events/README.md) | `https://events-mcp.headcountlabs.com/mcp/public/events` |
| [Headcount Labs Doctors](headcountlabs-doctors/README.md) | `https://doctors-mcp.headcountlabs.com/mcp/public/doctors` |

Each folder holds a `.cursor-plugin/plugin.json` manifest and an `mcp.json` that points at the hosted server. The server code is not in this repository.

Website: https://headcountlabs.com

## Terms and privacy

- Terms of service: https://headcountlabs.com/terms/
- Privacy policy: https://headcountlabs.com/privacy/
- Support: charlestang@headcountlabs.com
