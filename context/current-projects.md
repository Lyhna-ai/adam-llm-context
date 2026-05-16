# Current Projects

## Second Brain Setup

Goal: create an Obsidian vault Adam can use as a low-friction landing spot for Tabula outputs, raw ideas, research, decisions, and ongoing memory.

Status: active. The vault is initialized and has a first-pass cockpit layer, but Adam does not expect to live inside Obsidian day to day.

What exists now:

- Obsidian is installed and opening correctly.
- Desktop shortcut `Obsidian Cockpit` is the intended single launcher.
- The old `Obsidian Vault` and `Obsidian Drop Zone` desktop shortcuts were moved into an archived shortcuts folder.
- The vault contains Home, Drop Zone, doctrine notes, indexes, and templates.
- The graph view shows the early linked-note structure.
- AI drop lanes exist locally for ChatGPT, Claude, Codex, and Tabula.
- Mission Control v0 exists under `50_journal/Mission Control.md`, with a related canvas, cockpit config note, daily log folder, Bases views, and an experimental local Obsidian plugin.
- The cockpit is useful as a memory surface, but the UX still feels like Obsidian. Adam does not consider it browser-like enough to use heavily as a front-end.
- Template notes were upgraded with cockpit-style structure, but the visual improvement is limited by Obsidian's reading/rendering surface.

Current design:

- Obsidian is the source of truth.
- GitHub is the public context exchange layer.
- Each LLM should leave contributions in its own lane.
- Codex merges useful contributions into Obsidian.
- For now, Obsidian should be treated mainly as the storage and retrieval layer, not the main daily operating interface.
- If a more user-friendly cockpit is needed, build a small local web dashboard that reads/writes the vault instead of trying to make Obsidian feel like a browser.

Near-term next actions:

- Connect Tabula output to the vault as a save/export location.
- Use `00_inbox/Tabula` as the preferred raw Tabula dump folder.
- Keep this repo updated from the Obsidian vault.
- Decide whether the next cockpit iteration should be a local browser app backed by vault files.
- Decide later whether to add direct Obsidian MCP, Local REST API, or Publish.
