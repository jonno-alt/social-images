# ASSOCIATION OUTREACH SESSION PROMPT
## Copy and paste this into Claude Desktop / Cowork

---

You are running an automated association outreach session for Jonno White, a leadership consultant and keynote speaker based in Brisbane, Australia.

## YOUR TASK THIS SESSION

**Category:** [INSERT CATEGORY e.g., "nursing specialty associations" or "engineering associations" or "HR associations"]
**Countries:** Australia, New Zealand, USA, UK, Canada, Singapore
**Scope:** national, state, and city-level
**Target:** Create up to 50 personalised Gmail draft emails to associations with VERIFIED contact emails

## PROCESS

1. **First**, clone the tracking repo and check what's already been done:
```bash
cd /home/claude
git clone https://{YOUR_GITHUB_PAT}@github.com/jonno-alt/social-images.git outreach-tracking 2>/dev/null || (cd outreach-tracking && git pull)
cat outreach-tracking/outreach/[category-slug]/tracking.json 2>/dev/null || echo "Starting fresh"
```

2. **Then**, systematically research associations in the category. For each one:
   - Search for the official website
   - Find the contact email on their OFFICIAL contact page, footer, Facebook page, government directory, or official PDF
   - ONLY use emails verified from official sources (never from data brokers alone)
   - If no email can be found, log it as "no_email_found" and move on

3. **Create Gmail drafts** for each verified email using this template:

**Subject:** Quick question for the {Full Association Name}

**Body (if going to a named person):**
Hi {First Name},

I realise this may come out of the blue, so I appreciate you taking the time to read this!

{2-3 personalised sentences about their members and challenges}

**Body (if going to a general email):**
Hi {Abbreviation} team,

I realise this will likely land with your admin team first, so thank you to whoever is reading this!

{2-3 personalised sentences about their members and challenges}

**Then the standard body:**
My name is Jonno White. I am a leadership consultant and keynote speaker who works with associations and {sector} organisations around the world. I recently delivered a keynote at the SRCA Queensland conference called "Speak Up, Stand Together: Communication That Builds a Championship Culture," focused on building high-performing cultures through courageous, respectful communication. I also delivered a bespoke keynote at the Institute of Healthcare Engineering Australia (IHEA) National Conference on the Gold Coast to 150+ delegates, where the feedback was fantastic, particularly around the mental health angle and the idea that looking after yourself and those around you is just as important as technical ability.

I am now offering three sessions specifically designed for {sector} audiences:

1. Speak Up, Stand Together: Communication That Builds a Championship Culture. A keynote on building a high-performing culture through courageous, respectful communication. It empowers frontline staff to replace unspoken barriers with clarity, connection, and shared accountability, with practical tools for psychological safety, feedback, and cultural ownership at every level.

2. The Human Side of AI in {Sector}: How to Lead Your Team Through the Greatest Disruption to the Sector in a Generation. Not about the technology. It is about how {sector} leaders can guide their teams through the disruption, keep people engaged, and build cultures that thrive through change rather than just surviving it.

3. Working Genius Team Workshop. The fastest growing team assessment in the world, developed by Patrick Lencioni and The Table Group. A highly interactive session that helps {sector} teams understand their natural gifts and frustrations so they can work together more effectively, reduce burnout, and actually enjoy the work again.

I am the bestselling author of Step Up or Step Out (10,000+ copies sold globally), a Certified Working Genius Facilitator, and I host The Leadership Conversations Podcast with 230+ episodes reaching listeners in 150+ countries. I am represented by most of the leading speaker bureaus in Australia and New Zealand, including Celebrity Speakers Australia, Keynote Entertainment, ICMI, EntertainOz, Speakers Solutions, EventSpeakers, Great Expectation Speakers and Trainers, Inspire Speakers, and Claxton Speakers.

Would any of these be a fit for {their conference if known, or "your annual conference"}, a {chapter/branch} event, or a professional development session for your members? I can deliver face to face or virtually.

More than happy to send through more information or to answer any questions.

Cheers!
Jonno

Jonno White
Co-Founder, Clarity Group Global
jonno@consultclarity.org
0481 829 906

4. **After creating all drafts**, update the tracking file and push to GitHub:
```bash
cd /home/claude/outreach-tracking
mkdir -p outreach/[category-slug]
# Write updated tracking.json
git add -A
git commit -m "Outreach: [category] - [date] - [N] drafts"
git push
```

5. **Report** a summary of what was done, what was drafted, and what's left to research.

## RULES
- Never use em dashes. Use commas, periods, or rewrite the sentence.
- Never fabricate claims about Jonno.
- For AU/NZ associations, mention "I am based in Australia so face to face is easy"
- Adapt session descriptions for the sector (e.g., "AI in Engineering" not "AI in Nursing" for engineering associations)
- VERIFY every email before drafting. If you can't verify it, don't draft it.
- Log everything, including associations where no email was found.

## GO
Start researching and drafting now. Work through systematically by country, starting with Australia and New Zealand, then USA, then UK, Canada, and Singapore. Create as many drafts as possible up to 50.
