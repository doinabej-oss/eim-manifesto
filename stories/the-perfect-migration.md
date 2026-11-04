# The perfect migration

*Illustrates: [01 Context](../principles/01-context.md) · [02 Quality × Quantity](../principles/02-quality-x-quantity.md)*

A real story, and a recent one, from the world of investigations.

We were migrating information from a legacy repository: almost 5,000 records, each with
its related digital evidence. Around one and a half million files, over 500 gigabytes of
content. For an enterprise, nothing unusual. So we migrated. Every single file.

At the end, the numbers matched. The files arrived. The migration was technically
successful.

But there was a catch. In the legacy repository, the files were organised in folders,
and the folder path wasn't decoration. It was the provenance:
**Case › Source › Evidence file**. It told you where each piece of evidence came from.

In the new repository, everything landed in one flat structure. Every file still had its
*What* and its *Where*. But it had lost its *Why*: the files could no longer be related
to their cases. And for evidence, where it came from is half of what it means.

**We migrated every tree. And we lost the forest.**

## What we took from it
- A migration can be technically perfect and still lose information.
- Structure is information. Before you flatten it, write down what it meant, and carry
  that meaning across as metadata.
- An AI reading those files today could understand every sentence, and still not know
  what each document *is*, or which case it belongs to.

> *Names and systems are kept general on purpose, and figures are rounded. Have a similar
> story? [Add it](../CONTRIBUTING.md#add-a-story).*
