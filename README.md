# Hi, I'm `blockedby`

Senior Backend & Applied AI Engineer focused on agentic developer tooling, production backends, and practical automation.

I build coding-agent systems as bounded, inspectable engineering infrastructure: explicit tools, reusable skills, isolated runtimes, multi-model delegation, and evidence-backed verification.

## Current focus

- Pi/Pipi runtime and workflow tooling
- Agent Skills for code review, browser automation, GitHub planning, and completion verification
- Multi-agent orchestration across Pi, Codex, Claude, Luna, and Terra
- Deterministic web evidence with optional LLM-assisted interpretation
- Backend systems in Go and TypeScript/Node.js
- Production debugging, observability, CI/CD, and Linux automation

## Selected work

### [Pipi](https://github.com/blockedby/my-pi-setup) — my current agent environment

An isolated Pi setup with its own pinned runtime and `~/.pipi` state. It brings together subagent profiles, parallel workflows, background terminals, browser tooling, Codex-backed tools, reusable skills, and a dark GitHub-style interface without replacing a regular Pi installation. My integration work is maintained in a public fork of [`davis7dotsh/my-pi-setup`](https://github.com/davis7dotsh/my-pi-setup).

### [plan-gh-backlog](https://github.com/blockedby/plan-gh-backlog)

An Agent Skill and Python CLI that turns structured roadmaps into validated, dependency-aware GitHub backlogs. It supports deterministic batch planning and conflict-safe, idempotent publication of labels, milestones, epics, tasks, checklists, and native sub-issues.

### [Evidence-Driven Code Review](https://github.com/blockedby/gpt5.6-reviewer)

A review skill and contract toolkit that separates confidence from impact, routes only verified serious regressions back as blockers, and keeps closure review focused on the exact remediation surface.

### [pi-codex-tools](https://github.com/blockedby/pi-codex)

Pi tools for deterministic web search/fetch, Codex-assisted summaries, patch validation, and bounded delegated coding tasks with structured outputs, sandboxes, timeouts, and debug evidence.

### [browser-chrome skill](https://github.com/blockedby/browser-chrome-skill)

A portable Agent Skills package for safe Chrome DevTools automation, with disposable headless sessions for public checks and a separate persistent headed mode for authenticated browser work.

### [Kwispr](https://github.com/blockedby/kwispr)

My actively developed fork of [`MaksBoi/kwispr`](https://github.com/MaksBoi/kwispr): Linux voice dictation for Wayland/KDE with cloud, OpenRouter, and local/offline STT; a Rust inference runtime; native KDE shortcuts and tray UI; rootless installation; and optional trusted-LAN inference.

## Reusable Agent Skills

I maintain a public [general-purpose skill set](https://github.com/blockedby/pi-agent-setup/tree/main/skills/general) used across my Pi/Pipi workflows:

- [`backend-quality`](https://github.com/blockedby/pi-agent-setup/tree/main/skills/general/backend-quality) — API, storage, validation, auth, idempotency, and data-safety review;
- [`frontend-quality`](https://github.com/blockedby/pi-agent-setup/tree/main/skills/general/frontend-quality) — frontend implementation and UI-quality checks;
- [`devops-quality`](https://github.com/blockedby/pi-agent-setup/tree/main/skills/general/devops-quality) — configuration, CI, containers, deployment, and runtime readiness;
- [`visual-composition`](https://github.com/blockedby/pi-agent-setup/tree/main/skills/general/visual-composition) — product-quality visual hierarchy, responsive composition, states, and interaction polish;
- [`completion-verification`](https://github.com/blockedby/pi-agent-setup/tree/main/skills/general/completion-verification) — fresh acceptance evidence before readiness or completion claims;
- [`git-branching`](https://github.com/blockedby/pi-agent-setup/tree/main/skills/general/git-branching) — safe PR-first branches, worktrees, rebases, and synchronization;
- [`browser-chrome`](https://github.com/blockedby/browser-chrome-skill) — controlled headed and disposable headless Chrome automation;
- [`explanatory-html-pages`](https://github.com/blockedby/pi-agent-setup/tree/main/skills/general/explanatory-html-pages) — self-contained technical explainers with readable diagrams;
- [`modern-skill-revising`](https://github.com/blockedby/pi-agent-setup/tree/main/skills/general/modern-skill-revising) — focused context and instruction design for modern models.

The standalone [`code-review`](https://github.com/blockedby/gpt5.6-reviewer/tree/main/skills/code-review) and [`plan-gh-backlog`](https://github.com/blockedby/plan-gh-backlog) skills extend this set with evidence-driven review and deterministic GitHub backlog publication.

## Additional public engineering work

- [Go OpenRouter SDK work](https://github.com/blockedby/go-openrouter) — fork/contribution work around streaming, reasoning, tool calling, structured outputs, prompt caching, multimodal inputs, and usage fields.
- [vibe-practicum-vpn](https://github.com/blockedby/vibe-practicum-vpn) — public-safe Linux/KDE VPN and routing automation, test labs, guarded operations, and redacted diagnostics.
- [Agentic Engineering Lab](https://github.com/blockedby/agentic-engineering-lab) — the broader index of public tooling, workflows, OSS evidence, and sanitized case studies.

## How I work

I prefer small, sharp PRs with explicit acceptance criteria and fresh evidence:

1. define the problem, constraints, and success conditions;
2. split work into bounded, conflict-aware slices;
3. delegate exploration, implementation, and audit to the right model or tool;
4. keep deterministic evidence separate from model interpretation;
5. verify with focused tests, builds, static checks, browser probes, or API evidence;
6. record what changed, why, and what remains risky.

## Background

Previously worked across high-load backend systems, DeFi/Web3 infrastructure, smart contracts, fintech workflows, CI/CD, and team leadership.

Main stack: Go, TypeScript/Node.js, PostgreSQL, Redis, Docker, Kubernetes, Linux, Solidity.

Open to Applied AI Engineer, AI Tooling Engineer, Forward-Deployed Software Engineer, Backend AI Platform, and Founding Engineer roles.
