# QA Cycle

## Purpose
Baseline QA loop for routine tasks in a multi-session environment. Confirms quality without stalling throughput.

## How it interacts with other files
Uses `workflow/expectations.md`, compares against Builder handoff, logs to `workflow/historylog.md`, and escalates to deep_qa_cycle.md for higher-risk items.

## Steps
1) Author expectations: Before inspecting diffs, draft/update `workflow/expectations.md` using `workflow/tasks.md`, session data in `workflow/session_registry.md`, and the Builder handoff; note resource limits.  
2) Validate: Inspect diffs and run required tests; capture commands with session ID and compare results to the expectations you just wrote.  
3) Decide: Approve or list issues with repro steps and impacted sessions.  
4) Log: Record evidence, expectations updates, and outcome in `workflow/historylog.md`; note if deep QA is needed.  
5) Escalate: Trigger `agents/deep_qa_cycle.md` for high-risk items or notify `agents/roles/orchestrator.md` for push/merge decisions and conflict handling.
