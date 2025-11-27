# Entrypoint

## Purpose
Global kickoff for multi-session work. Sets scope, constraints, resource caps, and routing rules for Builders, QA, and Orchestrator.

## How it interacts with other files
Directs agents to `agents/prompt_engineering_cycle.md`, `agents/builder_cycle.md`, `agents/qa_cycle.md`, and `agents/deep_qa_cycle.md`. Coordinates with `agents/roles/orchestrator.md`, `workflow/session_registry.md`, `workflow/concurrency_playbook.md`, `workflow/resource_budgeting.md`, and `workflow/autoscheduler.md`.

## Steps
1) Set objectives, constraints, and resource budgets for this run using `workflow/expectations.md` and `workflow/resource_budgeting.md`.  
2) Register sessions, owners, and environments in `workflow/session_registry.md`; note concurrency rules in `workflow/concurrency_playbook.md`.  
3) Pull work via `workflow/autoscheduler.md` into `workflow/tasks.md`, then run `agents/prompt_engineering_cycle.md` before each `agents/builder_cycle.md`.  
4) Define QA depth (baseline vs `agents/deep_qa_cycle.md`) and escalation paths to `agents/roles/orchestrator.md` for conflicts or capacity changes.  
5) Log decisions and risks in `workflow/historylog.md`.
