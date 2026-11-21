# Set up Job Hunter

Two ways to run it. Path A is a Grok Bot that can hunt on a schedule. Path B works in an ordinary chat app with no account beyond the one you already have.

The bot never applies or sends messages for you. You stay in control of every submit and every email.

## Before you start: install Simplify

Install [Simplify](https://simplify.jobs), a free Chrome extension that autofills job applications. Make a free account, add the extension to Chrome, and fill in your profile there once (contact info, work history, education, resume). Then when you open a real application form, Simplify fills in the standard fields, and you paste the custom answers from your Job Hunter packet into the rest. You still review and press Submit yourself.

## A. Grok Bot

1. Create a Grok Bot account if you do not already have one, then sign in.
2. Open the Job Hunter template link:

   https://x.ai/bot/1Bam7NFo7BJ98UjYreRB-

3. Add or import the bot so you have your own copy of Job Hunter. Your copy is private to you.
4. When the bot asks you to connect Gmail, do that. This is how it can read recruiter mail and help draft follow-ups. It will not send messages unless you later ask it to draft one and you send it yourself.
5. Upload your resume (and any short writing samples you want it to learn from).
6. Do the intake interview. Answer one question at a time. Be honest about location, salary floor, dealbreakers, and how you actually write. The bot will turn your answers into profile files (`PROFILE.md`, `FILTERS.md`, `RUBRIC.md`, `VOICE.md`, `TARGETS.md`).
7. When intake is done, say yes if you want the daily hunt turned on. The bot will search and score roles and keep a queue of only the ones at or above your floor (default 22 out of 25).
8. When you are ready to apply, ask it to prep a packet for a role in your queue. Copy the answers into the real application form and submit them yourself. Use the follow-up drafts the same way: copy, then send.

If anything in the profile looks wrong, tell the bot and have it update the file before you apply.

## B. No install (ChatGPT, Claude, Gemini, or another AI chat)

1. Open the Job Hunter repo: https://github.com/miles5g/job-hunter
2. Download it. Click the green **Code** button, then **Download ZIP**. Unzip the folder on your computer. (If you prefer, you can also just open the `prompts/` files on GitHub and copy them.)
3. Open a new chat in ChatGPT, Claude, Gemini, or another AI chat.
4. Open `prompts/01-intake.md`, copy the whole file, and paste it into the chat. Attach or paste your resume if you have one. Answer the questions one at a time.
5. When the chat gives you the profile files (`PROFILE.md`, `FILTERS.md`, `RUBRIC.md`, `VOICE.md`, `TARGETS.md`), save them. The easiest place is the `templates/` folder in the unzipped project, replacing the blanks (or save a personal copy next to them). Keep those files. You will paste them into later chats.
6. When you want to hunt for jobs, start a chat (or keep the same one), paste your saved profile files, then paste `prompts/02-hunt.md`. If the chat can browse the web, it can search and score roles. If it cannot, it will give you a search plan and score postings you paste in. Save the updated queue (you can use `tracker/QUEUE_TEMPLATE.md`). In a plain chat there is no automatic daily scan, so run this prompt yourself whenever you want a hunt.
7. When you are ready to apply, paste your profile files, the job link or queue row, and `prompts/03-apply-packet.md`. Copy the packet answers into the real form and submit them yourself.
8. After you apply, or when a recruiter writes back, paste `prompts/04-follow-up.md` plus the thread and your profile files. Copy the draft, then send it yourself. Log the date in `tracker/applications.csv`.

Do not commit your filled-in profile, resume, or queue to a shared repo or a public fork.

## If you get stuck

- You need the five profile files before a hunt or a packet will be any good. If they are missing, run intake again or paste the files you already saved.
- The queue should stay short and honest. An empty queue is fine. Do not lower the floor just to fill space.
- If a draft does not sound like you, point at the line and have the chat rewrite it against your `VOICE.md`.
