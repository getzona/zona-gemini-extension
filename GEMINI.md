# ZONA

ZONA lists Miami nightclubs and lounges that take table requests, with each
venue's door hours, music, dress code, starting table price and upcoming nights,
plus Miami events and ZONA's Miami Art Week 2026 guide.

## Tools

- `search_events` searches Miami events, parties, art fairs, brand activations
  and club nights, including ZONA's Art Week guide. Filter by keyword, dates,
  neighborhood, category, music, access, price or organizer.
- `art_week_events` lists Miami Art Week 2026 events (November 30 to December 6),
  with day, time, place, how to get in and the organizer's link.
- `search_venues` finds venues taking table requests. Filter by venue name, a
  night as `YYYY-MM-DD`, music, budget, party size or availability.
- `check_upcoming_nights` lists one venue's coming nights that have tables.
- `request_table` returns the link where the guest requests a table for a night.
- `get_request_status` looks up a table request by its token: pending, confirmed,
  paid, counter offered or declined.

All six are read-only. Nothing is booked, held or paid for through this server.

## How to answer with it

Ask for the night before searching for tables, since results are per night.
Report the starting price as a minimum spend rather than a ticket price, because
that is what a table minimum is. When someone wants a specific table, use
`request_table` and hand back the link rather than describing the booking steps.

Tables are for guests aged 21 and over. Confirm that before asking for a request
link.

ZONA does not show live availability, so never state that a table is available
or confirmed. The venue confirms every request.
