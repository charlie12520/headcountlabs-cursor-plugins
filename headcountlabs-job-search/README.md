# Headcount Labs Job Search

Search current job postings collected from public job boards and company career sites; every job links to its original posting. Tools: search_jobs, get_job, count_jobs (live counts, can group by employer, city, state and more), salary_range, market_lookup and market_breakdown (pay percentiles and job counts from a daily U.S. snapshot), market_dimensions, list_fields and search_docs. Read-only. This keyless endpoint needs no account or API key; one search shows up to 250 jobs, up to 50 per page.

MCP server (Streamable HTTP, no account or API key): `https://api.headcountlabs.com/mcp/public`

## Try it

No sign-in or API key; add the URL as a remote MCP server (Streamable HTTP). 1) count_jobs {"filters":{"company":"Stripe"}} -> a live job count (about 1,400 in late Oct 2026). 2) search_jobs {"filters":{"title":"nurse","state":"TX"},"limit":3} -> 3 Texas nursing jobs with employer, location, dates and posting/apply links; if it returns query_timeout, retry once. 3) salary_range {"title":"Registered Nurse","place":"Texas"} -> yearly pay percentiles (median about $92k) with sample size and as_of date.

## Terms and privacy

- Terms of service: https://headcountlabs.com/terms/
- Privacy policy: https://headcountlabs.com/privacy/
- Support: charlestang@headcountlabs.com
