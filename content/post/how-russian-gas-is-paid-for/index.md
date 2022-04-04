---
title: "How Russian Gas Is Paid For"
date: 2022-04-04T08:54:05+01:00
summary: "How the new payment process for gas in Russia will work, including how it is settled at the Moscow Exchange, all of which leads to some interesting observations"
tags: [mmt, russia, central bank, exports, imports, external sector, NCC]

---
{{<figure src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Gazprom_HQ_1.jpg" alt="Gazprom HQ 1">}}

At the end of March [we finally got the details](https://www.lse.co.uk/fx/news/putins-decree-on-russian-gas-purchases-in-roubles-4mr38tmr39pjjes.html) of how Russia will require foreign buyers of gas to make payment.

The [process is relatively straightforward]({{< relref "rouble-rumble-continues" >}}). For EU buyers, contracts will remain in force at the price stated in EUR. The change is the account Gazprom will require payment into at Gazprombank, from one denominated in EUR to one denominated in RUB.

In addition banks making payments on behalf of gas buyers will not be able to pay into Gazprom's RUB account directly. Instead they will have to open a 'K' series account in EUR at Gazprombank and make the EUR payment there. Gazprombank will then act as agent for the gas buyer and place those EUR on the Moscow Exchange for auction in exchange for RUB which will then be placed in a parallel 'K' series account denominated in RUB at Gazprombank. Gazprombank will then, again as agent, transfer the RUB from the 'K' series account to the RUB account of Gazprom.

Only when Gazprom receives the RUB into its account is the payment considered to have been made under Russian Law.

There we could end the discussion and, in fact, many commentators have done just that. Here, however, we like to look a little deeper into things to see how things work institutionally and answer the questions that have been ignored: where is the RUB on the Moscow exchange actually coming from, and who in their right mind would hold the EUR in Russia right now?

To do that we need to dive into the Moscow Exchange and find out how that works.

The Moscow Exchange is a highly advanced clearing house offering very sophisticated facilities to traders. Its key feature over other exchanges is that, due to its unified status in Russia, it can offer trading across all financial markets: shares, commodities, derivatives and, unusually, foreign exchange. All of these markets are accessible via a Single Settlement account, meaning that margin posted on any market can be used on all the markets within the exchange.

The best analogy for an exchange is a casino. When you go into a casino you exchange money for casino chips. Then you play the games and hopefully at the end of the evening you have some chips left to exchange back into real money. In aggregate across all players what goes in, comes out - less the house fee. For our purposes, we can extend the analogy to say that the Moscow Exchange has the widest selection of games of any exchange, but that the games are limited in scope because most of them tend to be in Russian. Other than noting that the FX games can settle today and tomorrow as well as T+2, the games themselves are not our concern. We will focus on how this particular casino exchanges money for chips and back again.

The Moscow Exchange has a subsidiary known as the National Clearing Centre (NCC) which acts as a central counterparty for all trades on the Moscow Exchange. That means, legally, you buy and sell your items from and to NCC. However, as it is a non-credit financial institution, it acts as a pure middleman between you and the real buyer or seller. Helpfully, [NCC has a document](https://fs.moex.com/files/18521) with an overview of the clearing and settlement process, including listing the correspondent accounts NCC holds for the main currencies it trades in.

{{< figure src="moex-settlement.png" >}}

If you wondered [why JP Morgan paid the coupons on dollar denominated Russian bonds](https://www.reuters.com/business/russian-sovereign-bond-payment-received-by-jpmorgan-processed-source-2022-03-17/), now you know.

If you check the sanctions list you'll note that these correspondent accounts are notable by their absence - [even VTB Bank](https://www.vtb.eu/en/news/vtb-bank-deutschland-ag-excluded-from-eu-sanctions). The ['historic sanctions'](https://www.myjoyonline.com/uk-foreign-secretary-liz-truss-announces-historic-round-of-sanctions/) somehow seem to have overlooked the obvious place where you would apply financial sanctions, if you actually wanted to affect Russia's ability to transact with the West.

Now that we know how the NCC operates we can describe how the gas payment transactions are likely to work and answer the questions “who is going to hold the EUR” and “where will the RUB come from”, both of which will lead to an interesting conclusion. Although not a surprising one if you know your monetary history.

We start with the initial payment from the EU gas buyer into their K account at Gazprombank. This is a standard transfer across TARGET2 from the source bank which leaves Gazprombank with increased ECB reserves.

{{< figure src="table-1.png" >}}

After that Gazprombank puts transfers the EUR from the K accounts onto the Moscow Exchange for auction, likely using the T+0 (EURRUB_TOD) [facility of the exchange](https://www.moex.com/en/markets/currency/). This may continue to go via JP Morgan, but it is more likely that NCC will maintain a correspondent account in EUR directly at Gazprombank, cutting out the risky middleman and a needless TARGET2 transfer. Within Gazprombank this results in the balances of the EUR K-accounts being transferred to the credit of NCC, and NCC creating EUR-denominated settlement 'chips' within its settlement system. Here we assume all the EUR balance is transferred and the auction position is fully pre-funded.

{{< figure src="table-2.png" >}}

The question now is who is going to provide the liquidity to the clearing house to allow the auction to conclude. There are few Russian bills that require EUR to settle, as nothing is being officially sold to Russia, and financial sanctions have made Russian entities averse to holding EUR at all. What that should do in an open market is send the Rouble sky high - with a great many EUR required to purchase any RUB. There just isn't the open market liquidity for anything else.

However because the exchange risk is still with Gazprom - remember that the pricing for their gas is still in EUR - that would mean Gazprom earning very few RUB for their work, which would cause major issues with funding production in Russia. Like all good Modern Mercantilist nations Russia has a central bank whose job it is to hoover up unwanted foreign currency and supply local currency against it - thereby stopping the exchange rate ascending into nosebleed territory. Prior to financial sanctions that is precisely what it would do, and is the reason why it amassed such a large amount of foreign assets (which are actually financial rubbish for an export led nation, not a 'war chest' as the uneducated like to portray them. They end up at the central bank, essentially, because nobody else wants them at the exchange rate the central bank wants to maintain).

After financial sanctions … the Bank of Russia will continue to do exactly the same thing, with a very slight alteration in procedure. That way it ensures that Gazprom gets a decent amount of RUB for its work.

In addition, since it has to hold the ECB reserves, it is likely that Gazprombank will bid in the auction.

To show how both sides resolve the liquidity issue, we assume here that in the auction Gazprombank gets half the EUR and Bank of Russia gets the other half at an exchange rate of 1:112. The settlement statements will be on a net basis. Bank of Russia will get a call for 5600 RUB, and Gazprombank will get a call for 0 RUB since the proceeds of the sale (11200 RUB) are greater than the cost of the purchase (5600 RUB). There will be no call for EUR since the position was pre-funded.

{{< figure src="table-3.png" >}}

Now the trades are settled within the NCC. Gazprombank can then withdraw funds from NCC and credit the RUB K-Account of the EU Buyer with their RUB. The 50 EUR Gazprombank 'won' in the auction is discounted into 5600 RUB by Gazprombank directly.

{{< figure src="table-4.png" >}}

Finally Gazprom can be paid in RUB

{{< figure src="table-5.png" >}}

In all international trades the buyer pays with the currency they have and the seller receives the currency they want to hold. Here we have shown how EUR magically transforms into RUB and how the RUB exchange rate is still kept under control by the Bank of Russia.

So what's the surprising conclusion. First a history lesson. During the cold war, following the invasion of Hungary, the Russians abandoned their US dollar deposits directly in American Banks and opened an account with a British Bank, the Narodny Bank, that happened to have Russian ownership. The British Bank then held the USD deposit directly with the US bank and the Russians held accounts with Narodny Bank denominated in USD. Since these things could only circulate in Europe they became known as 'Eurodollars'. A major role in the Eurodollar market was played by the Midland Bank, which is now part of HSBC who, you will note from above, remains the GBP correspondent bank for the NCC.

Note the final position in the balance sheet above. Gazprombank holds the actual deposit at the ECB, the NCC holds a correspondent position at Gazprombank, and the Bank of Russia holds its EUR liquidity in casino chips at the NCC - able to supply EUR to whoever needs them on the Moscow Exchange.

Say hello to the RuskiEuro.
* * *

_Chat about this and any other MMT topics on Discord with the growing [New Wayland community](https://discord.com). New members can click this [invite link](https://discord.gg/JN6HKUd) which will add the server to your Discord account_
