---
name: apply-packet
description: >-
  Use to prepare a paste-ready application packet for a queued role: live form
  scan, unique answers, a tailored cover letter only when the form has a field,
  voice check, LinkedIn outreach, and recruiter follow-up drafts. Never apply
  or send for the person.
---

# Apply packet

Prepare a packet the person can paste into the real form and send themselves. Never auto-submit. Never mass-apply. Do not invent interview answers for questions the form does not ask unless they request interview prep separately.

If the profile files are missing, stop and get them (intake or a paste) before drafting.

## When to prep

After a hunt or queue restock, prep the top roles (default: top 10 by score, then newer first) so the person is not handed an empty shortlist. Skip roles that fail a hard filter. A location that is only a soft flag can still be prepped if they want that band.

A packet is not done until it meets the ready bar, or you have a clear blocked reason (form is login-only, posting closed, missing profile facts, and so on).

## Live form scan

Open the public apply form and map every field in order:

- Field label, required or optional, type (short text, long text, file, select, checkbox)
- Select or checkbox options that need a decision
- Whether there is a cover letter or "additional information" field
- Uploads (resume, transcripts) and any instructions

If the form is behind a login, say so, prep from the posting plus any fields you can see, and mark the packet as needing a live pass once they can open the form. Re-scan if the form may have changed.

## Packet contents

Write a markdown packet with a short ID in the filename or title. Include:

1. **Basic info:** company, title, score breakdown, posting date, location, salary if posted, apply URL, one-sentence summary.
2. **Application (form order):** one section per field, in the exact live form order. Each open-ended or unique field gets a paste-ready answer. Uploads can be a short note with no answer box. Decision fields (work authorization, start date, salary expectation, referral, and the like) get a recommended answer from `PROFILE.md` and `FILTERS.md`, plus a flag if they still need to confirm a number.
3. **Cover letter:** include it only if the form has a cover field (required or optional). If there is no cover field, omit the letter.
4. **Packet notes:** source of the form order, geo or filter notes, anything blocked or unconfirmed.
5. **LinkedIn outreach** as the last section.

Every long answer and the cover should be unique to this company and role. Do not clone a prior packet and swap the name.

## Voice and facts

- Follow `VOICE.md`. Plain and human, like this person on a careful professional email or a phone call, depending on what their voice file says.
- Short, clear sentences. Contractions only if their voice file allows them. Concrete what they built or changed.
- No slang unless their samples actually use it. No consultant or AI filler.
- Never use em dashes, en dashes, or double hyphens. Use commas, periods, or parentheses.
- Honor the banned-word list in `VOICE.md` (including passionate, leverage, I'm thrilled, synergy, and the rest).
- Use only facts in `PROFILE.md`, the resume, or something they confirmed. Never invent metrics, tools, awards, job history, or a "do not claim" item.

## Cover letter (only if the form has a field)

Default shape, unless `VOICE.md` says otherwise:

- Body about 320 to 360 words, 4 paragraphs, and the full letter fills one Letter page without spilling over
- Block format, no indents, one blank line between paragraphs, each paragraph one line in the source file
- Header from `PROFILE.md` (name, location, email, links they provided). Do not invent contact details
- Greeting `Hi <Company> team,` unless a verified person is the better addressee
- Paragraph 1: the job and why they want it, with one specific true thing about the company
- Paragraph 2: what they do now, only confirmed facts
- Paragraph 3: two or three real pieces of work in concrete detail
- Paragraph 4: an honest gap or stretch plus a true supporting detail, then a simple close
- Unique to this role. Write it fresh.

## LinkedIn outreach

Every packet ends with a LinkedIn section:

- **Send to:** a real, verified person plus a backup, with links, in this form: `Name, Title at Company (LinkedIn URL). Backup: Name, Title (LinkedIn URL).` Find them on public LinkedIn, the job post, or a company team page. Confirm they currently work there in a relevant role. Never invent a person. If the pick is inferred, mark it `(best guess)`. Address the note to the main person's first name. A packet with a `[Name]` placeholder is not ready.
- Roles under 23: a connect note (300 characters max) and a follow-up after they accept (about 500 to 700 characters).
- Roles scored 23 to 25: an InMail instead, if they use InMail (subject under 60 characters, body about 120 to 180 words). Otherwise use the connect note and follow-up.
- True facts only, voice rules, no dashes, no markdown inside the message text.

## Recruiter email drafts

If they ask for an email, or you are using the follow-up prompt, draft only to a verified address (the posting, a company careers page, or a message they already received). Never guess an email pattern and call it verified. Subject and body in their voice. Do not send it.

## Voice check

Before you show a cover, form answer, LinkedIn note, or recruiter email, check it against `VOICE.md`: banned words, dash marks, invented facts, and whether it sounds like them. If a second reviewer is available, use it. Otherwise do the check yourself and fix issues before the person sees a "final" draft.

## Ready bar

A packet is ready only if all of these are true:

1. The live form was scanned, or the login-wall limit is clearly marked
2. Every open-ended or unique question has a paste-ready answer
3. A cover is included only when the form has a cover field, and that cover meets length, punctuation, voice, and uniqueness rules
4. Decision fields are filled or explicitly waiting on the person
5. LinkedIn outreach is present, last, and uses verified (or clearly labeled best-guess) contacts with no name placeholders
6. Location and hard filters are honest
7. The role still scores at or above the floor
8. Nothing in the do-not-claim list appears

If any of that is missing, the packet still needs work. Do not hand over stubs as if they were done.

## After they apply

They tell you when they submitted. Add a row to `tracker/applications.csv`, move the role to Applied in the queue, and set a follow-up date. Never restore an applied ID to Pending. Do not apply for them.
