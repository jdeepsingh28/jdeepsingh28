# Jaideep Singh

Quantitative finance student, building on prediction markets.

As I learn this field, I try to apply what I pick up to prediction
markets — turning ideas into data, measurement, and honest results.

## Currently

Earning liquidity-program rewards on **Kalshi** — soon **Polymarket** too —
by market-making: posting continuous two-sided quotes to provide depth and
capture each venue's liquidity incentives. The same events trade on both
venues, so the real edge is doing this *across* them and watching the gap
between — cross-venue spread, mispricings, price discovery.

That all rests on recording both feeds faithfully, which is the public piece:
**[Cross-Venue-Market-Data-Research](https://github.com/jdeepsingh28/Cross-Venue-Market-Data-Research)**
captures both venues' order books on one venue-neutral core — surviving
disconnects and *proving* it never silently dropped a message. Two venues, two
integrity models (Polymarket's book-hash vs. Kalshi's sequence contiguity),
recovering through one shared resync path.

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
