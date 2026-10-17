# Sources

How to read citations in the reference files:

- **Letters A–H** (for example "(B)" or "(G)") point to one of eight primary-source research passes done in October 2026. The ledger for each pass is below: every source, its date and URL, and how much of it was read. The working notes behind each pass aren't published, because they contain hundreds of transcript excerpts; where a reference file needs a specific source, it names the venue and date instead. The underlying sources are all public and listed here.
- **V1 row N / V2 row N** point to the fact-check ledgers in [`factcheck-2025-2026.md`](factcheck-2025-2026.md) (V1) and [`factcheck-pre-2025.md`](factcheck-pre-2025.md) (V2).
- **H §…** points to [`x-posting-analysis.md`](x-posting-analysis.md), which is published in full.
- **Transcript tags:** [T-official] means an official or human-made transcript, [T-auto] a machine transcript, [Report] a news report quoting the source.

## A: Lex Fridman podcast (all five episodes)

| # | Title | Date | Venue | URL | Type | % read |
|---|---|---|---|---|---|---|
| 18 | Elon Musk: Tesla Autopilot | Apr 2019 | Lex Fridman Podcast (then "AI Podcast") | https://web.archive.org/web/2023/https://karpathy.ai/lexicap/0018-large.html (episode: https://lexfridman.com/elon-musk/) | [T-auto] Whisper-large, no speaker labels | 100% (~32 min) |
| 49 | Elon Musk: Neuralink, AI, Autopilot, and the Pale Blue Dot | 12 Nov 2019 | Lex Fridman Podcast | https://lexfridman.com/wordpress/wp-content/uploads/2019/11/elon_musk_lex_fridman_2_transcript.pdf | [T-official] Rev.com transcript, speaker-labelled | 100% (~36 min) |
| 49 (alt) | same | same | same | https://web.archive.org/web/2023/https://karpathy.ai/lexicap/0049-large.html | [T-auto] | downloaded only, not needed |
| 252 | Elon Musk: SpaceX, Mars, Tesla Autopilot, Self-Driving, Robotics, and AI | 28 Dec 2021 | Lex Fridman Podcast | https://web.archive.org/web/2023/https://karpathy.ai/lexicap/0252-large.html | [T-auto] Whisper-large, no speaker labels | ~100% of the transcript (2h31m of a 2h39m episode; the missing part is ad reads) |
| 252 (check) | same | same | same | https://podscripts.co/podcasts/lex-fridman-podcast/252-elon-musk-spacex-mars-tesla-autopilot-self-driving-robotics-and-ai | [T-auto] second machine transcript | spot-checked 4 key passages, all matched |
| 400 | Elon Musk: War, AI, Aliens, Politics, Physics, Video Games, and Humanity | 9 Nov 2023 (transcript posted 10 Nov) | Lex Fridman Podcast | https://lexfridman.com/elon-musk-4-transcript/ | [T-official] speaker-labelled, timestamped | 100% (2h16m) |
| 438 | Elon Musk and Neuralink team (Musk, DJ Seo, Matthew MacDougall, Bliss Chapman, Noland Arbaugh) | 2 Aug 2024 | Lex Fridman Podcast | https://lexfridman.com/elon-musk-and-neuralink-team-transcript/ | [T-official] | Musk's segment (0:00–1:28) 100%. The other ~7 h was searched for every mention of "Elon" and those passages were read (~5%). |
| — | Podcast index (to check for later episodes) | fetched 2026-10-16 | lexfridman.com | https://lexfridman.com/podcast/ | — | searched for "Musk" |

Notes on the transcripts:
- The official lexfridman.com transcripts (#400, #438) and the Rev PDF (#49) are cleaned: almost every "um/uh" is removed and there are some mishearings, e.g. "government deficiency commission" for *efficiency*, "foam paradox" for *Fermi*, "inquisitive" for *acquisitive*, and "area under the code" for *curve*.
- Whisper (Lexicap) also removes many fillers, but #252 still shows heavy restarts ("so, so, so therefore", "the, the, the").
- Lexicap timestamps for #252 are relative to its own audio and may be several minutes off the YouTube chapter times.

---

## B: The Joe Rogan Experience (seven episodes, 2018–2025)

| # | Title | Date | Venue | URL | Type | % read |
|---|---|---|---|---|---|---|
| 1 | JRE #1169 – Elon Musk | 7 Sep 2018 (~2h36m) | The Joe Rogan Experience | https://podscripts.co/podcasts/the-joe-rogan-experience/1169-elon-musk | [T-auto] | 100% |
| 2 | JRE #1470 – Elon Musk | 7 May 2020 (~2h00m) | JRE | https://podscripts.co/podcasts/the-joe-rogan-experience/1470-elon-musk | [T-auto] | 100% |
| 3 | JRE #1609 – Elon Musk | 11 Feb 2021 (~3h24m) | JRE | https://podscripts.co/podcasts/the-joe-rogan-experience/1609-elon-musk | [T-auto] | 100% |
| 4 | JRE #2054 – Elon Musk | 31 Oct 2023 (~2h41m) | JRE | https://podscripts.co/podcasts/the-joe-rogan-experience/2054-elon-musk | [T-auto] | 100% |
| 5 | JRE #2223 – Elon Musk | 4 Nov 2024, eve of the election (~2h41m) | JRE | https://podscripts.co/podcasts/the-joe-rogan-experience/2223-elon-musk | [T-auto] | 100% |
| 6 | JRE #2281 – Elon Musk | 28 Feb 2025 (~3h10m) | JRE | https://podscripts.co/podcasts/the-joe-rogan-experience/2281-elon-musk | [T-auto] | 100% |
| 7 | JRE #2404 – Elon Musk | 31 Oct 2025 (~3h20m) | JRE | https://podscripts.co/podcasts/the-joe-rogan-experience/2404-elon-musk | [T-auto] | 100% |
| 8 | Podscripts JRE episode index, pages 1–16 (#2150–#2566, the latest listed) | crawled 2026-10-16 | podscripts.co | https://podscripts.co/podcasts/the-joe-rogan-experience?page=1..16 | index | 100% of those pages |
| 9 | Web searches for a 2026 Musk JRE appearance (2 queries) | 2026-10-16 | web | (TheTVDB, Apple Podcasts, Podchaser, Newsweek results) | [Report] | result snippets only |

**2026 check:** no JRE episode with Musk was found for 2026. The podscripts index runs through #2566, and its only Musk episodes from #2150 onward are #2223, #2281 and #2404. Searches turned up 2026 Musk podcast appearances only on other shows (for example Moonshots with Peter Diamandis). So #2404 (Oct 2025) is his latest JRE.

---

## C: Talks, speeches and on-stage conversations (2003–2026)

| # | Title | Date | Venue | URL | Type | % read |
|---|---|---|---|---|---|---|
| 1 | TED: "The mind behind Tesla, SpaceX, SolarCity" (Chris Anderson) | Feb 2013 | TED2013, Long Beach | https://www.ted.com/talks/elon_musk_the_mind_behind_tesla_spacex_solarcity/transcript | T-official | 100% |
| 2 | TED: "The future we're building — and boring" | Apr 2017 | TED2017, Vancouver | https://www.ted.com/talks/elon_musk_the_future_we_re_building_and_boring/transcript | T-official | 100% |
| 3 | TED: "A future worth getting excited about" | Apr 2022 (recorded at Giga Texas) | TED | https://www.ted.com/talks/elon_musk_a_future_worth_getting_excited_about/transcript | T-official | 100% |
| 4 | TED2022 live: "Twitter, Tesla and how his brain works" | Apr 14 2022 | TED2022, Vancouver | https://www.ted.com/talks/elon_musk_elon_musk_talks_twitter_tesla_and_how_his_brain_works_live_at_ted2022/transcript | T-official | 100% |
| 5 | Stanford ETL lecture | Oct 2003 | Stanford STVP | https://www.youtube.com/watch?v=afZTrfvB2AQ | T-auto | 100% |
| 6 | Caltech commencement | Jun 2012 | Caltech | https://www.youtube.com/watch?v=u688eJkLBRM | T-auto | 100% |
| 7 | USC Marshall commencement | May 16 2014 | USC | https://www.youtube.com/watch?v=SuxneQ-ANgw (re-upload; USC's own e7Qh-vwpYH8 has captions disabled) | T-auto | 100% |
| 8 | Code Conference (Swisher & Mossberg) | Jun 1 2016 | Recode, Rancho Palos Verdes | https://www.youtube.com/watch?v=wsixsRI-Sz4 | T-auto | 100% |
| 9 | YC "How to Build the Future" (Sam Altman) | Sep 2016 | Y Combinator / Tesla Fremont | https://www.youtube.com/watch?v=tnBQmEqBCY0 | T-auto | 100% |
| 10 | YC AI Startup School (Garry Tan) | Jun 2025 | YC, San Francisco | https://www.youtube.com/watch?v=cFIlta1GkiE | T-auto | 100% |
| 11 | Khan Academy conversation (Sal Khan) | Apr 2013 | Khan Academy, Mountain View | https://www.youtube.com/watch?v=vDwzmJpI4io | T-official (Khan-uploaded captions) | 100% |
| 12 | WSJ CEO Council (Matt Murray) | Dec 8 2020 | WSJ (remote) | https://www.youtube.com/watch?v=RHihEU0PVlc (3rd-party upload) | T-auto | 100% |
| 13 | WSJ CEO Council (Joanna Stern) | Dec 6 2021 | WSJ (remote) | https://www.youtube.com/watch?v=Dl5BJt8UTE0 (3rd-party upload; WSJ's lSD_vpfikbE had no captions) | T-auto | 100% |
| 14 | WSJ CEO Council (Thorold Barker), extra | May 23 2023 | WSJ, London/remote | https://www.youtube.com/watch?v=PDy7s1SDDn4 | T-auto | ~95% |
| 15 | VivaTech (Maurice Lévy + Arnault, Heydemann, Dubey + floor Q&A) | Jun 16 2023 | VivaTech, Paris | https://www.youtube.com/watch?v=tMdFGrnp5XI (Sky News stream) | T-auto | 100% |
| 16 | VivaTech (Maurice Lévy + numbered floor Q&A) | May 23 2024 | VivaTech, Paris (video link) | https://www.youtube.com/watch?v=nUzGCwFckWM | T-auto | 100% |
| 17 | WEF Davos conversation with Larry Fink | Jan 22 2026 | WEF Annual Meeting | https://www.rev.com/transcripts/musk-speaks-at-wef (WEF's own page returned 403) | T-auto (Rev) | 100% |
| 18 | DealBook Summit (Andrew Ross Sorkin), extra | Nov 29 2023 | NYT DealBook, NYC | https://www.rev.com/transcripts/dealbook-summit-2023-elon-musk-interview-transcript | T-auto (Rev) | 100% |
| 19 | World Government Summit (Al Gergawi) | Feb 13 2017 | WGS, Dubai | https://worldgovernmentssummit.org/observer/articles/detail/elon-musk-on-why-the-world-needs-a-universal-basic-income ; video https://www.youtube.com/watch?v=rCoFKUJ_8Yo | Report | quotes only |
| 20 | World Government Summit "Conversation 2.0" | Feb 15 2023 | WGS, Dubai (video) | https://en.protothema.gr/2023/02/15/elon-musk-criticises-the-concept-of-world-government-at-the-world-government-summit-video | Report | quotes only |
| 21 | Abundance360 Summit (Diamandis) | Mar 19 2024 | A360 (video link) | https://www.diamandis.com/blog/elon-abundance-ai-human-survival | Report (host's recap) | quotes only |
| 22 | Qatar Economic Forum (Mishal Husain, Bloomberg) | May 20 2025 | QEF, Doha (video link) | https://krdo.com/money/cnn-business-consumer/2025/05/20/elon-musk-says-hell-spend-a-lot-less-money-on-politics/ ; https://kuwaittimes.com/article/28144/business/musk-committed-to-being-tesla-ceo-for-next-5-years | Report | quotes only |
| 23 | Ron Baron conference talks (2016, 2022); Milken | — | — | baroncapitalgroup.com, evannex.com: no transcript; Milken appearance not found | — | 0% |

In total, 18 primary transcripts were read in full: about 150,000 words of Musk on stage, from 2003 to 2026.

## D: Journalist interviews (2012–2026)

| # | Title | Date | Venue | URL | Type | % read |
|---|---|---|---|---|---|---|
| S1 | SpaceX: Entrepreneur's race to space (Pelley) | aired 2012-03-18 / 06-03 | CBS 60 Minutes | https://www.cbsnews.com/news/spacex-entrepreneurs-race-to-space/ | [T-official] CBS script | 100% |
| S2 | Tesla and SpaceX: Elon Musk's industrial empire (Pelley) | 2014-03-30 | CBS 60 Minutes | https://www.cbsnews.com/news/tesla-and-spacex-elon-musks-industrial-empire/ | [T-official] | 100% |
| S3 | Tesla CEO Elon Musk: The 60 Minutes Interview (Stahl) | 2018-12-09 | CBS 60 Minutes | https://www.cbsnews.com/news/tesla-ceo-elon-musk-the-2018-60-minutes-interview/ | [T-official] (as aired) | 100% |
| S4 | Full Q&A: Elon Musk on Recode Decode (Swisher) | rec. 2018-10-31, pub. 11-02 | Recode/Vox | https://www.vox.com/2018/11/2/18053428/recode-decode-full-transcript-elon-musk-tesla-spacex-boring-company-kara-swisher-podcast | [T-official] (edited) | ~85% (tech mid-section skimmed) |
| S5 | Elon Musk Details 'Excruciating' Personal Toll of Tesla Turmoil | 2018-08-16 | New York Times | https://www.nytimes.com/2018/08/16/business/elon-musk-interview-tesla.html (via web.archive.org) | [Report] | ~95% |
| S6 | Elon Musk BBC interview (James Clayton), full 57-min upload | 2023-04-11/12 | BBC / Twitter Spaces | https://www.youtube.com/watch?v=955qSKQ0Hlc | [T-auto] | 100% |
| S7 | CNBC Transcript: Elon Musk sits down with David Faber | 2023-05-16 | CNBC | https://nbcuniversalnewsgroup.com/cnbc/2023/05/16/cnbc-exclusive-cnbc-transcript-elon-musk-sits-down-with-cnbcs-david-faber-live-on-cnbc-tonight/ (Wayback 2025-09-14) | [T-official] | 100% |
| S8 | DealBook Summit 2023 Elon Musk Interview (Sorkin) | 2023-11-29 | NYT DealBook | https://www.rev.com/transcripts/dealbook-summit-2023-elon-musk-interview-transcript | [T-official] (Rev) | 100% |
| S9 | Don Lemon Show ep. 1 | posted 2024-03-18 | X / YouTube | video https://www.youtube.com/watch?v=hhsfjBpKiTw; reports: AP (clickondetroit.com/business/2024/03/19/4-things-to-know-...), CNBC (cnbc.com/2024/03/18/elon-musk-suggests-his-prescription-ketamine-use-is-good-for-investors.html), ABC7/CNN (abc7ny.com/don-lemon-elon-musk-interview-ketamine/14545836/) | [Report] | reports 100%; video 0% |
| S10 | Kudlow interview ("with great difficulty") | 2025-03-10 | Fox Business | https://futurism.com/elon-musk-trying-not-cry-tesla ; Mediaite | [Report] | report 100%; video 0% |
| S11 | Musk and DOGE on Bret Baier | 2025-03-27 | Fox News Special Report | https://www.rev.com/transcripts/musk-and-doge-on-brett-baier | [T-official] (Rev) | Musk portions ~100% |
| S12 | Hannity interviews Trump and Musk | 2025-02-18 | Fox News | https://rollcall.com/factbase/trump/transcript/donald-trump-interview-sean-hannity-fox-news-with-elon-musk-february-18-2025/ | [T-official] (Factbase) | Musk lines 100% |
| S13 | Mishal Husain interview, Qatar Economic Forum | 2025-05-20 | Bloomberg | video https://www.youtube.com/watch?v=80I8LbQvHUU ; report https://macmyths.com/what-happened-when-mishal-husain-pressed-elon-musk-on-doge-and-he-called-her-an-npc/ | [Report] (secondary, low-tier) | report 100%; video 0% |
| S14 | Pogue interview at Starbase | aired 2025-06-01 | CBS Sunday Morning | https://www.cbsnews.com/amp/texas/news/elon-musk-disappointed-by-trump-big-beautiful-bill-doge ; TheWrap; HuffPost via Yahoo | [Report] | reports 100%; video 0% |
| S15 | Jordan Peterson interview | 2024-07-22 | Daily Wire / X | https://okcfox.com/news/nation-world/elon-musk-likens-childs-gender-transition-to-being-killed-by-the-woke-mind-virus-... | [Report] | report 100% |
| S16 | The full-length interview with Elon Musk (Minton Beddoes) | ~2026-07-23 | The Economist | video https://www.youtube.com/watch?v=XuoqKYxDHVc ; reports https://www.ibtimes.co.uk/elon-musk-economist-media-feud-1811078 , https://www.ibtimes.co.uk/pathetic-crash-out-elon-musk-dragged-childish-reaction-journalists-loathed-comment-1811539 | [Report] | reports 100%; video 0% |
| — | Axios on HBO (Nov 2018) | 2018-11-25 | HBO | https://www.youtube.com/watch?v=4qUA3nNWyCg | not read (captions blocked) | 0% |
| — | Tucker Carlson (Fox) | 2023-04-17/18 | Fox News | https://www.youtube.com/watch?v=bQ45lsDxL6Q | not read | 0% |

## E: His own writing and long-form written interviews

| # | Title | Date | Venue | URL | Type | % read |
|---|---|---|---|---|---|---|
| 1 | "The Secret Tesla Motors Master Plan (just between you and me)" | 2 Aug 2006 | Tesla blog | web.archive.org/web/2016/https://www.tesla.com/blog/secret-tesla-motors-master-plan-just-between-you-and-me | [T-official] | 100% |
| 2 | "Master Plan, Part Deux" | 20 Jul 2016 | Tesla blog | web.archive.org/web/2017/https://www.tesla.com/blog/master-plan-part-deux | [T-official] | 100% |
| 3 | Master Plan Part 3, "Sustainable Energy for All of Earth" | Apr 2023 | Tesla PDF white paper | tesla.com/ns_videos/Tesla-Master-Plan-Part-3.pdf (archived) | Corporate document, not in his voice | 0%. The PDF text was CID-encoded and couldn't be extracted. |
| 4 | "Master Plan Part IV" | Sep 2025 | tesla.com/master-plan-part-4 | web.archive.org/web/2025/https://www.tesla.com/master-plan-part-4 | [T-official] corporate text, **unsigned** | 100% |
| 5 | "All Our Patent Are Belong To You" | 12 Jun 2014 | Tesla blog | web.archive.org/web/2016/https://www.tesla.com/blog/all-our-patent-are-belong-you | [T-official] | 100% |
| 6 | "A Most Peculiar Test Drive" (rebuttal of the NYT) | 13 Feb 2013 | Tesla blog | web.archive.org/web/2014/https://www.tesla.com/blog/most-peculiar-test-drive | [T-official] | 100% |
| 7 | "Model S Fire" | 4 Oct 2013 | Tesla blog | web.archive.org/web/2014/https://www.tesla.com/blog/model-s-fire | [T-official] | 100% |
| 8 | "The Mission of Tesla" | 18 Nov 2013 | Tesla blog | web.archive.org/web/2016/https://www.tesla.com/blog/mission-tesla | [T-official] | about 95% |
| 9 | "Partial Recall" | Jun 2013 | Tesla blog | web.archive.org/web/2016/https://www.tesla.com/blog/partial-recall | [T-official] | 100% |
| 10 | "The Tesla Approach to Distributing and Servicing Cars" | 22 Oct 2012 | Tesla blog | web.archive.org/web/2016/https://www.tesla.com/blog/tesla-approach-distributing-and-servicing-cars | [T-official] | 100% |
| 11 | "Hyperloop Alpha" (PDF), plus the matching Tesla blog post | 12 Aug 2013 | spacex.com / teslamotors.com | web.archive.org/web/2014/http://www.spacex.com/sites/spacex/files/hyperloop_alpha-20130812.pdf | [T-official] | The intro and first-person section (about 5 of 57 pp) in full, plus the closing open-source note |
| 12 | "Taking Tesla Private" (email to staff, posted to the blog) | 7 Aug 2018 | Tesla blog | web.archive.org/web/2018/https://www.tesla.com/blog/taking-tesla-private | [T-official] | 100% |
| 13 | "Staying Public" | 24 Aug 2018 | Tesla blog | web.archive.org/web/2018/https://www.tesla.com/blog/staying-public | [T-official] | 100% |
| 14 | "Timing is Everything", statement on Falcon 1 Flight 3 | 6 Aug 2008 | spacex.com press | web.archive.org/web/2008/http://www.spacex.com/press.php?page=20080806 | [T-official] | about 90% |
| 15 | "Making Humans a Multi-Planetary Species" | Jun 2017 | *New Space* 5(2), doi 10.1089/space.2017.29009.emu | web.archive.org/web/2018/http://online.liebertpub.com/doi/full/10.1089/space.2017.29009.emu | [T-official]: his edited 2016 IAC talk, in his voice | 100% |
| 16 | "I am Elon Musk, CEO/CTO of a rocket company, AMA!" | 5–6 Jan 2015 | r/IAmA (thread 2rgsan) | api.pullpush.io/reddit/search/comment/?author=elonmuskofficial | [T-official] | 100% of his 26 answers. The parent questions were also fetched. |
| 17 | "I am Elon Musk, ask me anything about becoming a spacefaring civ!" | 23 Oct 2016 | r/spacex (thread 590wi9) | same API | [T-official] | 100% of his 15 answers |
| 18 | Wait But Why Pt 1, "Elon Musk: The World's Raddest Man" | May 2015 | waitbutwhy.com | waitbutwhy.com/2015/05/elon-musk-the-worlds-raddest-man.html | [Interview-print] | 100% |
| 19 | WBW Pt 2, "How Tesla Will Change the World" | Jun 2015 | waitbutwhy.com | waitbutwhy.com/2015/06/how-tesla-will-change-your-life.html | [Interview-print] | about 30%: every Musk-quote paragraph and footnote |
| 20 | WBW Pt 3, "How (and Why) SpaceX Will Colonize Mars" (5 pages) | Aug 2015 | waitbutwhy.com | …/how-and-why-spacex-will-colonize-mars.html/1–5 | [Interview-print], plus a verbatim email from Musk | about 35%: every Musk-quote paragraph on all 5 pages |
| 21 | WBW Pt 4, "The Cook and the Chef: Musk's Secret Sauce" | Nov 2015 | waitbutwhy.com | waitbutwhy.com/2015/11/the-cook-and-the-chef-musks-secret-sauce.html | [Interview-print] | about 40%: all Musk passages |
| 22 | WBW, "SpaceX's Big Fucking Rocket – The Full Story" | Sep 2016 | waitbutwhy.com | waitbutwhy.com/2016/09/spacexs-big-fking-rocket-the-full-story.html | [Interview-print] | about 40% |
| 23 | WBW, "Neuralink and the Brain's Magical Future" | Apr 2017 | waitbutwhy.com | waitbutwhy.com/2017/04/neuralink.html | [Interview-print] | about 20%: all Musk block quotes |
| 24 | Chris Anderson Q&A, "Elon Musk's Mission to Mars" | Oct 2012 | Wired | wired.com/2012/10/ff-elon-musk-qa/ | [Interview-print] | 100% |
| 25 | Tom Junod, "Elon Musk: Triumph of His Will" | Dec 2012 issue | Esquire | esquire.com/news-politics/a16681/elon-musk-interview-1212/ | [Interview-print] in a profile | 100% |
| 26 | Neil Strauss, "Elon Musk: Inventor's Plans for Outer Space, Cars, Finding Love" | Nov 2017 | Rolling Stone | web.archive.org/web/2017/http://www.rollingstone.com/culture/features/elon-musk-inventors-plans-for-outer-space-cars-finding-love-w511747 | [Interview-print] | about 100% |
| 27 | "Dear Twitter Advertisers" | 27 Oct 2022 | X, 3 images | x.com/elonmusk/status/1585619322239561728 | [T-official] | 100% |
| 28 | America Party launch post | 5 Jul 2025 | X | x.com/elonmusk/status/1941584569523732930 | [T-official] | 100% |
| 29 | DOGE farewell post | 28 May 2025 | X | x.com/elonmusk/status/1927877957852266518 | [T-official] | 100% |
| 30 | H-1B fight posts (4) | 27–28 Dec 2024 | X | …/1872744295884841262, …/1872797210066436560, …/1872860577057448306, …/1872862144615838054 | [T-official] | 100% |
| 31 | "I regret some of my posts…" | 11 Jun 2025 | X | x.com/elonmusk/status/1932695486684950962 | [T-official] | 100% |
| 32 | "Never incorporate your company in the state of Delaware" | 30 Jan 2024 | X | x.com/elonmusk/status/1752455348106166598 | [T-official] | 100% |
| 33 | "~25% voting control" reply | 15 Jan 2024 | X | x.com/elonmusk/status/1746999488252703098 | [T-official] | About 90%: the long-post tail was cut off by the endpoint |
| 34 | Midterms post ("fire all politicians…") | 3 Jun 2025 | X | x.com/elonmusk/status/1929984535456035202 | [T-official] | 100% |
| 35 | Welt am Sonntag op-ed backing the AfD | 28 Dec 2024 | Welt am Sonntag, via Euronews | euronews.com/2024/12/28/elon-musk-backs-far-right-afd-party-in-an-op-ed-for-german-newspaper-die-welt | [Report] (translated fragments) | about 10% of the op-ed |
| 36 | SpaceX–xAI merger statement | 2 Feb 2026 | spacex.com / staff memo, via eNCA/AFP | enca.com/business/musk-merges-xai-spacex-bid-build-space-data-centers | [Report] | Fragments only |
| 37 | Kevin Rose, *Foundation* ep. 20 | c. 2012 | Revision3 / YouTube (L-s_3b5fRd8) | youtube.com/watch?v=L-s_3b5fRd8 | — | 0%: captions blocked (HTTP 429), and no transcript was found |
| 38 | r/spacex BFR AMA | 14 Oct 2017 | Reddit | — | — | 0%: not indexed by PullPush |

---

## F: Private communications made public and sworn testimony

| # | Source | Date of material | Venue | URL | Type | % read |
|---|---|---|---|---|---|---|
| S1 | OpenAI email archive. Musk v. Altman court exhibits plus OpenAI blog posts of Mar 2024 and Dec 2024, compiled by habryka. The OpenAI blog pages themselves returned 403. | May 2015 – Oct 2022 | LessWrong (pulled via GraphQL) | https://www.lesswrong.com/posts/5jjk4CDnj9tA7ugxr/openai-email-archives-from-musk-v-altman-and-openai-blog | [T-official] (exhibit text reproduced) | 100% |
| S2 | Musk text-message exhibits H and J, Twitter v. Musk (Del. Ch.), 40 pages | Jan 21 – Jun 17, 2022 | DocumentCloud scan of the court filing | https://www.documentcloud.org/documents/23112929-elon-musk-text-exhibits-twitter-v-musk/ (page images at s3.documentcloud.org/.../pages/...-pN-xlarge.gif) | [T-official] (read from page images) | 100% (all 40 pages; a few cells too small to attribute with certainty, flagged) |
| S3 | "Progress, Precision and Profit," Tesla all-hands email | Apr 17, 2018 | Electrek (full text) | https://electrek.co/2018/04/17/tesla-model-3-production-goal-6000-units-per-week/ | [T-official] | 100% |
| S4 | Contractor "barnacles" follow-up email | ~May 4–6, 2018 | Electrek (full text) | https://electrek.co/2018/05/06/tesla-brutal-review-contractors-firing-vouching-employee/ | [T-official] | 100% |
| S5 | "Remote work is no longer acceptble" and "To be super clear," two Tesla emails | May 31, 2022 | Electrek and Teslarati (full text) | https://electrek.co/2022/06/01/elon-musk-tesla-employees-come-back-office-or-quit/ ; https://www.teslarati.com/musk-clarifies-teslas-updated-work-from-home-policy-in-follow-up-email-to-employees/ | [T-official] | 100% |
| S6 | "Pause all hiring worldwide" ("super bad feeling") exec email, plus the all-staff 10% salaried-cut email | Jun 2–3, 2022 | Teslarati, citing Reuters and @WholeMarsBlog | https://www.teslarati.com/tesla-reportedly-set-to-drop-10-of-its-employees-musk-has-super-bad-feeling-about-economy/ ; https://www.teslarati.com/elon-musk-says-tesla-will-reduce-salaried-headcount-by-10-while-increasing-hourly-employees/ | [Report] (exec email never leaked in full); [T-official] for the staff-email excerpt | 100% of articles |
| S7 | Twitter first all-company email | Nov 9, 2022 | CNBC transcription | https://www.cnbc.com/2022/11/10/read-elon-musks-first-email-to-all-twitter-employees.html | [T-official] | 100% |
| S8 | "A Fork in the Road" | Nov 16, 2022 | CNBC transcription, republished by NBC | https://www.nbcnews.com/tech/tech-news/elon-musk-demands-twitter-staff-commit-long-hours-leave-rcna57455 | [T-official] | 100% |
| S9 | SpaceX Raptor "production crisis" email (Thanksgiving) | Nov 26, 2021 | Space Explored, via Drive Tesla Canada | https://driveteslacanada.ca/spacex/spacex-elon-musk-raptor-engine-production-crisis/ | [T-official] (near-full excerpts) | 100% of article (~90% of email) |
| S10 | "Plan Going Forward," SpaceX email/statement after Falcon 1 Flight 3 failure | Aug 2, 2008 | Universe Today (full text) | https://www.universetoday.com/16440/elon-musk-i-will-never-give-up-after-falcon-1-loss/ | [T-official] | 100% |
| S11 | "Acronyms Seriously Suck" | May 2010 | Vance, *Elon Musk* (2015), via Goodreads quote page | https://www.goodreads.com/quotes/7054854-from-time-to-time-musk-will-send-out-an-e-mail | [T-official] (book reprint) | 100% |
| S12 | 2024 "absolutely hard core about headcount" exec email | Apr 29, 2024 | The Information, via Carscoops | https://www.carscoops.com/2024/04/two-senior-tesla-execs-leave-the-company-hundreds-more-layoffs-reportedly-coming/ | [Report] (excerpts only) | 100% of article |
| S13 | Musk v. Altman trial, Day 1 (opening statements and Musk direct) | Apr 28, 2026 | NPR | https://www.npr.org/2026/04/28/nx-s1-5801438/musk-altman-openai-trial-opening-statements | [Report] | 100% |
| S14 | Musk v. Altman, Days 2–3 (cross, redirect, recross) | Apr 29–30, 2026 | CNBC live blog | https://www.cnbc.com/2026/04/30/openai-trial-elon-musk-sam-altman-live-updates.html | [Report] | 100% |
| S15 | Musk v. Altman, Day 3 | Apr 30, 2026 | The Guardian | https://www.theguardian.com/technology/2026/apr/30/openai-founding-trial-elon-musk-sam-altman | [Report] | 100% |
| S16 | Musk v. Altman, cross-exam on Apr 29 ("jackass") | Apr 29, 2026 | NPR via WLRN | https://www.wlrn.org/npr-breaking-news/2026-04-29/musk-continued-his-testimony-from-yesterday-in-lawsuit-against-openai | [Report] | 100% (fetched summary) |
| S17 | Musk v. Altman trial roundup (Yahoo/Guardian syndication) | Apr–May 2026 | Yahoo Finance | https://finance.yahoo.com/sectors/technology/articles/sam-altman-tries-fend-off-173104980.html | [Report] | 100% (fetched summary) |
| S18 | Musk v. Altman verdict (AP) | May 18, 2026 | WAVY (AP) | https://www.wavy.com/news/national/jury-rules-against-elon-musk-in-his-feud-with-openai-saying-he-filed-his-lawsuit-too-late/amp/ | [Report] | 100% (fetched summary) |
| S19 | Brockman testimony (Reuters) and Achiam testimony | May 5, 2026 and earlier | Khaleej Times (Reuters); NBC Bay Area; chatgptiseatingtheworld | https://www.khaleejtimes.com/business/tech/elon-musk-was-going-to-hit-me-openai-executive-says-at-trial ; https://www.nbcbayarea.com/news/local/testimony-closes-liability-phase-musk-vs-altman-trial/4084688/ ; https://chatgptiseatingtheworld.com/2026/05/05/openai-lawyer-methodically-dissects-elon-musks-case-via-greg-brockman-testimony/ | [Recalled]/[Report] | 100% (summaries) |
| S20 | Musk v. Altman Wikipedia page (dates, verdict, citation list) | 2026 | Wikipedia | https://en.wikipedia.org/wiki/Musk_v._Altman | secondary | ~100% (fetched summary) |
| S21 | Unsworth defamation trial, Musk cross-exam (Day 1) | Dec 3, 2019 | The Guardian | https://www.theguardian.com/technology/2019/dec/04/elon-musk-pedo-guy-insult-was-not-classy-but-not-meant-literally | [Report] | 100% |
| S22 | Unsworth trial | Dec 3, 2019 | Slate | https://slate.com/technology/2019/12/elon-musk-trial-pedo-guy-diver-lawsuit.html | [Report] | 100% |
| S23 | Unsworth verdict | Dec 6, 2019 | CNBC | https://www.cnbc.com/2019/12/06/unsworth-vs-musk-pedo-guy-defamation-trial-verdict.html | [Report] | 100% |
| S24 | SolarCity post-trial opinion, In re Tesla Motors (Del. Ch., VC Slights). Quotes the Musk trial transcript. | Apr 27, 2022 (trial Jul 12–13, 2021) | CourtListener | https://www.courtlistener.com/opinion/6463496/in-re-tesla-motors-inc-stockholder-litigation/ | [T-court-op] | ~35% (keyword-extracted every Musk transcript cite; 64 hits) |
| S25 | SolarCity trial, Day 1 (AP) | Jul 12, 2021 | KMPH (AP); Al Jazeera | https://kmph.com/news/nation-world/musk-to-opposing-lawyer-i-think-you-are-a-bad-human-being ; https://www.aljazeera.com/economy/2021/7/12/elon-musk-set-to-testify-over-tesla-purchase-of-solarcity | [Report] | 100% |
| S26 | SolarCity trial, Day 2 (Bloomberg) | Jul 13, 2021 | Al Jazeera | https://www.aljazeera.com/economy/2021/7/13/elon-musk-spars-with-attorney-during-tesla-solarcity-trial | [Report] | 100% |
| S27 | Tornetta v. Musk post-trial opinion (Del. Ch., Chancellor McCormick). Quotes the Musk trial transcript, his deposition and his emails. | Jan 30, 2024 (trial Nov 2022) | CourtListener | https://www.courtlistener.com/opinion/9470356/richard-j-tornetta-v-elon-musk/ | [T-court-op] | ~30% (keyword extraction; 22 + 4 testimony passages read in context) |
| S28 | Tornetta trial, Musk testimony | Nov 16, 2022 | Al Jazeera (Reuters) | https://www.aljazeera.com/economy/2022/11/16/musk-defends-56bn-pay-package | [Report] | 100% |
| S29 | "Funding secured" securities trial (In re Tesla Securities Litigation, N.D. Cal.), Days 2–3 of Musk testimony | Jan 23–24, 2023 | CNN via ABC17 | https://abc17news.com/money/cnn-business-consumer/2023/01/23/420-price-was-not-a-joke-elon-musk-testifies-again-in-trial-over-controversial-tweet/ ; https://abc17news.com/money/cnn-business-consumer/2023/01/24/elon-musk-is-back-on-the-stand-in-trial-over-controversial-funding-secured-tweet-2/ | [Report] | 100% |
| S30 | DOGE "Fork in the road" and "five things" emails (context) | Jan 28 and Feb 22–24, 2025 | Wikipedia, DOGE article §"Fork in the road and Five things emails" | https://en.wikipedia.org/wiki/Department_of_Government_Efficiency | secondary | 100% of section |
| S31 | Inverse write-up of the 2018 email | Apr 19, 2018 | Inverse | https://inverse.com/article/43905-elon-musk-ignore-rules | [Report] | 100% (redundant with S3) |

Blocked or unreadable sources:
- The openai.com blog posts (403).
- theverge.com and businessinsider.com (crawler blocked).
- Delaware courts PDF server (rejected).
- The WSJ and Washington Post trial articles (paywall or fetch failure).
- The electrive.com 2024 article.

---

## G: Earnings calls, shareholder meetings, product events, SpaceX talks and the 2026 IPO

| # | Title | Date | Venue | URL | Type | % read |
|---|---|---|---|---|---|---|
| 1 | Tesla Q1 2018 earnings call (the "boring bonehead questions" call) | 2018-05-02 | Webcast | https://www.youtube.com/watch?v=mgPz6fKgIJ0 (call audio upload) | [T-auto] | 100% |
| 1b | CNBC, "Here are highlights of Elon Musk's strange Tesla earnings call" | 2018-05-03 | CNBC | https://www.cnbc.com/2018/05/03/here-are-highlights-of-elon-musks-strange-tesla-earnings-call-theyre-killing-me.html | [Report] | 100% |
| 2 | Tesla Q2 2018 earnings call (the apology call) | 2018-08-01 | Webcast | https://www.fool.com/earnings/call-transcripts/2018/08/06/tesla-tsla-q2-2018-earnings-conference-call-transc.aspx | [T-edited] | 100% |
| 3 | Tesla Q4 2019 earnings call | 2020-01-29 | Webcast | https://www.fool.com/earnings/call-transcripts/2020/01/30/tesla-inc-tsla-q4-2019-earnings-call-transcript.aspx | [T-edited] | 100% |
| 4 | Tesla Q2 2020 earnings call | 2020-07-22 | Webcast | https://www.fool.com/earnings/call-transcripts/2020/07/23/tesla-tsla-q2-2020-earnings-call-transcript.aspx | [T-edited] | 100% |
| 5 | Tesla Q4 2022 earnings call | 2023-01-25 | Webcast | https://www.fool.com/earnings/call-transcripts/2023/01/26/tesla-tsla-q4-2022-earnings-call-transcript/ | [T-edited] | 100% |
| 6 | Tesla Q1 2023 earnings call | 2023-04-19 | Webcast | https://www.rev.com/transcripts/tesla-tsla-q1-2023-earnings-call-transcript | [T-edited] | 100% of what is posted (Rev's text stops at about 1:00:17) |
| 7 | Tesla Q2 2023 earnings call | 2023-07-19 | Webcast | https://www.fool.com/earnings/call-transcripts/2023/07/19/tesla-tsla-q2-2023-earnings-call-transcript/ | [T-edited] | 100% |
| 8 | Tesla Q4 2023 earnings call ("between two waves"; 25% voting control) | 2024-01-24 | Webcast | https://www.fool.com/earnings/call-transcripts/2024/01/24/tesla-tsla-q4-2023-earnings-call-transcript/ | [T-edited] | 100% |
| 9 | Tesla Q1 2024 earnings call | 2024-04-23 | Webcast | https://www.fool.com/earnings/call-transcripts/2024/04/23/tesla-tsla-q1-2024-earnings-call-transcript/ | [T-edited] | 100% |
| 10 | Tesla Q2 2024 earnings call | 2024-07-23 | Webcast | https://www.fool.com/earnings/call-transcripts/2024/07/24/tesla-tsla-q2-2024-earnings-call-transcript/ | [T-edited] | 100% |
| 11 | Tesla Q3 2024 earnings call | 2024-10-23 | Webcast | https://www.fool.com/earnings/call-transcripts/2026/04/22/tesla-tsla-q3-2024-earnings-call-transcript/ (the URL date is Fool's error) | [T-edited] | 100% |
| 12 | Tesla Q4 2024 earnings call | 2025-01-29 | Webcast | https://www.fool.com/earnings/call-transcripts/2025/01/29/tesla-tsla-q4-2024-earnings-call-transcript/ | [T-edited] | 100% |
| 13 | Tesla Q1 2025 earnings call | 2025-04-22 | Webcast | https://www.rev.com/transcripts/tesla-q1-2025-earnings-call (cross-checked against https://vectorshift.ai/research/companies/tesla/earnings/2025-q1) | [T-edited] | 100% |
| 14 | Tesla Q2 2025 earnings call | 2025-07-23 | Webcast | https://www.fool.com/earnings/call-transcripts/2025/07/23/tesla-tsla-q2-2025-earnings-call-transcript/ | [T-edited] | 100% |
| 15 | Tesla Q3 2025 earnings call | 2025-10-22 | Webcast | https://www.fool.com/earnings/call-transcripts/2025/10/22/tesla-tsla-q3-2025-earnings-call-transcript/ | [T-edited] | 100% |
| 16 | Tesla Q4 2025 earnings call | 2026-01-28 | Webcast | https://www.fool.com/earnings/call-transcripts/2026/01/28/tesla-tsla-q4-2025-earnings-call-transcript/ | [T-edited] | 100% |
| 17 | Tesla Q1 2026 earnings call | 2026-04-22 | Webcast | https://evwire.com/p/tesla-tsla-q1-2026-earnings-call-full-transcript | [T-edited] | 100% |
| 18 | Tesla Q2 2026 earnings call | 2026-07-22 | Webcast | https://www.fool.com/earnings/call-transcripts/2026/08/05/tesla-tsla-q2-2026-earnings-call-transcript/ | [T-edited] | 100% |
| 19 | Tesla Battery Day + 2020 annual meeting | 2020-09-22 | Fremont parking lot | https://www.rev.com/transcripts/tesla-2020-battery-day-transcript-september-22 | [T-edited] | 100% |
| 20 | Tesla AI Day 2021 | 2021-08-19 | Palo Alto | https://www.youtube.com/watch?v=j0z4FweCy4M | [T-auto] | 100% (Musk and Q&A read closely; engineer talks skimmed) |
| 21 | Tesla AI Day 2022 | 2022-09-30 | Palo Alto | https://www.youtube.com/watch?v=ODSJsviD_SU | [T-auto] | 100% (same) |
| 22 | Tesla 2023 Investor Day (Master Plan 3) | 2023-03-01 | Giga Texas | https://www.youtube.com/watch?v=Hl1zEzVUV7w | [T-auto] | ~100% (Musk segments and Q&A closely; engineer and finance segments skimmed) |
| 23 | Tesla 2023 Annual Shareholder Meeting | 2023-05-16 | Giga Texas | https://www.youtube.com/watch?v=bZNL_8bUz6A | [T-auto] | 100% |
| 24 | Tesla 2024 Annual Shareholder Meeting | 2024-06-13 | Giga Texas | https://www.youtube.com/watch?v=remZ1KMR_Z4 | [T-auto] | 100% |
| 25 | Tesla 2025 Annual Shareholder Meeting ($1T pay vote) | 2025-11-06 | Giga Texas | https://www.youtube.com/watch?v=VGPlvmMjPtE | [T-auto] | 100% |
| 26 | "Making Humans a Multiplanetary Species" | 2016-09-27 | IAC Guadalajara | https://www.youtube.com/watch?v=H7Uyfqi_TE8 | [T-official] (SpaceX's human captions) | 100% of the talk (the upload has no Q&A) |
| 27 | "Making Life Multiplanetary" | 2017-09-29 | IAC Adelaide | https://www.youtube.com/watch?v=tdUX3ypDVwI | [T-auto] | 100% |
| 28 | Starship Update | 2022-02-10 | Starbase | https://www.youtube.com/watch?v=3N7L8Xhkzqo | [T-auto] | 100% |
| 29 | Musk talk to SpaceX staff, "The Road to Making Life Multiplanetary" | 2024-04 (early April) | Starbase | https://www.youtube.com/watch?v=8HghGdGouRQ (fan upload) | [T-auto] | 100% |
| 30 | Jamie Dimon video interview of Musk for JPMorgan retail clients (IPO marketing; filed as FWP Exhibit B) | 2026-06-04 | JPMorgan HQ (video link) | https://www.sec.gov/Archives/edgar/data/1181412/000162828026041365/eu_interviewtranscript06.htm | [T-official] | 100% |
| 31 | SpaceX final IPO prospectus (424B4) | 2026-06-12 | SEC | https://www.sec.gov/Archives/edgar/data/1181412/000162828026042639/spaceexplorationtechnologi.htm | primary document | about 3% (Musk-related sections only) |
| 32 | SpaceX pricing term sheet (FWP) | 2026-06-11 | SEC | https://www.sec.gov/Archives/edgar/data/1181412/000162828026042466/spaceexplorationtechnologi.htm | primary document | 100% |
| 33 | SpaceX (SPCX) Q2 2026 earnings call, its first as a public company | 2026-08-04 | Webcast, Bastrop TX | https://www.webull.com/news/15387111038133248 (Motley Fool transcript) | [T-edited] | 100% |
| 34 | EVwire, "Tesla unveils the new Roadster…" | 2026-10-16 | EVwire | https://evwire.com/p/tesla-roadster-unveiled-specs-performance-thrust-rocket | [Report] | 100% (has no Musk quotes; used only for the Roadster track record) |

**Not obtained.** YouTube captions were rate-limited (HTTP 429), and no text transcript was found for:
- We, Robot (2024-10-10)
- the Starship update (2019-09-28)
- the Starbase update (2025-05-27)
- the Nasdaq listing-day remarks (2026-06-12)

## H: X/Twitter posting analysis (about 7,600 posts read in archives)

Published in full: [`x-posting-analysis.md`](x-posting-analysis.md).
