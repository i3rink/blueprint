# qb
Annick QB
Internal quote builder for Annick Bathrooms. Private repository.

What it is

A single-file PWA replacing the Moon Invoice + Google Docs quoting workflow. Covers the full sales journey from bathroom survey through to a priced customer quote and warehouse packing slip.

Modules

Module 1 — Bathroom Planner
Room drawing, fixture placement, pre-survey capture, installation spec, additional works pricing, materials quantities.

Module 2 — Quote Builder
Package selection, 10-step product configurator, upgrade pricing, discount gate, quote summary. Supabase persistence — jobs save and reload by Job ID.

Tech

Single HTML file. Vanilla JS, no framework, no build step. Hosted on GitHub Pages. Supabase for job persistence.

Versioning

Semver. Version string is in the HTML comment on line 1 and in the page title. Every push should bump the version and include a one-line commit message.

Access

Internal use only — Shaun (sales), Scott (catalogue/admin), Neil (build). Not for distribution.
