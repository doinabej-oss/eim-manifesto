# Zero annulments

*Illustrates: [03 Knowledge](../principles/03-knowledge.md) · [04 Governance](../principles/04-governance.md) · [06 Accountability](../principles/06-accountability.md)*

A different project. Another perfect story.

We were asked a simple question: how many documents had been annulled? The query was
correct. The data model had a STATUS field, and ANNULLED was one of its values. We ran it.

**Zero annulments.** For two years, 2017 and 2018, the bars on the chart sat at zero.

That couldn't be right. So we got curious, and went looking for the people who would know.
Down in IT support, on level minus one, someone remembered. During those years, the normal
annulment process had stopped working properly. The business couldn't simply stop, so
people came down and whispered:

*"Psst… could you annul this document for me?"*

And IT support did something. They typed **ANNULLED** into the document's TITLE.
The STATUS stayed **ACTIVE**.

| Field | Value |
|---|---|
| TITLE | ANNULLED – … |
| STATUS | ACTIVE |

The rule was never in the system. It was in someone's memory.

## AI cannot whisper
A person, puzzled by the zeros, could go downstairs and ask. An AI agent can't, unless
we have written the rule down or given it a way to ask. Otherwise it reads the register,
never the sticker: STATUS = ACTIVE.

## What we took from it
- Systems hold the data. People hold the context. (**Knowledge**)
- When TITLE and STATUS disagree, don't let anyone, or any agent, just pick one. Find out
  what really happened. (**Governance**)
- Somebody has to decide what ACTIVE means, and which field counts. (**Governance**)
- Somebody typed ANNULLED. Who owned that decision? (**Accountability**)

> *Names and systems are kept general on purpose. Have a similar story?
> [Add it](../CONTRIBUTING.md#add-a-story).*
