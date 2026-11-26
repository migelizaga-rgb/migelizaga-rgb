### Hi, I'm Miguel 👋

AI/agent engineer. I design the guardrails that let coding agents ship to production safely, and I'm looking for teams building agent systems and LLM tooling.

I build and run AI-agent systems in production: a self-hosted agent gateway with
scheduled jobs, human approval gates on every outbound action, and a CI/deploy
pipeline where most of the code is written by coding agents and reviewed by risk
tier.

#### Featured

| Project | What it shows |
|---|---|
| [coding-agent-playbook](https://github.com/migelizaga-rgb/coding-agent-playbook) | The operating system I use for Claude Code + Codex: risk-tiered review, cheap/strong model routing, low-token handoffs, a deploy queue so agents never deploy concurrently. Tested, drop-in templates and skills. |
| [self-hosted-agent-case-study](https://github.com/migelizaga-rgb/self-hosted-agent-case-study) | Case study of running a personal agent gateway in production: guarded deploys of owner-edited live code, version-pinned hot-patches that fail loud on upstream drift, approval-gated actions. With runnable examples. |
| [agent-apple-bridge](https://github.com/migelizaga-rgb/agent-apple-bridge) | Swift macOS service giving AI agents guarded access to Contacts, Messages, Notes and Reminders over a Unix socket, with an outbound guard and secret redaction. |
| [tool-action-classifier](https://github.com/migelizaga-rgb/tool-action-classifier) | Dependency-free library that classifies agent tool calls as read-only, reversible or irreversible so a runtime knows what needs human approval. Fails closed. |
| [openclaw-places-tools](https://github.com/migelizaga-rgb/openclaw-places-tools) · [openclaw-google-cli-tools](https://github.com/migelizaga-rgb/openclaw-google-cli-tools) | OpenClaw plugins: Google Places search/details, and a compact tool surface over the `gog` Google CLI. |
| [AIPM-Asana-021-Miguel](https://github.com/migelizaga-rgb/AIPM-Asana-021-Miguel) | Records-management UI prototype built with an AI-assisted product-management workflow. |

#### Open-source contributions

- **openclaw/openclaw**: [fix(memory): explain unpromoted candidates in dreaming reports](https://github.com/openclaw/openclaw/pull/145458) (merged)
- **openclaw/crabbox**: [deliver secrets to new Sprites as root-only files, never in config or argv](https://github.com/openclaw/crabbox/pull/2956) (open)
- **openclaw/crabbox**: [fixed lease IDs and keep heartbeated leases awake](https://github.com/openclaw/crabbox/pull/2877) (open)

#### Stack

TypeScript / Node · Bash · Go (reading/contributing) · GitHub Actions · launchd · Claude Code · Codex
