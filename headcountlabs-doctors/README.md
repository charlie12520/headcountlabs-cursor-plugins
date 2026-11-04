# Headcount Labs Doctors

Find U.S. doctors, nurse practitioners, dentists and other clinicians near a point by plain specialty words, or by name or NPI, from public CMS data (NPPES and Medicare). Also find Medicare-certified hospitals and nursing homes with certified beds and CMS star rating, a clinician's hospital and group affiliations, and specialty counts for an area. Directory facts only, not medical advice; whether a doctor takes new patients is not known. Read-only, no account or API key.

MCP server (Streamable HTTP, no account or API key): `https://doctors-mcp.headcountlabs.com/mcp/public/doctors`

## Try it

No auth needed (keyless, read-only). 1) find_doctors {"lat":41.8781,"lon":-87.6298,"radius_m":2000,"specialty":"pediatrician","limit":2} -> clinicians in downtown Chicago, nearest first, with NPI, address and phone. 2) get_doctor {"npi":"1710980339"} -> LOUIS HIOTIS, MD, internal and pediatric medicine. 3) find_facilities {"q":"Mayo Clinic","state":"MN","limit":2} -> Medicare-certified facilities such as MAYO CLINIC HEALTH SYSTEM - LAKE CITY (nursing home, 90 beds).
