# Source-spider method

This directory is a recursive source graph for history of mathematics.

## Rules

1. Start from a named seed page or work.
2. Record a source as **located** when bibliographic metadata or a usable copy has been found.
3. Record it as **spidered** only after its references, notes, or bibliography have actually been inspected.
4. Preserve only verified citation edges. The fact that two works concern the same topic is a thematic relation, not a citation.
5. Give every spidered source its own Markdown node recording:
   - bibliographic identity;
   - what was actually inspected;
   - short mathematical/historical notes;
   - outgoing references;
   - bibliography status;
   - unresolved follow-up.
6. De-duplicate repeated references while preserving every incoming edge.
7. Put inaccessible, paywalled, incomplete, or not-yet-read references in [recursion-queue.md](recursion-queue.md). Never silently promote a located bibliography to a spidered one.
8. Prefer primary documents, author/institutional publication lists, scholarly repositories, publishers, reviews, and bibliographic databases. Wikipedia is deliberately useful here as a high-connectivity seed whose footnotes and bibliography are themselves spidered.
9. Summarize copyrighted work; do not reproduce substantial text.
10. Use public professional information only. Private contact information, home addresses, and similar personal data are not part of this repository.

## Scope

The seed corpus is June Barrow-Green, Jesper Lützen, Jed Z. Buchwald, Jeremy Gray, and Athanase Papadopoulos. The project is `math.HO`: mathematical history and overview. It is not a visualization project.

See [source-map.md](source-map.md) for the graph and [thanks.md](thanks.md) for attribution.
