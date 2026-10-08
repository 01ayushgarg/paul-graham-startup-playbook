# 04 · Survival: runway, ramen profitability, not dying

> "If you can just avoid dying, you get rich. That sounds like a joke, but it's actually a pretty good
> description of what happens in a typical startup." [die, Aug 2007]

## Default alive or default dead?

His question, from *Default Alive or Default Dead?*:

> "Assuming their expenses remain constant and their revenue growth is what it has been over the last
> several months, do they make it to profitability on the money they have left?" [aord, Oct 2015]

"Half the founders I talk to don't know whether they're default alive or default dead." [aord] He adds that
worrying too early costs little, while worrying too late is very dangerous, and that the question doesn't
make sense to ask very early on. [aord] He mentions a calculator by Trevor Blackwell for working it out.
[aord]

### The arithmetic (standard, not his)

With cash B, constant monthly expenses E, current monthly revenue R and monthly revenue growth g:

- Each month: revenue = previous revenue × (1 + g); cash = cash + revenue − E.
- **Months to profitability:** n = ln(E / R) / ln(1 + g).
- **Default alive** if cash is still above zero in month n. **Default dead** if it hits zero first.

Two invented examples (worked in full in `templates/02-default-alive-check.md`):

| B | E | R | g (monthly) | Result |
|---|---|---|---|---|
| $300k | $50k | $20k | 6% | Alive: profitable in month 16 with about $44k left |
| $300k | $50k | $20k | 3% | Dead: cash runs out in month 12, revenue still under $30k |

Our reading: the difference between those two companies is three points of monthly growth. That is why
chapter 03 and this one belong together.

He also warns against treating investors as the plan. With steep revenue growth, "say over 5x a year", you
can start to count on investor interest, but only start, because investors are fickle. So you should always
have a written plan B: what you'd do to survive without new money, and when you'd switch. [aord]

## The fatal pinch

> "The fatal pinch is default dead + slow growth + not enough time to fix it." [aord]

In *The Fatal Pinch* he gives three reasons the next raise is harder than the last: you're spending more,
investors have higher standards for companies that already raised, and "The company is now starting to read
as a failure." [pinch, Dec 2014] YC's advice is to act as if any money you raise is the last you'll get.
[pinch]

If you're already in it, his advice is to assume the probability of raising more is zero, then choose:
"you can shut down the company, you can increase how much you make, and you can decrease how much you
spend." [pinch] On making more, he suggests asking customers "what do you need that you'd pay a lot for?"
rather than pitching your product. [pinch]

## Don't hire too fast

> "Hiring too fast is by far the biggest killer of startups that raise money." [aord]

He reads big staffs at successful startups as more the effect of growth than its cause. [aord] In a 2022
post he gave the timing: startups usually take a year or two to work out exactly what their business is,
and "The biggest preventable cause of failure is spending too much money, by hiring too many people, during
this period." [X 2022-07-24](https://x.com/paulg/status/1551276104056311809)

His 2005 version was blunter: "The most important way to not spend money is by not hiring people." [start,
Mar 2005] In 2019 he suggested being really cheap, because it saves you from hiring too many people, renting a
fancy office and buying growth. [X 2019-08-11](https://x.com/paulg/status/1160445442464739328)

## Ramen profitable

> "Ramen profitable means a startup makes just enough to pay the founders' living expenses." [ramenprofitable,
> Jul 2009]

Its main value, in his account, is that it buys you time. [ramenprofitable] He lists better terms and more
interest from investors, higher morale, and freedom from the distraction of fundraising. [ramenprofitable]
The risk: it can turn you into a consulting firm. He calls it "a trick for not dying en route."
[ramenprofitable]

## Morale is the real cause of death

> "When startups die, the official cause of death is always either running out of money or a critical
> founder bailing... But I think the underlying cause is usually that they've become demoralized." [die]

"Startups rarely die in mid keystroke. So keep typing!" [die] The danger sign is a sentence ending in "but
we're going to keep working on the startup" [die], because "The number one thing not to do is other things."
[die] And on deals: "Deals fall through." [13sentences, Feb 2009]

## How to apply (our suggestion)

1. **Run the arithmetic monthly** with the template, using the last three to six months of growth.
2. **If dead, write the plan B the same day:** what you'd cut, in what order, and the date you'd switch.
   [aord]
3. **Freeze hiring** until the company is default alive or growth clearly pays for the hire. Our threshold,
   not his.
4. **Check for the pinch:** default dead, slow growth, under about 12 months of runway (our cut-off). If all
   three, apply his three options: shut down, make more, spend less. [pinch]
5. **Check for other things.** Any second job, side project or "while we wait" plan? [die]

## Failure modes

- **"We'll raise."** Saying "We're default dead, but we're counting on investors to save us" out loud is his
  test. [aord]
- **Hiring ahead of the business.** [aord, X 2022-07-24]
- **Ramen trap:** profitable through consulting work that stops you building the product. [ramenprofitable]
- **Using an old growth rate.** The question is about recent months, not the best quarter. [aord]

**Checks to run:**
1. Default alive or default dead? Show the arithmetic.
2. Runway in months, at current burn.
3. Plan B written down: what you'd cut, and the date you'd switch. [aord]
4. Any hire planned before you know what the business is? [X 2022-07-24]
5. Is anything pulling you away from the startup while you tell yourself you're still on it? [die]
