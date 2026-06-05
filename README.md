# Jaideep Singh

Quantitative finance student building prediction-market research infrastructure.

## Projects

### Cross-Venue Prediction-Market Research

Capturing tick-level market data for the same events on Kalshi and Polymarket
to study cross-venue spread, mispricings, and price discovery.

- Dual-venue tick recorder (Kalshi signed-RSA WebSocket + Polymarket CLOB
  WebSocket) running 24/7 on GCP.
- Capture raw, normalize later: every message saved to a raw tape, mirrored
  to a GCS data lake, then converted to venue-neutral, time-partitioned Parquet.
- Both venues stamped on one chrony-disciplined clock, so cross-venue lead-lag
  is signal, not clock skew.

*Repository publishing soon.*

<!--
  Draft scaffold. Next slots to fill:
  ### Algorithmic Trading System
  ### (anything else worth featuring)
-->
