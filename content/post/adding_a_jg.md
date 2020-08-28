---

title: "Adding a JG to the Baseline Model"
date: 2020-08-28T09:33:39+01:00
description: "Algorithm changes required to the Baseline Model to support a Job Guarantee"
tags: [mmt, jg, models]

---

I've added a branch to the [Baseline Model][3] code to support the Job
Guarantee and [written up a summary and the detailed algorithm changes
required][1].

The changes are made by adding a "Firm 101" to the model that acts like
any other firm other than it
conforms to the Job Guarantee restrictions: 

- there is always a job opening
- the wage is fixed
- the wage is always paid as Firm 101 has no liquidity restrictions

In addition Firm 101 has adaptations to the economy it is running in:

- labour hours are transformed into the same single, stockable, tradeable good
in the economy as all other hours are
- the good is sold at a fixed price
- the good competes with private sector output at that price
- sale of the good at the fixed price is the only taxation mechanism
- the productivity of Firm 101 is much lower than a private firm
- nobody is ever made redundant from Firm 101
- households try to get off the Job Guarantee
- households still hold out for a bit looking for a better wage, if they
are made redundant by a private firm, and will remain unemployed while
doing so

The restrictions and adaptations are included to ensure the model Job
Guarantee [controls inflation][2] properly.

I have a truly marvelous demonstration of this update which this blog
post is too long to contain.

[1]: https://github.com/newwayland/baseline-economy/blob/jg/notes/jg-rules.md
[2]: https://new-wayland.com/blog/how-the-jg-controls-inflation/
[3]: https://new-wayland.com/blog/revealed-the-simple-change-that-breaks-mainstream-macro/
