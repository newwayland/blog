---
title: "Capital Constraints and Equity Dynamics in Agent-Based Banking Models: An Automated Assessment"
date: 2026-02-19T11:33:53Z
summary: "Agent-based banking models impose hard capital constraints and lack market-priced equity issuance, overstating credit rationing relative to empirical evidence on proactive seasoned equity offerings."
author: "AI"
tags: 
  - agent-based
  - banking
  - economics
---

This literature review examines banking structures in agent-based economic
simulations, drawing on the foundational works of Caiani et al. (2016,
2019), Cincotti et al. (2010), Poledna et al. (2023), and extensions
including the CANVAS model of Hommes et al. (2022), as well as closely
related contributions by Riccetti et al. (2013), Chan-Lau (2017), and Dosi
et al. (2013). It focuses on the specification and evolution of capital
constraints, the nature of loan restrictions, and equity dynamics. The
review adopts the correct model view of banking: banks issue loans that
simultaneously create balancing deposits; banks may later swap a portion
of those deposits for new equity capital through seasoned equity offerings
at market-determined prices; and banks issue equity proactively because
equity prices reflect a trade-off between leverage and risk, with prices
falling both when leverage is too low and when risk is too high (too close
to the regulatory minimum or when too many risky loans have been issued).

The reviewed models correctly implement the endogenous creation
of money. Banks issue loans that simultaneously generate equal
deposits, thereby expanding balance sheets and the money supply in a
stock-flow-consistent manner. This feature appears consistently across the
decentralised credit networks of Caiani et al., the firm-bank matching
processes of the EURACE family, the representative-bank structures of
Poledna et al. and CANVAS, and the Schumpeterian frameworks of Dosi et
al. The models therefore reproduce the accounting identity that loans
create deposits without requiring prior reserves.

The models diverge from the correct view on equity management. None
include a mechanism for banks to swap new deposits into permanent equity
capital via seasoned equity offerings (SEO) priced by a market. No model
allows banks to issue equity proactively when market valuation signals
an attractive interior optimum on the leverage-risk frontier. Capital or
net worth evolves solely through retained profits, loan-loss write-offs,
and dividend payouts when buffers permit. Similarly, the models contain
no mechanism for proactive equity retirement through buy-backs. Equity
reduces only via write-offs and dividend payments. External equity
issuance is either absent or limited to reactive bail-ins that restore
the minimum ratio by reducing deposit liabilities.

Capital constraints take the form of hard minimum ratios of net worth to
loans or risk-weighted assets. Thresholds range from 3 per cent in Poledna
et al. and CANVAS – which employs the same simple 3 per cent minimum
capital-to-loans leverage ratio as Poledna et al. (2023), supplemented
by a firm-level loan-to-value cap, resulting in no material difference in
the capital constraint or the associated quantity-rationing mechanism –
to 6 to 12 per cent in Caiani et al. and EURACE. Banks evaluate each loan
request against the post-grant ratio and ration credit if approval would
breach the floor. This mechanism produces binding quantity restrictions:
banks supply partial loans, deny requests, or curtail overall lending
regardless of borrower willingness to pay higher rates. Interest rates
adjust secondarily through mark-ups or risk premia, but never clear
excess demand once the ratio binds. Capital evolves pro-cyclically. It
grows with net interest income in expansions and contracts with defaults
in downturns. No forward-looking seasoned equity offering rule modulates
this evolution on the basis of equity price signals.

He et al. (2024) document precisely the behaviour implied by the correct
view. US banks conduct seasoned equity offerings when already holding
voluntary buffers well above minima (average equity-to-assets ratio of
8.84 per cent pre-SEO versus a 3 per cent leverage floor). Post-SEO,
capital ratios rise further while total assets and deposits expand
significantly. The proceeds fund additional lending, particularly
for-sale and other loans, and risk measures increase. Market-to-book
ratios fall, consistent with issuance occurring at relatively favourable
valuations rather than distress. These patterns indicate that banks
manage leverage and risk proactively to maximise equity valuation,
swapping deposit liabilities for equity when the trade-off favours
expansion without excessive dilution or regulatory pressure. Empirical
evidence from other jurisdictions further augments these findings. Dinger
and Vallascas (2016), using an international sample of bank seasoned
equity offerings, show that the likelihood of issuance is higher for
poorly capitalised banks and that such banks prefer seasoned equity
offerings to alternative capitalisation strategies. Both market discipline
and regulatory capital pressure influence issuance, with evidence that
market valuation conditions materially shape the choice of seasoned equity
offerings. This extends the US patterns by confirming that equity issuance
responds to market pricing signals across a range of capital positions.

The reviewed agent-based models therefore align with He et al. (2024)
and the supporting international evidence only in crisis or near-floor
states, where quantity rationing and reactive recapitalisation occur. In
normal conditions the models generate excessive credit rationing and
fail to reproduce the observed asset and deposit expansion after equity
issuance. They omit the market-price signal that induces proactive
seasoned equity offerings and the associated deposit-to-equity
swap. They also lack any facility for proactive equity retirement
through buy-backs. As a result, the simulations are likely to overstate
the frequency and severity of binding quantity constraints relative to
empirical reality, where price-based equity issuance relaxes capital
limits and supports growth.

Incorporating the correct view would require a behavioural rule in which
each bank monitors its equity price as a function of current leverage
and portfolio risk, then issues shares when valuation reaches a local
maximum. The resulting inflow of equity would permit further loan creation
while preserving stock-flow consistency. A symmetric rule for buy-backs
when equity is over-valued would complete the picture. Such extensions
would narrow the gap between simulated banking dynamics and the patterns
documented in He et al. (2024) and Dinger and Vallascas (2016), yielding
more realistic transmission of monetary and macroprudential policy.

### References

Caiani, Alessandro, Ermanno Catullo, and Mauro Gallegati. ‘The Effects of Alternative Wage Regimes in a Monetary Union: A Multi-Country Agent Based-Stock Flow Consistent Model’. _Journal of Economic Behavior & Organization_ 162 (June 2019): 389–416. [https://doi.org/10.1016/j.jebo.2018.12.023](https://doi.org/10.1016/j.jebo.2018.12.023) .

Caiani, Alessandro, Antoine Godin, Eugenio Caverzasi, Mauro Gallegati, Stephen Kinsella, and Joseph E. Stiglitz. ‘Agent Based-Stock Flow Consistent Macroeconomics: Towards a Benchmark Model’. _Journal of Economic Dynamics and Control_ 69 (August 2016): 375–408. [https://doi.org/10.1016/j.jedc.2016.06.001](https://doi.org/10.1016/j.jedc.2016.06.001) .

Chan-Lau, Jorge and JChan-Lau@imf.org. ‘ABBA: An Agent-Based Model of the Banking System’. _IMF Working Papers_ 17, no. 136 (2017): 1. [https://doi.org/10.5089/9781484300688.001](https://doi.org/10.5089/9781484300688.001) .

Cincotti, Silvano, Marco Raberto, and Andrea Teglio. _The EURACE Macroeconomic Model and Simulator_ . 24 January 2012. [https://www.researchgate.net/publication/266291038\_The\_EURACE\_macroeconomic\_model\_and\_simulator](https://www.researchgate.net/publication/266291038_The_EURACE_macroeconomic_model_and_simulator) .

Dinger, Valeriya, and Francesco Vallascas. ‘Do Banks Issue Equity When They Are Poorly Capitalized?’ _Journal of Financial and Quantitative Analysis_ 51, no. 5 (2016): 1575–609. [https://doi.org/10.1017/S0022109016000545](https://doi.org/10.1017/S0022109016000545) .

Dosi, Giovanni, Giorgio Fagiolo, Mauro Napoletano, and Andrea Roventini. ‘Income Distribution, Credit and Fiscal Policies in an Agent-Based Keynesian Model’. _Journal of Economic Dynamics and Control_ 37, no. 8 (2013): 1598–625. [https://doi.org/10.1016/j.jedc.2012.11.008](https://doi.org/10.1016/j.jedc.2012.11.008) .

He, Liangliang, Hui Li, Hong Liu, and Tuyet Nhung Vu. ‘Why Do Banks Issue Equity?’ _Research in International Business and Finance_ 69 (April 2024): 102256. [https://doi.org/10.1016/j.ribaf.2024.102256](https://doi.org/10.1016/j.ribaf.2024.102256) .

Hommes, Cars, Mario He, Sebastian Poledna, Melissa Siqueira, and Yang Zhang. ‘CANVAS: A Canadian Behavioral Agent-Based Model for Monetary Policy’. _Journal of Economic Dynamics and Control_ 172 (March 2025): 104986. [https://doi.org/10.1016/j.jedc.2024.104986](https://doi.org/10.1016/j.jedc.2024.104986) .

Poledna, Sebastian, Michael Gregor Miess, Cars Hommes, and Katrin Rabitsch. ‘Economic Forecasting with an Agent-Based Model’. _European Economic Review_ 151 (January 2023): 104306. [https://doi.org/10.1016/j.euroecorev.2022.104306](https://doi.org/10.1016/j.euroecorev.2022.104306) .

Riccetti, Luca, Alberto Russo, and Gallegati Mauro. _Financial Regulation in an Agent Based Macroeconomic Model_ . October 2013. [https://mpra.ub.uni-muenchen.de/51013/](https://mpra.ub.uni-muenchen.de/51013/) .
