# Controlled Decay

An interactive dashboard visualizing a longitudinal photo dataset of a decaying subject over time — filter, sort, and scrub through a timeline of tending vs. entropy, styled with restraint-driven, intentional visual design rather than a generic admin-dashboard look.

*Status: In active development and update. Schema and architecture below reflect what was the current build; live demo and dataset will be added after the project is finished updating. See Mockup below:*

## Mockup
<img width="986" height="758" alt="image" src="https://github.com/user-attachments/assets/2e65b9f0-7171-4d29-9700-7848df6fe8fe" />

## Tech Stack
React · Figma · MySQL · REST API · AWS RDS

## Concept
A real decaying subject, photographed over weeks, is logged alongside the interventions used to tend it. The dashboard lets a viewer scrub through time and see the tension between deliberate tending and unstoppable decay, visually restrained (limited palette, generous whitespace) so the interface itself reflects the concept rather than fighting it with default dashboard chrome.

## What This Demonstrates
- API design and consumption, a custom REST layer over a MySQL database hosted on AWS RDS
- Dashboard-scale state management (filters, sort, and date range all interacting correctly)
- Figma-to-code workflow, UI built directly from design files
- Data visualization fundamentals (timeline navigation, filtered views)

## Build Progress
- [ ] MySQL schema + seed data
- [ ] REST API (single endpoint, read-only)
- [ ] React app consuming live data
- [ ] Filter + sort + timeline interaction
- [ ] Figma-driven visual design pass
- [ ] Deploy + endpoint tests + documentation

## A Note on Status
*Rebuilding the dashboard to replicate the fall season and the natural decay that occurs from the changing seasons.*
