> **Machine-generated research.** Gathered automatically on 2026-10-05. Facts only,
> with sources. Nothing here is analysis — that belongs in `teardowns/`.

# Perplexity — Week 4, Monday (brief)

Week 4 of the calendar (Oct 5–9, 2026). Monday session = brief.

**Collection note:** `www.perplexity.ai` (homepage, pricing page) could not be fetched this run — the permission prompt went unanswered in an unattended session. `docs.perplexity.ai` was reachable. Pricing and positioning below are secondary and flagged as such; verify against the live page during the session.

## Positioning, in their words

- Homepage headline and pricing-page wording: **not verified this run** (fetch blocked, see note).
- The one primary-sourced statement of intent found is about advertising. Perplexity told the *Financial Times* it was winding down its ad program by end of 2026, about a year after launching it in Nov 2024. An unnamed executive: **"A user needs to believe this is the best possible answer"**; another said ads risk making users **"suspicious of everything."** Taz Patel, who led the ads effort, left before it concluded. ([Campaign](https://www.campaignlive.com/article/perplexity-pulls-plug-ads-citing-trust-concerns-ai/1949142), 2026-02-20, reporting FT)

## Pricing (secondary — unverified against the primary page)

| Tier | Price | Notes |
|---|---|---|
| Free | $0/mo | Cited answers, basic models, limited daily usage |
| Pro | $20/mo | Top models, deep research, 4,000 bonus credits |
| Max | $200/mo | Frontier models, 10,000 monthly + 35,000 bonus credits, Model Council, Brain |
| Enterprise Pro | $40/user/mo | Pro + admin controls, central billing |
| Enterprise Max | $325/user/mo | Max + SCIM, audit logs |
| Comet Plus | $5/mo | Publisher content bundle (see below) |

([CloudZero](https://www.cloudzero.com/blog/perplexity-pricing/), 2026-09-21.) CloudZero says annual Pro is reported "near $200 a year" but that Perplexity's public page shows **only monthly** pricing. Comet browser itself is free across all plans; API is billed separately.

**Comet Plus publisher split:** $5/mo, with **80% of subscription revenue to publishers** and 20% retained for compute, drawn initially from a **$42.5M revenue pool**. ([Engadget](https://www.engadget.com/ai/perplexity-has-cooked-up-a-new-way-to-pay-publishers-for-their-content-204255019.html), 2025-08-25)

## Funding / valuation — sources disagree

- **$500M round, ~$14B valuation**, June 2025; **~$20B** by Sept 2025 ([Wikipedia](https://en.wikipedia.org/wiki/Perplexity_AI), accessed 2026-10-05). A **$200M round at $20B** (Sept 2025, Reuters-sourced), **total funding $1.22B** ([Panto](https://www.getpanto.ai/blog/perplexity-ai-statistics), 2026-08-07).
- **Early 2026: "Series E-6" to $21.21B** ([Wikipedia](https://en.wikipedia.org/wiki/Perplexity_AI)) vs **$22.6B in January 2026** and **"~$20B, June 2026 raise"** ([AI Business Weekly](https://aibusinessweekly.net/p/perplexity-ai-statistics), updated 2026-08-01). These do not reconcile, and no primary announcement of a 2026 round was found.

## Scale, revenue, headcount — sources disagree

- **ARR:** ~$100M early 2025 → ~$200M late 2025 → **>$450M March 2026**, with $656M targeted for year-end 2026 ([Panto](https://www.getpanto.ai/blog/perplexity-ai-statistics); [AI Business Weekly](https://aibusinessweekly.net/p/perplexity-ai-statistics)). [getlatka](https://getlatka.com/companies/pplx.ai) lists **$500M ARR**. Company-confirmed ARR: **not found**.
- **Users:** **~45M MAU** mid-2026 vs **"surpassed 100M MAU" across all products**, attributed to the *Financial Times* — a two-fold conflict, possibly a definitional one ([AI Business Weekly](https://aibusinessweekly.net/p/perplexity-ai-statistics); [Panto](https://www.getpanto.ai/blog/perplexity-ai-statistics)). 80.5M lifetime app downloads.
- **Queries:** last CEO-sourced figure is **780M/month, May 2025**, ~30M/day, +20% MoM ([Wikipedia](https://en.wikipedia.org/wiki/Perplexity_AI)). Estimated **1.2–1.5B/month** mid-2026 (Stan Ventures via [AI Business Weekly](https://aibusinessweekly.net/p/perplexity-ai-statistics)).
- **Headcount: 247**, MoM −12.41%, YoY +325.3% ([Crustdata](https://profiles.crustdata.com/company/perplexity-ai), Sept 2026). Measurement method is a data-vendor estimate, not a company figure. Wikipedia's only number is 52 (2024). Official headcount: **not found**.
- **Paid subscriber count:** not found in any source checked.
- **Revenue effect of the ads exit:** "Revenue jumped 50% the month after Perplexity abandoned advertising entirely in February 2026" — single secondary source, uncorroborated ([AI Business Weekly](https://aibusinessweekly.net/p/perplexity-ai-statistics)).

## Shipped in the last 90 days

Product releases ([Releasebot](https://releasebot.io/updates/perplexity-ai), accessed 2026-10-05):

- **Sep 21** — Effort Mode (Light/Standard/High/Ultra) for Computer; Portable Computer for Windows/Linux with local execution; Hybrid Computer for Mac; Skills Marketplace; enterprise analytics API
- **Aug 24** — Computer in Email; Search as Code reliability to 92.6%; Perplexity Search SDK; connector approval controls
- **Jul 27** — Enterprise RBAC; Brain memory to all Max subscribers globally; Check Sources; Source Context Panel
- **Jul 13** — Brain self-improving memory; website publishing to pplx.app or custom domains; private-company research via Forge Global

API side, primary source ([docs.perplexity.ai](https://docs.perplexity.ai/docs/agent-api/migrate-from-sonar/overview)): **Sonar Chat Completions support ended September 27, 2026.** Sonar tiers now map onto Agent API presets (Sonar/Sonar Pro → `fast`, Reasoning Pro → `low`, Deep Research → `high`/`xhigh`); async requests are no longer supported. "Fast Search" launched Sept 2026 at **$1.00 per 1,000 requests**; GPT-5.x variants retire **Oct 24, 2026** ([changelog](https://docs.perplexity.ai/docs/resources/changelog)).

Earlier 2026 context: Perplexity Computer (Feb), Personal Computer for Mac (Apr), for Windows (Jul) ([Wikipedia](https://en.wikipedia.org/wiki/Perplexity_AI)).

## Three questions today's session should answer

1. Six tiers from $5 to $325, and the $5 one pays 80% straight back out to publishers — is Comet Plus a revenue line, or a content-licensing cost wearing a subscription's clothes?
2. Every outside number comes in two incompatible versions (45M vs 100M+ users, $20B vs $22.6B, $450M vs $500M ARR) and the last CEO-sourced usage figure is 17 months old — which single number would most change your read, and is its absence a choice?
3. Ninety days of shipping is almost entirely Computer, Brain, Skills and local execution, while the API retired Sonar to resell other labs' frontier models. If the answer engine is now a funnel for an agent product, what does Perplexity own underneath it?
