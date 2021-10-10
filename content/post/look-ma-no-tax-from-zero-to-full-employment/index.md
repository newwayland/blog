---

title: "Look Ma No Tax: From Zero to Full Employment"
date: 2020-09-01T06:47:21+01:00
summary: "Demonstrating how the Job Guarantee precisely offsets the drain to savings"
tags: [mmt, jg, models]

---

In the [original model][2] and the [price shopping model][3] the money
supply was exogenous, in that you had to allocate a fixed amount of
money to entities and hope that was the right amount for the
economy. Finding the right amount to avoid an inflation or deflation
takes some effort.

Adding the Job Guarantee automatic stabiliser changes that to an
endogenous approach. The Job Guarantee automatically adds the right amount
of money into the circulation as required by the entities operating within
it. In this post all the simulation runs start with both Households and
Firms on zero liquidity, showing how the Job Guarantee can bootstrap a
monetary economy. And incidentally how you would introduce a new currency.

I've been trying out some different scenarios by changing the other
parameters of the [Job Guarantee Model][1] with some interesting results.

Here's a trace where the JG goods price is dropped to zero - essentially
removing all forms of taxation from the model.

{{<figure src="jg-from-zero-22-1-0-22.png" alt="JG with no taxation">}}

No inflation. In fact we get wage growth against a stable goods price
as productivity is redistributed to the wage share and away from
profit. Which is what you would want to see in a system where productivity
is fixed.

The business cycle appears to have disappeared. 

What we have instead is a high level of savings with a slightly skewed
distribution that leads to a small amount of unsatisfied demand and very
low inventories.  Essentially the people run out of things to buy in each
cycle but the firms can't price change to absorb that because they are
in competition with each other for market share.  This is where the drive
for productivity improvements would normally come from - to fill the gap.

Contrast that trace with one where the Job Guarantee charges a
'competitive price' for its output.

{{<figure src="jg-from-zero-22-1-21-22.png" alt="JG with price charges">}}

Here there is much more dislocation in the economy. Firms try to cut
wage costs. Savings and profits are squeezed. And we get a deflating
goods price. It's not a great business environment - as we can see with
the large inventories.

But demand is still satisfied and the savings distribution is far more
even if an awful lot lower.

The JG price here is acting like a tax during a slump, draining savings
and demand during the wrong part of the cycle. 

You get a similar effect if you charge a punitive price for JG
output. This causes somewhat lower dislocation to the
business sector at the cost of higher poverty during the bootstrap phase.

{{<figure src="jg-from-zero-22-1-44-22.png" alt="JG with punitive charges">}}



[1]: http://jg.model.new-wayland.com/
[2]: http://baseline-economy.model.new-wayland.com/
[3]: http://price-shopping.model.new-wayland.com/
