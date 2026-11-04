# Headcount Labs Companies

Look up U.S. companies from public records: SEC EDGAR, GLEIF, USAspending, Wikidata and state business registries. Find a company by name or web domain, get one by ticker, CIK, LEI, Wikidata ID or domain, and list its direct parents and subsidiaries from GLEIF and Wikidata ownership links. Every record names its sources, and get_company_record returns the full source-linked record. Read-only, no account or API key. Preview data: coverage is partial and unknown fields are null.

MCP server (Streamable HTTP, no account or API key): `https://companies-mcp.headcountlabs.com/mcp/public/companies`

## Try it

No auth needed (keyless, read-only). 1) get_company {"ticker":"NVDA"} -> Nvidia Corp, SEC CIK 0001045810, LEI 549300S4KLFTLO7GSQ80, domain nvidia.com. 2) find_companies {"q":"Alphabet","limit":2} -> Alphabet Inc. first (CIK 0001652044, domain abc.xyz). 3) company_family {"lei":"5493006MHB84DD0ZWV18"} -> Google LLC listed as a subsidiary of Alphabet.

## Terms and privacy

- Terms of service: https://headcountlabs.com/terms/
- Privacy policy: https://headcountlabs.com/privacy/
- Support: charlestang@headcountlabs.com
