# Job Hunter

A free, do-it-yourself job-search kit. It interviews you to figure out what you actually want, helps you find and score jobs, and drafts paste-ready applications and follow-ups in your own voice. It never applies or sends anything for you. You stay in control of every submit and every message.

**Who it's for:** anyone looking for a job who wants a calmer, more organized search: fewer, better-fit applications instead of spraying resumes. No tech skills needed. If you can copy and paste into ChatGPT, Claude, or Gemini, you can use it.

**New here? Start with [SETUP.md](SETUP.md).** It has a 5-step Quick start and plain instructions for both ways to use it.

## Quick start

1. Open the [intake prompt](https://github.com/miles5g/job-hunter/blob/main/prompts/01-intake.md) and click the **copy** button (two overlapping squares) at the top right of the text.
2. Paste it into a new chat in ChatGPT, Claude, or Gemini. Attach your resume if you have one. Answer the questions (about an hour; you can stop and come back).
3. At the end it gives you your profile in one block. Copy it into one Google Doc called **My Job Hunter profile**.
4. To find jobs, apply, or follow up, paste that doc into a new chat with the matching prompt: [hunt](https://github.com/miles5g/job-hunter/blob/main/prompts/02-hunt.md), [apply](https://github.com/miles5g/job-hunter/blob/main/prompts/03-apply-packet.md), or [follow up](https://github.com/miles5g/job-hunter/blob/main/prompts/04-follow-up.md).
5. When you are ready to apply, install the free [Simplify Copilot](https://chromewebstore.google.com/detail/simplify-copilot-autofill/pbanhockgagggenencehbnadejlgchfc) Chrome extension for the basic fields, and submit yourself.

## How it works

| Step | Prompt | What you get |
|------|--------|--------------|
| 1. Intake | [`01-intake.md`](prompts/01-intake.md) | Your profile: who you are, your hard no's, how jobs get scored, your voice, and where to look |
| 2. Hunt | [`02-hunt.md`](prompts/02-hunt.md) | Jobs scored out of 25. Only the ones at or above your minimum score make your shortlist |
| 3. Apply | [`03-apply-packet.md`](prompts/03-apply-packet.md) | Paste-ready answers to the application's questions, plus a short cover letter only if it asks for one |
| 4. Follow up | [`04-follow-up.md`](prompts/04-follow-up.md) | Short follow-up and reply drafts to real contacts |

Each prompt says at the top what to paste with it. A plain chat can't run on a schedule, so you run the hunt prompt yourself whenever you want fresh jobs.

## Or use it as a Grok Bot

With a Grok Bot, the search can run every morning on its own, keep your shortlist up to date, and draft packets and follow-ups for you to check and send. Open the template, click **Add to Grok Bot**, and do the intake. The bot then asks for your resume, offers to connect Gmail, and offers the morning search. Full steps are in [SETUP.md](SETUP.md).

Template link: https://x.ai/bot/1Bam7NFo7BJ98UjYreRB-

The `skills/` folder has the instructions the bot uses, so other AI agents can use them too.

## What's in this project

- `SETUP.md` step-by-step setup for both ways to use it
- `prompts/` copy-and-paste prompts for any AI chat
- `templates/` blank versions of the five profile sections the intake fills in (`PROFILE`, `FILTERS`, `RUBRIC`, `TARGETS`, `VOICE`)
- `tracker/QUEUE_TEMPLATE.md` a simple shortlist table you can keep in a Google Doc or Google Sheet
- `tracker/applications.csv` a blank application log. In Google Sheets, use File > Import > Upload to open it
- `skills/` bot versions of the intake, hunt, and apply steps

## Ground rules it follows

1. Never applies or sends a message for you.
2. Never makes up facts, employers, numbers, jobs, or contacts.
3. Checks every draft against your voice so it sounds like you, not a chatbot.
4. Only writes to real, named contacts.
5. Keeps weaker jobs off your shortlist. A short shortlist is fine.

## Keep your stuff private

Your filled-in profile, resume, and shortlist are personal. Don't post them publicly.

## License

MIT. See [`LICENSE`](LICENSE).
