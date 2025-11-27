# Builder Cycle

## Purpose
Parallel-friendly execution loop. Keeps each session aligned to plan, avoids conflicts, and leaves clear traces for QA and Orchestrator.

## How it interacts with other files
Consumes tasks from `workflow/tasks.md` via `workflow/autoscheduler.md`, follows `workflow/concurrency_playbook.md`, `workflow/resource_budgeting.md`, and logs to `workflow/historylog.md`. Handoffs go to `agents/qa_cycle.md` or `agents/deep_qa_cycle.md`.

## Steps
1) Intake: Read refined prompt, `workflow/tasks.md`, `workflow/expectations.md`, and session details in `workflow/session_registry.md`; restate scope and dependencies.  
2) Plan: Draft checkpoints mapped to roles; note collision risks per `workflow/concurrency_playbook.md` and resource limits per `workflow/resource_budgeting.md`.  
3) Execute: One checkpoint at a time using the right role guidance; log commands/results with session ID in `workflow/historylog.md`.  
4) Self-check: Run targeted tests; record outcomes and resource usage if relevant.  
5) Handoff: Summarize scope, files touched, and test outcomes for QA or `agents/deep_qa_cycle.md`; flag unresolved conflicts for `agents/roles/orchestrator.md`.
