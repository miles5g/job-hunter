---
name: job-hunt-scan
description: >-
  Use when hunting for new job openings (when asked or from a morning
  routine): search many sources, score against the person's files, enforce
  dealbreakers, and keep a shortlist (queue) of only jobs at or above their
  minimum score.
---

# Job hunt scan

Search for jobs, score them against this person's files, and keep a shortlist (queue) of only the ones that reach their minimum score. Never apply, never message a recruiter, and never pad the queue to make it look busy. Many people using this are not technical. Report in plain words.

If `PROFILE.md`, `FILTERS.md`, `RUBRIC.md`, `VOICE.md`, or `TARGETS.md` are missing, stop and run `job-search-intake` first (or ask the person to paste their "My Job Hunter profile" doc).

## Sources

Search widely, using `TARGETS.md` as the map. Pick the sources that fit their field:

- Indeed and LinkedIn job search
- Career pages of companies they named, and big employers in their field and area (for example hospitals and health systems, school districts, universities, city, county, and state governments, retailers, nonprofits)
- Government job sites (USAJOBS, state and local job boards)
- Industry job boards and associations for their field
- Company application pages (Workday, Greenhouse, Lever, iCIMS, Ashby, and others)

Use the keywords, locations, and exclusions in `TARGETS.md` and `FILTERS.md`. Do not import a company list from some other searcher.

Only report postings you actually opened. Never invent a job, a link, or a date. If a source is blocked or needs a login, say so and use another public source.

## For each posting

1. Record the official title, employer, location text, posting date (first published if you can find it), pay if posted, and the apply link.
2. Read the posting. Do not score from the title alone.
3. Apply hard filters first. If it fails a dealbreaker, skip it and note why. Do not put it in the queue.
4. Score Fit, Level, Location, Growth, and Joy (1 to 5 each) using `RUBRIC.md`. Write a one-line reason for each when you report the job.
5. Be honest about location. A city-only listing is not a Location 5 unless the posting clearly matches their best-case setup. Unclear return-to-office is a 3, not a 5.
6. Prefer postings first published in the last 21 days, or whatever window they set. Older jobs can be mentioned if they are unusually strong, but do not crowd out fresher ones.
7. If the total is below their minimum score (from `RUBRIC.md`; 22 if none was set), do not add it to the queue. Mention a near-miss only if they asked for close calls.

## Queue rules

- The queue holds only jobs at or above the minimum score that also pass hard filters.
- There is no minimum number of jobs. A short or empty queue is a valid result.
- Never fill space with jobs below the minimum score.
- Prefer higher scores when you have a choice.
- Sort by total score, high to low, then newer first on ties.
- Give each job a short unique ID. Do not reuse an ID from an applied or closed job.
- Dedup against the current queue and their application log (same employer + job + location, or the same apply link).
- If a queued job has closed, disappeared, or failed a later filter check, move it to Closed or removed and say so.
- After every hunt, update the queue. In this kit, that is a queue based on `tracker/QUEUE_TEMPLATE.md`. In a plain chat, give them the full updated table to paste into their Google Doc or Google Sheet.

## What to report

Keep the report short and useful:

- How many postings you reviewed, and how many made the shortlist
- New queue jobs, each with ID, title, employer, score breakdown, posting age, location, link, and one or two sentences on why it is in
- Jobs you removed, and why
- Near-misses only if they are close and the person wants them
- Anything uncertain (location, pay, closed or open) that they should know before applying
- An offer to prep packets for the top 3 new jobs, or whichever ones they pick

Do not recommend they apply to everything in the queue. The queue is a shortlist, not a to-do list.

## Safety

- Never submit an application.
- Never create accounts or contact employers unless they clearly asked you to draft (not send) a specific note.
- Do not scrape or store private data you should not have. Use public postings and pages.
- If a source is blocked or login-walled, say so and use another public source. Do not ask them to hand over passwords.
