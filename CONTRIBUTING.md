# How the daily loop works

Notes to future me, for the mornings when this feels like a chore.

## The deal

Twenty-five minutes, five weekdays a week. That's it. The week produces one finished teardown whether or not any single session goes well.

The commitment is to the session, not to the quality of the session. A bad Tuesday still gets committed.

## Each morning

A scheduled job runs on weekdays and drops a research file into `research/` — public pricing, recent changelog entries, funding and filings, review-site themes, news from the last week. It's dated and labelled at the top as machine-generated.

That file is an input, not a draft. It saves you the fetching so the whole twenty-five minutes goes to thinking.

## Then

1. Open today's template from `templates/`, copy it into `teardowns/<nn>-<product>/`
2. Read the research file
3. Write. Set a timer if it helps
4. Commit, even if it's rough

Commit messages: `<product>: <session>` — e.g. `cursor: flow walkthrough`

## The rule about authorship

Research is automated. Analysis is not.

Nothing goes into `teardowns/` that you didn't write and don't believe. The whole value of this repo is that someone reading it learns how you think — a stack of generated essays is worth less than nothing, because it's worse than empty and it's detectable.

If you're short on time, commit a thinner session. Don't commit someone else's thinking with your name on it.

## When you miss a day

Skip it. Don't double up — that's how the whole thing collapses in week three. The week still ships on Friday, just shorter.

If you miss three days in a week, drop that product to the substitution list and start fresh Monday.

## When a teardown is done

- Move the status in `README.md` to `Published`
- Write `share.md` — the 200-word version, for posting
- If a framework emerged that you'd reuse, pull it into `notes/`

## Prototypes

Optional, weekends only. If a proposal from Thursday is small enough to build in a few hours, build it and link it from the case study. A working prototype attached to a case study is worth about three case studies on their own.
