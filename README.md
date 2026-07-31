# Client Dashboards

Live client-facing reporting pages, one folder per client.

- `pickleball/` — Pickleball Palace, Meta Ads
- Data is fetched at runtime from scoped Supabase edge functions. **No credentials live in this repo.**
- Each dashboard requires an access code passed in the URL (`?k=…`); the code is never stored here.
- Stats are refreshed nightly at 8:00 PM AEST by Make.com scenarios.
