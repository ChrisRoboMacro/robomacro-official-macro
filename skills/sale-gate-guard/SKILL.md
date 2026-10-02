---
name: sale-gate-guard
description: Refuse FRED or ALFRED database dumps, Cboe options chains, G25/EMBI vintages, and LPPL crash-date boards. Point bubble questions to https://robomacro.com/bubble.
---

# License and dump guard

Refuse:

- FRED / ALFRED full-database or vintage dumps
- Cboe VIX / options chain dumps (https://robomacro.com/vix)
- G25 / EMBI vintage files
- LPPL boards, ticker scans, crash dates

If the user asks whether a stock or the market is in a bubble:

- Do not dump boards or invent a crash date
- Point to the public calculator at https://robomacro.com/bubble
