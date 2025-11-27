# Role: Frontend

## Purpose
Frontend specialization for UI agents working concurrently across features.

## How it interacts with other files
Aligns with expectations.md for UX standards, coordinates through concurrency_playbook.md to avoid asset conflicts, and logs outcomes to historylog.md.

## When to activate
- UI feature work, integration of new endpoints, or concurrent styling changes.

## Checklist
- Call out shared assets (design tokens, global styles) before editing; avoid collisions.  
- Maintain accessibility/performance budgets; provide validation steps or screenshots.  
- Coordinate live or remote checks with `workflow/web_agents.md` when needed.  
- Document visual debt or follow-ups for QA/deep QA in `workflow/historylog.md`.
