---
name: apply-packet
description: >-
  Use to prepare a paste-ready application packet for a shortlisted job: the
  application's real questions in order, unique answers, a short cover letter
  only when the form has a field, a voice check, optional LinkedIn notes to a
  real named person, and recruiter follow-up drafts. Never apply or send for
  the person.
---

# Apply packet

Prepare a packet the person can paste into the real application and submit themselves. Never auto-submit. Never mass-apply. Do not invent interview answers for questions the form does not ask unless they request interview prep separately. Many people using this are not technical. Use plain words.

If the profile files are missing, stop and get them (intake or a pasted "My Job Hunter profile" doc) before drafting.

## When to prep

After a hunt, offer to prep packets for the top 3 jobs (highest score, then newest), or ask which ones they want. Do not prep the whole shortlist unless they ask. Skip jobs that fail a hard filter. A job with only a soft-flag concern can still be prepped if they want it.

A packet is not done until it meets the ready bar, or you have a clear blocked reason (the form needs a login, the posting closed, profile facts are missing, and so on).

## Get the real questions

1. If you can open the public application, list every field in order: label, required or optional, type (short text, long text, file, dropdown, checkbox), dropdown or checkbox options that need a decision, whether there is a cover letter or "additional information" field, and uploads.
2. If the form needs a login or will not load (common with Workday and many large employers), say so plainly and ask them to open the application themselves and paste the questions or send screenshots. Until then, prep from the posting and mark the packet "needs the real questions."
3. Questions or screenshots they paste count as the form. Use their order.

Many people use the free Simplify Copilot Chrome extension for basic fields (name, contact info, work history, education). Focus on the custom questions. List basic fields only when they need a decision.

## Packet contents

Write the packet in plain, copyable text with a short ID in the title. Include:

1. **Job info:** employer, title, score breakdown, posting date, location, pay if posted, apply link, one-sentence summary.
2. **Answers, in form order:** one section per question, in the real order. Each written or unique question gets a paste-ready answer. Uploads can be a short note. Decision fields (work authorization, start date, pay expectation, referral, and the like) get a suggested answer from `PROFILE.md` and `FILTERS.md`, plus a flag if they still need to confirm a number.
3. **Cover letter:** include it only if the form has a cover letter field (required or optional). If there is no field, leave it out.
4. **Packet notes:** where the question order came from, location or filter notes, anything blocked or unconfirmed.
5. **LinkedIn note (optional, last):** see below.

Every long answer and the cover should be unique to this employer and job. Do not clone a prior packet and swap the name.

## Voice and facts

- Follow `VOICE.md`. Plain and human, like this person writing a careful professional email.
- Short, clear sentences. Contractions only if their voice file allows them. Concrete about what they did or changed.
- No slang unless their samples actually use it. No buzzwords or AI filler.
- Never use these: em dashes, en dashes, double hyphens, passionate, leverage, I'm thrilled, I'm excited to, synergy, spearhead, drive impact, at the intersection of, I'd love the opportunity, deeply, seamless, robust, unlock, empower, journey, resonate, not just X but Y, rhetorical questions, lists of three adjectives, and anything that sounds like a LinkedIn post or a consultant pitch. Use commas, periods, or parentheses instead of dashes. Also honor their personal bans in `VOICE.md`.
- Use only facts in `PROFILE.md`, the resume, or something they confirmed. Never invent numbers, tools, awards, job history, or a "do not claim" item.

## Cover letter (only if the form has a field)

Default shape, unless `VOICE.md` says otherwise:

- Short, under one page: 3 or 4 short paragraphs
- No indents, one blank line between paragraphs
- Header from `PROFILE.md` (name, location, email, links they provided). Do not invent contact details
- Greeting `Hi <Company> team,` unless they name a real person
- Cover: the job and why they want it (with one specific true thing about the employer), what they do now, one or two real examples, and an honest gap or stretch plus a simple close
- Unique to this job. Write it fresh.

## LinkedIn note (optional)

Include this only when there is a real, named person: someone the person gave you (name and LinkedIn link), or a contact named on the job post or the employer's own pages whom you confirmed currently works there in a relevant role.

- Format the recipient as `Name, Title at Company (link)`, and address the note by first name.
- Write a connect note (300 characters max) and a follow-up for after they accept (about 500 to 700 characters).
- Only write an InMail if they ask for one (subject under 60 characters, body about 120 to 180 words).
- Never invent a person, never guess, and never leave a `[Name]` placeholder. If there is no real person, skip the section and add one line on how they could find one (the job post, the employer's LinkedIn page, or its team page).
- True facts only, voice rules, no dashes, plain text inside the message.

## Recruiter email drafts

If they ask for an email, draft only to a real address (the posting, the employer's careers page, or a message they already received). Never guess an email pattern and call it real. Subject and body in their voice. Do not send it.

## Voice check

Before you show a cover, form answer, LinkedIn note, or recruiter email, check it against `VOICE.md`: banned words, dash marks, invented facts, and whether it sounds like them. If a second reviewer is available, use it. Otherwise do the check yourself and fix issues before the person sees a "final" draft.

## Ready bar

A packet is ready only if all of these are true:

1. The real questions were used (from the live form or their paste), or the packet is clearly marked "needs the real questions"
2. Every written or unique question has a paste-ready answer
3. A cover is included only when the form has a cover field, and it meets the length, punctuation, voice, and uniqueness rules
4. Decision fields are filled or clearly waiting on the person
5. Any LinkedIn note goes to a real, named person with no placeholders (or the section is skipped with a one-line tip)
6. Location and hard filters are honest
7. The job still scores at or above their minimum score
8. Nothing in the do-not-claim list appears

If any of that is missing, the packet still needs work. Say what is blocked. Do not hand over stubs as if they were done.

## After they apply

They tell you when they submitted. Add a row to their application log (`tracker/applications.csv`, or one line they can paste into their tracking spreadsheet), move the job to Applied in the queue, and set a follow-up date (about one week out unless they pick another). Never move an applied job back to Pending. Do not apply for them.
