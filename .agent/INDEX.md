<!-- BEGIN PAF-PROJECT-ROUTE -->
# Project Agent Information

The existence of this directory declares PAF participation. The repository-root
`AGENTS.md` makes this route discoverable before PAF is installed.

If `~/.project-agent/framework/` is absent, continue the project task and install
PAF only when the developer selects setup. Reuse this repository's configured Git
transport to clone Framework Origin's `stable` branch:

```text
git clone --branch stable --single-branch ssh://git@project.cureinteractive.com:222/cure-interactive/project-agent-framework.git ~/.project-agent/framework
```

Then preview and explicitly complete the canonical two-checkout Project Agent
home. Native Windows PowerShell and Command Prompt use:

```text
~\.project-agent\framework\paf.cmd tool/framework/install.py --complete-bootstrap --transport-project <repository-root>
~\.project-agent\framework\paf.cmd tool/framework/install.py --complete-bootstrap --transport-project <repository-root> --apply
```

POSIX-compatible shells, including Git Bash, use:

```text
~/.project-agent/framework/paf tool/framework/install.py --complete-bootstrap --transport-project <repository-root>
~/.project-agent/framework/paf tool/framework/install.py --complete-bootstrap --transport-project <repository-root> --apply
```

The completion transaction verifies the bootstrapped Framework Implementation,
adds the independent Time Evidence checkout, preserves configured PuTTY transport,
and remains safely retryable after a companion-clone failure.

When the Framework Implementation exists, follow its `AGENTS.md`, including the
non-blocking daily refresh. To finish or refresh this project's thin route,
preview and then apply adoption with the launcher for the active shell:

```text
~\.project-agent\framework\paf.cmd tool/project/adopt.py --project <repository-root>
~\.project-agent\framework\paf.cmd tool/project/adopt.py --project <repository-root> --apply
```

```text
~/.project-agent/framework/paf tool/project/adopt.py --project <repository-root>
~/.project-agent/framework/paf tool/project/adopt.py --project <repository-root> --apply
```

Incomplete bootstrap or identity state is advisory framework health, not a
project blocker. After adoption, follow the Framework Implementation's
applicability route, then load only existing task-relevant child routes here.
Project-specific content is materialized only when useful. Canonical skills
remain discoverable through `~/.project-agent/framework/skill/INDEX.md` without
per-project or host-native skill installation.

PAF guidance applies forward to new work and natural transitions. Do not rewrite
existing project records or active work merely to match newer guidance.
<!-- END PAF-PROJECT-ROUTE -->
