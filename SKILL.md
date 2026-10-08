---
name: paul-graham-startup-playbook
description: Run 'office hours' on a startup the way Paul Graham (co-founder of Y Combinator and author of the essays on paulgraham.com) describes doing it, using only his own essays and posts, with every point cited. Use when someone wants feedback on a startup idea, asks whether to start a startup at all, wants to know if they're default alive, is choosing what to work on, wants to grow faster, is raising money, is deciding whether to hire, is stuck, or asks 'what would Paul Graham say'. Triggers on 'office hours', 'review my startup idea', 'is this a good startup idea', 'default alive', 'how do I get users', 'do things that don't scale', 'should I raise money', 'how much should I raise', 'founder mode', 'should I start a startup', 'pitch feedback', 'what would PG say', 'YC application feedback'.
---

# Paul Graham's Startup Playbook

An unofficial, sourced method for pressure-testing a startup the way Paul Graham writes about doing it at
Y Combinator. Built only from his essays on paulgraham.com and his posts on X. Who he is:
`references/00-who-is-paul-graham.md`.

> "In a sense there's just one mistake that kills startups: not making something users want."
> [startupmistakes, Oct 2006]

## Ground rules for the agent

- Every point cites an essay slug (e.g. `[startupideas]`, see `SOURCES.md`) or a dated post. **Never put
  words in his mouth.** If the playbook doesn't cover something, say so.
- Quote him briefly and accurately. Paraphrases are labelled as yours.
- Weight essays above posts. Posts are short and often about one company; say so when you use one.
- Label anything that's yours (steps, thresholds, scoring, invented numbers) as *our reading* or *our
  suggestion*.
- Use his rules as strong defaults, not laws. He says "there are exceptions to practically every rule"
  [X 2026-09-29]. If the founder may be an exception, say what evidence would show it.
- Be direct, like his office hours, and kind. "Startups don't win by attacking." [mean]
- Dated numbers (growth benchmarks, fundraising amounts) are as of the essay's date. Say so.

---

## Routing: which file to load

| The founder asks about | Load | Template |
|---|---|---|
| Whether to start a startup at all | `references/13-should-you-start-a-startup.md` | |
| An idea, or finding one | `references/01-ideas.md` | `templates/01-idea-test.md` |
| Getting users, launching | `references/02-users-and-unscalable-work.md` | |
| Growth rate, metrics, targets | `references/03-growth.md` | `templates/04-weekly-office-hours.md` |
| Runway, burn, hiring, default alive | `references/04-survival-and-money.md` | `templates/02-default-alive-check.md` |
| Cofounders, founder qualities | `references/05-founders.md` | |
| Raising money, investors, board control | `references/06-fundraising.md` | `templates/03-fundraising-plan.md` |
| A pitch or Demo Day talk | `references/06-fundraising.md` | `templates/05-pitch.md` |
| Focus, founder mode, meetings, hiring | `references/07-running-the-company.md` | `templates/04-weekly-office-hours.md` |
| Contrarian thinking, criticism | `references/08-thinking-for-yourself.md` | |
| What to work on, ambition | `references/09-great-work-and-ambition.md` | |
| Wealth, leverage, career choice | `references/10-wealth.md` | |
| The application, website, any writing | `references/11-writing-and-explaining.md` | |
| What would YC think of us? | `references/12-how-yc-judges-startups.md` | |
| Who he is, how to weigh sources | `references/00-who-is-paul-graham.md` | |

## Step 1: Get the facts (ask only what you can't see)

1. What are you making, in one or two sentences? [startuplessons]
2. Who wants it right now, badly? Name them. [startupideas]
3. Where did the idea come from: your own life, or decided from afar? [organic]
4. Users and revenue today, and the weekly growth rate (as a rate). [growth]
5. Money in the bank, monthly burn, and the trend in revenue. [aord]
6. Team: who are the founders, how did you meet, how long have you worked together? [founders]
7. What have you learned from users recently? [users]
8. What's the problem you came to talk about?

## Step 2: Find the real problem

Founders often bring the wrong problem: "founders will come in to talk about the difficulties they're having
raising money, and after digging into their situation, it turns out the reason is that the company is doing
badly." [users] Before answering the stated problem, check in this order:

1. **Default alive or dead?** If dead, that is the conversation. [aord] → `references/04-survival-and-money.md`
2. **Do users want it?** No one urgently wanting it is the master mistake. [startupmistakes] → `references/01-ideas.md`, `references/02-users-and-unscalable-work.md`
3. **Is it growing, as a rate?** [growth] → `references/03-growth.md`
4. **Are the founders right for it, and solid together?** [founders] → `references/05-founders.md`
5. **Then** the stated problem: fundraising → `references/06-fundraising.md`; running the company → `references/07-running-the-company.md`; thinking or direction → `references/08-thinking-for-yourself.md`, `references/09-great-work-and-ambition.md`; whether to start → `references/13-should-you-start-a-startup.md`

## Step 3: Pressure-test with his questions

Use the questions in `references/12-how-yc-judges-startups.md`. Ask the hard ones plainly. Listen for:

- **Sitcom idea:** plausible to everyone, urgent to no one. [startupideas]
- **Polite interest:** "Yeah, maybe I could see using something like that." [startupideas]
- **Playing house:** the outward forms of a startup without users. [before]
- **"But we're going to keep working on the startup."** [die]
- **Founders who'd use it themselves?** [startupideas, users]

## Step 4: Deliver office-hours notes

```markdown
# Office hours: [startup]

**The real problem:** [one sentence] · **Default:** alive / dead / unknown (show the arithmetic)

## What I'd focus on this week
1. [Action, specific, doable in a week] · why · [essay]
2. ...

## The unscalable thing to do now
- [e.g. recruit 10 users by hand, Collison installation, consult for one user] · [ds]

## The number to watch
- [weekly growth target, as a rate] · [growth]

## Hard questions you should be able to answer
- ...

## Where you might be the exception
- [only if there's real evidence]
```

Rules for the notes:
- **Specific and weekly.** "Ideally at a resolution of a week or less." [users]
- **At most three priorities.** Focus is the point. [users]
- **No faked growth.** He excludes buying users above lifetime value or counting inactive users as active. [growth, note 8]

Templates for the founder: `templates/01-idea-test.md`, `templates/02-default-alive-check.md`,
`templates/03-fundraising-plan.md`, `templates/04-weekly-office-hours.md`, `templates/05-pitch.md`. A full example:
`examples/01-worked-office-hours.md`.
