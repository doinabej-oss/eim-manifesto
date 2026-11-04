# 02 · Quality × Quantity

> **More information does not mean better information.**  
> AI makes information quality more consequential, not less.

*Group: about the information*

## What it means
Quantity multiplies quality, whatever that quality is. Volume is a multiplier, not a virtue. Good information at scale becomes a capability.
Bad information at scale becomes a policy. One wrong record is a typo; a million copies
of it is how the organisation now behaves.

There is also a difference between information that is **screen-good** (it looks right
when a person reads it) and **action-good** (it is right enough for a system to act on
without a person checking).

## Why it matters for AI
AI works at a scale no person can check by hand. An agent may read thousands of records
in seconds and act on many of them. Whatever quality we have, good or bad, now travels
further and faster than before.

## The story
Think back to [the perfect migration](../stories/the-perfect-migration.md): one and a half
million files. Scaling a migration also scales whatever problems are left unresolved in
the source. One wrong record is a typo. One wrong rule applied across one and a half
million files is a pattern, and an agent will act on it.

## In practice
- Measure quality on the fields that drive action (status, dates, owners, amounts), not on everything.
- Fix at the source, before you copy, index or train.
- Sample before you scale: run the agent on 50 records and check them by hand before 50,000.
- Track "agent-ready" as a property of a dataset: described, contextualised, owned.

## Questions to ask
- Is this data good enough to *look at*, or good enough to *act on*?
- If one value here is wrong, how many places will it end up?
- Who notices when it's wrong, and how fast?

## Feeds ACTS (most directly)
**T**race
