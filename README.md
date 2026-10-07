# Jaideep Singh

MS in Quantitative Finance at Fordham. Building on prediction markets.

As I learn this field, I try to apply what I pick up to prediction
markets — turning ideas into data, measurement, and honest results.

## Currently

Maintaining a 24/7 capture system for Kalshi and Polymarket market data: every WebSocket message
recorded to hourly tapes, published to versioned cloud storage, and checked each morning against
the venues' own records.
- Both Venues: Fed decisions, CPI/Inflation, NFL/CFB games 
- Only Kalshi: every commodity market

<!-- CAPTURE-STATS:START — everything between these markers is rewritten by the daily update. -->

| | Kalshi | Polymarket |
|---|---|---|
| Hours recorded, last 7 days | 168 of 168 | 168 of 168 |
| Seconds with no recorder running, last 7 days | 9.5 s | 9.5 s |
| Order books rebuilt and checked against the venue, last 7 days | checked 7 of 7 days, mismatches on 3 | checked 1 of 7 days, no mismatches |

*Recording daily since 2026-09-19. This covers 2026-09-29 to 2026-10-05 (UTC). Updated 2026-10-06.*

<!-- CAPTURE-STATS:END -->

## Projects

- **[kalshi-btc-bot](https://github.com/jdeepsingh28/kalshi-btc-bot)** — a
  volatility-gated market maker for Kalshi's hourly BTC markets. Sold far-OTM
  tails to collect premium, buying them back as they decayed; every entry gated
  on a live volatility signal. Deployed live ~3.5 weeks (223 events), retired
  Apr 2026 — packaged with its real, reconciled trading record.

- **[kalshi-weather-bot](https://github.com/jdeepsingh28/kalshi-weather-bot)**
  — two decoupled systems for Kalshi daily-high-temperature markets: a
  multi-model NWP forecast pipeline (GEFS / HRRR / ECMWF across 18 cities) and
  a premium-selling market maker that traded them live in early 2026. Retired
  March 2026, with the honest note on which piece drove the edge.

---

*Updated whenever I have a new project or result to add. Hope you enjoy.*

<!--
  Project slots to add as repos / results land:
  - Cross-venue BTC price-discovery study (honest result)
  - Algorithmic Trading System
-->
