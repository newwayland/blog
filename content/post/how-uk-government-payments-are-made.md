---

title: "How Money is Created in the UK"
summary: "Money is created in the UK by order of HM Treasury. Here's how it works"
date: 2020-12-26T09:00:00Z
tags: [mmt, uk-accounting-study, payments]

---

![Tenners](images/tenners.jpeg)
For the past few months I’ve been working with Andrew Berkeley and Richard Tye helping them complete [“An Accounting Model of the UK Exchequer” which has been published online by GIMMS as a working document](https://gimms.org.uk/2020/12/26/accounting-model-uk-exchequer/).

The study is a tour-de-force of research and history by Andrew and Richard, and I’m very grateful to have been invited in to assist with the accounting and systemic analysis of the structures that lie at the heart of the UK monetary system and add my little bit to the document. However I do stand on the shoulders of giants. 

The study proves conclusively that the source of ‘moneyness’ in the UK is the Consolidated Fund, and that the whole of the Sterling currency area derives from its activities  - to the extent that we can show that the ‘net financial wealth’ of the non-government sector that arises from the MMT viewpoint is precisely balanced by a ‘sui generis’ asset that sits on the balance sheet of the Consolidated Fund. A balance sheet that is never fully drawn up anywhere.

The Bank of England is just a bank and operates in the same manner as any other bank (to the extent that it [requires capital injections from HM Treasury](https://www.bankofengland.co.uk/-/media/boe/files/letter/2018/chancellor-letter-210618.pdf) to maintain its loss adjusting buffers).  A bank that is and remains, both legally and structurally, subsidiary and subservient to HM Treasury in all ways. Its primary task is to discount liabilities imposed upon it by HM Treasury into bank liabilities. It does that by order of HM Treasury, has done since at least the 19th century, and continues to do so today. The Bank has no legal authority to refuse those orders.

On a morning the Consolidated Fund account at the Bank of England starts with a zero balance. The first order of business is to authorise and transfer sufficient funds from the Consolidated Fund to the Paymaster General Supply Account(s) ready to clear BACS payments initiated three days earlier. The journal for that looks like this

{{< rawhtml >}}
<table>
  <tr>
   <td>
   </td>
   <td colspan="4" ><strong>Journal</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Entity</strong>
   </td>
   <td colspan="2" ><strong>Assets</strong>
   </td>
   <td colspan="2" ><strong>Liabilities</strong>
   </td>
  </tr>
  <tr>
   <td rowspan="2" ><strong>Consolidated Fund (CF)</strong>
   </td>
   <td rowspan="2" >From PMG Supply
   </td>
   <td rowspan="2"  style="text-align: right">
+20

   </td>
   <td rowspan="2" >To BoE
   </td>
   <td rowspan="2"  style="text-align: right">
+20

   </td>
  </tr>
  <tr>
  </tr>
  <tr>
   <td rowspan="2" ><strong>Bank of England (BoE)</strong>
   </td>
   <td rowspan="2" >From CF
   </td>
   <td rowspan="2"  style="text-align: right">
+20

   </td>
   <td rowspan="2" >To PMG Supply
   </td>
   <td rowspan="2"  style="text-align: right">
+20

   </td>
  </tr>
  <tr>
  </tr>
  <tr>
   <td rowspan="2" ><strong>PMG Supply</strong>
   </td>
   <td rowspan="2" >From BoE
   </td>
   <td rowspan="2"  style="text-align: right">
+20

   </td>
   <td rowspan="2" >To CF
   </td>
   <td rowspan="2"  style="text-align: right">
+20

   </td>
  </tr>
  <tr>
  </tr>
</table>
{{< /rawhtml >}}

Government has a special BACS grade designed just for government payments (BACS Grade 3, or government grade - as distinct from the other two ‘Consumer grade’ and ‘Bank grade’). This allows the HM Treasury to use a different account at the Bank of England as the source of payment, as distinct from the account where the debit will be applied. That ‘Nostro’ account is the Paymaster General Supply Account. (Nostro/Vostro processes are ancient banking mechanisms arising in Italy during the Renaissance).

The result is that the Consolidated Fund account at the Bank of England is debited and the PMG Supply account is credited with whatever amount is required and the BACS transfer takes place - drawing from the PMG Supply account to pay everybody that is scheduled to be paid by the government today.

Now you would think that means the Consolidated Fund runs an overdraft, and in one sense you’d be right. However in the UK that doesn’t quite apply because [the law states the following](https://www.legislation.gov.uk/ukpga/Vict/29-30/39/section/11): 

> All moneys paid into the Bank of England on account of the Exchequer shall be considered by the Governor and Company of the said Bank as forming one general fund in its books; and all orders directed by the Treasury to the Bank for issues out of credits to be granted by the Comptroller and Auditor General, as herein-after provided for the public service, shall be satisfied out of such general fund

Which means that the Bank has to treat all accounts of the Exchequer as one. If you had a current account and a savings account, the bank would charge overdraft fees if you went overdrawn on the current account - regardless of what you had in the savings account. The Bank of England can’t do that to HM Treasury as the law forbids it.

So what is the offsetting account? This is the job of the Debt Management Account (DMA) run by the Debt Management Office (DMO). The task of the DMO is to drain money from the banking system to offset the injections that are coming from the rest of HM Treasury. And it does this by exchanging gilts and Treasury bills for the excess money HM Treasury is constantly adding to the bank system. 

This process runs alongside the payment system in real time and is coordinated by cash flow reports from the rest of HM Treasury to the DMO several times a day. DMO tries very hard not to disrupt the money markets with its activities, while at the same time aiming to offset HM Treasury’s activity at a net cost that is less than the default alternative - which is just to leave the banking system with the extra money. The DMO explains the process [in its annual review](https://www.dmo.gov.uk/media/17019/gar1920.pdf):

> The DMA is used to manage the Exchequer’s net cash position. Balances in central government accounts contained within the Exchequer pyramid are swept on a daily basis into the NLF and the DMA is required to offset the resultant NLF balance through its borrowing and lending in the money markets. The DMA is held at the Bank of England and a positive end-of-day balance must be maintained at all times; it cannot be overdrawn. Automatic transfers from the government Ways and Means (II) account at the Bank of England would offset any negative end-of-day balances, though it is an objective to minimise such transfers.

Although the DMO has a very good idea of what payments will be going out on a particular day, what it doesn’t know is how much tax will flow into HMRC’s general account at the Bank of England. That is very much the stuff of educated guesses. 

Since this uncertainty may lead to the DMA becoming overdrawn, and it is a KPI of DMO to avoid that, the DMA maintains a variable positive balance overnight as a buffer against this cash flow forecast uncertainty. 

So where does this buffer come from? Surely it is borrowed in the market? Well when you analyse the processes and net them off, as we have done in the study, you find that it is an identical mechanism to a capital injection by HM Treasury. It is entirely illusionary. There to make the numbers look good and allow a net movement around ~+£1bn rather than zero. The non-government sector actually has no less money overall.
