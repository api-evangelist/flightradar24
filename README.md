# Flightradar24

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
