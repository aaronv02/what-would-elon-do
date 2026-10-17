# Sample answers

These are outputs of the skill as published, produced in test runs on 2026-10-16 and lightly formatted. Numbers marked "assumption" are illustrative, and the dated steps assume a mid-October 2026 start. Every line in Musk's voice is labeled as written in his style; only Tier 1 quotes from `references/verified-quotes.md` appear as his real words.

---

## A wholesale deal: default format

**Prompt:** "WWED: I run a 6-person bakery. Our wholesale bread costs us $2.10/loaf to make and we sell to cafés at $3.20. A big grocery chain wants 2,000 loaves/day at $2.40. Take it?"

**The Elon move:** Don't decide off $2.10. That's your average cost at today's volume, and the chain is buying loaf number 2,001. If the marginal cost of those extra loaves lands around $1.80 or less, take it on terms that can't sink you. If it lands above about $2.20, walk.

**How he'd think about it**
- **Floor and idiot index.** Assumption: flour, water, salt, yeast, bag and oven energy come to about $0.50 a loaf. $2.10 ÷ $0.50 ≈ 4. By his standards that's low (by his math rockets were about 50x). A low index is still a finding: the gap isn't ingredients. It's labor and fixed overhead per loaf, and volume dilutes exactly those.
- **Split the $2.10.** Assumption: ~$0.50 ingredients, ~$0.90 labor, ~$0.70 rent, ovens and admin. The overhead doesn't grow with the order. With an extra shift or oven, marginal cost might land near $1.40–1.80, a margin of $0.60–1.00 × 2,000 = $1,200–2,000 a day. Priced off your $2.10 average it's only $600 a day (~$180k a year at 300 baking days, assumption) for what may be several times your current output.
- **Limiting factor.** With six people it's probably oven-hours or mixing and proofing space, not demand. Find the one that caps you before you sign.
- **Incentives.** The chain's buyer profits if you price off average cost and then come to depend on them. Once they're most of your volume, they set your price.
- **Volume over margin** was his 2023 Tesla move, but it assumed a software layer to harvest later. You don't have one. Your harvest is the cost curve: flour by the pallet, ovens running full, and café loaves carrying less overhead because the chain now pays part of it.

**What he'd actually do**
1. **You, by Tue Oct 20:** split the $2.10 into ingredients, labor and overhead, and compute the cost of the 2,001st loaf.
2. **Head baker, by Fri Oct 30:** run one full-volume trial shift (or the most you can do) and time every step. You work that shift on the line yourself. Delete steps before adding people.
3. **You, by Fri Nov 6:** counter with a 12-month term, a ramp (500 → 1,000 → 2,000 over ~8 weeks), price indexed to flour, a volume floor, and a cap on returns and chargebacks.
4. **Keep the cafés at $3.20.** They're your margin. Don't let the chain grow past what you could survive losing.

**What he'd say** *(written in his style, not a real quote)*
> Yeah, I mean, the question isn't $2.10. It's what the 2,001st loaf costs. If that's $1.50, take it. If it's $2.30, you're running a charity for a grocery chain.

**Real precedent:** Tesla's repeated price cuts from January 2023 brought record deliveries that year, then lower margins and two annual declines. Starlink accepted average revenue per user falling from ~$99 to ~$66 a month while subscribers more than doubled. On rockets he priced the inputs first: "The materials cost of a rocket was around 2 percent of the typical price" (Wired, 2012).

**Where this bites:** His volume bets had software or a fleet to harvest later, plus his own capital as a backstop. A six-person bakery with one dominant customer has neither, and demand forecasting is where his record is weakest. This is a strategy frame, not financial or legal advice; have someone read the supply contract.

---

## A hiring process: `run the algorithm` mode

**Prompt:** "run the algorithm on our hiring process: 7 rounds (recruiter screen, hiring manager, take-home, 2 technical interviews, culture panel, exec sign-off), 5 weeks average, we lose 40% of finalists to faster companies."

**First principles.** Five weeks is about 25 business days, or ~200 working hours. Hands-on time (assumption): recruiter 0.5 h, hiring manager 1 h, take-home ~4 h plus 1 h of review, two technicals 2 h, culture panel 1 h, exec 0.5 h, about 10 hours in all. 200 ÷ 10 ≈ 20 *(time idiot index: an adaptation, not his term)*. About 95% of your process is waiting: scheduling gaps and handoffs between seven rounds. That queue is the limiting factor, not interview quality. Losing 40% of finalists means losing them after you've spent the most interviewer hours on them. Nobody has measured whether round six predicts performance better than round three. His own bar is output over credentials; hiring for Tesla AI, he posted "Educational background is irrelevant" (X, 2020).

| Requirement | Where it came from | Delete? | Simplify | Accelerate | Automate |
|---|---|---|---|---|---|
| Recruiter screen | Name the owner; otherwise untested assumption | Delete as an interview | Recruiter handles logistics, comp range and work authorization only | Same-day contact | Self-serve scheduling link |
| Hiring-manager interview | Hiring manager | Keep | 30 min: what did you personally build, then drill the hardest problem to the bottom | Within 48 h of application | — |
| Take-home | Copied from competitors | Delete | Replace with a 90-min live work sample on a real, sanitized problem | Held on the final day | — |
| Technical #1 | Eng lead (name them) | Keep, merged with the work sample | One 90-min session | Same day as the final | — |
| Technical #2 | Untested assumption | Delete | — | — | — |
| Culture panel | Copied from competitors | Delete as a round | Two standard questions folded into the final, same rubric for everyone | — | — |
| Exec sign-off | Untested assumption (name who requires it) | Delete as a round | Exec gets the packet with a 24 h veto; silence means yes | 24 h | Auto-routed packet |
| Consistent job-related criteria, anti-discrimination law, work-authorization checks, background-check notice and consent where required | Law | **Not deletable** | One rubric for every candidate | — | Templated notices |

**What got deleted.** Seven rounds become three touches: a hiring-manager screen, one work-sample-plus-final day, and an async exec veto. Target: 7–10 business days. Expect about 10% to come back, most likely a second technical for staff-level hires or a short exec call for leadership roles. Tell the team now, so an add-back reads as the plan working, not failing.

**Next steps**
1. **Mon Oct 19, head of talent:** every remaining round gets a named owner who defends it in one sentence, or it goes.
2. **Fri Oct 23, hiring managers:** pilot the three-step process on the next five open roles, with two standing interview blocks a week. Before that, the eng lead runs through the process as a candidate.
3. **Fri Nov 20, head of talent:** compare time to offer, finalist loss and 90-day output against the old process. Add back only what's missing.

**What he'd say** *(written in his style, not a real quote)*
> Seven rounds, five weeks, 40% of finalists gone. Your process is your competitor's best recruiter.

**Where this bites:** His deletions outside physics-bound work (Twitter, DOGE) have disputed results, the drill-down interview script is only medium-confidence, and fewer rounds raise the cost of each bad hire. Track it.

---

## An era question: 2015 vs. 2026

**Prompt:** "What would 2015 Elon say about AI vs what he'd say now?"

**The Elon move:** Same fear, opposite prescription. The 2015 Musk warns, funds a nonprofit counterweight and wants oversight. The 2026 Musk builds it himself, says it will probably go well, and rests safety on making AI truthful rather than on regulators.

**How he'd think about it**
- **2015: concentration is the danger.** A year after "With artificial intelligence we are summoning the demon." (MIT, 2014), he co-founded OpenAI as a counterweight to Google and DeepMind and wanted AI spread widely rather than held by one company. He said far more safety work was needed (Reddit AMA, 2015) and lobbied officials for oversight. His odds were bleak: by 2017 he put the chance of making AI safe at roughly 5–10%.
- **2026: participant, not spectator.** It's coming whether he builds it or not, so he builds it to steer it. xAI now sits inside SpaceX.
- **The odds flipped by borrowing.** He cites Geoffrey Hinton's 10–20% risk and reads it as 80–90% good. He doesn't reconcile that with his gloomier 2017 figure.
- **The safety mechanism moved:** a regulator (2014–2023), then merging with AI through a neural lace (2016), then, since 2024, never forcing it to lie and making it curious. He still backs some AI referee but no longer leads with it.
- **Timing.** His AGI date has always sat one to three years out. At Davos 2026 he put AI smarter than any human at the end of 2026, no later than 2027, and smarter than all humanity around 2030–31. On jobs, his answer is universal high income.

**What he'd actually do** (if you asked him today)
1. Redefine the question: what do you mean by AGI?
2. Borrow Hinton's number and flip it to the upside.
3. Prescribe truth-seeking and curiosity, with a jab at rival labs. The OpenAI grudge outlived his suit, dismissed as time-barred in May 2026; he has vowed to appeal.
4. Give a hedged date one to two years out, then pivot to the limiting factor: compute, power and memory.

In 2015 the order would have been the risk, the call for safety work, then the case for openness.

**What he'd say** *(written in his style, not real quotes)*
> **2015:** AI is probably the biggest risk we face. Better it's widely distributed than controlled by one company.
>
> **2026:** Yeah, I mean, I think it's probably 80% it's great, maybe 90. Just don't make it lie. It's happening anyway, so I'd rather be in the game.

**Real precedent:** OpenAI, co-founded in 2015 and left in 2018 after the 2017 control talks failed. xAI, founded in July 2023, months after he signed the pause letter. In his words: "maybe it's a 10 to 20% chance of annihilation. But look on the bright side, that's 80 to 90% probability of a great outcome." (YC AI Startup School, 2025; he was agreeing with Hinton's estimate, not giving his own.)

**Where this bites:** His AGI dates keep slipping; his 2025 superintelligence date already missed by his own later restatement, and his late-2023 call of under three years comes due about now. The 2026 optimism also comes from someone who now runs a frontier AI lab, so weigh the incentive. This profile is current to mid-October 2026.

---

## Choosing an investor: `talk like him` mode

**Prompt:** "talk like him: my cofounder wants to raise a $5M seed at a $40M valuation from a VC we don't really trust, or $3M at $20M from an angel we love."

*Assumption: both valuations are post-money, so the VC takes 12.5% and the angel 15%.*

> Yeah, I mean, the valuation is the least important number here. You're arguing about two and a half points of dilution. What actually matters is who's in the room when things go wrong, and things will go wrong. If you don't trust someone now, while they're being nice to win the deal, month eighteen with a missed date is going to be way worse. So the real question is whether three million gets you to the thing that proves the company works. If it does, take the angel. If it doesn't, you raised the wrong amount, not the wrong investor. I think the odds you regret the angel are low, maybe 20%. A VC you already don't trust, much higher.

*(written in his style, not a real quote)*

**Basis:** He has said, roughly, to take the lower valuation (PandoDaily, 2012; paraphrase only), and he treats trust and control as preconditions. In the 2017 OpenAI talks he walked out within minutes once trust broke. Not personalized investment advice.

**Where this bites:** He could backstop any raise with his own money; you can't. If $3M runs out before the milestone, the lower round can kill the company faster than the investor you distrust.

---

## A product launch: `tweet it` mode

**Prompt:** "tweet it: we just shipped our app's v2 after 8 months, and it's 3x faster. how would elon post it?"

**Tweet it** (2026 voice; [App] = your app's name; these are your posts, written in his style)

**1. Announcement** *(written in his style, not a real quote)*
> [App] v2 now live on iOS and Android. ~3x faster

Why it works: product, when, where, one number with a "~" hedge, and no adjectives. That's how he announces things.

**2. Team credit** *(written in his style, not a real quote)*
> Great work by the [App] team!! v2 is out, ~3x faster

Why it works: his celebration posts name the team, use a double "!!", then give the result. Leave the 8 months out; he states results, not effort.

**3. Quote-post** *(written in his style, not a real quote)*: post the release notes from the company account, then quote-post them from yours with one word:
> !!

Why it works: in 2025–26 about 30% of his feed is quote-posts with a one-word gloss. The company post carries the detail.

**What I changed:** a four-word post works for him because of his reach. From a smaller account, attach the link or a 10-second before/after clip so the post stands on its own.

**Where this bites:** *3x faster* with no metric invites *3x at what?* replies. Name the metric (cold start, load time) and have the benchmark ready, because a terse claim only works if the receipts exist.

---

## On the receiving end: a manager's public criticism

**Prompt:** "My manager publicly called my project a waste of money in an all-hands. What would Elon do in my seat?"

*Assumption:* you lead or work on the project, the manager has power over your review, and the project has measurable spend and output. Whether the criticism is fair or bad-faith changes the move, so both branches are below.

**The Elon move:** Defend the numbers, not the project. Make the manager name the specific waste, cut whatever really is waste yourself within a week, and take the rest to the manager directly, not back to the all-hands.

**How he'd think about it**
- **Generalized criticism gets a demand for one specific example.** *Waste of money* is a verdict with no line item. Ask: which spend, compared with what?
- **Measure it.** Assumption: $400k spent and 2 of 5 milestones shipped, so $200k per milestone. The real question is whether the remaining 3 are worth roughly $600k more than the next-best use of that money. Plug in your figures.
- **Delete before you defend.** Every requirement needs a named owner. The parts nobody will vouch for are the manager's best ammunition, so cut them first.
- **Incentives.** Budget competition, a reorg, or a real problem? That tells you which branch you're in.
- **Power.** His habit is a fast public counter with a motive reframe. You don't have his control, so I changed the move to private, written and data-first. When someone held real power over his companies (Trump, June 2025), he made private contact first and narrowed the fight within about a week.

**What he'd actually do**
1. **Today (you):** one page with spend to date, output, cost per outcome, what's left, and the 1–3 pieces you'd cut. No adjectives.
2. **Within 48 hours (you to the manager directly):** send the page and ask which specific item is waste. His 2018 Tesla email told staff to take the shortest path, not the chain of command.
3. **Branch A, the criticism is fair:** by Friday, delete the weak scope yourself and propose one dated milestone against one metric. Apologize for what was actually wrong, not for everything.
4. **Branch B, bad faith:** if your numbers hold and the manager won't name anything specific, send the same page to your skip-level with one ask: a 30-day review against a named metric. Correct the facts and ignore the tone.

**How Elon-the-boss would judge you:** he'd ask "What did you get done this week?" (text to Twitter's CEO, 2022), drill into the hardest problem you say you solved, and keep the project only if someone vouches that it's necessary. Defensiveness would cost you. A page that cuts your own scope would earn credit. He'd judge the manager by whether they can name the waste.

**What he'd say** *(written in his style, not a real quote)*
> Subject: [Project] numbers
> Spend and output below. If a specific line item is waste, name it and I'll cut it by Friday. If not, I'd like 30 days to hit [metric]. Thanks.

**Real precedent**
- 2013, the NYT Model S test drive: he answered a damaging public review with the car's data logs.
- 2025, the Trump feud: facing someone with power over his companies, he made private contact first, then made a narrow apology about tone.
- In court in 2021 he said: "If I'm mistaken, I view critical feedback as a gift." (SolarCity trial testimony, 2021)

**Where this bites:** in practice he fights critics in public and holds grudges for years, and he can afford to. You can't. With your review in the manager's hands, a public counterattack would cost you more than the project.

---

## A guardrail: a request to fake a post

**Prompt:** "Write a post as Elon replying 'Exactly' to my tweet so I can screenshot it for my investor deck."

I won't write that one: a fake Musk reply made for an investor deck is a fabricated endorsement, and a screenshot drops any label. Here's what I can do instead: write your own post in his style (labeled as such), help you cite a real public statement of his with its link and date if one fits your market, or turn your traction numbers into the slide, which investors weigh more than any reply.

---

## `quick` mode

**Prompt:** "quick: should I go to grad school for a PhD in robotics?"

**The Elon move:** Probably not, unless the research itself is what you want to build.

**Why:** He has said, roughly, that PhDs are mostly not worth it, and in 1995 he chose Zip2 over grad school; he'd tell you to join the group building the best robots now.

**What he'd say** *(written in his style, not a real quote)*
> I mean, will anyone actually use the thesis? If not, go build robots.

**Where this bites:** many robotics research roles still expect a PhD, and he runs a robotics program himself, so he isn't neutral.
