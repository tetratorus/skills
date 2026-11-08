---
name: cdpkit
description: Use the tetratorus/cdpkit desktop automation toolkit for Chrome, Slack, Notion, Granola, and Teams.
argument-hint: "<app> <task>"
triggers:
  - user
  - model
---

# CDPKit

The toolkit is maintained at https://github.com/tetratorus/cdpkit. This skill is an entry point, not a bundled installation of the toolkit.

Locate an existing checkout from the user's project context or ask where it is installed. Before using the toolkit, read its maintained skill at `<cdpkit-root>/.devin/skills/cdpkit/SKILL.md` and its repository instructions at `<cdpkit-root>/AGENTS.md`. Follow those operational instructions subject to the session's access and permission rules.

Run toolkit commands from that package root, not this skill directory. Use Node.js 22.13 or newer and verify its availability in the current environment.

Do not reinstall dependencies or restart desktop applications merely to locate or load the skill. Attach to an existing CDP-enabled app without launching or killing it; stop and report a blocker if attachment is unavailable.

Keep access read-only unless the user explicitly requests a write. Never expose authentication values. Store private outputs only under the checkout's gitignored `data/` directory. Do not inspect unrelated apps or conversations.

This entry adds no tool auto-approvals or permission overrides. Preserve all existing authorization deadlines and organizational controls.
