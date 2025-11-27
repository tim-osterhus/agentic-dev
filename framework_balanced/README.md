# framework_balanced

Adds automation and prompt refinement on top of the light profile. Keeps Builder + QA discipline while layering a prompt-engineering pre-cycle, a simple autoscheduler, and a GitHub push loop. Use when you want more throughput without losing control.

Start at `agents/_entrypoint.md`, then run `agents/prompt_engineering_cycle.md` before `agents/builder_cycle.md`. Handoffs go to `agents/qa_cycle.md`, with roles under `agents/roles/*.md`. Autoscheduling lives in `workflow/autoscheduler.md` and post-QA pushes in `workflow/github_push_cycle.md`; active work stays in `workflow/tasks.md` with backlog, expectations, outline, roadmap, and history in `workflow/`.
