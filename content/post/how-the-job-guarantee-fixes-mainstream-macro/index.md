---

title: "How the Job Guarantee Fixes Mainstream Macro"
summary: "Adding a Job Guarantee to the peer reviewed mainstream agent model"
date: 2020-08-29T12:17:56+01:00
tags: [models, mmt, mainstream, abm, jg]

---

[Last time][3] we broke the [mainstream macro model][1] by [adding
some price competition][2] to the mix. Here's another run with the same
parameters[^1]

[(Price Shopping Model)](http://price-shopping.model.new-wayland.com)
{{<figure src="price-shopping-2008.png" alt="Price Sensitive Output">}}

Yup, still very broken. 

Let's [add a Job Guarantee][4] to this model and see [how it controls][5] the economy

[(Job Guarantee Model)](http://jg.model.new-wayland.com)
{{<figure src="job-guarantee-2008.png" alt="Job Guarantee Output">}}

And the problem is fixed. Full employment from day one, no poverty, wages and prices stabilised. All exactly [by the book.][6]

[1]: https://doi.org/10.1016/j.jebo.2012.12.021
[2]: https://github.com/newwayland/baseline-economy/tree/price-shopping
[3]: {{< relref "revealed-the-simple-change-that-breaks-mainstream-macro" >}}
[4]: {{< relref "adding_a_jg" >}}
[5]: {{< relref "how-the-JG-controls-inflation" >}}
[6]: https://amzn.to/2G61Ii1

This trace has a few interesting artefacts in it that are worthy of note.

1. The wage slowly increases but the price of goods falls. Competition
does its job and the real wage share increases over time.

2. The Job Guarantee catches a major recession in the economy. 30% of
private sector jobs are lost and yet the economy barely skips a beat. The
Job Guarantee responds. Wages are reset downwards towards the guaranteed
wage and the private sector rapidly recovers.

3. There is a small amount of residual unmet demand. That doesn't affect
prices but it is correlated with the exhausting of the Job Guarantee
inventory buffer. More money ends up chasing nothing much - as there
isn't anything more to buy. Firms are too busy maintaining market share
against competitors.

Discuss this and any other post over on the [New Wayland Discord
Forum](https://discord.gg/JN6HKUd)

[^1]: Model parameters: Household Starting Money 3200, Firm Starting
Money 0, Initial Goods Price 27, Initial Daily Wage Rate 70, JG Wage 50,
JG Goods Price 50


