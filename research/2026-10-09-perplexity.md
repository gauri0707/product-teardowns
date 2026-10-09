> **Machine-generated research.** Gathered automatically on October 9, 2026. Facts only,
> with sources. Nothing here is analysis — that belongs in `teardowns/`.

**Week 4 · Perplexity · Friday "ship" session.** Scope for today per the loop: the week's biggest product news, plus anything that would date the analysis written Mon–Thu.

---

## What shipped this week (Sep 28 – Oct 9)

**Oct 7 — Two open-weight multimodal embedding models, `pplx-embed-v2-late`.** A 0.6B "edge" model and a 9B model, both published on Hugging Face under the MIT licence. Reported benchmarks for the 9B: 92.4% on MADQA (500 questions over ~18,000 PDF pages), 64.0% on BrowseComp+ paired with GPT-OSS-120B, 74.8% Recall@1000 on Q2D-Web (~190M documents), 65.2% on ViDoRe v3 image retrieval. The two models share one embedding space, so an index built with the 9B can be queried with the 0.6B. Hosted API access is described as "forthcoming" — no price announced. Perplexity's own write-up the same week is "Multimodal embeddings beyond a single vector" (Oct 7). ([aiweekly.co, Oct 8, 2026](https://aiweekly.co/alerts/perplexity-open-sources-pplx-embed-v2-late-924-on-madqa); [Perplexity blog index](https://www.perplexity.ai/hub/blog))

**Oct 5 — Automations, inline visualizations, GPT-6.1 Sol in Computer.** Automations run ongoing work on a schedule or on events in connected apps, can use Memory, Skills and connectors, and can pause for review before consequential actions. Inline visualizations add interactive charts and 3D explanations in Computer threads; financial charts use TradingView Lightweight Charts. GPT-6.1 Sol went to eligible paid subscribers and powers Light effort mode. A Perplexity post titled "Computer adds Automations for ongoing work" is dated Sep 29, so the feature appears to have been posted before the consolidated release note. ([Releasebot changelog, Oct 5, 2026](https://releasebot.io/updates/perplexity-ai); [Perplexity blog index](https://www.perplexity.ai/hub/blog))

**Oct 6 — Rings AI connector in Computer.** Team relationship data (who knows whom, relationship strength, past firm activity, open opportunities) available in the connector catalogue for Pro, Max, Enterprise Pro and Enterprise Max. Included at no extra charge with every Rings plan. ([PR Newswire, Oct 6, 2026](https://www.prnewswire.com/news-releases/rings-ai-and-perplexity-partner-to-bring-team-relationship-intelligence-into-perplexity-computer-302899876.html))

**Oct 1 — American Express business Skills.** Ten prebuilt Skills for Computer (cash-flow forecasting, tax prep, vendor benchmarking, scenario planning, reconciliation, campaign generation, demand forecasting, channel ROAS, ops monitoring, hiring). Eligibility: U.S. Amex Business Card Members with an active Perplexity **Enterprise** subscription who link their card via Plaid. Running Skills consumes Computer Credits; no dollar price, credit allotment or card-member count disclosed. ([Perplexity blog, Oct 1, 2026](https://www.perplexity.ai/hub/blog))

**Sep 28 — Agent API now supports reusable agents.** ([Perplexity blog index](https://www.perplexity.ai/hub/blog))

---

## Things that could date Mon–Thu's analysis

**Pricing — not verified from primary this run.** Perplexity's own pricing page could not be retrieved in this run. Best secondary figures, verified by the author against Perplexity's plans page in September 2026: Free $0; Pro $20/mo; Max $200/mo; Enterprise Pro $40/user; Enterprise Max $325/user. The same source says Perplexity does not publish annual pricing, and that third-party reports of ~$200/yr for Pro are unverified. ([CloudZero, Sep 21, 2026](https://www.cloudzero.com/blog/perplexity-pricing/)) **Treat as of September, not of today.**

**Publisher economics figures in circulation are over a year old.** The widely cited numbers — Comet Plus at $5/mo, an 80/20 split to publishers, a $42.5M first-phase pool, building on a Gannett deal — come from August 2025 reporting. No newer primary confirmation found for this run. ([TVNewsCheck, Aug 27, 2025](https://tvnewscheck.com/business/article/perplexitys-comet-plus-has-different-revenue-strategy-same-publisher-problem-will-it-work-this-time/); [Fortune, Aug 26, 2025](https://fortune.com/2025/08/26/perplexity-lawsuits-publishers-ai-search-nikkei-news-corp/))

**Legal posture shifted in August 2026 and has not been revisited since.** On Aug 4, 2026 the Ninth Circuit held that Perplexity does not "access" Amazon's computers under the CFAA or California's CDAFA — the *user*, not the agent or its developer, is the one accessing — and vacated the preliminary injunction that had barred Comet users from the Amazon Store. The ruling is narrow and does not reach other theories such as tort claims. Separate copyright suits (News Corp, Nikkei, Reddit, Forbes, Condé Nast have all been reported as disputing parties) are not resolved by it. ([Wilson Sonsini, Aug 7, 2026](https://www.wsgr.com/en/insights/ninth-circuit-addresses-cfaa-and-agentic-ai-tools-in-groundbreaking-decision.html))

**Valuation and revenue: sources disagree, no primary confirmation.** Wikipedia's funding table gives $14B (Jun 2025), ~$20B (Sep 2025), and $21.21B after a Series E-6 in early 2026, and flags a three-year $750M Azure GPU commitment (Jan 2026) as needing a citation. Secondary trackers variously cite $20B valuation with ~$200M ARR and ~$450M ARR in the same period. **Do not use an ARR number in the case study without a primary source — none was found.** ([Wikipedia, retrieved Oct 9, 2026](https://en.wikipedia.org/wiki/Perplexity_AI))

**Headcount:** not found for 2026. Wikipedia's only figure is ~52 employees in 2024.

---

## Three questions today's session should answer

1. The week's two biggest moves point in opposite directions — open-weighting the retrieval stack under MIT, and locking the Amex Skills behind an *Enterprise* subscription. Which of those is the actual revenue thesis the case study argues, and does the other one undercut it?
2. Computer's shift from answers to scheduled, event-triggered work changes the billing unit from a query to a credit. Does the Wednesday model still hold if the metered unit is agent-minutes rather than searches — and if not, which claim has to be rewritten rather than caveated?
3. The Ninth Circuit removed a *distribution* risk (agents may visit sites) without touching the *input* risk (copyright). Which of those two was load-bearing in the Monday brief's "unsolved publisher problem" framing, and does the case study need to split them?
