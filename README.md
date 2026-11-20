# Lucas Jang

I'm finishing a Management Science degree at NYU (December 2026), and I spend most of my spare time building small tools that do work for me. Most of them run on a schedule, often while I'm asleep. I write a lot of this alongside Claude Code, which is why so many of my repos have a `CLAUDE.md` in them.

## Live

[TrainVue](https://trainvue.app) is a practice booth for one-way video interviews. Its prompter follows your voice as you talk, and on a live call it can catch the interviewer's question and give you an outline for the answer. The code is private.

[Luminex Research](https://podcast.luminexenterprise.com) is a weekly crypto research podcast, 14 episodes in. A pipeline turns a written research memo into an episode with two AI hosts, publishes the audio and RSS feed from Cloudflare R2, and cuts vertical shorts from each one. The code is private.

## Public repos

[fomc-voice-volatility](https://github.com/LucasKSJang/fomc-voice-volatility) asks whether the Fed Chair's voice moves the market. I measured the audio of 30 FOMC press-conference openings against 1-second SPY moves. Loudness seemed to predict volatility (r = 0.42) until I controlled for how volatile the market already was before Powell started speaking, and then the effect went away. The repo keeps the first result and the checks that overturned it.

[research-factory-ONLYLOCALAI](https://github.com/LucasKSJang/research-factory-ONLYLOCALAI) does unattended web research on one desktop GPU. Topics go in and cited reports come out every day, with no API bill. It runs on Ollama with Qwen3, SearxNG, GPT Researcher and n8n, and getting it stable meant fixing seven bugs in those upstream projects. The README goes through each one.

[declassifier](https://github.com/LucasKSJang/declassifier) is a check to run before you publish something you built at a job. It looks for leftover company names, colleagues' email addresses, internal IDs and home-directory paths, and it keeps your list of sensitive terms outside the repo it scans, so the list itself never gets committed.

[writing-throughmap](https://github.com/LucasKSJang/writing-throughmap) is a skill for Claude Code and Codex that maps how an essay flows: what each paragraph is doing, which threads carry through, and where the gaps are. It draws all of that as a single offline HTML page.

[automation_v2](https://github.com/LucasKSJang/automation_v2) and [efficiency-maximizer-automation](https://github.com/LucasKSJang/efficiency-maximizer-automation) are cleaned-up versions of automations I built for a business-development team at a crypto asset manager. They include contact capture from Slack into Google Sheets, Gmail drafts written from a one-line Slack request, data-room follow-up tracking and a morning briefing agent.

## Private

There are about a dozen more repos, mostly scheduled agents: a daily metrics digest on Telegram, a pipeline that produces short AI-video Reels, an interview coach that runs as a Telegram bot, and a weekday shortlist of people worth reaching out to.
