# Zero annulments

*Illustrates: [03 Knowledge](../principles/03-knowledge.md) · [04 Governance](../principles/04-governance.md) · [06 Accountability](../principles/06-accountability.md)*

A different project. Another perfect story.

We were asked a simple question: how many documents had been annulled? The query was
correct. The data model had a STATUS field, and ANNULLED was one of its values. We ran it.

**Zero annulments. Zero annulments.** Year after year, the bars on the chart sat at zero.

That couldn't be right. So we got curious, and went looking for the people who would know.
Down in IT support, on level minus one, someone remembered. For years, when a document
needed annulling, people didn't use the process. They came down and whispered:

*"Psst… could you annul this document for me?"*

And IT support did something. They typed **ANNULLED** into the document's TITLE.
The STATUS stayed **ACTIVE**.

| Field | Value |
|---|---|
| TITLE | ANNULLED – … |
| STATUS | ACTIVE |

The rule was never in the system. It was in someone's memory.

## AI cannot whisper
A person, puzzled by the zeros, could go downstairs and ask. An AI agent can't. It will
read STATUS = ACTIVE, trust it, and act on it, confidently, every time.

## What we took from it
- Systems hold the data. People hold the context. (**Knowledge**)
- Somebody has to decide what ACTIVE means, and which field counts. (**Governance**)
- Somebody typed ANNULLED. Who owned that decision? (**Accountability**)

> *Names and systems are kept general on purpose. Have a similar story?
> [Add it](../CONTRIBUTING.md#add-a-story).*
