# Your Monday recipe: ACTS

**Before AI acts, remember ACTS.**

Use it before you connect an agent to a data source, before you launch an AI workflow,
or before you act on an AI answer that matters.

## A · Ask: challenge assumptions. What could be missing?
*Carries [04 Governance](../principles/04-governance.md)*
- [ ] We've asked what could be missing: exceptions, workarounds, things done outside the process.
- [ ] Each field the AI acts on has a named owner and an agreed definition.
- [ ] We know which system is the source of truth when two disagree.

## C · Comprehend: the context and the knowledge behind it
*Carries [01 Context](../principles/01-context.md) · [03 Knowledge](../principles/03-knowledge.md)*
- [ ] The AI sees the structure and metadata, not just the text.
- [ ] We've asked the people who know: what exceptions and workarounds exist here?

## T · Trace: the answer to a source you trust
*Carries [02 Quality × Quantity](../principles/02-quality-x-quantity.md) · [05 Transparency](../principles/05-transparency.md)*
- [ ] Every answer links to its source, version and date.
- [ ] We tested on a small sample, by hand, before scaling.

## S · Ship: with safeguards and a named owner
*Carries [06 Accountability](../principles/06-accountability.md)*
- [ ] A named person owns the outcome.
- [ ] We know what the AI may do alone, what needs a human, and how to roll back.

---

## Example: ACTIVE or ANNULLED?
Your agent is about to send renewal reminders for every document with STATUS = ACTIVE.

- **Ask:** what could be missing? Who decides what ACTIVE means here? Is STATUS the field that counts?
- **Comprehend:** is there anything people do outside the process? Check the titles. If they
  disagree with the status, find out why before the agent picks one.
- **Trace:** pick ten documents at random. Does each answer trace back to something you trust?
- **Ship:** with an owner, a dry run, and a way to stop it.

Six principles. Four letters. One habit: curiosity.
