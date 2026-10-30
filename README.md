# Flightradar24

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Flightradar24 is the world's most popular real-time flight tracking platform, monitoring over 250,000 daily flights using data from a global network of ADS-B, MLAT, and radar receivers. The FR24 API provides developers with programmatic access to live aircraft positions, historical flight data, flight summaries, and reference data for airports and airlines. The credit-based subscription API uses Bearer token authentication and is available at https://fr24api.flightradar24.com/api with three tiers — Explorer, Essential, and Advanced — covering hobby projects through high-volume commercial applications.

**Areas:** Aviation · Flight Tracking · Real-Time · Aircraft · Airports · Airlines · ADS-B · Historical Data

## Flightradar24 on APIs.io

Everything profiled for Flightradar24 is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/flightradar24/](https://apis.io/providers/flightradar24/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [Live Flights Light](https://apis.io/apis/flightradar24/live-flights-light/) — Returns a lightweight snapshot of real-time aircraft positions worldwide, including latitude, longitude, altitude, speed, heading, callsign, and aircraft…
- [Live Flights Full](https://apis.io/apis/flightradar24/live-flights-full/) — Returns complete real-time aircraft flight movement records including latitude, longitude, speed, altitude, and heading alongside enriched flight…
- [Historical Flights Light](https://apis.io/apis/flightradar24/historical-flights-light/) — Provides historical aircraft positional data using Unix timestamp ranges. Returns lightweight position records (latitude, longitude, altitude, speed,…
- [Historical Flights Full](https://apis.io/apis/flightradar24/historical-flights-full/) — Returns full historical aircraft flight movement records for a given time window, combining positional data with enriched flight metadata including origin,…
- [Flight Summaries](https://apis.io/apis/flightradar24/flight-summaries/) — Returns synopses of individual flights including key event timings and locations such as actual takeoff and landing times, departure and arrival airports,…
- [Flight Tracks](https://apis.io/apis/flightradar24/flight-tracks/) — Returns the full positional track of a specific flight identified by its FR24 flight ID. Provides a time-ordered sequence of latitude, longitude, altitude,…
- [Airports](https://apis.io/apis/flightradar24/airports/) — Returns detailed reference data for airports worldwide, including full airport name, IATA and ICAO codes, geographic coordinates, elevation, country, city,…
- [Airlines](https://apis.io/apis/flightradar24/airlines/) — Returns reference data for airlines including airline name, IATA code, and ICAO code. Supports lookup by identifier. Useful for resolving callsign prefixes…
- [Flightradar24 Airlines API](https://apis.io/apis/flightradar24/flightradar24-airlines-api/) — Reference data for airlines
- [Flightradar24 Airports API](https://apis.io/apis/flightradar24/flightradar24-airports-api/) — Reference data for airports worldwide
- [Flightradar24 Flight Summary API](https://apis.io/apis/flightradar24/flightradar24-flight-summary-api/) — Synopses of individual flights including event timings and key identifiers
- [Flightradar24 Flight Tracks API](https://apis.io/apis/flightradar24/flightradar24-flight-tracks-api/) — Full positional track of a specific flight by FR24 flight ID
- [Flightradar24 Historic Events API](https://apis.io/apis/flightradar24/flightradar24-historic-events-api/) — Historical flight event data (takeoff, landing, gate movements, airspace transitions)
- [Flightradar24 Historic Positions API](https://apis.io/apis/flightradar24/flightradar24-historic-positions-api/) — Historical aircraft position data (back to May 11, 2016)
- [Flightradar24 Live Positions API](https://apis.io/apis/flightradar24/flightradar24-live-positions-api/) — Real-time aircraft position data
- [Flightradar24 Usage API](https://apis.io/apis/flightradar24/flightradar24-usage-api/) — API account usage and credit consumption

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [fr24api-mcp](https://apis.io/servers/flightradar24/fr24api-mcp/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Flightradar24 Agentic Access](https://apis.io/agentic-access/flightradar24/flightradar24-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [AirportFull](https://apis.io/schemas/flightradar24/airport-full/)
- [FlightPositionLight](https://apis.io/schemas/flightradar24/flight-position-light/)
- [FlightSummaryFull](https://apis.io/schemas/flightradar24/flight-summary-full/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [context Context](https://apis.io/jsonld/flightradar24/context/)

#### Examples (4)

Example requests and responses.

- [Airport Full](https://apis.io/examples/flightradar24/airport-full/)
- [Flight Summary Full](https://apis.io/examples/flightradar24/flight-summary-full/)
- [Flight Tracks](https://apis.io/examples/flightradar24/flight-tracks/)
- [Live Positions Light](https://apis.io/examples/flightradar24/live-positions-light/)

#### Collections (8)

Postman and Open Collection request collections.

- [Flightradar24 Airlines API](https://apis.io/collections/flightradar24/open-flightradar24-airlines-api/)
- [Flightradar24 Airlines Airports API](https://apis.io/collections/flightradar24/open-flightradar24-airports-api/)
- [Flightradar24 Airlines Flight Summary API](https://apis.io/collections/flightradar24/open-flightradar24-flight-summary-api/)
- [Flightradar24 Airlines Flight Tracks API](https://apis.io/collections/flightradar24/open-flightradar24-flight-tracks-api/)
- [Flightradar24 Airlines Historic Events API](https://apis.io/collections/flightradar24/open-flightradar24-historic-events-api/)
- [Flightradar24 Airlines Historic Positions API](https://apis.io/collections/flightradar24/open-flightradar24-historic-positions-api/)
- [Flightradar24 Airlines Live Positions API](https://apis.io/collections/flightradar24/open-flightradar24-live-positions-api/)
- [Flightradar24 Airlines Usage API](https://apis.io/collections/flightradar24/open-flightradar24-usage-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Flightradar24 — jsonschema rules](https://apis.io/rules/flightradar24/flightradar24-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Flightradar24 Authentication](https://apis.io/security/flightradar24/flightradar24-authentication/)
- [Flightradar24 Domain Security](https://apis.io/security/flightradar24/flightradar24-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Plans](https://apis.io/plans/flightradar24/plans/)

#### Rate limits (1)

Published request limits.

- [Rate Limits](https://apis.io/rate-limits/flightradar24/rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Finops](https://apis.io/finops/flightradar24/finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://flightradar24.com)
- [Documentation](https://fr24api.flightradar24.com/docs/endpoints)
- [Getting started](https://fr24api.flightradar24.com/docs/getting-started)
- [Pricing](https://fr24api.flightradar24.com/subscriptions-and-credits)
- [Support](https://support.fr24.com/support/solutions/folders/3000022922)
- [Blog](https://www.flightradar24.com/blog/b2b/)
- [GitHub](https://github.com/Flightradar24)

## API Evangelist rating

**Kin Score 38.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 60.0 |
| Contract governance | 9.8 |
| Operational transparency | 2.6 |
| Developer ergonomics | 57.1 |
| Access clarity | 18.4 |

**Agent readiness 30.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/flightradar24/](https://apis.io/providers/flightradar24/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Flightradar24: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/flightradar24/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
