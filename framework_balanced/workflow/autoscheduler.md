# Autoscheduler

## Purpose
Lightweight pull scheduler that moves work from `tasks_backlog.md` into `tasks.md` without overloading the session.

## How to use
- Run after QA completes or on a cadence to keep one active task in flight.  
- Coordinate with `agents/prompt_engineering_cycle.md` before Builder starts.  
- Update `workflow/historylog.md` with each scheduling decision.

## Steps
1) Pick the highest-priority ready item; confirm dependencies and capacity.  
2) Assign owner/role, add to `tasks.md`, and link any context files.  
3) Trigger prompt_engineering_cycle.md for the new task.  
4) Record the scheduling decision in `workflow/historylog.md`.

## Safeguards
- Limit concurrent active tasks to the team’s capacity.  
- Defer items lacking clarity; request backlog updates first.  
- Pause scheduling if QA debt accumulates.
