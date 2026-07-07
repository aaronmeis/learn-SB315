# AGENTS.md

**This project participates in the multi-AI (Claude Code + Grok + human) research & automation system.**

## Read this first (every fresh session)

1. `C:\obsidian\personal_research_2026\SHARED_CONTEXT.md` — the single cross-tool hub. Every assistant and the human should read it.
2. The per-project runbook for this folder (usually `GROK.md` if you're in a Grok session, or `CLAUDE.md` for Claude-centric projects).
3. Check `grok inspect` (or equivalent) for currently loaded skills, MCP servers, and rules.

## Where the real context and skills live

- **Centralized, synced source of truth** (lives inside the Obsidian vault so it syncs across all your devices via ST/Syncthing):
  - Shared context: `C:\obsidian\personal_research_2026\Grok\Registry\` and the top-level `SHARED_CONTEXT.md`
  - Skills (prompts + workflows): `C:\obsidian\personal_research_2026\Grok\Skills\Centralized\`
  - Project templates & this skeleton: `C:\obsidian\personal_research_2026\Grok\Templates\New-Project\`
  - Registry of all projects: `C:\obsidian\personal_research_2026\Grok\Registry\Projects.md`

- **Local overrides** (this project only):
  - `.grok/skills/` — put project-specific skill customizations here (highest priority).
  - `GROK.md` or `CLAUDE.md` — project-specific runbook.

## On this machine the vault root is approximately:
`C:\obsidian\personal_research_2026`   (Windows example — update for Mac / other devices)

See `Grok/Registry/Machines.md` inside the vault for the authoritative per-machine paths.

## Lightweight project rule

Keep this `AGENTS.md` small. All the heavy shared knowledge lives in the synced vault under `Grok/`. This file just tells new sessions where to go.

Deeper subfolders can have their own `AGENTS.md` if needed (they take precedence).

Welcome — you're now part of the synced context system.
