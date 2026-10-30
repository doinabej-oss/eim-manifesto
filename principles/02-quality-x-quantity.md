# 02 · Quality × Quantity

> **Quantity multiplies quality, whatever that quality is.**

*Group: about the information*

## What it means
Volume is a multiplier, not a virtue. Good information at scale becomes a capability.
Bad information at scale becomes a policy. One wrong record is a typo; a million copies
of it is how the organisation now behaves.

There is also a difference between information that is **screen-good** (it looks right
when a person reads it) and **action-good** (it is right enough for a system to act on
without a person checking).

## Why it matters for AI
AI doesn't read one record and pause. It reads everything, quickly, and acts on it.
Whatever quality we have, AI reproduces it at speed.

## The story
Think back to [the perfect migration](../stories/the-perfect-migration.md): one and a half
million files. If one value had been wrong, we would have migrated it one and a half million times.

## In practice
- Measure quality on the fields that drive action (status, dates, owners, amounts), not on everything.
- Fix at the source, before you copy, index or train.
- Sample before you scale: run the agent on 50 records and check them by hand before 50,000.
- Track "agent-ready" as a property of a dataset: described, contextualised, owned.

## Questions to ask
- Is this data good enough to *look at*, or good enough to *act on*?
- If one value here is wrong, how many places will it end up?
- Who notices when it's wrong, and how fast?

## Feeds ACTS
**T**race
