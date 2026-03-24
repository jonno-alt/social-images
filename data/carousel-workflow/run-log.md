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

---

## Run: 2026-03-24T17:30:00+10:00

**Trigger:** Scheduled automatic run
**Input:** "Signs You're Avoiding a Difficult Conversation" - https://www.consultclarity.org/post/signs-avoiding-difficult-conversation
**Content Calendar Row:** 10

### Carousels Built

| Carousel | Slides | Folder |
|----------|--------|--------|
| avoiding-conversations-internal-battle | 8 | avoiding-conversations-internal-battle-2026-03-24 |
| avoiding-conversations-management-workaround | 8 | avoiding-conversations-management-workaround-2026-03-24 |
| avoiding-conversations-escalation-pattern | 8 | avoiding-conversations-escalation-pattern-2026-03-24 |
| avoiding-conversations-breaking-point | 8 | avoiding-conversations-breaking-point-2026-03-24 |

**Total slides:** 32 (8 per carousel x 4 carousels)
**Sizes:** Square (1080x1080), Portrait (1080x1350), Vertical (1080x1920)
**Videos:** 4 MP4 files (1080x1920, 4s per slide, h264 CRF 23)
**Pinterest pins:** 4 (1000x1500)
**Footer role:** Leadership Team Facilitator | Keynote Speaker | Author

### Decisions Made

- Blog post split into 4 carousels by theme: Internal Battle (signs 1-3), Management Workaround (signs 4-6), Escalation Pattern (signs 7-10), Breaking Point (signs 11-13)
- Footer role set to default (difficult conversations topic, no specific keyword match for school/Working Genius/offsite/etc.)
- Instagram photo tags applied to cover slide of each carousel: @brenebrown, @simonsinek, @patricklencioniofficial, @kimmalonescott, @adamgrant
- Pinterest skipped because channel has no boards configured
- YouTube skipped because daily post limit (10) already reached from previous runs
- Bluesky carousel 4 first attempt failed (image dimension fetch error), retried with 2 images successfully

### Platforms Scheduled

| Platform | Carousels 1-4 | Notes |
|----------|--------------|-------|
| LinkedIn | 4/4 | Square images, 200-400 word posts, no hashtags |
| Facebook | 4/4 | Square images, short captions |
| Instagram | 4/4 | Portrait images, photo tags + caption mentions, 5 hashtags |
| Threads | 4/4 | Square images, 1 topic tag (#leadership) |
| X/Twitter | 4/4 | 4 square images max, @BreneBrown mention on C1 |
| Google Business | 4/4 | 1 square image, learn_more button |
| TikTok | 4/4 | Video, short captions with hashtags |
| YouTube | 0/4 | BLOCKED: Daily limit reached (10 posts/day) |
| Bluesky | 4/4 | 4 square images max, link attachment |
| Pinterest | 0/4 | SKIPPED: No boards configured |

### Handle Research

- Added Brene Brown (LinkedIn, X, Instagram, TikTok, Facebook confirmed)
- Added Chartered Management Institute (X: @cmi_managers, Facebook confirmed)
- Added Gallup (LinkedIn, X, Facebook confirmed)
- Existing handles reused: Simon Sinek, Patrick Lencioni, Kim Scott, Adam Grant (all verified within 90 days)

### Errors and Warnings

- YouTube: Daily post limit (10) reached. All 4 YouTube videos need manual scheduling or will be queued on next available day.
- Pinterest: No boards configured on channel. Cannot schedule pins.
- Bluesky C4: First attempt failed with "Failed to fetch image dimensions: Internal Server Error". Retried with 2 images instead of 4, succeeded.
- GitHub clone failed due to disk space (repo 336MB, only 940MB available). Used Contents API for all uploads instead.

### Native Action Items for Jonno

1. **LinkedIn (all 4 posts):** Add personal profile tags natively if desired (Brene Brown, Simon Sinek, Patrick Lencioni, Kim Scott, Adam Grant). Buffer only supports 1st-degree connections.
2. **Facebook (all 4 posts):** Add personal profile tags natively (cannot tag personal profiles via API, only pages).
3. **X/Twitter (all 4 posts):** Add up to 10 photo tags natively (Buffer cannot add photo tags via API).
4. **TikTok (all 4 posts):** Consider replacing Buffer short captions with full native captions:
   - C1: "57% of people would do anything to avoid a difficult conversation. Here are 3 signs the battle is all in your head. Stop rehearsing. Start scheduling. Email jonno@consultclarity.org for my book Step Up or Step Out. #leadership #difficultconversations #management #leadershipdevelopment #teamculture"
   - C2: "Over 80% of workers hold back from challenging conversations. Are you managing around the problem? These 3 signs say yes. Email jonno@consultclarity.org for a proven framework. #leadership #management #teambuilding #difficultconversations #accountability"
   - C3: "Hope is not a management strategy. 4 signs the cost of avoidance is compounding. The conversation you dread is the one your team is waiting for. jonno@consultclarity.org #leadership #difficultconversations #accountability #teamculture #management"
   - C4: "People do not leave because of the difficult person. They leave because leadership would not address them. Have the conversation this week. jonno@consultclarity.org #leadership #teamculture #management #difficultconversations #leadershipdevelopment"
5. **YouTube (all 4 videos):** Schedule manually. Videos uploaded to GitHub:
   - C1: https://raw.githubusercontent.com/jonno-alt/social-images/main/carousels/avoiding-conversations-internal-battle-2026-03-24/avoiding-conversations-internal-battle-video.mp4
   - C2: https://raw.githubusercontent.com/jonno-alt/social-images/main/carousels/avoiding-conversations-management-workaround-2026-03-24/avoiding-conversations-management-workaround-video.mp4
   - C3: https://raw.githubusercontent.com/jonno-alt/social-images/main/carousels/avoiding-conversations-escalation-pattern-2026-03-24/avoiding-conversations-escalation-pattern-video.mp4
   - C4: https://raw.githubusercontent.com/jonno-alt/social-images/main/carousels/avoiding-conversations-breaking-point-2026-03-24/avoiding-conversations-breaking-point-video.mp4
6. **Pinterest:** Configure boards on Pinterest channel in Buffer, then schedule pins manually. Pin images uploaded to GitHub.
7. **Instagram (all 4 posts):** Verify photo tags applied correctly after posting.

### Excel Files Updated

- handle-database.xlsx: Added Brene Brown, Chartered Management Institute, Gallup
- content-calendar.xlsx: Marked "Signs You're Avoiding a Difficult Conversation" as "Carousel Created"
- carousel-log.xlsx: Added 4 new carousel entries

### Output Files

- 96 carousel slide PNGs (32 slides x 3 sizes)
- 4 Pinterest pin PNGs
- 4 MP4 videos
- All uploaded to GitHub: https://github.com/jonno-alt/social-images/tree/main/carousels/

---

## Run: 2026-03-24 ~18:30 AEST

**Trigger:** Scheduled automated run
**Blog Post:** Why Good Teachers Leave Schools
**URL:** https://www.consultclarity.org/post/why-good-teachers-leave-schools

### Carousels Built (7)
1. teachers-daily-energy-drain (7 slides) - Reasons 1-5: reactive mode, pastoral overload, task switching, role mismatch, competence trap
2. teachers-leadership-behaviours (7 slides) - Reasons 6-10: inconsistent backing, micromanagement, change saturation, negative feedback, niceness vs care
3. teachers-loss-of-autonomy (7 slides) - Reasons 11-15: low voice, erosion of autonomy, moral injury, no career paths, shifting goalposts
4. teachers-systemic-failures (7 slides) - Reasons 16-20: admin overload, meeting bloat, timetable design, data demands, learner complexity
5. teachers-breaking-points (7 slides) - Reasons 21-25: underperformance, toxic positivity, always-on, parent conflict, life-stage mismatch
6. teachers-5-mistakes-principals (7 slides) - 5 common principal misconceptions about retention
7. teachers-what-principals-can-do (7 slides) - 5 practical actions for this term

### Image Sizes
- Square: 1080x1080 (LinkedIn, Facebook, X/Twitter, Threads, Google Business, Bluesky)
- Portrait: 1080x1350 (Instagram)
- Vertical: 1080x1920 (TikTok video source)
- Pinterest pin: 1000x1500

### Videos
- 7 vertical MP4s (1080x1920, 4s/slide, concat demuxer, h264 CRF 23)

### Footer Role
- "Certified Working Genius Facilitator | Author | Keynote Speaker" (school topic)

### Decisions Made
- 7 carousels covering all 25 reasons plus mistakes and practical guide sections
- Topic keyword "school" matched footer role to "Certified Working Genius Facilitator | Author"
- Grouped 25 reasons into 5 groups of 5, matching the blog's section structure
- Added 2 additional carousels for "mistakes" and "practical guide" sections
- 7 slides per carousel: 1 cover + 5 content + 1 CTA

### Platforms Scheduled
- LinkedIn: 7 posts scheduled (automatic, addToQueue)
- Facebook: 7 posts scheduled
- Instagram: 7 posts scheduled (portrait images, photo tags + caption mentions)
- Threads: 7 posts scheduled
- X/Twitter: 7 posts scheduled (max 4 images per post)
- Google Business: 7 posts scheduled (1 image, whats_new with learn_more button)
- TikTok: 7 posts scheduled (video)
- Bluesky: 7 posts scheduled (max 4 images, link attachment)

### Platforms NOT Scheduled
- YouTube: Hit daily limit (10 posts max). All 7 videos need manual upload.
- Pinterest: No boards configured. Skipped. Pin images uploaded to GitHub.

### Handle Research Summary
- 17 new handles added to handle-database.xlsx
- New individuals: Richard Ingersoll, Linda Darling-Hammond, Andy Hargreaves, Michael Fullan, Viviane Robinson, Elena Aguilar, Todd Whitaker, Chase Mielke, Jack Worth, David Rock
- New organizations: RAND Corporation, Learning Policy Institute, OECD Education, ASCD, WeAreTeachers, NFER, McKell Institute
- Existing handles reused: Patrick Lencioni, Adam Grant, Brene Brown, Simon Sinek, Gallup

### GitHub Upload
- All carousel images and videos uploaded via Contents API
- 1 file failed (teachers-loss-of-autonomy/square/slide_06.png) due to rate limiting - needs manual retry
- Data files pushed via Contents API

### Errors and Warnings
- YouTube daily limit reached (10 posts max per day from previous runs)
- Pinterest no boards configured (same as previous runs)
- GitHub rate limiting caused 1 image upload failure
- X/Twitter first attempt for Carousel 1 exceeded 280 chars, fixed on retry

### Native Action Items Pending
- YouTube: Upload all 7 videos manually via YouTube Studio
- Facebook: Add personal profile tags natively (API only supports Page tags)
- X/Twitter: Add photo tags natively for all 7 posts (10 tags each)
- Instagram: Verify photo tags applied correctly for all 7 posts
- Pinterest: Configure boards, then schedule pins manually
- GitHub: Retry upload of teachers-loss-of-autonomy/square/slide_06.png

### Excel Files Updated
- handle-database.xlsx: 17 new entries added, all marked ACTIVE
- content-calendar.xlsx: "Why Good Teachers Leave Schools" marked as "Carousel Created"
- carousel-log.xlsx: 7 new rows added

### Output Files
- 7 carousel folders in GitHub: carousels/{name}-2026-03-24/
- Each folder: square/, portrait/, vertical/ subdirs + pin.png + video.mp4

## Run: 2026-03-24 (Scheduled)

**Trigger:** Scheduled automated run
**Input:** New Leader Identity Grief - https://www.consultclarity.org/post/new-leader-identity-grief
**Topic Keywords:** new leader, identity, grief, transition
**Footer Role:** Leadership Team Facilitator | Keynote Speaker | Author

### Carousels Built (7)
1. identity-grief-friendship-shift (6 slides) - Signs 1-3: The Friendship Shift
2. identity-grief-expert-identity-loss (6 slides) - Signs 4-6: The Expert Identity Loss
3. identity-grief-imposter-crisis (6 slides) - Signs 7-9: The Imposter Crisis
4. identity-grief-loneliness (6 slides) - Signs 10-12: The Loneliness Nobody Warned You About
5. identity-grief-identity-vacuum (6 slides) - Signs 13-15: The Identity Vacuum
6. identity-grief-emotional-tax (6 slides) - Signs 16-18: The Emotional Tax
7. identity-grief-rebuilding (7 slides) - Signs 19-23: Rebuilding Your Leadership Identity

### Image Sizes
- Square: 1080x1080 (LinkedIn, Facebook, X/Twitter, Threads, Google Business, Bluesky)
- Portrait: 1080x1350 (Instagram)
- Vertical: 1080x1920 (Video source, TikTok backup)
- Pinterest Pin: 1000x1500

### Videos Built (7)
All 7 carousels converted to 1080x1920 vertical MP4 (4 sec/slide, h264, CRF 23, 30fps)

### GitHub Upload
All images and videos uploaded to jonno-alt/social-images via Contents API.
Folders: carousels/identity-grief-*-2026-03-24/

### Handle Research
Added 16 new entries to handle-database.xlsx:
Herminia Ibarra, Liz Fosslien, Julie Zhuo, Michael Bungay Stanier, Marshall Goldsmith,
Linda A. Hill, Ram Charan, Ronald Heifetz, Justin Bariso, Sara Canaday, Rachel Pacheco,
Tessa Brock, Glenn Birkelev, RHR International, KPMG, Wharton Executive Education

### Scheduling Results
- LinkedIn: 7/7 scheduled (automatic, addToQueue)
- Facebook: 7/7 scheduled (automatic, addToQueue)
- Instagram: 7/7 scheduled (portrait images, automatic, addToQueue)
- Threads: 7/7 scheduled (square images, automatic, addToQueue)
- X/Twitter: 7/7 scheduled (max 4 square images, automatic, addToQueue)
- Google Business: 7/7 scheduled (1 image + learn_more CTA, automatic, addToQueue)
- TikTok: 4/7 scheduled (video only). Parts 5-7 hit daily limit (25 posts/day).
- YouTube: 0/7 scheduled. Hit daily limit (10 posts/day).
- Bluesky: 7/7 scheduled (max 4 square images + link attachment, automatic, addToQueue)
- Pinterest: 0/7. No boards configured on the Pinterest channel.

**Total: 53 posts scheduled across 8 platforms**

### Native Action Items Pending
1. **TikTok**: Schedule parts 5-7 manually when daily limit resets
   - Part 5: "Who am I now?" The identity vacuum of leadership #LeadershipIdentity #LeadershipGrief #NewManager #Leadership
   - Part 6: The emotional tax nobody puts in the job description #EmotionalIntelligence #LeadershipGrief #NewManager #Burnout
   - Part 7: 5 signs you're rebuilding your leadership identity #LeadershipGrowth #LeadershipGrief #NewManager #Leadership
   - Videos at: carousels/identity-grief-identity-vacuum-2026-03-24/, carousels/identity-grief-emotional-tax-2026-03-24/, carousels/identity-grief-rebuilding-2026-03-24/

2. **YouTube**: Schedule all 7 videos when daily limit resets
   - Use vertical videos from each carousel folder
   - Category: 27 (Education), Privacy: public
   - Titles: "[Section Name]: New Leader Identity Grief (Part N/7)"

3. **Pinterest**: Configure boards on Pinterest channel, then schedule pin
   - Pin image at: carousels/new-leader-identity-grief-2026-03-24/pin.png

4. **LinkedIn**: Add photo tags natively if 10+ people tagged (standard text @mentions used)

5. **X/Twitter**: Add photo tags natively (up to 10 per post)

6. **Instagram**: Verify all photo tags applied correctly after Buffer publishes

### Decisions Made
- Used default footer role "Leadership Team Facilitator | Keynote Speaker | Author" (no specific keyword match)
- Split blog into 7 carousels matching the 7 section categories
- Signs 19-23 (Rebuilding) grouped into one larger carousel (7 slides) since it's the resolution section
- Used under 150 chars for TikTok captions (Path 1 standard)
- Skipped Pinterest (no boards configured)
- Limited X/Twitter to 4 images per post per platform rules

### Errors/Warnings
- TikTok: Daily limit reached after 4 posts (parts 5-7 need manual scheduling)
- YouTube: Daily limit reached (0 posts scheduled, all 7 need manual scheduling)
- Pinterest: No boards configured on channel (pin image created but not scheduled)
- GitHub upload: One transient connection error on emotional-tax slide_03 (retried successfully)

### Excel Files Updated
- content-calendar.xlsx: Marked "New Leader Identity Grief" as "Carousel Created"
- handle-database.xlsx: Added 16 new handles
- carousel-log.xlsx: Added 7 new carousel entries

### Output Files
- 7 carousel folders with square/portrait/vertical PNGs + MP4 video each
- 1 Pinterest pin (1000x1500)
- All hosted on GitHub at jonno-alt/social-images
