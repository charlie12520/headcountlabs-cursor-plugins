# Headcount Labs Events

Find public events in large U.S. cities from venue, city, library, university and community calendars, by city or point, time window (today, tonight, this weekend, next 7 days or dates), free or paid, and category. Get one event with venue, price and source link, see the next dates of a recurring series, and count what is on in a window. Times should be checked at the source. Read-only, no account or API key. Preview data: coverage is partial.

MCP server (Streamable HTTP, no account or API key): `https://events-mcp.headcountlabs.com/mcp/public/events`

## Try it

No auth needed (keyless, read-only). Results depend on the date. 1) event_counts {"city":"chicago","when":"next_7_days"} -> total, free and per-category counts for Chicago this week (about 150 to 250). 2) find_events {"city":"san francisco","when":"this_weekend","is_free":true,"limit":3} -> free SF events this weekend, soonest first, with start time and source URL. 3) get_event with an id from step 2 -> the event details: time, price and source link, plus venue and organizer when known.

## Terms and privacy

- Terms of service: https://headcountlabs.com/terms/
- Privacy policy: https://headcountlabs.com/privacy/
- Support: charlestang@headcountlabs.com
