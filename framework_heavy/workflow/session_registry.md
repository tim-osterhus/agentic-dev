# Session Registry

## Purpose
Registry of active agent sessions, their roles, resources, and status.

## How it interacts with other files
Referenced by autoscheduler.md for assignments, by orchestrator.md for coordination, and by resource_budgeting.md for usage tracking.

## How to use
- Create an entry when a session starts; update status and check-ins on a cadence.  
- Link each entry to `workflow/tasks.md` items and history log entries.  
- Note reservations so `workflow/resource_budgeting.md` stays accurate.

## Template
- Session ID / owner / role  
- Task assignment(s) and status (open/paused/closed)  
- Environment or workspace notes  
- Resource reservations (compute/credits/time)  
- Links to historylog entries and prompts  
- Last sync timestamp and next check-in
