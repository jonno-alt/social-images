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
