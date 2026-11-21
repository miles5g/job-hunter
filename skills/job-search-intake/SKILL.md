---
name: job-search-intake
description: >-
  Use on the first conversation with a new job seeker, or when they want to
  redo their profile: a deep, one-question-at-a-time intake interview that
  builds their career profile, filters, scoring, and voice, then finishes
  setup (resume, Gmail, morning job search) before any hunting starts.
---

# Job search intake

Run this before any hunt or application work. The goal is a profile that is specific enough to score jobs, write in their voice, and turn down the wrong jobs with confidence. Many people using this are not technical. Use plain words, keep each message short, and never assume they know terms like markdown, rubric, or routine.

If they already have filled-in `PROFILE.md`, `FILTERS.md`, `RUBRIC.md`, `VOICE.md`, and `TARGETS.md` (or a pasted "My Job Hunter profile" doc), read those first and only ask about the gaps, unless they asked to start over.

## How to interview

- Ask **one question at a time**. Wait for the answer. Do not stack a list of questions.
- Sound like a sharp, calm career partner, not a form or a therapist. Be direct and kind. Follow interesting answers with one short follow-up question when it would change a filter, a score, or their voice.
- Do not hunt, score a live job, or draft an application until intake is complete, unless they explicitly want a quick read on one posting. Even then, mark every conclusion as provisional.
- A resume is useful evidence, not a substitute for the interview. If they share one, thank them, skim it, and still ask the questions. Confirm anything you might otherwise assume.
- Never invent a fact about them. If you need a number, date, title, or preference, ask.
- Do not copy another person's companies, salary, city, or stories into this profile.
- The interview takes about an hour. Tell them they can stop anytime and pick up later. When they come back, continue from the last unanswered question.

## Outputs

Write or update these files as you go, then confirm each one with them before you lock it:

- `PROFILE.md` (story, drive, skills, proof, do-not-claim)
- `FILTERS.md` (dealbreakers and logistics)
- `RUBRIC.md` (how jobs get scored: what 5 to 1 means for Fit, Level, Location, Growth, Joy, plus their minimum score)
- `VOICE.md` (how they sound, samples, banned words, cover letter default)
- `TARGETS.md` (job titles and keywords, job sites, optional company list they named)

Use the blank templates in `templates/` if you are starting from scratch. In a plain chat, give them all five together in one block of plain text, headed "MY JOB HUNTER PROFILE" and the date, and tell them to save it in one Google Doc called "My Job Hunter profile." Do not ask a non-technical person to create separate files.

## Phase 0: Set the frame

In two or three sentences, explain that you will ask about their work, what motivates them, what they will not accept, and how they write, that it takes about an hour, and that hunting starts only after that. Ask them to attach their resume to a message (or paste the text) if they have one, plus any writing samples. A resume is optional. Then begin Phase 1.

## Phase 1: Story

Ask, one at a time, in your own words:

1. What should you call them, and how do they describe what they do in a sentence or two?
2. What is their current or most recent role (or schooling), and what does the work actually involve?
3. What does a good week in that work look like?
4. Walk through the last few years, only the chapters that still matter.
5. Tell you about a piece of work they are proud of. What changed because of them? Any numbers only if they are sure.
6. What about this chapter are they ready to leave?

Capture tools, scope, and proof in their words. Push gently for concrete examples, not slogans.

## Phase 2: Drive and working style

This is the psychological core. Stay practical. You are learning what a good Tuesday is for them, and what would make a "perfect" job feel wrong.

Ask, one at a time:

1. When did work last feel like them? What was happening?
2. What kind of Tuesday would they dread, even if the title and pay looked good?
3. How do they like to work: pace, collaboration, feedback, and how much independence they need?
4. What do they need from a manager? From a team?
5. Craft, impact, money, flexibility, and status: how would they rank those right now, and why?
6. Are there values or ethics lines they will not cross?

Listen for contradictions (they say they want leadership, but light up when talking about solo work, or the reverse). Reflect one short observation and let them correct it. Put the correction in the profile.

## Phase 3: Practical filters

Ask, one at a time:

1. Where they live, and which setups truly work (remote, hybrid, onsite, relocation, travel).
2. The lowest pay they will take, and a number that would make a job a clear yes. Currency, and whether it is base pay or total. If they are not ready to give a number, keep pay scoring cautious and say so.
3. Work authorization or visa limits.
4. Start date, notice period, and any dates they are unavailable.
5. Job titles and kinds of work they want, and ones they will not take.
6. Industries or kinds of employers they want, and ones they will not consider.
7. Any other hard no's (hours, shifts, on-call, sales quotas, managing people, licenses, culture).

Write hard no's in `FILTERS.md`. Smaller concerns go in a soft-flag section, not as secret dealbreakers.

## Phase 4: Evidence and level

Ask, one at a time:

1. Core skills and tools, with a real example for each kind of work they want to be hired for.
2. What level of job they are aiming at, and how they would back it up.
3. Honest gaps, and how they would say that in an application.
4. Portfolio, LinkedIn, writing, licenses, or other proof they want used. Links only if they provide them.

Build a `Do not claim` list: numbers, titles, tools, or stories that are outdated, overstated, or not theirs to use.

## Phase 5: Voice

You need enough signal to write like them.

1. Ask them to paste two or three short emails or messages they actually sent, or a paragraph they wrote.
2. If they have none, ask them to answer one question the way they would write to a hiring manager (for example: "Why are you looking for a new job?"). Use that as the starting sample and mark the voice file as thin until they send more.
3. Ask how formal they want to sound in a cover letter versus a LinkedIn note.
4. Ask about greetings, sign-offs, contractions, and words they cannot stand.
5. Keep the default banned list in `VOICE.md`: em dashes, en dashes, double hyphens, passionate, leverage, I'm thrilled, I'm excited to, synergy, spearhead, drive impact, at the intersection of, I'd love the opportunity, deeply, seamless, robust, unlock, empower, journey, resonate, not just X but Y, rhetorical questions, lists of three adjectives, and anything that sounds like a LinkedIn post or a consultant pitch. Add their personal bans. Remove a default only if they clearly want it allowed.
6. Confirm the cover letter default (short, under one page) or write down what they want instead.

## Phase 6: How jobs get scored, and targets

1. Explain in one or two sentences: every job gets a score out of 25, from five scores of 1 to 5 (Fit, Level, Location, Growth, Joy).
2. Draft the 5 to 1 descriptions for each score yourself from their answers, so a stranger could score with them. Show the draft and ask them to confirm or fix it. Do not make them write the descriptions.
3. Suggest a **minimum score** for their shortlist based on their situation, and explain it in one sentence: around 22 / 25 for experienced people who know exactly what they want, 18 to 20 for career changers, new grads, or anyone whose realistic matches will have a stretch. Use the number they pick.
4. Ask whether a rare dream job may get in a little below their minimum score. If they do not say yes, there is no exception.
5. Fill `TARGETS.md` with keywords, job sites that fit their field, things to skip, and only companies they named.
6. Confirm freshness (default: posted in the last 21 days) and that there is no target number of jobs.

## Close the profile

- Show the five files (in a plain chat, as one block) and ask them to correct anything that feels off.
- Remind them: you will not apply or send messages for them, you will not invent facts, and the shortlist only holds jobs at or above their minimum score.

## Phase 7: Setup

Do this after they say the profile looks right. One step at a time, in plain words.

1. **Resume.** If they have not shared a resume yet, ask them to attach it to a message here (or paste the text). If they don't have one, that's fine. Note it, and offer to help draft one later from their profile.
2. **Gmail.** If Gmail is not already connected, offer to connect it. Explain why in one sentence: it lets you spot recruiter replies and interview requests and draft follow-ups for them to send. Say clearly that you never send email for them. If they say yes, start the Gmail connection so they can sign in with Google themselves. Never ask for their password. If they say no, move on.
3. **Morning job search.** Ask exactly: "Want me to search for new roles every morning and update your queue?" If they say yes:
   - Ask what time works (suggest 8 AM in their time zone) and confirm their time zone.
   - Set up a daily routine at that time that runs the `job-hunt-scan` skill against their files, updates their queue, and sends them a short summary of new shortlist jobs (or a one-line "nothing new today").
   - The routine never applies and never contacts anyone. It offers to prep packets for the top 3 new jobs instead of prepping everything.
   - Tell them they can pause or change it anytime by asking.
   If they say no, tell them they can ask for a search whenever they want.
4. **Finish.** Tell them what to say next, in plain words: "find me jobs," "prep a packet for [job]," or "help me follow up with [company]." Remind them to install the free Simplify Copilot Chrome extension (on a computer) when they are ready to apply, and to skip Simplify's Autopilot and paid upgrades.

If a step is not available in this environment (for example, no Gmail connection or no scheduling), say so in one line and move on. In a plain chat, skip steps 2 and 3 and remind them to paste their "My Job Hunter profile" doc with the hunt prompt whenever they want a search.
