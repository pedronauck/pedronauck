# hi, I'm Pedro Nauck 👋

> 🤖 Building harness for AI.

I'm a software engineer based in **San Francisco**, founder of [Compozy](https://compozy.com) — where we're building the orchestration layer that takes AI coding agents from *idea* to *shipped code* in a single pipeline.

Before AI ate everything, I spent a decade shipping open-source developer tools — **[Docz](https://github.com/doczjs/docz)** (23.6k+ ⭐), **[react-adopt](https://github.com/pedronauck/react-adopt)** (1.6k+ ⭐), **[reworm](https://github.com/pedronauck/reworm)** (1.4k+ ⭐), and a long tail of React, JS, and tooling libraries. I've also shipped **Rust systems work** — notably contributing to **[FuelLabs/data-systems](https://github.com/FuelLabs/data-systems)**, the official data-streaming libraries for the Fuel Network. Today, most of my work lives at the intersection of **agents, local-first runtimes, and developer experience**.

---

### Tech I ship with

![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Bun](https://img.shields.io/badge/-Bun-000000?style=flat&logo=bun&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/-Codex-412991?style=flat&logo=openai&logoColor=white)
![CLI](https://img.shields.io/badge/-CLI-4D4D4D?style=flat&logo=gnu-bash&logoColor=white)
![MCP](https://img.shields.io/badge/-MCP-6E40C9?style=flat&logoColor=white)

---

## 🧭 Start here

If you only have a minute, these are the projects I'd point you to first:

- 🎼 **[compozy](https://github.com/compozy/compozy)** — Orchestrate AI coding agents from idea to shipped code, in one pipeline. *(2.2k+ ⭐)*
- 🏢 **[agh](https://github.com/compozy/agh)** — An open workplace for AI agents — local-first runtime with durable sessions and agent-to-agent networking.
- 📚 **[kb](https://github.com/compozy/kb)** — Build topic-based knowledge bases from code, URLs, files and YouTube. Obsidian-compatible vaults, zero cloud deps.
- 📓 **[skeeper](https://github.com/compozy/skeeper)** — Version PRDs, tech specs, ADRs and AI plans in a sidecar Git repo — without polluting your main PRs.
- 🔁 **[codex-loop](https://github.com/compozy/codex-loop)** — Keep Codex tasks running until they actually finish — by time, rounds, or independently confirmed goal.
- 🧩 **[skills](https://github.com/pedronauck/skills)** — My curated collection of **126 agent skills** for Claude Code and compatible assistants. *(375+ ⭐)*

---

## 🎼 The Compozy ecosystem — *the agent harness*

The core thesis: AI agents are powerful but unreliable on their own. They need a **harness** — orchestration, durable state, peer discovery, knowledge, and quality gates — to turn one-shot generations into shippable software. This is what we're building at [@compozy](https://github.com/compozy).

### Orchestration & runtime

| Project | What it does |
| --- | --- |
| 🎼 **[compozy](https://github.com/compozy/compozy)** | CLI that drives the full lifecycle of AI-assisted dev — PRDs → specs → tasks → concurrent execution → code review remediation. *(Go, 2.2k+ ⭐)* |
| 🏢 **[agh](https://github.com/compozy/agh)** | An open workplace for AI agents. Runs Claude Code, Codex, OpenClaw and friends as durable, inspectable sessions with peer-to-peer capability sharing over the open `agh-network/v0` protocol. *(Go)* |
| 🧠 **[go-orchestrator](https://github.com/compozy/go-orchestrator)** | Next-level agentic orchestration framework. *(Go)* |
| 🌉 **[arky](https://github.com/compozy/arky)** | LLM providers bridge and SDK in Rust. *(Rust)* |

### Quality loops & QA

| Project | What it does |
| --- | --- |
| 🔁 **[codex-loop](https://github.com/compozy/codex-loop)** | Release-grade QA loop for Codex CLI. Iterates until duration / rounds / goal targets are met — not just on the first plausible answer. *(Go)* |
| 🔁 **[cc-loop](https://github.com/compozy/cc-loop)** | Same harness, but wired into Claude Code lifecycle hooks. *(Go)* |

### Knowledge & spec tooling

| Project | What it does |
| --- | --- |
| 📚 **[kb](https://github.com/compozy/kb)** | Build LLM-ready knowledge bases from code, URLs, files and YouTube. Outputs Obsidian-compatible vaults with codebase metrics, dead-code detection and semantic search. *(Go)* |
| 📓 **[skeeper](https://github.com/compozy/skeeper)** | Sidecar Git repo for spec artifacts. Keeps PRDs, ADRs, and AI plans versioned and diffable — separate from main-branch noise. *(Go)* |
| 🕸️ **[gograph](https://github.com/compozy/gograph)** | Go codebase graph analyzer. Powers structural queries for agents working in large Go repos. *(Go)* |

### Distribution

| Project | What it does |
| --- | --- |
| 🍺 **[homebrew-compozy](https://github.com/compozy/homebrew-compozy)** | Official Homebrew tap for the Compozy CLI suite. |

---

## 🛠️ Personal tools & scaffolds

| Project | What it does |
| --- | --- |
| 🧩 **[skills](https://github.com/pedronauck/skills)** | 126 curated agent skills across original work, hand-picked community gems, marketing playbooks, and broader dev tooling. *(375+ ⭐)* |
| 🪜 **[devstack](https://github.com/pedronauck/devstack)** | Full-stack scaffold generator — Bun + Turborepo + React 19 + Hono + Drizzle + Postgres in minutes, not days. *(TS)* |
| 🪜 **[go-devstack](https://github.com/pedronauck/go-devstack)** | Same idea, Go edition. |

---

## 🪦 OSS classics — *the React/JS era*

A selection of projects I'm best known for from my pre-AI life. Several are archived or in maintenance mode, but they shipped to a lot of people.

| Project | What it is | ⭐ |
| --- | --- | --- |
| **[docz](https://github.com/doczjs/docz)** | ✍️ "It has never been so easy to document your things." MDX-based docs framework. *(archived)* | 23.6k |
| **[react-adopt](https://github.com/pedronauck/react-adopt)** | 😎 Compose render-props components like a pro. | 1.6k |
| **[reworm](https://github.com/pedronauck/reworm)** | 🍫 The simplest way to manage state. | 1.4k |
| **[micro-router](https://github.com/pedronauck/micro-router)** | 🚉 A tiny, functional router for Zeit's Micro. | 615 |
| **[react-video](https://github.com/pedronauck/react-video)** | 🎞 React component to load video from Vimeo or YouTube across any device. | 274 |
| **[react-simpletabs](https://github.com/pedronauck/react-simpletabs)** | Just a simple tabs component built with React. | 184 |
| **[algorithms-with-es6](https://github.com/pedronauck/algorithms-with-es6)** | Classic algorithms implemented in modern JavaScript. | 159 |
| **[reicons](https://github.com/pedronauck/reicons)** | 💅 Bundle your SVGs into fully customized React components. | 111 |
| **[gatsby-starter-docz](https://github.com/pedronauck/gatsby-starter-docz)** | 📝 Gatsby starter with Docz + a blog for your docs. | 90 |
| **[frontend-styleguide](https://github.com/pedronauck/frontend-styleguide)** | Keep your frontend code clean, legible and beautiful. | 70 |
| **[yarn-workspaces-example](https://github.com/pedronauck/yarn-workspaces-example)** | One of the earliest public examples of Yarn monorepos. | 45 |
| **[oneoften](https://github.com/pedronauck/oneoften)** | Tips, tricks and tutorials on "How to build a large-scale JS application." | 44 |
| **[which-licenses-i-have](https://github.com/pedronauck/which-licenses-i-have)** | 📝 Learn about the licenses around your packages. | 30 |
| **[storz](https://github.com/pedronauck/storz)** | Global state machines, made easy. | 21 |

---

## ⚡ What I'm doing now

- Shipping **Compozy** and the surrounding agent stack
- Running multiple agent instances concurrently as a daily driver — and learning what breaks
- Writing and speaking about **agentic engineering**: how teams should actually adopt agents in production
- Sponsoring open-source builders I rely on ([@raphamorim](https://github.com/raphamorim))

---

## 🤝 Let's connect

- 𝕏 / Twitter — [@pedronauck](https://twitter.com/pedronauck) (personal) · [@compozyai](https://twitter.com/compozyai) (product)
- 🌐 Website — [compozy.com](https://compozy.com)
- 📦 Orgs — [@compozy](https://github.com/compozy) · [@doczjs](https://github.com/doczjs)

---

<sub>📍 San Francisco · 🇧🇷 → 🇺🇸 · Coffee-powered · Always shipping</sub>
