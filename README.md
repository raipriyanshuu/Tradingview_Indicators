# TradingView Pine Script indicators

Pine Script v6 overlay indicators. Paste a file into the TradingView Pine Editor and click "Add to chart".

| File | Indicator | What it shows |
|---|---|---|
| `Multi_VWAP.pine` | Multi-VWAP | Daily / Weekly / Monthly / Yearly VWAPs with volume-weighted σ or % bands, previous-period VWAP, higher-timeframe fallback when chart history is short |
| `TPO_Levels.pine` | TPO Levels | Decision-useful structure from each session's TPO profile (POC, value area, IB, single prints, tails, poor highs/lows, naked POCs) |
| `Key_Levels.pine` | Key Levels (D/W/M/Y) | Daily / weekly / monthly / yearly reference levels |
| `MA_Map.pine` | MA Map | Moving-average map |

All scripts share the same session engine: Auto / Exchange session / Main session (RTH) / Full 24h / Custom (crypto day anchor, NSE/BSE 09:15 IST, MCX and others on the exchange session, US futures RTH or Globex).
