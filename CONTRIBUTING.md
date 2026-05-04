# Contributing to Nausika

Thanks for taking the time to file something — feedback is what shapes a public beta.

## What goes where

| You want to… | Use this |
|---|---|
| Report something wrong with a forecast, route, place, or auth flow | [Bug template](https://github.com/nausika-app/nausika-feedback/issues/new?template=bug.yml) |
| Ask for something missing or different | [Feature template](https://github.com/nausika-app/nausika-feedback/issues/new?template=feature.yml) |
| Tell us a region is missing, thin, or wrong | [Coverage template](https://github.com/nausika-app/nausika-feedback/issues/new?template=coverage.yml) |
| Ask a usage question | hello@nausika.app — issues are for actionable reports |
| Disclose a vulnerability | security@nausika.app — see [SECURITY.md](SECURITY.md) |

## Filing well

A useful report contains, at minimum:

- **What you did** — the prompt, tool call, or URL
- **What you got** — the answer, error, or behavior
- **What you expected** — what would have been correct
- **Where** — coordinates, port name, or rough bounding box (especially for coverage)
- **When** — UTC timestamp, helpful for forecast-related reports

Please search [open issues](https://github.com/nausika-app/nausika-feedback/issues) before filing. A thumbs-up on an existing report counts more than a duplicate.

## What we'll do

- Triage cadence: **weekly**. Issues get a `triage` label until reviewed.
- `accepted` → on the work list. `wontfix` → won't act, with a reason. `needs-info` → reporter input required.
- No SLA — Nausika is in public beta, run by a solo maintainer. Best-effort responsiveness.
- We'll close issues that are off-topic, duplicates, or unactionable. Disagreement is welcome — argue your case in the thread.

## What we don't accept

- Reports sourced from proprietary marine platforms (Navily, ActiveCaptain, Garmin, etc.). All data must be your own observation or from open-licensed sources (OpenStreetMap/ODbL).
- Bulk submissions or scraped output.
- Demands for an SLA, refunds, or contractual commitments — this is a free public beta.

## Code contributions

There's no code in this org's public repos today. The product itself is closed-source for now. If you're building something on top of Nausika and want to share examples or clients, open an issue first to discuss before opening a PR.

— Andrea
