# 01 · Context

> **Meaning lives in structure, not only in content.**

*Group: about the information*

## What it means
An AI agent can understand every sentence in a document and still misunderstand what the
document *is*: a draft or the signed version, current or superseded, for which client,
under which contract. Much of that meaning is not in the text. It lives in the structure
around it: folder paths, metadata, links between records, the system it came from.

## Why it matters for AI
Retrieval and agents read content very well. They read structure only if we keep it and
expose it. When structure is lost, the content survives, and so does the confidence of
the answer. The meaning does not.

## The story
[The perfect migration](../stories/the-perfect-migration.md): 100% of the files arrived.
The folder path that held their provenance did not.

## In practice
- Treat metadata and relationships as part of the payload in every migration, copy or index job.
- Before you flatten a hierarchy, write down what the hierarchy *meant*.
- Keep links between records (contract ↔ amendment ↔ invoice) alive in the target system.
- When you chunk documents for retrieval, carry the document-level context into each chunk.

## Questions to ask
- If this file were found alone, would we know what it is?
- What did the old structure tell people that the new one doesn't?
- Which fields does the AI actually see, and which ones only humans see?

## Feeds ACTS
**C**omprehend
