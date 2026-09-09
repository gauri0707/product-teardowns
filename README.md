# Product Teardowns

Weekly teardowns and case studies of products I find interesting — how they're built, how they make money, and what I'd ship next.

Each teardown follows the same five-part structure and takes one week. The finished write-up lives in `teardowns/`. The raw research that fed it lives in `research/`, kept in the open so the reasoning is auditable.

**Maintained by [Gauri Krishnamoorthy Thevar](https://github.com/gauri0707)** · Product & engineering, Mumbai

---

## The teardowns

| # | Product | Domain | Status | Week of |
|---|---------|--------|--------|---------|
| 01 | Cursor | AI / dev tools | Planned | Sep 14, 2026 |
| 02 | Razorpay | Fintech | Planned | Sep 21, 2026 |
| 03 | Linear | B2B SaaS | Planned | Sep 28, 2026 |
| 04 | Perplexity | AI | Planned | Oct 5, 2026 |
| 05 | Stripe | Fintech | Planned | Oct 12, 2026 |
| 06 | Notion AI | AI | Planned | Oct 19, 2026 |
| 07 | Zerodha / Kite | Fintech | Planned | Oct 26, 2026 |
| 08 | Vercel | Dev tools | Planned | Nov 2, 2026 |
| 09 | Claude (Anthropic) | AI | Planned | Nov 9, 2026 |
| 10 | UPI ecosystem | Fintech infra | Planned | Nov 16, 2026 |
| 11 | Figma | B2B SaaS | Planned | Nov 23, 2026 |
| 12 | GitHub Copilot | AI / dev tools | Planned | Nov 30, 2026 |
| 13 | Synthesis: pricing AI products | Essay | Planned | Dec 7, 2026 |

Full schedule and rationale: [`CALENDAR.md`](CALENDAR.md)

---

## How each teardown is built

One product per week, five working sessions of about 25 minutes each.

| Day | Session | Output |
|-----|---------|--------|
| Mon | **Brief** — why this product, why now, what's public | `00-brief.md` |
| Tue | **Flow** — walk the core journey, annotate the friction | `01-flow.md` |
| Wed | **Model** — business model, unit economics, moat | `02-model.md` |
| Thu | **Proposal** — what's broken, what I'd ship, success metrics | `03-proposal.md` |
| Fri | **Ship** — assemble the case study, write the short version | `README.md`, `share.md` |

Templates for each session are in [`templates/`](templates/).

## Repo layout

```
teardowns/<nn>-<product>/    finished case study + the five session files
research/                    dated research notes (machine-assisted, labelled)
templates/                   the five session templates
notes/                       reusable frameworks that emerge across teardowns
CALENDAR.md                  the 13-week schedule
CONTRIBUTING.md              how the daily loop works
```

## A note on method

Research gathering is automated — a scheduled job pulls public pricing, changelogs, filings, reviews, and news into `research/` each weekday morning. Those files are machine-generated and labelled as such at the top.

Everything in `teardowns/` is written by me. The analysis, the judgment calls, and the product bets are mine; the automation just does the fetching so the thinking gets the full session.
