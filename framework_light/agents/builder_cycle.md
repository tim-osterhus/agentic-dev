# Builder Cycle

## Purpose
Single-task execution loop. Keep scope narrow, diffs small, and leave a reproducible trail for QA.

## Inputs
- Active card: `workflow/tasks.md`  
- Expectations and constraints: `workflow/expectations.md`  
- Context: `workflow/outline.md` and recent `workflow/historylog.md`  
- Roles: `agents/roles/*.md` (pick the right specialization)

## Steps
1) Intake: Restate the goal, constraints, and risks from `workflow/tasks.md` and `workflow/expectations.md`.  
2) Plan: Draft 3–7 checkpoints and map each to a role (backend/frontend/infra/tests). Note the plan in your own scratchpad before editing files.  
3) Execute: Work one checkpoint at a time using the matching role guidance. Keep edits small; log commands, decisions, and blockers in `workflow/historylog.md`.  
4) Self-check: Run fast, relevant tests/lints. Capture commands and results in `workflow/historylog.md`.  
5) Handoff: Summarize scope, files touched, and test outcomes for QA, then point them to `agents/qa_cycle.md`.

## Handoff Template
- Scope covered: …  
- Files touched: …  
- Commands/tests run + results: …  
- Known gaps/blockers: …  
- Notes added to `workflow/historylog.md`: Y/N (where?)
