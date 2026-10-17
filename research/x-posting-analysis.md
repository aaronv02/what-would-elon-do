# H — Musk's X/Twitter output at scale (2010 – Oct 2026)

This is a quantitative and qualitative analysis of Elon Musk's posting on X/Twitter from 2010 to October 2026, built from a sample of archived posts plus published analyses, for the what-would-elon-do skill. Compiled 2026-10-16. Sections are numbered §0–§9 and cited elsewhere as "H §N". Evidence labels: **[MEASURED n=…]** is a figure counted from the post sample described in §0; **[REPORTED: source]** is a figure published elsewhere and not re-derived; **[T-primary]** is verbatim post text read on an archive page (PolitiTweet, or a Wayback copy of a Nitter/xcancel page), with **P** and **N** marking which; **[Report]** is post text quoted secondhand by a news report. In §5, **(verified)** marks a first-use date read on the archive page itself; in §8, **CONFIRMED**, **UPGRADE**, **Not found** and **Not found verbatim** give each quote-bank line's status.

## 0. Method: sources and sampling

1. **PolitiTweet archive of @elonmusk** (polititweet.org, account 44196397). It holds 824 pages of 30 posts each, about 24,700 posts. Coverage runs from Dec 2011 to 3 Apr 2023, when Twitter cut off its API, and includes retweets and some deleted posts.
   - Every 4th page was sampled (pages 2, 6, 10 … 822, plus 824): 207 pages, giving **6,188 posts, about 25% of the archive, spread evenly through time**.
   - About 40 more pages were read to find specific known posts and verify quotes.
   - PolitiTweet stores text in the old format. Posts longer than about 117 characters are cut off with "…" and a t.co link; these were counted as "long."
2. **Wayback Machine copies of Nitter and xcancel mirrors of @elonmusk** (nitter.net, nitter.privacydev.net, nitter.it, nitter.1d4.us, xcancel.com, lightbrd.com, nitter.kuuro.net, nitter.privacyredirect.com). There are 79 timeline snapshots from Jan 2023 to Sep 2026, each a burst of about 20 consecutive posts, plus 30 archived single-post pages from 2026.
   - After removing duplicates: **2023 = 797 posts (PolitiTweet + mirrors), 2024 = 185, 2025 = 861, 2026 = 189**.
   - **Each page shows the account's lifetime post counter.** Reading it across 45 dates gives a measured posting rate for 2023–2026 (§2.1).
   - Caveat: most mirror snapshots are of the "Tweets" tab, which leaves out his replies. Only 14 snapshots are of the "Tweets & Replies" tab, so 2024–26 reply shares come from a small subset (§2.3).
3. **Parsing.** All posts were parsed with custom scripts that counted words, emoji, lengths, reply targets and post types.
   - Post type: a reply starts with @handles (PolitiTweet) or carries a "Replying to" header (Nitter). A retweet starts with "RT @" or carries a retweet header. A quote has an embedded quote box (Nitter only; PolitiTweet quotes show up as "orig" plus a link).
   - Length is measured after removing URLs and the leading @handles.
4. **Published quantitative analyses**, read where reachable (ledger below). Several were paywalled or blocked; for those, secondary summaries were used and labeled as such.
5. **Not reachable in Oct 2026:**
   - xcancel.com now returns "service is suspended … ongoing legal proceedings".
   - nitter.net posts a notice that X Corp sent cease-and-desist letters on 24 Aug and 8 Sep 2026 demanding Nitter instances shut down.
   - Other mirrors sit behind proof-of-work bot checks, which were not bypassed.
   - So there is **no live public mirror of his feed as of this writing**, and 2026 coverage relies only on Wayback copies.

## 1. Source ledger

| # | Title / what | Date | Venue | URL | Type | % read |
|---|---|---|---|---|---|---|
| 1 | PolitiTweet @elonmusk archive (207 sampled pages + ~40 targeted pages) | 2011–Apr 2023 | polititweet.org | https://polititweet.org/tweets?account=44196397 | [T-primary] | ~30% of pages (6,188 posts parsed) |
| 2 | Wayback copies of Nitter/xcancel @elonmusk timelines (79 snapshots) | Jan 2023–Sep 2026 | web.archive.org | e.g. https://web.archive.org/web/20260911070834/https://xcancel.com/elonmusk | [T-primary] | 100% of each snapshot (~1,650 posts) |
| 3 | Wayback copies of 30 single-post pages on xcancel/nitter, 2026 | 2026 | web.archive.org | e.g. https://web.archive.org/web/2026*/xcancel.com/elonmusk/status/* | [T-primary] | 100% |
| 4 | WSJ, "Elon Musk's Hard Turn to Politics, in 300,000 of His Own Words" (via Gigazine summary; the WSJ original is paywalled) | Aug 2024 | WSJ / gigazine.net | https://gigazine.net/gsc_news/en/20240827-elon-musk-politics-x-post | [Report] | 100% of summary, 0% of original |
| 5 | The Economist, "Elon Musk's transformation, in his own words" (38,000 posts) | 21 Nov 2024 | economist.com (Wayback) | https://www.economist.com/briefing/2024/11/21/elon-musks-transformation-in-his-own-words | [Report] | ~5% (paywall; only the intro was readable) |
| 6 | WION on the Economist's sleep/posting-time chart | 4 Mar 2025 | wionews.com | https://www.wionews.com/world/elon-musk-sleeps-less-analysis-shows-when-does-doge-chief-hit-the-bed-8777136 | [Report] | 100% |
| 7 | Just the News, reporting a NOTUS/Social Blade count (141.5 posts/day) | 25 Feb 2025 | justthenews.com | https://justthenews.com/accountability/media/elon-musk-averages-1415-posts-x-day-over-past-month-report | [Report] | 100% |
| 8 | Aaj Tak / India Today OSINT, Social Blade analysis (154/day; 29,172 posts in 2024) | 20 Feb 2025 | aajtak.in | https://www.aajtak.in/world/story/elon-musk-posts-154-times-a-day-where-does-he-find-the-time-tesla-x-spacex-ntcpvp-dskc-2172003-2025-02-20 | [Report] | 100% |
| 9 | "Elon Talks, Tesla Falls" (daily post counts, 20 Jan–28 Feb 2025) | 2025 | Substack (veridelisi) | https://veridelisi.substack.com/p/elon-talks-tesla-falls-the-more-elon | [Report] | 100% |
| 10 | Zenodo dataset README: complete Musk tweets with emotion and Big Five annotation | 2025 | zenodo.org | https://zenodo.org/records/14836471 | README only (data not downloaded) | 100% of page |
| 11 | R-bloggers, "Visualizing Elon Musk's Twitter addiction" (Kaggle data, Jan–Oct 2022) | Nov 2022 | r-bloggers.com | https://www.r-bloggers.com/2022/11/visualizing-elon-musks-twitter-addiction | [Report] | 100% |
| 12 | Bloomberg Law / Businessweek, "Everything Elon Musk Has Tweeted About Since Jan. 31" (2,747 tweets) | 14 Oct 2022 | bloomberglaw.com | https://news.bloomberglaw.com/mergers-and-acquisitions/everything-elon-musk-has-tweeted-about-since-jan-31 | [Report] | ~15% (charts and paywall not readable) |
| 13 | CCDH misinformation counts (via TechCrunch, CNN affiliate, AFP) | Aug and Nov 2024 | press | https://techcrunch.com/2024/11/05/elon-musks-false-and-misleading-election-claims-have-been-viewed-2-billion-times-on-x | [Report] (search snippets only) | ~10% |
| 14 | Lines.com page on Polymarket weekly "# of Musk tweets" market (2026 pace) | Jun 2026 | lines.com | https://www.lines.com/prediction-markets/politics/elon-musk-of-tweets-june-12-june-19 | [Report] (low reliability, contradicts itself) | 100% |
| 15 | nitter.net shutdown notice; xcancel suspension notice | Oct 2026 | live sites | https://nitter.net , https://xcancel.com | primary notice | 100% |
| 16 | Axios, "Engagement with Musk's tweets explodes post takeover" | Dec 2022 | axios.com | https://www.axios.com/2022/12/06/musk-tweets-engagement-data | blocked (403) | 0% |

## 2. Quantitative findings

### 2.1 Total volume and posting rate

**Lifetime totals**
- **[MEASURED] Lifetime post counter on his profile**, read from archived mirror pages. It counts posts, replies, reposts and quotes, net of deletions:

| Date | Counter |
|---|---|
| 31 Jan 2023 | 22,499 |
| 23 Aug 2023 | 29,803 |
| 1 Jan 2024 | 35,492 |
| 1 Jul 2024 | 47,921 |
| 3 Dec 2024 | 61,082 |
| 6 Jan 2025 | 65,529 |
| 7 Jun 2025 | 79,698 |
| 7 Dec 2025 | 90,703 |
| 25 Mar 2026 | 100,027 |
| 1 Jul 2026 | 105,100 |
| 11 Sep 2026 | 108,395 |

  - **He passed 100,000 posts in about March 2026.**
  - Roughly 79% of his lifetime output (about 86,000 of 108,000) was posted after 31 Jan 2023.
- **[REPORTED: Zenodo dataset README]** "Complete Musk Tweets": 60,567 tweets from 4 Jun 2010 to 24 Jan 2025. A political-annotation subsample keeps the 18,262 tweets over 49 characters, so only about 30% of his tweets are longer than 49 characters. The sample's length data agrees (§2.4).
- **[REPORTED: WSJ via Gigazine]** About 42,000 posts and replies from 2019 to July 2024. His own words total about 300,000. Including the posts he replied to, the exchange runs to about 1.5 million words. (The two word counts have different bases; this reconciles the "300,000" headline with the 1.5M figure.)

**Rate by period**

**[MEASURED]** Net posts per day, from differences in the counter above (45 dated readings):

| Period | Posts/day |
|---|---|
| Feb–May 2023 | 32.7 |
| May–Aug 2023 | 38.8 |
| Aug–Dec 2023 | 45.3 |
| Jan–Apr 2024 | 65.3 |
| Apr–Jul 2024 | 71.9 |
| Jul–Sep 2024 | 50.5 |
| **Sep–Dec 2024 (election)** | **118.0** |
| Dec 2024–Jan 2025 | 130.8 |
| **Jan–Feb 2025 (early DOGE)** | **134.0** |
| 24 Feb–4 Mar 2025 | **150.8 (peak measured)** |
| Mar–Apr 2025 | 102.3 |
| **Apr–Jul 2025 (DOGE wind-down, Trump feud)** | **~48–52** |
| Jul–Aug 2025 | 69.8 |
| Sep–Nov 2025 | 56.3 |
| Dec 2025–Mar 2026 | 86.3 |
| Mar–Jun 2026 | 51.2 |
| Jul–Sep 2026 | **~45.6** |

- **Calendar 2024 [MEASURED]:** 35,492 → 65,529 between 1 Jan 2024 and 6 Jan 2025, about **30,000 posts (≈82/day)**.
- This matches the **[REPORTED: India Today OSINT / Social Blade]** figure of 29,172 posts in 2024, 18,335 of them after his Trump endorsement.
- Jan–Jul 2024 [MEASURED]: about 12,400. This matches **[REPORTED: WSJ]**: about 13,000 posts Jan–Jul 2024, "nearly the same as all of 2023"; about 9/day in 2019 vs about 61/day in 2024.

**Estimated yearly totals before 2023 [MEASURED, n = 6,188-post PolitiTweet sample × 4; includes retweets; ± about 10%]**

| Year | Estimated posts |
|---|---|
| 2012 | ~330 |
| 2013 | ~480 |
| 2014 | ~240 |
| 2015 | ~480 |
| 2016 | ~860 |
| 2017 | ~1,420 |
| 2018 | ~2,520 |
| 2019 | ~3,480 (≈9.5/day, matching WSJ's 9/day) |
| 2020 | ~3,720 |
| 2021 | ~3,350 |
| 2022 | ~5,510 (≈15/day) |
| 1 Jan–3 Apr 2023 | ~2,300 (≈25/day) |

**Other published counts**
- **[REPORTED: NOTUS / Social Blade via Just the News]** 4,246 posts in the 30 days before 25 Feb 2025 (141.5/day), with 1,314 in the peak week.
- **[REPORTED: India Today]** 154/day during 18–25 Nov 2024. Weekly averages: May 2024 332, Jun 270, Jul 415, Aug 437, Sep 580, Nov 977.
- **[REPORTED: veridelisi Substack]** 20 Jan–28 Feb 2025: mean 106 posts/day, maximum 219, minimum 29.
- **[REPORTED: R-bloggers, Kaggle data]** Jan–Oct 2022: about 11 tweets/day, one every 2h08m on average, and "most of his tweets are replies."
- **[REPORTED: Lines.com, low reliability]** 2026 Polymarket tracker: 186 counted posts in the week of 2–9 Jun 2026, about 27/day. This tracker counts main-feed posts, quotes and reposts but not most replies. The counter-based figure (all types) for Jun–Jul 2026 is about 53/day, which suggests roughly half his 2026 output is replies.

**Takeaway.** Volume grew about 15× from 2019 (~9/day) to the Feb 2025 peak (~150/day), tracking political involvement. It has since settled at **about 45–55/day in mid-2026**: roughly 1,400–1,600 posts a month, still five times his 2019 rate.

### 2.2 Time of day

- **[REPORTED: The Economist chart, via WION]** Posts span 2014–Nov 2024. His only consistent gap is about 3–10 am (US Central). That gap appears only on days he stops posting, and Nate Silver read the chart as evidence he sleeps less.
- **[MEASURED n=885 timestamped posts from 2023–26 snapshots, UTC; weak, because snapshots catch bursts]**
  - Peaks at 07 UTC (82 posts; about 1–2 am Central) and 17–18 UTC (64 and 74; about noon–1 pm Central).
  - Trough at 09–13 UTC (20–29 per hour; about 3–8 am Central).
  - This matches the Economist's 3–10 am sleep window. Late-night posting (00–03 Central) is a heavy, normal part of his output.
- **[REPORTED: R-bloggers, 2022]** Lull from 3–6 am Texas time; he posts "at nearly all waking hours."

### 2.3 Post type: replies vs originals vs reposts vs quotes

**[MEASURED] Share of all collected items** (PolitiTweet sample 2012–Apr 2023; mirror snapshots after)

| Year | n | Reply | Original | Retweet | Quote |
|---|---|---|---|---|---|
| 2012 | 83 | 7% | 78% | 14% | – |
| 2013 | 120 | 23% | 68% | 9% | – |
| 2015 | 120 | 22% | 57% | 22% | – |
| 2016 | 215 | 45% | 34% | 20% | – |
| 2017 | 355 | 55% | 32% | 12% | – |
| 2018 | 630 | 64% | 24% | 11% | – |
| 2019 | 870 | 67% | 22% | 11% | – |
| 2020 | 930 | **75%** | 19% | 6% | – |
| 2021 | 837 | **76%** | 19% | 5% | – |
| 2022 | 1,378 | 71% | 24% | 5% | – |
| 2023 (PolitiTweet + "with replies" snapshots) | 797 | 71% | 16% | 9% | 4% |

**From "Tweets & Replies" snapshots only** (the only unbiased view after PolitiTweet ends; small and clustered)

| Year | n | Reply | Original | Retweet | Quote |
|---|---|---|---|---|---|
| 2023 | 120 | 82% | 8% | 5% | 5% |
| 2024 | 62 | 84% | 6% | 5% | 5% |
| 2025 | 188 | 34% | 10% | 30% | 27% |
| 2026 | 25 (biased: single-post pages archived because they were newsworthy) | 48% | 28% | – | 24% |

- **Shift:** from 2016 on he was mainly a replier, at three replies to every original post. In 2025–26 a large share moved to **quote-posts and reposts**: amplifying other accounts with a one-to-three-word comment such as "Exactly", "💯", "🎯", "Wow" or "True".
- On the "Tweets" tab (no replies) in 2025–26, **reposts are 48–50%** and **quotes about 30%** of what he puts on his main feed. Only about 12% are standalone originals.
- Quote-posting shows up in 2023 data and dominates by 2025. This fits WSJ's finding of heavy interaction with a small set of accounts.

### 2.4 Post-length distribution

**[MEASURED]** Own text only, with URLs and leading @handles removed; retweets excluded.

| Era | n | Median chars | p25 / p75 / p90 chars | Median words | 0 words (emoji/link only) | 1–3 words | 4–10 | 11–25 | 26+ |
|---|---|---|---|---|---|---|---|---|---|
| 2010–17 | 819 | 80 | 34 / 111 / 123* | 14 | 0% | 14% | 24% | 60% | 2% |
| 2018–19 | 1,330 | 41 | 15 / 88 / 117* | 8 | 2% | 28% | 31% | 33% | 6% |
| 2020–21 | 1,668 | 34 | 11 / 83 / 152 | 6 | 3% | 32% | 29% | 24% | 11% |
| 2022 | 1,309 | 32 | 8 / 75 / 141 | 6 | 4% | 33% | 33% | 22% | 9% |
| 2023 | 726 | 25 | 5 / 66 / 106 | 4 | 3% | **40%** | 30% | 22% | 6% |
| 2024 | 152 | 22 | 3 / 54 / 121 | 4 | 8% | 38% | 31% | 15% | 8% |
| 2025 | 449 | 23 | 4 / 61 / 117 | 4 | 6% | **41%** | 27% | 19% | 7% |
| 2026 | 95 (incl. 20 newsworthy single-post pages, so skews long) | 27 | 8 / 78 / 180 | 5 | 8% | 34% | 26% | 20% | 12% |

\*Before 2020 PolitiTweet cuts long posts at about 117 characters, so the upper percentiles are understated. 61 of the 2010–17 posts and 187 of the 2018–19 posts were cut off this way.

- **Shape:** posts have shortened steadily. The median fell from about 14 words (2010–17) to **4 words (2023–26)**.
- **About 40% of everything he writes since 2023 is 1–3 words**, and another 3–8% is emoji or a link with no words at all.
- A long tail remains: about 5–10% of posts run to 26+ words. These are policy arguments, engineering explanations and multi-paragraph rants, often in reply threads.
- After paid long posts arrived (2023), he occasionally posts very long pieces; the 2026 p90 is 180 characters.
- Cross-check: **[REPORTED: Zenodo README]** only 18,262 of 60,567 tweets (30%) exceed 49 characters through Jan 2025.

### 2.5 Frequency-ranked reply words, phrases and emoji

**(a) Whole replies, ranked** — the full text of a reply after removing @handles and links, lowercased.
- [MEASURED] All replies, 2012–2026, n = 4,393 (PolitiTweet sample plus mirror snapshots).
- Format is reply : count. The share of all replies is in brackets for the top items.

| Rank | Reply | Count |
|---|---|---|
| 1 | **"Yes"** | 105 (2.4%) |
| 2 | **"🤣"** | 91 (2.1%) |
| 3 | **"🤣🤣"** | 61 (1.4%) |
| 4 | link/image only | 53 |
| 5 | **"Exactly"** | 50 (+5 "Exactly!") |
| 6 | **"True"** | 42 |
| 7 | "Yeah" | 29 |
| 8 | "💯" | 25 |
| 9 | **"!!"** | 24 |
| 10 | "Absolutely" | 23 |
| 11 | "Wow" | 21 |
| 12 | "Yup" | 21 |
| 13 | "Interesting" | 20 |
| 14 | "😂" | 19 (all 2023+) |
| 15 | "!" | 17 |
| 16 | "Haha" | 15 |
| 17 | "Sure" | 13 |
| 18 | "Cool" | 12 |
| 19 | "🔥🔥" | 12 |
| 20 | "Ok" | 12 |
| 21 | "…" | 12 |

Next tier:
- "🎯" 10, "Agreed" 10, "Definitely" 9, "🤔" 9, "🔥" 9, "Coming soon" 9, "🤣💯" 8, "No" 8, "Nice" 8, "Good point" 8, "Pretty much" 8
- "Accurate" 7, "😉" 7, "Same" 7, "Indeed" 6, "Good question" 6, "For sure" 6, "🧐" 6, "Sigh" 6, "👍" 5, **"Concerning" 5**, "Haha true" 5
- "Working on it" 4, "Looking into it" 4, "Yikes" 4, "Seriously" 4, "Good thread" 4, "❤️" 4, "lol" 4, "Thanks!" 4
- "Fate 🖤 irony" 3, "Good summary" 3, "CGI IRL" 3

**(b) Opening word of any non-repost post** [MEASURED n=6,548]

| Rank | Opener | Count |
|---|---|---|
| 1 (tie) | 🤣 | 183 |
| 1 (tie) | Yes | 183 |
| 3 | I | 171 |
| 4 | The | 164 |
| 5 | This | 118 |
| 6 | Yeah | 108 |
| 7 | Exactly | 88 |
| 8 | We | 84 |
| 9 | Tesla | 80 |
| 10 (tie) | True | 77 |
| 10 (tie) | Good | 77 |
| 12 | Thanks | 66 |

Then: Wow 48, Haha 46, ! 46, 💯 39, Cool 37, Absolutely 36, Interesting 32, Yup 32, 😂 32, Maybe 30.

**(c) Families of agreement words** [MEASURED, share of all non-repost posts, n=6,548]

| Family | Count | Share |
|---|---|---|
| yes / yeah / yup / yep | 325 | **5.0%** |
| 🤣-led | 183 | 2.8% |
| contains "!!" | 89 | 1.4% |
| exactly | 88 | 1.3% |
| true | 77 | 1.2% |
| wow | 48 | 0.7% |
| haha | 47 | 0.7% |
| "!!" alone | 44 | 0.7% |
| 💯 | 39 | 0.6% |
| absolutely | 36 | 0.5% |
| interesting | 32 | 0.5% |
| 🔥 | 30 | 0.5% |
| good point / good question | 29 | 0.4% |
| 🤔 / 🧐 / 🤨 | 22 | 0.3% |
| agreed | 19 | 0.3% |
| 🎯 | 15 | 0.2% |
| accurate | 14 | 0.2% |
| **concerning** | 9 | **0.1%** |

**Surprise.** "Concerning" is far rarer than its meme status implies: 0.1% of posts overall, peaking at 0.7% in 2023. The real workhorses are **"Yes", "🤣", "Exactly", "True" and "!!"**.

**(d) Shift in short replies by era** [MEASURED]

| Era | n replies | Leading short replies |
|---|---|---|
| 2010–19 | 1,354 | "Yes" 38, "Exactly" 11, "Ok" 8, "True" 7, "Coming soon" 5, "Good point" 5, "Definitely" 5, "Haha" 5, "Thanks!" 4 |
| 2020–22 | 2,319 | "🤣" 65, "Yes" 58, "🤣🤣" 45, "True" 27, "Exactly" 26, "💯" 16, "Yup" 15, "Absolutely" 14 |
| 2023–26 | 720 | "🤣" 25, **"😂" 19**, **"!!" 17**, "Exactly" 13, "Wow" 12, "🤣🤣" 11, "Yeah" 11, "💯" 9, "Interesting" 9, "True" 8, "Concerning" 4, "Nuts" 3 |

- 2010–19 replies are customer-service and engineering in tone: "Coming soon", "Good point", "Will do", "Looking into it", "Working on it".
- 2020–22 brings laugh-emoji agreement.
- 2023–26 adds 😂 as a second laugh emoji and "!!" as a standalone reply.

**(e) Emoji**

[MEASURED] Occurrences / number of posts containing the emoji:

| Era | Posts with any emoji | Top emoji |
|---|---|---|
| 2010–19 (n=2,149) | **5.5%** | 🤣 28/16, ♥️ 16/8, 😀 12/11, 💨 10/10, 🖤 9/4, 🚀 9/6, 😉 6/5, 🛰 4/4 |
| 2020–22 (n=2,977) | **11.9%** | 🤣 263/177, 💯 29/29, 🔥 25/16, ♥️ 17/11, 🇺🇸 13/3, 🎯 10/10, 🖤 9/8, 🤔 9/9 |
| 2023–26 (n=1,422) | **16.5%** | 🤣 83/59, 😂 48/48, 🇺🇸 40/11, 🔥 31/22, 💯 26/26, 🎯 10/10, 🤨 5/5, 🧐 4/4, 🤷‍♂️ 4/4 |
| All (n=6,548) | 10.8% | 🤣 374, 🔥 60, 💯 55, 🇺🇸 53, 😂 48, ♥️ 40, 🎯 20, 🖤 18, 🚀 18, 🤔 17 |

- 🤣 is by far his signature: 252 posts, about 3.8% of all non-repost posts. It is often doubled ("🤣🤣") and often combined: "🤣💯", "🔥🤣", "🤣🎯".
- **First 🤣 in the sample: 14 Apr 2019.** **First 😂: 5 Feb 2023**, and 😂 is used only from 2023 on.
- 🇺🇸 appears in repeated bursts ("🇺🇸🇺🇸🇺🇸🇺🇸 Team America 🇺🇸…", 6 Jun 2025).
- 🖤 shows up in his "Fate 🖤 irony" phrase.
- **[REPORTED: Bloomberg Businessweek, Oct 2022]** ran a "most-used emoji" chart on 2,747 tweets. The chart was not readable in text.

**(f) Style markers** [MEASURED, % of non-repost posts]

| Marker | 2010–17 | 2018–19 | 2020–21 | 2022 | 2023 | 2024 | 2025 | 2026 |
|---|---|---|---|---|---|---|---|---|
| "!" | 9.8 | 9.5 | 14.0 | 13.2 | 15.7 | 10.5 | 13.1 | 7.4 |
| "!!" | 0.2 | 1.3 | 1.6 | 1.2 | 2.3 | 0.7 | 2.2 | 0 |
| "?" | 2.4 | 2.5 | 3.0 | 5.4 | 4.7 | 5.9 | 5.8 | – |
| 🤣/😂 | 0 | 1.2 | 4.7 | 7.5 | 8.5 | 6.6 | 7.1 | 3.2 |
| "haha" | 0.1 | 1.6 | **2.6** | 1.0 | 0.1 | 0 | 0 | 0 |
| " & " instead of "and" | 6.2 | **13.9** | 12.7 | 6.1 | 5.0 | 0.7 | 1.1 | 3.2 |
| ALLCAPS word (4+ letters) | 2.2 | 0.8 | 1.0 | 0.5 | 0.6 | 0 | 2.2 | 4.2 |
| "legacy media" | 0 | 0 | 0 | 0.1 | 0 | 3.9 | 0.7 | 2.1 |
| "Grok" | 0 | 0 | 0 | 0 | 0.1 | 0 | 6.9 | **9.5** |
| "AI" | 0.7 | 0.2 | 0.6 | 0.8 | 1.1 | 1.3 | 2.2 | **6.3** |
| "Tesla" | **9.3** | 8.5 | 5.8 | 3.3 | 1.7 | 2.0 | 2.4 | 5.3 |

- "haha" gave way to 🤣 and 😂 after 2022.
- The "&" habit is a strong marker of his 2018–21 voice.
- Emphatic capitals return in 2025–26, e.g. "MOUNTAIN of DISGUSTING PORK", "VASTLY", "Universal HIGH INCOME".

### 2.6 Who he replies to

**[MEASURED]** Top reply targets, by first @handle replied to:

| Era | Top targets |
|---|---|
| 2010–19 | @erdayastronaut 42, @flcnhvy 31, @annerajb 18, @teslaownerssv 18, @fredericlambert 13, @cleantechnica 10, @teslarati 10, @nextspaceflight 9, @electrekco 8, @kristennetten 7 |
| 2020–22 | @ppathole 91, @wholemarsblog 90, @teslaownerssv 84, @erdayastronaut 71, @billym2k 57, @flcnhvy 48, @evafoxu 39, @lexfridman 27, @teslarati 23, @engineers_feed 21, @waitbutwhy 17, @pmarca 11 |
| 2023–26 | **@billym2k 41, @cb_doge 32**, @thebabylonbee 11, @stillgray 11, @teslaownerssv 11, @evafoxu 11, @wholemarsblog 10, @monitoringbias 9, @davidsacks 9, @wallstreetsilv 8, @kanekoathegreat 8, @alx 8, @jason 7, @iamharaldur 7, @scottadamssays 7, @endwokeness 6, @basedbeffjezos 6 |

- He has always talked mostly to a small ring of fan, enthusiast and ally accounts. The ring changed:
  - **2010–19:** space and EV bloggers and journalists (Everyday Astronaut, Electrek, Teslarati, CleanTechnica).
  - **2020–22:** Tesla and SpaceX superfans, plus meme accounts (Pranay Pathole, WholeMarsBlog, BillyM2k, Lex Fridman, WaitButWhy).
  - **2023–26:** meme, "news-aggregator" and political-commentary accounts (cb_doge, BillyM2k, Babylon Bee, Stillgray, MonitoringBias, EndWokeness, Kanekoa, DavidSacks), alongside the Tesla fan core.
- **[REPORTED: WSJ via Gigazine]** He interacted with @EndWokeness more than 470 times (2019–Jul 2024). In 2023 he made at least 18 replies, reposts or quotes to foreign leaders (Modi, Netanyahu, Orbán).

### 2.7 Topic drift

**[MEASURED] Top content words** (stopwords removed):

| Era | Top words |
|---|---|
| 2010–19 | tesla 195, good 102, model 73, great 63, spacex 63, rocket 62, car 57, thanks 56, launch 50, falcon 47, dragon 38, orbit 32, production 29, landing 29, mars 26, solar 27, starship 27 |
| 2020–22 | tesla 142, **twitter 108**, good 93, great 89, should 78, true 72, people 64, haha 56, beta 46, production 43, starship 38, starlink 36, mars 33, energy 32 |
| 2023–26 | **people 38**, twitter 29, should 28, good 24, tesla 24, exactly 24, great 23, **media 20**, true 20, wow 18, **grok 18**, **legacy 15**, platform 13, **america 11**, free 12, public 12 |

**[REPORTED: WSJ via Gigazine]**
- Monthly posts with political terms in 2024 ran about 230× their 2019 level.
- Over 400 posts said "woke". Since 2023, more than 1,400 posts used DEI, racist, trans or gender terms.
- In 2022, about 900 posts named Twitter, roughly twice as many as named Tesla. In Nov 2022, 36% of his posts mentioned Twitter.
- His first post over 1M likes was the coronavirus panic post (6 Mar 2020). The Trump endorsement (13 Jul 2024) drew 210M+ views.

**[REPORTED: CCDH]**
- 50 false or misleading election posts drew 1.2B views (Jan–Jul 2024).
- At least 87 such posts drew more than 2B views in 2024.
- His political posts drew 17.1B views after the Trump endorsement.

## 3. How he does things on X: real examples

Unless marked otherwise, every example below is [T-primary]: the post text read on PolitiTweet (P, with tweet id where noted) or on a Wayback copy of a Nitter/xcancel page (N). Dates are UTC. Each subsection quotes a few short representative posts and summarizes the other sampled examples.

### 3.1 Announcing products and launches

| Date | Post | Src |
|---|---|---|
| 2018-08-07 | "Am considering taking Tesla private at $420. Funding secured." | P, id 1026872652290379776 |
| 2019-11-06 | "Cybertruck unveil on Nov 21 in LA near SpaceX rocket factory" | P |
| 2022-11-19 | "Tesla FSD 10.69.3.1 going to wide release now" | P |
| 2026-02-03 | "To the stars! @SpaceX & @xAI are now one company" (quote-post) | N |

Other sampled announcements follow the same form: the Tesla Semi unveil webcast (2017-11-12, P), a service-scheduling app release (2018-12-20, P), the Model Y unveil date and venue (2019-03-03, P), Battery Day (2020-09-11, P), the FSD Beta 10 rollout (2021-09-02, P), a Grok-generated Starship flight summary (2023-11-18, N), and an in-house AI training stack written in C for 220k GB300s (2026-05-28, N).

**Pattern**
- Announcements are bare, factual one-liners: product + date + place, no adjectives. Occasional hype is bolted on, e.g. "blow your mind clear out of your skull."
- Version numbers ("10.69.3.1") and engineering specs appear in the announcement itself.
- Schedules come with hedges ("probably Tuesday", "about 2 weeks later", "~"). Many software timelines slip, and he re-announces them in replies.
- Launch-day material is mostly **reposts of @SpaceX/@Tesla** plus a short quote ("Congrats…"). He also announces through replies to fan accounts rather than standalone posts.

### 3.2 Celebrating

| Date | Post | Src |
|---|---|---|
| 2019-02-04 | "First firing of Starship Raptor flight engine! So proud of great work by @SpaceX team!!" | P |
| 2020-12-09 | SN8 exploded on landing: "…but we got all the data we needed! Congrats SpaceX team hell yeah!!" | P |
| 2025-06-22 | "Super congratulations to the @Tesla_AI software & chip design teams on a successful @Robotaxi launch!!…" | N |

Other sampled celebrations: Falcon/Dragon reaching orbit (2012-05-22, P), the first crewed Dragon return (2020-08-02, P), the first Giga Texas production cars and opening party (2022-04-08, P), Morocco's World Cup run (2022-12-10, P), and SpaceX's 96 launches in 2023 (2023-12-29, N).

**Pattern**
- Credit almost always goes to "the team" by company or site ("Tesla China team", "Giga Berlin team", "tower team & supporting contractors"), not to himself.
- Double "!!" is the norm.
- Exploding test vehicles are celebrated as data wins: "we got all the data we needed!"

### 3.3 Mourning

| Date | Post | Src |
|---|---|---|
| 2021-09-16 | "RIP, Sir Sinclair. I loved that computer." | P |
| 2025-09-10 | Charlie Kirk shooting: "The shot looked real bad, but I sure hope Charlie makes it somehow" (19:28 UTC) | N |

Other sampled examples: a note on Christopher Hitchens ending "May the good man RIP" (2011-12-21, P); a one-word "RIP" reply (2019-07-15, P); "A tragic loss of life" (2023-02-06, P); after the Kirk shooting he **reposted** others' tributes (e.g. @JDVance and @TheCriticalDri2, within 2 hours) instead of writing his own (2025-09-10, N); and a joke-mourning post about a game character (2025-01-06, N).

**Pattern**
- Mourning is rare in the sample: 14 hits for RIP/tragic/condolence out of about 6,500 posts, and several of those are figurative ("Tragic case of ego/ability").
- When it happens it is short: 1–8 words, plus a personal detail ("I loved that computer").
- He often mourns by reposting others' longer tributes.
- He does not write long eulogies. Searches around the Queen Elizabeth (Sep 2022), Kobe Bryant (Jan 2020) and Shinzo Abe (Jul 2022) deaths turned up nothing in the sampled pages; that is not proof of silence.

### 3.4 Apologizing

| Date | Post | Src |
|---|---|---|
| 2018-04-13 | "Yes, excessive automation at Tesla was a mistake. To be precise, my mistake. Humans are underrated." | P, id 984882630947753984 |
| 2022-12-18 | After the backlash over banning links to rival platforms: "…My apologies. Won't happen again." | P |
| 2023-03-07 | "I would like to apologize to Halli for my misunderstanding of his situation…" | P, id 1633253950198624257 |

Other sampled apologies: for TSLA's one-day swing ("Sorry for the roller coaster", 2012-01-17, P); for "heavy stuff" about climate change (2013-05-25, P); to Unsworth, conceding "his actions against me do not justify my actions against him" (2018-07-18, P, cut off in archive); for a software-update glitch, with a policy change (2019-05-05, P); for an app outage blamed on increased network verbosity (2021-11-20, P); "Sorry about that. Fixing as fast as possible!" (2022-10-28, P); and a "My apologies, but…" defense of an FSD rollout priority on HW4 Model Y (2024-07-25, N).

**Pattern**
- Apologies are frequent for product and service glitches. The template: "Sorry" + a technical cause + the fix or policy change.
- Personal apologies are rare. They come after private contact ("Better to talk to people than communicate via tweet", 2023-03-07, after a video call with Halli). They often assign part of the blame elsewhere ("things I was told").
- He follows them with a joke: "I also apologize to everyone named Alex in this 🧵" (2023-03-08).
- **Sarcastic pseudo-apologies are common:** "I would like to apologize for firing these geniuses…" (2022-11-15); "I'm not sorry for party rocking" (2021-10-17).
- He also writes "My apologies, but…" to defend a decision (2024-07-25).

### 3.5 Attacking

| Date | Post | Src |
|---|---|---|
| 2022-09-21 | "Unsurprisingly, Reich is also a hypocrite" | P |
| 2023-11-18 | "…X Corp will be filing a thermonuclear lawsuit against Media Matters and ALL those who colluded…" | N |
| 2025-06-05 | The Trump feud, 17:39–20:26 UTC: about 40 posts in under 3 hours, including quote-posts of old Trump/Johnson/Thune statements ("Where is the Mike Johnson of 2023!?"), "Such an obvious lie. So sad.", and a since-deleted post alleging Trump appeared in the Epstein files | N |

Other sampled attacks: calling a Reveal story "bs" (2018-05-22, P); calling short-selling "a scam legal only for vestigial reasons" (2021-01-28, P); accusing the WSJ of "giving foot massages to a criminal" (2022-11-24, P); calling the NYT's output uninteresting "propaganda" (2023-04-02, P); calling Steve Bannon "a criminal" (2025-06-06, N); and labeling a post by AOC "misleading" (2026-09-11, N).

**Pattern**
- Attacks are short, labeling verdicts: "bs", "hypocrite", "criminal", "propaganda", "lie".
- He quote-posts the target's own past words ("Remember this?", "Where is the man who wrote these words?").
- Attacks run in rapid bursts mixed with ally amplification ("💯", "Exactly") and laugh emoji ("This just gets better and better 🤣🤣…").
- Legal threats escalate with superlatives ("thermonuclear").

### 3.6 Deflecting and denying

| Date | Post | Src |
|---|---|---|
| 2018-07-15 | "Reports that I am a top donor to GOP are categorically false." | P |
| 2024-02-11 | "…SpaceX is selling Starlink terminals to Russia. This is categorically false." | N |
| 2026-02-01 | "Legacy media lies relentlessly" | N |

Other sampled denials: "I didn't walk back anything, apart from media hype" (2015-10-10, P); denying any communication with Trump (2022-05-06, P); "Bad reporting by FT" on Starlink funding in Ukraine (2022-10-07, P); "Headline is misleading." (2022-10-21, P); "Utterly false" (2022-12-02, P); "Legacy media lies" and legacy media as a "click-maximizing machine" (2024-11-25, N); saying legacy media tried to cancel him over his inauguration-rally gesture (2025-01-24, N); and rejecting reported Epstein links, calling Epstein "a creepy loser" (2026-02-01, N).

**Pattern**
- Flat denial words: "false", "categorically false", "utterly false", "misleading".
- He then turns the frame onto the messenger: FT, Merc News, "legacy media", "far-left propagandists".
- Before 2022 he named the specific outlet and gave counter-facts (dollars, percentages). After 2023 it is the generic "legacy media lies", often with a Grok link as proof (2024-11-25).

### 3.7 Joking

| Date | Post | Src |
|---|---|---|
| 2018-06-19 | "That's ridiculous, lions can't vote, they don't even have opposable thumbs…" | P |
| 2022-04-28 | "Next I'm buying Coca-Cola to put the cocaine back in" | P, id 1519480761749016577 |
| 2022-10-28 | "Comedy is now legal on Twitter" | P, id 1586104694421659648 |

Other sampled jokes: offering Einhorn "a box of short shorts" (2018-08-01, P); "420 operational Starlink satellites 🛰 😉" (2020-04-22, P); "Excuse me, I only sell Doge!" (2020-07-18, P); "Just a scratch. We can buff it out." (2020-11-14, P; repeated 2022-10-16); a fake drug called "Regretamine" (2021-03-01, P); "Entering Twitter HQ – let that sink in!" with a sink video (2022-10-26, P, id 1585341984679469056); and a sarcastic "money can't buy happiness" post (2026-02-05, N).

**Pattern**
- His humor runs on number jokes (69, 420), puns and literalism ("lions can't vote"), and shitposting about short-sellers.
- Joking is usually done by reaction rather than composition: "🤣" or "🤣🤣" alone is his second most common reply.
- Since 2025, sarcasm is often political: "Hitler was a far-left socialist. Therefore, socialists are Hitler. Inescapable logic 😂" (2026-08-09).

## 4. How his posting changed, by era

All numbers here are [MEASURED] from §2 unless labeled.

| Era | Volume | Mix | Voice | Topics and circle |
|---|---|---|---|---|
| **2010–2015: Occasional CEO-broadcaster** | ~250–500 posts a year | 57–78% originals, few replies | Full sentences (median 14 words); early "!!" ("Falcon flew perfectly!!", 2012). Reads Sam Harris/Hitchens, posts climate essays ("Sorry for all the heavy stuff abt climate change", 2013) | Tesla, SpaceX, solar |
| **2016–2019: Reply-guy engineer and customer service** | ~860 (2016) → ~3,500 (2019), ≈9.5/day | Replies rise 45% → 67% | "&" for "and" (14% of posts), "Coming soon", "Good point", "Will do", "Looking into it", "Sorry for the delay". Engineering numbers in replies (Isp, bar, T/W). 🤣 appears in 2019 | Clashes: "pedo guy" (2018, now deleted; not in archive), "Funding secured" (2018), Unsworth apology |
| **2020–2022: Meme lord, then Twitter owner** | ~3,700/yr (2020) → ~5,500 (2022) | Replies peak at **75–76%** | Median 6 words; 🤣 becomes his top reply; "haha" peaks (2.6%) | Doge/420/69 jokes; COVID contrarianism ("The coronavirus panic is dumb", 2020-03-06); free speech from Mar 2022; Twitter dominates late 2022 (#2 content word). Reply circle: superfans and meme accounts. Political turn May 2022 ("This is false… with Trump") |
| **2023: Owner-operator of X** | ~25/day (Q1) → ~45/day (Q4) | ~70–82% replies | **😂 and standalone "!!" appear**; median 4–5 words | "Concerning" peaks (0.7%), Grok launches (Nov 2023), "legacy media", Media Matters ("thermonuclear lawsuit"). Circle moves to meme/political aggregators (cb_doge, BillyM2k, Babylon Bee) |
| **2024: Campaign surrogate** | 65–72/day (H1) → **118/day (Sep–Dec)**; ~30,000 posts in the year | Quotes 35% of main-feed items | "legacy media" 3.9%, "free speech" 2.6%, Democrats 2.0%; "You are the media now" | [REPORTED: WSJ] political-term posts 230× 2019; [REPORTED: CCDH] 87+ false/misleading election posts with 2B+ views |
| **Early 2025: DOGE peak** | **134–151/day** (Jan–early Mar) | Quote-posts and reposts dominate: main feed ~48% reposts, ~30% quotes, ~12% originals | ALLCAPS returns | — |
| **Apr–Jul 2025: Break and feud** | Falls to ~48–52/day | — | Trump feud of 5 Jun 2025 (~40 posts in under 3 hours); "America Party" floated ("Is it time to create a new political party…80% in the middle?", 2025-06-05) | — |
| **Late 2025–2026: AI and Grok promoter** | 56–86/day (late 2025) → ~45–53/day (mid-2026); passed 100,000 lifetime posts in Mar 2026 | — | — | "Grok" in 9.5% and "AI" in 6.3% of sampled 2026 posts; xAI–SpaceX merger ("To the stars!", 2026-02-03); Neuralink ("Jesus-level miracles", 2026-06-30); "Universal HIGH INCOME" (2026-04-17). Culture-war posting continues (Epstein denials Feb 2026, race and crime claims Jun 2026, "Legacy media lies relentlessly") |

**Constant across all eras**
- Very short replies.
- A small ring of fan and ally accounts.
- Credit to "the team" when celebrating.
- Timelines with "~" and "probably".
- Instant 🤣 reactions.
- Rapid bursts at night (US time).

## 5. Signature recurring phrases: first known use

"First in the sample" is a **lower bound**: the sample covers about 25% of 2011–Apr 2023 pages and about 1,800 posts from 2023–26, so earlier uses may exist. Dates marked **(verified)** were read on the archive page itself.

| Phrase | First known use found | Notes |
|---|---|---|
| "!!" (double exclamation) | 2012-05-22 "Falcon flew perfectly!!" | Lifelong; standalone "!!" reply mostly 2020+ |
| "Exactly" | 2013-02-27 | 81 uses in sample |
| "Interesting" (often "Interesting..." with a link) | 2013-04-13 | |
| "Coming soon" | 2014-04-05 | Mostly 2014–2021 product era |
| "Haha" | 2015-04-30 | Fades after 2022 |
| "Wow" | 2016-10-02 | Rising in 2025–26 |
| "true" as a whole reply | 2016-08-09 | |
| "Yup" | 2017-09-29 | |
| "Looking into it" | 2018-04-08 | Customer-service era |
| "Fate loves irony" / "Fate 🖤 irony" | 2018-06-15 | Recurs, e.g. "Fate loves irony, but hates hypocrisy" (2023-02-18) |
| "Sigh" | 2018-06-16 | |
| "Funding secured" | 2018-08-07 **(verified, id 1026872652290379776)** | One-off that became a meme |
| "Absolutely" | 2018-11-19 | |
| "nobody ever changed the world on 40 hours a week" | 2018-11-26 **(verified)** | |
| 🤣 | 2019-04-14 | #1 emoji |
| "The machine that makes the machine" | 2019-10-15 "designing & building the machine that makes the machine" | |
| 69 / 420 jokes | $420 on 2018-08-07; "69% want car tunnels!" on 2019-12-28; "420 operational Starlink satellites" on 2020-04-22 | |
| "Just a scratch(, we can buff it out)" | 2020-11-14 | Repeated 2022-10-16; a 2025 Ship 36 use is reported but unverified |
| "Doge" | 2020-07-18 in sample | Reported earlier (2019) |
| "Use Signal" | 2021-01-07 **(verified)** | |
| "Gamestonk!!" | 2021-01-26 **(verified)** | |
| "Dogecoin is the people's crypto" | 2021-02-04 **(verified)** | |
| "The most entertaining outcome is the most likely" | **2021-02-10 (verified, id 1359612035374473217)** | Repeated 2025-06-07 as "Most entertaining outcome is most likely", just after the Trump feud |
| 💯 | 2021-10-27 | |
| "Free speech is essential to a functioning democracy" | 2022-03-25 | Start of the Twitter-buy framing |
| "Extremely concerning" / "Concerning" | 2022-04-19 | Peak 2023 |
| "woke mind virus" | 2022-04-20 ("The woke mind virus is making Netflix unwatchable") | Possibly earlier |
| "Who controls the memes Controls the Universe" | 2022-05-26 in sample | Possibly earlier |
| "Accurate" | 2022-05-03 | |
| "Population collapse … much bigger risk to civilization than global warming" | 2022-08-26 **(verified)** | |
| "let that sink in" | 2022-10-26 **(verified)** | |
| "Comedy is now legal on Twitter" | 2022-10-28 **(verified)** | |
| "Vox Populi, Vox Dei" | 2022-11-19 | Used with polls |
| "Unregretted user-minutes" | 2022-12-13 | X's metric |
| "legacy media" | 2022-12-27 | Dominant by 2024 |
| 😂 | 2023-02-05 | |
| "Grok" | 2023-11-18 | |
| "This is the way" | 2024-11-25 in sample | |
| "You are the media now" | 2024-11-25 ("That's because it's working. You are the media now.") | |
| "Best part is no part" | **2025-08-13** (reply, lightbrd/Wayback snapshot of 14 Aug 2025) | |
| "Hardcore" (engineers / software) | 2019-11-24 "Hardcore body engineers will understand this…"; still in use 2025–26 ("Just hardcore engineering", 2026-06-30) | |

## 6. Per-source notes: published analyses

- **WSJ (Aug 2024), via Gigazine.**
  - Sample: about 42,000 posts and replies, 2019–Jul 2024.
  - Volume: 9/day (2019) → 61/day (2024). Jan–Jul 2024 alone ≈ 13,000 posts.
  - Wording: about 300,000 of his own words; about 1.5M including the posts he replied to.
  - Political terms 230× up. "Woke" 400+ times. 1,400+ posts using DEI/racist/trans/gender terms since 2023.
  - @EndWokeness interaction 470+ times.
  - Quoted lines: "DEI must DIE" (2023-12-15); "I fully endorse President Trump" (2024-07-13, 210M+ views).
  - Self-label "avowed moderate" (2019); he announced he would vote Republican on 2022-05-18. [Report]
- **The Economist (21 Nov 2024).** 38,000 posts; headline "Poster boy". The intro quotes his plea that leaders post themselves: "…that way people know it's really you!" [Report]. Its sleep and posting-time chart, via WION, shows a 3–10 am gap. The body was paywalled.
- **NOTUS / Social Blade; India Today / Social Blade.** These are the best published 2024–25 rate figures, and they agree with the counter measurements in §2.1 to within about 3%.
- **R-bloggers (Kaggle, 2022).** About 11/day, a lull from 3–6 am, mostly replies.
- **Zenodo (2025).** 60,567 tweets, 2010 – Jan 2025, each typed as reply/retweet/original and annotated for emotion and Big Five. Only 18,262 exceed 49 characters.
- **Bloomberg Businessweek (Oct 2022).** 2,747 tweets. The readable text says: "much of his activity… replying to people tweeting about SpaceX, Starlink and Tesla", and that he uses "shorthand popular with heavy social media users".
- **CCDH (2024).** False or misleading election posts: 50 with 1.2B views (Jan–Jul); at least 87 with 2B+ views (full year). Political posts drew 17.1B views after the endorsement.

## 7. Cross-source synthesis: most important insights for prediction

1. **His default output is a 1–4-word reaction, not a statement.** The median post since 2023 is about 4 words, and about 40% of posts are 1–3 words. The modal reply is "Yes", "🤣", "Exactly", "True", "!!", "💯", "Wow" or "Interesting". A realistic Musk reply to most things is a single affirmation or emoji. Multi-paragraph posts are a minority (about 5–10%). (§2.4, §2.5)
2. **He amplifies more than he authors.** 2016–2024 was reply-dominated (64–84% replies). In 2025–26 his main feed is about half reposts and about 30% quote-posts with a one-word gloss. Only about 10–12% of what appears on his profile is an original standalone post. (§2.3)
3. **Volume tracks political mobilization, not business news.** It went from ~9/day (2019) to ~118/day (election fall 2024) to ~150/day (DOGE, Feb–Mar 2025), then fell back to ~45–55/day by mid-2026. Expect spikes when he is in a political fight; quieter, AI-focused posting otherwise. (§2.1)
4. **His circle is small and self-reinforcing.** In every era, about a dozen fan or ally accounts receive a large share of his replies. The ring shifted from space and EV bloggers to Tesla superfans to political meme aggregators (cb_doge, BillyM2k, Babylon Bee, EndWokeness). He mostly agrees with them. (§2.6)
5. **Laughter is his most common reply, and the laugh emoji changed.** "haha" (2015–21) gave way to 🤣 (2019+, #1 emoji, about 4% of posts), then 😂 (2023+). 🤣 also goes on attacks ("This just gets better and better 🤣🤣"). (§2.5)
6. **Apologies are operational, rarely personal.** He says "Sorry"/"Apologies" readily for glitches and delays, with a cause and a fix. He apologizes to people only after private contact, and the apology carries partial blame-shifting ("things I was told that were untrue"). Sarcastic "apologies" are about as common as real ones. (§3.4)
7. **Celebration always credits "the team"**, named by site or company, with "!!". A failed test is "got all the data we needed!" (§3.2)
8. **Mourning is minimal and often done by reposting.** Expect "RIP" or a one-line personal note, not a eulogy. (§3.3)
9. **Denial formula:** "This is false" / "categorically false" / "misleading", then blame the outlet. After 2023 it collapses to the generic "Legacy media lies", sometimes with Grok links as proof. (§3.6)
10. **Fights escalate in rapid bursts:** about 40 posts in under 3 hours on 5 Jun 2025. The mechanics are quote-posting the opponent's old words, short insult labels ("criminal", "hypocrite"), ally amplification, and a closing "Most entertaining outcome is most likely". (§3.5)
11. **Product announcements are terse.** Product + date + place, with version numbers and hedged timelines ("probably", "~", "next week"). (§3.1)
12. **Nocturnal posting.** Heavy output at 00–03 Central time, with the only reliable gap at about 3–10 am. (§2.2)
13. **Surprise: "Concerning" is a meme, not a habit.** It appears in only about 0.1% of posts (peak 0.7% in 2023), whereas "Yes" alone appears in about 2.4% of replies. (§2.5)
14. **Tesla has receded and AI/Grok has risen.** Tesla was in 9% of his posts in 2010–17 and about 2% in 2023–25. "Grok" reached about 7–10% and "AI" about 6% of sampled 2026 posts. (§2.5f)
15. **Typography fingerprints by era:** "&" for "and" (2018–21, 13–14%), "~" before numbers, "!!", rare all-lowercase replies ("true", "bs"), and emphatic ALLCAPS returning in 2025–26.

## 8. Quote-bank check (against the skill's verified-quotes list)

**Tier 1**

| Quote | Status | Exact wording, date, source |
|---|---|---|
| "If anyone is arrested, I ask that it only be me" | **CONFIRMED** | X, 2020-05-11, PolitiTweet id 1259945593805221891: "…I will be on the line with everyone else. If anyone is arrested, I ask that it only be me." (posted as Tesla restarted production against Alameda County rules) https://polititweet.org/tweet?account=44196397&tweet=1259945593805221891 |
| "Educational background is irrelevant" | **CONFIRMED** | X, 2020-02-03 UTC (2 Feb US time), id 1224182478501482497, in a Tesla AI hiring post ("Educational background is irrelevant, but all must…") |
| "The most entertaining outcome is the most likely." | **CONFIRMED** | Earliest found 2021-02-10, id 1359612035374473217. Recurs 2025-06-07 as "Most entertaining outcome is most likely" (xcancel snapshot) |
| "You are the media now." | **CONFIRMED** (one instance) | 2024-11-25 quote-post: "That's because it's working. You are the media now." (nitter.privacydev snapshot of 26 Nov 2024). An earlier 2024 use may exist |
| "The machine that makes the machine is vastly harder than the machine itself." | **Not found verbatim** | Nearest found: 2019-10-15, "designing & building the machine that makes the machine — please consider working at Tesla or SpaceX." |
| "A collapsing birth rate is the biggest danger civilization faces by far." | **Not found** | Nearest found: 2022-08-26, "Population collapse due to low birth rates is a much bigger risk to civilization than global warming" (id 1563020169160851456) |
| "Just a scratch" | **Pattern CONFIRMED** | 2025 instance not seen. Earlier uses: "Just a scratch. We can buff it out." (2020-11-14), "Just a scratch, we can buff it out" (2022-10-16) |

Not encountered in the samples, so neither confirmed nor refuted:
- "I regret some of my posts…" (Jun 2025)
- "Vindicated"
- "Civilization is rare…"
- "Never incorporate…"
- "I am uncomfortable growing Tesla…"
- "Success maybe, excitement guaranteed!"
- "Congrats @SpaceX team on an exciting test launch…"
- "Looks like we can be ready to launch again…"

**Tier 2 → upgrades**

| Tier 2 line | Status | Exact wording, date, source |
|---|---|---|
| Excessive automation was a mistake | **UPGRADE** | "Yes, excessive automation at Tesla was a mistake. To be precise, my mistake. Humans are underrated." X reply to @timkhiggins, 2018-04-13, id 984882630947753984 |
| Nobody ever changed the world on 40 hours a week | **UPGRADE** | "There are way easier places to work, but nobody ever changed the world on 40 hours a week" X, 2018-11-26, id 1067173497909141504 |
| The best part is no part | **UPGRADE** (short form) | "Best part is no part" X reply, 2025-08-13 (Wayback of lightbrd.com/elonmusk, 14 Aug 2025). The "best process is no process" half was not seen |
| "Let that sink in" | **UPGRADE** (exact wording; Tier 2 restricts it to event references) | "Entering Twitter HQ – let that sink in!" 2022-10-26, id 1585341984679469056 |
| "Comedy is now legal" | **UPGRADE** (exact wording) | "Comedy is now legal on Twitter" 2022-10-28, id 1586104694421659648 |

**Extra verified posts useful for the bank**
- "The coronavirus panic is dumb" (2020-03-06, id 1236029449042198528)
- "Tesla stock price is too high imo" (2020-05-01, id 1256239815256797184)
- "Use Signal" (2021-01-07)

Also verified, and quoted elsewhere in this file: the Coca-Cola post (2022-04-28, §3.7), "Funding secured" (2018-08-07, §3.1) and the Halli apology (2023-03-07, §3.4); plus a pronouns joke aimed at Anthony Fauci (2022-12-11).

## 9. Gaps

- **Web search access was limited during compilation**, so some published analyses could not be found or reached.
  - Economist body (paywall).
  - WSJ original (paywall; summary used).
  - Axios (403), Guardian (blocked).
  - Bloomberg charts (images).
  - Full CCDH reports.
  - Any NYT or Washington Post quantitative studies.
  - Academic papers on arXiv or Google Scholar were not searched.
- **Live mirrors are gone.** xcancel is suspended, nitter.net has shut down after X Corp's Aug–Sep 2026 cease-and-desist letters, and other instances sit behind bot checks. So **2026 data is limited to Wayback snapshots** (189 items, plus 30 single-post pages that are biased toward newsworthy posts).
  - Sep 11 – Oct 16, 2026 is essentially unsampled.
  - Reply share for 2024–26 rests on small "Tweets & Replies" samples (n = 62, 188 and 25).
- **PolitiTweet text cut-off.** Text before about 2020 is cut at about 117 characters, so long-post percentiles for 2010–19 are understated.
- **PolitiTweet completeness.** It does not hold posts deleted before it began tracking, e.g. the 2018 "pedo guy" post.
- **Time-of-day data is weak.** It comes from clustered snapshot bursts.
- **"First known use" dates are lower bounds** from a 25% sample, except where marked verified.
- **Not downloaded:** the Zenodo, Kaggle and HuggingFace datasets. With them one could compute exact per-year reply shares and vocabulary for 2010 – Jan 2025.
