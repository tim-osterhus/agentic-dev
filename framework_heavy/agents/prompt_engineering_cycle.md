# Prompt Engineering Cycle

## Purpose
Refine prompts for multi-session workloads to keep parallel agents aligned and reduce rework.

## How it interacts with other files
Runs before builder_cycle.md instances start, leveraging tasks.md, session_registry.md, and historylog.md to tailor prompts per session.

- TODO: Define prompt templates by role or session type.
- TODO: Capture approvals and distribute prompts to agents.
- TODO: Add safeguards to prevent conflicting instructions.
