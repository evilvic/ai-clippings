---
title: "Hacker News Show #4"
source: "https://githubawesome.com/hacker-news-show-4/"
author:
  - "[[GithubAwesome]]"
published: 2026-04-14
created: 2026-04-15
description: "Hacker News Show, episode four. 35 projects from this week's Show HN."
tags:
  - "clippings"
---
This is The Hacker News Show, Episode 4. We've compiled 35 open-source repositories that recently went viral on Hacker News.

![](https://www.youtube.com/watch?v=mYU9vcvL-yk)

No. 1 - Hippo Memory

![](https://githubawesome.com/content/images/2026/04/image-106.png)

Every new AI session starts with amnesia. Hippo Memory fixes that with a biologically-inspired approach. Memories decay over time with configurable half-lives, but facts the agent uses frequently undergo retrieval strengthening and become permanent. At the end of each session, a sleep-based consolidation phase merges and prunes what the agent learned, same as human memory during sleep. Three-tier architecture (buffer, episodic, semantic) backed by SQLite with BM25+embedding hybrid search. Integrates with Claude Code, Cursor, Codex via SessionEnd hooks.

[https://github.com/kitfunso/hippo-memory](https://github.com/kitfunso/hippo-memory?ref=githubawesome.com)

No. 2 - git bayesect

A Bayesian spin on `git bisect` designed for probabilistic failures — the kind of intermittently flaky tests that standard bisection can't reliably pin down. It applies Beta-Bernoulli conjugacy and entropy minimization to identify the likeliest culprit commit without requiring a known failure rate, and it's fully automatable via a test command flag.

[https://github.com/hauntsaninja/git_bayesect](https://github.com/hauntsaninja/git_bayesect?ref=githubawesome.com)

No. 3 - pg_textsearch

Timescale's production-ready PostgreSQL extension brings BM25 relevance ranking natively into Postgres, replacing the aging `ts_rank` with a modern algorithm tunable via k1 and b parameters. It introduces a custom `<@>` operator, supports Block-Max WAND optimization for fast top-k retrieval, and works across JSONB fields and multilingual indexes. For teams already on Postgres who've been eyeing dedicated search engines just for ranking quality, this removes a significant architectural trade-off.

[https://github.com/timescale/pg_textsearch](https://github.com/timescale/pg_textsearch?ref=githubawesome.com)

No. 4 - Zerobox

A lightweight process sandbox that runs commands with deny-by-default security — no writes, no network, no environment variables unless explicitly granted — without the overhead of Docker or VMs. Its most compelling feature is credential injection: API keys are never exposed to the sandboxed process; they're substituted by a proxy only for approved hostnames. With ~10ms overhead, Rust and TypeScript SDKs, and an obvious fit for LLM tool-call sandboxing.

[https://github.com/afshinm/zerobox](https://github.com/afshinm/zerobox?ref=githubawesome.com)

No. 5 - Claudraband

A thin but clever CLI wrapper around Claude Code that adds persistent, resumable sessions via tmux — solving the stateless session problem for long-running autonomous workflows. It exposes an HTTP daemon for remote control and an ACP server for editor integration (Zed, Toad), making it possible to drive Claude Code programmatically without losing session context.

[https://github.com/halfwhey/claudraband](https://github.com/halfwhey/claudraband?ref=githubawesome.com)

No. 6 - react-rewrite

A visual in-browser editor for React apps that writes changes back to source files in real time — no manual code edits required. It works as a proxy server that injects an overlay into your existing dev server, supporting element inspection, Tailwind property editing, inline text changes, and drag-to-reorder, with a staged batch workflow before committing anything to disk. Supports Next.js, Vite, and CRA.

[https://github.com/donghaxkim/react-rewrite](https://github.com/donghaxkim/react-rewrite?ref=githubawesome.com)

No. 7 - Agents Observe

A real-time observability dashboard for Claude Code's multi-agent workflows, capturing every tool call and subagent relationship through hook events streamed over WebSockets to a React UI. The stack — Hono server, SQLite, React 19, Docker — is deliberately simple, and the value proposition is equally simple: when Claude Code runs autonomously across parallel subagents, you currently have no visibility; this fixes that.

[https://github.com/simple10/agents-observe](https://github.com/simple10/agents-observe?ref=githubawesome.com)

No. 8 - Kiyeovo

A decentralized, end-to-end encrypted desktop messenger built on libp2p that offers two distinct network modes: a fast relay-assisted mode for low-latency DMs and calls, and a Tor-routed anonymous mode for censorship resistance. Built with React, TypeScript, and Electron, it carves out a niche between Briar (Tor-only) and Session (proprietary nodes) by letting users switch modes per their threat model.

[https://github.com/Realman78/Kiyeovo](https://github.com/Realman78/Kiyeovo?ref=githubawesome.com)

No. 9 - mtproto.zig

A Telegram MTProto proxy written in Zig that clocks in at 177 KB binary and 0.75 MB baseline RAM — roughly 10x leaner than the official Go and Rust alternatives. It disguises Telegram traffic as TLS 1.3 HTTPS and layers on an impressive arsenal of DPI evasion techniques including TCP MSS fragmentation, split-TLS with 1-byte records, and IPv6 rotation. Built for exactly the environments where Telegram is blocked and resource-constrained servers are the norm.

[https://github.com/sleep3r/mtproto.zig](https://github.com/sleep3r/mtproto.zig?ref=githubawesome.com)

No. 10 - korb

A Haskell CLI for automating REWE grocery orders through reverse-engineered mobile APIs, with a suggestion engine formally verified in Lean 4. The intended workflow is agentic: add items via Siri shortcuts, have Claude build the basket via korb commands, review, and confirm. Currently non-functional: REWE is actively blocking it via Cloudflare TLS fingerprinting.

[https://github.com/yannick-cw/korb](https://github.com/yannick-cw/korb?ref=githubawesome.com)

No. 11 - Openbrowser

A Rust-built headless browser designed specifically for AI agents that outputs semantic page state — ARIA roles, landmarks, interactive elements with unique IDs — rather than screenshots or pixel buffers. It requires no Chrome binary, typically runs under 200ms, and supports Markdown/JSON/tree output formats, a CDP server, BFS-based site graph mapping, and optional V8 JavaScript execution. The core insight is that agents need actionable structure, not visual rendering.

[https://github.com/JasonHonKL/Openbrowser](https://github.com/JasonHonKL/Openbrowser?ref=githubawesome.com)

No. 12 - Raincast

An AI-powered desktop app generator that takes natural language descriptions and produces fully functional Tauri + React applications, complete with native system APIs and one-click compilation to standalone binaries. It supports 9 layout templates and both Anthropic and Google Gemini backends, with a "proxy binary" mechanism that intercepts Tauri invoke() calls during live preview before handing off to a compiled binary for production.

[https://github.com/tihiera/raincast](https://github.com/tihiera/raincast?ref=githubawesome.com)

No. 13 - Pegboard

A parametric, AI-generated pegboard toy system designed for 3D printing, born from a parent's desire to skip hours in CAD software. Built entirely in Python using parametric generators rather than hand-modeled meshes, it produces interchangeable play pieces, gears, and snap-together boards on a 40mm grid. The repo includes an `AGENTS.md` specifically written for coding agents to extend the system.

[https://github.com/virpo/pegboard](https://github.com/virpo/pegboard?ref=githubawesome.com)

No. 14 - TinyOS

A production-grade RTOS that fits in under 10 KB of flash and 2 KB of RAM, targeting the kind of microcontrollers where every byte counts. Its scheduler delivers O(1) priority lookup across 256 priority levels, and the feature set punches well above its weight class: TCP/IP, TLS 1.3, MQTT with QoS, CoAP, A/B OTA updates, and a wear-leveling filesystem. POSIX compatibility layers for pthreads and BSD sockets.

[https://github.com/cmc-labo/tinyos-rtos](https://github.com/cmc-labo/tinyos-rtos?ref=githubawesome.com)

No. 15 - numa

A self-contained DNS resolver written from scratch in Rust — no external DNS libraries — that bundles ad blocking (385K+ domains via Hagezi Pro), DNSSEC validation, DNS-over-TLS/HTTPS, and automatic `.numa` domains with TLS for local dev services into a single ~8 MB binary. Portable privacy infrastructure that works the same whether you're at a coffee shop or behind a corporate firewall.

[https://github.com/razvandimescu/numa](https://github.com/razvandimescu/numa?ref=githubawesome.com)

No. 16 - baremail

A ~60 KB PWA that talks directly to the Gmail API with no backend server — viable over airplane Wi-Fi or spotty rural connections where loading Gmail's multi-megabyte JavaScript bundle isn't an option. Built with Preact, TypeScript, and a Service Worker/IndexedDB offline layer, it supports keyboard-driven navigation, offline compose with message queuing, and plain-text reading. All OAuth tokens stay on-device.

[https://github.com/matt-virgo/baremail](https://github.com/matt-virgo/baremail?ref=githubawesome.com)

No. 17 - modo

An open-source AI IDE built on top of Void (a VS Code fork) that enforces a spec-driven workflow: every feature request must pass through requirements, design, and task documents before a single line of code is generated. Steering files, agent hooks with circular-dependency detection, and a switchable autopilot/supervised mode round out a system aimed at developers who want AI assistance with guardrails rather than raw autocomplete.

[https://github.com/mohshomis/modo](https://github.com/mohshomis/modo?ref=githubawesome.com)

No. 18 - craft

A thin build-system wrapper for C/C++ that replaces the often painful CMake setup process with a single `craft.toml` config file. Rather than reimplementing a build system from scratch, it auto-generates `CMakeLists.txt` and handles git-based dependency fetching behind the scenes, keeping CMake as the actual build engine while hiding its complexity.

[https://github.com/randerson112/craft](https://github.com/randerson112/craft?ref=githubawesome.com)

No. 19 - marimo-pair

A shell-based bridge that drops AI agents directly into running marimo notebook sessions, enabling code execution with full awareness of the notebook's live variable state. Marimo is a reactive Python notebook framework that stores notebooks as plain `.py` files and re-executes cells automatically on change. Marimo-pair extends this by letting agent CLIs like Claude Code participate in that reactive environment.

[https://github.com/marimo-team/marimo-pair](https://github.com/marimo-team/marimo-pair?ref=githubawesome.com)

No. 20 - Brightbean Studio

An open-source, self-hostable social media management platform positioning itself as a free alternative to Buffer and SocialPilot — with no per-seat, per-channel, or per-workspace limits. It covers 10+ platforms (including Bluesky, Mastodon, TikTok, and Threads) via direct first-party API integrations, and ships with approval workflows, a unified social inbox, and a client portal. Django 5/HTMX stack with Docker Compose deployment.

[https://github.com/brightbeanxyz/brightbean-studio](https://github.com/brightbeanxyz/brightbean-studio?ref=githubawesome.com)

No. 21 - finalrun-agent

An AI-driven mobile testing CLI that lets you write test scenarios in plain-English YAML and then watches an AI agent — backed by Gemini, GPT, or Claude — navigate your app on an emulator, interpret the screen, and generate pass/fail reports with video and logs. Its automated test-and-fix loops can diagnose failures and apply corrections without human intervention.

[https://github.com/final-run/finalrun-agent](https://github.com/final-run/finalrun-agent?ref=githubawesome.com)

No. 22 - ttf-doom

A playable DOOM-style raycasting engine embedded inside a TrueType font file, exploiting the Turing-complete bytecode VM that Apple designed in 1991 for pixel-grid hinting. The raycaster repositions 16 vertical bar contours in the glyph "A" to render perspective walls, receiving player coordinates through CSS `font-variation-settings` axes — meaning the 3D view is literally rendered by your browser's font engine.

[https://github.com/4RH1T3CT0R7/ttf-doom](https://github.com/4RH1T3CT0R7/ttf-doom?ref=githubawesome.com)

No. 23 - mdarena

A benchmarking tool that empirically measures whether your `CLAUDE.md` instruction files actually help AI agents or quietly make them worse. It mines merged pull requests as a test dataset, runs Claude against each under baseline and CLAUDE.md conditions, and grades results via real test execution or diff overlap. In the project's own testing, a consolidated alternative to the existing CLAUDE.md performed worse than no instructions at all.

[https://github.com/HudsonGri/mdarena](https://github.com/HudsonGri/mdarena?ref=githubawesome.com)

No. 24 - OberonSystem3Native

Rochus Keller has updated Oberon System 3 — Niklaus Wirth's historically significant OS from the early 1990s — to boot via the Multiboot standard, replacing its obsolete bootloader and enabling it to run on modern hardware and virtual machines. The project recently achieved running on a Raspberry Pi 3B, overcoming USB timing challenges with custom microsecond waits against the BCM2837's hardware timer.

[https://github.com/rochus-keller/OberonSystem3Native](https://github.com/rochus-keller/OberonSystem3Native?ref=githubawesome.com)

No. 25 - DecisionNode

A CLI and local MCP server that gives AI coding assistants a shared, persistent memory for architectural decisions — stored as JSON with vector embeddings so any tool (Claude Code, Cursor, Windsurf) can semantically query past choices. It uses Gemini embeddings for retrieval, flags near-duplicate decisions at 75% similarity, and keeps a full audit trail of which tool or human made each call.

[https://github.com/decisionnode/DecisionNode](https://github.com/decisionnode/DecisionNode?ref=githubawesome.com)

No. 26 - keeper

A hardened secret management library for Go that pairs Argon2id key derivation with XChaCha20-Poly1305 encryption, storing secrets in an embedded bbolt database with per-bucket Data Encryption Keys and tamper-evident HMAC audit chains. It ships in three modes — embeddable Go library, HTTP handler, and a terminal REPL with no-echo entry.

[https://github.com/agberohq/keeper](https://github.com/agberohq/keeper?ref=githubawesome.com)

No. 27 - fast-ebook

A Rust-backed Python library for reading and writing EPUB files that clocks in 6.7x faster than the incumbent ebooklib stack — converting War and Peace from EPUB to Markdown in 56ms versus 375ms. Built with PyO3 bindings, it mirrors ebooklib's API closely enough that migration is often just a one-line import swap.

[https://github.com/arc53/fast-ebook](https://github.com/arc53/fast-ebook?ref=githubawesome.com)

No. 28 - zoneless

An open-source drop-in replacement for Stripe Connect payouts that routes marketplace seller disbursements over Solana USDC at roughly $0.002 per transaction — versus Stripe's 0.25% + $0.25. It mimics Stripe's webhook shapes and object models for easy migration, covers 220+ countries (vs. Stripe's ~47), and settles in seconds rather than days. Real-world validation from PromptBase (450K+ users) which cut ~$9,400/month in payout fees.

[https://github.com/zonelessdev/zoneless](https://github.com/zonelessdev/zoneless?ref=githubawesome.com)

No. 29 - dinobase

A query layer that lets AI agents issue a single SQL statement spanning 101 different SaaS APIs, databases, and cloud storage sources simultaneously, using DuckDB under the hood and Parquet as the local sync format. Across 11 LLMs and 75 questions, it achieved 91% accuracy versus 35% for per-source MCP tools, at one-sixteenth the cost per correct answer.

[https://github.com/DinobaseHQ/dinobase](https://github.com/DinobaseHQ/dinobase?ref=githubawesome.com)

No. 30 - clickhouse-etl

GlassFlow's open-source stream processing engine that moves and transforms high-volume data from Kafka into ClickHouse at terabyte scale, without requiring a full streaming platform like Flink. It supports stateless transformations via an expression engine and stateful operations including deduplication and temporal joins, with a dead-letter queue and OpenTelemetry metrics baked in.

[https://github.com/glassflow/clickhouse-etl](https://github.com/glassflow/clickhouse-etl?ref=githubawesome.com)

No. 31 - skrun

An open-source agent runtime that wraps AI skills — defined in SKILL.md files compatible with Claude Code, Copilot, and Codex — and exposes them as production POST endpoints with automatic fallback across five LLM providers (Anthropic, OpenAI, Google, Mistral, Groq). It handles streaming via Server-Sent Events, async webhooks, stateful persistence across runs, and MCP tool calling.

[https://github.com/skrun-dev/skrun](https://github.com/skrun-dev/skrun?ref=githubawesome.com)

No. 32 - tui-use

Solves a real gap in AI agent toolkits: the inability to interact with terminal programs that demand keyboard input — REPLs, debuggers, full-screen TUI apps like vim or lazygit. It spawns processes in pseudo-terminals, runs a background daemon to keep sessions alive across CLI calls, and renders ANSI escape sequences through a headless xterm emulator so agents receive clean plain text. The `wait --text <pattern>` command blocks until a specific prompt appears.

[https://github.com/onesuper/tui-use](https://github.com/onesuper/tui-use?ref=githubawesome.com)

No. 33 - multigres-operator

A Kubernetes operator for managing sharded, distributed PostgreSQL clusters via a single `MultigresCluster` custom resource, handling topology, certificates, backups via pgBackRest, and observability (Prometheus, Grafana, OpenTelemetry) out of the box. It bypasses StatefulSets in favor of direct pod and PVC management for granular control.

[https://github.com/multigres/multigres-operator](https://github.com/multigres/multigres-operator?ref=githubawesome.com)

No. 34 - go-bt

A minimal behavior tree library for Go, designed around cooperative multitasking: nodes return Success, Running, or Failure instantly — no blocking — with all state stored in a generic `BTContext[T]` rather than in node instances. A background `Supervisor` ticks the tree at configurable intervals, and clock injection means you can simulate hours of time in microseconds during tests.

[https://github.com/rvitorper/go-bt](https://github.com/rvitorper/go-bt?ref=githubawesome.com)

No. 35 - turbovec

Implements TurboQuant, a Google Research algorithm (ICLR 2026), for training-free vector compression to 2-4 bits per dimension — achieving 16x compression on 1536-dimensional embeddings with recall comparable to FAISS. The trick is a random orthogonal rotation that makes any input distribution uniform, enabling optimal Lloyd-Max scalar quantization without ever fitting a codebook to your data. On ARM (M3 Max) it's 13-20% faster than FAISS FastScan.

[https://github.com/RyanCodrai/turbovec](https://github.com/RyanCodrai/turbovec?ref=githubawesome.com)
