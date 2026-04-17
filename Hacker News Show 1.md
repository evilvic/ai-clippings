---
title: "Hacker News Show #1"
source: "https://githubawesome.com/hacker-news-show-1/"
author:
  - "[[GithubAwesome]]"
published: 2026-03-22
created: 2026-04-03
description: "Today we're launching something new: the Hacker News Show. Instead of our usual GitHub trending list, we're going straight to the Show HN section, where solo developers post the things they've been building. Thirty projects, hand-picked from the archives.No. 1 - TermcraftTermcraft is a fully playable 2D sandbox"
tags:
  - "clippings"
---
Today we're launching something new: the Hacker News Show. Instead of our usual GitHub trending list, we're going straight to the Show HN section, where solo developers post the things they've been building. Thirty projects, hand-picked from the archives.

![](https://www.youtube.com/watch?v=i9YpWp0hXgg)

No. 1 - Termcraft

![](https://githubawesome.com/content/images/2026/03/image-275.png)

Termcraft is a fully playable 2D sandbox survival game that runs entirely in the terminal, written in Rust. Procedural generation across the Overworld, Nether, and End dimensions. Mining, crafting, furnaces, hostile mobs, dungeons, all rendered in ASCII directly in your console. If you spend most of your day in a terminal anyway, this is a reasonable use of your lunch break.

[https://github.com/pagel-s/termcraft](https://github.com/pagel-s/termcraft?ref=githubawesome.com)

No. 2 - Switchboard

![](https://githubawesome.com/content/images/2026/03/image-276.png)

If you're running multiple Claude Code sessions and losing track of which agent is doing what, Switchboard is the missing layer. It's a desktop app built with Electron and SQLite that organizes all your CLI coding sessions by project, gives you full-text search across them, and alerts you when an agent stalls and needs input. Less tab chaos, more visibility into what's actually running.

[https://github.com/doctly/switchboard](https://github.com/doctly/switchboard?ref=githubawesome.com)

No. 3 - Fortransky

![](https://githubawesome.com/content/images/2026/03/image-277.png)

Someone built a fully functional terminal Bluesky client in Fortran. The firehose decoder is Rust, but the core logic is modern Fortran. It landed on Hacker News and opened up a genuine conversation about how readable and performant modern Fortran actually is when people bother to look at it. Keeping the old languages alive in the most unexpected places.

[https://github.com/FormerLab/fortransky](https://github.com/FormerLab/fortransky?ref=githubawesome.com)

No. 4 - pi-worker

![](https://githubawesome.com/content/images/2026/03/image-278.png)

Pi-Worker gives you autonomous agent workers that run natively in the terminal, built for complex multi-step pipelines.Hand it a high-level task, and it handles execution in your local environment without you managing each step manually.For anyone building serious AI automation pipelines, worth checking the repository.

[https://github.com/qaml-ai/pi-worker](https://github.com/qaml-ai/pi-worker?ref=githubawesome.com)

No. 5 - Entroly

![](https://githubawesome.com/content/images/2026/03/image-279.png)

The developer behind Entroly was burning 200 bucks a month just sending useless boilerplate code to their models. So they wrote a context optimizer in Rust. Instead of dumping whole files into your prompt, it uses token budgeting and entropy scoring to strip out the junk before it even hits the API. It supposedly cuts token costs by almost 80 percent and adds less than 10 milliseconds of latency.

[https://github.com/juyterman1000/entroly](https://github.com/juyterman1000/entroly?ref=githubawesome.com)

No. 6 - rsloop

![](https://githubawesome.com/content/images/2026/03/image-280.png)

Uvloop is the standard choice for speeding up async Python, but it doesn't run on Windows. Rsloop does. It's a new asyncio event loop written in Rust, drop-in compatible with existing code, with strong p99 latency numbers for API servers and native Windows support out of the box. If you're running async Python backends on Windows and uvloop hasn't been an option, this is worth benchmarking.

[https://github.com/RustedBytes/rsloop](https://github.com/RustedBytes/rsloop?ref=githubawesome.com)

No. 7 - GoldenMatch

![](https://githubawesome.com/content/images/2026/03/image-281.png)

Entity resolution at scale is a genuinely hard problem. GoldenMatch makes it look straightforward. It uses a three-tier approach: fast fuzzy logic handles the obvious matches, and only the genuinely ambiguous edge cases get sent to GPT-4o-mini as a tiebreaker. The result is 97% F1 accuracy on 100,000 messy records in 13 seconds, at a cost that amounts to pennies per run.

[https://github.com/benzsevern/goldenmatch](https://github.com/benzsevern/goldenmatch?ref=githubawesome.com)

No. 8 - ps2-llm

![](https://githubawesome.com/content/images/2026/03/image-282.png)

Someone ran a large language model on a PlayStation 2. The PS2 has 32MB of RAM, which is obviously nowhere near enough to load a model. The solution was a custom inference engine that streams weights directly from the CD-ROM drive, matrix by matrix, as needed. It's slow. It works. It absolutely did not need to exist, and someone built it anyway.

[https://github.com/xaskasdf/ps2-llm](https://github.com/xaskasdf/ps2-llm?ref=githubawesome.com)

No. 9 - Banish

![](https://githubawesome.com/content/images/2026/03/image-283.png)

Writing complex state machines in Rust usually means deeply nested match statements that are hard to follow and harder to aintain. Banish is a procedural macro that lets you define states and transition rules declaratively instead. It uses a fixed-point looping model, where a state keeps re-evaluating its rules until nothing fires before moving on. Zero runtime overhead, compiles down to pure Rust.

[https://github.com/LoganFlaherty/banish](https://github.com/LoganFlaherty/banish?ref=githubawesome.com)

No. 10 - Batear

![](https://githubawesome.com/content/images/2026/03/image-284.png)

Batear is a drone detection system that runs on a $15 ESP32 microcontroller with a single microphone. It uses Goertzel filters to identify the specific audio harmonics of drone rotors, runs 24/7 on battery, and triggers an alarm locally with no cloud connection involved.For $15 in hardware and some open-source firmware, that's a genuinely impressive capability.

[https://github.com/TN666/batear](https://github.com/TN666/batear?ref=githubawesome.com)

No. 11 - Orchestrator

![](https://githubawesome.com/content/images/2026/03/image-285.png)

Orchestrator gives you a tmux-style split-pane terminal dashboard for running multiple Claude sessions simultaneously. Instead of managing agents one at a time, you get a unified interface for assigning tasks across a coordinated swarm, all visible in one place. For anyone who's wanted to run parallel agents without the tab chaos, this is the direct solution.

[https://github.com/MatchaOnMuffins/orchestrator](https://github.com/MatchaOnMuffins/orchestrator?ref=githubawesome.com)

No. 12 - QueryPad

![](https://githubawesome.com/content/images/2026/03/image-286.png)

Opening Python or a spreadsheet app just to check a column in a large CSV is one of those small annoyances that adds up fast. QueryPad is a browser-based SQL playground powered by DuckDB. Drop in a CSV, JSON, or Parquet file and run SQL queries against it directly in the browser. Nothing uploads anywhere, everything processes locally, and DuckDB handles gigabytes without breaking a sweat.

[https://github.com/vericontext/querypad](https://github.com/vericontext/querypad?ref=githubawesome.com)

No. 13 - Inner Warden

![](https://githubawesome.com/content/images/2026/03/image-287.png)

Inner Warden is a self-hosted security agent for Linux and macOS written in Rust. It uses eBPF kernel programs to block attacks at wire speed, detects privilege escalation in real time, and deploys honeypots to misdirect attackers. No cloud dependencies, no data leaving the machine. Your server handling its own defense locally is a meaningful shift from alert-and-respond.

[https://github.com/InnerWarden/innerwarden](https://github.com/InnerWarden/innerwarden?ref=githubawesome.com)

No. 14 - NC Web

![](https://githubawesome.com/content/images/2026/03/image-288.png)

Someone saw a screenshot of Norton Commander and immediately rebuilt it in vanilla JavaScript for the browser. Dual-pane layout, iconic blue interface, F-key toolbar, the whole thing. It uses the Origin Private File System API for actual file management, so it's not just a visual gag. Pure 90s nostalgia that actually works in 2026.

[https://github.com/victorantos/NC](https://github.com/victorantos/NC?ref=githubawesome.com)

No. 15 - filenotes.nvim

![](https://githubawesome.com/content/images/2026/03/image-289.png)

Filenotes.nvim opens a floating Markdown scratchpad tied to whatever file you're currently editing in Neovim. It hashes the file path and saves the note to a hidden.notes folder at the project root, so your context and reminders stay organized without touching the actual code. Small plugin, genuine quality of life improvement for anyone who leaves themselves notes in comments.

[https://github.com/UsamaQaisrani/filenotes.nvim](https://github.com/UsamaQaisrani/filenotes.nvim?ref=githubawesome.com)

No. 16 - AI SDLC Scaffold

![](https://githubawesome.com/content/images/2026/03/image-290.png)

Most AI coding sessions skip straight to implementation. The planning phase gets ignored, and the architecture suffers for it. AI SDLC Scaffold is a template repository that forces the pre-work. Structured Markdown scaffolding for user stories, architecture decisions, and requirements, designed specifically to make your agent plan the system before writing any code.

[https://github.com/pangon/ai-sdlc-scaffold](https://github.com/pangon/ai-sdlc-scaffold?ref=githubawesome.com)

No. 17 - Capit

![](https://githubawesome.com/content/images/2026/03/image-291.png)

Running autonomous agents without spend limits is a reasonable way to return from lunch to a $50 API bill. Capit sits between your agents and your LLM providers, enforcing hard-coded budgets per agent and per provider. If something goes rogue or gets stuck in a loop, it cuts off before the damage compounds. For anyone running agents unattended, this should probably be in the stack already.

[https://github.com/day50-dev/capit](https://github.com/day50-dev/capit?ref=githubawesome.com)

No. 18 - MakhalReader

![](https://githubawesome.com/content/images/2026/03/image-292.png)

500 unread RSS items every morning is not a reading habit, it's a backlog. MakhalReader parses full-text feeds and runs every article through a local LLM like Ollama, scoring each one from 1 to 10 based on your actual interests. Clickbait listicles sink, high-signal engineering posts surface. The tagline is "an RSS reader that thinks before you do." Hard to argue with that.

[https://github.com/Tutanka01/makhalReader](https://github.com/Tutanka01/makhalReader?ref=githubawesome.com)

No. 19 - VideoZero Skills

![](https://githubawesome.com/content/images/2026/03/image-293.png)

Most AI agents can write code. VideoZero Skills lets them animate it. It's a toolkit of agentic skills built specifically to give AI coding agents programmatic control over the Motion Canvas engine. Your agent can write the animation code, render text and shapes, and output finished code-visualization videos without any manual intervention.

[https://github.com/VideoZero/skills](https://github.com/VideoZero/skills?ref=githubawesome.com)

No. 20 - Woti

![](https://githubawesome.com/content/images/2026/03/image-294.png)

Scheduling across five time zones usually means opening three different websites and doing mental arithmetic. Woti is a terminal UI built in Rust that shows an interactive timeline of multiple time zones side by side. Scrub forward and backward to find the overlap window where everyone is actually awake. Fast, local, and solves the problem without leaving the terminal.

[https://github.com/aleris/woti](https://github.com/aleris/woti?ref=githubawesome.com)

No. 21 - Elastik

![](https://githubawesome.com/content/images/2026/03/image-295.png)

Elastik rethinks the AI agent and web interaction problem in under 200 lines of code. Instead of building a complex agentic UI, it treats the LLM purely as an untrusted HTTP client using the Model Context Protocol, forcing it to interact with a database, HTML frontend, and server through a properly isolated sandbox. It's a clean demonstration of applying web security principles to AI architecture.

[https://github.com/rangersui/Elastik](https://github.com/rangersui/Elastik?ref=githubawesome.com)

No. 22 - React Container Kit

![](https://githubawesome.com/content/images/2026/03/image-296.png)

Context provider boilerplate is one of those things every React project reinvents slightly differently. React Container Kit is a lightweight utility layer on top of unstated-next that gives you named containers, clean provider composition, and TypeScript helpers out of the box. Write it once, stop rewriting it everywhere. Small library, real reduction in friction across projects.

[https://github.com/harveyrandall/react-container-kit](https://github.com/harveyrandall/react-container-kit?ref=githubawesome.com)

No. 23 - Agent Password

![](https://githubawesome.com/content/images/2026/03/image-297.png)

Hardcoding API keys for local AI agents is an obvious security problem with no great solution until now. Agent Password is a local macOS password manager built specifically for AI workflows. Secrets live in an encrypted SQLite vault, and when an agent needs one, it requests access through Touch ID. Tap your fingerprint, the agent gets the key, nothing sits in plaintext.

[https://github.com/tartavull/agent-password](https://github.com/tartavull/agent-password?ref=githubawesome.com)

No. 24 - Nya AI

![](https://githubawesome.com/content/images/2026/03/image-298.png)

Nya AI is an open-source collaborative platform that puts AI chat, team workspaces, rich-text pages, cloud storage, and channels in one place. The practical difference from just using ChatGPT alongside your other tools: the AI can actually read your team's files and operate inside documents, rather than existing in a separate tab you copy-paste between.

[https://github.com/NitroRCr/nyaai](https://github.com/NitroRCr/nyaai?ref=githubawesome.com)

No. 25 - AI Scrum Master Template

![](https://githubawesome.com/content/images/2026/03/image-299.png)

AI Scrum Master Template turns a GitHub repo into a self-managing development pipeline using GitHub Actions and Claude. A Scrum Master agent reads feature requests, breaks them into Kanban tickets, and routes them to separate Planner, Developer, and Tester agents. The whole thing runs inside your existing issue tracker without any additional infrastructure.

[https://github.com/plusai-solutions/ai-scrum-master-template](https://github.com/plusai-solutions/ai-scrum-master-template?ref=githubawesome.com)

No. 26 - Rover

![](https://githubawesome.com/content/images/2026/03/image-300.png)

Most support chatbots answer questions. Rover just does the thing for you. Drop a single script tag into your web app and it embeds a live AI agent directly in the UI. Tell it to help you check out, and it takes over the DOM, navigates the page, clicks buttons, and fills out forms in real time. The gap between "here's a help article" and "I'll do it for you" is significant. Rover sits firmly on the useful side of it.

[https://github.com/rtrvr-ai/rover](https://github.com/rtrvr-ai/rover?ref=githubawesome.com)

No. 27 - CYCLE

![](https://githubawesome.com/content/images/2026/03/image-301.png)

Pomodoro works for some people. For everyone else, the 25-minute cutoff hits right in the middle of actual focus. Cycle flips it. Work for as long as you're genuinely in flow, hit stop when you're done, and it calculates a proportional rest break based on how long you actually worked. No arbitrary timer cutting you off, no guilt about going over. Simple idea, surprisingly well executed.

[https://github.com/saint-angels/CYCLE](https://github.com/saint-angels/CYCLE?ref=githubawesome.com)

No. 28 - OpenHarness

![](https://githubawesome.com/content/images/2026/03/image-302.png)

If the official Anthropic and OpenAI SDKs feel like too much framework for what you're actually trying to build, OpenHarness is worth a look. It's a TypeScript library on top of Vercel's AI SDK that gives you composable building blocks for agentic workflows without the overhead. Supports the AGENTS.md spec, subagent delegation, and auto-compaction for long conversations out of the box.

[https://github.com/MaxGfeller/open-harness](https://github.com/MaxGfeller/open-harness?ref=githubawesome.com)

No. 29 - Sift

![](https://githubawesome.com/content/images/2026/03/image-303.png)

A failing test suite that dumps 13,000 lines of logs into your agent's context is an expensive problem most people are just absorbing. Sift sits between your terminal and your agent, captures the output, groups repeated failures, and compresses it into a structured diagnosis. 200,000 tokens of raw logs down to 120, without losing the actual debug signal. The kind of tool that pays for itself immediately.

[https://github.com/bilalimamoglu/sift](https://github.com/bilalimamoglu/sift?ref=githubawesome.com)

No. 30 - Skill Lab

Writing agent skills is easy. Writing agent skills that actually trigger correctly is a different problem.Skill Lab is a Python CLI tool that runs 19 static checks on your SKILL.md files, validating structure, naming, and descriptions. It statically lints your skill files, which is fine. But the second half is what actually sold me. It uses Claude to auto-generate brutal edge-case prompts, then tests them against a live model to prove your skill actually activates in context.

![](https://githubawesome.com/content/images/2026/03/image-305.png)

[https://github.com/8ddieHu0314/Skill-Lab](https://github.com/8ddieHu0314/Skill-Lab?ref=githubawesome.com)