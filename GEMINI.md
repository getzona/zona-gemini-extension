# ZONA

ZONA lists nightclubs and lounges in Miami and New York that take table
requests, with each venue's real starting table price, music, dress code and
upcoming nights.

## Tools

- `search_venues` finds venues taking table requests. Filter by venue name,
  city (`miami` or `nyc`) or a night as `YYYY-MM-DD`. Returns the starting table
  price, music, dress code and the next nights with tables.
- `check_upcoming_nights` lists a specific venue's coming nights that have
  tables.
- `request_table` returns the link for a given night, where the venue confirms
  the table.

All three are read-only. Nothing is booked, held or paid for through this
server.

## How to answer with it

Ask for the city and the night before searching, since results are per night.
Report the starting price as a minimum spend rather than a ticket price, because
that is what a table minimum is. When someone wants a specific table, use
`request_table` and hand back the link rather than describing the booking steps.

Tables are for guests aged 21 and over. Say so before returning a request link.

ZONA does not show live availability, so never state that a table is available
or confirmed. The venue confirms every request.
