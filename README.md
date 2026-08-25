# WOB-Video-Experiment

**WOB is an experimental methodology**. Its goal is to provide a means of refactoring source code for data intensive applications, and increase their effectiveness.

**WOB Compared with Conventional Refactoring**
Traditional refactoring improves code structure and maintainability.
Performance optimization finds slow parts and makes them faster.
Profile-guided optimization measures where execution time is being spent and concentrates effort there.
Adaptive systems vary behaviour depending on conditions, usually within a specific mechanism.

**WOB takes a broader system-level view:**
Is this processing justified here, at this level, and in this form?
A conventional optimizer might find an expensive function and make it faster.
WOB may instead discover that the larger system can avoid, reduce, defer, reuse, reorder, or selectively deepen that processing.

**The distinction is:**
Traditional optimization improves execution. WOB reconsiders how much processing should happen, where, and when.
WOB can refactor code that has been already been conventionally refactored, because it is doing something entirely different. 


This was the first attempt at applying the simple WOB rule (6 words!) to a known data processing algorithm - early results were promising.  However an underlying principle emerged when applying the rule, so the experiment was abandoned in favour of a loftier goal.  The WOB rule was born, and thus the entire methodology.

[Watch demo video](https://github.com/SimBuddy/WOB-Video-Experiment/blob/main/wob_vs_full_demo.mp4)

Video is left for posterity.
