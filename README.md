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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Flightradar24 is the world's most popular real-time flight tracking platform, monitoring over 250,000 daily flights using data from a global network of ADS-B, MLAT, and radar receivers. The FR24 API provides developers with programmatic access to live aircraft positions, historical flight data, flight summaries, and reference data for airports and airlines.

**API Portal:** https://fr24api.flightradar24.com/  
**Documentation:** https://fr24api.flightradar24.com/docs/endpoints  
**Base URL:** https://fr24api.flightradar24.com/api  
**Authentication:** Bearer token (Authorization header) + Accept-Version: v1 header  

## APIs

| API | Description |
|-----|-------------|
| Live Flights Light | Real-time aircraft positions (lightweight) |
| Live Flights Full | Real-time aircraft positions with full flight metadata |
| Historical Flights Light | Past aircraft positions by time range (lightweight) |
| Historical Flights Full | Past aircraft positions with full flight metadata |
| Flight Summaries | Takeoff/landing event synopses, real-time and historical |
| Flight Tracks | Full positional track for a specific flight by FR24 flight ID |
| Airports | Airport reference data (name, IATA/ICAO, coordinates, timezone) |
| Airlines | Airline reference data (name, IATA/ICAO codes) |

## Plans

| Plan | Price | Monthly Credits | Rate Limit |
|------|-------|-----------------|------------|
| Explorer | $9/month | 30,000 | 10 req/min |
| Essential | $99/month | 450,000 | 30 req/min |
| Advanced | $900/month | 4,050,000 | 200 req/min |

A promotional deal active through December 31, 2026 doubles monthly credits for all plans on billing cycles starting on or before that date.

## SDKs

- Python SDK: https://fr24api.flightradar24.com/docs/sdk/python
- JavaScript SDK: https://github.com/Flightradar24/fr24api-sdk-js
- MCP Server: https://github.com/Flightradar24/fr24api-mcp
