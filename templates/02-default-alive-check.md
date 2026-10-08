# Template 02 · Default alive or default dead?

The question is his [aord, Oct 2015]: if expenses stay constant and revenue keeps growing at the rate of the
last several months, do you reach profitability on the money you have left? PG mentions a calculator by
Trevor Blackwell for this [aord]. The arithmetic below is standard, not his. Do it monthly.

## Inputs

| Input | Symbol | Value |
|---|---|---|
| Cash in the bank | B | |
| Monthly expenses, assumed constant | E | |
| Current monthly revenue | R | |
| Monthly revenue growth over the last 3 to 6 months, e.g. 0.06 for 6% | g | |

If you only know weekly growth w: g = (1 + w)^(52/12) − 1.

## The formula

- Each month k: revenue R_k = R × (1 + g)^k; cash C_k = C_(k−1) + R_k − E, starting from C_0 = B.
- **Months to profitability:** n = ln(E / R) / ln(1 + g), rounded up.
- **Cash used before profitability** ≈ n × E − R × ((1 + g)^(n+1) − (1 + g)) / g.
- **Default alive** if that is less than B. **Default dead** if it's more: cash hits zero first.
- If g is zero or negative, you never reach profitability on this path. You're default dead unless R ≥ E
  already.

## Filled-in example (invented numbers)

B = $300,000 · E = $50,000 · R = $20,000 · g = 6% a month.

n = ln(50,000 / 20,000) / ln(1.06) = 0.916 / 0.0583 ≈ 15.7, so **month 16**.

| Month | Revenue | Cash at end of month |
|---|---|---|
| 1 | $21,200 | $271,200 |
| 2 | $22,472 | $243,672 |
| 3 | $23,820 | $217,492 |
| 6 | $28,370 | $147,877 |
| 9 | $33,790 | $93,616 |
| 12 | $40,244 | $57,643 |
| 15 | $47,931 | $43,451 |
| 16 | $50,807 | $44,258 |

Cash used before profitability ≈ 16 × $50,000 − $20,000 × (1.06^17 − 1.06) / 0.06 ≈ $255,700, which is
less than B. **Default alive:** revenue passes expenses in month 16, and the cash low point is about $43k in
month 15.

Same company at **g = 3%**: cash runs out in month 12, with revenue at about $28,500. **Default dead**, with
roughly 11 months of runway.

Our reading: three points of monthly growth separate a company that lives from one that needs investors to
survive.

## Your numbers

| Month | Revenue | Cash at end of month |
|---|---|---|
| 1 | | |
| 2 | | |
| 3 | | |
| ... | | |

## Then answer

1. Alive or dead? ______ Months to profitability (n): ______
2. If dead: months until cash runs out: ______. Is this the fatal pinch, default dead with slow growth and
   not enough time to fix it? [aord]
3. Plan B, written down: what you'd cut, and the date you switch to it. [aord] ______
4. Say it out loud: "We're default dead, but we're counting on investors to save us." Does it alarm you?
   [aord]
5. Any hires planned? He calls hiring too fast the biggest killer of startups that raise money. [aord]

If you're already in the pinch, his advice is to assume you can't raise more, then choose between shutting
down, making more and spending less. [pinch, Dec 2014]
