# Zero annulments

*Illustrates: [03 Knowledge](../principles/03-knowledge.md) · [04 Governance](../principles/04-governance.md) · [06 Accountability](../principles/06-accountability.md)*

A different project. An enterprise repository: four million records, and a process that
had existed for twenty years: records annulment. Once a document (a decision, a report,
an authorisation) is annulled, it is no longer valid.

We were asked a simple question: how many records had been annulled, and when? The data
model had a STATUS field, and ANNULLED was one of its values. We ran the query.

For two years, 2017 and 2018, the chart showed **zero annulments**.

Organisations can do many things. Staying perfectly consistent for two years is rarely
one of them. So we got curious. We compared records, looked for explanations, and
eventually found someone who remembered.

During those years, the normal annulment process had stopped working properly. But the
business couldn't simply stop: people still needed documents annulled. So they found
another way. They went downstairs to IT support, on level minus one, and asked quietly:

*"Psst… could you annul this document for me?"*

And IT support helped. Well, they did something. They added the word **ANNULLED** to the
document's TITLE. The STATUS stayed **ACTIVE**.

| Field | Value |
|---|---|
| TITLE | ANNULLED – … |
| STATUS | ACTIVE |

To anyone querying the status, these records looked like any other active record. The
query was correct: the system returned exactly what its data said. It just didn't answer
the business question we thought we were asking.

The title didn't settle it either. A word typed into a title shows that someone wanted
the document annulled. On its own, it doesn't prove that a formal annulment took place.
The history that explained the conflict wasn't in the status field, and it wasn't in the
documented process. It was in someone's memory.

## AI cannot whisper
A person puzzled by the zeros could go downstairs and ask. An AI agent can't wander down
to level minus one or find the colleague who remembers 2017. Left to itself, it reads the
register, never the sticker: it sees STATUS = ACTIVE and has no reason to doubt it.

That isn't a limit we have to accept. We can design agents to recognise conflicting
signals, consult the right person, or stop. But only if we give them what people carry
in their heads: the sources, the rules, the known exceptions, and a path to escalate.
The unwritten rules have to be written down.

## What we took from it
- Systems hold the data. People hold the context. (**Knowledge**)
- A conflict between two fields is a question to investigate, not a choice for an agent
  to make. Neither TITLE nor STATUS alone tells you the authoritative business state. (**Governance**)
- Somebody has to decide what ACTIVE means, which field counts, and what happens when
  they disagree. (**Governance**)
- Who had authorised IT support to annul documents? Nobody. Everyone helped. Nobody owned
  it. (**Accountability**)

> *Names and systems are kept general on purpose. Have a similar story?
> [Add it](../CONTRIBUTING.md#add-a-story).*
