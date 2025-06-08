# Income Distribution

> General rule: "from $20 to $100 per hour, considering all accumulated hours, balancing the effective rate."

Effective rate = the total amount of money paid by the cooperative to a member, divided by the total number of hours.

All of the following discussions concern only cooperative members. External participants are paid at the rate of $20/hour (or the agreed rate if the participant is very qualified/rare). However, nothing prevents the board of shareholders from deciding to pay part of the bonus to these participants as well.

## Example 1 

The cooperative has five members, each worked 500 hours for the cooperative, and the cooperative earned a profit of $50k. After receiving the profit, the cooperative will pay each `500*$20=$10k`. After paying the minimum rate, nothing remains to distribute.

## Example 2 

In the same cooperative, each member spent another 500 hours on the cooperative (that is, each has 500 paid and 500 unpaid hours), and after this, the cooperative started earning $100k/month, i.e., $1.2m/year (let's allow ourselves this dream). The profit will be distributed as follows:

- First, the new 500 hours for each will be paid at $20/hour, for which $50k will be allocated. $1.15k remains.
- About this $1.15k, the board of shareholders decides what part to pay the members and what part to direct to development (and for what exactly). The decision is limited by two rules: 1) not more than 50% on bonuses and 2) not more than $100/hour for every hour spent "since the beginning of time."
- Option a): leave everything for development. Then each hour remains paid at the minimum rate of $20.
- Option b): pay ourselves the maximum bonus, that is, each worked hour is brought up to the $100 rate. For one member, this requires: `1000h * ($100-$20) = 1000*80 = $80k`, and for five — `$400k`. We check that the bonus share in the profit does not exceed 50%: `$400/$1150=34.7%`.
- Option c): allocate for bonuses, say, 20%, the rest — for development. This turned out to be `$1.15m*20%=$230k` for bonuses. We divide this amount by the total number of hours (`5*1000`): `$230k/5k=$46`, that is, to the $20 that were already paid for each hour, we can add another $46.

## Example 3

Suppose in the previous example option c) was chosen, and for the next year the first participant worked 1000 new hours, and all the others 500 each. The profit remained unchanged, $100k/month=$1.2m/year.

- As before, we first pay the new hours at the minimum rate: `$20*(500*4+1000)=$60k`. The remaining amount is `$1200k-$60k=$1140k`.
- Option a). Suppose now we decided to spend 50% of the profit on bonuses, which will give us $570k. Let's see if we can "utilize" this money.
  - We calculate the effective rate of each participant:
    - for the first one: `($20*2000+$46*1000)/(500+500+1000)=$43/hour` (all 2000 hours were paid at the minimum rate of $20, and each of the 1000 old hours was rewarded with $46)
    - for all others: `($20*1500+$46*1000)/(500+500+500)=$50.4/hour`  (all 1500 hours were paid at the minimum rate of $20, and each of the 1000 old hours was rewarded with $46)
    - (In reality, you don't need to remember which hour was paid at what cost, you just need to keep track of the total number of hours and total amount of money paid for each participant.)
  - The effective rate allows calculating the unpaid bonus amount for each participant:
    - for the first, it is `($100-$43)*2000=$114k`
    - for the others, it is `($100-$50.4)*1500=$75.6k`
  - If we pay this money, a total of `4*$75.6k+$114k=$416.4k` will be paid, which is only 36% of the profit. The rule "not more than $100/hour" does not allow paying more.
  - After this payment, the effective rate for each becomes $100/hour until the end of the accounting period, where it will be "diluted" by new unpaid hours and reduced.
- Option b). Suppose we decide to spend only 10% of the profit on bonuses, which is $114k.
  - The calculation of the effective rate for each participant is the same as in option a).
  - The cooperative strives to equalize effective rates for each participant.
  - The average effective rate across the cooperative before the payment of bonuses will be:
    - a total of `1500*4+2000=8k` hours worked;
    - a total of `$20*8k=$160k` under the minimum rate and another $230k in bonuses, totaling $390k;
    - `$390k/8k = $48.75/hour` — this is more than the first participant but less than the other four.
  - The average effective rate after the bonus payment:
    - the same number of hours;
    - $114k more money, i.e., `$390k+$114k=$504k`;
    - a total of `$504k/8k=$63/hour` — this is more than any participant had.
  - To understand how much to pay everyone, we calculate the difference between each participant's effective rate and the average effective rate after the bonus, and multiply it by the total number of hours worked "since the beginning of time":
    - for the first: `difference=$63-$43=$20`, hours worked — 2000, `bonus=$20*2000=$40k`.
    - for others: `difference=$63-$50.4=$12.6`, hours worked — 1500, `bonus=$12.6*1500=$18.9k`.
  - After this procedure, the effective rates of all participants leveled and became $63.
  - [A situation may arise where the effective rates of individual shareholders are higher than the average effective rate after the bonus payment — in this case, these shareholders do not receive a bonus in this period. It is necessary to think through whether this will lead to strange results — and look for other boundary cases.]
