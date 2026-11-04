# Headcount Labs: All Indexes

Every Headcount Labs index through one MCP server: current job postings with live counts and pay ranges, U.S. companies with parent and subsidiary links, public services and government programs, grocery products and prices, places with hours, public events, doctors and Medicare facilities, and inspections, in one connection with 54 tools. Use this instead of installing the single-index plugins one by one. Every record links to its source. Read-only, no account or API key.

MCP server (Streamable HTTP, no account or API key): `https://mcp.theinternetindex.org/mcp`

This is the combined gateway for all Headcount Labs indexes (it identifies itself as "The Internet Index", the gateway name). The single-index plugins in this repository connect to one index each.

## Try it

No sign-in or API key; add the URL as a remote MCP server (Streamable HTTP). 1) count_jobs {"filters":{"company":"Stripe"}} -> a live job count (about 1,500 on Nov 3 2026). 2) get_company {"ticker":"NVDA"} -> NVIDIA with its identifiers and sources. 3) find_doctors {"lat":41.8781,"lon":-87.6298,"radius_m":2000,"specialty":"pediatrician","limit":2} -> two clinicians near downtown Chicago with NPI and address.

## Terms and privacy

- Terms of service: https://headcountlabs.com/terms/
- Privacy policy: https://headcountlabs.com/privacy/
- Support: charlestang@headcountlabs.com
