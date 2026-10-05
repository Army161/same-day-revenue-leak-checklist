# Card Fee Net Card

Assumes a card rail fee of 2.9% + $0.30, USD, no tax, no refund. Round fee to the nearest cent. This is a worksheet, not a quote from your processor.

| Price | Fee | Net |
| --- | --- | --- |
| 3.00 | 0.39 | 2.61 |
| 4.00 | 0.42 | 3.58 |
| 5.00 | 0.45 | 4.55 |
| 6.00 | 0.47 | 5.53 |
| 7.00 | 0.50 | 6.50 |
| 8.00 | 0.53 | 7.47 |
| 9.00 | 0.56 | 8.44 |

Formula: fee = round(price * 0.029 + 0.30, 2). Net = price - fee.

A $1 price nets about $0.67 and does not clear a $1 floor after fees. $3 is the smallest price on this card that does.

Not tax advice. Not a promise that a sale will happen.
