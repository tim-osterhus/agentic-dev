# Tasks (Active)

## Purpose
List of active tasks being executed across sessions.

## How it interacts with other files
Populated by autoscheduler.md, referenced by builder_cycle.md and qa_cycle.md, and linked to session_registry.md for ownership.

## How to use
- Keep only in-flight tasks here; archive completions to `workflow/historylog.md`.  
- Each task should point to a session in `workflow/session_registry.md`.  
- Pull new tasks from `workflow/tasks_backlog.md` via `workflow/autoscheduler.md`.

## Template
- Task ID / owner / session ID: …  
- Scope and constraints: …  
- Acceptance criteria and required tests: …  
- Dependencies and collision notes: …  
- Links to prompts, historylog entries, and roadmap references: …  
- Status and next checkpoint: …
