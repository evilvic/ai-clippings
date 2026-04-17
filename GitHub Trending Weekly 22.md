---
title: "GitHub Trending Weekly #22"
source: "https://githubawesome.com/github-trending-weekly-22/"
author:
  - "[[GithubAwesome]]"
published: 2026-02-06
created: 2026-04-03
description: "Welcome to GitHub Trending Weekly, episode 22! This week I’ve got 31 projects packed with tools and AI projects you won’t want to miss.No.1Edit Banana converts diagram images into editable DrawIO files. Upload a screenshot of a flowchart or architecture diagram, and it segments the"
tags:
  - "clippings"
---
Welcome to GitHub Trending Weekly, episode 22! This week I’ve got 31 projects packed with tools and AI projects you won’t want to miss.

![](https://www.youtube.com/watch?v=fRzCTvIwA2A)

No.1

![](https://githubawesome.com/content/images/2026/02/image-66.png)

Edit Banana converts diagram images into editable DrawIO files. Upload a screenshot of a flowchart or architecture diagram, and it segments the shapes, extracts text, and converts it into an editable format. The output preserves colors and layout—each box, arrow, and label becomes a separate draggable element in DrawIO. It handles dashed lines, curved connectors, and multi-layer diagrams that simpler conversion tools miss.

[https://github.com/BIT-DataLab/Edit-Banana](https://github.com/BIT-DataLab/Edit-Banana?ref=githubawesome.com)

No.2

![](https://githubawesome.com/content/images/2026/02/image-67.png)

OpenAI released their new Codex Desktop app for macOS only. Codex Desktop Rebuild extracts the Electron components from the official installer and recompiles the native modules to run on Windows and Linux. The rebuilt version includes the same interface as the Mac app: parallel agent threads, the visual planning dashboard, and git worktree isolation. running natively on your PC.

[https://github.com/Haleclipse/CodexDesktop-Rebuild](https://github.com/Haleclipse/CodexDesktop-Rebuild?ref=githubawesome.com)

No.3

![](https://githubawesome.com/content/images/2026/02/image-68.png)

agent-device is a CLI for controlling iOS and Android devices programmatically. It lets agents or scripts open apps, tap buttons, type text, scroll, and take screenshots. Uses accessibility APIs to inspect and interact with UI elements.Works with simulators and physical devices. Includes retry logic for flaky connections and stale UI snapshots. Supports multiple sessions, coordinate or reference-based targeting.

[https://github.com/callstackincubator/agent-device](https://github.com/callstackincubator/agent-device?ref=githubawesome.com)

No.4

![](https://githubawesome.com/content/images/2026/02/image-69.png)

Paying ten bucks a month for Suno when there's a free open-source model that runs on your own GPU? ACE-Step UI just gave you a Spotify-grade interface for ACE-Step 1.5. Full song generation with vocals and lyrics, instrumental mode, built-in audio editor, stem separation, custom parameters for everything. Create unlimited tracks, no queue limits, you own all the rights. Runs completely local — no monthly fees, ever.

[https://github.com/fspecii/ace-step-ui](https://github.com/fspecii/ace-step-ui?ref=githubawesome.com)

No.5

![](https://githubawesome.com/content/images/2026/02/image-70.png)

Claude Opus 4.6 wrote a C compiler in Rust. Full toolchain—preprocessor, parser, SSA optimizer, code generator, assembler, linker, debug symbols. It compiles the Linux kernel, PostgreSQL, FFmpeg, Redis, and QEMU. Supports x86, ARM, and RISC-V. Works as a drop-in GCC replacement for make and CMake. Nearly 4,000 commits, all AI-generated with no human editing.

[https://github.com/anthropics/claudes-c-compiler](https://github.com/anthropics/claudes-c-compiler?ref=githubawesome.com)

No.6

![](https://githubawesome.com/content/images/2026/02/image-71.png)

Step 3.5 Flash is a 196-billion-parameter model that only uses 11 billion parameters per token. This sparse activation design means it runs fast despite its size—you get the intelligence of a flagship model without the lag.The new multi-token prediction system generates code at 350 tokens per second by predicting four tokens simultaneously. It handles 256k context windows and works with text, images, and other input types.

[https://github.com/stepfun-ai/Step-3.5-Flash](https://github.com/stepfun-ai/Step-3.5-Flash?ref=githubawesome.com)

No.7

![](https://githubawesome.com/content/images/2026/02/image-72.png)

Prek is a Rust rewrite of pre-commit that runs faster and uses less disk space. It's a single binary with no dependencies that can run your existing pre-commit configs in parallel. Unlike pre-commit, which creates separate Python environments for each repository, Prek uses a shared toolchain. This means faster hook installation and less wasted disk space from duplicate tools. CPython and FastAPI have already switched to it.

[https://github.com/j178/prek](https://github.com/j178/prek?ref=githubawesome.com)

No.8

![](https://githubawesome.com/content/images/2026/02/image-73.png)

Firewall blocking your traffic? VPN not working? paqet just went around everything. paqet is a SOCKS5 proxy that bypasses firewalls using raw packet injection.Instead of using the OS network stack, it injects TCP packets directly via pcap, avoiding kernel-level connection tracking. Traffic is encrypted with KCP.Requires iptables rules to prevent the kernel from sending RST packets. Once configured, it's invisible to standard network monitoring.

[https://github.com/hanselime/paqet](https://github.com/hanselime/paqet?ref=githubawesome.com)

No.9

![](https://githubawesome.com/content/images/2026/02/image-74.png)

Karpathy said AI writes 80% of his code and he spends 20% reviewing it. Pro Workflow literally optimizes for that exact ratio. It's a Claude Code plugin with persistent SQLite memory — every correction you make gets stored and searched with full-text search. While Claude's thinking in one branch, you're coding in another. Works across thirty-two AI coding agents via SkillKit translation.

[https://github.com/rohitg00/pro-workflow](https://github.com/rohitg00/pro-workflow?ref=githubawesome.com)

No.10

![](https://githubawesome.com/content/images/2026/02/image-75.png)

ClawRouter is a Smart LLM router for your OpenClaw agent that stops you from burning money. If it’s a basic question, it routes it to a cheap model like DeepSeek; if it’s complex code, it escalates to Claude Sonnet. It runs entirely locally, supports micropayments so you don't need to manage thirty different API keys, and finally cuts your inference bill by 80% without you lifting a finger.

[https://github.com/BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter?ref=githubawesome.com)

No.11

![](https://githubawesome.com/content/images/2026/02/image-76.png)

Cloudflare open-sourced Kumo, their component library built on Base UI. This means the accessibility features—keyboard navigation, focus management, ARIA attributes—are built into the components by default.The library is tree-shakeable and includes a semantic color token system. The repo includes an AGENTS.md file. This makes it easier for tools like Claude to generate code using Kumo components correctly.

[https://github.com/cloudflare/kumo](https://github.com/cloudflare/kumo?ref=githubawesome.com)

No.12

![](https://githubawesome.com/content/images/2026/02/image-77.png)

OpenViking is ByteDance's approach to organizing agent memory as a hierarchical filesystem instead of a flat vector database. This reduces token usage compared to loading everything upfront.The retrieval system searches directories recursively—it identifies the most relevant directory first, then explores its contents layer by layer. There's also a visualization tool for inspecting which contexts were retrieved during a task.

[https://github.com/volcengine/OpenViking](https://github.com/volcengine/OpenViking?ref=githubawesome.com)

No.13

![](https://githubawesome.com/content/images/2026/02/image-78.png)

Maestro is a macOS app for running multiple AI coding sessions in parallel. It manages up to 12 simultaneous sessions, each in its own terminal and git worktree. You can run different tasks (features, bug fixes, refactors) on separate branches with different models without conflicts.Includes a git graph view, MCP server for agent status reporting, and preset configurations. Works with any AI CLI tool.

[https://github.com/its-maestro-baby/maestro](https://github.com/its-maestro-baby/maestro?ref=githubawesome.com)

No.14

![](https://githubawesome.com/content/images/2026/02/image-79.png)

tgterm is a C project by antirez (the Redis creator) that lets you control your Mac terminal through Telegram. You connect a bot to your machine and send commands from your phone. perfect for casually interacting with agents, or just finishing that one last thing before bed. It uses SQLite to store state and supports basic screenshots. No SSH setup, VPN, or web dashboard required—just Telegram messages.

[https://github.com/antirez/tgterm](https://github.com/antirez/tgterm?ref=githubawesome.com)

No.15

![](https://githubawesome.com/content/images/2026/02/image-80.png)

You know that feeling when you type git diff and your terminal just vomits a wall of red and green at you? Yeah. I got tired of that.This is difi. It's basically a code review assistant that doesn't make you want to cry. Clean file tree on the left, your actual changes on the right. If you spot a bug while reviewing, you just press 'E'. It instantly opens Neovim and jumps your cursor to that exact line so you can fix it.

[https://github.com/oug-t/difi](https://github.com/oug-t/difi?ref=githubawesome.com)

No.16

![](https://githubawesome.com/content/images/2026/02/image-81.png)

Living behind a firewall that blocks half the internet? Yeah, VPNs don't always cut it anymore. paqctl is a censorship circumvention tool that runs Paqet and GFW-Knocker backends to tunnel traffic using raw sockets and KCP. You install it on a VPS and run both methods simultaneously. If one gets blocked, you can switch to the other. It provides a SOCKS5 proxy.

[https://github.com/SamNet-dev/paqctl](https://github.com/SamNet-dev/paqctl?ref=githubawesome.com)

No.17

![](https://githubawesome.com/content/images/2026/02/image-82.png)

Mission Control is a project management interface for coordinating multiple AI agents. You define agents in markdown files, assign tasks through a Kanban board, and the system dispatches them to OpenClaw sessions. Agents report when they finish tasks and can communicate with each other for coordination. There's a supervisor agent that reviews completed work. Agents can run on different machines and upload their output via API.

[https://github.com/crshdn/mission-control](https://github.com/crshdn/mission-control?ref=githubawesome.com)

No.18

![](https://githubawesome.com/content/images/2026/02/image-83.png)

Causal Forcing is a Tsinghua research project for real-time video generation on a single RTX 4090. It uses a three-stage distillation process to train diffusion models that can generate video frame-by-frame. Two model variants are available: frame-wise generation produces more dynamic motion, while chunk-wise generation prioritizes temporal consistency.

[https://github.com/thu-ml/Causal-Forcing](https://github.com/thu-ml/Causal-Forcing?ref=githubawesome.com)

No.19

![](https://githubawesome.com/content/images/2026/02/image-84.png)

BotMaker is a web interface for deploying chatbots. You select an AI provider (OpenAI, Anthropic, etc.) and a messaging platform (Telegram, Discord), and it creates an isolated Docker container for each bot with its own workspace and environment variables. The dashboard shows resource usage and lets you start, stop, or delete bots. It automatically cleans up unused containers.

[https://github.com/jgarzik/botmaker](https://github.com/jgarzik/botmaker?ref=githubawesome.com)

No.20

![](https://githubawesome.com/content/images/2026/02/image-85.png)

OpenHamClock is an open-source rebuild of HamClock, a popular ham radio dashboard tool. OpenHamClock displays satellite imagery, space weather data from NOAA, DX spots, band conditions, and POTA/SOTA activator locations on an interactive map. It updates every 30 seconds and includes eight map styles. It runs on Raspberry Pi, desktop environments, Docker, or cloud platforms like Railway.

[https://github.com/accius/openhamclock](https://github.com/accius/openhamclock?ref=githubawesome.com)

No.21

![](https://githubawesome.com/content/images/2026/02/image-86.png)

This tool converts scanned PDFs to EPUB format using PaddleOCR Layout Analysis API. It detects document structure—paragraphs, headers, images, and tables—and automatically splits the content into chapters based on heading hierarchy. It removes page numbers and running headers, embeds images, and includes checkpointing to resume interrupted conversions.

[https://github.com/jarodise/pdf2epub-paddle](https://github.com/jarodise/pdf2epub-paddle?ref=githubawesome.com)

No.22

![](https://githubawesome.com/content/images/2026/02/image-87.png)

OpenUsage is a menu bar app that displays usage data for AI coding tools in one place. It currently supports Cursor, Claude, and Codex, with plans to add Gemini and Copilot. It uses a plugin system—each provider is a JavaScript file that fetches usage data and renders it as progress bars. The app refreshes automatically every few minutes. It's built with Tauri and React, so it runs on multiple platforms.

[https://github.com/robinebers/openusage](https://github.com/robinebers/openusage?ref=githubawesome.com)

No.23

![](https://githubawesome.com/content/images/2026/02/image-88.png)

Skyll is an API that lets AI agents search for and retrieve skill files at runtime. Instead of pre-installing skills, agents can query the API for relevant SKILL.md files and inject them into context as needed. It aggregates skills from skills.sh and other sources, ranks results by relevance, and returns structured JSON. It caches responses to avoid GitHub rate limit issues. The API is available as both a REST endpoint and an MCP server.

[https://github.com/assafelovic/skyll](https://github.com/assafelovic/skyll?ref=githubawesome.com)

No.24

![](https://githubawesome.com/content/images/2026/02/image-89.png)

xfr is a network throughput testing tool with a graphical interface. It displays live bandwidth graphs instead of terminal output and includes a server dashboard for monitoring multiple tests simultaneously. It supports TCP, UDP, and QUIC protocols with built-in encryption. It also exports Prometheus metrics, offers multiple color themes, and lets you compare test results over time.

[https://github.com/lance0/xfr](https://github.com/lance0/xfr?ref=githubawesome.com)

No.25

![](https://githubawesome.com/content/images/2026/02/image-90.png)

NodeWarden is a Bitwarden-compatible password manager that runs on Cloudflare Workers. It requires no server maintenance and uses Cloudflare's free tier.You deploy it by setting a JWT secret, then use the official Bitwarden clients to connect to your instance. Passwords are end-to-end encrypted, and file attachments are stored in Cloudflare R2.

[https://github.com/shuaiplus/NodeWarden](https://github.com/shuaiplus/NodeWarden?ref=githubawesome.com)

No.26

![](https://githubawesome.com/content/images/2026/02/image-91.png)

voxtral.c is a C implementation of Mistral's 4-billion-parameter speech-to-text model with no external dependencies. You compile the C program, download the 9GB model file, and run transcription locally. It memory-maps model weights from disk for fast loading and streams decoded tokens to the terminal in real-time. You can pipe audio through ffmpeg or use the C API to integrate transcription into other applications.

[https://github.com/antirez/voxtral.c](https://github.com/antirez/voxtral.c?ref=githubawesome.com)

No.27

![](https://githubawesome.com/content/images/2026/02/image-92.png)

Foundry is an OpenClaw plugin that observes repetitive workflows and generates code to automate them. If you run the same sequence of commands multiple times, Foundry can create a tool that executes them as a single action. The system can modify its own codebase based on what it learns. It validates new code in a sandbox before deployment and tracks which automations work reliably.

[https://github.com/lekt9/openclaw-foundry](https://github.com/lekt9/openclaw-foundry?ref=githubawesome.com)

No.28

![](https://githubawesome.com/content/images/2026/02/image-93.png)

AutoFigure generates editable SVG diagrams from text descriptions of research methods. You input a methods section, and it produces a vector graphic you can modify. It uses an LLM to create the initial layout, applies SAM3 segmentation to identify components, removes backgrounds, and assembles the result into an SVG template with an embedded editor.

[https://github.com/ResearAI/AutoFigure-Edit](https://github.com/ResearAI/AutoFigure-Edit?ref=githubawesome.com)

No.29

![](https://githubawesome.com/content/images/2026/02/image-94.png)

Skill Scanner is a Cisco security tool that analyzes AI agent skills for vulnerabilities before deployment. It checks for prompt injection attacks, data exfiltration risks, and malicious code. It uses four detection methods: YARA pattern matching, behavioral analysis that traces data flows, LLM-based semantic analysis, and VirusTotal integration for binary scanning.

[https://github.com/cisco-ai-defense/skill-scanner](https://github.com/cisco-ai-defense/skill-scanner?ref=githubawesome.com)

No.30

![](https://githubawesome.com/content/images/2026/02/image-95.png)

Youtu-RAG is a retrieval system from Tencent that uses specialized agents for different data types. It supports PDFs, Excel files, and databases.The system includes separate agents for Text-to-SQL conversion, Excel analysis with Python execution, and metadata-based document filtering. It runs locally with MinIO storage and includes a web UI built without external dependencies.

[https://github.com/TencentCloudADP/youtu-rag](https://github.com/TencentCloudADP/youtu-rag?ref=githubawesome.com)

No.31

![](https://githubawesome.com/content/images/2026/02/image-96.png)

Itsytv is a macOS menu bar app for controlling Apple TV. It provides a floating remote interface with a d-pad, standard playback buttons, and keyboard shortcut support for navigation. It handles text input for search and passwords, displays now playing information with album art and progress bars, and shows an app grid with icons from the App Store.

[https://github.com/nickustinov/itsytv-macos](https://github.com/nickustinov/itsytv-macos?ref=githubawesome.com)