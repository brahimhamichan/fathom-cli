---
name: fathom-cli
description: Agent-first CLI and skill for listing, filtering, searching, exporting, and retrieving Fathom meetings, transcripts, and summaries via Fathom's official API. Use whenever a task involves Fathom meetings, teams, team members, or webhooks.
---

# fathom-cli

Agent-first CLI + skill for Fathom's official API.

Install:

- `npm i -g fathom-video-cli`, or one-shot: `npx -y fathom-video-cli`

Default stance:

- Prefer the official API-backed CLI over browser automation.
- Prefer `--json` output for machine use.
- Filter before exporting.
- Use `fathom meetings grep` for content search across summaries/transcripts.
- Run `fathom doctor --json` as a sanity check.

Full skill instructions, workflows, and agent prompts live in [`skills/fathom/SKILL.md`](skills/fathom/SKILL.md) and [`skills/fathom/agents`](skills/fathom/agents).
