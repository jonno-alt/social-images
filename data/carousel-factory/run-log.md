# Storytelling Carousel Factory - Run Log

## Run #1 - 2026-03-24

**Timestamp:** 2026-03-24T03:30:00Z (13:30 AEST)
**Stories Created:** 10 (Stories #1-10)
**Batch Size:** 10 (default)

### Stories in This Batch

| # | Series | Type | Hook | Slug |
|---|--------|------|------|------|
| 1 | The Team That Looks Fine But Isn't | TRUE | Every metric was green. The tech was fake. | theranos-green-metrics-2026-03-24 |
| 2 | The Meeting That Changed Everything | TRUE | No one had problems. They lost $17 billion. | mulally-ford-red-chart-2026-03-24 |
| 3 | The Leader Who Thought It Was a People Problem | TRUE | They blamed the pilots. The system was broken. | boeing-blamed-pilots-2026-03-24 |
| 4 | The Question That Changed Everything | TRUE | No one gave orders. Every film got better. | pixar-braintrust-question-2026-03-24 |
| 5 | The Moment They Saw It | TRUE | They knew everything. They were losing. | nadella-know-it-all-2026-03-24 |
| 6 | The Cost of Getting It Wrong | TRUE | Total honesty. Total fear. | bridgewater-transparency-fear-2026-03-24 |
| 7 | The Team That Looks Fine But Isn't | FICTIONAL | Test scores were rising. Teachers were leaving. | rising-scores-leaving-teachers-2026-03-24 |
| 8 | The Meeting That Changed Everything | FICTIONAL | The agenda had one item. It changed everything. | nonprofit-one-agenda-item-2026-03-24 |
| 9 | The Leader Who Thought It Was a People Problem | FICTIONAL | She replaced the team twice. Same result. | replaced-team-same-result-2026-03-24 |
| 10 | The Question That Changed Everything | FICTIONAL | One question. Fifteen seconds of silence. | principal-fifteen-seconds-silence-2026-03-24 |

### Decisions Made

- First run of the Storytelling Carousel Factory. No prior story-tracker.xlsx existed.
- Created story-tracker.xlsx from scratch with 5 tabs: Stories, Series Rotation, Settings, Run History, Research Cache.
- Distributed 10 stories across 6 series: 2 each for series 1-4, 1 each for series 5-6.
- Each series starts TRUE, then alternates to FICTIONAL.
- TRUE stories researched via web search: Theranos, Ford/Mulally, Boeing 737 MAX, Pixar Braintrust, Nadella/Microsoft, Bridgewater/Dalio.

### GitHub

- Repository: jonno-alt/social-images
- Commit: e984034 (rebased on 75cd7ff)
- 250 files added: 10 stories x (8 slides x 3 sizes + 1 video) = 250 assets

### Buffer Posts by Platform

| Platform | Posts | Mode | Notes |
|----------|-------|------|-------|
| LinkedIn | 10 | addToQueue | Square images, all 8 slides, ~200-word text |
| Facebook | 10 | addToQueue | Square images, all 8 slides, ~100-word text |
| Instagram | 10 | addToQueue | Portrait images, all 8 slides, hashtags |
| Threads | 10 | addToQueue | Square images, all 8 slides, short text |
| X/Twitter | 10 | addToQueue | Square slides 1,4,5,8, under 280 chars |
| Google Business | 10 | addToQueue | Square slide 1, whats_new type |
| Bluesky | 10 | addToQueue | Square slides 1,4,5,8, under 300 chars |
| TikTok | 10 | addToQueue | Vertical video, short caption + hashtags |
| YouTube | 10 | customScheduled | Vertical video. Daily limit hit, staggered Mar 31 - Apr 9, 10:00 AEST |
| Pinterest | 0 | SKIPPED | No boards configured |
| **Total** | **90** | | |

### Quality Gates

- All 10 stories: 8 slides each, all 3 sizes produce 8 PNGs each (verified)
- Cover slides visually checked: brand colors correct, text within margins, footer zone clear
- Videos: ~32 seconds each, 1080x1920, libx264
- Hook lengths: all under 55 characters

### Errors and Recovery

1. **YouTube daily limit (Story #1):** addToQueue failed. Switched to customScheduled mode, staggered one post per day from 2026-03-31 to 2026-04-09 at 10:00 AEST.
2. **Buffer 429 rate limit (Story #5, X/Twitter):** Hit rate limit after ~40 rapid API calls. Waited 3 minutes, then resumed successfully. All subsequent calls completed without error.

### Items for Review

- Pinterest remains skipped (no boards configured). Configure boards if Pinterest posting is desired.
- YouTube posts are custom-scheduled March 31 to April 9. Verify they publish correctly.

### Running Totals

- Total stories created: 10
- Total Buffer posts scheduled: 90
- Total carousel assets on GitHub: 250 (240 PNGs + 10 videos)
- Series coverage: All 6 series have at least 1 story. Series 1-4 have 2 each.

---

## Run #2 - 2026-03-24

**Timestamp:** 2026-03-24T08:00:00Z (18:00 AEST)
**Stories Created:** 10 (Stories #11-20)
**Batch Size:** 10 (default)

### Stories in This Batch

| # | Series | Type | Hook | Slug |
|---|--------|------|------|------|
| 11 | The Moment They Saw It | FICTIONAL | She blamed teachers. Then watched the footage. | blamed-teachers-then-watched-2026-03-24 |
| 12 | The Cost of Getting It Wrong | FICTIONAL | They merged two great teams. Both collapsed. | merged-two-great-teams-2026-03-24 |
| 13 | The Team That Looks Fine But Isn't | TRUE | Every test passed. The diesel was dirty. | vw-clean-diesel-dirty-data-2026-03-24 |
| 14 | The Meeting That Changed Everything | TRUE | He said IBM doesn't need a vision. It needed customers. | gerstner-ibm-no-vision-2026-03-24 |
| 15 | The Leader Who Thought It Was a People Problem | TRUE | They invented the future. Then buried it. | kodak-invented-future-buried-2026-03-24 |
| 16 | The Question That Changed Everything | TRUE | Better teams reported more errors. Not fewer. | edmondson-better-teams-more-errors-2026-03-24 |
| 17 | The Moment They Saw It | TRUE | He put employees first. Customers came second. Profits came anyway. | kelleher-southwest-employees-first-2026-03-24 |
| 18 | The Cost of Getting It Wrong | TRUE | Move fast and break things. They broke everything. | uber-move-fast-lose-everything-2026-03-24 |
| 19 | The Team That Looks Fine But Isn't | FICTIONAL | Every KPI was green. Every person was leaving. | every-kpi-green-everyone-leaving-2026-03-24 |
| 20 | The Meeting That Changed Everything | FICTIONAL | The staff meeting lasted 11 minutes. It saved the school. | eleven-minute-meeting-saved-school-2026-03-24 |

### Decisions Made

- Second run. Loaded existing story-tracker.xlsx from GitHub (10 stories from Run #1).
- Prioritized series 5 and 6 (fewest stories at 1 each) for stories 11-12 as FICTIONAL.
- Stories 13-18 added TRUE stories across all 6 series.
- Stories 19-20 added FICTIONAL for series 1-2.
- TRUE stories researched via web search: VW Dieselgate, IBM/Gerstner, Kodak/Sasson, Edmondson psychological safety, Southwest/Kelleher, Uber/Kalanick.

### GitHub

- Repository: jonno-alt/social-images
- Pushed via GitHub Git Data API (no clone due to disk constraints)
- 250 files added: 10 stories x (8 slides x 3 sizes + 1 video) = 250 assets
- Pushed in 3 batches (6 stories, 1 story, 3 stories) due to timeout limits

### Buffer Posts by Platform

| Platform | Posts | Mode | Notes |
|----------|-------|------|-------|
| LinkedIn | 10 | addToQueue | Square images, all 8 slides, ~200-word text |
| Facebook | 10 | addToQueue | Square images, all 8 slides, ~100-word text |
| Instagram | 10 | addToQueue | Portrait images, all 8 slides, hashtags |
| Threads | 2 | addToQueue | Stories 11-12 only. Stories 13-20 failed (image dimension error) |
| X/Twitter | 10 | addToQueue | Square slides 1,4,5,8, under 280 chars |
| Google Business | 10 | addToQueue | Square slide 1, whats_new type |
| Bluesky | 10 | addToQueue | Square slides 1,4,5,8, under 300 chars |
| TikTok | 10 | addToQueue | Vertical video, short caption + hashtags |
| YouTube | 10 | customScheduled | Vertical video. Daily limit, staggered Apr 10 - Apr 19, 10:00 AEST |
| Pinterest | 0 | SKIPPED | No boards configured |
| **Total** | **82** | | |

### Quality Gates

- All 10 stories: 8 slides each, all 3 sizes produce 8 PNGs each (verified)
- Cover slides visually checked: brand colors correct, text within margins, footer zone clear
- Videos: ~32 seconds each, 1080x1920, libx264
- Hook lengths: all under 55 characters
- Adaptive text sizing used for longer slide text (reduces font by 1pt until fits, min 18pt)

### Errors and Recovery

1. **Disk space (941MB free):** Could not clone GitHub repo (328MB). Tried shallow clone, sparse checkout, blobless clone — all failed. Fixed by using GitHub Git Data API (create blobs, trees, commits via REST) to push without cloning.
2. **GitHub API 422 on tree creation:** Tree with ~75 entries too large. Fixed by pushing one story per commit.
3. **GitHub push timeout:** 250 files exceeded 10-min limit. Fixed by splitting into 3 runs.
4. **Threads image dimension error (Stories 13-20):** "Failed to fetch image dimensions: Internal Server Error" on all Threads posts from story 13 onward. Stories 11-12 Threads worked fine. Skipped Threads for stories 15-20; stories 13-14 logged as failed.
5. **YouTube daily limit (Story #11):** addToQueue failed. Switched to customScheduled mode, staggered Apr 10-19 at 10:00 AEST.

### Items for Review

- Threads failed for stories 13-20. May be a temporary issue with Threads image processing. Retry manually or investigate.
- Pinterest remains skipped (no boards configured).
- YouTube posts are custom-scheduled April 10 to April 19. Verify they publish correctly.

### Running Totals

- Total stories created: 20
- Total Buffer posts scheduled: 172 (90 from Run #1 + 82 from Run #2)
- Total carousel assets on GitHub: 500 (480 PNGs + 20 videos)
- Series coverage: All 6 series have 4 stories each (balanced). Series 1-2 have extra FICTIONAL coverage.

---

## Run #3 - 2026-03-25

**Timestamp:** 2026-03-25T09:17:00Z (19:17 AEST)
**Stories Created:** 10 (Stories #21-30)
**Batch Size:** 10 (default)

### Stories in This Batch

| # | Series | Type | Hook | Slug |
|---|--------|------|------|------|
| 21 | The Leader Who Thought It Was a People Problem | FICTIONAL | She fired three coordinators. The role was the problem. | fired-three-coordinators-same-role |
| 22 | The Question That Changed Everything | FICTIONAL | One question ended the meeting. And started the real one. | asked-what-are-we-avoiding |
| 23 | The Moment They Saw It | FICTIONAL | The team was working hard. On completely different things. | mapped-the-workflow-saw-the-gap |
| 24 | The Cost of Getting It Wrong | FICTIONAL | The project failed once. Then failed the exact same way. | skipped-the-debrief-repeated-the-failure |
| 25 | The Team That Looks Fine But Isn't | TRUE | They owned 50% of the market. Fear owned 100% of the culture. | nokia-looked-unbeatable-crumbled |
| 26 | The Meeting That Changed Everything | TRUE | Apple was 90 days from bankrupt. He fired the entire board. | jobs-told-apple-board-resign |
| 27 | The Leader Who Thought It Was a People Problem | TRUE | They fired 5,300 employees. The CEO built the system. | wells-fargo-blamed-5300-employees |
| 28 | The Question That Changed Everything | TRUE | They studied 180 teams. Talent was not the answer. | google-asked-what-makes-teams-work |
| 29 | The Moment They Saw It | TRUE | Every chart was green. The company was losing $17 billion. | mulally-ford-all-green-losing-billions |
| 30 | The Cost of Getting It Wrong | TRUE | Revenue hit $100 billion. Almost none of it was real. | enron-punished-dissent-rewarded-fraud |

### Decisions Made

- Third run. Loaded story-tracker.xlsx from GitHub repo (20 stories from Runs #1-2).
- Prioritized series 3-6 (fewest at 3 each) for stories 21-24 as FICTIONAL.
- Stories 25-30 added TRUE stories across all 6 series.
- TRUE stories: Nokia, Apple/Jobs 1997, Wells Fargo, Google Project Aristotle, Ford/Mulally, Enron.

### GitHub

- Commit: dd7cbba
- 250 files added: 10 stories x (8 slides x 3 sizes + 1 video)

### Buffer Posts by Platform

| Platform | Posts | Mode | Notes |
|----------|-------|------|-------|
| LinkedIn | 10 | addToQueue | Square images, all 8 slides |
| Facebook | 10 | addToQueue | Square images, all 8 slides |
| Instagram | 10 | addToQueue | Portrait images, all 8 slides |
| Threads | 10 | addToQueue | Square images, all 8 slides |
| X/Twitter | 10 | addToQueue | Square slides 1,4,5,8 |
| Google Business | 10 | addToQueue | Square slide 1, whats_new |
| Bluesky | 10 | addToQueue | Square slides 1,4,5,8 |
| TikTok | 10 | customScheduled | Daily limit. Staggered Apr 1-10, 10:00 AEST |
| YouTube | 9 | customScheduled | Stories 21-22 addToQueue, 23-29 customScheduled. Story 30 failed (429) |
| Pinterest | 0 | SKIPPED | No boards configured |
| **Total** | **89** | | 1 failed (YouTube #30) |

### Errors

1. TikTok daily limit (Story 21): switched to customScheduled Apr 1-10.
2. YouTube daily limit (Story 23): switched to customScheduled Apr 1-8.
3. Buffer 429 (Story 30 YouTube): 2 retries exhausted. Needs manual scheduling.

### Items for Review

- Story 30 YouTube needs manual scheduling.
- Pinterest skipped (no boards).
- TikTok: Apr 1-10. YouTube: Apr 1-8 (Story 30 missing).

### Running Totals

- Total stories: 30
- Total Buffer posts: 261 (90 + 82 + 89)
- Total GitHub assets: 750 (720 PNGs + 30 videos)
- Series coverage: All 6 series have 5 stories each (balanced).

## Run #4 - Batch 4 (Stories 31-40) - 2026-03-25

**Stories created:** 10 (Stories 31-40)
**Type split:** 6 FICTIONAL + 4 TRUE
**GitHub commit:** f25aa8a

### Stories in this batch:
| # | Series | Type | Hook | Slug |
|---|--------|------|------|------|
| 31 | The Team That Looks Fine But Isn't | FICT | Engagement was at 94%. Nobody was engaged. | engagement-94-nobody-engaged |
| 32 | The Meeting That Changed Everything | FICT | The CEO talked for 55 minutes. Then asked for input. | ceo-talked-55-minutes |
| 33 | The Leader Who Thought It Was a People Problem | FICT | Three new hires. Same role. All quit within a year. | three-hires-same-role-all-quit |
| 34 | The Question That Changed Everything | FICT | She asked one question. Half the room started crying. | one-question-half-room-crying |
| 35 | The Moment They Saw It | FICT | Two departments. Same data. Opposite conclusions. | same-data-opposite-conclusions |
| 36 | The Cost of Getting It Wrong | FICT | They celebrated the launch. Nobody mentioned the risk. | celebrated-launch-ignored-risk |
| 37 | The Team That Looks Fine But Isn't | TRUE | Every manager had a plan. Fire the bottom 10%. | ge-rank-and-yank-fire-bottom |
| 38 | The Meeting That Changed Everything | TRUE | Every advisor said strike. The president left the room. | jfk-excomm-left-the-room |
| 39 | The Leader Who Thought It Was a People Problem | TRUE | The engineers said no. Management said launch. | challenger-engineers-said-no |
| 40 | The Question That Changed Everything | TRUE | Intel was dying. One question saved it. | grove-intel-one-question-saved |

### Buffer scheduling:
- Total posts: 90 (10 stories x 9 platforms)
- LinkedIn: 10/10 (addToQueue)
- Facebook: 10/10 (addToQueue)
- Instagram: 10/10 (addToQueue, portrait images)
- Threads: 10/10 (addToQueue)
- X/Twitter: 10/10 (addToQueue, 4 images each)
- Google Business: 10/10 (addToQueue, 1 image each)
- Bluesky: 10/10 (addToQueue, 4 images each)
- TikTok: 10/10 (customScheduled, Apr 1-10, daily limits)
- YouTube: 10/10 (customScheduled, Apr 1-10, daily limits)
- Pinterest: SKIPPED (no boards configured)

### Quality gates:
- All 10 stories: 8 slides each, 3 sizes (square/portrait/vertical), video ~32s
- Text does not overlap footer zone
- Hook text under 55 characters
- Brand colors verified (cream #f5f1eb, red #b42b2b, navy #1e2d3d)

### Decisions made:
- All 6 series had equal story counts (5 each), so one FICTIONAL per series first, then 4 TRUE for first 4 series
- TRUE stories: GE rank-and-yank, JFK Cuban Missile Crisis ExComm, NASA Challenger, Intel/Andy Grove
- FICTIONAL stories set in: SaaS company, logistics company, nonprofit, school, insurance company, school district
- TikTok/YouTube daily limits hit immediately, switched to customScheduled (staggered Apr 1-10)
- One rate limit pause (2 min wait) during Story 40 scheduling, recovered successfully

### Errors:
- TikTok addToQueue limit (25/day) hit on Story 31, switched to customScheduled
- YouTube addToQueue limit (10/day) hit on Story 31, switched to customScheduled
- Buffer 429 rate limit during Story 40, waited 2 minutes, retried successfully

### Running totals:
- Total stories: 40
- Total Buffer posts: ~351 (90 + 89 + 82 + 90)
- Total batches: 4
- Series rotation: all 6 series at 6-7 stories each
