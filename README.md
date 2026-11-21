# Job Hunter

A free, do-it-yourself job-search kit. It interviews you to figure out what you actually want, helps you find and score roles, and drafts paste-ready applications and follow-ups in your own voice. It never applies or sends anything for you. You stay in control of every submit and every message.

**Who it's for:** anyone looking for a job who wants a calmer, more organized search: fewer, better-fit applications instead of spraying resumes. No coding needed. If you can copy and paste into ChatGPT or Claude, you can use it.

New here? [SETUP.md](SETUP.md) has step-by-step instructions for both ways to run it.

## Start in 2 minutes

1. Open [`prompts/01-intake.md`](prompts/01-intake.md) and copy everything in it.
2. Paste it into a new chat in ChatGPT, Claude, or Gemini. Attach your resume if you have one.
3. Answer the questions. It asks one at a time.
4. At the end it writes five short profile files. Save them (the `templates/` folder in a downloaded copy of this repo works, or any private notes folder).

That's it. Next time you want to look for roles or apply, paste the next prompt plus your saved files.

## How it works

| Step | Prompt | What you get |
|------|--------|--------------|
| 1. Intake | [`01-intake.md`](prompts/01-intake.md) | Your profile, filters, scoring rubric, search targets, and a voice guide |
| 2. Hunt | [`02-hunt.md`](prompts/02-hunt.md) | Roles scored out of 25. Only the ones at or above your floor (default 22) make the queue |
| 3. Apply | [`03-apply-packet.md`](prompts/03-apply-packet.md) | Paste-ready answers in the form's order, plus a cover letter only if the form asks for one |
| 4. Follow up | [`04-follow-up.md`](prompts/04-follow-up.md) | Short follow-up and outreach drafts to verified contacts |

Each prompt says at the top which saved files to paste in with it. A plain chat can't run on a schedule, so you run the hunt prompt yourself whenever you want fresh roles.

## Or run it as a Grok Bot

With a Grok Bot, the same workflow runs on its own: a daily hunt, a queue it keeps up to date, and packets and follow-ups drafted for you to review and send. Open the template, add your own copy, connect Gmail, upload your resume, and do the intake. Full steps are in [SETUP.md](SETUP.md).

Template link: https://x.ai/bot/1Bam7NFo7BJ98UjYreRB-

The `skills/` folder has the instructions the bot uses, so other agents can load them too.

## What's in the repo

- `SETUP.md` step-by-step setup for both paths
- `prompts/` copy-and-paste prompts for any AI chat
- `templates/` blank versions of the profile files the intake fills in (`PROFILE`, `FILTERS`, `RUBRIC`, `TARGETS`, `VOICE`)
- `tracker/QUEUE_TEMPLATE.md` a simple queue page for scored roles
- `tracker/applications.csv` a blank application log you can open in Excel or Google Sheets
- `skills/` agent versions of the intake, hunt, and apply steps

## Ground rules it follows

1. Never applies or sends a message for you.
2. Never makes up facts, employers, numbers, or contacts.
3. Checks every draft against your voice guide so it sounds like you, not a chatbot.
4. Only uses recruiter names and emails that have been verified.
5. Keeps filler out of the queue. A short queue is fine.

## Keep your stuff private

Your filled-in profile, resume, and queue are personal. Don't commit them to a public fork.

## License

MIT. See [`LICENSE`](LICENSE).
