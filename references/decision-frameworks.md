# How Musk Reasons and Decides

> **Quotes here are evidence. In answers, quote Musk verbatim only from Tier 1 of verified-quotes.md.**
> Citation keys (research passes A–H, fact-check rows "V1/V2 row N", "H §N") resolve in [`../research/sources.md`](../research/sources.md) and the other files in `../research/`.

Current to 2026-10-16.

**Labels.** [verified] = checked against a primary source (transcript, document, court exhibit or archived post). [reported] = a reputable outlet or his biographer, not checked against a primary. [contested] = disputed, with both sides given. [unverified] = not confirmed; use only with the label.

**Quote tags.** [O] official/human transcript or original document · [A] machine transcript checked in context · [P] archived X post · [R] reputable report or print interview.

**Sources.**
- Lex Fridman #252 (Dec 2021), #400 (Nov 2023), #438 (Aug 2024): lexfridman.com transcripts; #252 via Lexicap/Wayback.
- Rogan #NNNN: podscripts.co.
- TED 2013/2017/2022: ted.com transcripts.
- Talks on YouTube: Khan 2013 (vDwzmJpI4io), YC 2016 (tnBQmEqBCY0), YC 2025 (cFIlta1GkiE).
- Rev transcripts: DealBook 2023, Davos 2026.
- Wired 2012: wired.com/2012/10/ff-elon-musk-qa/
- New Space 2017: doi.org/10.1089/space.2017.29009.emu
- Tesla and SpaceX calls: fool.com / rev.com.

---

## 0. The model in one screen

His loop, as he describes it and as his conduct shows (2003–2026):
1. **Reframe the question** until it is "least wrong" (Lex #438).
2. **Find the physics floor:** what do atoms and energy allow? Everything above it is negotiable.
3. **Size the gap in orders of magnitude.**
4. **Ask who profits from the gap** (incentives) before asking which technology closes it.
5. **Run the algorithm:** requirements → delete → simplify → accelerate → automate.
6. **Attack the current limiting factor in person;** predict the next one.
7. **Go/no-go:** is success *possible*, and does it matter? Not: is it likely?
8. **Iterate in hardware,** test to failure, never with human lives.
9. **Most aggressive internal date,** padded portfolio targets, acceptance of lateness.

| Framework | 2002–2015 | 2016–2022 | 2023–Oct 2026 (now) |
|---|---|---|---|
| First principles | Rocket/battery cost floors; "physics approach" only for "something new" (TED 2013) | Factory as product | Applied to AI compute, power, space data centers, government; the phrase itself is rare in casual talk |
| Algorithm | "Simplicity… fewer components" (2003); "I don't believe in process" (2012) | Practiced (2018 fluff test, 2022 Raptor deletions), not yet named | Five steps stated in full (Lex #438); "Best part is no part" (2025); DOGE with disputed results |
| Limiting factor | Engineering talent (WBW 2015) | Battery cells | Chips, power, memory, said in nearly every talk |
| Odds | SpaceX "maybe 10%" | "Branching stream of probabilities"; AI safety "5 to 10 percent chance of success" (2017) | Hinton's 10–20% doom flipped to 80–90% good; SpaceX retold as "maybe 1%" |
| Vertical integration | Cost: "overhead to the fifth power" | "Because others aren't doing it" | Existential: Terafab, power, SpaceX–xAI merger |
| Deadlines | Falcon 1 "March of next year" (2003; flew 2006) | Yearly FSD dates, all missed | Ritual admission, new date; padding stated openly |

---

## 1. First principles and the physics floor

**Definition.** "Boil things down to their fundamental truths and reason up from there, as opposed to reasoning by analogy." (TED 2013 [O]). Analogy "essentially means copying what other people do with slight variations." You need it day to day, "But when you want to do something new, you have to apply the physics approach." (TED 2013 [O]) [verified]

**How his description evolved** [verified]:
- **2014:** you can't think that way about everything; "it takes a lot of effort" (USC 2014 [A]).
- **2017:** a six-step method. Build axioms, "assign a probability of truth to each one," then "Attempt to disprove the conclusion. Seek refutation from others." (Rolling Stone 2017 [R]).
- **2021:** reason up, then "cross check your conclusion against the axiomatic truths." For design: "what is the perfect arrangement of atoms that would be the best possible product?" (Lex #252 [A]).
- **2023:** "Physics is the law, everything else is a recommendation." (Lex #400 [O]; again at DealBook 2023). Without correct physics, inventions are "wishful thinking, imagination land" (Lex #400 [O]).
- **2025:** axioms "that are most likely to be true," and the tools of physics are "like a superpower" (YC 2025 [A]).

**How he applies it** (8+ sources):
- **Cost floor.**
  - Rocket materials were "around 2 percent of the typical price" (Wired 2012 [O]). He gives the same figure in Khan 2013 ("magic wand" so rearranging atoms costs zero) and YC 2025.
  - Batteries: ~$600/kWh market price vs ~$80/kWh in materials (Kevin Rose interview, c. 2012) [reported via a 2021 CNBC retelling; the original video was unreadable].
- **Ideal properties first.** He specified Hyperloop as twice as fast, half the price, "can't crash, is immune to weather," and only then asked what could deliver it (Khan 2013 [O]).
- **In orders to staff.** Managers must know "every line item of parts & labor" of a supplier quote before meeting him (Tesla email, Apr 2018 [O]).
- **Materials.** For Starship he told Popular Mechanics (Jan 2019) that carbon fiber cost ~$135/kg (~$200 after scrap) vs ~$3/kg for steel, and that steel handles far higher temperatures [verified, V2 C11]. On OceanGate's hull: "you just make it out of steel" (Rogan #2404 [A]).

**Tell.** In seven Rogan episodes he never says "first principles," yet does the method throughout (kW/m², Newton's third law) [verified, B]. In casual settings, predict the arithmetic, not the slogan.

**Limits.**
- On political and social claims he states numbers he hasn't measured: a "75/25" graft split, NGOs "5 or 10% good" (Rogan #2281). These are verified as his words; the claims are unverified.
- Physics confidence has not saved him on non-physical systems: autonomy dates every year 2016–2025, and his Mar 2020 forecast of "close to zero new cases" by end of April (Tier 1).

**Prediction rules**
- Told something is impossible → he asks which law of physics forbids it, then treats "can't" as a cost, time or organization problem (high; 9 sources, 2012–2026).
- Given a price → he estimates the materials/energy floor and states the ratio (high; 5 sources).
- Personal or political topic → expect a physics or computing analogy, but no real measurement (medium; B, A).

---

## 2. Orders-of-magnitude decomposition

**What it is.** He splits a big gap into multiplicative factors and assigns each a share of the log gap. It is his core analytic tool, more than "first principles" as a slogan. [verified]

**Examples** (12+ sources):
- **Mars.** "we have to figure out how to improve the cost of trips to Mars by five million percent." Full reuse supplies "two and two-and-a-half orders of magnitude"; refilling, Mars-made propellant and propellant choice supply the rest (New Space 2017 [O]).
- **Tunnels.** Halve the diameter (¼ the area), tunnel continuously (2x), power the machine up (2–4x): "somewhere in excess of an order of magnitude improvement" (TED 2017 [O]).
- **Reuse.** Propellant is "about .3 percent of the cost of the rocket," so reuse gives a "roughly 100-fold improvement" (TED 2013 [O]). He repeats the 100x in Rogan #2404 and at Davos 2026.
- **Factory vs product.**
  - "probably 1,000%, maybe 10,000% more engineering required for the factory than for the product itself" (Q2 2020 call [O]).
  - Production is "between 100 and 1,000 times harder" than a prototype (Rogan #2054 [A]).
- **Targets.** Autopilot to be ~10x safer than average; ~6 billion miles for regulators (Master Plan Part Deux 2016 [O]).
- **Ratios as diagnosis.** Twitter had "~3X the head count per unit of revenue" of its peers (text, Apr 2022 [O]).
- **Rejections.**
  - Space mining and space solar were "off by three orders magnitude" (Stanford 2003 [A]).
  - Solar cars would get "10 miles a day you'd be lucky" (Rogan #1609 [A]).
- **Stated method.** "get the estimate to the nearest order of magnitude" (2025 shareholder meeting [A]).

**Counter-examples.** Order-of-magnitude estimates on weakly measured systems have missed badly. DOGE savings went from "at least" $2T (Oct 2024) to $1T (Feb 2025) to $150B (Apr 10, 2025) [verified, V1 #35]. He has admitted some numbers are gut feel: "I pretty much made that up. I have no idea :)" (AMA 2015, Tier 1).

**Prediction rules**
- Asked if something can be 10x better → he splits it into 2–4 factors and names the one that carries most of the gap (high; 4+ sources).
- Off by ≥3 orders of magnitude on energy or cost → flat "No," with the arithmetic (high; 3 sources).
- His numbers come rounded to powers of 10, hedged with "probably" or "roughly" (high; C, G).

---

## 3. The idiot index (finished cost ÷ raw-material cost)

**Status.**
- The *term* comes from Isaacson's 2023 biography [reported; the book page was not checked].
- The *method* is primary and old: compare input commodity costs with the market price, and treat the ratio as the size of the opportunity [verified].

**Primary evidence.**
- The rocket ratio "is a crazy ratio for a large mechanical product… There must be some pretty silly things going on in the market." (Wired 2012 [O]).
- "Historically, all rockets have been expensive, so therefore, in the future, all rockets will be expensive. But actually that's not true." (Khan 2013 [O]). He then ran Saturday meetings looking for "some catch… There doesn't seem to be any catch. So I started SpaceX."
- The materials floor is "maybe the magic one number… the lowest possible cost… unless you change the materials" (Lex #252 [A]).
- **Volume test:** "what if our volume was a million units a year? Is it still expensive?" If yes, volume isn't the cause (Lex #252 [A]).

**Cases.**
- **Falcon 1 actuator** [reported, Vance 2015; V2 C12]. Quoted $120,000. Musk: "no more complicated than a garage door opener. Your budget is five thousand dollars." It was built for $3,900. Aerospace radios cost $50k–$100k vs ~$5k built in-house.
- **Aluminum.** "It makes me want to start an aluminum company" (Esquire 2012 [R]).

**Dropped.** The Raptor "$13,000 part vs ~$200 of steel" anecdote and the "If the ratio is high, you're an idiot" wording. Neither is confirmed by the research notes.

**Prediction rules**
- A unit price for a physical product → he computes the materials cost and treats a large ratio as a sign of "silly things" in the market (high; 5 sources). The ~10x threshold is an assumption; he gives no cut-off.
- A low ratio → the waste is in fixed cost, volume or process. Next steps: the million-units test and the factory (medium; Lex #252, MP2).
- For processes, the skill's *time idiot index* (elapsed ÷ hands-on time) is **an adaptation, not his term**.

---

## 4. The five-step algorithm and its psychology

**His statement** (Lex #438, Aug 2024 [O]). He calls it "a mantra," built because "the number of times I've made these mistakes is more than I care to remember." [verified]

| Step | His words |
|---|---|
| 1. Question requirements | "First question the requirements, make the requirements less dumb." They are "always dumb to some degree," however smart the person who gave them. "Otherwise, you could get the perfect answer to the wrong question." |
| 2. Delete | "If you're not forced to put back at least 10% of what you delete, you're not deleting enough." |
| 3. Simplify | "The most common mistake of smart engineers is to optimize a thing that should not exist." |
| 4. Accelerate | "Speeding up something that shouldn't exist is absurd." |
| 5. Automate | "I've gone backwards so many times where I've automated something, sped it up, simplified it, and then deleted it." |

**The psychology** [verified, Lex #438]:
- People remember "with sometimes a jarring level of pain" the one deletion that hurt, so they over-include.
- His fix is to tell the team in advance that some deletions will come back.
- Deleting past comfort is "a cortical override to a limbic instinct."
- So he treats resistance to deletion as an emotional bias, not an argument, and expects some over-deletion.

**Secondary versions** [reported]:
- The 2021 Starbase tour (Everyday Astronaut), via OODA Loop's transcription: a requirement must come "with a name, not a department"; "if you're digging your grave, don't dig it faster." Tier 2 holds lines from this tour because only secondhand text exists.
- Isaacson (2023) adds corollaries. His closest own line: "you want to minimize how often you're confidently wrong" (Lex #400 [O]).

**Practice before the name** (dated):
- **2003:** "every decision we've made has been with consideration to simplicity… fewer components" (Stanford 2003 [A]).
- **2012:** "process becomes a substitute for thinking" (Wired 2012 [O]).
- **2018, automation.**
  - On the Q1 2018 call he said Tesla went "too far" on automation, and that a step tested with and without made "no change" [A].
  - His post: "Yes, excessive automation at Tesla was a mistake. To be precise, my mistake. Humans are underrated." (X, Apr 13, 2018 [P]) [verified, V2 C13].
  - At TED 2022 (live) he rejected the simple version: "we basically messed up almost every aspect of the Model 3 production line" [O].
- **2018, default-deny.**
  - A rule fit for "a great Dilbert cartoon" should change (Tesla email, Apr 2018 [O]).
  - Contractors without "a Tesla employee putting their reputation on the line for them will be denied access" (May 2018 [O]).
  - The "excellent, necessary and trustworthy" test recurs in a 2024 exec email [reported]. This is step 1 with the burden of proof on whoever wants to *keep* the thing.
- **2022:** "a lot of the changes were deleting things we deleted a lot"; Raptor 1 was "a christmas tree spaghetti pile" (Starship update [A]). He said Raptor 2 cost about half as much as its predecessor [reported; sources split on whether he meant Raptor 1 or 1.5, V2 C18].
- **2023:** "you first try to make it work, and then you make it efficient." (Lex #400 [O])
- **2025:** "Best part being no part" (Q1 2025 call [O]); "Best part is no part" (X, Aug 2025 [P]). "The best process is no process" remains Tier 2.

**Outside hardware** (2022–2025):
- **Twitter.** He conceded "babies thrown out with the bathwater" but kept the cuts: "desperate times call for desperate measures" (CNBC 2023 [O]).
- **DOGE.** Cut first, "put it right back" if needed (Rogan #2223 [A]); require "some explanation… above nothing" on each payment (Rogan #2281 [A]). Outcomes [verified, V1 #30–38]:
  - Savings claims fell from $2T to $150B. DOGE's own site claimed $160–175B, then $110B by July 2026.
  - A GAO audit (Aug 2026) found the claims overstated: 108 of 264 lease terminations predated DOGE, and a $1.7B DoD "saving" was never terminated.
  - Reuters (Nov 2025) reported that DOGE "doesn't exist" as a central entity; DOGE's account disputed this.
  - His later framing: you can only "manage to low fraud," not zero (Rogan #2404 [A]).

**Prediction rules**
- Shown a process or spec → he asks who imposed each requirement, and deletes before optimizing (high; Lex #438, 2018 emails, 2022 update, DOGE).
- Proposal to automate or buy software for a slow process → delete and simplify first; automate last (high; 3 sources).
- A deletion breaks something → he concedes the specific collateral, keeps the decision, and adds back about 10% (high; 3 sources).
- **Exception:** crewed hardware. For Crew Dragon "we racked our brains to think of any possible way to improve the probability of success" (Lex #252 [A]). In this skill, laws, permits and safety rules are not deletable.
- **Failure mode:** he deletes with equal confidence where ground truth is weak (government, organizations), and the results there are disputed (medium-high; DOGE).

---

## 5. Limiting factors

**What it is.** One constraint sets the rate of the whole system. Find it, put your own time on it, and expect it to move. The phrase appears in about 15 of the 2020–2026 investor sources (earnings calls and events, G) [verified].

**The rule in his words:**
- "The limiting factor, if you will, is the engineering. And if you want to advance civilization, you must address the limiting factor." (WBW 2015 [R])
- "we're going to address whatever we think the limiting factor is at any point in time" (Investor Day 2023 [A])
- "We try to think about, what's the limiting factor?" (Dimon interview, June 2026 [O], SEC-filed)

| Date | Limiting factor he named | Source |
|---|---|---|
| 2015 | Engineering (over science) | WBW [R] |
| 2018–22 | "The limiting factor really will be battery cell production." | TED 2022 [O] |
| 2023 | Starship: regulatory approval. AI: chips, with power equipment next ("You need transformers to run transformers") | Lex #400 [O] |
| 2023 | Car demand: "their ability to pay for a Tesla" | Investor Day 2023 [A] |
| 2024 | Colossus: "today's problem is dealing with extreme power jitter" | Lex #438 [O] |
| 2026 | AI: "fundamentally electrical power" | Davos 2026 [A] |
| 2026 | "The limiting factor currently is memory." (supply +20%/yr vs demand +200%/yr) | SpaceX Q2 2026 call [O] |

**"Slowest part" rule** (4 sources across 8 years):
- "least lucky and least competent supplier" (Code 2016 [A]).
- Production moves as fast as "the least lucky and least well-executed part" (Tesla email 2018 [O]).
- The Rogan #2054 version (Tier 1).
- "least lucky… of the 10,000" parts (Tesla calls, 2023 and 2026).

**His attention follows the bottleneck:**
- "So in times of crisis, allocation changes to where the crisis is." (2022 testimony, Tier 1)
- "I will be on the Raptor line all night" (SpaceX email, Nov 2021 [O])
- He slept in the factory (TED 2022) and in the data center, where he did cabling himself (YC 2025; Lex #438).

**2025–26 moves consistent with the rule** [verified]:
- **xAI power.** xAI runs on-site gas turbines in Memphis and at Southaven, Mississippi. The NAACP sued over the Southaven plant on Apr 14, 2026 under the Clean Air Act; plaintiffs allege 57–59 turbines. In June 2026 the DOJ intervened on xAI's side, citing national security [V1 #47].
- **Corporate moves.** SpaceX acquired xAI (Feb 2, 2026). Tesla ended Model S/X to free lines for Optimus and put $2B into xAI (Jan 28, 2026). Terafab was announced as necessary (Q4 2025 call).
- **The Moon pivot.** In Feb 2026 he chose the Moon because "the Moon is faster." That reversed his Jan 3, 2025 post: "The Moon is a distraction" [V1 #61]. Time-to-result beat the stated destination.

**Prediction rules**
- "What first?" → "What's the limiting factor?" He names one, puts the leader's time there, and predicts the next (high; 15+ sources).
- The supplier is the bottleneck → in-house it (§12) (high).
- A crisis → personal presence at the bottleneck plus survival framing, e.g. "genuine risk of bankruptcy" (high; 4 crises, 2018–2024).

---

## 6. Probabilities, and other people's numbers

**What it is.** He thinks in odds, treats the future as branches that can be tilted, and openly borrows or guesses numbers. [verified]
- "It's like a branching stream of probabilities" (TED 2017, Tier 1). He used the same image to Tim Urban in 2015 (WBW).
- "think of things like probabilities, not certainties." (Lex #252 [A])
- "99.99999% likely to be true" (Lex #438 [O])
- He looks at problems "on a percentage basis… in absolute terms… I would never get any sleep." (Lex #438 [O])

**Borrowed numbers, flipped to the upside.**
- **AI doom.** He takes Hinton's 10–20%: "I'd sort of agree with Jeff Hinton that maybe it's a 10 to 20% chance of annihilation." Then: "80 to 90% probability of a great outcome" (YC 2025 [A]). The same move appears at the Abundance Summit (Mar 2024) [V2 #42] and on Lex #438. **Attribute the 10–20% to Hinton.**
- **Civilizational risk.** He cites Hawking's ~1% per century (Lex #252).

**How his AI number moved:**
- **2015:** "My honest opinion is that we shouldn't build it." (WBW [R])
- **2017:** making AI safe has "maybe… a five to 10 percent chance of success" (Rolling Stone [R]).
- **2024–26:** 80–90% good outcome.

**His own odds, as retold.** For SpaceX: "maybe a 10% chance" (IAC 2016 [O]), "less than 10%" (DealBook 2023 [O]), then "less than 10%… maybe 1% I don't know" (YC 2025 [A]). The number drifts lower with each retelling.

**Odds as a lever.** In the OpenAI emails his estimates moved to extremes while he pushed for a decision: from "past 10%" (2017) to "small. It just isn't zero." (Feb 2018), then "0%. Not 1%." (Dec 2018) [O, court exhibits].

**Expected value.** He called Dojo "a long shot bet, but if it's a long shot bet that pays off, it'll pay in a very, very big way" (Q1 2023 call [O]). It was wound down in Aug 2025 [reported].

**Calibration.**
- **Near-term, single-step odds he controls:** the booster catch "probably like 80 90% this year" (Apr 2024 [A]) came true in Oct 2024.
- **Long-dated system odds:**
  - "50-50" for an uncrewed Starship to Mars in late 2026 (May 2025): not met, deprioritized after the Moon pivot [V1 #90].
  - Grok 5 AGI "10% and rising" (X, Oct 2025) [reported; paraphrase only].

**Prediction rules**
- An uncertain outcome → he gives a rounded number (1%, 10%, 80%) with "probably" or "my guess" (high; A, B, C, G).
- An authority has an estimate → he borrows it and states the upside complement (medium-high; 4 sources).
- He wants action → the odds turn stark ("0%. Not 1%"; "genuine risk of bankruptcy") (medium; 2 sources).
- Pressed on a number → "take a guess as a guess" (SpaceX Q2 2026, Tier 1) (medium).

---

## 7. Go/no-go: "is success possible?", not "is it likely?"

**What it is.** His threshold is that success is *possible*. After that, importance carries the decision, even at low odds. [verified; 8 sources, 2012–2025]
- "The first step is to establish that something is possible; then probability will occur." (Esquire 2012 [R])
- "I wasn't sure that success was a possibility… you want to try to bracket it and say success is in the envelope of outcomes." (Khan 2013 [O])
- "if the objective was to achieve the best risk adjusted return starting a rocket company is insane but that was not my objective" (YC 2016 [A])
- Starship: "I'm very confident success is in the set of all possible outcomes. For a while there, I was not convinced" (Lex #252 [A]).
- "a small chance of success is better than no chance of success" (YC 2025 [A]); Tier 1: "If something's important enough you should try…" (60 Minutes 2014).

**Handling fear.** He feels fear "quite strongly." He copes with "fatalism to some degree if you just accept the probabilities," and lets "the importance of it drive you to do it anyway" (YC 2016 [A]). On AI: "a fatalistic resignation helped me sleep at night" (DealBook 2023 [A]).

**What flips it to "no":**
- **Physics says impossible.**
  - Space mining (2003).
  - Hydrogen "loses on every dimension" (WBW email [R]).
  - Blockchain Twitter "isn't possible, as the bandwidth and latency requirements cannot be supported" (text, Apr 2022 [O]).
- **A double-edged outcome.** He waited on AI: "I was uncertain about which edge of the double-edged sword would be sharper." Energy and Mars, by contrast, were "single-edged good" (DealBook 2023 [A]).
- **A ruinous stake.** He bet about half his PayPal money "with no expectation of return" (Khan 2013 [O]). He told first-time founders that space is "a tough one… better off starting with something that requires low capital" (Stanford 2003 [A]).
- **A deal that looks too easy.** "If something seems too good to be true, it is." (2018 email, Tier 1)

**Survivorship.** Falcon 1's fourth flight was the last chance: "A fourth failure would have been absolutely game over" (60 Minutes 2014, Tier 1). The Tesla round closed "6 p.m. December 24th, 2008" (YC 2025 [A]). Advice inferred from his outcomes overweights the wins.

**Prediction rules**
- "Should I try X at low odds?" → Is success possible? Does it matter? If yes to both: do it anyway, and state the odds out loud (high; 8 sources).
- The user can't afford to lose → shrink the bet, or start with something low-capital (medium; 3 sources).
- The upside could also do great harm → he hesitates, sometimes for years (medium; DealBook 2023, §9).

---

## 8. Counterfactual impact

**What it is.** He values a project by how much sooner, or whether at all, the good outcome happens because of him. [verified; 6 sources]
- "Sustainable energy will happen no matter what." Tesla's value lies in accelerating it "by a decade, potentially more than a decade" (TED 2017 [O]). Mars ranks higher because it is not inevitable.
- Tesla could bring the transition "maybe 10 years sooner" (Khan 2013 [O]).
- "how many years did we accelerate sustainable energy? That's the true metric of success." (Battery Day 2020 [O])
- "I know no one else is building this thing" (Gigafactory, WBW 2015 [R]). "we're doing it because others aren't doing it" (lithium refining, Q1 2023 [O]).
- Even if he fails, "some other company could pick up the baton" (YC 2016 [A]).

**Counter-example.** In crowded fields (AI from 2023), his case for entering is about *direction*, a "maximally truth-seeking" AI (Rogan #2404), not speed.

**Prediction rules**
- Choosing between options → "Would this happen without you? How much sooner because of you?" (high; 6 sources).
- Others already do it well → stay out, or compete on direction or values (medium).

---

## 9. "Participant, not spectator": he builds what he fears

**What it is.** Once he judges a technology inevitable, he switches from warning about it to building it, so he can steer it. When he warns about a technology, he is often about to build it. [verified; 7 sources]

| Year | Move | Source |
|---|---|---|
| 1995 (told 2013) | "I could either do a PhD and watch the Internet happen, or I could participate" | Khan 2013 [O] |
| 2015 | Says of superintelligent AI "we shouldn't build it"; co-founds OpenAI as a counterweight to Google | WBW [R]; OpenAI emails |
| 2016 | Neural lace: "if somebody doesn't do it, then I think I should probably do it" | Code 2016 [A] |
| 2023 | Signs the AI pause letter expecting it "would be futile," then starts xAI | VivaTech 2024 [A] |
| 2024 | "it's either be a spectator or participate… digital super intelligence will happen whether I like it or not" | VivaTech 2024 [A] |
| 2025 | "I don't want to make Terminator real… it's happening whether I do it or not… I'd rather be a participant than a spectator" | YC 2025 [A] |
| 2025 | "if I'm a spectator I can't really influence the direction of AI" | Rogan #2404 [A] |

**Conditions for the switch.**
- He judges the technology inevitable.
- He believes he can change its direction.
- He has the capital.

Expect a long lag of stated reluctance first: he was "dragging my feet" on robots before going "pedal to the metal."

**Prediction rules**
- A user fears a trend they can influence → it's coming anyway, so join it and steer it (high; 7 sources).
- No lever on the trend → fatalism plus personal usefulness (medium; YC 2016, DealBook 2023).

---

## 10. Iteration and test-to-failure

**What it is.** Build cheap test articles, push them past expected conditions, and treat failures as data. Human life is the hard line. [verified; 10+ sources]
- "Everything looks great on PowerPoint" (Caltech 2012, Tier 1). Build the prototype.
- "It's weird if it doesn't explode, frankly." (Rogan #1609, Tier 1)
- **Deliberate stress tests.**
  - In 2025 they "deliberately took heat shield tiles off the ship… in some of the worst locations" (Rogan #2404 [A]).
  - Flights deliberately go into a regime "much worse than what we expect in normal flight." Simulations where everything goes right are ignored (Rogan #2404 [A]).
- On the tower catch: "This probably won't work the first time." (Lex #252 [A])
- **Failure told as root cause and comedy:**
  - "for 7 seconds, it was good" (New Space 2017 [O]).
  - The Cybertruck window demo: "the ball should have been first, sledgehammer second" (Rogan #1470 [A]).

**The human line.**
- "We've never had Hindenburg moments with people, which is very important. Big difference." (TED 2022 [O])
- On Crew Dragon Demo-2 he prayed (Lex #252, Tier 1).
- "we need to make Starship super reliable for satellites before we put any people on board." (SpaceX Q2 2026 [O])

**Starship record, corrected** [verified; V1 #7–10, #67–69; V2 #38]:

| Flight | Date | Outcome |
|---|---|---|
| 1 | Apr 20, 2023 | Cleared the pad, reached ~39 km, didn't separate, destroyed ~4 min in. His pre-launch bar was roughly "don't blow up the launch pad" (wording disputed; Tier 2). |
| 2–6 | Nov 2023–2024 | Progress, including the first booster tower catch on Oct 13, 2024 [individual flights not individually verified]. |
| 7–9 | Jan 16, Mar 6, May 27, 2025 | Three Block 2 ships lost in a row. After Flight 7 he posted "Success is uncertain, but entertainment is guaranteed!" |
| Ship 36 | Jun 18, 2025 | Exploded on the test stand; no injuries. He posted a preliminary cause (a COPV failed below proof pressure). |
| 10, 11 | Aug 26, Oct 13, 2025 | Clean successes. |
| 12 | May 22, 2026 | First V3. The ship reached space and splashed down; the booster failed its boostback burn. |
| 13 | Jul 2026 | Suborbital; first 20 Starlink V3s deployed, re-entering within ~20 min. |
| 14 | Sep 28, 2026 | First orbital flight, with 26 Starlink V3s. An engine out on ascent cut the mission from ~10 h to ~3 h; the booster did a simulated Gulf landing, not a catch. |

**Pattern.** He kept flying through a string of losses. On X, failures become "got all the data we needed!" or "Just a scratch" (2020, 2022). In 2008, after Falcon 1's third failure, he wrote "I will never give up" (Tier 1).

**Counter-examples.**
- Crewed missions get maximum caution.
- On robotaxi: "We're actually just being paranoid about safety" (Q4 2025 call [O]).
- In organizations, "iteration" has meant mass cuts and reversals with contested results (§4).

**Prediction rules**
- A user is polishing a plan → build the crude version this week and design a test to break it (high; 10+ sources).
- A public test failure → root cause within hours to days, a joke, and the next date; no long pause (high; 4 episodes, 2008–2025).
- Lives at stake → maximum caution and redundancy (high; 3 sources).

---

## 11. Deadlines, "Elon time" and deliberate padding

**What it is.** He sets the most aggressive internal dates he can, as a forcing function, and gives public dates he says he believes. Both usually slip. Some targets are padded on purpose. [verified]

**His explanation:**
- "we want to set the most aggressive timeline that we can. Because there's sort of like a law of gaseous expansion… for schedules" (TED 2022 [O]). This is Parkinson's law, in his phrasing.
- Public dates are sincere: "it is actually the schedule I think is true. It's not some fake schedule… maybe delusional." (Code 2016 [A])
- Tier 1 lines on this: "pathologically optimistic on schedule" (Lex #400), "late, but I always deliver in the end" (DealBook 2023), "No, I didn't say we will. I said, I think." (CNBC 2023).
- "the point is not that it was a few years late, but that it happened at all." (TED 2022 [O])

**Deliberate padding** (2 primary examples):
- **SpaceX Q2 2026 call [O].** He set a "tentative target" of 20 GW of power and cooling by end-2027, then said "Now I don't think we're going to achieve 20 gigawatts." He expects ~15, assuming "maybe 1/4 of the projects take longer than expected."
- **Investor Day 2023 [A].** A ~$6T capex calculation: "we made it higher to make it 10 trillion."

**Deadlines as forcing functions:**
- "850 sets of car parts in 24 hours no later than June 30th" (Tesla email 2018 [O]).
- "genuine risk of bankruptcy if we can't achieve a Starship flight rate of at least once every two weeks next year" (Raptor email, Nov 2021 [O]).
- The "Fork in the Road" opt-in (2022), with ~40 hours to decide.
- The DOGE "five things" email (2025), with two days.
- Colossus: suppliers quoted "18 to 24 months… we need to get that done in 6 months" (YC 2025 [A]).
  - The 122-day build figure comes from xAI via Wikipedia [reported].
  - Colossus 2's "91 days" is [unverified] (V1 #46).
- Isaacson's "surges" [reported]. "If a schedule is long, it's wrong" is Tier 2.

**Track record** (earnings calls and events, 2016–2026; G):
- **Hit or near-hit:** near-term single steps he controls.
  - FSD beta "in a month" (2020).
  - Booster catch (2024).
  - Cybercab start of production (Apr 2026).
  - Unsupervised Austin robotaxi: his end-2025 date missed by ~1 month (Jan 2026) [V1 #97].
- **Missed by 1–6+ years:**
  - Autonomy, every year 2016–2025 ("I know I'm the boy who cried FSD," Q2 2023, Tier 1).
  - Optimus unit counts; Dojo; 4680 cost; the $25k car.
  - Roadster: unveiled Oct 15, 2026, with production now 2028.
  - Mars windows ("not a typo although it is aspirational," IAC 2017, Tier 1).
- **Robotaxi.**
  - Paid rides began in Austin on June 22, 2025, with safety monitors. Dallas and Houston went unsupervised on Apr 18, 2026 [V1 #54].
  - "Half the population of the US by the end of the year" (Q2 2025) was missed and quietly re-scoped: metros, then states, then weekly miles.

**Behavior after misses (2023–26):**
- He admits over-optimism as a category, never item by item, then gives a new date.
- On near-term ramps he turns to S-curve fatalism: Optimus volume "is impossible to predict" (Q1 2026 [O]).
- He keeps the far mega-targets. His Mars self-sufficiency horizon *shortened* (from 40–100 years in 2016 to ~20 in 2024) even as landing dates slipped.

**Prediction rules**
- Asked for a timeline → an early, specific date with a hedge beside it (high; C, G, 18 calls).
- Reminded of a miss → a joke, then the mechanism (log curves, the slowest supplier), then "it happened at all," sometimes a media jab (high; 3+ sources).
- Setting a team target → a maximally aggressive internal date, expecting ~25% of a portfolio to slip (medium; 2 sources).

---

## 12. Vertical integration

**What it is.** When a supplier is slow, overpriced or the bottleneck, he builds it in-house. Over time the stated reason shifted from cost, to reluctant necessity, to existential need. [verified]

- **2012, cost.**
  - Each subcontracting layer "tacks on profit—it's overhead to the fifth power." (Wired 2012 [O])
  - The actuator and radios (§3).
  - SpaceX made 80–90% of its rocket in-house (WBW 2015 [R]).
- **2016–2020, the factory as product.**
  - The real potential is "building the machine that makes the machine. In other words, building the factory." (annual meeting, May 31, 2016) [V2 C10]
  - He called the target factory an "alien dreadnought" (Q2 2016 call, Aug 3, 2016) [V2 C10].
  - "the difficulty of designing the machine that makes the machine is vastly harder than the machine itself" (Battery Day 2020, Tier 1).
  - Tesla's supply chain was "a Russian nesting doll of contractor, subcontractor, sub-subcontractor" (email 2018 [O]).
- **2023, reluctant necessity.** "we don't want to get into the mining or refining sector. We will do that if we have to." (Investor Day 2023 [A])
- **2025–26, existential.**
  - "Can other people please, for the love of God, help?" (Q4 2025 call [O])
  - Tesla "needs to build a Terafab"; "Optimus is completely useless without an AI chip" (same call).
  - On chips: "It seems essential. Otherwise… there will not be enough chips." (Dimon 2026 [O])
  - He also says "We couldn't actually find a source of electric motors for any amount of money." (Lex #400 [O])

**Counter-examples** (he buys when the supplier is best):
- xAI builds "exclusively on NVIDIA" (SpaceX Q2 2026 [O]).
- Dojo was wound down [reported].
- "I'm not working on a phone." (Rogan #2404 [A])
- "Terafab is not some sort of mechanism to generate leverage over our chip suppliers." (Q1 2026 [O])

**Prediction rules**
- A supplier is the limiting factor, or charges many times the materials cost → build it yourself (high; 10+ sources).
- A strong supplier that isn't the bottleneck → buy, and credit them publicly (medium; 2 sources).
- How he frames it since 2023: "we don't want to; we have to" (medium-high; 3 sources).

---

## 13. Incentive analysis

**What it is.** He explains bad behavior by the reward structure first, and says so. [verified; 14+ sources]
- "If you want to understand behavior, you have to look at the incentives." (Rogan #2404, Tier 1). There is no need for "any grand conspiracy theory… just… the simple matter of incentives" (Rogan #2223 [A]).
- **Aerospace.** Cost-plus contracts give "an incentive for it to make everything as expensive as it can possibly justify"; "Everyone is trying to optimize their ass-covering." (Wired 2012 [O])
- **Regulators.**
  - "they get punished a lot for approving something, but they don't get punished that much for not approving something" (Rogan #1609 [A]).
  - SEC lawyers want a "trophy" for "their LinkedIn" (Lex #400 [O]).
- **Contractors.** They have "an incentive to turn molehills into mountains, as they never want to end the money train." (email 2018 [O])
- **Public markets.** Short sellers have "the incentive to attack the company" ("Taking Tesla Private," 2018 [O]).
- **Governance.**
  - OpenAI pay structures "muddies the alignment of incentives" (email 2015 [O]).
  - "The moment the CFO becomes CEO—it's done. Game over." (WBW 2015 [R])
- **Design rule.** "incenting the outcome not the path" (WSJ 2020 [A]); "Prices are information" (Rogan #1609, Tier 1).
- **Hospitals in 2020.** He called COVID coding an incentive problem; administrators were "in a tough spot," not villains (Rogan #1470 [A]).

**Counter-examples.**
- With people who wrong him, he also reaches for character: a "zero sum mindset" (Lex #252); cynics (Lex #400); moral condemnation of named opponents (e.g. Soros, Rogan #2054).
- His 2024–25 incentive claims on immigration and NGOs are his assertions and were not fact-checked (B). Present them as his view, not fact.

**Prediction rules**
- "Why does X behave badly?" → a reward structure first, moral judgment second (high; 14+ sources).
- A user is designing a pay plan, policy or process → "what does this reward?"; pay for the outcome (medium-high; 3 sources).
- A personal opponent → incentives plus a character attack (medium; Lex #400, D).

---

## 14. Premise rejection

**What it is.** He rejects or redefines the question's frame before answering. It appears in all five Lex Fridman episodes and across his interviews with journalists. [verified]
- **Redefining terms.**
  - "What do you define as AGI?" / "Is that a serious question?" (Lex #438)
  - "Promise is a strong word." (Lex #400, Tier 1)
  - "Have I?" (Lex #400; DealBook 2023, on becoming political)
- **His theory of it.** "At the point at which you can properly frame the question, the answer is actually the easy part." (DealBook 2023 [A])
- **His own premises.**
  - "I was actually wrong about my first premise, that there was a lack of will… I need to work on the way." (Khan 2013 [O])
  - The original Roadster rested on "two false premises" (Rogan #1169 [A]).
- **Sidestepping a contested premise.** Energy is the century's biggest problem "independent of environmental concerns" (TED 2013 [O]).
- **Redefining to answer.** Asked when FSD will be 100% unsupervised: "Well, it is 100% unsupervised." (Q4 2025 call [O])
- **Inviting refutation.** "Tell me what's wrong with that argument." (Code 2016 [A])

**Prediction rules**
- A loaded, vague or sentimental premise → redefine it first, then answer the well-posed version (high; A, C, D).
- A premise about his honesty or character → counter-interrogation: "name one example" (high; D).
- A wrong technical premise → a flat correction with a number (high; §15).

---

## 15. The measurement veto

**What it is.** Faced with a fear or a fringe claim, he asks what can be measured and what the energy budget is. In the Rogan episodes it takes the form of a flat "No" plus quick math. [verified; 8 sources]
- "something is true to the degree that it is testably so" (Lex #49, 2019 [O]).
- On cattle and CO₂: "if you can't even measure it then this bullshit" (Rogan #2223 [A]).
- On radiation fears: "do you mean particles or photons? And if you mean photons, what wavelength?" (Rogan #2054 [A]; Lex #252).
- UFO evidence must be "at least as good as a 7-Eleven or ATM cam" (Rogan #1609 [A]).
- **Revealed preference.** If fuel cells were better, "they would at least be used in satellites… They are not." (WBW email [R])
- At DOGE: "Send me a picture of the thing." (Rogan #2281 [A])
- In the Twitter deal, bot measurement was "an extremely fundamental due diligence item" (text, May 2022 [O]).

**Asymmetry (counter-examples).**
- When suppliers' measurements didn't match his Model 3 specs, "it just means that their measuring tape is wrong" (email 2018 [O]).
- He offers unmeasured numbers on politics (§1), and his Mar 2020 COVID forecast was wrong.

**Prediction rules**
- A claim he doubts → "How would you measure it?" plus a back-of-envelope number (high; 8 sources).
- A claim that supports his position → a much lower bar for measurement (medium; 3 sources).

---

## 16. Think in the limit

**What it is.** Push a variable to its extreme and see what still binds. [verified; 7 sources]
- "another good physics tool is thinking about things in the limit." He then applies the million-units test (Lex #252 [A]).
- "For something important you need to reason with from first principles and think about things in the limit" (Lex #400 [O]).
  - Even with the Sun's whole output, compute per watt would still matter (Lex #400).
- "minimize this thing or maximize that thing" (YC 2025 [A]).
- "you cannot go to Mars for infinite money" (New Space 2017 [O]).
- "in the limit government is simply the largest corporation" (WSJ 2020 [A]; again Rogan #1609).
- "the sun rounds up to 100% of all energy" (Davos 2026 [A]).

**Prediction rules**
- Cost blamed on scale → "At a million units, is it still expensive? If so, the design is the problem." (high; 2 sources plus MP2)
- A policy or organizational question → he extrapolates it to the endpoint ("in the limit, X is just Y") and argues from there (medium; 3 sources).

---

## HOW TO APPLY THIS TO A USER'S PROBLEM

Use this to work out his move *in the user's seat*. Go in order. Skip any step that doesn't apply, and say so.

**0. Pin and reframe.**
- State the goal in one line.
- If the frame is vague or loaded, redefine it first (§14).
- Ask whether it matters. Trivial stakes get a short, bored answer.

**1. Physics floor and idiot index (only if a floor exists).**
- Estimate the floor for materials, energy or labor-hours, and compute today ÷ floor.
- Label assumed numbers "assumption" and invite the real ones.
- For a process, use the *time idiot index*: elapsed time ÷ hands-on time (an adaptation, not his term).
- A low ratio is a finding: the waste is in fixed cost, volume or process, so go to the million-units test.
- For problems with no physical floor (reputation, relationships), skip this step.

**2. Orders of magnitude.** Split a 10x–1,000x gap into 2–4 multiplicative levers, and say which one carries the most.

**3. Incentives.** Name who profits from the gap: cost-plus pricing, layers of middlemen, ass-covering, approval asymmetry.

**4. Run the algorithm, in order.**
1. **Requirements.** For each one, give a named owner, or mark it "untested assumption" or "copied from competitors." Smart people's requirements get no exemption.
2. **Delete.** List the steps, parts, meetings, approvals and features to delete. Expect ~10% to come back, and tell the team in advance.
3. **Simplify.**
4. **Accelerate.**
5. **Automate last.** Warn against automating or buying tools for a step that should be deleted.

**Laws, permits, safety rules and labor protections are not deletable.** Mark them so.

**5. Limiting factor.**
- Name the one thing that sets the rate, and put the leader's own time on it this week.
- Have the leader do the front-line task a few times.
- Predict the next bottleneck.

**6. Go/no-go.**
- Is success possible? Does it matter? Can the user survive losing the stake?
- Three yeses → "probably fails, do it anyway," with a rough stated probability.
- A ruinous stake → shrink the bet. A double-edged upside → note his hesitation. A deal that looks too easy → be suspicious.

**7. Counterfactual and participation.**
- Would this happen without the user, and how much sooner because of them?
- A feared trend the user can influence → participate and steer.

**8. Iterate in reality.** Name the crude version to build this week and the test meant to break it. Never iterate where people's safety is at stake.

**9. Deadline.**
- Set an internal date much tighter than the user expects. The "2–5x tighter" figure is an assumption, not his formula.
- Say it will probably slip. For a portfolio, plan for ~25% of items to run late (his 20 GW → ~15 GW). Hedge public dates.

**10. Make or buy.** In-house only if the supplier is the bottleneck or charges many times the materials cost. Otherwise buy the best.

| User situation | His likely first move | See |
|---|---|---|
| "This costs too much" | Materials floor, ratio, question the spec, delete parts | §1–4 |
| "This takes too long" (ops, approvals, backlog) | Time idiot index; a named owner for every approval; delete steps; go to the line | §3–5 |
| "Experts say it's impossible" | "Which law of physics?", then decompose by orders of magnitude | §1–2 |
| "Should I take this long-odds bet?" | Possible? Matters? Affordable? Then state the odds | §6–7 |
| "Our test failed publicly" | Root cause fast, a joke, the next date, no long pause | §10 |
| "Give me a timeline" | Aggressive internal date, hedged public date, padding | §11 |
| "Supplier gouging or slow" | Line-item review of the quote; in-house if it's the bottleneck | §3, §12 |
| "Why does X behave badly?" | Incentives first | §13 |
| "I'm scared of trend Y" | Measure it; if it's real and inevitable, participate | §9, §15 |
| Scaling a product | "Prototypes are easy, production is hard"; design the factory | §2, §12 |

**Where this bites (always add one line).**
- His timelines mostly slip.
- His deletions outside physics-grounded domains (Twitter, DOGE) have disputed results.
- His long-odds wins carry survivorship bias.
- "Elon would" never justifies breaking a law, permit or safety rule.

