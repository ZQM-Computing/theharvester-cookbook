# theHarvester Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **theHarvester cookbook** for passive reconnaissance from public sources. Patterns are drawn from the ZQM fleet's theHarvester 4.11.1 installs (source clone and tag checkout, never the PyPI 0.0.1 stub) and its passive crt.sh demo against zqmlabs.com only. Passive sources only — nothing active, nothing intrusive. It is intended for OSINT practitioners who enumerate domains, emails, and hosts passively. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** theHarvester patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

OSINT practitioners who enumerate domains, emails, and hosts passively.

## Prerequisites

- theHarvester 4.11.1
- Python 3.11+
- An in-scope domain you own or are authorized to research

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-crtsh-passive` | Passive certificate-transparency enumeration with crt.sh |
| 02 | `02-source-config` | Configuring passive sources and API keys (keys stay out of repos) |
| 03 | `03-output-formats` | JSON and XML outputs and how to read them |

## Repository layout

```text
theharvester-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [amass-cookbook](https://github.com/ZQM-Computing/amass-cookbook) — Passive subdomain enumeration and graph output
- [spiderfoot-cookbook](https://github.com/ZQM-Computing/spiderfoot-cookbook) — Passive OSINT automation as a service
- [scrapy-cookbook](https://github.com/ZQM-Computing/scrapy-cookbook) — Polite web scraping spiders, pipelines, and exports
