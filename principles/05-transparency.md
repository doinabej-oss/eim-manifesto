# 05 · Transparency

> **Every outcome needs a path back to its source.**  
> AI can simplify the answer. It must never make its origin invisible.

*Group: about how we act on it*

## What it means
As developers, we don't trust code we can't trace: we have logs, versions and stack traces.
Information deserves the same: which source an answer came from, which version, which rule
was applied.

A fluent answer is not a trace. AI can make the answer simpler; it must never make its origin invisible.

## Why it matters for AI
AI answers can sound equally confident whether they are right or wrong. Seeing where an
answer came from doesn't prove it's right, but without it you can't check: is the source
current, is it authoritative, and does it actually say what the answer claims? A trace is
what makes that check possible.

When the agent says "this contract expires in March", can you click through to the clause?

## In practice
- Show sources with every AI answer: document, version, date, system.
- Log which records an agent read and which rule it applied when it acted.
- Keep versions, so "what did it know at the time?" has an answer.
- Make "I can't find a source" a valid answer instead of a guess.

## Questions to ask
- Can I click from this answer to the exact source?
- Is that source the current version?
- If this decision is challenged in six months, can we reconstruct it?

## Feeds ACTS (most directly)
**T**race
