# ZONA for Gemini CLI

Adds ZONA's nightlife table inventory to Gemini CLI. Ask for a table in Miami or
New York and get real venues, real nights, real table minimums and a link to
request one.

## Install

```
gemini extensions install https://github.com/getzona/zona-gemini-extension
```

## What it does

Three read-only tools:

| Tool | Purpose |
| --- | --- |
| `search_venues` | Venues taking table requests, by name, city or night |
| `check_upcoming_nights` | A venue's coming nights that have tables |
| `request_table` | The link for a night, where the venue confirms |

Nothing is booked, held or charged through the server. It connects to
`https://mcp.getzona.app/mcp` over streamable HTTP and needs no account or key.

Tables are for guests aged 21 and over.

## About

ZONA is a nightlife booking app for Miami and New York. More at
[getzona.app](https://getzona.app).

## License

MIT. See [LICENSE](LICENSE).
