# GitHub Push Cycle

## Purpose
Standardize commit/push steps after QA approval to keep history clean.

## How to use
- Trigger only after `agents/qa_cycle.md` approves the task.  
- Ensure required checks and branch rules are known before committing.  
- Record outcomes in `workflow/historylog.md`.

## Steps
1) Re-run required tests/lints; confirm results.  
2) Summarize changes and craft a clear commit message.  
3) Commit and push to the appropriate branch; note PR expectations if any.  
4) Append push details (commit hash, branch, status) to `workflow/historylog.md`.  
5) Update `workflow/tasks.md` status and close or archive as needed.

## Template for repo-specific notes
- Required checks before push: …  
- Commit message/branch format: …  
- When to batch or squash: …  
- Release/PR steps (if any): …
