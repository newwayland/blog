---
title: "The Tyranny of Zero: How Nothing Controls Everything"
date: 2025-02-16T09:19:03Z
summary: "How a simple numerical concept exerts outsized influence over institutional operations and economic thought."

---
This week, I've been playing with the latest 'AI' models and teaching
them the vagaries of the UK Exchequer institutional arrangements. With
the new 'reasoning' models, they will iterate towards a solution to the
problem you ask them, which means that it is possible to get them to
execute a rudimentary simulation of the institutional processes.

The beauty of the reasoning models lies in their running commentary,
which is endlessly entertaining. Running the Exchequer is right at the
edge of their current capabilities, as one run noted:

> The challenge is managing a large number of transactions and generating output logs, keeping track of over 10 accounts, and maintaining exact balancing, all in a structured format. The complexity of this is definitely daunting!

On many runs, they will fail to reach a solution, and you can quiz them
about what the problem was:

> The difficulty lay in orchestrating a series of cash movements and recourse transfers among multiple accounts—each with its own rules—so that a £1000M spending order (fully authorised by Parliament) could be executed, all while maintaining strict cash‑basis accounting and ensuring that every institution's role was respected. The interplay of these detailed constraints meant that every step had to be carefully aligned, and any misstep (such as inadvertently using the DMA for spending or netting non‑cash items) would violate the rules. That is why discovering a path that meets all these requirements has proven to be particularly challenging.

Or they will get in a loop trying to resolve perceived contradictions
and end up running down a lot of dead ends before timing out:

> Reasoned about reworked Day 1 with £1000M spending **for 10m 29s**

They will even comment, occasionally, on the apparent futility of the
whole exercise:

> Maybe the correct flow is:
>
> Day 1: Spend £3bn, reserves increase. DMO does repo to drain reserves.
>
> Day 2: Tax £3bn, reserves decrease. DMO does reverse repo to add reserves.
>
> But this way, the net effect is zero. But why would the DMO drain reserves after spending and then add them back after taxing? That seems redundant.

One particularly intriguing aspect is how the AI models often struggle
with the concept of zero, much like most humans. This is not surprising,
considering that AI models are essentially sophisticated auto-correctors,
with their probability tree weights tuned from the average human
understanding.

That understanding is faulty in this area. The invention of double-entry
accounting predates the notion of zero—the earliest accounts use Roman
Numerals, not Arabic. Each account is merely a list of credits and debits,
and the totals are compared to one another to see if the account is
'in credit', 'in debit', or 'balanced'. What that list even means is
external to the accounting.

In many simulations, the AI models start to impose restrictions around
the notion of zero that are not specified in the instructions.

> Wait, so the process is:
>
> - Comptroller grants a credit authorization to the Exchequer Account.
> - Treasury issues an order to the Bank to transfer funds from the Exchequer Account to PMG Drawing Account.
> - The Bank executes this by debiting the Exchequer Account and crediting the PMG Drawing Account.
>
> But if the Exchequer Account starts at zero, how can it be debited? Unless the credit authorization effectively allows the Exchequer Account to go into a negative balance, which is prohibited. This suggests that the credit authorization is an actual accounting entry that credits the Exchequer Account, allowing it to have a positive balance to be debited.
>
> But rule 6 says Comptroller credits are not accounting entries. This is conflicting. Maybe the correct interpretation is that the authorization allows the Treasury to credit the Exchequer Account up to the authorized amount, which is then used for transfers.
>
> Alternatively, perhaps the authorization is not an accounting entry, but the subsequent transfer from the Exchequer Account to PMG is done via creating money, which is offset by a liability.
>
> This is getting complicated.

The models will very often get stuck inventing wild and wonderful
scenarios that avoid them having to cross the Rubicon, such as
delaying the state pension payments to the afternoon so they can get
a reserve-draining repo in during the morning. Yet we know for a fact
that state pension payments go out first thing every day, even though
the Exchequer account starts every day balanced.

At this point, the models often ignore their instructions, inventing
non-cash assets out of nowhere to try to justify where the payment came
from[^1] or just refusing to do double entry properly so the numbers add up.

Of course, I could add a rule telling the model what to do, but where is
the fun in that?

I want to know if the reasoning algorithms the machines
are using can get there on their own.

Eventually, on some runs, the model will detect the subtle difference
between the authorisation rules on the National Loans Fund:

> The Comptroller and Auditor General shall from time to time at the request of the Treasury grant credits on the National Loans Fund for sums payable out of the Fund

And the Consolidated Fund:  

> The Comptroller and Auditor General shall, on receipt of a requisition from the Treasury, grant the Treasury a credit on the Exchequer account at the Bank of England (or on its growing balance)

Noticing that final bit in the brackets allows the model to get there:

> This way, the simulation doesn't fail. The key was recognizing that the Exchequer Account can go overdrawn, allowing the recourse to draw from it even if it's negative.
>
> Therefore, on Wednesday, the DMO uses recourse to Exchequer to cover the shortfall. The Exchequer's negative balance is then offset by the tax inflow during the sweep.
>
> This resolves the issue.

Which begs the question: if a mere machine can figure this out, what's
stopping those who call themselves economists from doing the same?

{{<joindiscord>}}

[^1]: This particular model has already applied to be Chancellor of the Exchequer
