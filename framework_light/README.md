# framework_light

Minimal Builder + QA loop with the fewest moving parts. Single-task-at-a-time, single-session focus. Prioritizes simplicity, low cognitive overhead, and lean markdown control surfaces. Use as a disciplined baseline before adding automation.

## agents/_entrypoint.md
High-level instructions the Builder reads first. Frames the task scope, constraints, and success criteria. TODO: Add onboarding reminders and guardrails.

## agents/builder_cycle.md
Step-by-step loop for the Builder agent. Covers intake, plan, execute, and handoff to QA. TODO: Define stop conditions and logging cadence.

## agents/qa_cycle.md
Step-by-step loop for the QA agent. Focus on verification, reproducible checks, and acceptance notes. TODO: Add quick test checklist.

## agents/roles/backend.md
Backend specialization guidance for Builder/QA when server work appears. TODO: Add patterns, pitfalls, and sample checks.

## agents/roles/frontend.md
Frontend specialization guidance for UI or client tasks. TODO: Add accessibility and responsiveness checks.

## agents/roles/infra.md
Infrastructure specialization guidance for deployment or ops tasks. TODO: Add env assumptions and rollback notes.

## agents/roles/tests.md
Testing specialization guidance for writing and stabilizing tests. TODO: Add flaky-test handling and coverage expectations.

## workflow/tasks.md
Active tasks in scope for the current session. TODO: Add task template and acceptance markers.

## workflow/tasks_backlog.md
Queued tasks not yet in play. TODO: Add prioritization notes and intake rules.

## workflow/historylog.md
Chronological record of actions and outcomes. TODO: Add log format and required metadata.

## workflow/expectations.md
Defines quality bars, constraints, and communication norms. TODO: Add severity levels and defect handling.

## workflow/outline.md
High-level outline for current workstream. TODO: Add milestones and checkpoints.

## workflow/roadmap.md
Forward-looking plan beyond the current session. TODO: Add time horizons and review cadence.
