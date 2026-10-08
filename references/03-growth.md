# 03 · Growth

The core source is *Startup = Growth* [growth, Sep 2012]. All benchmarks below are from that 2012 essay,
written about YC startups at that time.

## A startup is a company designed to grow fast

> "A startup is a company designed to grow fast... The only essential thing is growth. Everything else we
> associate with startups follows from growth." [growth, Sep 2012]

In his account, what makes something a startup isn't being new, or technical, or venture-funded. It's
building something a lot of people want and being able to reach them. [growth] Growth then becomes the
tool for every decision: "You can use growth like a compass to make almost every decision you face."
[growth]

## Know your number, as a rate

"If there's one number every founder should always know, it's the company's growth rate." [growth] He means
the ratio of new to existing, not a count. "We get about a hundred new customers a month" is, in his words,
"not a rate." [growth] Measure revenue if you charge, active users if you don't. [growth]

**Benchmarks, as of 2012:** "A good growth rate during YC is 5-7% a week. If you can hit 10% a week you're
doing exceptionally well. If you can only manage 1%, it's a sign you haven't yet figured out what you're
doing." [growth, Sep 2012] YC measured per week partly because Demo Day was close and partly because early
startups need fast feedback. [growth]

| Weekly growth | Yearly multiple [growth] |
|---|---|
| 1% | 1.7x |
| 2% | 2.8x |
| 5% | 12.6x |
| 7% | 33.7x |
| 10% | 142.0x |

His own illustration: a company making $1000 a month and growing 1% a week makes $7,900 a month four years
later; at 5% a week it makes $25 million a month. [growth]

## Set a weekly target and let it decide

His method: "pick a growth rate they think they can hit, and then just try to hit it every week." [growth]
Anything that hits the target is right, with one explicit exclusion: "trickery like buying users for more
than their lifetime value, counting users as active when they're really not" and similar tricks. [growth,
note 8] Hitting a weekly target doesn't mean only looking a week ahead; it can justify a hire who pays off in
a month. [growth]

He applied the same rule in a 2026 office hours. A startup had three possible paths to getting huge, and he
told them "to optimize for growth rate and let that decide."
[X 2026-08-21](https://x.com/paulg/status/2090644637971263640) That was advice to one company, not a stated
general rule. **Our reading:** it's the 2012 compass idea applied to choosing between paths.

## How to apply (our suggestion)

The steps and thresholds here are ours, built on his rate-not-count rule.

1. **Pick the metric.** Revenue if you charge; otherwise active users, with "active" defined before you look
   at the data. [growth]
2. **Convert to a weekly rate.** If you only have monthly numbers, weekly rate = (1 + monthly rate)^(12/52)
   − 1. Weekly to monthly: (1 + weekly rate)^(52/12) − 1.
3. **Set a target you think you can hit**, and write it where the team sees it. [growth]
4. **Each week, record actual against target.** If you miss, find the cause before choosing next week's
   work.
5. **Diagnose slow growth in this order (ours):** churn first, then activation, then acquisition. He calls
   churn the worst reason for slow growth, because it means people tried the product and decided they didn't
   like it. [X 2026-03-10](https://x.com/paulg/status/2031492573697560705)
6. **Graph the rate, not just the total.** He suggests graphing the growth rate of the number you care
   about. [X 2026-03-19](https://x.com/paulg/status/2034756891818004629)

## Worked numbers (invented)

A startup says it grows *about 4% a month*.

- Weekly: 1.04^(12/52) − 1 = **about 0.9% a week.**
- His 2012 benchmark of 5-7% a week is, in monthly terms, 1.05^(52/12) − 1 ≈ **23.5%** to 1.07^(52/12) − 1
  ≈ **34%** a month.
- So 4% a month is below even the 1% a week that he says is "a sign you haven't yet figured out what you're
  doing." [growth]
- **Our reading:** the conversation should be about what users want, not about marketing. See chapter 02.

## Failure modes

- **Counting, not rating.** A hundred new customers a month says nothing about growth. [growth]
- **Faking it.** Buying users above lifetime value, or counting inactive users, is excluded by his own
  definition. [growth, note 8]
- **Leaky bucket.** Sign-ups grow but churn hides it. [X 2026-03-10]
- **Applying YC benchmarks to the wrong stage or business.** The 5-7% figure is for early startups during YC
  in 2012, with small bases. Our reading: a company with large revenue will grow more slowly in percentage
  terms, and that alone doesn't mean it's failing.
- **Growth as the only number.** Default alive still matters (chapter 04).

## Why it fixes the rest

He wrote in 2006 that "If you have decent growth, you'll win in the end, no matter how obscure you are now."
[startuplessons, Apr 2006] He also credits Joe Kraus with the idea that you make what you measure, and
suggests plotting users daily on a sheet of paper on the wall. [13sentences, Feb 2009] In 2026 he put it as
"No credential will get you more credibility with investors than growth."
[X 2026-09-01](https://x.com/paulg/status/2094839060711747596)

**Checks to run:**
1. What is your weekly growth rate, as a ratio, on revenue (or active users)?
2. What weekly target are you committed to? Did you hit it last week?
3. Is slow growth from not being known, from friction at sign-up, or from churn?
4. Is any of the growth "trickery" by his definition? [growth, note 8]
