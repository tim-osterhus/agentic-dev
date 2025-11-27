# Prompt Engineering Cycle
## Purpose
Refine task/system prompts before the Builder acts to reduce churn and clarify constraints.

## Inputs
- Active card: `workflow/tasks.md` (or candidate from `workflow/tasks_backlog.md`)  
- Quality bar: `workflow/expectations.md`  
- Context: `workflow/outline.md`, `workflow/roadmap.md`, and `workflow/historylog.md`

## Steps
1) Intake: Read the task and expectations; list ambiguities, dependencies, and constraints.  
2) Draft prompt: Create or refine the system/user prompt for this task; keep scope tight and cite acceptance checks.  
3) Share: Post the refined prompt, open questions, and decisions to `workflow/historylog.md`; brief Builder and QA.  
4) Adjust: If scope or dependencies change, request updates to `workflow/tasks_backlog.md`, `workflow/outline.md`, or `workflow/roadmap.md` before Builder starts.  
5) Handoff: Point Builder to `agents/builder_cycle.md` with the finalized prompt. Re-run this cycle if the task resets.
