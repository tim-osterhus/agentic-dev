# Prompt Engineering Cycle

## Purpose
Refine prompts for multi-session workloads so parallel agents stay aligned and avoid rework.

## How it interacts with other files
Runs before builder_cycle.md instances start, using `workflow/tasks.md`, `workflow/session_registry.md`, and `workflow/historylog.md` to tailor prompts per session. Coordinates with orchestrator.md for conflict checks.

## Steps
1) Read the active tasks and session assignments; note overlaps, constraints, and resource limits from `workflow/resource_budgeting.md`.  
2) Draft/refine prompts per session/role; call out dependencies, boundaries, and collision risks.  
3) Share prompts with Builders/QA and `agents/roles/orchestrator.md`; log versions and open questions in `workflow/historylog.md`.  
4) Update prompts if scope or conflicts change; keep `workflow/tasks.md` and `workflow/session_registry.md` in sync.
