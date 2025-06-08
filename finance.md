# Income Distribution

> General rule: "from $20 to $100 per hour, considering all accumulated hours, balancing the effective rate."

Effective rate = the total amount of money paid by the cooperative to a member, divided by the total number of hours worked.

The following discussions pertain only to cooperative members. External participants are paid at a rate of $20/hour (or the agreed-upon rate if the participant is particularly skilled or hard to find). However, the board may also decide to award bonuses to these participants.

## Example 1 

The cooperative consists of five members, each of whom has worked 500 hours, resulting in a profit of $50k. After receiving the profit, the cooperative will pay each member `500*$20=$10k`. After paying the minimum rate, there is nothing left to distribute.

## Example 2 

In the same cooperative, each member contributes an additional 500 hours (meaning each has 500 paid and 500 unpaid hours), and subsequently, the cooperative begins earning $100k per month or $1.2m annually (hypothetically). The profit distribution works as follows:

- Initially, the new 500 hours for each member will be compensated at $20/hour, allocating $50k for this. This leaves $1.15m.
- The board decides how much of the remaining $1.15m will be paid to members and how much will be reinvested in development. This decision is governed by two rules: 1) not more than 50% for bonuses and 2) not exceeding $100/hour for each hour worked "since the inception."
- Option a): All funds are allocated for development. Thus, every hour is compensated at the minimum rate of $20.
- Option b): Distribute the maximum possible bonus, raising each hour to the $100 rate. For one member, this requires: `1000h * ($100-$20) = 1000*80 = $80k`, and for five members — `$400k`. Check that the bonus portion does not exceed 50% of the profit: `$400/$1150=34.7%`.
- Option c): Allocate 20% for bonuses and the rest for development. This leads to `$1.15m*20%=$230k` allocated for bonuses. Divide this amount by the total hours (`5*1000`): `$230k/5k=$46`, so an additional $46 can be added to each hour compensated at $20.

## Example 3

Suppose in the previous scenario option c) was chosen, and for the following year, the first member worked 1000 new hours while others worked 500 each. The profit remains constant at $100k/month or $1.2m/year.

- As before, new hours are compensated at the minimum rate: `$20*(500*4+1000)=$60k`, leaving `$1.2m-$60k=$1.14m`.
- Option a). Now we decide to spend 50% of the profit on bonuses, equating to $570k. Let's examine whether we can utilize this amount.
  - Calculate the effective rate for each participant:
    - For the first: `($20*2000+$46*1000)/(500+500+1000)=$43/hour` (2000 hours paid at minimum rate $20, and 1000 old hours boosted by $46 each)
    - For others: `($20*1500+$46*1000)/(500+500+500)=$50.4/hour` (1500 hours paid at minimum rate $20, and 1000 old hours boosted by $46 each)
    - (It is unnecessary to track individual hour payment rates, just the total hours and total payment for each participant.)
  - The effective rate enables calculation of the unpaid bonus amount for each participant:
    - For the first: `($100-$43)*2000=$114k`
    - For others: `($100-$50.4)*1500=$75.6k`
  - Paying these amounts would total `4*$75.6k+$114k=$416.4k`, making up only 36% of the profit. Rules limit further payment to not more than $100/hour.
  - After this payment, each participant's effective rate rises to $100/hour for the rest of the period, where it will decrease being diluted by new unpaid hours.
- Option b). Suppose we choose to allocate just 10% of the profit for bonuses, which is $114k.
  - The computation of the effective rate for each participant remains the same as in option a).
  - The cooperative aims to balance effective rates for each participant.
  - The average effective rate across the cooperative before bonus payout:
    - Total hours worked is `1500*4+2000=8k`;
    - Total payout is `$20*8k=$160k` for minimum rate plus $230k for bonuses, totaling $390k;
    - Hence, `$390k/8k = $48.75/hour` — higher than the first member's, but lower than the rest.
  - The average effective rate after bonus payout:
    - Total hours remain unchanged;
    - Earnings increase by $114k, totaling `$390k+$114k=$504k`;
    - Consequently, `$504k/8k=$63/hour` — exceeding any individual's previous rate.
  - To determine payment for each, subtract each participant's effective rate from the new average effective rate, and multiply by total hours worked "from inception":
    - For the first: `difference=$63-$43=$20`, with 2000 hours worked, `bonus=$20*2000=$40k`.
    - For others: `difference=$63-$50.4=$12.6`, with 1500 hours worked, `bonus=$12.6*1500=$18.9k`.
  - Following this, effective rates are balanced at $63.
  - [There could be cases where some members' effective rates exceed the new average rate after bonuses, resulting in no bonus for that period. These edge cases need careful consideration to avoid unexpected outcomes.]
