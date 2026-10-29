> **Machine-generated research.** Gathered automatically on 2026-10-29. Facts only,
> with sources. Nothing here is analysis — that belongs in `teardowns/`.

**Week 7 · Zerodha / Kite · Thursday — Proposal session.**

## The loudest recurring complaint: reliability

- **3 Feb 2026.** DownDetector reports began ~08:00 IST, peaked above **250** around 09:10 IST, fell to ~7 by 10:40 IST. Users reported blank holdings, network errors and blocked trades while trying to open or close positions, during the rally that followed the India–US trade deal. Zerodha replied to individual posts on X but issued **no official statement**; cause not disclosed ([Inc42, 3 Feb 2026](https://inc42.com/buzz/zerodha-users-complain-of-glitches-amid-market-rally-after-india-us-trade-deal/)).
- Same incident, user-reported detail (TradingQnA, 3–5 Feb 2026): an order placed at 9:15 failed, was cancelled and re-placed, then executed late; **market depth and LTP frozen for ~6 minutes** after an execution, in both equity and F&O; option chain slow to refresh. Zerodha's bulletin acknowledged a **margin-display problem in the Kite order window** (4 Feb) and an RCA was promised in-thread. Several users asked Zerodha for a **public status page**; one asked that Kite work on Android 12 and older devices ([tradingqna.com/t/zerodha-glitches/191060](https://tradingqna.com/t/zerodha-glitches/191060)).
- Secondary log, self-described as not exhaustive: 3 Feb 2026 (margin fetch, positions, fund additions, 09:15–09:42); 5 Dec 2025 (Cloudflare outage — hit Zerodha, Groww **and** Angel One); 3 Sep 2025 (delayed price updates near open) ([Multibagg, 9 Sep 2026](https://www.multibagg.ai/market-pulse/articles/zerodha-kite-outage-reliability-cmttvzaor000e2mn0cx2ruz74)).
- Precedent for the accountability question: the **BSE Grievance Redressal Committee ordered Zerodha to pay ₹8,225** for a 7 Jul 2023 glitch, finding it took no corrective action after an exchange alert that bandwidth use passed 70%. COO Venu Madhav called the 70% finding a "blatant mistake", disputed the cause, and said Zerodha "has a mandate to assess and refund legitimate losses" ([Inc42, 13 Oct 2023](https://inc42.com/buzz/bse-committee-blames-zerodhas-inaction-for-tech-glitch-brokerage-terms-order-blatant-mistake/)).

## The regulatory floor changed in January

SEBI circular **HO/38/44/12(1)2026-MIRSD-TPD1, 9 Jan 2026**, effective immediately, superseding the 25 Nov 2022 framework ([summary](https://taxguru.in/sebi/sebi-revamps-technical-glitch-rules-to-ease-broker-compliance.html); [circular PDF](https://www.cse-india.com/upload/upload/Jan_092026_2.pdf)):

- A "glitch" = malfunction affecting trading or risk-management functions for a **contiguous five minutes or more**.
- **Explicitly excluded:** cloud or global-provider disruptions, MII-side issues, new-account KYC, back-office issues not affecting trading/settlement, payment-gateway failures, and **decision-support tools such as charts and P&L statements**.
- Applies to brokers with **>10,000 registered clients**.
- Notify exchanges *and clients* within **2 hours** (was 1 hour); preliminary report T+1; **RCA within 14 working days**; filed via "Samuhik Prativedan Manch".
- **No financial disincentive** when only one mode (app or web) fails while the other works, or for "minor" glitches — exchanges to define minor.

## Feature requests: mostly shipped

Request thread, **16 Apr 2026**: one-tap order execution; order placement from charts; a "super order" with built-in trailing SL; smoother in-app TradingView charts. Staff (Swapneel_Dey) replied the same day that chart trading and trailing SL were already in progress, and on 16 Jun that "TSL in GTT is currently available in beta" and "TFC on the app is presently under testing" ([thread](https://tradingqna.com/t/feature-request-one-tap-orders-chart-trading-trailing-sl-in-kite/193285)).

Shipped since, from Zerodha's own changelog ([zerodha.com/z-connect](https://zerodha.com/z-connect/category/kite/feed)): Terminal Mode (18 Mar), new marketwatch on app (25 Mar), TSL-in-GTT beta (15 May, [announcement](https://tradingqna.com/t/introducing-trailing-stop-loss-in-gtt-orders-on-kite-beta/194095)), position grouping (27 May), **Trailing Stoploss on Kite web (23 Jun)**, **Screener on Kite web (15 Jul)**, Stock SIP (7 Aug), **Trade from Charts in the app (4 Sep)**.

Still open: **one-tap execution** (acknowledged, no ship found); **percentage-based** trailing SL — "Kite only allows for a fixed-point trailing stop-loss", which a trend-follower argues breaks as price rises ([10 Jul 2026](https://tradingqna.com/t/feature-request-true-percentage-based-trailing-stop-loss-tsl-on-kite/195786), no staff reply visible); public status page; older-Android performance.

## What competitors already do

- **Angel One** shipped TradingView integration **free to all clients** — order placement from charts, drag to modify stop-loss and target — announced **9 Jul 2026**, i.e. ~2 months before Kite's in-app TFC ([angelone.in](https://www.angelone.in/news/product-updates/angel-one-integrates-tradingview-access-for-clients-here-is-what-the-new-trading-setup-includes)).
- **Dhan** is claimed to offer chart execution, a screener, an options strategy builder with payoff graph and margin preview, iceberg and draft orders, overtrading-and-loss alerts, and margin release ~4 PM on expiry day. Source is affiliate-promotional and uncited — **verify before using** ([Moneycontain, 26 Jan 2026](https://moneycontain.com/dhan-vs-zerodha-active-traders/)).
- **Public status page:** none found for Zerodha, Groww, Upstox, Angel One or Dhan. Traders rely on third parties (DownDetector, [downrightnow.in](https://downrightnow.in/trading), StatusGator).

## Complaint volume (treat as unverified)

Aggregated exchange disclosures: NSE complaints **734 in FY26** (~0.11 per 1,000 clients), 1,075 in FY25, 378 in FY27 to date; BSE 22, 223, 8 ([Chittorgarh](https://www.chittorgarh.com/broker-complaints/zerodha/18/)). That page's "last updated" date (Oct 2024) predates the figures it carries — **do not cite without a primary check**.

**Not found:** any Zerodha-published uptime or downtime figure; a Zerodha public status page; monthly complaint data from a primary exchange source; confirmation that an RCA was filed for 3 Feb 2026; a written Zerodha compensation policy.

## Three questions today's session should answer

1. Every ask in the April request thread shipped inside five months — chart trading, trailing SL, screener — while the complaint users repeat loudest, reliability and what happens afterwards, produced no shipped artefact. Is that a roadmap choice, or evidence that reliability isn't ownable as a *product* bet? If you propose it anyway, what is the shippable thing: a status page, an RCA commitment, or an automatic compensation rule?
2. Every symptom users reported on 3 Feb — frozen LTP, stale market depth, blank holdings, app-only failure — sits at or inside SEBI's January exemptions (charts and decision-support tools excluded, no disincentive when one mode works, two hours to notify). Does a proposal that beats that floor buy a trader anything they can feel, or is it compliance theatre with better copy?
3. Angel One put order-from-chart in front of every client, free, two months before Kite did. If the feature gap now closes in weeks, which part of Kite is actually load-bearing for retention — and should the proposal aim at the thing a competitor *can't* copy in a quarter instead?
