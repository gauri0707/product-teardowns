> **Machine-generated research.** Gathered automatically on 27 October 2026. Facts only,
> with sources. Nothing here is analysis — that belongs in `teardowns/`.

**Week 7 · Zerodha / Kite · Tuesday (flow).** Calendar slot Oct 26–30, 2026 — on schedule.

---

## The documented signup path (primary)

Zerodha's own step list, [support.zerodha.com — online account opening](https://support.zerodha.com/category/account-opening/resident-individual/ri-online/articles/what-documents-do-i-need-to-open-an-account), fetched 27 Oct 2026. **14 numbered steps:** mobile + OTP → email + OTP → PAN and DOB → segment selection + T&C → Aadhaar KYC (Aadhaar no., OTP, captcha, 6-digit DigiLocker PIN) → personal details → bank linking (UPI or manual) → IPV (live camera capture) → signature (draw or upload) → nominee (optional, "can do it later") → e-sign (Aadhaar OTP + DigiLocker PIN again) → upload bank proof (if manual) or income proof (if F&O).

Gates and timings stated on that page:

- **Four separate OTP/PIN challenges**: mobile, email, Aadhaar+DigiLocker at KYC, Aadhaar+DigiLocker again at e-sign.
- Online path requires a **resident Indian whose mobile is linked to Aadhaar**; otherwise offline only.
- **User ID appears as soon as forms are signed. Account opens "within 48 working hours."** Orders can be placed only "once exchanges activate the account."
- **F&O requires income proof** — salary slip above ₹15,000/month gross, or ITR/Form 16 above ₹1,20,000/year.
- E-sign name must match the Aadhaar name or the forms are rejected.

## Deliberate friction inside the order path (primary)

- **Limit orders far from LTP are rejected** — blocked 50%–150% away from LTP (buy 150% above, sell 50% below); not applied when LTP is under ₹100. Stated reason: preventing "freak trades"; suggested workaround is GTT. Options with both LTP and OI at zero are blocked outright. ([support.zerodha.com](https://support.zerodha.com/category/trading-and-markets/alerts-and-nudges/kite-error-messages/articles/limit-orders-far-away-from-ltp-are-rejected), fetched 27 Oct 2026)
- **Order slicing**: orders above exchange freeze limits auto-split — Nifty up to **50 slices × 1,800 qty = 36,000** — brokerage charged per executed slice. **Market Protection** converts market orders to limit at a band edge (2% for equities/futures under ₹100). Available margin and 5/20 depth now sit inside the order window; **"Remember F&O quantity"** is opt-in in profile settings. ([Z-Connect](https://zerodha.com/z-connect/featured/order-placement-simplified), 25 Mar 2025)
- **Nudge v2**, announced **23 Sep 2026**: from warnings to "allowing you to set hard limits to stay disciplined." No limit types, thresholds or mechanics published. ([Z-Connect](https://zerodha.com/z-connect/updates/coming-soon-nudge-v2))

## Complaints on the core order flow (Zerodha's own forum)

- **New mobile order window**, thread opened **4 Sep 2026**: the partial window "places the buy/sell buttons at the bottom of the screen, which gets hidden behind the keyboard"; the poster dismisses the keyboard before every order, says it "completely ruined my muscle memory," and asks for a setting to restore the old fullscreen window. On tablets at reduced zoom it becomes a draggable box that always reopens at the bottom. Zerodha's reply (5 Sep 2026): **"No UI changes are planned"** — citing accessibility and regulatory alignment, offering only to review whether older elements can be kept. ([tradingqna.com](https://tradingqna.com/t/the-new-order-window-is-very-inconvenient/197764))
- **Lot-vs-quantity default**, thread from 25 Jul 2025, still live **22–23 Jan 2026**: the overlay "holds the last order placement state." Nithin replied that remembering last state "has been a popular feature for over a year"; siva clarified F&O remembers last size per underlying while equity defaults to 1. On 22 Jan 2026 the poster reported a **~₹1,80,000 loss** after 35,000 Nifty quantity went in with LOT selected instead of Quantity, and asked for a user-level default-to-quantity setting; siva said it would be passed on. *User-claimed loss, unverified; no change announced.* ([tradingqna.com](https://tradingqna.com/t/ui-changes-in-kite-causing-huge-trading-impact/184676))
- Google Play, [com.zerodha.kite3](https://play.google.com/store/apps/details?id=com.zerodha.kite3&hl=en_IN), fetched 27 Oct 2026: **4.5 stars, ~3.94 lakh ratings, 1 crore+ downloads, updated 25 Aug 2026.** Review of 19 Jul 2026: GTT orders "often reject or restrict small stop-losses based on percentage or price conditions," no simple way to set an exact SL and target.

## Secondary sources (claims, not measurements)

- [Groww vs Zerodha onboarding](https://productgrowth.in/insights/fintech/groww-vs-zerodha-onboarding/) (Oct 2025, upd. Jun 2026): Groww **2 signup fields / 3-min KYC goal** vs Zerodha **"5+ fields with strictness" / 5–7 min KYC**; Groww lands on a ₹0 portfolio with a ₹100 SIP CTA, Zerodha on the full Kite terminal. No funnel data — the times are a target and an estimate.
- A 2022 [Kite onboarding teardown](https://shubhambrnw.medium.com/zerodha-kite-onboarding-teardown-535c4568a985) surveyed account-opening-to-first-purchase time: **<1 day 16.7%, <1 week 25%, ~15 days 16.7%, ~1 month 41.7%** (n claimed 15, percentages imply 12).
- **Reliability during the core loop:** an aggregator ([multibagg.ai](https://www.multibagg.ai/market-pulse/articles/zerodha-kite-outage-reliability-cmttvzaor000e2mn0cx2ruz74), ~9 Sep 2026) lists 3 Sep 2025, 5 Dec 2025 (Cloudflare, multi-broker) and 3 Feb 2026 (~09:15–09:42, margins not loading in the order window); no primary sources linked, AI disclaimer attached. One primary artefact: Zerodha telling users to fall back to Kite web on mobile during a price-update failure, "Order placement is not affected" ([@zerodha on X](https://x.com/zerodha/status/1963094614161715610), Sep 2025).

**Not found:** any Zerodha-published funnel, drop-off or activation figures; median time-to-first-trade; the realised distribution behind the "48 working hours" promise; Nudge v2 mechanics; iOS App Store ratings; G2 review volume for Kite.

---

## Three questions today's session should answer

1. Signup is 14 steps and four OTP/PIN challenges, and the first order waits on exchange activation up to 48 working hours after signing — so "time to first value" is two numbers, not one. Which belongs in the walkthrough, and which steps are regulatory floor versus Zerodha's own choice?
2. The order window's memory of last F&O quantity and lot-vs-qty is both the "popular feature" Nithin defends and the mechanism in a claimed ₹1.8 lakh fat-finger loss. Is persistent order state friction-removal for the heavy trader or an un-owned default — and which user is that window designed for?
3. Zerodha answered the September complaints with "No UI changes are planned," citing accessibility and regulation, while announcing Nudge v2 hard limits the same month. How does this teardown tell friction added for compliance or protection apart from friction that's simply unexamined?
