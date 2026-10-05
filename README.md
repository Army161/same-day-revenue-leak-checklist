# Same-Day Revenue Leak Checklist

One page. Twelve checks. Use it on a live checkout before you call a link revenue.

This file is the product. One sale is $3.00. Card fee is about $0.39 (2.9% + $0.30). Expected net about $2.61. Not a guarantee of sales. Not financial advice.

## How to use

Open the processor dashboard in live mode, not test mode. Run the checks in order. Write the evidence id next to each line (charge id, session id, or none). Stop at the first red item and fix that before buying traffic.

## The twelve checks

1. Live mode. Dashboard toggle says live. A test-mode payment is not cash.
2. Active price. The product has one active USD price at or above $3. A $1 price nets under $1 after the card fee.
3. Payment link loads. The public URL returns a checkout, not a 404 or inactive message.
4. Success path exists. After pay, the buyer gets the file, a redirect, or a confirmation that contains the download. A thank-you with no file is not delivery.
5. Charge status. Newest charge is succeeded, not requires_capture, processing, or failed.
6. Amount net of fees. Gross minus fee minus refunds is the only number that counts. Pending payout is not a second sale.
7. No self-charge. The card and email are not yours. Moving your own money is not profit.
8. Webhook or receipt. checkout.session.completed fired, or the receipt email went out. If neither, the buyer may have paid and received nothing.
9. Open disputes. Dispute count for this charge is zero. A dispute reverses the net.
10. Refund window. Digital file, delivered on the success redirect. Refund if the file does not open.
11. Payout account. Available balance currency is USD and a bank account is attached. Otherwise settlement sits in the processor.
12. One offer live. Do not add a second link until this one has a public URL and a delivery path.

## Evidence line

Date:
Payment link:
Charge id:
Gross:
Fee:
Refunds:
Net:
Delivered (yes/no):

## What this is not

Not a trading signal. Not a promise of profit. Not a reason to charge your own card.
