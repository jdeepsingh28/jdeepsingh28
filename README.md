# Jaideep Singh

MS Quantitative Finance at Fordham. Building on prediction markets.

As I learn this field, I try to apply what I pick up to prediction
markets — turning ideas into data, measurement, and honest results.

## Currently

**MS Quantitative Finance at Fordham**, graduating December 2027 — studying derivatives and
financial programming, and pointing what I pick up at prediction markets.

## Recently

**Market making on Kalshi (June–August 2026).** An automated engine posted continuous two-sided,
post-only quotes 24/7 on a GCE VM under systemd, into Kalshi's liquidity-incentive program. This was
market making, not directional trading: the system quoted both sides of a market rather than taking a
view on the outcome.

**Cross-venue research across Kalshi and Polymarket (April–June 2026).** The same events list on
both venues, and the gap between them is where the interesting questions live — cross-venue spread,
mispricing, price discovery. That rested on recording both feeds faithfully —
**[Cross-Venue-Market-Data-Research](https://github.com/jdeepsingh28/Cross-Venue-Market-Data-Research)**
captures both venues' order books on one venue-neutral core — surviving disconnects and *proving* it
never silently dropped a message. Two venues, two integrity models (Polymarket's book-hash vs. Kalshi's
sequence contiguity), recovering through one shared resync path. It recorded 14 consecutive days across
both venues.

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

- **[kalshi-category-ingest](https://github.com/jdeepsingh28/kalshi-category-ingest)**
  — map Kalshi's full open-market catalog and ingest any category to Parquet
  for analysis.

---

*Updated whenever I have a new project or result to add. Hope you enjoy.*

<!--
  Project slots to add as repos / results land:
  - Cross-venue BTC price-discovery study (honest result)
  - Algorithmic Trading System
-->
