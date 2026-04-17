---
title: "Hacker News Show #3"
source: "https://githubawesome.com/hacker-news-show-3/"
author:
  - "[[GithubAwesome]]"
published: 2026-03-30
created: 2026-04-03
description: "This is Hacker News Show, episode three. 34 projects, all the best from this week's Show HN.No. 1 - TurboliteSQLite's portability is the appeal, but latency kills it the moment your data lives in the cloud. Turbolite is a SQLite Virtual File System written in Rust that serves"
tags:
  - "clippings"
---
This is Hacker News Show, episode three. 34 projects, all the best from this week's Show HN.

![](https://www.youtube.com/watch?v=zMKQjeBY69U)

No. 1 - Turbolite

![](https://githubawesome.com/content/images/2026/03/image-439.png)

SQLite's portability is the appeal, but latency kills it the moment your data lives in the cloud. Turbolite is a SQLite Virtual File System written in Rust that serves queries directly from S3 buckets. Zstd page-level compression and intelligent B-tree prefetching bring cold JOIN queries under 250 milliseconds over the network. Local database performance, cloud storage scale. The gap between the two just got a lot smaller.

[https://github.com/russellromney/turbolite](https://github.com/russellromney/turbolite?ref=githubawesome.com)

No. 2 - Quickbeam

![](https://githubawesome.com/content/images/2026/03/image-440.png)

Every Elixir stack eventually gets a Node.js process bolted on for JavaScript SSR, and it never feels clean. QuickBEAM fixes that by embedding a full JavaScript runtime directly inside the Erlang VM. JS environments run as native GenServer processes inside your OTP supervision trees. Elixir spawns isolated runtimes, sends messages, sets memory limits for untrusted code.

[https://github.com/elixir-volt/quickbeam](https://github.com/elixir-volt/quickbeam?ref=githubawesome.com)

No. 3 - DuckDB-HNSW-ACORN

![](https://githubawesome.com/content/images/2026/03/image-441.png)

Standard vector search with metadata filtering is a two-step problem: find the nearest neighbors, then filter, which means you're doing extra work on results you're going to discard anyway. DuckDB-HNSW-ACORN pushes the filtering directly into the HNSW traversal graph using the ACORN-1 algorithm. The metadata filter runs during the search rather than after it, which means faster queries and higher recall on filtered results.

[https://github.com/cigrainger/duckdb-hnsw-acorn](https://github.com/cigrainger/duckdb-hnsw-acorn?ref=githubawesome.com)

No. 4 - Paseo

![](https://githubawesome.com/content/images/2026/03/image-442.png)

Running autonomous agents means being tethered to your laptop to catch when something needs attention. Paseo connects to a local daemon on your machine and lets you monitor and control your agents from your phone, desktop, or terminal. Voice mode dictation, worktree support, and an encrypted remote relay, with your code staying on your own hardware the entire time.

[https://github.com/getpaseo/paseo](https://github.com/getpaseo/paseo?ref=githubawesome.com)

No. 5 - ClawMem

![](https://githubawesome.com/content/images/2026/03/image-443.png)

Claude Code starts every session without memory of what came before. ClawMem fixes that. It's a local memory context engine for Claude Code and OpenClaw that runs hybrid RAG retrieval on your GPU. Semantic search, cross-encoder reranking, and self-evolving memory notes all fused into a single SQLite vault. Your agents permanently remember your project architecture, coding preferences, and outstanding context across sessions.

[https://github.com/yoloshii/ClawMem](https://github.com/yoloshii/ClawMem?ref=githubawesome.com)

No. 6 - Lockpaw

![](https://githubawesome.com/content/images/2026/03/image-444.png)

Locking your Mac to step away and accidentally killing a long-running agent session is a specific kind of frustrating. Lockpaw is a 3.4MB native macOS app that drops a black privacy screen and blocks input without triggering sleep. Agents keep running, display stays dark, Touch ID brings it back instantly. The missing sleep mode for people running autonomous agents.

[https://github.com/sorkila/lockpaw](https://github.com/sorkila/lockpaw?ref=githubawesome.com)

No. 7 - Odyssey

![](https://githubawesome.com/content/images/2026/03/image-445.png)

Packaging AI agents for different environments usually means rewriting deployment logic for each one. Odyssey is a bundle-first agent runtime written in Rust that lets you define an agent once and run the same artifact across your local terminal, embedded SDKs, and shared runtime servers. Strict OS-level sandboxing included regardless of where it runs.

[https://github.com/liquidos-ai/Odyssey](https://github.com/liquidos-ai/Odyssey?ref=githubawesome.com)

No. 8 - Awesome-AutoResearch

![](https://githubawesome.com/content/images/2026/03/image-446.png)

Karpathy's autoresearch concept sparked a wave of community adaptations, and awesome-autoresearch curates all of them in one place. GPU kernel optimization, novel writing, codebase improvement, prompt engineering, the community has applied the endless loop structure to almost everything imaginable. If you want a map of where autonomous self-improvement research is actually heading in practice, this is the repository worth bookmarking.

[https://github.com/WecoAI/awesome-autoresearch](https://github.com/WecoAI/awesome-autoresearch?ref=githubawesome.com)

No. 9 - JulIDE

![](https://githubawesome.com/content/images/2026/03/image-447.png)

Julia developers have been stuck with general-purpose IDEs that weren't built with the language in mind. JulIDE is a dedicated Julia editor built with Tauri, React, and Rust. Full Language Server Protocol integration, a debugger, and inline execution, packaged into a 10-megabyte install. Purpose-built tooling for a language that deserved it a long time ago.

[https://github.com/sinisterMage/JulIde](https://github.com/sinisterMage/JulIde?ref=githubawesome.com)

No. 10 - Aerko

![](https://githubawesome.com/content/images/2026/03/image-448.png)

Aerko is a fitness web app built entirely with Vanilla JS and Native Web Components, no React, no Node modules, no framework overhead. Runs completely offline, stores health data locally encrypted with AES-GCM via IndexedDB. Fast, private, and your data never touches a server. "Most advanced fitness web app in history" is a bold claim, but the engineering decisions behind it are genuinely sound.

[https://github.com/SrPakura/AERKO\_PWA](https://github.com/SrPakura/AERKO_PWA?ref=githubawesome.com)

No. 11 - Druids

![](https://githubawesome.com/content/images/2026/03/image-449.png)

Druids is a reference architecture for building domain-specific AI skills for Claude Code. Installable skills designed to navigate complex design systems, execute visual iterations, and run regimen verifications autonomously. Less a finished product and more a masterclass in how to structure custom agent tooling properly.

[https://github.com/fulcrumresearch/druids](https://github.com/fulcrumresearch/druids?ref=githubawesome.com)

No. 12 - Foundry

![](https://githubawesome.com/content/images/2026/03/image-450.png)

Foundry is a CMS written in Go that uses Markdown files as the source of truth, no database required. API-first architecture, a clean admin UI, and a plugin system that extends both the backend and frontend. Blogs, documentation sites, landing pages, all driven by files you already own. For anyone who's over-engineered a content site with a database it didn't need, this is the simpler path.

[https://github.com/sphireinc/Foundry](https://github.com/sphireinc/Foundry?ref=githubawesome.com)

No. 13 - Outworked

![](https://githubawesome.com/content/images/2026/03/image-451.png)

Outworked gives every Claude Code agent its own pixel-art sprite sitting at a desk in an 8-bit office. You're the boss, they're the employees. Assign tasks, watch them walk around the screen and collaborate while they write your code. Completely unnecessary, deeply charming, and somehow makes waiting for an agent to finish feel significantly more entertaining.

[https://github.com/outworked/outworked](https://github.com/outworked/outworked?ref=githubawesome.com)

No. 14 - pgsemantic

![](https://githubawesome.com/content/images/2026/03/image-452.png)

Adding semantic search to an existing PostgreSQL database usually means schema changes, new infrastructure, or migrating your data somewhere else. Pgsemantic skips all of that. Install it, point it at your database, pick a text column, and it syncs rows and generates embeddings in the background without touching your schema. Search gets exposed natively to AI agents as well.

[https://github.com/varmabudharaju/pgsemantic](https://github.com/varmabudharaju/pgsemantic?ref=githubawesome.com)

No. 15 - Elato Local

![](https://githubawesome.com/content/images/2026/03/image-453.png)

Elato Local runs real-time conversational AI with voice cloning entirely on Apple Silicon, nothing sent to the cloud. An ESP32 microcontroller connects via WebSocket transport, turning cheap hardware into a responsive multilingual AI companion running off your local models. For anyone who's wanted to build a physical AI device without handing every conversation to a cloud provider, this is the open-source foundation worth building on.

[https://github.com/akdeb/Elato-Local](https://github.com/akdeb/Elato-Local?ref=githubawesome.com)

No. 16 - Relay

![](https://githubawesome.com/content/images/2026/03/image-454.png)

Want an AI coworker but terrified of giving them unsupervised access to your company data? Relay is the open-source alternative to Claude Cowork. It runs on your own infrastructure, and unlike every other agent framework, it doesn't just run loose, your AI writes a plan first, then stops for approval before pushing code, updating Jira, or messaging a client. You control what executes.

[https://github.com/SeventeenLabs/relay](https://github.com/SeventeenLabs/relay?ref=githubawesome.com)

No. 17 - jid

![](https://githubawesome.com/content/images/2026/03/image-455.png)

Working with complex JSON in the terminal is a guessing game, you write a jq filter, run it, get nothing, tweak it, repeat. jid kills that loop. It's an interactive terminal tool that lets you drill into JSON in real-time — auto-completes fields as you type, Tab through nested arrays, and shows matching data instantly. Full JMESPath support, installs via Homebrew in seconds. Once you use it, going back feels absurd.

[https://github.com/simeji/jid](https://github.com/simeji/jid?ref=githubawesome.com)

No. 18 - Lightfeed Extractor

![](https://githubawesome.com/content/images/2026/03/image-456.png)

LLM-powered web scraping pipelines fail the moment the model returns malformed JSON, and they fail silently in the worst cases. Lightfeed Extractor pairs Playwright browser automation with Zod schema validation and custom recovery logic that salvages usable data from broken AI outputs instead of crashing. Partial results beat no results when a pipeline needs to keep running.

[https://github.com/lightfeed/extractor](https://github.com/lightfeed/extractor?ref=githubawesome.com)

No. 19 - Verifiers

![](https://githubawesome.com/content/images/2026/03/image-457.png)

Reinforcement learning for LLMs requires consistent, well-defined reward signals, and building that infrastructure from scratch for every project is redundant work. Verifiers provides a standardized harness for training environments, sandboxes, and reward rubrics. Synthetic data generation, multi-turn puzzle evaluation, capability scoring — the infrastructure layer that lets you focus on the research rather than the scaffolding around it.

[https://github.com/PrimeIntellect-ai/verifiers](https://github.com/PrimeIntellect-ai/verifiers?ref=githubawesome.com)

No. 20 - Forkrun

![](https://githubawesome.com/content/images/2026/03/image-458.png)

Xargs and GNU Parallel get the job done until you're running on modern multi-socket hardware and the cross-socket memory traffic becomes the bottleneck. Forkrun is a drop-in replacement written entirely in Bash using coprocs, with a NUMA-aware design that keeps memory traffic local to each socket. Up to 400x faster than existing tools on modern CPUs.

[https://github.com/jkool702/forkrun](https://github.com/jkool702/forkrun?ref=githubawesome.com)

No. 21 - Fio

![](https://githubawesome.com/content/images/2026/03/image-459.png)

Fio is a brush-based CSG 3D world editor and game engine built in Python and PyOpenGL, directly inspired by Quake's Radiant and Valve's Hammer. Unified forward renderer, real-time lighting, and stencil shadows, all in a tool that captures the workflow of the editors that defined an era of level design.

[https://github.com/ViciousSquid/Fio](https://github.com/ViciousSquid/Fio?ref=githubawesome.com)

No. 22 - Layerleak

![](https://githubawesome.com/content/images/2026/03/image-460.png)

Git repos get scanned for secrets routinely. Docker image layers get ignored, and that's where things get quietly dangerous. Layerleak tears apart Docker Hub image histories and metadata hunting for accidentally baked-in API keys and secrets. Completely agentless, no infrastructure required to run it. If you're pushing images to Docker Hub and haven't scanned the layers, this should be the next thing you run.

[https://github.com/Brumbelow/layerleak](https://github.com/Brumbelow/layerleak?ref=githubawesome.com)

No. 23 - Anvil

![](https://githubawesome.com/content/images/2026/03/image-461.png)

Managing multiple AI coding sessions across terminal tabs with no structure is a chaos that compounds fast. Anvil is a desktop IDE built specifically for parallel agent work. Agents organized into an interactive grid, each running in an isolated Git worktree so multiple agents code simultaneously without stepping on each other. More agents, actual coordination between them.

[https://github.com/zdenham/anvil](https://github.com/zdenham/anvil?ref=githubawesome.com)

No. 24 - Wit

![](https://githubawesome.com/content/images/2026/03/image-462.png)

Multiple AI agents working the same repository simultaneously is a new problem, and file-level merge conflicts are the predictable result. Wit is a lightweight coordination daemon that tracks agent states in a local SQLite database. An agent locks a specific symbol before editing it, and any other agent attempting the same function gets a LOCK\_CONFLICT warning with details on who holds the lock.

[https://github.com/amaar-mc/wit](https://github.com/amaar-mc/wit?ref=githubawesome.com)

No. 25 - OpenSnek

![](https://githubawesome.com/content/images/2026/03/image-463.png)

Razer's official macOS support has always been inconsistent, and some newer mice get left out entirely. OpenSnek is a 7-megabyte native Mac app built by reverse-engineering the Bluetooth Low Energy protocol. Button remapping, DPI adjustment, RGB control, no cloud telemetry, no Synapse required. For Razer mouse owners on Mac who've been stuck with default settings, this is the fix that should have shipped officially.

[https://github.com/gh123man/opensnek](https://github.com/gh123man/opensnek?ref=githubawesome.com)

No. 26 - SentinelGate

![](https://githubawesome.com/content/images/2026/03/image-464.png)

Giving an AI agent terminal access without any layer of control between it and your system is a risk most people are quietly accepting. SentinelGate sits between your agent and your system as an MCP proxy firewall, intercepting every tool call and evaluating it against Role-Based Access Control and CEL policies before anything executes. Dangerous commands get blocked instantly, and a full audit trail captures everything.

[https://github.com/Sentinel-Gate/Sentinelgate](https://github.com/Sentinel-Gate/Sentinelgate?ref=githubawesome.com)

No. 27 - Moonshine Flow

![](https://githubawesome.com/content/images/2026/03/image-465.png)

Moonshine beats Whisper Large v3 on accuracy at a fraction of the size, but integrating raw speech models means handling audio chunking, Voice Activity Detection, and streaming buffers yourself. MoonshineFlow abstracts all of that. It's a lightweight pipeline that handles the messy audio processing and streams live transcription directly into your LLM or agent workflow. Real-time local voice input reduced to a single line of code.

[https://github.com/JRMeyer/MoonshineFlow](https://github.com/JRMeyer/MoonshineFlow?ref=githubawesome.com)

No. 28 - Orloj

![](https://githubawesome.com/content/images/2026/03/image-466.png)

Terraform brought infrastructure under version control and declarative management. Orloj does the same for AI agents. Define agents, tools, permissions, and pipelines as YAML manifests. Orloj handles scheduling, Kubernetes-style execution, and inline policy enforcement. Your entire agent swarm in Git, deployable and auditable the same way your infrastructure is.

[https://github.com/OrlojHQ/orloj](https://github.com/OrlojHQ/orloj?ref=githubawesome.com)

No. 29 - bsts-causalimpact

![](https://githubawesome.com/content/images/2026/03/image-467.png)

Google's CausalImpact is the gold standard for causal inference, but the Python ports have always been compromised versions of the original R implementation. This rewrite puts the Gibbs sampler in Rust and exposes it via Python. No TensorFlow dependency, 100% mathematical parity with the original R library, and 30x faster. The Python port that finally doesn't make you wish you'd just used R.

[https://github.com/YuminosukeSato/bsts-causalimpact](https://github.com/YuminosukeSato/bsts-causalimpact?ref=githubawesome.com)

No. 30 - Breathe-Memory

![](https://githubawesome.com/content/images/2026/03/image-468.png)

Standard RAG memory flattens everything and wastes tokens. Breathe-memory works differently, two phases. Before each response, SYNAPSE extracts entities, traverses a concept graph, and injects only relevant memories into the prompt in under 60 milliseconds. When the context fills, GraphCompactor kicks in, instead of a lossy summary, it compresses the conversation into a structured graph of topics, decisions, and artifacts.

[https://github.com/tkenaz/breathe-memory](https://github.com/tkenaz/breathe-memory?ref=githubawesome.com)

No. 31 - Xmloxide

![](https://githubawesome.com/content/images/2026/03/image-469.png)

Libxml2 going unmaintained left a critical gap in the XML parsing ecosystem that a huge amount of software depends on. Xmloxide fills it. A developer used an autonomous AI agent to iteratively rebuild the entire library in Rust, producing a memory-safe, high-performance XML parser with a C-API that passes 100% of the W3C conformance tests.

[https://github.com/jonwiggins/xmloxide](https://github.com/jonwiggins/xmloxide?ref=githubawesome.com)

No. 32 - Orca

![](https://githubawesome.com/content/images/2026/03/image-470.png)

Orca from StablyAI puts everything on a spatial canvas — multiple coding agents running simultaneously across isolated worktrees, with native terminal tracking, notifications, and git status all visible in one place. The terminal tab hunting stops. The unified control plane begins. For anyone running serious multi-agent workflows who's outgrown the scattered terminal approach, this is the IDE that was built for exactly that problem.

[https://github.com/stablyai/orca](https://github.com/stablyai/orca?ref=githubawesome.com)

No. 33 - Grafana-TUI

![](https://githubawesome.com/content/images/2026/03/image-471.png)

Switching to a browser to check server metrics when you're already in the terminal is an unnecessary context switch. Grafana-TUI connects directly to your Grafana instance and renders dashboards in the terminal using Go and Bubble Tea. Time-series data, bar charts, and heatmaps, all in the command line. Your metrics, without leaving where you already are.

[https://github.com/lovromazgon/grafana-tui](https://github.com/lovromazgon/grafana-tui?ref=githubawesome.com)

No. 34 - LLM-Gateway

![](https://githubawesome.com/content/images/2026/03/image-472.png)

Standard LLM gateways expose API endpoints over the network and hope your perimeter holds. LLM-Gateway from OpenZiti takes a different approach. Zero open listening ports, cryptographic identity enforcement, and semantic routing across multiple inference instances using OpenZiti's zero-trust overlay. For enterprises routing OpenAI and Anthropic traffic at scale, this is the security architecture that treats the network itself as untrusted.

[https://github.com/openziti/llm-gateway](https://github.com/openziti/llm-gateway?ref=githubawesome.com)