---
title: "GitHub Trending Today #27"
source: "https://githubawesome.com/github-trending-today-27/"
author:
  - "[[GithubAwesome]]"
published: 2026-03-20
created: 2026-04-03
description: "Today, I’ve handpicked 36 trending open source projects on GitHub. tools, dev utilities, and some cool ideas that are blowing up.No. 1 - Ichinichichinichi is a beautifully opinionated journaling app. Most note-taking apps overwhelm you with folders, tags, and templates. Ichinichi just gives you one note per"
tags:
  - "clippings"
---
Today, I’ve handpicked 36 trending open source projects on GitHub. tools, dev utilities, and some cool ideas that are blowing up.

![](https://www.youtube.com/watch?v=19AUlTi-Ki8)

**No. 1 - Ichinichi**

![](https://githubawesome.com/content/images/2026/03/image-238.png)

chinichi is a beautifully opinionated journaling app. Most note-taking apps overwhelm you with folders, tags, and templates. Ichinichi just gives you one note per day, and here is the catch: you cannot edit yesterday's note. What is done is done. It stores everything locally with end-to-end AES-GCM encryption, and forces you to stop fussing over the past so you can focus on building a daily writing habit.

[https://github.com/katspaugh/ichinichi](https://github.com/katspaugh/ichinichi?ref=githubawesome.com)

No. 2 - Recordly

![](https://githubawesome.com/content/images/2026/03/image-239.png)

If you are tired of paying subscriptions for Screen Studio just to make a tutorial video, you need this. Recordly is a screen recorder and editor built for macOS and Windows. You record your screen, it does the rest. Cursor animations, auto zoom-ins on clicks, webcam overlays. Looks like you spent hours editing. You didn't. If you're a developer shipping demo videos, there's no reason to keep paying for the alternative.

[https://github.com/webadderall/Recordly](https://github.com/webadderall/Recordly?ref=githubawesome.com)

No. 3 - Notchi

![](https://githubawesome.com/content/images/2026/03/image-240.png)

Notchi puts a animated pixel sprite in your MacBook notch. That's the whole pitch. It sits quietly in the menu bar until your Claude Code or terminal AI starts running, then a little character drops down and reacts to what it's doing in real time. It's basically a Tamagotchi for your coding agent. Does it make you more productive? No. Is it the best thing installed on my machine right now? Possibly.

[https://github.com/sk-ruban/notchi](https://github.com/sk-ruban/notchi?ref=githubawesome.com)

No. 4 - MiroFish-Offline

![](https://githubawesome.com/content/images/2026/03/image-241.png)

MiroFish went viral for a reason. a SimCity-style engine that runs thousands of AI agents to forecast real-world events based on live news. The catch was the cloud API costs, which made it impractical for most people to actually run. Someone fixed that. MiroFish-Offline strips out the cloud dependencies entirely and replaces them with a local Neo4j graph database and Ollama models.

[https://github.com/nikmcfly/MiroFish-Offline](https://github.com/nikmcfly/MiroFish-Offline?ref=githubawesome.com)

No. 5 - Gabagool

![](https://githubawesome.com/content/images/2026/03/image-242.png)

Gabagool is a WebAssembly interpreter written from scratch in Rust. The name is funny. What it does is not. The whole thing is fully snapshotable. Freeze the entire execution state mid-tick, serialize it, spin up new processes from that exact point, and watch them diverge. It also ships with a time-travel debugger. If you've spent any time doing low-level systems work, you know how hard this is to pull off.

[https://github.com/friendlymatthew/gabagool](https://github.com/friendlymatthew/gabagool?ref=githubawesome.com)

No. 6 - Antfly

![](https://githubawesome.com/content/images/2026/03/image-243.png)

Antfly is a distributed, multimodal search engine written in Go. It combines full-text BM25 search, vector similarity, and graph traversal all into a single binary! Backed by the Pebble storage engine and etcd's raft library, it even ships with built-in ML inference. You don't need external APIs for embeddings. Antfly handles the entire RAG memory pipeline out of the box!

[https://github.com/antflydb/antfly](https://github.com/antflydb/antfly?ref=githubawesome.com)

No. 7 - Horizon

![](https://githubawesome.com/content/images/2026/03/image-244.png)

Are you drowning in a sea of overlapping terminal windows? Horizon is a GPU-accelerated spatial terminal observatory built in Rust. Instead of tabs or split panes, Horizon places your terminals, AI agents, and dev tools onto an infinite, zoomable canvas! It operates just like a Miro board or Figma canvas, allowing you to organize, pan, and zoom around your active sessions so you never lose track of a running script again.

[https://github.com/peters/horizon](https://github.com/peters/horizon?ref=githubawesome.com)

No. 8 - Slug

![](https://githubawesome.com/content/images/2026/03/image-245.png)

The Slug font rendering algorithm just went MIT licensed. If you don't know Slug. it's Eric Lengyel's GPU text rendering method. Dynamic dilation, custom HLSL shaders, genuinely fast and crisp output. It was previously patent-locked, which kept it out of most independent projects entirely. That's done now. The reference code is public, free to use, and directly applicable to any custom game engine or graphics pipeline.

[https://github.com/EricLengyel/Slug](https://github.com/EricLengyel/Slug?ref=githubawesome.com)

No. 9 - OpenCLI

![](https://githubawesome.com/content/images/2026/03/image-246.png)

OpenCLI turns any website or Electron app into a command-line interface. By using a secure Chrome extension bridge, it reuses your active, logged-in browser session so your terminal can interact directly with sites like Twitter, Reddit, or YouTube without complex API auth. it can CLI-ify Electron apps, meaning you can literally have an AI agent living in your terminal that autonomously drives and controls other AI desktop apps!

[https://github.com/jackwener/opencli](https://github.com/jackwener/opencli?ref=githubawesome.com)

No. 10 - Slim

![](https://githubawesome.com/content/images/2026/03/image-247.png)

Ngrok works, but you're paying for it. Slim doesn't cost anything. It's a lightweight CLI tool written in Go. One command exposes your local server via a public slim.show URL. It also generates trusted root certificates for clean HTTPS.local domains, and handles CORS and WebSockets without any extra configuration. For webhook testing and local dev work, it covers everything Ngrok does for most people.

[https://github.com/kamranahmedse/slim](https://github.com/kamranahmedse/slim?ref=githubawesome.com)

No. 11 - Gitagent

![](https://githubawesome.com/content/images/2026/03/image-248.png)

Most AI agents today are a mess of config files, database state, and Python code scattered across a project. Gitagent puts all of it in a Git repo. Prompts, rules, memory, tools. extracted into a portable format that lives entirely in version control. Clone the repo, get a fully functional agent. That's it. The version control angle alone is worth paying attention to.

[https://github.com/open-gitagent/gitagent](https://github.com/open-gitagent/gitagent?ref=githubawesome.com)

No. 12 - AppGrid

![](https://githubawesome.com/content/images/2026/03/image-249.png)

If you're on KDE Plasma 6 and the default Kickoff menu isn't doing it for you, AppGrid is a straight upgrade. It's a fullscreen grid-style app launcher. think macOS Launchpad, with some COSMIC desktop influence mixed in. Background blur, smooth animations, folder support, and KRunner search built in. Linux desktop customization has quietly gotten very good. This is a solid example of that.

[https://github.com/xarbit/plasma6-applet-appgrid](https://github.com/xarbit/plasma6-applet-appgrid?ref=githubawesome.com)

No. 13 - OpenOats

![](https://githubawesome.com/content/images/2026/03/image-250.png)

Most meeting transcribers just record what happened. OpenOats is doing something different. It runs completely offline on Mac, transcribing both sides of a call in real time. But while you're talking, it's also searching your local Markdown notes. and when a relevant topic comes up, it surfaces the right talking points on screen, live, mid-conversation.

[https://github.com/yazinsai/OpenOats](https://github.com/yazinsai/OpenOats?ref=githubawesome.com)

No. 14 - TUIStudio

![](https://githubawesome.com/content/images/2026/03/image-251.png)

Building terminal UIs usually means calculating grid coordinates by hand and guessing at layouts until something looks right. TUIStudio skips all of that. It's a visual drag-and-drop editor for terminal app layouts. Drop components onto a canvas, tweak flexbox and grid settings visually, and see a live ANSI preview as you go. When you're done, export directly to Ink, BubbleTea, or Textual.

[https://github.com/jalonsogo/tui-studio](https://github.com/jalonsogo/tui-studio?ref=githubawesome.com)

No. 15 - Actrun

![](https://githubawesome.com/content/images/2026/03/image-252.png)

Every developer has a branch somewhere with 40 commits that just say "fix" or "try again." That's what testing GitHub Actions in production looks like. Actrun runs your entire CI/CD pipeline locally before you push anything. It's built in MoonBit, cross-compiles natively, and works via Docker or npx if you'd rather not install anything. No more polluting your commit history to debug a broken workflow.

[https://github.com/mizchi/actrun](https://github.com/mizchi/actrun?ref=githubawesome.com)

No. 16 - Altimate Code

![](https://githubawesome.com/content/images/2026/03/image-253.png)

General-purpose AI coding agents and data warehouses are a bad combination. Wrong table names, broken joins, hallucinated column references. Altimate Code is built specifically for data engineering. Instead of guessing at your schema, it queries your actual catalog locally in 2 milliseconds without touching the warehouse. It understands dbt, knows your lineage, and ships with 100+ purpose-built tools for Snowflake and BigQuery.

[https://github.com/AltimateAI/altimate-code](https://github.com/AltimateAI/altimate-code?ref=githubawesome.com)

No. 17 - Claw3D

![](https://githubawesome.com/content/images/2026/03/image-254.png)

What if you could watch your AI agents work in a 3D virtual office? Claw3D does exactly that. It's a fully open-source 3D environment for your OpenClaw workforce. Walk around the office, drag and drop furniture, put on background music. When an agent is reviewing a pull request, walk up to their virtual desk and see the code diffs on their screen. It basically turns your AI infrastructure into The Sims.

[https://github.com/iamlukethedev/Claw3D](https://github.com/iamlukethedev/Claw3D?ref=githubawesome.com)

No. 18 - RX Data Store

![](https://githubawesome.com/content/images/2026/03/image-255.png)

If JSON.stringify is becoming a bottleneck, RX is worth benchmarking against your current setup. It's a binary encoding format and drop-in JSON replacement. The numbers are hard to ignore, 18x smaller output through string deduplication and binary-encoded numbers. For single-key lookups, it skips deserialization entirely using zero-allocation JavaScript Proxies, which puts it at 23,000x faster than standard JSON parsing in that scenario.

[https://github.com/creationix/rx](https://github.com/creationix/rx?ref=githubawesome.com)

No.19 - ApiArk

![](https://githubawesome.com/content/images/2026/03/image-256.png)

Postman works, but 800MB of RAM and a mandatory cloud account to test a local endpoint is a hard sell in 2026. ApiArk is built with Tauri v2 and Rust, idles at 60MB, and has no cloud telemetry at all. Your collections save as plain YAML files on your filesystem, so they version control cleanly with Git. Fast, private, and your data stays on your machine.

[https://github.com/berbicanes/apiark](https://github.com/berbicanes/apiark?ref=githubawesome.com)

No. 20 **\- Impeccable**

![](https://githubawesome.com/content/images/2026/03/image-257.png)

AI coding agents building frontend UIs always default to the same generic look. purple gradients, default Inter fonts, nested cards everywhere. Impeccable fixes that. It's an installable design skill for Claude Code that acts as an expert creative director. Twenty steering commands and curated anti-patterns that explicitly force the AI to avoid cliché UI tropes. Turn your LLM into a master of modern frontend design.

[https://github.com/pbakaus/impeccable](https://github.com/pbakaus/impeccable?ref=githubawesome.com)

No. 21 - My Translator

![](https://githubawesome.com/content/images/2026/03/image-258.png)

Translation SaaS adds up fast, and most of it is just a wrapper around APIs you could call yourself. My Translator skips the middleman entirely. It's open-source, runs on macOS and Windows, and does real-time speech translation on your desktop using free TTS engines. Plug in your own API keys, and that's it. No subscription, no data routed through someone else's servers.

[https://github.com/phuc-nt/my-translator](https://github.com/phuc-nt/my-translator?ref=githubawesome.com)

No. 22 - Collaborator

![](https://githubawesome.com/content/images/2026/03/image-259.png)

Managing multiple AI agents right now means scattered terminal panes, constant app switching, and no real picture of what's running where. Collaborator puts everything on a single infinite canvas. Terminals, context files, running code, all arranged spatially on a pan-and-zoom workspace built for macOS. No tab hunting, no context switching.

[https://github.com/collaborator-ai/collab-public](https://github.com/collaborator-ai/collab-public?ref=githubawesome.com)

No. 23 - OpenBrand

![](https://githubawesome.com/content/images/2026/03/image-260.png)

Paste a URL, get the brand kit. OpenBrand scrapes any website and pulls out the logos, exact hex color palettes, and core visual assets automatically. No digging through DevTools, no manually eyedropping colors off a screenshot. For competitive research or seeding an AI design system, it cuts out a genuinely tedious part of the process.

[https://github.com/ethanjyx/OpenBrand](https://github.com/ethanjyx/OpenBrand?ref=githubawesome.com)

No. 24 - App Store Preflight

![](https://githubawesome.com/content/images/2026/03/image-261.png)

Getting rejected by Apple after a two-week review cycle is one of the more demoralizing parts of iOS development. App Store Preflight runs before you submit. It pulls your app metadata and checks it against 100+ Apple Review Guidelines, flagging missing privacy manifests, competitor mentions, and banned AI keywords before any human reviewer sees it.

[https://github.com/truongduy2611/app-store-preflight-skills](https://github.com/truongduy2611/app-store-preflight-skills?ref=githubawesome.com)

No. 25 - Lux

![](https://githubawesome.com/content/images/2026/03/image-262.png)

Redis is solid, but the single-threaded architecture starts showing its limits at scale. Lux is a drop-in replacement written in Rust. Full RESP protocol compatibility, so existing Redis clients work without any code changes. Benchmarks show up to 5.6x faster performance, and the Docker image comes in at 1MB. If you're hitting Redis bottlenecks and don't want to rewrite your client layer, this is the straightforward path forward.

[https://github.com/lux-db/lux](https://github.com/lux-db/lux?ref=githubawesome.com)

No. 26 - Fabro

![](https://githubawesome.com/content/images/2026/03/image-263.png)

Most AI agent dashboards feel like they were designed as an afterthought. Fabro is clearly not that. It's an open-source orchestration UI for managing AI agents, built with the same keyboard-driven that makes Linear feel good to use. It supports the Agent Communication Protocol, so you can plug in multiple AI providers and manage everything from one interface instead of juggling separate dashboards per service.

[https://github.com/fabro-sh/fabro](https://github.com/fabro-sh/fabro?ref=githubawesome.com)

No. 27 - Vpskit

![](https://githubawesome.com/content/images/2026/03/image-264.png)

Setting up a bare-metal VPS from scratch usually requires an hour of reading outdated tutorials. Vpskit does it in one bash command. System updates, protected user, hardened SSH, firewall config, Docker, and a Caddy reverse proxy with auto-updates. No third-party services, nothing phoning home. Clean, secure, deployment-ready in minutes.

[https://github.com/mariusdjen/vpskit](https://github.com/mariusdjen/vpskit?ref=githubawesome.com)

No. 28 - Radiant

![](https://githubawesome.com/content/images/2026/03/image-265.png)

Paul Bakaus just dropped Radiant. 80+ production-ready shaders and visual effects for the web. Fluid simulations, light refractions, particle effects. Drop them directly into React or vanilla JS and they work. No build setup, no third-party packages to manage. If your current frontend is held together with CSS transitions and good intentions, this is a significant upgrade.

[https://github.com/pbakaus/radiant](https://github.com/pbakaus/radiant?ref=githubawesome.com)

No. 29 - Meetscribe

![](https://githubawesome.com/content/images/2026/03/image-266.png)

Otter.ai works, but a corporate bot sitting in your confidential meetings is a legitimate concern for a lot of teams. Meetscribe runs entirely on your machine. It captures both mic and system audio, uses Whisper and Pyannote offline to separate speakers automatically, then generates a timestamped PDF summary through a local Ollama model. Works with Zoom, Teams, and Slack. For anyone handling sensitive conversations, that's the whole pitch.

[https://github.com/pretyflaco/meetscribe](https://github.com/pretyflaco/meetscribe?ref=githubawesome.com)

No. 30 - OpenShell

![](https://githubawesome.com/content/images/2026/03/image-267.png)

OpenShell from NVIDIA is a sandboxed runtime built specifically for autonomous agents. Deny-by-default network policies, strict filesystem restrictions. Your agent can run scripts, write code, and self-modify without any of that touching the host machine. If you're running Claude Code or any autonomous agent around the clock, this is the layer that should be between it and your system.

[https://github.com/NVIDIA/OpenShell](https://github.com/NVIDIA/OpenShell?ref=githubawesome.com)

No. 31 - Paper-dl

![](https://githubawesome.com/content/images/2026/03/image-268.png)

Academic literature pipelines have an annoying gap between finding papers and actually having them locally for analysis. Paper-dl closes it. It's a lightweight Python tool that takes JSON search results and automatically downloads the full PDFs from arXiv directly to your machine. Clean, simple, and built specifically to feed a local RAG-powered research database.

[https://github.com/RuizeLyu/paper-dl](https://github.com/RuizeLyu/paper-dl?ref=githubawesome.com)

No. 32 - Data-anim

![](https://githubawesome.com/content/images/2026/03/image-269.png)

Most scroll animation libraries are overkill for what most projects actually need. Data-anim handles it with HTML data attributes and weighs under 3KB gzipped. 30+ animations, stagger effects, anti-FOUC protection built in, and it works in any framework without configuration. Add the script, add the attributes, done.

[https://github.com/ryo-manba/data-anim](https://github.com/ryo-manba/data-anim?ref=githubawesome.com)

No. 33 - Element-source

![](https://githubawesome.com/content/images/2026/03/image-270.png)

Element-source tells you exactly which file and line of code rendered any DOM element in your browser. Works across React, Vue. The practical use case for AI development is direct: your agent clicks an element on screen and opens the exact source line that produced it. No hunting through the component tree, no guessing at file paths. Built originally for context-aware AI tooling, but useful for anyone doing serious debugging work.

[https://github.com/aidenybai/element-source](https://github.com/aidenybai/element-source?ref=githubawesome.com)

No. 34 - LATENT

![](https://githubawesome.com/content/images/2026/03/image-271.png)

Someone taught a humanoid robot to play tennis, and the training data was 5 hours of imperfect amateur movement captured outside a lab. That's the part worth sitting with. Not clean motion capture, not carefully curated demonstrations, just messy human footage fed into a latent action space model. The Unitree G1 can now side-step, adapt in real time, and sustain multi-shot rallies against actual human players.

[https://github.com/GalaxyGeneralRobotics/LATENT](https://github.com/GalaxyGeneralRobotics/LATENT?ref=githubawesome.com)

No. 35 - Mori

![](https://githubawesome.com/content/images/2026/03/image-272.png)

If you're context-switching between multiple Git worktrees and losing terminal state every time, Mori is built for exactly that. It gives each worktree its own persistent, GPU-accelerated workspace powered by tmux and libghostty, wrapped in a native macOS sidebar. Jump between branches and projects without losing what was running.

[https://github.com/vaayne/mori](https://github.com/vaayne/mori?ref=githubawesome.com)

No. 36 - aurl

![](https://githubawesome.com/content/images/2026/03/image-273.png)

If you've ever fat-fingered a curl command against a production endpoint, aurl is a reasonable response to that experience. It's a CLI tool written in Go that turns any API into a strongly-typed interface. Native support for OpenAPI 3.0, Swagger, and GraphQL. It auto-detects authentication, validates your payload against the spec before sending, and generates documentation from introspection.

[https://github.com/ShawnPana/aurl](https://github.com/ShawnPana/aurl?ref=githubawesome.com)