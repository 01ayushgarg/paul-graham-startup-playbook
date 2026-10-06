# Paul Graham's Startup Playbook

**An unofficial, fully sourced playbook and AI skill that runs "office hours" on your startup, built only
from Paul Graham's own essays and posts.**

Paul Graham co-founded Viaweb (sold to Yahoo in 1998) and Y Combinator (2005), which has funded over 3,000
startups including Airbnb, Dropbox, Stripe and Reddit. He has published more than 220 essays on
paulgraham.com. This repo turns 50 of them, plus 35 of his recent posts, into a method you can run on your
own company.

> "In a sense there's just one mistake that kills startups: not making something users want."
> Paul Graham, The 18 Mistakes That Kill Startups (2006)

> ⚠️ **Unofficial.** Not written, reviewed or endorsed by Paul Graham or Y Combinator. It's a structured
> guide in our own words, with short credited quotes and a link to every essay so you can read the original.

---

## What's inside

### The playbook

| # | Chapter | What you'll learn |
|---|---|---|
| 00 | [Who Paul Graham is](references/00-who-is-paul-graham.md) | Viaweb, YC, and the ideas YC was built on |
| 01 | [Startup ideas](references/01-ideas.md) | Notice, don't think up · sitcom ideas · dig a well · live in the future · schlep blindness |
| 02 | [Users and unscalable work](references/02-users-and-unscalable-work.md) | Make something people want · recruit by hand · delight · launch fast |
| 03 | [Growth](references/03-growth.md) | Startup = growth · weekly rate · 5-7% a week · growth as a compass |
| 04 | [Survival and money](references/04-survival-and-money.md) | Default alive or dead · the fatal pinch · ramen profitable · don't hire too fast |
| 05 | [Founders](references/05-founders.md) | Relentlessly resourceful · determination · persistent vs obstinate · cofounders |
| 06 | [Fundraising](references/06-fundraising.md) | Fundraising in one sentence · convincing investors · herd dynamics · the equity equation |
| 07 | [Running the company](references/07-running-the-company.md) | Speed and focus · founder mode · maker's schedule · hiring · the 18 mistakes |
| 08 | [Thinking for yourself](references/08-thinking-for-yourself.md) | Correct and novel · keep your identity small · what you can't say · how to disagree |
| 09 | [Great work and ambition](references/09-great-work-and-ambition.md) | How to do great work · superlinear returns · procrastination · cities |
| 10 | [Wealth](references/10-wealth.md) | Measurement and leverage · users are the proof · how people get rich now |
| 11 | [Writing and explaining](references/11-writing-and-explaining.md) | Write like you talk · write simply · explain it in two sentences |
| 12 | [How he judges a startup](references/12-how-yc-judges-startups.md) | Black swan farming · founders over ideas · the questions he asks |

### Templates

| Template | Use it to |
|---|---|
| [01 Idea test](templates/01-idea-test.md) | Pressure-test an idea with his 11 questions before you commit |
| [02 Default alive check](templates/02-default-alive-check.md) | Find out whether you live or die on current numbers |
| [03 Fundraising plan](templates/03-fundraising-plan.md) | Decide whether to raise, then run it his way |
| [04 Weekly office hours](templates/04-weekly-office-hours.md) | A 20-minute weekly review: the number, the three problems, users |

### Worked example

[Office hours, start to finish](examples/01-worked-office-hours.md): a fictional startup with invented
numbers, run through the whole skill.

---

## How to use this

### 1. Run it as an AI skill (10 minutes)

**Install** into your agent's skills folder. For Claude Code:

```bash
git clone https://github.com/01ayushgarg/paul-graham-startup-playbook \
  ~/.claude/skills/paul-graham-startup-playbook
```

If your agent doesn't read skill folders, paste `SKILL.md` into the chat and attach the chapters it asks for.

**Then ask for office hours.** Copy and fill in:

```text
Run Paul Graham-style office hours on my startup.

What we make (one or two sentences):
Who wants it right now, by name or type:
Where the idea came from:
Users / revenue today, and weekly growth rate:
Cash in the bank, monthly burn:
Founders, and how long we've worked together:
What we've learned from users recently:
What I want to talk about:
```

**You get back:** the real problem (often not the one you came with), whether you're default alive, at most
three priorities for this week, the unscalable thing to do now, the number to watch, the hard questions you
should be able to answer, and where you might be the exception. Every point cites the essay it comes from.

**Other things you can ask:**
- *"Is this a good startup idea?"*
- *"Am I default alive or default dead?"* (give it your numbers)
- *"Should I raise money now, and how much?"*
- *"Should we hire these three people?"*
- *"How do I get my first 100 users?"*
- *"What would Paul Graham say about this pitch?"*
- *"Help me pick what to work on."*

### 2. Use the templates (30 minutes, no AI)

1. [Idea test](templates/01-idea-test.md) before you commit.
2. [Default alive check](templates/02-default-alive-check.md) once a month.
3. [Weekly office hours](templates/04-weekly-office-hours.md) every week.
4. [Fundraising plan](templates/03-fundraising-plan.md) only when you decide to raise.

### 3. Read it

Start with chapter 01 if you're looking for an idea, 03 and 04 if you're running a startup now, 06 if
you're raising, and 08 and 09 if you're deciding what to do with your life.

**His own caveat:** "there are exceptions to practically every rule." Use this to sharpen your judgement,
not to replace it.

---

## How it stays honest

- **First-party only:** his essays and his posts. No summaries by other people.
- **Every quote checked by script** against the essay's raw text before publishing.
- **Every claim cited** with the essay's slug, which maps to a URL and date in [`SOURCES.md`](SOURCES.md).
- **Credit where he gives it:** ideas he attributes to others (Paul Buchheit, Joe Kraus, Sam Altman, Peter
  Thiel and more) are labelled.
- **Dated numbers stay dated:** growth benchmarks and fundraising figures carry the essay's year.
- **Our own reading is marked**, never presented as his words.

## Sources

The full list (50 pages from paulgraham.com and 35 posts on X, with titles, dates and links) is in
[`SOURCES.md`](SOURCES.md). The essays used most:

How to Get Startup Ideas · Do Things that Don't Scale · Startup = Growth · Default Alive or Default Dead? ·
The Fatal Pinch · Ramen Profitable · How Not to Die · Startups in 13 Sentences · The 18 Mistakes That Kill
Startups · The Hardest Lessons for Startups to Learn · What We Look for in Founders · Relentlessly
Resourceful · The Right Kind of Stubborn · Before the Startup · What Startups Are Really Like · How to Raise
Money · A Fundraising Survival Guide · How to Convince Investors · Founder Mode · Maker's Schedule, Manager's
Schedule · What I've Learned from Users · How to Do Great Work · Superlinear Returns · How to Think for
Yourself · How to Make Wealth · Write Like You Talk · Black Swan Farming.

## License

- **Our text** (chapters, skill, templates, structure): [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- **Quotes** remain Paul Graham's words. They're short, credited excerpts for commentary and are **not**
  covered by this license. Read the full essays at [paulgraham.com](https://www.paulgraham.com/articles.html).

See [`LICENSE`](LICENSE).

## Corrections

Spot a misquote or a broken link? Open an issue with the essay link.
