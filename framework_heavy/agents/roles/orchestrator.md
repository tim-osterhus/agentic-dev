# Role: Orchestrator

## Purpose
Coordinate multiple agent sessions, resolve conflicts, and ensure throughput stays aligned with resource budgets.

## How it interacts with other files
Owns session_registry.md updates, enforces concurrency_playbook.md rules, and triggers deep_qa_cycle.md or resource_budgeting.md interventions when needed.

## When to activate
- Coordinating more than one active session, resolving collisions, or managing resource constraints.

## Checklist
- Maintain `workflow/session_registry.md` with owners, statuses, environments, and reservations.  
- Enforce `workflow/concurrency_playbook.md`; reassign or pause work to avoid collisions.  
- Watch `workflow/resource_budgeting.md`; throttle or pause sessions when limits approach.  
- Trigger `agents/deep_qa_cycle.md` for high-risk items and keep `workflow/historylog.md` updated after each cadence.
