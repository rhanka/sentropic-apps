# sentropic-apps

Deployable Sentropic applications and their single deploy chain.

Apps born here (stage 3 of the staging plan): the artifact site `pages.sent-tech.ca` and the remote control `remote.sent-tech.ca`.
Libraries (`@sentropic/*`) stay in their own repositories and are consumed as published packages.

Design reference: `spec/SPEC_EVOL_SENTROPIC_APPS_MONOREPO.md` in `rhanka/sentropic` (owner decision 2026-11-15: staged creation).

Rules: Make-only, Docker-first, one deploy pipeline, one owner approval per production promotion. No secret is ever committed.
