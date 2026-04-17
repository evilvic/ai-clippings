---
title: "Hacker News Show #2"
source: "https://githubawesome.com/hacker-news-show-2/"
author:
  - "[[GithubAwesome]]"
published: 2026-03-24
created: 2026-04-03
description: "The Show HN section has been on fire lately. 35 projects pulled straight from Hacker News.No. 1 - DD PhotosDD Photos is a self-hosted static photo gallery generator built with Go and SvelteKit. Parallel goroutines process hundreds of images in seconds, converting everything to optimized WebP and generating"
tags:
  - "clippings"
---
The Show HN section has been on fire lately. 35 projects pulled straight from Hacker News.

![](https://www.youtube.com/watch?v=ZndbgtdcbOI)

No. 1 - DD Photos

![](https://githubawesome.com/content/images/2026/03/image-339.png)

DD Photos is a self-hosted static photo gallery generator built with Go and SvelteKit. Parallel goroutines process hundreds of images in seconds, converting everything to optimized WebP and generating JSON indexes automatically. The output is a fully static SvelteKit site with a PhotoSwipe lightbox built in. No database, no server code, no login walls. Host it on S3 or Apache for next to nothing and send the link to whoever needs it.

[https://github.com/dougdonohoe/ddphotos](https://github.com/dougdonohoe/ddphotos?ref=githubawesome.com)

No. 2 - Threadprocs

![](https://githubawesome.com/content/images/2026/03/image-340.png)

Threadprocs is an experimental Linux project that lets multiple independent executables share a single virtual address space. The practical consequence is that you can pass raw C++ or Rust pointers between completely separate programs with zero-copy overhead. No serialization, no shared memory gymnastics, no IPC overhead. Just a pointer, passed directly.

[https://github.com/jer-irl/threadprocs](https://github.com/jer-irl/threadprocs?ref=githubawesome.com)

No. 3 - Git Surgeon

![](https://githubawesome.com/content/images/2026/03/image-341.png)

AI agents write a lot of code and commit it messily. Git Surgeon is built for exactly that problem. It's a set of Git primitives designed specifically for autonomous coding agents, giving them the tools to slice, amend, and organize commits cleanly as they work. The result is a repository history that doesn't look like a bot was in charge, even when one was.

[https://github.com/raine/git-surgeon](https://github.com/raine/git-surgeon?ref=githubawesome.com)

No. 4 - GrobPaint

![](https://githubawesome.com/content/images/2026/03/image-342.png)

Paint.NET doesn't run on macOS, so someone built the next best thing. GrobPaint is a lightweight image editor built with vanilla JavaScript and a Python pywebview backend. Layers, 16 blend modes, magic wand selection, native project saving, completely offline. No Electron, no subscription, no bloat. Exactly as described: somewhere between MS Paint and Paint.NET, running natively on macOS.

[https://github.com/groverburger/grobpaint](https://github.com/groverburger/grobpaint?ref=githubawesome.com)

No. 5 - Agent Kernel

![](https://githubawesome.com/content/images/2026/03/image-343.png)

Persistent agent memory usually implies a vector database and a weekend of setup. Agent Kernel is three markdown files and a Git repo. Clone it, point Claude Code or Cursor at it, and the agent figures out how to use it on its own. It maintains identity, tracks world state in a knowledge folder, and writes append-only daily session logs.

[https://github.com/oguzbilgic/agent-kernel](https://github.com/oguzbilgic/agent-kernel?ref=githubawesome.com)

No. 6 - Zsweep

![](https://githubawesome.com/content/images/2026/03/image-344.png)

Zsweep is Minesweeper rebuilt for people who think the original UI was the problem. Svelte, Vim keybindings, no Windows 95 chrome. Navigate the grid entirely from the keyboard, track metrics like 3BV/s, and play in time-attack mode designed around pure speed. If Monkeytype scratches a particular itch for you, this is the same energy applied to Minesweeper.

[https://github.com/oug-t/zsweep](https://github.com/oug-t/zsweep?ref=githubawesome.com)

No. 7 - AI Engineering From Scratch

![](https://githubawesome.com/content/images/2026/03/image-345.png)

AI Engineering From Scratch is an open-source curriculum with 230+ hands-on lessons across 20 phases. Linear algebra and neural networks from first principles, through to autonomous agent swarms, implemented in Python, Rust, and TypeScript. For anyone who's been building on top of AI and wants to actually understand what's underneath it, this is the curriculum worth blocking out time for.

[https://github.com/rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch?ref=githubawesome.com)

No. 8 - ContextD

![](https://githubawesome.com/content/images/2026/03/image-346.png)

ContextD runs silently in the background on macOS, taking a screenshot every 2 seconds, running local OCR on whatever changed, and saving the extracted text to SQLite. A local LLM like Claude Haiku progressively summarizes your activity as the day goes on. Everything gets exposed through a local HTTP API so other agents can query exactly what you've been working on at any point.

[https://github.com/thesophiaxu/contextd](https://github.com/thesophiaxu/contextd?ref=githubawesome.com)

No. 9 - ThermalMarky

![](https://githubawesome.com/content/images/2026/03/image-347.png)

Everyone has a cheap thermal printer sitting in a drawer after two uses. ThermalMarky is a lightweight Python web server that takes standard Markdown and translates it for thermal printers. Bold, headers, alignment, QR codes on the fly, WebUI included, Docker supported. Send it a Markdown file, get a receipt. Genuinely good reason to dig that printer back out.

[https://github.com/sadreck/ThermalMarky](https://github.com/sadreck/ThermalMarky?ref=githubawesome.com)

No. 10 - GOAL.md

![](https://githubawesome.com/content/images/2026/03/image-348.png)

GOAL.md is a markdown framework that lets an AI agent optimize your codebase overnight using an autoresearch loop inspired by Andrej Karpathy's work. Write a measurement script, whether that's test coverage, API reliability, or something custom, and the agent runs a modify-verify-retain-or-discard loop against your score until you wake up. Fifty commits of optimized code by morning.

[https://github.com/jmilinovich/goal-md](https://github.com/jmilinovich/goal-md?ref=githubawesome.com)

No. 11 - Crack

![](https://githubawesome.com/content/images/2026/03/image-349.png)

Crack taps into the undocumented lid angle sensor on modern MacBooks and maps the opening angle to a creaking door sound in real time. Open the lid slowly, get a long horrifying squeak. Slam it shut, get the full effect. Completely useless, technically impressive, guaranteed to clear out a coffee shop. One of the better ways anyone has spent a weekend.

[https://github.com/ronreiter/crack](https://github.com/ronreiter/crack?ref=githubawesome.com)

No. 12 - Agent-IM

![](https://githubawesome.com/content/images/2026/03/image-350.png)

Copying context between multiple Claude Code and Codex sessions manually is one of those problems that shouldn't still exist. Agent-IM is a minimalist chat room system for AI agents built on an MCP server. Agents create a room, invite each other, define their roles, and communicate directly to collaborate on a problem.

[https://github.com/LinklyAI/agent-im](https://github.com/LinklyAI/agent-im?ref=githubawesome.com)

No. 13 - AutoPrompter

![](https://githubawesome.com/content/images/2026/03/image-351.png)

Writing system prompts by intuition and hoping they hold up in production is how most people do it. AutoPrompter makes it an engineering problem instead. It runs iterative tests against multiple models, measures function-calling accuracy, and automatically suggests optimizations based on what actually performs better. Prompt engineering that produces evidence instead of opinions.

[https://github.com/gauravvij/autoprompter](https://github.com/gauravvij/autoprompter?ref=githubawesome.com)

No. 14 - MCP-Scan

![](https://githubawesome.com/content/images/2026/03/image-352.png)

Most developers set up MCP configs once and never look at them again. mcp-scan audits yours. It checks for hardcoded API keys, flags overly broad filesystem permissions, and detects typosquatted malicious NPM packages in your server arguments. If you're running Cursor or Claude Desktop with MCP tools and haven't audited your config, this should probably be the next thing you run.

[https://github.com/rodolfboctor/mcp-scan](https://github.com/rodolfboctor/mcp-scan?ref=githubawesome.com)

No. 15 - M33mu

![](https://githubawesome.com/content/images/2026/03/image-353.png)

M33mu is a full ARMv8-M Cortex-M33 emulator written in C, built for firmware developers who want to debug embedded systems without touching physical hardware. TrustZone awareness, built-in GDB remote server, terminal UI, and execution recording for reverse-stepping through firmware bugs. Step backward through a crash to find exactly where things went wrong.

[https://github.com/danielinux/m33mu](https://github.com/danielinux/m33mu?ref=githubawesome.com)

No. 16 - Z1

![](https://githubawesome.com/content/images/2026/03/image-354.png)

Z1 connects Claude directly to your live browser environment so your agent can interact with a running React app instead of just editing files blindly. It modifies local files on the fly and uses Git branches to track changes as it works. The feedback loop between AI-generated UI and the actual running application closes without you manually switching context. Agentic UI generation that actually knows what it's looking at.

[https://github.com/thomscoder/z1](https://github.com/thomscoder/z1?ref=githubawesome.com)

No. 17 - Refrax

![](https://githubawesome.com/content/images/2026/03/image-355.png)

Someone wanted Arc's tab duplication without the memory cost, so they built a new browser. Refrax uses an undocumented private macOS class called CAPortalLayer to mirror the GPU memory of a single web page across multiple windows. Hundreds of live-updating tabs, RAM footprint of one. The engineering here is genuinely impressive.

[https://refrax.website/](https://refrax.website/?ref=githubawesome.com)

No. 18 - FlowState

![](https://githubawesome.com/content/images/2026/03/image-356.png)

FlowState is Agent Kernel's core idea packaged as an MCP server. Connect it to Claude Code and your agent retains memory about your project architecture, your coding preferences, and outstanding bugs across sessions. Pick up on Monday exactly where Friday left off, without spending the first twenty minutes re-explaining the codebase. Persistent context that travels with the project.

[https://github.com/dialectforge/FlowStateV1.1](https://github.com/dialectforge/FlowStateV1.1?ref=githubawesome.com)

No. 19 - Mamba-rs

![](https://githubawesome.com/content/images/2026/03/image-357.png)

Mamba-rs is a full Mamba State Space Model implementation written in Rust with custom CUDA kernels. Inference and full backward-pass BPTT training, no Python anywhere in the stack. For anyone who wants to experiment with Mamba architecture at the metal level without the overhead of a Python ML framework, this is the starting point.

[https://github.com/silvermpx/mamba-rs](https://github.com/silvermpx/mamba-rs?ref=githubawesome.com)

No. 20 - Meow-SSH

![](https://githubawesome.com/content/images/2026/03/image-358.png)

Most SSH config files are a graveyard of IP addresses nobody remembers and keys nobody can locate. Meow-SSH is a lightweight terminal UI for managing SSH connections, switching keys, and jumping into remote environments without digging through config files. Fast, organized, and wrapped in a cat-themed aesthetic that makes it considerably more enjoyable than it has any right to be.

[https://github.com/abhishekgahlot2/meow-ssh](https://github.com/abhishekgahlot2/meow-ssh?ref=githubawesome.com)

No. 21 - Jensenify-MCP

![](https://githubawesome.com/content/images/2026/03/image-359.png)

Jensenify-MCP injects the complete texts of Homer, Shakespeare, Tolstoy, and the King James Bible into every single AI tool call. 2.9 million tokens of classic literature loaded into context so your coding agent has "deep humanistic grounding" when it fixes a null pointer exception. The creator acknowledges it costs a fortune in API tokens. That's the joke, and also entirely the point.

[https://github.com/kenm47/jensenify-mcp](https://github.com/kenm47/jensenify-mcp?ref=githubawesome.com)

No. 22 - Mnesis

![](https://githubawesome.com/content/images/2026/03/image-360.png)

Mnesis is a lightweight Python library for state and memory management in backend applications. Clean API for persisting and recalling data structures without rolling your own solution or pulling in something heavier than the problem warrants. Straightforward utility that fills a gap Python's standard library leaves open.

[https://github.com/Lucenor/mnesis](https://github.com/Lucenor/mnesis?ref=githubawesome.com)

No. 23 - Mnemo

![](https://githubawesome.com/content/images/2026/03/image-361.png)

Switching between agent frameworks usually means losing everything the agent learned in the previous one. Mnemo is a local-first CLI that serializes agent memory into a normalized JSON schema, diffs snapshots to show exactly what changed between sessions, and migrates memories between backends like Mem0 and Letta.

[https://github.com/joshndala/mnemo-agent](https://github.com/joshndala/mnemo-agent?ref=githubawesome.com)

No. 24 - ez-stack

![](https://githubawesome.com/content/images/2026/03/image-362.png)

Stacked PRs are one of those workflows that feels impossibly messy to manage manually after the first rebase goes wrong. Ez-stack handles the orchestration using standard git and gh commands you already know, with metadata stored in a simple JSON file. No custom Git internals, no new mental model to learn. Clean stacked PR workflow without replacing the tools you already use.

[https://github.com/rohoswagger/ez-stack](https://github.com/rohoswagger/ez-stack?ref=githubawesome.com)

No. 25 - Samuel (Reading AI Agent)

![](https://githubawesome.com/content/images/2026/03/image-363.png)

Samuel is a fully autonomous reading agent built on the OpenClaw framework with real-time voice mode. It reads your local Apple Books, summarizes chapters, recites context, and turns pages autonomously using screen vision. The language learning use case is the interesting one: run it while watching a foreign film and it provides real-time context from what it sees and hears.

[https://github.com/sambuild04/reading-ai-agent](https://github.com/sambuild04/reading-ai-agent?ref=githubawesome.com)

No. 26 - Revise.io

![](https://githubawesome.com/content/images/2026/03/image-364.png)

Revise.io is a collaborative document editor with built-in revision history and Git-style visual diffs for writing. The useful part is the integrated AI proofreader that works against rules you define yourself. Tell it to enforce APA 7 formatting or avoid exclamation points, and it holds to that standard consistently across every draft. Google Docs with version control and a style guide that actually sticks.

[https://revise.io/](https://revise.io/?ref=githubawesome.com)

No. 27 - Smriti

![](https://githubawesome.com/content/images/2026/03/image-365.png)

Smriti treats agent memory the way Git treats code. Instead of relying on chat history that breaks down when you change direction, it enforces clean checkpoints at the data layer. Fork execution paths, switch models, compare decisions across branches, all without re-explaining the project context from scratch. The name means memory in Sanskrit. The implementation earns it.

[https://github.com/himanshudongre/smriti](https://github.com/himanshudongre/smriti?ref=githubawesome.com)

No. 28 - Wireframed.js

![](https://githubawesome.com/content/images/2026/03/image-366.png)

Wireframed.js converts your live, fully-styled HTML into a hand-drawn wireframe aesthetic with a single script drop. No rebuilding the prototype in Figma, no stripping out styles manually. The functional HTML stays functional, it just looks like a sketch. Clients focus on the layout and flow instead of arguing about button colors. The fastest path from working prototype to client-ready mockup.

[https://github.com/Lywald/Wireframed.js](https://github.com/Lywald/Wireframed.js?ref=githubawesome.com)

No. 29 - Brand Toolkit

![](https://githubawesome.com/content/images/2026/03/image-367.png)

Brand Toolkit is a Claude Code plugin that packages real expert frameworks directly into runnable skills. Donald Miller's StoryBrand, April Dunford's positioning methodology, and a built-in anti-slop checker that flags banned corporate buzzwords like "synergy" and "empower" before they make it into your copy.

[https://github.com/jgerton/brand-toolkit](https://github.com/jgerton/brand-toolkit?ref=githubawesome.com)

No. 30 - DockAutoHide

![](https://githubawesome.com/content/images/2026/03/image-368.png)

DockAutoHide watches your screen and toggles Dock auto-hide only when a window actually overlaps it. Dock stays visible when you need it, disappears when something bumps into it, reappears when the coast is clear. No manual toggling, no permanently hiding it, no wasted screen real estate. The kind of feature that feels obvious in hindsight and should have shipped with macOS years ago.

[https://github.com/nshcr/DockAutoHide](https://github.com/nshcr/DockAutoHide?ref=githubawesome.com)

No. 31 - Codex Claude Bridge

![](https://githubawesome.com/content/images/2026/03/image-369.png)

Claude Code and Codex are both strong tools that have no way to talk to each other. This project fixes that. It's a bidirectional bridge using Claude Code Channels and MCP tool calls to route messages between the two agents in real time, with a web UI to watch the conversation unfold. Anthropic and OpenAI models debating and coding together in your terminal.

[https://github.com/abhishekgahlot2/codex-claude-bridge](https://github.com/abhishekgahlot2/codex-claude-bridge?ref=githubawesome.com)

No. 32 - Wet

![](https://githubawesome.com/content/images/2026/03/image-370.png)

Long Claude Code sessions hit a wall when the context window fills up. Wet fixes that without you having to intervene. It's a Go proxy that sits between Claude Code and the Anthropic API, exposing hidden endpoints that let Claude profile and optimize its own context window. When token count gets too heavy, the agent pauses, compresses older messages, prunes irrelevant tool outputs, and restructures its working memory before the next request goes out.

[https://github.com/buildoak/wet](https://github.com/buildoak/wet?ref=githubawesome.com)

No. 33 - CellState

![](https://githubawesome.com/content/images/2026/03/image-371.png)

Anthropic rewrote Claude Code's terminal renderer because Ink was causing screen flicker. Nathan Cannon read that post and turned the approach into a standalone library. CellState runs purely inline instead. It uses a custom React reconciler and double-buffered rendering to diff at the cell level, calculating exactly which characters changed and only emitting escape sequences for those specific cells.

[https://github.com/nathan-cannon/cellstate](https://github.com/nathan-cannon/cellstate?ref=githubawesome.com)

No. 34 - Skill (by Emil Kowalski)

![](https://githubawesome.com/content/images/2026/03/image-372.png)

Emil Kowalski is one of the more respected voices in design engineering, known specifically for his work on animations and UI craft. He compiled his entire body of writing on animations, design, and frontend performance into a single installable AI skill. Run npx skills add emilkowalski/skill and your Claude or Cursor agent picks up that sensibility immediately.

[https://github.com/emilkowalski/skill](https://github.com/emilkowalski/skill?ref=githubawesome.com)

No. 35 - claudebox

![](https://githubawesome.com/content/images/2026/03/image-373.png)

API token costs add up fast when you're building and testing AI tools all day. Claudebox runs Claude Code inside a sandboxed Docker container, but authenticates using your existing $20 Claude subscription instead of a developer API key. It then exposes a fully OpenAI-compatible API on localhost, so any tool, framework, or agent that can hit an OpenAI endpoint can use your flat-rate subscription as the backend.

[https://github.com/ArmanJR/claudebox](https://github.com/ArmanJR/claudebox?ref=githubawesome.com)