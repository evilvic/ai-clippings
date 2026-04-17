---
title: "GitHub Trending Today #22"
source: "https://githubawesome.com/github-trending-today-22/"
author:
  - "[[GithubAwesome]]"
published: 2026-02-10
created: 2026-04-03
description: "This is GitHub Trending Today #22, and I’ve got 30 open-source projects that are trending right now — AI projects, and developer utilities that are getting serious traction on GitHub.No.1Your open-source project is drowning in AI-generated garbage PRs from people who don't understand the code? Mitchell Hashimoto"
tags:
  - "clippings"
---
This is GitHub Trending Today #22, and I’ve got 30 open-source projects that are trending right now — AI projects, and developer utilities that are getting serious traction on GitHub.

![](https://www.youtube.com/watch?v=a1dVtpA9ES8)

No.1

![](https://githubawesome.com/content/images/2026/02/image-97.png)

Your open-source project is drowning in AI-generated garbage PRs from people who don't understand the code? Mitchell Hashimoto built Vouch to fix that. Explicit trust system where users have to be vouched for by trusted community members before they can contribute. Maintain a flat-file list of vouched and denounced users, GitHub Actions auto-close PRs from unvouched people, collaborators can vouch or denounce via issue comments.

[https://github.com/mitchellh/vouch](https://github.com/mitchellh/vouch?ref=githubawesome.com)

No.2

![](https://githubawesome.com/content/images/2026/02/image-98.png)

VisionClaw connects Meta Ray-Ban glasses to Gemini for real-time AI vision and voice interaction. Tap the AI button, speak, and Gemini sees what you're looking at through the camera. It can add items to lists, send messages, search the web, or control smart home devices by routing through the OpenClaw gateway. Streams camera at 1 FPS and bidirectional audio over WebSocket to Gemini Live API.

[https://github.com/sseanliu/VisionClaw](https://github.com/sseanliu/VisionClaw?ref=githubawesome.com)

No.3

![](https://githubawesome.com/content/images/2026/02/image-99.png)

Ralph Playbook is a guide for using Ralph effectively. Based on Geoff Huntley's research and videos, it covers a three-phase workflow: Jobs-to-be-Done → specs → planning mode → building mode. maintain 40-60% context utilization, use subagents for memory extension, steer with patterns and backpressure rather than instructions, let the agent self-correct through iteration. Includes specific file structures, bash scripts, and loop mechanics.

[https://github.com/ClaytonFarr/ralph-playbook](https://github.com/ClaytonFarr/ralph-playbook?ref=githubawesome.com)

No.4

![](https://githubawesome.com/content/images/2026/02/image-100.png)

Excalidraw MCP App is an MCP server that lets AI create Excalidraw diagrams. Ask Claude to draw architecture diagrams, flowcharts, or other visuals, and it opens an interactive Excalidraw editor. Claude can take screenshots of the diagram and iterate based on feedback. Diagrams render with pan/zoom, draw-on animations, and auto-centered text in shapes. Install via.mcpb bundle or build from source.

[https://github.com/antonpk1/excalidraw-mcp-app](https://github.com/antonpk1/excalidraw-mcp-app?ref=githubawesome.com)

No.5

![](https://githubawesome.com/content/images/2026/02/image-101.png)

x-research-skill is an MCP skill that lets Claude search and analyze X content. It breaks research questions into multiple search angles, scans tweets, follows threads, and reads linked content. Results are synthesized into a sourced markdown report organized by theme. Surfaces high-engagement tweets with metrics and deep-dives linked content. For questions where the relevant discussion is happening on Twitter rather than indexed web pages.

[https://github.com/rohunvora/x-research-skill](https://github.com/rohunvora/x-research-skill?ref=githubawesome.com)

No.6

![](https://githubawesome.com/content/images/2026/02/image-102.png)

Your team is running AI agents but every time someone new touches the project they start from scratch? OneContext just fixed that. Agent self-managed context layer that records your agent's full trajectory, shares it on Slack so anyone can talk to it, and lets anyone load that context to continue from the exact same point. Unified context for all AI agents across your team—no more starting over, no more lost progress.

[https://github.com/TheAgentContextLab/OneContext](https://github.com/TheAgentContextLab/OneContext?ref=githubawesome.com)

No.7

![](https://githubawesome.com/content/images/2026/02/image-103.png)

LocalGPT is a local AI assistant with persistent memory. It's a 27MB app that stores data in plain Markdown files. You can literally open a file called MEMORY.md and edit exactly what the AI knows about you. Includes a background daemon that runs scheduled tasks autonomously. You just write a task in the heartbeat file, and the AI wakes up on a schedule to do the work autonomously while you sleep.

[https://github.com/localgpt-app/localgpt](https://github.com/localgpt-app/localgpt?ref=githubawesome.com)

No.8

![](https://githubawesome.com/content/images/2026/02/image-104.png)

Ever fumbled with notes on camera, breaking eye contact to read your script? Textream is a macOS teleprompter app that highlights your script as you speak using local AI. It scrolls with you and pauses when you pause. Tap any word to jump ahead, pause and resume anytime, and adjust the size to fit your screen. It displays text in a small overlay right next to your webcam, so you read while looking directly at the camera.

[https://github.com/f/textream](https://github.com/f/textream?ref=githubawesome.com)

No.9

![](https://githubawesome.com/content/images/2026/02/image-105.png)

claude-code-controller provides programmatic control of Claude Code by implementing its internal filesystem protocol—the inbox and task file system that agents use to communicate.You can spawn Claude Code processes with their full toolset, run multi-agent workflows (like parallel security, performance, and style reviews), and create task queues that agents claim from.

[https://github.com/The-Vibe-Company/claude-code-controller](https://github.com/The-Vibe-Company/claude-code-controller?ref=githubawesome.com)

No.10

![](https://githubawesome.com/content/images/2026/02/image-106.png)

Boris Cherny created Claude Code. Someone extracted every productivity tip from his threads and turned it into a template repo. ChernyCode gives you the exact configuration Cherny and his team use. Memory files that persist context across sessions — CLAUDE.md for project-wide rules, personal ones for your preferences. Skills you invoke with slash commands for repeated workflows like commit-push-PR or finding technical debt.

[https://github.com/meleantonio/ChernyCode](https://github.com/meleantonio/ChernyCode?ref=githubawesome.com)

No.11

![](https://githubawesome.com/content/images/2026/02/image-107.png)

What happens to your password manager if you’re gone tomorrow? After concussions and a documentary about memory loss, a developer built ReMemory: a cryptographic dead man’s switch using Shamir’s Secret Sharing. You encrypt files, split the key into five shares, and give them to friends. Any three can recover it; two reveal zero information. Each share is an offline HTML file—no servers, installs, or internet—built to work even decades later.

[https://github.com/eljojo/rememory](https://github.com/eljojo/rememory?ref=githubawesome.com)

No.12

![](https://githubawesome.com/content/images/2026/02/image-108.png)

Emacs is forty years old. Its display engine is fifty thousand lines of C designed for text terminals in the nineteen-eighties. CPU-only rendering. No GPU. No video. No smooth animations. Your GPU sits idle while Emacs struggles with large images. Someone looked at this and said we're rebuilding the entire thing in Rust. Neomacs replaces that fifty thousand lines with four thousand lines of GPU-accelerated wgpu code.

[https://github.com/eval-exec/neomacs](https://github.com/eval-exec/neomacs?ref=githubawesome.com)

No.13

![](https://githubawesome.com/content/images/2026/02/image-109.png)

Wonder what AI sees when browsing the web? While your browser shows visual chaos—images, ads, menus—AI tools like Claude get clean markdown. A new browser called md-browse lets you see that view. It requests markdown-first from compatible sites like Vercel docs, and converts everything else using Turndown, stripping scripts, styles, and navigation to show just content.

[https://github.com/needle-tools/md-browse](https://github.com/needle-tools/md-browse?ref=githubawesome.com)

No.14

![](https://githubawesome.com/content/images/2026/02/image-110.png)

OpenClaw is cool but you need a Mac mini or a VPS to run it? MimiClaw just put the entire thing on a $5 chip. ESP32-S3 microcontroller, no Linux, no Node.js, just pure C—plug it into USB power and message it on Telegram. Full ReAct agent loop with Anthropic's Claude, tool use protocol for web search and time sync, local memory stored on flash in plain text markdown files.

[https://github.com/memovai/mimiclaw](https://github.com/memovai/mimiclaw?ref=githubawesome.com)

No.15

![](https://githubawesome.com/content/images/2026/02/image-111.png)

AI agents need to run code but giving them unrestricted access to your machine is a terrible idea. Matchlock is a CLI tool that runs ephemeral Linux VMs in under one second for sandboxed code execution. Full isolation, disposable filesystems, everything blocked by default. Here's the clever part — when your agent calls an API the real credentials get injected in-flight by a transparent MITM proxy.

[https://github.com/jingkaihe/matchlock](https://github.com/jingkaihe/matchlock?ref=githubawesome.com)

No.16

![](https://githubawesome.com/content/images/2026/02/image-112.png)

StrongDM's AI team has a rule: no human is allowed to look at the code. Not for code review, not for debugging, nothing. Their three-person team spends a thousand dollars a day per engineer on LLM tokens and ships production software they've literally never read. Attractor is the system that makes this possible and the repo has zero lines of code—just three markdown files with specs written in natural language.

[https://github.com/strongdm/attractor](https://github.com/strongdm/attractor?ref=githubawesome.com)

No.17

![](https://githubawesome.com/content/images/2026/02/image-113.png)

Napkin — a Claude Code skill that persists memory between sessions. The agent writes notes to.claude/napkin.md about what broke, how it was fixed, and patterns it noticed. Next session, it reads the file before starting work. Think of it as the agent keeping a running changelog of its own work—helpful if you're working on the same codebase across multiple days.

[https://github.com/blader/napkin](https://github.com/blader/napkin?ref=githubawesome.com)

No.18

![](https://githubawesome.com/content/images/2026/02/image-114.png)

CodePilot is a GUI wrapper for Claude Code.Instead of typing commands in the terminal, you get a chat interface with a file tree showing what Claude is accessing. You can click to approve permissions rather than typing "yes" repeatedly. Chat history saves to SQLite and persists between sessions. If you're constantly switching contexts or managing multiple conversations, the visual organization helps.

[https://github.com/op7418/CodePilot](https://github.com/op7418/CodePilot?ref=githubawesome.com)

No.19

![](https://githubawesome.com/content/images/2026/02/image-115.png)

Stop giving your AI agents your actual API keys. You are asking to get hacked. You need to look at Gondolin. It’s a new sandbox project from Armin Ronacher—the guy who created Flask. We all know we need to sandbox AI code, but Docker isn’t enough. Gondolin spins up a micro-VM in milliseconds, but here is the genius part: the network stack is written in JavaScript.

[https://github.com/earendil-works/gondolin](https://github.com/earendil-works/gondolin?ref=githubawesome.com)

No.20

![](https://githubawesome.com/content/images/2026/02/image-116.png)

TinyClaw connects Claude Code to WhatsApp for conversational AI responses. Scan a QR code, send messages from your phone, and get Claude responses with persistent context. Uses a file-based queue to process messages sequentially without race conditions. Runs in tmux with four panes: WhatsApp client, queue processor, heartbeat monitor, and logs. Heartbeat sends periodic checks to keep tasks alive.

[https://github.com/jlia0/tinyclaw](https://github.com/jlia0/tinyclaw?ref=githubawesome.com)

No.21

![](https://githubawesome.com/content/images/2026/02/image-117.png)

MaximizeToVirtualDesktop — brings macOS-style full-screen behavior to Windows 11. On macOS, clicking the green button sends a window to its own virtual desktop. Windows just makes the window bigger. This tool adds the macOS behavior: press Ctrl+Alt+Shift+X, and the window moves to a new virtual desktop. Close it or click again, and it returns to the original desktop. The temporary desktop disappears.

[https://github.com/shanselman/MaximizeToVirtualDesktop](https://github.com/shanselman/MaximizeToVirtualDesktop?ref=githubawesome.com)

No.22

![](https://githubawesome.com/content/images/2026/02/image-118.png)

If you are trying to bridge two servers—like a local machine behind a restrictive firewall and a remote VPS—you know that setting up an L2TP tunnel is usually a headache. You need to use VortexL2. It is a CLI tool that completely automates L2TPv3 Ethernet tunnels. It handles the connection, sets up HAProxy for high-performance port forwarding, and automatically creates Systemd services so your tunnel survives a reboot.

[https://github.com/iliya-Developer/VortexL2](https://github.com/iliya-Developer/VortexL2?ref=githubawesome.com)

No.23

![](https://githubawesome.com/content/images/2026/02/image-119.png)

Stik is a quick-capture note app. Hit a keyboard shortcut, type your thought, close. Under three seconds. Notes save as markdown files in your Documents folder. No account, no sync setup. If you already use iCloud or Dropbox, it works with those. On-device AI suggests folders. Semantic search finds notes by concept, not just keywords. You can pin notes as desktop stickies.

[https://github.com/0xMassi/stik\_app](https://github.com/0xMassi/stik_app?ref=githubawesome.com)

No.24

![](https://githubawesome.com/content/images/2026/02/image-120.png)

Crust is a security gateway that sits between your AI agent and the LLM. It intercepts tool calls before they execute and blocks dangerous ones based on rules you define.Write YAML rules to block access to.env files, shell history, SSH keys, or self-modification attempts. Hot reload lets you add rules without restarting. It scans both the conversation history and the LLM's response before executing commands.

[https://github.com/BakeLens/crust](https://github.com/BakeLens/crust?ref=githubawesome.com)

No.25

![](https://githubawesome.com/content/images/2026/02/image-121.png)

Blossom is a color picker that displays as a flower—eighteen petals arranged in two rings, sorted by hue. An arc slider controls saturation from bright to dark. It handles viewport edges automatically. If the picker opens too close to the bottom, it shifts up and repositions the slider. Written in vanilla JS with wrappers for React, Vue, Svelte, and Angular. Same API across all frameworks.Pass colors as hex, RGB, HSL, or objects.

[https://github.com/dayflow-js/BlossomColorPicker](https://github.com/dayflow-js/BlossomColorPicker?ref=githubawesome.com)

No.26

![](https://githubawesome.com/content/images/2026/02/image-122.png)

Picobot is a lightweight AI agent framework with persistent memory and tool calling.12MB binary that runs on 20MB RAM. Includes a skills system, Telegram integration, and heartbeat scheduler. Fast cold start compared to Python-based frameworks.Built-in tools: filesystem access, shell execution, web fetch, subagent spawning, skill creation. Skills are markdown files the agent can create and use.

[https://github.com/louisho5/picobot](https://github.com/louisho5/picobot?ref=githubawesome.com)

No.27

![](https://githubawesome.com/content/images/2026/02/image-123.png)

PaperBanana generates publication-quality diagrams from text descriptions.Give it a methodology description and caption, and it runs a five-agent pipeline: retrieves similar diagrams from 13 examples, generates a plan, refines for academic aesthetics, renders the image, then critiques and iterates.Works for methodology diagrams and statistical plots. Uses Google Gemini's free tier.

[https://github.com/llmsresearch/paperbanana](https://github.com/llmsresearch/paperbanana?ref=githubawesome.com)

No.28

![](https://githubawesome.com/content/images/2026/02/image-124.png)

Someone reverse-engineered a menu animation using pure CSS—no JavaScript. A circle expands from the top-left corner to fill the screen using clip-path with radius 1.42 × 100vmax. Works on any screen size since vmax uses the larger dimension. Includes a polygon clip-path for light ray effects. Pure HTML and CSS—click the button, circle grows, menu fades in.

[https://github.com/Momciloo/fun-with-clip-path](https://github.com/Momciloo/fun-with-clip-path?ref=githubawesome.com)

No.29

![](https://githubawesome.com/content/images/2026/02/image-125.png)

Claude Pulse is a terminal status bar that shows your Claude Code usage limits. It displays session usage (with a 5-hour countdown), weekly rolling total, and plan tier. Progress bars change color as you approach limits. Pulls data from Anthropic's OAuth API—the same numbers you'd see at claude. Caches responses for 30 seconds to avoid excessive API calls.Includes 10 themes if you care about aesthetics.

[https://github.com/NoobyGains/claude-pulse](https://github.com/NoobyGains/claude-pulse?ref=githubawesome.com)

No.30

![](https://githubawesome.com/content/images/2026/02/image-126.png)

You're using Obsidian Tasks but you need Apple Reminders for the notifications and Siri integration? Obsync just gave you two-way sync. Obsync is a Mac menu bar app that syncs Obsidian Tasks with Apple Reminders.Two-way sync with Obsidian as the source of truth. Tasks flow to Reminders automatically. Completions in Reminders write back to markdown files.Uses surgical edits instead of full line reconstruction.

[https://github.com/Santofer/Obsync](https://github.com/Santofer/Obsync?ref=githubawesome.com)