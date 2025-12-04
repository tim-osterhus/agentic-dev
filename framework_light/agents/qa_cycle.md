# QA Cycle

## Purpose
Lightweight verification for a single task. Validate against expectations, surface gaps, and confirm readiness to push.

## Inputs
- Active card: `workflow/tasks.md`  
- Expectations: `workflow/expectations.md` (authored/updated by QA before validation)  
- Builder handoff summary and git diff  
- Recent context: `workflow/historylog.md`

## Steps
1) Author expectations: Before inspecting diffs, draft/update `workflow/expectations.md` using `workflow/tasks.md` and the Builder handoff.  
2) Validate: Inspect diffs; run targeted tests/lints. Compare results to the expectations you just wrote.  
3) Decide: Approve or list issues with repro steps and severity. If fixes are needed, bounce back to the Builder with exact asks.  
4) Log: Append a QA entry to `workflow/historylog.md` capturing evidence, commands, expectations updates, and decisions.

## QA Note Template
- Expectations met? Y/N (evidence)  
- Tests run (command + status): …  
- Issues/gaps: …  
- Next actions or reassignments: …
