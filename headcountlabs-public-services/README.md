# Headcount Labs Public Services

Find where to get public services in the U.S.: food pantries, SNAP and WIC sites, community health centers, Head Start, HUD housing counselors, senior and city service centers near a point, with address, phone, hours, requirements and languages where known. Also look up government programs by name or assistance listing number (10.551 is SNAP) and the agencies that run them. Directory facts only; it never decides eligibility. Read-only, no account or API key. Preview data with sources on every record.

MCP server (Streamable HTTP, no account or API key): `https://public-services-mcp.headcountlabs.com/mcp/public/public-services`

## Try it

No auth needed (keyless, read-only). 1) find_services {"lat":40.7128,"lon":-74.006,"radius_m":2000,"limit":3} -> service sites in Lower Manhattan, nearest first, such as a SNAP retailer and the Food Pantry at Pace University, with address and phone when known. 2) service_counts {"lat":40.7128,"lon":-74.006,"radius_m":2000} -> site totals by category (seniors, food, health...). 3) get_program {"assistance_listing":"10.551"} -> Supplemental Nutrition Assistance Program (SNAP) with summary and eligibility.
