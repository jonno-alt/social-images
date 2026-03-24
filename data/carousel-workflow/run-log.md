# Carousel Workflow Run Log

## Run: In Their Own Words

- **Run timestamp:** 2026-03-24 ~12:18 AEST
- **Trigger:** Manual
- **Topic/Input:** Testimonials page from consultclarity.org

---

## Carousels Built

| Carousel | Slides | Footer Role |
|----------|--------|-------------|
| In Their Own Words | 10 | Leadership Team Facilitator, Keynote Speaker, Author |

## Slide Breakdown

1. Cover: "In Their Own Words"
2. Kathy Dickson, CEO ASBA, Australia (93.75% satisfaction)
3. Brett Bleakley, Livingstone Christian School, Australia (most effective PD)
4. Emily Hynes, Australia (coach without dominance)
5. Tim Chalmers, Australia (siloed to unified)
6. Trent Raddatz, Australia (never more on team)
7. Edward Amey, United States (best offsite ever)
8. Alexandru Jurje, Romania (wish I had it 30 years ago)
9. Claire Whereat, Australia (support not review)
10. CTA: Ready to Lead With Clarity

---

## Decisions Made

- **Footer role line:** "Leadership Team Facilitator | Keynote Speaker | Author" selected because testimonials span all service lines (general leadership default).
- **Quote selection:** Chose 8 strongest one-liners across all 4 service categories (keynotes, Working Genius, coaching, book) for geographic and service diversity.
- **TikTok posting path:** Path 1 (Buffer direct) since no people to tag.
- **Pinterest:** Skipped. get_channel returned empty boards array. Logged for Jonno to configure boards on Pinterest.
- **Tagging:** Minimal. Testimonial providers are clients, not public figures with widely known social handles. No @tagging applied.

---

## Actions Taken

### Images Created
- Square (1080x1080): 10 slides
- Portrait (1080x1350): 10 slides
- Vertical (1080x1920): 10 slides
- Pinterest pin (1000x1500): 1

### Video Built
- in-their-own-words.mp4: 1080x1920, 40 seconds, 0.4 MB

### GitHub Upload
- Pushed to jonno-alt/social-images, commit 0533ba9
- Folder: carousels/in-their-own-words-2026-03-24/
- 32 files (30 PNGs + 1 pin + 1 MP4)

### Buffer Posts Scheduled (9 of 10 platforms)

| # | Platform | Channel ID | Status | Scheduled |
|---|----------|-----------|--------|-----------|
| 1 | LinkedIn | 69c077acaf47dacb6944e53b | Scheduled | 2026-03-24 16:12 AEST |
| 2 | Facebook | 60370296a73c5c70fa70c977 | Scheduled | 2026-03-25 02:12 AEST |
| 3 | Instagram | 69bb7e247be9f8b1716f91c7 | Scheduled | 2026-03-25 02:12 AEST |
| 4 | Threads | 69bb7ee47be9f8b1716f9388 | Scheduled | 2026-03-25 00:30 AEST |
| 5 | X/Twitter | 69bb7fdc7be9f8b1716f9570 | Scheduled | 2026-03-25 00:30 AEST |
| 6 | Google Business | 69bb7f1d7be9f8b1716f9409 | Scheduled | 2026-03-25 04:02 AEST |
| 7 | TikTok | 69bb7e7b7be9f8b1716f927a | Scheduled | 2026-03-25 00:30 AEST |
| 8 | YouTube | 69bb7eff7be9f8b1716f93c9 | Scheduled | 2026-03-25 00:30 AEST |
| 9 | Bluesky | 69c08393af47dacb694508b8 | Scheduled | 2026-03-24 16:12 AEST |
| 10 | Pinterest | 69c083cdaf47dacb694509ec | SKIPPED | No boards configured |

---

## Handle Research

- No handle research performed. Testimonial providers are clients, not public figures requiring social media tagging.
- handle-database.xlsx not updated this run (no new handles to add).

---

## Errors or Warnings

- Pinterest skipped due to empty boards array from get_channel.

---

## Items Flagged for Jonno's Review

1. **Pinterest boards:** No boards exist on the cgroupglobal Pinterest account. Configure at least one board to enable Pinterest scheduling on future runs.
2. **Slide design review:** First carousel built with this workflow. Please review the cover, quote, and CTA slides for any design tweaks before the next batch.

---

## Native Action Items Pending

- None required for this carousel (no personal profile tagging, no Path 2 TikTok, no listicle LinkedIn).

---

## Excel Files Updated

- carousel-log.xlsx: 1 row added
- content-calendar.xlsx: 1 row added
- handle-database.xlsx: No changes (no handles researched)

---

## Output Files Created

- 30 PNG slides (3 sizes x 10 slides)
- 1 Pinterest pin PNG
- 1 MP4 video (40 seconds)
- Run log (this file)

---

## Run: 2026-03-24 (Scheduled)

- **Trigger:** Scheduled automatic run
- **Result:** No pending blog posts
- **Details:** All 7 rows in content-calendar.xlsx have Carousel Status = "Carousel Created". No rows with status "Not Started" found.
- **Action:** None required. Add new blog post URLs to content-calendar.xlsx with status "Not Started" to queue future carousel builds.
- **Errors:** None

---

## Run: 2026-03-24 (Scheduled)

**Trigger:** Scheduled automated run
**Input:** "Handle the Brilliant Jerk at Work" - https://www.consultclarity.org/post/handle-brilliant-jerk-work
**Source:** Content calendar row 8 (first "Not Started" entry)

### Carousels Built (7 total)
1. **The Brilliant Jerk Problem** - 8 slides (cover + 6 content + CTA)
2. **Recognise the Real Cost** - 8 slides
3. **Diagnose Before You Act** - 8 slides
4. **Intervene With Structure** - 8 slides
5. **Reinforce Culture Through Action** - 8 slides
6. **6 Mistakes Leaders Make With Brilliant Jerks** - 8 slides
7. **Your First 30 Days Action Plan** - 8 slides

### Image Sizes
- Square (1080x1080): LinkedIn, Facebook, X/Twitter, Threads, Google Business, Bluesky
- Portrait (1080x1350): Instagram
- Vertical (1080x1920): Video source, TikTok backup
- Pinterest pin (1000x1500): Generated for each carousel

### Videos
- 7 vertical MP4 videos (1080x1920, 4s per slide, h264 CRF 23, 30fps)
- Concat demuxer approach, cream letterboxing

### GitHub Upload
- Repository: jonno-alt/social-images
- 182 files uploaded (178 first pass + 4 retried successfully)
- Folders: carousels/[name]-2026-03-24/{square,portrait,vertical}/

### Scheduling Results
**Platforms scheduled (56 posts total across 7 carousels):**
- LinkedIn: 7/7 scheduled (automatic, addToQueue)
- Facebook: 7/7 scheduled
- Instagram: 7/7 scheduled (portrait images, photo tags on slide 1)
- Threads: 7/7 scheduled (with topic tag "leadership")
- X/Twitter: 7/7 scheduled (under 280 chars)
- Google Business: 7/7 scheduled (whats_new with learn_more button)
- TikTok: 7/7 scheduled (video, under 150 chars)
- Bluesky: 7/7 scheduled (with link attachment)

**Platforms NOT scheduled:**
- YouTube: Hit daily limit (10 posts/day). All 7 videos need manual scheduling.
- Pinterest: No boards configured. All 7 pins need board setup first.

### Footer Role Used
Leadership Team Facilitator | Keynote Speaker | Author (default, topic is general leadership/team dynamics)

### Decisions Made
1. Blog sections mapped to 7 carousels covering all major themes
2. Used default footer role (topic covers general leadership, not specifically schools/Working Genius/coaching)
3. Step numbers used on carousels 2-6 where tips are numbered
4. Instagram photo tags: @simonsinek, @adamgrant, @patricklencioniofficial, @bylizwiseman, @kimmalonescott (verified public accounts)
5. X/Twitter kept under 280 chars with no @mentions in text (documented for native tagging)
6. TikTok kept under 150 chars

### Handle Research Summary
- 13 people researched: Robert Sutton, Kim Scott, Amy Edmondson, Simon Sinek, Reed Hastings, Patrick Lencioni, Liz Wiseman, Tessa West, Adam Grant, Dave Bailey, Kathryn Landis, Tim Duggan, Achim Nowak
- All added to handle-database.xlsx with verified handles
- Most active on LinkedIn and X/Twitter
- Limited Bluesky/Threads presence across group

### Native Action Items Pending

**LinkedIn (all 7 posts):**
- Add @mentions natively if not 1st-degree connections: Robert Sutton, Kim Scott, Amy Edmondson, Simon Sinek, Patrick Lencioni, Liz Wiseman, Tessa West, Adam Grant

**Facebook (all 7 posts):**
- Add personal profile tags natively (Buffer only supports Page tags)

**X/Twitter (all 7 posts):**
- Add photo tags natively (up to 10): @simonsinek, @AdamMGrant, @AmyCEdmondson, @kimballscott, @LizWiseman, @patricklencioni, @TessaWestNYU, @work_matters, @davesuperman, @AchimNowak

**Instagram (all 7 posts):**
- Verify all photo tags applied correctly after posting

**TikTok (all 7 posts):**
- Standard posts (under 150 chars). No native caption needed.

**YouTube (all 7 videos - NOT SCHEDULED):**
- Schedule manually via YouTube Studio or Buffer when daily limit resets
- Video URLs in GitHub: carousels/[name]-2026-03-24/[name]-video.mp4
- Add @channel mentions in YouTube Studio

**Pinterest (all 7 pins - NOT SCHEDULED):**
- Create a board first (e.g., "Leadership Tips")
- Then schedule pins with pin.png images from each carousel folder

### Excel Files Updated
- content-calendar.xlsx: Row "Handle the Brilliant Jerk at Work" marked as "Carousel Created"
- carousel-log.xlsx: 7 new rows added
- handle-database.xlsx: 13 new handle entries added

### Errors/Warnings
- Disk space limited (91% used). Could not git clone. Used Contents API for uploads instead.
- YouTube daily post limit reached (10/day). 7 videos need manual scheduling.
- Pinterest has no boards configured. 7 pins saved but not scheduled.
- 4 GitHub uploads failed on first attempt but all succeeded on retry.
