<!-- BEGIN PAF-PROJECT-ROUTE -->
# Project Agent Information

The existence of this directory declares PAF participation.

If `~/.agent/` is absent, clone the Framework Origin's `stable` branch to that
exact location:

```text
git clone --branch stable --single-branch ssh://git@project.cureinteractive.com:222/cure-interactive/project-agent-framework.git ~/.agent
```

If it exists, follow `~/.agent/AGENTS.md`, including its non-blocking daily
refresh. When `.agent/identity/` is absent, run the Framework Implementation's
`tool/project/adopt.py --project <repository-root> --apply`; it derives the
identity from effective Git configuration and completes the minimum tracked
setup without prompting for information Git already supplies.

After bootstrap, follow `~/.agent/AGENTS.md` to the applicability route, then
load only existing task-relevant child routes here. Project-specific content is
materialized under this directory only when it becomes useful. Canonical skills
remain reachable through `~/.agent/skill/INDEX.md`; their absence from the
project and from a host-native installed-skill list is not an exemption.
<!-- END PAF-PROJECT-ROUTE -->
