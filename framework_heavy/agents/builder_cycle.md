# Builder Cycle

## Purpose
Structured loop for Builders working in parallel streams. Keeps execution coordinated and observable.

## How it interacts with other files
Consumes tasks from tasks.md via autoscheduler.md, references expectations.md, and reports progress into historylog.md for orchestrator visibility.

- TODO: Define per-session checkpoints and logging fields.
- TODO: Add rules for avoiding conflicts noted in concurrency_playbook.md.
- TODO: Outline handoff requirements to qa_cycle.md or deep_qa_cycle.md.
