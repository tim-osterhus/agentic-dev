# Autoscheduler

## Purpose
Assigns backlog items to sessions to keep pipelines full without overloading resources.

## How it interacts with other files
Pulls from tasks_backlog.md, updates tasks.md, respects resource_budgeting.md, and records choices in historylog.md for transparency.

## Steps
1) Evaluate readiness: priority, dependencies, and clarity in `tasks_backlog.md`.  
2) Match tasks to sessions in `workflow/session_registry.md` using capacity and skills.  
3) Check `workflow/resource_budgeting.md` before activating; reserve resources if needed.  
4) Move task to `workflow/tasks.md`, note collisions, and log the decision in historylog.md.  
5) Trigger prompt_engineering_cycle.md for each activated task.

## Safeguards
- Limit concurrent tasks per session; honor conflict rules in concurrency_playbook.md.  
- Defer tasks lacking clarity; request backlog updates first.  
- Pause scheduling if QA/deep QA backlog grows.
