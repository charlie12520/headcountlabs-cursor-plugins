# Headcount Labs Prices

Grocery and household products from Open Food Facts and USDA, with dated shelf-price observations from Open Prices and BLS benchmarks. Find products by name or brand, look one up by barcode (UPC, EAN or GTIN), find the cheapest recently observed prices with store and date, find stores with prices near a point, and get price statistics. Prices are past observations, not live shelf prices. Read-only, no account or API key. Data under ODbL from Open Food Facts, Open Prices and OpenStreetMap contributors.

MCP server (Streamable HTTP, no account or API key): `https://products-mcp.headcountlabs.com/mcp/public/products`

## Try it

No auth needed (keyless, read-only). 1) get_product {"gtin":"00016000275263"} -> GENERAL MILLS Cheerios with its recent prices (USD $1.99 seen 2026-07-24). 2) find_products {"q":"cheerios","limit":3} -> three Cheerios products with barcodes. 3) find_prices {"q":"oat milk","limit":3} -> cheapest observed oat milk prices, each with store, city and date seen.

## Terms and privacy

- Terms of service: https://headcountlabs.com/terms/
- Privacy policy: https://headcountlabs.com/privacy/
- Support: charlestang@headcountlabs.com
