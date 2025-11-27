# framework_heavy

Designed for high-throughput setups with multiple web/CLI agents running in parallel. Supports many tasks in flight, deeper QA layers, and explicit resource budgeting.

Start at `agents/_entrypoint.md`, then run `agents/prompt_engineering_cycle.md` and `agents/builder_cycle.md` per session. QA can escalate to `agents/deep_qa_cycle.md`. Roles (including orchestrator) live under `agents/roles/*.md`. Session and resource controls live in `workflow/session_registry.md`, `workflow/concurrency_playbook.md`, and `workflow/resource_budgeting.md`. Web/remote guidance is in `workflow/web_agents.md`. Active work stays in `workflow/tasks.md` with backlog, expectations, outline, roadmap, autoscheduler, and history in `workflow/`.
