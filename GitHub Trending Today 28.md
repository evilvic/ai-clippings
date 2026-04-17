---
title: "GitHub Trending Today #28"
source: "https://githubawesome.com/github-trending-today-28/"
author:
  - "[[GithubAwesome]]"
published: 2026-03-23
created: 2026-04-03
description: "This is GitHub Trending Today, episode number 28. We have tracked down 33 repositories trending right now on GitHub.No. 1 - ZerobootDocker containers are safer than host access but slow to spin up. Zeroboot splits the difference. It uses Firecracker microVMs and KVM copy-on-write memory forking to spawn"
tags:
  - "clippings"
---
This is GitHub Trending Today, episode number 28. We have tracked down 33 repositories trending right now on GitHub.

![](https://www.youtube.com/watch?v=HI3IuextGpc)

No. 1 - Zeroboot

![](https://githubawesome.com/content/images/2026/03/image-306.png)

Docker containers are safer than host access but slow to spin up. Zeroboot splits the difference. It uses Firecracker microVMs and KVM copy-on-write memory forking to spawn fully isolated virtual machines in under one millisecond at 265 kilobytes of RAM per fork. Fast enough that the security tradeoff disappears. For anyone running AI agents that need genuine isolation without the startup penalty, this is the architecture worth paying attention to.

[https://github.com/zerobootdev/zeroboot](https://github.com/zerobootdev/zeroboot?ref=githubawesome.com)

No. 2 - Folio

![](https://githubawesome.com/content/images/2026/03/image-307.png)

PDF generation in Go is a genuinely painful problem. Most solutions are either abandoned libraries or a headless Chrome instance you don't want to maintain. Folio is a pure Go, zero-dependency PDF library with a full layout engine. HTML-to-PDF conversion, flexbox, tables, and digital signatures all built in. It also compiles to WebAssembly, so you can test layouts directly in the browser on their WASM playground before writing a line of server code.

[https://github.com/carlos7ags/folio](https://github.com/carlos7ags/folio?ref=githubawesome.com)

No. 3 - Autonovel

![](https://githubawesome.com/content/images/2026/03/image-308.png)

Autonovel from Nous Research takes a seed concept and outputs a print-ready PDF, ePub, and audiobook. The Hermes Agent runs a modify-evaluate-discard loop throughout: writing the draft, running an automated literary critic to fix repetition, dividing chapters, generating cover art, and voicing the final audiobook. The whole publishing pipeline in a single Python script.

[https://github.com/NousResearch/autonovel](https://github.com/NousResearch/autonovel?ref=githubawesome.com)

No. 4 - ASCII Studio

![](https://githubawesome.com/content/images/2026/03/image-309.png)

ASCII Studio takes a video file and converts it into character-based ASCII frames that play back smoothly in the browser. It's a TypeScript project, optimized for smooth sequential playback rather than just dumping static text files. Retro loading screens, hacker aesthetic demo reels, or just turning a movie clip into something ridiculous. Genuinely fun project with obvious creative applications.

[https://github.com/vansh-nagar/ascii-studio](https://github.com/vansh-nagar/ascii-studio?ref=githubawesome.com)

No. 5 - Kimodo

![](https://githubawesome.com/content/images/2026/03/image-310.png)

Kimodo is a kinematic motion diffusion model from NVIDIA's Spatial Intelligence Lab, trained on over 700 hours of motion capture data. Instead of purely text-prompted motion generation, you can lock specific joints in place as hard kinematic constraints and let the model generate fluid, realistic movement around them. For animation workflows where you need a character's hand on a specific surface or a foot planted at an exact point, that's a meaningful capability.

[https://github.com/nv-tlabs/kimodo](https://github.com/nv-tlabs/kimodo?ref=githubawesome.com)

No. 6 - 7/24 Office

![](https://githubawesome.com/content/images/2026/03/image-311.png)

7/24 Office is a self-evolving AI agent system in 3,500 lines of pure Python.26 built-in tools, MCP support, and a three-layer memory system. The part that matters most for unattended operation is the self-repair capability: when an agent hits a bug, it debugs its own logic and keeps running without human intervention.

[https://github.com/wangziqi06/724-office](https://github.com/wangziqi06/724-office?ref=githubawesome.com)

No. 7 - Mails

![](https://githubawesome.com/content/images/2026/03/image-312.png)

Autonomous agents that interact with the real world eventually need to handle email, and raw HTML email is not something you want to feed directly into a context window. Mails strips the formatting noise and gives agents a clean interface for parsing incoming messages, drafting replies, and managing communications programmatically. The missing inbox for your AI workforce.

[https://github.com/chekusu/mails](https://github.com/chekusu/mails?ref=githubawesome.com)

No. 8 - Memoria

![](https://githubawesome.com/content/images/2026/03/image-313.png)

Memoria bills itself as Git for AI agent memory, and the analogy holds up. It sits between your agent and its database, providing zero-copy branching, snapshots, and point-in-time rollbacks. Before a risky refactor, snapshot the memory state. If the agent hallucinates and goes sideways, one command rolls it back to exactly before things went wrong.

[https://github.com/matrixorigin/Memoria](https://github.com/matrixorigin/Memoria?ref=githubawesome.com)

No. 9 - Sonar

![](https://githubawesome.com/content/images/2026/03/image-314.png)

We all hate running complex lsof or netstat commands just to figure out what process is hogging port 3000. Sonar is a tiny, zero-dependency CLI that shows you everything listening on your localhost. It displays clear process names, Docker container info, and clickable URLs in a gorgeous table. And yes, it lets you instantly kill rogue processes with a single command.

[https://github.com/RasKrebs/sonar](https://github.com/RasKrebs/sonar?ref=githubawesome.com)

No. 10 - Chops

![](https://githubawesome.com/content/images/2026/03/image-315.png)

Anyone running Claude Code, Cursor, and Codex will notice that markdown files and prompt instructions scattered across their filesystem with no good way to manage them. Chops is a native macOS app built specifically for that problem. Browse, edit, and organize all your agent skills and custom instructions from one clean interface, without digging through dotfiles.

[https://github.com/Shpigford/chops](https://github.com/Shpigford/chops?ref=githubawesome.com)

No. 11 - Emulate

![](https://githubawesome.com/content/images/2026/03/image-316.png)

Testing against live third-party APIs in CI is slow, costs money, and breaks whenever the external service has a bad day. Emulate from Vercel Labs intercepts those requests and mocks the API behavior locally, built specifically for CI environments and no-network sandboxes. Test suites and agents run at full speed without touching an external server.

[https://github.com/vercel-labs/emulate](https://github.com/vercel-labs/emulate?ref=githubawesome.com)

No. 12 - Ghostling

![](https://githubawesome.com/content/images/2026/03/image-317.png)

The Ghostty team extracted the core of their terminal engine and rebuilt it as a minimum viable emulator in a single C file using Raylib for graphics. It's a direct demonstration of how to embed a GPU-accelerated terminal into any application or game engine without pulling in Electron or any other heavy framework. For anyone who's wanted a terminal inside their own software and didn't know where to start, this is the blueprint.

[https://github.com/ghostty-org/ghostling](https://github.com/ghostty-org/ghostling?ref=githubawesome.com)

No. 13 - My Brain Is Full Crew

![](https://githubawesome.com/content/images/2026/03/image-318.png)

A PhD student hit cognitive overload and automated their way out of it. The repository is a 10-agent Obsidian crew running on scheduled tasks. A Scribe, Postman, Sorter, and others handle email ingestion, inbox triage, broken markdown link repair, and health habit tracking autonomously. Built out of necessity rather than ambition, which usually means it actually works.

[https://github.com/gnekt/My-Brain-Is-Full-Crew](https://github.com/gnekt/My-Brain-Is-Full-Crew?ref=githubawesome.com)

No. 14 - Diffity

![](https://githubawesome.com/content/images/2026/03/image-319.png)

Code review on AI-generated diffs usually means pushing to GitHub just to get a readable view. Diffity runs locally inside any Git repo and opens a syntax-highlighted diff in the browser. Leave review comments on the diff, and the built-in Claude Code integration reads those comments and applies the fixes automatically. The full review loop without leaving your machine.

[https://github.com/kamranahmedse/diffity](https://github.com/kamranahmedse/diffity?ref=githubawesome.com)

No. 15 - Flash-MoE

![](https://githubawesome.com/content/images/2026/03/image-320.png)

Flash-MoE runs a 397-billion parameter model on a MacBook Pro by streaming 209 gigabytes of weights from SSD into RAM on demand, using techniques from Apple's LLM in a Flash paper. It hits 4.4 tokens per second on consumer hardware. That number matters less than what it proves: the memory ceiling for local AI is not where most people assumed it was.

[https://github.com/danveloper/flash-moe](https://github.com/danveloper/flash-moe?ref=githubawesome.com)

No. 16 - FilmKit

![](https://githubawesome.com/content/images/2026/03/image-321.png)

FilmKit connects to Fujifilm X-series cameras directly in the browser using WebUSB, then uses the camera's own internal processor to convert RAW files to JPEG. No desktop software, no installation, no third-party conversion algorithm approximating what the camera would have done. The camera does the conversion itself, in the browser, at full speed.

[https://github.com/eggricesoy/filmkit](https://github.com/eggricesoy/filmkit?ref=githubawesome.com)

No. 17 - Modly

![](https://githubawesome.com/content/images/2026/03/image-322.png)

Modly is a local desktop app that runs image-to-3D mesh generation entirely on your own GPU using the Hunyuan3D 2 Mini model. No cloud credits, no per-generation costs, no images leaving your machine. Drop in an image, get a detailed 3D asset out. For anyone experimenting with 3D generation who doesn't want to burn through API budget to do it.

[https://github.com/lightningpixel/modly](https://github.com/lightningpixel/modly?ref=githubawesome.com)

No. 18 - 0DIN Scanner

![](https://githubawesome.com/content/images/2026/03/image-323.png)

Mozilla is stepping into the AI security ring with the 0DIN Scanner! As AI agents get more autonomy, ensuring they are secure from prompt injections and jailbreaks is critical. Built on top of the open-source GARAK framework, this is a beautiful, enterprise-grade vulnerability management platform specifically built for generative AI. It gives you a graphical UX, automated scheduling, and a proprietary probe library to actively red-team your own LLM applications!

[https://github.com/0din-ai/ai-scanner](https://github.com/0din-ai/ai-scanner?ref=githubawesome.com)

No. 19 - LLM Circuit Finder

![](https://githubawesome.com/content/images/2026/03/image-324.png)

No retraining, no fine-tuning, no additional parameters. Just duplicate three specific layers during the forward pass and route the hidden states through the same reasoning circuit twice. That simple intervention pushed a 24-billion parameter model's logical deduction score from 0.22 to 0.76. The mechanistic interpretability angle is what makes this genuinely interesting beyond the benchmark number.

[https://github.com/alainnothere/llm-circuit-finder](https://github.com/alainnothere/llm-circuit-finder?ref=githubawesome.com)

No. 20 - Oxyde

![](https://githubawesome.com/content/images/2026/03/image-325.png)

Oxyde is an async Python ORM with a Rust core underneath, built around Pydantic v2 as a first-class citizen rather than an afterthought. You get Django-style objects.filter( query syntax, strict Pydantic validation on every model, and the performance overhead of Rust instead of Python handling the heavy lifting. For Python backend developers who've accepted slow ORM performance as a fact of life, this is worth benchmarking against your current stack.

[https://github.com/mr-fatalyst/oxyde](https://github.com/mr-fatalyst/oxyde?ref=githubawesome.com)

No. 21 - ReactMotion

![](https://githubawesome.com/content/images/2026/03/image-326.png)

Most AI avatars are static while you're talking. ReactMotion fixes the part that makes them feel uncanny. It generates listener motions in real time based on the acoustic features of incoming speech. Nods, weight shifts, subtle facial reactions, all driven by how the voice actually sounds rather than canned animations on a timer.

[https://github.com/awakening-ai/ReactMotion](https://github.com/awakening-ai/ReactMotion?ref=githubawesome.com)

No. 22 - Context Gateway

![](https://githubawesome.com/content/images/2026/03/image-327.png)

Large codebases eat through context windows fast, and the token costs compound quickly on long sessions. Context Gateway sits between your agent and the LLM API, pre-computing conversation summaries in the background and compressing history intelligently as the session grows. The claim is 50% token reduction without losing critical semantic context.

[https://github.com/Compresr-ai/Context-Gateway](https://github.com/Compresr-ai/Context-Gateway?ref=githubawesome.com)

No. 23 - Claude Peers MCP

![](https://githubawesome.com/content/images/2026/03/image-328.png)

Claude-peers is an MCP server that lets multiple Claude Code instances on the same machine communicate directly with each other. One agent working on the frontend can ping the backend agent and ask what an endpoint is named, and the answer lands in its context window immediately. No copy-pasting between terminals, no human relaying messages between sessions.

[https://github.com/louislva/claude-peers-mcp](https://github.com/louislva/claude-peers-mcp?ref=githubawesome.com)

No. 24 - Crust

![](https://githubawesome.com/content/images/2026/03/image-329.png)

Go and Rust dominate CLI tooling for good reasons, but if TypeScript is your language, the startup overhead has always been a real tradeoff. Crust is a TypeScript-first CLI framework built natively on Bun, with composable modules and the startup speed that makes Bun worth using in the first place. Complex, modular command-line tools that boot instantly and feel native.

[https://github.com/chenxin-yan/crust](https://github.com/chenxin-yan/crust?ref=githubawesome.com)

No. 25 - Han

![](https://githubawesome.com/content/images/2026/03/image-330.png)

Han is a fully compiled, statically-typed programming language where every keyword is written in Korean Hangul. Not a toy. It compiles to native binaries through LLVM, has a Rust-based toolchain, and ships with an interpreter for fast iteration. The real argument it's making: there's no technical reason programming languages have to be built around English. Han is proof.

[https://github.com/xodn348/han](https://github.com/xodn348/han?ref=githubawesome.com)

No. 26 - SparkVSR

![](https://githubawesome.com/content/images/2026/03/image-331.png)

SparkVSR is a video super-resolution model that only needs you to do a fraction of the work. Manually enhance a handful of keyframes from a low-resolution or degraded video, and the model propagates those restored details across the entire clip automatically. Old film restoration, cinematic VFX, high-end upscaling, the use cases are obvious and the approach is smarter than brute-forcing every frame individually.

[https://github.com/taco-group/SparkVSR](https://github.com/taco-group/SparkVSR?ref=githubawesome.com)

No. 27 - GSAP AI Skills

![](https://githubawesome.com/content/images/2026/03/image-332.png)

GSAP is already the standard for web animation. Now there are official AI skills for it. GreenSock just dropped GSAP AI Skills, designed to load directly into Claude Code or Cursor. Instead of your agent producing static, lifeless UI, it gains the architectural knowledge to write complex scroll-triggered animations the way a senior frontend developer actually would.

[https://github.com/greensock/gsap-skills](https://github.com/greensock/gsap-skills?ref=githubawesome.com)

No. 28 - ClawTeam-OpenClaw

![](https://githubawesome.com/content/images/2026/03/image-333.png)

ClawTeam-OpenClaw is a fork of ClawTeam rebuilt specifically for the OpenClaw framework, adding a multi-agent swarm coordination layer on top. If you're already running OpenClaw, this gives you the infrastructure to orchestrate dozens of workers in parallel against large software engineering tasks without building the coordination layer yourself.

[https://github.com/win4r/ClawTeam-OpenClaw](https://github.com/win4r/ClawTeam-OpenClaw?ref=githubawesome.com)

No. 29 - Minutes

![](https://githubawesome.com/content/images/2026/03/image-334.png)

Minutes captures your meeting audio and generates formatted, actionable notes using local AI models. No cloud, no subscription, no frantic typing while trying to actually listen. Show up, have the conversation, read the summary afterward. The meeting that could have been an email can at least stop requiring your full attention.

[https://github.com/silverstein/minutes](https://github.com/silverstein/minutes?ref=githubawesome.com)

No. 30 - Unslop

![](https://githubawesome.com/content/images/2026/03/image-335.png)

Unslop is a lightweight utility from Matt Shumer that detects and rewrites AI slop. Feed it generated text full of "delve into," "fast-paced digital landscape," and "it's important to note," and it comes out the other side sounding like a person wrote it. Given that half the internet now reads like scrub 'AI slop' fever dream, the timing is good.

[https://github.com/mshumer/unslop](https://github.com/mshumer/unslop?ref=githubawesome.com)

No. 31 - Drift

![](https://githubawesome.com/content/images/2026/03/image-336.png)

Drift is a terminal screensaver written in Go that kicks in automatically when you go idle. Multiple ASCII and ANSI visual scenes, single go install command, one line in your.zshrc and it's set up permanently. Completely unnecessary, extremely satisfying. The kind of thing you install and then walk away from your desk on purpose.

[https://github.com/phlx0/drift](https://github.com/phlx0/drift?ref=githubawesome.com)

No. 32 - Clearly Markdown

![](https://githubawesome.com/content/images/2026/03/image-337.png)

Most Markdown editors add features until the writing gets buried. Clearly goes the other direction. Native macOS, no toolbars, no file trees, just typography and the document. Built with native performance in mind, it strips away all the bloated toolbars and complex file trees, leaving you with nothing but gorgeous typography and your thoughts.

[https://github.com/Shpigford/clearly](https://github.com/Shpigford/clearly?ref=githubawesome.com)

No. 33 - HTMX VSCode Toolkit

![](https://githubawesome.com/content/images/2026/03/image-338.png)

HTMX development in VS Code without this extension means memorizing attribute names or tabbing out to the docs constantly. The HTMX VSCode Toolkit adds deep intellisense, attribute auto-completion, and inline documentation for every HTMX tag directly in the editor. Small install, immediate quality of life improvement for anyone building hypermedia-driven apps.

[https://github.com/atoolz/htmx-vscode-toolkit](https://github.com/atoolz/htmx-vscode-toolkit?ref=githubawesome.com)