# Headcount Labs Places

Find shops, restaurants, cafes, pharmacies, libraries and other places near a point in the 20 largest U.S. cities, with address, phone, website, weekly hours and open-now when hours are known. Filter by name, brand, category or open time, and count chain locations versus independents nearby. Data from OpenStreetMap contributors (ODbL), Overture Maps, All the Places, Foursquare OS Places and city open data; each record names its sources. Read-only, no account or API key.

MCP server (Streamable HTTP, no account or API key): `https://places-mcp.headcountlabs.com/mcp/public/places`

## Try it

No auth needed (keyless, read-only). 1) find_places {"lat":40.758,"lon":-73.9855,"radius_m":800,"category":"pharmacy","limit":3} -> 3 pharmacies near Times Square, nearest first (Duane Reade and CVS Pharmacy, 1619 Broadway), with address, distance and phone when known. 2) brand_counts {"lat":40.758,"lon":-73.9855,"radius_m":1000} -> counts by chain (Starbucks, Chase, Dunkin' and more) plus the number of independent places. 3) get_place with an id from step 1 -> that place's full record; open_now is null when hours are unknown.
