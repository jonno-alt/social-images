# Research Ready: [DATE]

**Run:** [N] | **Segment:** [Segment description] | **Pipeline:** [N]

## Targets for Gemini

Paste this table into Gemini after the prompt from `gemini-prompt.md`.

| # | Organisation | Acronym | Website | Sector | Pipeline | Contact Name | Contact Title | Email | Email Type | Confidence | Organisation Notes |
|---|-------------|---------|---------|--------|----------|-------------|---------------|-------|-----------|------------|-------------------|
| 1 | Example Org | EO | example.org | Business | 1 | Jane Smith | CEO | jane@example.org | Direct | CONFIRMED | Peak body for example industry. 500+ members across Australia. Navigating digital transformation and workforce challenges. |
| 2 | Another Org | AO | another.org.au | Tourism | 1 | (Generic inbox) | - | info@another.org.au | Generic | FALLBACK | State tourism body. Promotes regional tourism. Works with 200+ operators. |

## Skipped Targets

| Organisation | Reason |
|-------------|--------|
| Already Corp | Already contacted via GMass on 2026-03-10 |
| Duplicate Inc | Domain already in tracker (Run 1, Wave 3) |

## Gmail Check Results

Summary of Gmail searches performed to avoid duplicates:
- Searched: `from:jonno@consultclarity.org to:example.org` - No prior contact
- Searched: `from:jonno@consultclarity.org to:another.org.au` - No prior contact

## After Gemini Generates Emails

1. Create Gmail drafts from Gemini output
2. Update `outreach-tracker.xlsx` (add rows with Status = "Draft created")
3. Update `run-log.md` (append wave entry)
4. Push both files to GitHub
