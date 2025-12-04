# framework_heavy

High-throughput, parallel-friendly framework. Supports multiple web/CLI agents, deeper QA layers, resource budgeting, and orchestrated scheduling. Drop-in ready for multi-session work.

## How to use (humans)
- Drop this folder into your repo. Keep the file `tell the agent to open README.md and follow instructions.txt` so the agent knows where to start.
- Ask your agent to open this `README.md` and follow the startup steps below.
- Provide project context via **Context to capture** and populate `workflow/roadmap.md`, `workflow/tasks_backlog.md`, `workflow/resource_budgeting.md`, and `workflow/session_registry.md`.

## How to start (agents)
1) Open `agents/_entrypoint.md`.  
2) Register sessions in `workflow/session_registry.md`; note collision rules in `workflow/concurrency_playbook.md` and limits in `workflow/resource_budgeting.md`.  
3) Pull work from `workflow/tasks_backlog.md` using `workflow/autoscheduler.md` into `workflow/tasks.md`.  
4) Run `agents/prompt_engineering_cycle.md` → `agents/builder_cycle.md` with roles from `agents/roles/*.md`.  
5) QA via `agents/qa_cycle.md`; escalate to `agents/deep_qa_cycle.md` for high-risk items.  
6) Coordinate pushes with the orchestrator role and log everything in `workflow/historylog.md`.

## Flow summary
- **Autoscheduler** + **Session registry** assign tasks → **Prompt Engineering** → **Builder** (per session) → **QA/Deep QA** → orchestrated push → **Historylog**.  
- **Concurrency playbook** and **Resource budgeting** govern safety and capacity; **Web agents** defines remote access rules.

## Context to capture (answer briefly, paste where relevant)
- What is the project/repo for, and current priority?  
- Tech stack, infra, and deployment constraints?  
- Forbidden areas or risky files/services?  
- Required tests/commands before QA, deep QA, and push?  
- Branch/commit rules and release cadence?  
- Resource budgets (time/credits/compute) per session/task?

## File map
- `tell the agent to open README.md and follow instructions.txt` — cue file for agents.  
- `agents/` — entrypoint, prompt engineering, builder/QA/deep QA cycles, roles (incl. orchestrator).  
- `workflow/` — tasks/backlog, autoscheduler, session registry, concurrency playbook, resource budgeting, web agents, expectations, outline, roadmap, history.
