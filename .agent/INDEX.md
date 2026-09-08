<!-- BEGIN PAF-PROJECT-ROUTE -->
# Project Agent Information

The existence of this directory declares PAF participation.

If `~/.project-agent/framework/` is absent, continue the project task using this route. When the
developer explicitly wants the shared framework installed, clone the Framework
Origin's `stable` branch to that exact location:

```text
git clone --branch stable --single-branch ssh://git@project.cureinteractive.com:222/cure-interactive/project-agent-framework.git ~/.project-agent/framework
```

If it exists, follow `~/.project-agent/framework/AGENTS.md`, including its non-blocking daily
refresh. Incomplete bootstrap or identity state is advisory framework health,
not a project blocker. Run `tool/project/adopt.py --project <repository-root>
--apply` when the developer chooses to refresh the thin project route.

After bootstrap, follow `~/.project-agent/framework/AGENTS.md` to the applicability route, then
load only existing task-relevant child routes here. Project-specific content is
materialized under this directory only when useful. Canonical skills remain
discoverable through `~/.project-agent/framework/skill/INDEX.md` without per-project or
host-native skill installation.

PAF guidance applies forward to new work and natural transitions. Do not rewrite
existing project records or active work merely to match newer guidance.
<!-- END PAF-PROJECT-ROUTE -->
