# Daycare Watch public data

This repository contains public childcare availability snapshots generated from official Canadian government and municipal sources for the Daycare Watch application.

## Data layout

- `data/current.json` and `data/changes.json` — Manitoba / Winnipeg
- `data/bc-vancouver/` — Vancouver, BC
- `data/bc-surrey/` — Surrey, BC
- `data/bc-burnaby/` — Burnaby, BC
- `data/bc-victoria/` — Victoria, BC
- `data/on-toronto/` — Toronto, Ontario

Each supported region publishes `current.json` and `changes.json`. The files are generated automatically by the private Daycare Watch collector. They contain only information intended for the public product and derived from public official sources.

Availability signals must be interpreted according to the upstream source. Manitoba may publish numeric reported vacancies, while British Columbia and Toronto primarily publish age-specific availability indicators. A published signal is not a guarantee that a place is still available; families should confirm directly with the provider.
