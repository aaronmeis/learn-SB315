# GROK.md — learn-SB315

**Project location (this machine):** `C:\projects\learn-SB315`

Part of the synced multi-AI research ecosystem. See the central context first.

## Required reading order

1. `C:\obsidian\personal_research_2026\SHARED_CONTEXT.md` (or the equivalent path on this machine — see `Grok/Registry/Machines.md`)
2. This file.
3. Relevant notes in the Obsidian vault (especially recent work in `00 Inbox` or the project's own notes).

## Centralized vs Local

**Central (synced in Obsidian vault — edit these in Obsidian on any device):**
- All reusable skills: `Grok/Skills/Centralized/`
- Project templates and bootstrap logic
- The master registry of projects
- SHARED_CONTEXT.md

**Local to this project folder (for this project only):**
- `.grok/skills/` — custom skills or overrides that only apply here.
- Any scripts or assets specific to this project.

To get the latest central skills on this machine, make sure your `~/.grok/config.toml` includes the Centralized path (see `Grok/Registry/Machines.md` for the exact string for this OS).

## Common starting commands in a Grok session here

```powershell
grok inspect                 # see skills, MCPs, rules that are active
/mcps                        # manage the obsidian-vault MCP etc.
/skills                      # list or inject a skill
/skills new-grok-project     # (once the bootstrap skill is loaded)
```

## Creating decks / using Obsidian directly

- Use the local `pptx` skill (or the full one from `~/.grok/skills/pptx`) for creating/editing presentations.
- Use the `obsidian-vault` MCP (search first with `search_tool`, then `use_tool`) for direct read/write of notes.
- For Gamma-hosted decks, use the `grok-gamma` CLI from its own repo.

## Adding this project to the central view

If the bootstrap skill was not used, manually add a row to:
`C:\obsidian\personal_research_2026\Grok\Registry\Projects.md`

You can also propose an update to the high-level map in `SHARED_CONTEXT.md` if this project is long-lived.

---

**Machine note**: Replace the bracketed placeholders above with real values for this project. The bootstrap process tries to do this automatically.

This file + the central `Grok/` folder in the vault is what lets you start fresh project folders without creating one giant ever-growing tree while still having all the shared knowledge and skills available and synced.
