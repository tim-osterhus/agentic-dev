# framework_balanced

Adds automation and prompt refinement on top of the light profile. Keeps Builder + QA discipline while layering a prompt-engineering pre-cycle, a simple autoscheduler that pulls from the backlog, and a GitHub push loop for clean handoffs. Use when you want more throughput without losing control.

## adds: prompt_engineering_cycle.md
Purpose: refine instructions before each Builder loop to reduce churn. TODO: Define how prompts are adjusted and approved.

## adds: autoscheduler.md
Purpose: lightweight pull scheduler for tasks_backlog.md. TODO: Describe prioritization and assignment signals.

## adds: github_push_cycle.md
Purpose: repeatable commit/push path after QA approval. TODO: Outline checks, commit message guidance, and branch rules.
