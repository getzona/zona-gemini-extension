# ZONA for Gemini CLI

Adds ZONA's Miami nightlife to Gemini CLI. Ask for a table or what's on in Miami
and get real venues, real nights, real table minimums, Art Week events and a
link to request a table.

## Install

```
gemini extensions install https://github.com/getzona/zona-gemini-extension
```

## What it does

Six read-only tools:

| Tool | Purpose |
| --- | --- |
| `search_events` | Miami events and club nights, including the Art Week guide |
| `art_week_events` | Miami Art Week 2026 events, November 30 to December 6 |
| `search_venues` | Venues taking table requests, by name, night, music, budget or party size |
| `check_upcoming_nights` | A venue's coming nights that have tables |
| `request_table` | The link for a night, where the venue confirms |
| `get_request_status` | Where a table request stands, by its token |

Nothing is booked, held or charged through the server. It connects to
`https://mcp.getzona.app/mcp` over streamable HTTP and needs no account or key.

Tables are for guests aged 21 and over.

## About

ZONA is a nightlife booking app for Miami. More at
[getzona.app](https://getzona.app).

## License

MIT. See [LICENSE](LICENSE).
