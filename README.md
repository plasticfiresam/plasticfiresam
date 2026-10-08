# Mobile and Web Developer

I’m a passionate **mobile developer** with **7+ years of experience in IT**, specializing in **Flutter** for cross-platform app development. I also enjoy diving into **CI/CD processes** and various **automation tasks**, ensuring smooth and efficient workflows. Additionally, I’m currently exploring **web development** with **React** and **Next.js**, expanding my skill set to build scalable, high-performance solutions.

---

## 📂 Experience
- **Surf Studio ([surf.dev](https://surf.dev))**  
  *Senior Developer, Flutter Lead*  
  *(September 2026 – Now)*

- **Independent developer**
 *Mobile and Frontend developer capable of architecture design of complex systems*

- **Solutions4Future** ([solutions4future.ru](https://solutions4future.ru)) (*subsidiary of Unilever RuBy*)  
  *Lead Developer for HR Products*  
  *(Sep 2024 - Sep 2025)*

- **Surf Studio ([surf.dev](https://surf.dev))**  
  *Senior Developer, ex-Tech Lead, and Pre-Sale Lead*  
  *(June 2022 – Aug 2024)*

- **Enlighted Digital ([enlighted.ru](https://enlighted.ru))**  
  *Mobile Developer*  
  *(Aug 2019 – June 2022)*

- **Paraweb LLC ([paraweb.me](https://paraweb.me))**  
  *Frontend and Mobile Developer*  
  *(June 2017 – June 2022)*

---

## 🤖 AI-First Development

Since January 2026 everything I build goes through AI tools. Over the year it grew from using an agent as a debugger or copilot into an AI-first workflow: coding agents close tasks end to end, and I own the specification, acceptance criteria, quality gates and review.

### How it evolved

- **Q1 — AI as a debugger.** Cursor and its agent for investigating and fixing bugs in existing production projects.
- **Q2 — Spec-driven development.** Hand-written specifications (functional, API and non-functional requirements, user scenarios) and Figma MCP integration. Agents implemented features in parallel with my own work in the same project.
- **Q3 → now — AI-first.** Tasks are closed by agents (Claude Code, Codex, and Cursor until June 2026) running in parallel in isolated environments. In existing projects I build the infrastructure for agentic development; new products are built entirely with AI.

### Making existing projects agent-ready

- Machine-checkable quality gates that agents run before handing work over: feature boundaries, design tokens, CSS layers, typecheck baselines, API contract checks. Tools report JSON with per-stage timings.
- Task tracker integration through CLI (Yandex Tracker, Jira, GitHub, GitLab): requirement readiness checks, iterating with the task author, status transitions, packaged task inputs.

### Products built with AI

Project names are under NDA, so they are described by type.

- **Showcase website and CMS for a large sports and entertainment complex.** Nuxt 4 SSR site in three languages and a Laravel + Filament CMS with a public API for the site and the mobile app. The agent workflow is automated end to end: a Figma page is split into sections, and each section goes through an autopilot — spec from Figma → layout → browser screenshots → metric and pixel diff → independent judge agents (composition, adaptive, details) that see only images, never the code — until it converges.
- **E-commerce mobile apps (Flutter):** a fashion retail app (catalog, cart, checkout, loyalty, AI assistant), a restaurant chain ordering and loyalty app with its backend, an online pharmacy client ported from a web prototype, and a clinic appointment booking app.
- **AI-first design pipeline for mobile apps (pilot).** A designer describes the UI, an agent writes the Flutter layout inside a dedicated UI package behind a typed per-screen contract, and acceptance is based on golden images. A Next.js + Tailwind prototype serves as an executable spec; a gate traces every numeric constant in the Flutter client back to its source in the prototype.
- **Food service apps:** a food ordering app and a cashier app for a food court platform, maintained and modernized with agents.
- **Fitness coaching platform:** Flutter monorepo with two apps for iOS and Android (chat, WebRTC calls, video).
- **Corporate AI code review service for GitLab.** Reviews merge requests with the Claude Agent SDK in read-only mode and posts inline discussions with severity and suggestions. Review rules come from the project's `AGENTS.md`/`CLAUDE.md`; the admin panel shows the agent transcript and cost of every run.
- **Build distribution portal:** receives Flutter builds from GitLab CI; Android and iOS OTA installs, public links with QR codes, notifications to the task tracker.
- **SaaS for sports coaches:** subscriptions, schedule, attendance, billing, training plans. Go + Vue.
- **Mobile game prototype:** Godot 4 roguelite shooter.
- **Utilities:** a Figma link redirector that maps the design owner's links to the file copies developers can access; agent orchestration monitoring.

### Tooling for agentic development

- **Task dispatcher for coding agents.** A task can't start until release authority and acceptance criteria are agreed (the agreement is locked by hash); then launch, watch, delivery gate and acceptance. Built after analyzing an agent loop that produced 441 messages and zero delivered tasks in a day.
- **Multi-agent orchestration:** parallel Claude Code and Codex sessions in terminal workspace managers (herdr, Orca) under a coordinator agent.
- **Agent telemetry:** Claude Code and Codex → OpenTelemetry → Prometheus, Loki, Grafana to track agents' cost, time and behavior; a hook-based activity log with scheduled digests.
- **Versioned agent configuration:** shared rules for coding, Git and task trackers across Claude Code, Codex and Pi; shared skills; a reproducible dev environment with pinned CLI tools.
- **Instructions backed by data:** global rules derived from clustering 2,200+ of my own prompts; A/B behavioral evals of `AGENTS.md` variants.

---

## 🛠️ Skills

- **Mobile Development:** Flutter, Dart, Swift/Kotlin  
- **Web Development:** React, Next.js, Angular 2+, TypeScript, HTML/CSS, Deno  
- **AI Development:** Claude Code, Codex, Cursor, Claude Agent SDK, MCP (Figma), OpenSpec, skills, subagents, hooks, spec-driven development  
- **Tools & Practices:** Git, Firebase, RESTful API, CI/CD, SOLID  
