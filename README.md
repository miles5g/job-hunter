# Job Hunter

A personal job-search system you can run yourself. It interviews you in depth, hunts for roles, keeps a scored queue of only the best fits, and prepares paste-ready applications in your own voice. It never applies or sends messages for you.

New here? Follow the exact setup steps in [SETUP.md](SETUP.md).

## What it does

- **Deep intake interview.** One question at a time, covering your story, what actually drives you, your dealbreakers, how you work best, and how you sound in writing.
- **Daily hunt.** Search job boards and company career sites, then score each role against your rubric.
- **Scored queue.** Only roles at or above your floor (default 22 out of 25) stay in the queue. No filler.
- **Paste-ready packets.** Live form scans, unique answers, and a cover letter only if the form asks for one, written in your voice.
- **Verified follow-ups.** Recruiter notes and LinkedIn outreach use real, checked contacts. No invented names or emails.

## Two ways to use it

See [SETUP.md](SETUP.md) for the full beginner walkthrough.

### A. Grok Bot

Create a Grok Bot account, open the Job Hunter template, add or import the bot, connect Gmail, upload your resume, and answer the intake.

Template link: TEMPLATE_LINK

After setup, the bot can run a daily hunt, keep your queue, and draft packets and follow-ups for you to send.

### B. Any AI chat (ChatGPT, Claude, Gemini)

No install. Download this repo as a ZIP, or open the `prompts/` folder, then paste the prompts in order:

1. `01-intake.md` to build your profile files
2. `02-hunt.md` when you want to search and score roles
3. `03-apply-packet.md` when you are ready to apply to a role
4. `04-follow-up.md` after you apply, or when a recruiter writes back

Save the profile files the chat produces (`PROFILE.md`, `FILTERS.md`, `RUBRIC.md`, `VOICE.md`, `TARGETS.md`) into the `templates/` folder, and paste them back in at the start of later chats. The daily auto-scan needs an agent with web access and scheduling, so in a plain chat you run the hunt prompt yourself.

## Files in this repo

- `SETUP.md` exact beginner steps for both paths
- `skills/` instructions a Grok Bot (or another agent) can load
- `prompts/` self-contained paste-in prompts for a plain chat
- `templates/` blank versions of the profile files the intake fills in
- `tracker/QUEUE_TEMPLATE.md` a simple queue page
- `tracker/applications.csv` a header-only application log

Copy the templates into your own folder and fill them in during intake. Do not commit your filled-in profile, resume, or queue to a shared repo.

## Rules the system always follows

1. Never apply or send for you.
2. Never invent facts, employers, numbers, or contacts.
3. Voice-check every draft against your voice file.
4. Only use recruiter emails and names you have verified.
5. Keep filler out of the queue.

## License

Released under the MIT License. See `LICENSE`.
