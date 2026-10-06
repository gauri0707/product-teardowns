> **Machine-generated research.** Gathered automatically on 2026-10-06. Facts only,
> with sources. Nothing here is analysis — that belongs in `teardowns/`.

# Perplexity — Week 4, Tuesday (flow)

Week 4 of the calendar (Oct 5–9, 2026). Tuesday session = flow.

**Collection note:** `www.perplexity.ai` (help center) was blocked again this run — permission prompt unanswered in an unattended session, same as Monday. Everything below is third-party. The first-party onboarding copy is unverified; walk the live product yourself.

## The documented primary journey

The most detailed public teardown set is aiuxplayground's, updated mid-June 2026.

**Composer** — two mode chips sit on the bar at first load: **Search** (quick answers) and **Computer** (multi-step agentic work). Computer mode renames the model picker to "Orchestrator." File uploads and source toggles (Web, Academic) live behind a `+` menu, separate from the mode chips. Two voice-entry paths coexist: in-bar listening with confirm controls, and a full-screen orb. ([composer teardown](https://aiuxplayground.com/teardowns/perplexity/composer), 17 screens, updated 2026-06-16)

**Output** — tabbed Answer / Links / Images; research steps collapsed but expandable; contextual follow-up chips; per-answer export to PDF, Markdown, DOCX; rewrite modes (Search, Deep research, Learn step by step); highlight a passage to add a follow-up or check sources. ([output teardown](https://aiuxplayground.com/teardowns/perplexity/output), 18 screens, updated 2026-06-15)

**Citations** — five verification surfaces: inline domain chips with "+N" at claim endpoints, a favicon stack on the answer bar, chip popovers with 1/N navigation, a sources sidebar, and a Links tab. "Wrong sources" is a first-class feedback option, distinct from generic inaccuracy. ([citations teardown](https://aiuxplayground.com/teardowns/perplexity/citations), 16 screens, updated 2026-06-15)

### Friction those teardowns name
- Three routes to the same source list (popover, sidebar, Links tab) — ambiguous for first-timers
- Connector toggles give no bar-level feedback once armed; model pickers are "mostly lock icons" on free plans
- Research steps "easy to miss on fast scroll"; the selection menu appears only after you highlight text
- Model names ("Sonar") opaque without capability hints; bar placeholder copy shifts constantly
- No way to flag one specific failed citation from the feedback modal

## Signup / account friction

**Mandatory SMS 2FA, rolled out ~late April 2026.** Pro subscribers had to verify a phone number from the same region as their subscription — including users who already had 2FA on. Rollout was inconsistent (web blocked while mobile still worked, for some). The help center was quietly updated about a week before Apr 29 2026, citing security: "some users may be asked to verify their phone numbers before they can continue using the Perplexity app." No opt-out found. Deleting the account also requires phone verification. ([PiunikaWeb](https://piunikaweb.com/2026/04/29/perplexity-demands-phone-numbers-pro-subscribers/), 2026-04-29, sourcing r/perplexity_ai; [i10x](https://i10x.ai/news/perplexity-ai-mandates-phone-2fa-pro-subscribers-backlash) headline corroborates, contents unverified)

Still surfacing a month later: "They did a system update and now required mobile SMS verification…Support refused to help" — blair F., Owner, 2026-05-24 ([Capterra](https://www.capterra.com/p/10014721/Perplexity/reviews/)).

## Review-site signal — the split is stark

| Source | Rating | n | Accessed |
|---|---|---|---|
| Apple App Store (US) | 4.8 | 512K ratings | 2026-10-06 |
| [Capterra](https://www.capterra.com/p/10014721/Perplexity/reviews/) | 4.2 | 35 reviews | 2026-10-06 |
| [Trustpilot](https://www.trustpilot.com/review/www.perplexity.ai) | 1.4 TrustScore (83% one-star) | 825 reviews | 2026-10-06 |

Nearly four stars apart. The populations are almost certainly different — billing-dispute self-selection versus install base — but nothing found reconciles them.

Recurring complaints by surface:

- **Billing and cancellation** (dominant on Trustpilot): unexpected charges, auto-renewal without consent, difficulty cancelling. "They took your payment, refuse to resolve the complaint, and then tell you there is nobody else you can speak to" (2026-09-09)
- **Credits exhausted mid-month** on Pro, requiring top-up purchases (Trustpilot)
- **Support entirely automated**, no human escalation; "complete silence for 2 weeks" — Melad K., Student, 2026-04-06 (Capterra)
- **Answer flow**: run-to-run inconsistency ("Sometimes you feel the agent is totally aligned… Some other times it seems sluggish" — José Javier F., 2026-04-24); too many sources on simple queries, too few on hard ones; manual cross-checking still needed (Capterra)
- **Mobile tap target**: full-width suggested-question buttons catch accidental taps while scrolling and replace the thread, "no option to turn that setting off" ([App Store](https://apps.apple.com/us/app/perplexity-ai-search-chat/id1668000334) review, 2025-02-27 — 19 months old, verify it still reproduces)

Latest iOS build **26.39.0**, released 2026-10-05; notes read only "Bug fixes and improvements."

## Comet first-run

- The assistant panel docks right at launch, taking roughly half the screen: "the assistant snapped onto the right side of the screen and refused to move." No minimize or resize found; the writer uninstalled after five minutes ([globalmarketsx](https://globalmarketsx.substack.com/p/i-just-tried-perplexity-comet-and), 2025-10-08 — a year old, likely stale)
- 15–20% more RAM than Chrome; Gmail/Google features need "extensive account access" ([AI Central](https://aicentral.substack.com/p/perplexitys-comet-browser-impressive), 2025, exact date not stated)
- Assistant scroll position not preserved across tab switches — "I have to scroll down again" (2026-03-30). A moderator closed the thread 2026-04-07: the public forum is API-only, consumer feedback goes to support.perplexity.ai ([community.perplexity.ai](https://community.perplexity.ai/t/perplexity-assistant-in-comet-update/4422))
- A published Comet onboarding walkthrough with timed steps: **not found**.

## Three questions today's session should answer

1. Five ways to reach the same source list, plus a first-class "wrong sources" button — is verification something users actually perform, or theatre that makes an answer feel checkable without being checked? What would you measure to tell those apart?
2. The two loudest friction points in this product aren't in the answer at all: a phone number demanded to log in *and* to delete, and a cancellation path people take to Trustpilot instead of support. Deliberate (fraud and credit abuse control) or neglect — and what evidence would settle it?
3. Search vs. Computer is a decision forced before the first word is typed, while the capability behind it is a lock icon on the free plan. Does that mode chip teach the product or gate it?
