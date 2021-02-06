# NEXT-VERSION


# v0.3.0
- Mostly fixed a performance regression:
  Average template parsing performance is increased by ~295% since last version \[266us -> 87us\].
  It is still ~10% \[from 78us\] behind the performance before the advanced html tag attribute parsing was implemented
  (but this is expected).
- Added iterator implementations for the AST structures.
  There is one basic iterator which visits all nodes in the AST and a advanced iterator which visits all nodes together with a context.
  This context contains information about it's neighbor nodes and so on.
- Removed `HasChildren` Trait because it was not as useful as it seems and was not implemented for all AST types.

# v0.2.1
Initial release as a separate crate from ludtwig.
