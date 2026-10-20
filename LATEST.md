# XAUUSD DAILY QUANTITATIVE ASSESSMENT - 2026-10-20 (Pre-London, 07:00 UTC)

## AT A GLANCE
| | |
|---|---|
| **Stance** | ⚪ STAND ASIDE — bearish-leaning composite, inside the no-execution band |
| **Composite** | -2 / 4 |
| **Confidence** | MODERATE — `market_levels.json` `generated_at_utc` is 2026-10-20T05:55:01Z, ~1h15m old (fresh), and the live XAUUSD bid (4,122.11) matches the H4/D1 bar closes exactly, so the gold/miner complex reads high-confidence. But DXY's live bid/ask field is broken (0.0/0.0, tick_time null) so that vote rests on D1 bar history alone, and USOIL remains fully absent from MT5 ("symbol not found") with no reliably-dated web quote found for Oct 17-20 either — two of four votes carry real data gaps, capping overall confidence at MODERATE. Note the h4/d1 bar timestamps in this file run a few hours ahead of true UTC (broker server time labeled "Z"), but they're internally consistent with the live tick, not a stale-bar artifact |
| **Current spot** | $4,122.11 bid (live MT5 tick) |
| **Level above** | 4,147.17 immediate failed-reclaim high (today's H4 sweep-back) · 4,199.06 Oct 16 D1 cycle high / overhead supply |
| **Level below** | 4,115.64 today's fresh H4 swept low / immediate support retest · 4,073.37 Oct 14 D1 cycle low / hard invalidation |
| **Why** | XAUUSD (-1) confirmed a structural breakdown with three straight lower-high/lower-low sessions; GDX/GDXJ (-1) confirms via a fresh GDXJ D1 low with no stabilization; DXY (0) and USOIL (0) stay neutral on broken/absent feeds, keeping composite short of confluence |
| **Watch today** | None within the next 1-2 sessions; next FOMC decision is Oct 27-28 (~5-6 trading sessions out) — outside the immediate window but the week's dominant risk for position sizing |
| **Vs yesterday** | Composite **-2 (stand aside) → -2 (stand aside)**: label and score unchanged, but vote composition flipped — XAUUSD worsened from 0 to -1 as the breakdown confirmed, while DXY improved from -1 to 0 as the feed showed range compression rather than confirmed expansion; GDX/GDXJ held at -1 and USOIL held at 0. Data quality also improved sharply: the MT5 bridge outage flagged in prior reports has resolved, moving confidence from LOW to MODERATE |

## DAILY 4-VOTE LEDGER
- 🔴 XAUUSD: confirmed DCH exhaustion (Oct 16 high 4,199.06) now mid-decline seeking a fresh DCL | Three straight lower highs (4,199.06 → 4,190.42 → 4,147.17) and lower lows (4,147.19 → 4,136.55 → 4,115.64); today's 04:00 UTC H4 bar swept to 4,115.64, reclaimed only briefly to 4,143.85, then rolled back to the current 4,122.11 bid with no broken swing low reclaimed | vote: **-1**
- ⚪ DXY: range-bound consolidation, no new D1 extreme since the Oct 5 high of 102.295 | Live bid/ask feed is broken (0.0/0.0, tick_time null); available D1 bars stay confined to a 101.56-102.30 band for three straight weeks, including today's bar (open 101.77, close 101.608) — compression, not confirmed expansion either way | vote: **0**
- ⚪ USOIL: cycle phase undetermined — feed and web both blind | MT5 `WTI_V6_CFD` mapping returns "symbol not found or no tick"; today's WebSearch produced no reliably-dated mid-to-late-October WTI price (only undated mirror pages and a September OPEC monthly average), so no distribution top or fresh impulsive low can be confirmed | vote: **0**
- 🔴 GDX/GDXJ: continued distribution, no cycle-low stabilization | GDXJ's live bid (108.65) is itself a fresh D1 low, printed below both the Oct 8 close (110.81) and the immediate post-crash Oct 7 close (109.15); GDX sits flat at its Oct 8 post-crash close (86.70 vs. 86.68) with no higher-low reclaim — miners offer no stabilization signal to counter gold's breakdown | vote: **-1**

**COMPOSITE SCORE: -2 / 4**
**STANCE: STAND ASIDE**

## RATIONALE
XAUUSD (-1) has moved from range compression into a confirmed breakdown: after topping at 4,199.06 on Oct 16, price has printed three consecutive declining sessions with progressively lower highs (4,199.06 → 4,190.42 → 4,147.17) and lower lows (4,147.19 → 4,136.55 → 4,115.64), including today's sweep to 4,115.64 that reclaimed only briefly to 4,143.85 before rolling back to the current 4,122.11 bid with no swing low reclaimed. DXY (0) is genuinely mixed: the live bid/ask feed is broken, but the available D1 history shows the index still confined to the same 101.56-102.30 band it has held for three weeks, with today's bar closing 101.608 — tight compression rather than directional expansion. USOIL (0) stays unscored: the MT5 WTI mapping remains fully broken and today's web search produced no reliably-dated quote for the Oct 17-20 window, so there is no basis to call a distribution top or a fresh impulsive low. GDX/GDXJ (-1) confirms gold's weakness rather than diverging from it: GDXJ's live bid is itself a fresh D1 low, below both its Oct 8 and Oct 7 post-crash closes, while GDX sits flat at its own post-crash close with no higher-low reclaim — miners offer no stabilization signal. Net composite is -2/4: bearish-leaning on a now-confirmed XAUUSD structural breakdown and continued miner distribution, but short of the -3/-4 confluence threshold because DXY and USOIL remain genuinely neutral/unscored, so no execution is sanctioned. The next FOMC decision (Oct 27-28) is still ~5-6 trading sessions out and outside the immediate 1-2 session window, but worth flagging for size discipline as the week progresses.

## VISUAL TRADE PLAN - PRICE LADDER (XAUUSD)
```
4199.06  ---  Oct 16 D1 cycle high / overhead supply
4147.17  ---  immediate resistance — today's H4 failed-reclaim high
4122.11 >>>   CURRENT SPOT (live MT5 bid)
4115.64  ---  immediate support retest — today's H4 swept low
4073.37  ---  hard invalidation — Oct 14 D1 cycle low / structural floor
```

## QUARTERLY THEORY SESSION CADENCE
- Q1 (06:00-07:30 UTC): asian range capture — today's own 04:00-08:00 UTC H4 bars already swept 4,115.64 and rejected back toward 4,122; expect the Asian range to keep probing this fresh-low zone as baseline liquidity forms.
- Q2 (07:30-09:00 UTC): judas swing — any push back toward 4,147.17 (today's failed-reclaim high) should be read as a liquidity run against the bearish-leaning composite into London, not a reversal signal; no entry is sanctioned while composite sits at -2/4.
- Q3 (09:00-10:30 UTC): true trend distribution — composite is bearish-leaning but not confluence-grade, so expect continued two-way chop around the 4,115-4,147 zone rather than a clean composite-aligned push lower.
- Q4 (10:30-12:00 UTC): terminal distribution — reassess the ledger once DXY's broken feed resumes a live tick or USOIL regains MT5/web coverage; a break and hold below 4,115.64 or a reclaim above 4,147.17 is the first structural tell for tomorrow.

## EXECUTION PARAMETERS
- Directional bias: cash
- Entry trigger: NONE authorised — composite (-2/4) sits inside the -2/+2 stand-aside band
- Take profit 1: n/a
- Take profit 2: n/a
- Hard invalidation: n/a
- Re-arm conditions: For a short (toward -3/-4): needs DXY to break above 102.295 (Oct 5 D1 high) once its live feed is restored, or USOIL to confirm a fresh impulsive daily-cycle low once feed/web data becomes available. For a long (toward +3/+4, i.e. the breakdown failing): needs GDX/GDXJ to post a confirmed cycle-low stabilization (a fresh D1 higher low, not a flat-to-lower print) and DXY to roll over with a confirmed lower structural high. Either way, DXY's live bid/ask (currently 0.0/null) should be confirmed working and USOIL's MT5 mapping fixed (or a reliably-dated web quote found) before either vote is trusted to move off 0. No FOMC/CPI/PPI falls within the next 1-2 sessions (next FOMC Oct 27-28), so no additional pre-event caution is needed beyond the standing stand-aside.

## SOURCES
- `market_levels.json` (repo root) — MetaTrader5 / IC Markets Global, generated_at_utc 2026-10-20T05:55:01Z
- [FOMC Meeting Schedule 2026](https://fedratecalc.com/fomc-meeting-schedule/) — confirms Oct 27-28 as the next FOMC decision date
- [XAUUSD awaits a decisive signal — RoboForex](https://roboforex.com/beginners/analytics/forex-forecast/gold/xau-usd-gold-forecast-2026-10-14/) — Oct 14 dollar/yields-vs-gold narrative context

Price/structure from live MT5 feed (market_levels.json). Not investment advice.
