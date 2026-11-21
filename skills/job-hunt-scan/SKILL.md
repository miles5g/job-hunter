---
name: job-hunt-scan
description: >-
  Use when hunting for new job openings (manually or from a daily routine):
  search many sources, score against the person's rubric, enforce dealbreakers,
  and keep a queue of only top-scoring roles.
---

# Job hunt scan

Search for roles, score them against this person's files, and keep a queue of only the ones that clear the floor. Never apply, never message a recruiter, and never pad the queue to make it look busy.

If `PROFILE.md`, `FILTERS.md`, `RUBRIC.md`, `VOICE.md`, or `TARGETS.md` are missing, stop and run `job-search-intake` first (or ask the person to paste those files).

## Sources

Search widely, using `TARGETS.md` as the map:

- LinkedIn job search
- Career pages of companies they named
- Common application hosts that fit their field (Greenhouse, Ashby, Lever, Workday, and others they use)
- Industry boards or associations they listed

Use the keywords, locations, and exclusions in `TARGETS.md` and `FILTERS.md`. Do not import a company list from some other searcher.

## For each posting

1. Record the official title, company, location text, posting date (first published if you can find it), salary if posted, and the apply URL.
2. Read the posting. Do not score from the title alone.
3. Apply hard filters first. If it fails a dealbreaker, skip it and note why. Do not put it in the queue.
4. Score Fit, Level, Location, Growth, and Joy (1 to 5 each) using `RUBRIC.md`. Write a one-line reason for each dimension when you report the role.
5. Be honest about location. A city-only listing is not a Location 5 unless the posting clearly matches their best-case setup (often explicit remote in an allowed country). Unclear return-to-office is a 3, not a 5.
6. Prefer postings first published in the last 21 days, or whatever window they set. Older roles can be mentioned if they are unusually strong, but do not crowd out fresher ones.
7. If the total is below the floor (default 22), do not add it to the queue. You may mention a near-miss only if they asked for borderline roles.

## Queue rules

- The queue holds only roles at or above the floor that also pass hard filters.
- There is no minimum pending count. A short or empty queue is a valid result.
- Never fill space with below-floor roles.
- Prefer 25 / 25 when you have a choice.
- Sort by total score, high to low, then newer first on ties.
- Give each role a short unique ID. Do not reuse an ID from an applied or closed role.
- Dedup against the current queue and `tracker/applications.csv` (same company + role + location, or the same apply URL).
- If a queued role has closed, disappeared, or failed a later filter check, move it to Closed or removed and say so.
- After every hunt, update the queue file. In this kit, that is a markdown queue based on `tracker/QUEUE_TEMPLATE.md`. If the person also keeps HTML, update both from the same facts.

## What to report

Keep the report short and useful:

- How many postings you reviewed, and how many cleared the floor
- New queue roles, each with ID, title, company, score breakdown, posting age, location, link, and one or two sentences on why it is in
- Roles you removed, and why
- Near-misses only if they are close and the person wants them
- Anything uncertain (location, pay, closed vs open) that they should know before applying

Do not recommend they apply to everything in the queue. The queue is a shortlist, not a to-do list.

## Safety

- Never submit an application.
- Never create accounts or contact employers unless they clearly asked you to draft (not send) a specific note.
- Do not scrape or store private data you should not have. Use public postings and pages.
- If a source is blocked or login-walled, say so and use another public source. Do not ask them to hand over passwords.
