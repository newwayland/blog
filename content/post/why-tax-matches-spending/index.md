---
title: "Why Tax Matches Spending"
summary: "A bit of multiplier maths so you can impress the neoliberals"
date: 2021-07-04T08:05:46+01:00
tags: [mmt, maths]

---

We are currently in an environment where people are going around repeating the mantra "more government spending means taxes must go up". 

But only, of course, by people who are hard of both accounting and mathematics. It's like the household analogy - a common fallacy.

Let's see why.

My spending is your income less tax. So for a tax rate of 20% and a spend of 100 the total spending looks like this

````
Total spend = (100) + (100 * 80%) + (80 * 80%) + (64 * 80%) ...
````

This is the spending multiplier and is a simple geometric progression of the usual form

````
s = a + a(1-t) + a(1-t)^2 + a(1-t)^3 + ... + a(1-t)^n
````

where `a` is the initial spend, `t` is the tax rate, `n` is the number of transactions, and `s` is the total induced spend across the economy by that sequence. Since the 'common ratio' `(1-t)` is less than 1, we can use the [sum to infinity formula of a geometric progression][0] to get the size of the maximum spend induced in the economy by that injection.

````
s = a / t
````

rearranging that gives you the following

````
st = a
````

which proves that the amount of tax collected `st` must (eventually) match the initial spending injection `a`. Unsurprisingly if you are using percentages against a bigger number, you get a bigger number out the end. The amount of tax collected increases as spending increases because that's how percentages work (duh!).

Now of course there won't be an infinite number of transactions induced. Currency units are a finite size and once you get below a particular amount they become useless. Certainly below one, but it may be higher depending upon how your currency unit is valued (In the UK, pounds are still useful. Pennies not so much). By playing with the geometric progression formula and using some not very advanced algebra you can come up with an equation to show how many transactions that will take.

````
n = (log(t)-log(a)+log(d))/log(1-t)
````

where `d` is the deminimis useful number of currency units.

[0]: https://www.math-only-math.com/sum-of-an-infinite-geometric-progression.html
