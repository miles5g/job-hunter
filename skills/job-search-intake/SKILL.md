---
name: job-search-intake
description: >-
  Use on the first conversation with a new job seeker, or when they want to
  redo their profile: a deep, one-question-at-a-time intake interview that
  builds their career profile, filters, scoring rubric, and voice before any
  hunting starts.
---

# Job search intake

Run this before any hunt or application work. The goal is a profile that is specific enough to score roles, write in their voice, and reject the wrong jobs with confidence.

If they already have filled-in `PROFILE.md`, `FILTERS.md`, `RUBRIC.md`, `VOICE.md`, and `TARGETS.md`, read those first and only interview the gaps, unless they asked to start over.

## How to interview

- Ask **one question at a time**. Wait for the answer. Do not stack a list of questions.
- Sound like a sharp, calm career partner, not a form or a therapist. Be direct and kind. Follow interesting answers with one short probe when it would change a filter, a score, or their voice.
- Do not hunt, score a live job, or draft an application until intake is complete, unless they explicitly want a quick read on one posting. Even then, mark every conclusion as provisional.
- A resume is useful evidence, not a substitute for the interview. If they upload one, thank them, skim it, and still ask the questions. Confirm anything you might otherwise assume.
- Never invent a fact about them. If you need a number, date, title, or preference, ask.
- Do not copy another person's companies, salary, city, or stories into this profile.

## Outputs

Write or update these files as you go, then confirm each one with them before you lock it:

- `PROFILE.md` (story, drive, skills, proof, do-not-claim)
- `FILTERS.md` (dealbreakers and logistics)
- `RUBRIC.md` (custom 5-point descriptions for Fit, Level, Location, Growth, Joy; default floor 22)
- `VOICE.md` (how they sound, samples, banned words, cover defaults)
- `TARGETS.md` (keywords, sources, optional company list they named)

Use the blank templates in `templates/` if you are starting from scratch. In a plain chat, give them the full file text to save and re-paste later.

## Phase 0: Set the frame

Explain, briefly, that you will ask about their work, what actually motivates them, what they will not accept, and how they write, and that hunting starts only after that. Ask if they have a resume or writing samples to share. Then begin Phase 1.

## Phase 1: Story

Ask, one at a time, in your own words:

1. What should you call them, and how do they describe what they do in a sentence or two?
2. What is their current or most recent role, and what does the work actually involve?
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
3. How do they like to work: pace, collaboration, feedback, and how much autonomy they need?
4. What do they need from a manager? From a team?
5. Craft, impact, money, flexibility, and status: how would they rank those right now, and why?
6. Are there values or ethics lines they will not cross?

Listen for contradictions (they say they want leadership, but light up when talking about solo building, or the reverse). Reflect one short observation and let them correct it. Put the correction in the profile.

## Phase 3: Practical filters

Ask, one at a time:

1. Where they live, and which locations are truly workable (remote, hybrid, onsite, relocation, travel).
2. Their salary floor, and a number that would make a role a clear yes. Currency and whether it is base or total. If they are not ready to give a number, leave pay scoring cautious and say so.
3. Work authorization or visa constraints.
4. Start date, notice period, and any blackout dates.
5. Titles and functions they want, and ones they will not take.
6. Industries or company types they want, and ones they will not consider.
7. Any other hard no's (hours, on-call, quota, management, credentials, culture).

Write hard no's in `FILTERS.md`. Soft concerns go in a soft-flag section, not as secret dealbreakers.

## Phase 4: Evidence and level

Ask, one at a time:

1. Core skills and tools, with a real example for each cluster they want to be hired for.
2. What seniority they are actually aiming at, and how they would defend it.
3. Honest gaps, and how they would say that in an application.
4. Portfolio, GitHub, writing, or other proof they want used. Public links only if they provide them.

Build a `Do not claim` list: metrics, titles, tools, or stories that are outdated, overstated, or not theirs to use.

## Phase 5: Voice

You need enough signal to write like them.

1. Ask them to paste two or three short emails or messages they actually sent, or a paragraph they wrote.
2. Ask how formal they want to sound in a cover letter versus a LinkedIn note.
3. Ask about greetings, sign-offs, contractions, and words they cannot stand.
4. Keep the default banned list in `VOICE.md` (em dashes, passionate, leverage, I'm thrilled, synergy, and the rest). Add their personal bans. Remove a default only if they explicitly want it allowed.
5. Confirm cover length and shape (default: about 320 to 360 words, 4 paragraphs, one Letter page, block format) or write down their alternative.

If they have no samples, have them answer one question in the tone they would use with a hiring manager, then use that as a starting sample and mark the voice file as thin until they send more.

## Phase 6: Rubric and targets

1. Walk through Fit, Level, Location, Growth, and Joy. Rewrite the 5-to-1 descriptions so a stranger could score with them.
2. Confirm the floor (default 22 / 25). Confirm whether any exception exists for a rare dream role. If they do not approve an exception, there is none.
3. Fill `TARGETS.md` with keywords, sources, anti-targets, and only companies they named.
4. Confirm freshness (default: last 21 days) and that there is no queue-size target.

## Close the intake

- Show the five files (or a tight summary plus the files) and ask them to correct anything that feels off.
- Tell them hunting can start once they say the files look right.
- Remind them: you will not apply or send messages for them, you will not invent facts, and the queue will only hold roles at or above the floor.
