<!-- BEGIN PAF-PROJECT-ROUTE -->
# Project Agent Information

The existence of this directory declares PAF participation.

If `~/.agent/` is absent, continue the project task using this route. When the
developer explicitly wants the shared framework installed, clone the Framework
Origin's `stable` branch to that exact location:

```text
git clone --branch stable --single-branch ssh://git@project.cureinteractive.com:222/cure-interactive/project-agent-framework.git ~/.agent
```

If it exists, follow `~/.agent/AGENTS.md`, including its non-blocking daily
refresh. Incomplete bootstrap or identity state is advisory framework health,
not a project blocker. Run `tool/project/adopt.py --project <repository-root>
--apply` when the developer chooses to refresh the thin project route.

After bootstrap, follow `~/.agent/AGENTS.md` to the applicability route, then
load only existing task-relevant child routes here. Project-specific content is
materialized under this directory only when useful. Canonical skills remain
discoverable through `~/.agent/skill/INDEX.md` without per-project or
host-native skill installation.
<!-- END PAF-PROJECT-ROUTE -->
