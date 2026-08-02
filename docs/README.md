# Outergy Website docs — map

| Tier | What lives here | Ask yourself |
|---|---|---|
| `intent/` | Holdco-site roadmap/specifications and `decisions/` (ADRs) | *why* are we building this? |
| `as-built/` | Current site architecture/data truth and dated issue ledgers | what is true *now*? |
| `reference/` | Durable procedures and evidence | durable how-to / evidence |
| `../tasks/STATUS.md` | current task state — replace, never append | what's in flight? |

`companies.html` is the portfolio-card source for this site. Each card's product claims remain subordinate to the matching app repository's `docs/intent/VALUE-PROPOSITION.md`; do not copy those documents into this aggregate repository.

When website ledgers are added, release gates read `as-built/BUG-REPORTS.md ## Open`. A recurring bug moves back to Open with its dated trail intact. Never edit inside SENTRY-RADAR markers.
