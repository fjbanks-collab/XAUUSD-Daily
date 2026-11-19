# XAUUSD DAILY QUANTITATIVE ASSESSMENT - 2026-11-19 (Pre-London, 07:00 UTC)

## AT A GLANCE
| | |
|---|---|
| **Stance** | ⚪ STAND ASIDE — no execution authorised |
| **Composite** | -1 / 4 |
| **Confidence** | LOW — `market_levels.json` is **stale**: `generated_at_utc` and every tick timestamp are still 2026-11-17T06:55:02Z/08:55Z, now ~48h old as of this run (07:07 UTC Nov 19) — the MT5 bridge has not pushed a fresh snapshot for a second consecutive morning (it was already flagged stale yesterday on the same Nov 17 file). WebSearch found no reliably-dated Nov 19 UTC XAUUSD quote to substitute. All four votes are carried forward verbatim from yesterday's stale-data read, with zero new structural evidence on any instrument. |
| **Current spot** | $3,871.88 — **last confirmed MT5 bid** (Nov 17 08:55 UTC tick), carried forward; no fresher quote could be confirmed |
| **Level above** | $3,901.16 (Nov 16 H4 high) · $3,923.09 (Nov 13 D1 high — daily cycle high) |
| **Level below** | $3,852.47 (broken Nov 12 D1 low, now support) · $3,831.76 (Nov 16 H4/D1 low) |
| **Why** | Composite -1 (unchanged): XAUUSD's confirmed sweep-and-reclaim daily-cycle-low reversal (+1) remains offset by DXY's intact higher-high dollar expansion (-1) and GDX/GDXJ's continued miner distribution/divergence (-1); USOIL stays a confirmed data blackout (0) |
| **Watch today** | None scheduled in the next 1-2 sessions — next NFP is Dec 4, next FOMC is Dec 8-9, next CPI is Dec 10, next PPI is Dec 15, 2026 |
| **Vs yesterday** | Composite **-1 (stand aside) → -1 (stand aside)**: unchanged — the MT5 bridge has now failed to refresh for two consecutive mornings, so the file and all four votes remain carried forward verbatim with no new structural evidence in either direction |

## DAILY 4-VOTE LEDGER
- 🟢 XAUUSD: confirmed DCL, sweep-and-reclaim reversal (stale, carried forward) | The Nov 16 04:00 H4 bar swept through the broken Nov 12 cycle low (3852.47) to a fresh low of 3831.76, and price built a higher-low H4 sequence (3833.83→3861.72→3870.18) back above that broken low to the last confirmed 3871.88 bid; no fresher tick exists to confirm continuation or invalidate it today | vote: **+1**
- 🔴 DXY: sustained higher-high expansion intact (stale, carried forward) | D1 closes climbed every session since the Nov 6 low (102.103→103.333), with a fresh high of 103.608 printed before the last confirmed 103.408 bid; no fresher tick exists to confirm a reversal today, so the structural dollar-pressure read stands | vote: **-1**
- ⚪ USOIL: data blackout persists, no confirmable cycle-phase read | `WTI_V6_CFD` explicitly returns `"error": "symbol not found or no tick"` in the feed with no broker-level fix across two mornings, and web search found no single reliably-dated Nov 19 WTI reversal/continuation signature to substitute, so this stays unscored rather than forced | vote: **0**
- 🔴 GDX/GDXJ: confirmed distribution, lagging severely into spot's reclaim (stale, carried forward) | GDX's last confirmed bid (79.20) and GDXJ's last confirmed close (95.69), both from the Nov 16 NY session, extended declines below the prior Friday close even as XAUUSD swept its low and reclaimed higher; no fresher tick exists to confirm stabilization today | vote: **-1**

**COMPOSITE SCORE: -1 / 4**
**STANCE: STAND ASIDE**

## RATIONALE
This morning's run again found `market_levels.json` completely unrefreshed — `generated_at_utc` and every tick timestamp are identical to the Nov 17 snapshot used yesterday, meaning the MT5 bridge has now missed two consecutive pre-London pushes and there is zero new structural information on any of the four votes. XAUUSD's last confirmed read remains a completed daily-cycle-low reversal: the Nov 16 sweep through the broken Nov 12 low (3852.47) to 3831.76, followed by a higher-low H4 sequence back to 3871.88, still stands unconfirmed-or-denied by fresher data (Vote 1: +1). DXY's last confirmed read is an unbroken higher-high dollar expansion into 103.608/103.408, which continues to structurally cap gold (Vote 2: -1). GDX/GDXJ's last confirmed prints (79.20 / 95.69) still show miners diverging bearishly from spot's bounce (Vote 4: -1). USOIL remains a full MT5 data blackout (`WTI_V6_CFD` symbol error) with no reliable dated web substitute found (Vote 3: 0, unscored). The resulting composite of -1/4 sits inside the -2 to +2 stand-aside band, identical to yesterday's conclusion; no high-impact event (next NFP Dec 4, next FOMC Dec 8-9, next CPI Dec 10, next PPI Dec 15) falls within the next 1-2 sessions, so no additional pre-event size caution is layered on top of the data-staleness caution already driving the LOW confidence rating — operationally, the MT5 bridge itself needs attention given the second straight missed push.

## VISUAL TRADE PLAN - PRICE LADDER (XAUUSD)
```
3923.09   ---  Nov 13 D1 high — daily cycle high, bull-confirmation level if reclaimed
3901.16   ---  Nov 16 H4 high — immediate overhead resistance / Q2 judas-swing probe zone
3871.88  >>>  LAST CONFIRMED SPOT — stale MT5 bid (Nov 17 08:55 UTC), no fresher tick available
3852.47   ---  broken Nov 12 D1 low, now support — retest pocket; holding favors continuation higher
3831.76   ---  Nov 16 H4/D1 low — swing-structure invalidation; loss resumes the bearish breakdown
```

## QUARTERLY THEORY SESSION CADENCE
- Q1 (06:00-07:30 UTC): asian range capture — cannot be read today; the feed has not updated since the Nov 17 session, so no fresh overnight range is confirmed for a second day running.
- Q2 (07:30-09:00 UTC): judas swing — watch for a probe into 3886.78-3901.16 that fails and fades, or a dip back into the 3852.47 retest pocket that holds; either outcome stays inside the no-trade range given the -1 composite, and should be treated cautiously until the feed refreshes.
- Q3 (09:00-10:30 UTC): true trend distribution — with the composite neutral (stand aside) and data stale, expect continued range-bound rotation between 3852.47 and 3901.16 absent a fresh vote flip or a restored live feed.
- Q4 (10:30-12:00 UTC): terminal distribution — watch whether price closes the session above 3901.16 (tilts toward bullish confirmation) or back below 3852.47 (resumes the bearish breakdown); no high-impact event today to force a resolution, but confirm against a live quote before acting, since today's read is built on a snapshot now two days old.

## EXECUTION PARAMETERS
- Directional bias: cash
- Entry trigger: NONE authorised — composite -1/4 sits inside the -2 to +2 stand-aside band, and the underlying price feed is stale for a second consecutive day, which independently rules out execution regardless of composite
- Take profit 1: n/a
- Take profit 2: n/a
- Hard invalidation: n/a
- Re-arm conditions: first, the MT5 bridge must push a fresh snapshot (it has now missed two consecutive mornings) so the ledger can be re-confirmed on live data; longs then need the composite to reach ≥+3 — e.g., DXY rolling over from its current higher-high structure and GDX/GDXJ stabilizing in tandem with a confirmed XAUUSD close above 3901.16; shorts need ≤-3 — e.g., XAUUSD losing 3852.47 and resuming toward/through 3831.76 while DXY extends and miners keep distributing. No high-impact print falls within the next 1-2 sessions, so no pre-event size reduction is separately mandated once the feed is restored.

## SOURCES
- `market_levels.json` (repo root) — MetaTrader5 / IC Markets Global, `generated_at_utc` 2026-11-17T06:55:02Z (stale, unrefreshed for a second consecutive morning as of this run)
- [Markets & the Fed: December 2026 meeting, jobs, CPI — what to watch](https://news.ifyouspent.com/en/news/fed-december-2026-meeting-jobs-cpi-what-to-watch) — confirms next FOMC Dec 8-9, next CPI Dec 10, 2026
- [December 2026 economic calendar: jobs Dec 4, FOMC Dec 9, CPI Dec 10](https://fxnx.com/en/blog/december-2026-economic-calendar-jobs-4-dec-fomc-9-dec-cpi-10) — corroborates NFP/FOMC/CPI dates, all outside the next 1-2 sessions

Price/structure from live MT5 feed (market_levels.json). Not investment advice.
