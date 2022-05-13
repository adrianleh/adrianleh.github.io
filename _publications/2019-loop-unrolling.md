---
title: "Loop unrolling with non-constant bounds in FIRM"
collection: publications
permalink: /publication/2019-loop-unrolling
excerpt: 'Unrolling loops where bounds are unknown at compile time'
date: 2019-09-30
venue: 'N/A'
paperurl: 'https://pp.info.uni-karlsruhe.de/uploads/publikationen/lehmann19bachelorarbeit.pdf'
citation: 'Adrian Lehmann (2019). &quot;Loop unrolling with non-constant bounds in FIRM". <i>KIT Bachelor Thesis</i>.'
---
Loop unrolling is the process of duplicating a loop’s body multiple times to reduce the number of conditional jumps. While we can easily unroll loops with constant bounds, unrolling loops with non-constant bounds proves to be a different challenge.

In this case, we can speculatively unroll a loop by a given factor, while making sure that the unrolled loop runs as often as possible, but less than or equal times to the original loop. To compensate for the discrepancy, we create so-called fixup code, which is responsible for running the remaining iterations. We employ two different strategies for creating the aforementioned fixup code: One where we duplicate the original loop and another where we utilize a generalized form of Duff’s device.

When experimentally evaluating the approach, even though we double the amount of unrollable loops to now unroll more than 10% of all loops, we cannot note any speed-up outside of the margin of error. The results indicate that loop unrolling does not seem to have a (significant) benefit without further optimization.

[Download paper here](https://pp.info.uni-karlsruhe.de/uploads/publikationen/lehmann19bachelorarbeit.pdf)

