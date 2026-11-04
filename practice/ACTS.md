# Your Monday recipe: ACTS

**Before AI acts, remember ACTS.**

Use it before you connect an agent to a data source, before you launch an AI workflow,
or before you act on an AI answer that matters.

Each step lists the principles it connects to most directly. In practice, quality,
governance and accountability matter in all four.

## A · Ask: challenge assumptions
*Most directly: [04 Governance](../principles/04-governance.md)*

What could be missing? What are we assuming about this information that we haven't checked?
- [ ] We've asked what could be missing: exceptions, workarounds, records handled outside the process.
- [ ] Each field the AI acts on has a named owner and an agreed definition.
- [ ] Where definitions conflict (two fields, two systems), we know who decides and which source wins.

## C · Comprehend: the context and the knowledge behind it
*Most directly: [01 Context](../principles/01-context.md) · [03 Knowledge](../principles/03-knowledge.md)*
- [ ] The AI sees the structure and metadata, not just the text.
- [ ] We've asked the people who know: what exceptions and workarounds exist here?

## T · Trace: the answer to a source you trust
*Most directly: [02 Quality × Quantity](../principles/02-quality-x-quantity.md) · [05 Transparency](../principles/05-transparency.md)*
- [ ] Every answer links to its source, version and date.
- [ ] We've checked that the source is current and authoritative, not only that it exists.
- [ ] We tested on a small sample, by hand, before scaling.

## S · Ship: with safeguards and a named owner
*Most directly: [06 Accountability](../principles/06-accountability.md)*
- [ ] A named person owns the outcome.
- [ ] We know what the AI may do alone, what needs a human, and how to roll back.
- [ ] We've designed what the agent does when its sources disagree: flag it, ask, or stop.

---

## Example: ACTIVE or ANNULLED?
Your agent is about to send renewal reminders for every document with STATUS = ACTIVE.

- **Ask:** what could be missing? Is STATUS the field that counts, and who decides what ACTIVE means?
- **Comprehend:** is anything done outside the process? Check whether titles, notes or
  comments say something different from the status.
- **Trace:** pick ten documents at random. Where STATUS and TITLE disagree, can you trace
  which one reflects the authoritative business state? If you can't, that's a finding to
  investigate, not a choice for the agent to make.
- **Ship:** decide what the agent does when the signals disagree (flag, ask a named owner,
  or skip), then go live with a dry run and a way to stop it.

Six principles. Four letters. One habit: curiosity.
**Don't outsource your curiosity to the model.**
