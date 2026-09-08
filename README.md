## Luxardo Labs

### Create. Experience. Share. Do.

Independent software lab in St. Louis. This is where "wouldn't it be cool if…" turns into something
that actually runs — backend, web, iOS, embedded firmware, and the infrastructure underneath.

Twenty-five years of tech before this: webmaster to architect to strategic leader, by way of Citi,
HP, BMC, AppDynamics, Grafana Labs, DataRobot, Leapwork, and Chronosphere (now Palo Alto Networks).
Each stop taught me something — how critical systems really behave, what enterprise complexity costs,
how to see what's happening under the hood, where AI is practical and where it isn't. Luxardo Labs is
where all of it comes together: the discipline of enterprise, the creativity of startups, and enough
technical depth to build the whole thing myself.

Built with intention, not growth metrics. For people who notice the difference between a maraschino
cherry and the real thing.

**Most of what's here is private.** Happy to walk through any of it — architecture, decisions, or a
live demo.

### Platforms

| | |
| --- | --- |
| **LuxWX** | Multi-tenant weather data platform. In production, generating revenue. Ingest from WeatherFlow, NWS, and public feeds into TimescaleDB; web portal, alerting, a native iOS app, and purpose-built e-ink displays. Kubernetes across dev and prod. |
| **Boutique** | Retail inventory and point-of-sale platform. FastAPI, HTMX, PostgreSQL, Square POS, loyalty, print services. |

### Conformance tooling

Versioned, containerized guards that run on every commit, across every project:

- **luxarch** — architecture conformance: layering, access-control coverage on mutating routes, schema conformance
- **luxlint** — style and types (ruff, mypy)
- **luxaudit** — dependency CVE scanning
- **luxios** — the Swift sibling (SwiftLint, swift-format, architecture, contracts)

Generating code quickly is the easy part. Keeping it structurally honest at volume is what makes it
safe to ship.

### Open source

| | | |
| --- | --- | --- |
| [kasa-collector](https://github.com/luxardolabs/kasa-collector) | TP-Link Kasa energy data → InfluxDB → Grafana | ⭐ 54 |
| [sense-collector](https://github.com/luxardolabs/sense-collector) | Sense Energy Monitor → InfluxDB → Grafana | ⭐ 29 |
| [luxupt](https://github.com/luxardolabs/luxupt) | Time-lapse video from UniFi Protect cameras | ⭐ 14 |
| [kidde-collector](https://github.com/luxardolabs/kidde-collector) | Kidde HomeSafe smoke / CO / air quality → InfluxDB → Grafana | ⭐ 7 |
| [luxswirl](https://github.com/luxardolabs/luxswirl) | Self-hosted, multi-agent uptime and infrastructure monitoring | |
| [luxmark](https://github.com/luxardolabs/luxmark) | Browser-based markdown editor. No server, no build step. | |
| [brother_ql](https://github.com/luxardolabs/brother_ql) | Modern Python library for Brother QL label printers | |

The collectors have been running in other people's homes since 2021.

### Stack

Python · FastAPI · PostgreSQL / TimescaleDB / pgvector · SQLAlchemy · Pydantic · HTMX · Tailwind ·
Swift / SwiftUI · Kubernetes · Docker · InfluxDB · Grafana · OpenTelemetry · ESPHome

---

Music composition degree from UMKC, still play and produce daily. Everything should have a
personality. Life's too short.

— **Dave Schmid** · St. Louis, MO · [luxardolabs.com](https://www.luxardolabs.com)
