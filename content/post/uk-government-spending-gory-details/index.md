---
title: "UK Government Spending - The Gory Details"
summary: "Precisely how Parliamentary authority to spend ends up as a payment in somebody's bank account, including the banking transactions that occur across the Government Banking Service to make that happen."
date: 2021-02-21T09:57:11Z
tags: [mmt, payments]

---

{{<figure src="drawing-on-supply.png" alt="Drawing on Supply">}}

It’s taken a great deal of work to get there, but now we have an approach that models the UK government financing system sufficiently accurately that it could be run on actual banking equipment.

Here are the Gory Details. 

The first step is for a department to request financing for its monthly commitments from HM&nbsp;Treasury. HM&nbsp;Treasury then asks the [Comptroller and Auditor General (C&AG)][3] for permission to finance that commitment. The C&AG is an officer of the House of Commons and is appointed by The Queen. This office checks that the requests from Treasury have been approved by Parliament. If they have, then C&AG will authorise the expenditure. 

The monthly allowance is then transferred from the Supply Account the Consolidated Fund holds at the Government Banking Service (GBS) to the department’s drawing account, also held at GBS. As a banking transaction the source account is the Supply Account and the destination account is the Departmental Drawing Account. 

The Supply Account is permanently overdrawn from the point of view of HM&nbsp;Treasury and the Consolidated Fund, which makes it an asset of Government Banking. 

{{<figure src="step-1a.png" alt="Step 1a">}}
{{<figure src="step-1b.png" alt="Step 1b">}}

Each day, departments set up payments via the BACS from their drawing accounts to whoever they have to pay to meet their obligations. The source account for these transactions is the department’s drawing account at GBS and the destination account is the payee’s account at a commercial bank. However, they use BACS grade 3 (government grade) for these transactions, which allows them to specify a ‘source of funds’ (Nostro) account and, because it is grade 3, that source of funds can be outside the originating bank (GBS). In this case, the Drawing account of the GBS at the Bank of England(BoE), and it is this account that eventually settles the payment. 

BACS is a three day process, and the aggregate amount of all the ‘in flight’ transactions is notified to HM&nbsp;Treasury as a cash flow forecast. In readiness for BACS settlement, HM&nbsp;Treasury adds cash to the Drawing account at the Bank of England from the Consolidated Fund’s Exchequer account at the Bank of England. The source account is the Exchequer Account at the Bank of England and the destination account is the Drawing Account of GBS at the Bank of England. In parallel, GBS makes the mirror transaction with a source of the Drawing Account mirror at GBS and a destination of the Supply Account at GBS. That clears the drawing accounts ready to make payments into the banking system.

The net result of these [Correspondent Banking][2] transactions is to move part of the Consolidated Fund’s overdraft from GBS to the BoE.

{{<figure src="step-2.png" alt="Step 2">}}

Now individual BACS payments can be settled in Sterling across the banking system by movement of funds at the Bank of England

{{<figure src="step-3.png" alt="Step 3">}}
{{<figure src="step-4.png" alt="Step 4">}}

Remember that this is a model of the payments system, which necessarily abstracts away from some complexity (in this case the intermediate steps within BACS) to reveal the essence of what is happening.

Is it exactly what happens at GBS? Unfortunately we will never know since both HM&nbsp;Treasury and HM Revenue and Customs are rather fond of quoting Freedom of Information exemptions whenever questions about the GBS arise. All of which is rather bizarre given that the [function of this part of government was widely documented prior to the 1990s.][1] 

Is that is because they have something to hide? Like HM&nbsp;Treasury, that is something I could neither confirm nor deny. 

[1]: https://amzn.to/3pDwzDJ
[2]: https://www.fatf-gafi.org/glossary/
[3]: https://www.nao.org.uk/about-us/
