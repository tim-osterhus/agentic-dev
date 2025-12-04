# QA Cycle
## Purpose
Verify Builder output against expectations and prepare for push. Close the loop or route fixes.

## Inputs
- Active card: `workflow/tasks.md`  
- Expectations: `workflow/expectations.md` (authored/updated by QA before validation)  
- Refined prompt: `agents/prompt_engineering_cycle.md` notes  
- Builder summary, git diff, and `workflow/historylog.md`

## Steps
1) Author expectations: Before inspecting diffs, draft/update `workflow/expectations.md` using `workflow/tasks.md`, the refined prompt, and the Builder handoff.  
2) Validate: Inspect diffs; run agreed tests/lints. Compare results to the expectations you just wrote.  
3) Decide: Approve or document gaps with repro steps and severity. If fixes are needed, push them back to the Builder and note updates in `workflow/tasks.md` if scope shifts.  
4) Log: Append QA results to `workflow/historylog.md` (evidence, commands, outcome) and note expectations updates.  
5) If approved, trigger `workflow/github_push_cycle.md`. If not, ensure required fixes are explicit and traceable.
