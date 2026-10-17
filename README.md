# What Would Elon Do

A [Claude skill](https://docs.claude.com/en/docs/claude-code/skills) that answers one question: **given your situation, what would Elon Musk actually do?**

Describe a decision you're facing: a bloated process, a failing launch, a hiring problem, a career move, a public pile-on. The skill tells you:
- how Musk would think about it;
- what he would do;
- how he would say it;
- where copying him would hurt you.

It is built from his documented record, read at the source, not from memes or secondhand summaries:
- podcasts and talks, read as full transcripts;
- his own writing;
- court-released emails and texts;
- 18 earnings calls;
- about 7,600 of his archived X posts.

Everything is fact-checked through mid-October 2026.

## Example prompts

```
What would Elon do? Our client onboarding takes 3 weeks and has 14 steps.
WWED: I'm 20, I have 40 beta users. Should I drop out?
Run the algorithm on our 7-round hiring process.
Roast my plan like Elon: [paste your plan]
Tweet it: we just shipped v2 and it's 3x faster.
Talk like him: should we take the bigger valuation from the VC we don't trust?
What would 2015 Elon say about AI vs. Elon now?
```

## What you get

By default, each answer has six parts:

| Section | What it is |
|---|---|
| **The Elon move** | The blunt verdict, in one or two sentences |
| **How he'd think about it** | His frameworks applied to your numbers: physics floor, idiot index, which requirement to delete, the limiting factor, the incentives |
| **What he'd actually do** | Concrete steps with an aggressive deadline |
| **What he'd say** | A post, spoken answer or email in his measured style, clearly labeled as not a real quote |
| **Real precedent** | Matching episodes from his career, with dates |
| **Where this bites** | The honest downside of copying him here |

Other modes: `quick`, `tweet it`, `run the algorithm`, `roast my plan`, `talk like him`, `deep dive`. The skill is era-aware: ask about "2015 Elon" and you get the 2015 version.

See [examples/sample-answers.md](examples/sample-answers.md) for real outputs.

## Install

**Claude Code** (personal skill):

```bash
git clone https://github.com/aaronv02/what-would-elon-do ~/.claude/skills/what-would-elon-do
```

To use it in a single project, clone it into that project's `.claude/skills/` folder instead.

**Claude.ai / Claude Desktop:** zip the folder and upload it under Settings → Capabilities → Skills.

The skill triggers on "what would Elon do" style questions, or you can ask for it by name.

## How it's built

`SKILL.md` holds the core of the skill:
- a 22-rule behavioral model;
- a reaction predictor;
- the output format and modes;
- a voice cheat-sheet built from measured data;
- the guardrails.

The depth lives in reference files. The skill reads them only when a question needs them:

| File | Covers |
|---|---|
| `references/decision-frameworks.md` | First principles as orders-of-magnitude math, the idiot index, the five-step "algorithm" in his own words, limiting factors, how he uses odds, "possible, not likely", building what he fears, deadlines and deliberate padding |
| `references/management.md` | How he writes orders, short yes / long no, default-deny with a named owner, hiring, "hardcore" ultimatums, cuts and rehiring, DOGE as a management case study, plus eight common team situations |
| `references/business-strategy.md` | 14 case studies, from the 2006 Master Plan to the 2026 SpaceX IPO; how he negotiates with investors, reframes companies, prices and quietly re-scopes missed targets; a 21-move playbook |
| `references/crises-and-reactions.md` | 26 dated crises, his interview-defense moves, courtroom behavior, X fight mechanics, and a reaction playbook by trigger |
| `references/advice.md` | The advice he gives individuals (modest and practical: "be useful"), plus 53 everyday questions with Musk-consistent answers |
| `references/worldview.md` | Mission, AI, Mars to Moon, jobs, energy, free speech, a year-by-year political arc, his value hierarchy, contradictions |
| `references/personality.md` | Biography, traits, how he handles personal questions, daily habits, humor, contradictions, blind spots |
| `references/timeline-and-track-record.md` | How his views changed from 2001 to 2026, about 100 dated predictions with outcomes, and what he got right vs. what he missed |
| `references/voice-and-style.md` | Measured voice: reply frequencies, post length by era, emoji and typography by era, spoken tics, email and text registers |
| `references/verified-quotes.md` | About 170 quotes checked against primary sources. These are the only lines the skill may use verbatim. A second tier lists well-known lines it may only paraphrase. |

### Research method

1. **Eight primary-source passes.** Each one read a slice of his public record in full: every Lex Fridman and Joe Rogan episode, TED and commencement talks, journalist interviews, his own writing, OpenAI and Twitter court exhibits, earnings calls and product events, and his X archive.
2. **Two fact-check passes.** These covered about 175 claims, checked against Reuters, AP, Bloomberg, court records and filings. No claim turned out to be invented; dozens of dates, numbers and attributions were corrected.
3. **An independent review** for accuracy, balance, and how real people (including his family) are treated.

The [`research/`](research/) folder holds the evidence:
- [`sources.md`](research/sources.md): about 160 sources, with what share of each was read;
- both [fact-check](research/factcheck-2025-2026.md) [ledgers](research/factcheck-pre-2025.md);
- the [X posting analysis](research/x-posting-analysis.md);
- a [changelog](research/changelog.md).

The working notes behind each pass aren't published, because they contain hundreds of transcript excerpts.

Every claim carries a label: **[verified]**, **[reported]**, **[contested]** (both sides given) or **[unverified]**.

## Design principles

- **Specific beats generic.** It runs his methods on your numbers instead of reciting "think from first principles".
- **Accurate beats flattering.** His misses sit next to his wins:
  - Most dated multi-step targets slipped by years.
  - DOGE's savings claims were disputed.
  - Cybertruck demand fell short of the hype.
  - Tesla's brand took damage in 2025.
- **Measured, not memed.** His real top replies on X are "Yes", 🤣, "Exactly" and "True". "Concerning" shows up in about 0.1% of his posts.
- **Neutral on politics.** It describes what he would likely say without endorsing it.
- **No impersonation.** It won't write content designed to pass as a real Musk post or statement.
- **Private people stay private.** It doesn't discuss his children's private matters and never uses anyone's former name.

## Disclaimer

This is an independent, unofficial project for education and commentary. It is not affiliated with, endorsed by or connected to Elon Musk, Tesla, SpaceX, X, xAI or any of his companies. Names are used only to identify the subject.

Its outputs are predictions based on public sources and may be wrong. They are not statements by Musk, and they are not financial, legal or medical advice. Short quotations are included for commentary, with sources cited.

## License

[MIT](LICENSE)
