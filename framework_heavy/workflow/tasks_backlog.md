# Tasks Backlog

## Purpose
Source queue for upcoming work to feed multiple sessions.

## How it interacts with other files
Autoscheduler.md pulls from here, product_architect.md curates entries, and orchestrator.md uses it to balance workloads.

## How to use
- Keep highest-priority ready items at the top; include resource needs and dependencies.  
- Use `workflow/autoscheduler.md` to move items into `workflow/tasks.md` with session assignments.  
- If unclear, add questions and leave unscheduled until clarified by `agents/roles/product_architect.md`.

## Template
- Priority, complexity, and risk tags: …  
- Description, constraints, and desired outcomes: …  
- Dependencies and resource needs: …  
- Suggested roles/sessions: …  
- Pre-work needed before activation (design, data, env): …
