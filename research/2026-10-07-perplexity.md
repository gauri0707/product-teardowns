> **Machine-generated research.** Gathered automatically on 2026-10-07. Facts only,
> with sources. Nothing here is analysis — that belongs in `teardowns/`.

# Perplexity — Week 4, Wednesday (model)

Week 4 of the calendar (Oct 5–9, 2026). Wednesday session = model.

**Collection note:** first-party pricing pages were unreachable again this run — `www.perplexity.ai` (pricing, help centre), `docs.perplexity.ai`, `openai.com` and `claude.com` all returned unanswered permission prompts in an unattended session. Every price below is secondary. Monday's file already carries the tier table; this file goes at the mechanics, the cost side and the margin dispute.

## The metric they price on: credits

Credits meter **Computer** (the agent), not search. Allocation is asymmetric: **Pro $20/mo gets a one-time 4,000-credit bonus and no recurring monthly grant; Max $200/mo gets 10,000 credits every month plus a 35,000 one-time bonus.** One credit ≈ **$0.01** (500 credits ≈ $5).

Observed consumption per task: **~31 credits** for a quick lookup or small file edit, **50–70** for multi-source research, **100+** for scheduled automations. The sharp edge is thread length — an identical SEO audit cost **40 credits in a fresh thread and 200–320 credits at message 50**, a 5–8× multiplier for the same requested work. ([karozieminski](https://karozieminski.substack.com/p/perplexity-computer-pricing-credits-2026), last verified 2026-06-12 — secondary, pre-dates the Sept Effort Mode release)

Max carries a **default $200 monthly spend cap, adjustable to $5,000** ([CloudZero](https://www.cloudzero.com/blog/perplexity-pricing/), 2026-09-21). Whether Sept's Effort Mode (Light/Standard/High/Ultra) changes the credit rate per task: **not found**.

## Revenue lines other than subscriptions

- **API:** ~$1 per million tokens plus per-request search fees on prepaid credits; Fast Search at **$1.00 per 1,000 requests** (Sept 2026). ([CloudZero](https://www.cloudzero.com/blog/perplexity-pricing/); docs changelog via Monday's file)
- **Comet Plus, $5/mo:** **80% of revenue to publishers, 20% retained for compute**, from a **$42.5M** pool. ([Axios](https://axios.com/2025/08/26/perplexity-comet-plus-subscription), 2025-08-26)
- **Commerce:** the Merchant Program "sets fees, commissions, and listing charges all at zero," explicitly contrasted with OpenAI's **4%** transaction fee on ChatGPT Instant Checkout ([stellagent](https://stellagent.ai/insights/perplexity-shopping-buy-with-pro), 2026-04-05; OpenAI's 4% corroborated by [eCommerceNews](https://e-commerce.news/story/openai-to-charge-4-fee-on-shopify-chatgpt-checkout)). A PayPal agentic-commerce partnership exists ([AI Business](https://aibusiness.com/generative-ai/paypal-perplexity-team-for-ai-powered-commerce)); whether any revenue flows to Perplexity from it: **not found**.
- **Ads:** wound down by end of 2026 (see Monday's file). So the one line with a positive marginal rate is deliberately set to zero and the other was switched off.

## Cost side

**Microsoft Azure: $750M, three years, signed Jan 29 2026** — a committed spend, not pay-as-you-go ([Bloomberg](https://bloomberg.com/news/articles/2026-01-29/perplexity-inks-microsoft-ai-cloud-deal-amid-dispute-with-amazon); [DCD](https://www.datacenterdynamics.com/en/news/perplexity-signs-750m-cloud-agreement-with-microsoft/)). Straight-lined that is ~$250M/yr against ARR estimates of $450–750M. Model inference is bought in — the API now resells other labs' frontier models (Monday's file).

## The margin dispute — the central unresolved fact

*The Information* reviewed internal documents and reported that Perplexity classified **free-tier and trial-user costs as R&D rather than cost of revenue**. End-2024: **$63M ARR**, **at least $57M** on AI models and services, of which **$33M served non-paying users**. Reclassified, the reported **60% gross margin becomes negative gross profit**. ([The Deep Dive](https://thedeepdive.ca/did-perplexity-fudge-its-numbers/), 2025-05-20, summarising [The Information](https://www.theinformation.com/articles/google-challenger-perplexity-growth-comes-high-cost) — paywalled, figures not independently verified)

2024 full year: **~$34M revenue, ~$65M losses**. Outside gross-margin estimates range **40% to 70%**, "a wide spread and all unverified"; revenue-to-valuation ≈ **44×**. Paying-subscriber count and unit economics are **undisclosed**. ([penchan](https://penchan.co/en/market/ai/perplexity/perplexity-valuation/), 2026-06-01)

**Sources disagree on current revenue:** $450M annualised (Mar 2026), $500M, and **$750M annualised as of Aug 2026 with $232M at end-2025** ([Sacra](https://sacra.com/c/perplexity/), through Aug 2026; [getlatka](https://getlatka.com/companies/pplx.ai)). No company-confirmed figure found. Any 2026 restatement of the margin question: **not found**.

## Competitor pricing, for comparison

| Product | Mid tier | Top consumer tier |
|---|---|---|
| Perplexity | Pro $20 | Max $200 |
| ChatGPT | Plus $20 (Go $8) | Pro $200 |
| Claude | Pro $20 | Max 20× $200 |
| Gemini | AI Pro $19.99 | AI Ultra **$99.99** |
| Grok | SuperGrok $30 | SuperGrok Heavy $300 |

([tech-insider](https://tech-insider.org/chatgpt-vs-claude-vs-gemini-vs-grok-subscription-pricing-2026/), 2026-09-27.) A January source lists Gemini AI Ultra at **$249.99** ([sentisight](https://www.sentisight.ai/ai-price-comparison-gemini-chatgpt-claude-grok/), 2026-01-22) — either a 60% cut during 2026 or one source is wrong; unresolved. $20 is the market's anchor, and Perplexity sits exactly on it at both ends.

## Three questions today's session should answer

1. Pro pays $20/mo and gets no recurring credits — only a one-time 4,000. Is Pro priced as search with a sample of the agent, or as a loss-leading holding pen for Max, and which reading does the 10,000/mo gap support?
2. A 5–8× credit multiplier on an identical task, driven by thread length rather than anything the user asked for, is the customer paying for Perplexity's context window. Is that a defensible meter or a mispriced metric — and what would you change it to without breaking the agent?
3. Ads off, merchant fees at zero, Comet Plus paying 80% out, a $750M fixed Azure commitment, and a margin that may have been negative once the free tier is counted. Which of those is the decision that has to be reversed first, and what do you expect to break when it is?
