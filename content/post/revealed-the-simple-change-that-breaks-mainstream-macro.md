---

title: "Revealed: The Simple Change That Breaks Mainstream Macro"
date: 2020-07-28T11:11:43+01:00
description: "Price competition breaks peer reviewed mainstream agent model"
tags: [models, mmt, mainstream, abm]

---

As regular visitors to the [New Wayland Discord Forum](https://discord.gg/ESGqEsv) will know, I've been working on [replicating a mainstream Baseline Model](https://github.com/newwayland/baseline-economy) (Lengnick, Matthias. (2013). Agent-based macroeconomics: A baseline model. Journal of Economic Behavior & Organization. 86.10.1016/j.jebo.2012.12.021). There are [quite a few issues](https://github.com/newwayland/baseline-economy/blob/master/notes/issues.md) with it technically but it is a good starting point. 

This is a model that strips away any part of reality that get in the way of demonstrating the mainstream outcome. It has one commodity, there are no banks, money is exogenous, wages are flexible - particularly downwards, etc, etc. The paper states "Finally, we demonstrated that the equilibrium is a robust result of the ACE economy for all markets. It does only break down, if either price or wage adjustment is turned off completely."

And the results[^1] appear to bear that out.

[(Baseline Model)](http://baseline.model.new-wayland.com)
![Baseline Output](images/ace-output-baseline.png)

However when you look into the design of the model (Section 2.3, pp108) you notice something peculiar:

> Each household visits one randomly determined firm of those he has a ... connection with

I don't know about you but I don't go to a shop randomly. I go to the one where I can get what I want at the cheapest price. Surely a good mainstream economist would do the same?

So let's make that change to this robust model. It's a single line change from

```python
    # Put the preferred suppliers in a random order 
    self.model.random.shuffle(self.preferred_suppliers)
```

to

```python
    # Put the preferred suppliers in price order
    self.preferred_suppliers.sort(key=attrgetter("goods_price"))
```

so rather than randomly visiting a supplier to see if they can fill our goods demand we go to the supplier with the cheapest price first and then the next cheapest and so on. 

Let's see what the results are

[(Price Shopping Model)](http://price-shopping.model.new-wayland.com)
![Price Sensitive Output](images/ace-output-price-shopping.png)

Oh dear. 

If this model is to be believed, full employment/price stability and price competition appear to be incompatible in the mainstream world. 

[^1]: Model parameters: Household Starting Money 3200, Firm Starting Money 0, Initial Goods Price 27, Initial Daily Wage Rate 70


