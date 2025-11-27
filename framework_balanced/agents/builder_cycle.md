# Builder Cycle
## Purpose
Execute a single task with prompt refinement in front and clear QA/push handoffs. Balance speed with traceability.

## Inputs
- Refined prompt: `agents/prompt_engineering_cycle.md` output  
- Active card: `workflow/tasks.md`; backlog via `workflow/autoscheduler.md`  
- Expectations: `workflow/expectations.md`; context in `workflow/outline.md` and `workflow/historylog.md`  
- Roles: `agents/roles/*.md`

## Steps
1) Intake: Read the refined prompt, `workflow/tasks.md`, and `workflow/expectations.md`; restate scope, constraints, and risks.  
2) Plan: Draft checkpoints mapped to roles (backend/frontend/infra/tests); keep 3–7 items.  
3) Execute: Work one checkpoint at a time using the matching role guidance. Log commands, decisions, and blockers in `workflow/historylog.md`.  
4) Self-check: Run targeted tests/lints; capture commands and results in `workflow/historylog.md`.  
5) Handoff: Summarize scope, files touched, and test outcomes for QA; direct them to `agents/qa_cycle.md`.  
6) After QA approval, support `workflow/github_push_cycle.md` (tests rerun, commit, push) and note the result in `workflow/historylog.md`.
