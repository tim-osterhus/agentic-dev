# framework_light

Minimal Builder + QA loop with the fewest moving parts. Single-task-at-a-time, single-session focus. Designed to be dropped into any repo and run immediately.

## How to use (humans)
- Drop this folder into your repo. Keep the file `tell the agent to open README.md and follow instructions.txt` so the agent knows where to start.
- Ask your agent to open this `README.md` and follow the startup steps below.
- Provide project context by answering the prompts in **Context to capture** and filling `workflow/roadmap.md`, `workflow/tasks_backlog.md`, or `workflow/tasks.md` as needed.

## How to start (agents)
1) Open `agents/_entrypoint.md` for the kickoff brief.  
2) If building, follow `agents/builder_cycle.md` and the relevant role in `agents/roles/*.md`.  
3) If validating, follow `agents/qa_cycle.md`.  
4) Track work in `workflow/tasks.md`; keep `workflow/historylog.md` updated.

## Flow summary
- **Entrypoint** → picks role → **Builder** runs plan → logs to **historylog** → **QA** verifies → close in **tasks/historylog**.  
- **tasks_backlog** feeds **tasks**; **outline** and **roadmap** keep direction; **expectations** sets quality bar.

## Context to capture (answer briefly, paste where relevant)
- What is the project/repo for, and current priority?  
- Tech stack and tooling constraints?  
- Forbidden areas or risky files?  
- Required tests/commands before accepting work?  
- Branching/push rules?

## File map
- `tell the agent to open README.md and follow instructions.txt` — cue file for agents.  
- `agents/` — entrypoint, cycles, roles.  
- `workflow/` — tasks, backlog, expectations, outline, roadmap, history.***
