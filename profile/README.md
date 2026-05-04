# Nausika

> Real maritime data for your AI assistant.

Nausika is a connector that grounds AI assistants in the one thing they cannot make up: real sea data. Marine forecasts, tides, curated coastal places, and a routing graph that respects coastlines — exposed as MCP tools you can plug into any compatible client.

**[nausika.app](https://nausika.app)** · **[Connect to your assistant](https://nausika.app/#install)** · **[Docs](https://nausika.app/docs)**

[![mcp.nausika.app](https://img.shields.io/website?url=https%3A%2F%2Fmcp.nausika.app%2Fhealth&label=mcp.nausika.app&up_message=live&down_message=offline&style=flat-square)](https://mcp.nausika.app/health) [![beta](https://img.shields.io/badge/status-public%20beta-blue?style=flat-square)](https://nausika.app) [![coverage](https://img.shields.io/badge/coverage-Mediterranean-1d6f42?style=flat-square)](https://github.com/nausika-app/nausika-feedback/issues/2)

---

## Status

- **Public beta.** Mediterranean basin is the curated coverage area for places and routing. Forecasts, tides, coastline, and geocode work globally via fallbacks.
- **MCP endpoint:** `https://mcp.nausika.app/mcp` — OAuth 2.1 (or M2M API key).
- **Coverage area today:** Mediterranean. Atlantic and other basins are next.
- Maintainer: [Andrea di Cagno](https://github.com/andreadicagno). Solo dev. Triage weekly. No SLA — this is a beta.

## What it does

| Tool | What it returns |
|---|---|
| `marine_forecast` | Wind, waves, swell, currents, visibility |
| `tides` | Heights and extremes |
| `sea_route` | Distance and waypoints over a coastline-aware graph |
| `search_places` | Anchorages, marinas, harbors with curated metadata |
| `geocode` / `is_water` | Location lookup, water/land checks |
| `calculator` | Fuel, time, ETA helpers |

Plus authenticated tools for boat profiles, favorites, ratings, routes, and place proposals. Full inventory at [nausika.app/docs](https://nausika.app/docs).

## What's in this org

- **[nausika-feedback](https://github.com/nausika-app/nausika-feedback)** — public issue tracker. File bugs, request features, flag coverage gaps. There is no code there; the maintainer triages weekly.

The product itself runs as a managed service and is closed-source for now. Clients, examples, and tooling may move into this org over time.

## Get in touch

| | |
|---|---|
| Bugs, features, coverage gaps | [Open an issue](https://github.com/nausika-app/nausika-feedback/issues/new/choose) |
| General contact | hello@nausika.app |
| Security disclosure | security@nausika.app |
| Privacy | privacy@nausika.app |

---

<sub>Operated from Italy. Not a navigation system; not a substitute for charts, almanacs, or seamanship. See the [disclaimer](https://nausika.app/#disclaimer).</sub>
