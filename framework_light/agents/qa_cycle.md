# QA Cycle

## Purpose
Lightweight verification for a single task. Validate against expectations, surface gaps, and confirm readiness to push.

## Inputs
- Active card: `workflow/tasks.md`  
- Quality bar: `workflow/expectations.md`  
- Builder handoff summary and git diff  
- Recent context: `workflow/historylog.md`

## Steps
1) Align: Confirm scope and constraints from `workflow/tasks.md` and `workflow/expectations.md`. Review the Builder handoff.  
2) Validate: Inspect diffs; run targeted tests/lints. Compare results to expectations.  
3) Decide: Approve or list issues with repro steps and severity. If fixes are needed, bounce back to the Builder with exact asks.  
4) Log: Append a QA entry to `workflow/historylog.md` capturing evidence, commands, and decisions.

## QA Note Template
- Expectations met? Y/N (evidence)  
- Tests run (command + status): …  
- Issues/gaps: …  
- Next actions or reassignments: …
