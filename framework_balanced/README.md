# framework_balanced

Adds prompt refinement and light automation on top of the minimal profile. Runs as a standalone, drop-in flow with Builder + QA discipline, a prompt-engineering pre-cycle, an autoscheduler, and a GitHub push loop.

## How to use (humans)
- Drop this folder into your repo. Keep the file `tell the agent to open README.md and follow instructions.txt` so the agent knows where to start.
- Ask your agent to open this `README.md` and follow the startup steps below.
- Provide project context by answering **Context to capture** and filling `workflow/roadmap.md`, `workflow/tasks_backlog.md`, or `workflow/tasks.md`.

## How to start (agents)
1) Open `agents/_entrypoint.md`.  
2) Run `agents/prompt_engineering_cycle.md` for any new task.  
3) Execute via `agents/builder_cycle.md` using the right role in `agents/roles/*.md`.  
4) QA via `agents/qa_cycle.md`; if approved, follow `workflow/github_push_cycle.md`.  
5) Scheduling: use `workflow/autoscheduler.md` to pull from `workflow/tasks_backlog.md` into `workflow/tasks.md`. Log decisions in `workflow/historylog.md`.

## Flow summary
- **Autoscheduler** moves backlog → **tasks** → **Prompt Engineering** → **Builder** → **QA** → **Push** (commit/push) → **Historylog** updated.  
- **Outline/Roadmap** guide priorities; **Expectations** set quality bar.

## Context to capture (answer briefly, paste where relevant)
- What is the project/repo for, and current priority?  
- Tech stack, tooling, and deployment constraints?  
- Forbidden areas or risky files?  
- Required tests/commands before QA and before push?  
- Branching/commit rules?

## File map
- `tell the agent to open README.md and follow instructions.txt` — cue file for agents.  
- `agents/` — entrypoint, prompt engineering, builder/QA cycles, roles.  
- `workflow/` — tasks, backlog, autoscheduler, expectations, outline, roadmap, history, GitHub push cycle.
