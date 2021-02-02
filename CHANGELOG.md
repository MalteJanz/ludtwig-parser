# NEXT-VERSION
- Mostly fixed a performance regression:
  Average template parsing performance is increased by ~295% since last version \[266us -> 87us\].
  It is still ~10% \[from 78us\] behind the performance before the advanced html tag attribute parsing was implemented
  (but this is expected).

# v0.2.1
Initial release as a separate crate from ludtwig.
