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

## Arlo OpenClaw To Hermes Migration

Goal: prepare Arlo for a careful OpenClaw Runtime to Hermes Agent migration.

Status: dossier filed 2026-05-16; Drop Zone library pass updated the local Obsidian state the same day.

What exists now:

- Public-safe dossier routing summary in this repo: `inbox/codex/2026-05-16-hermes-agent-dossier-for-arlo-openclaw-migration.md`.
- Private Obsidian copies filed under both Arlo and Keryke project memories.
- Arlo receives the dossier as migration guidance.
- Keryke receives the dossier as shared Hermes runtime knowledge only.
- Local Obsidian now also contains summarized 2026-05-16 notes for Arlo's real build-plan status, A.4 arc closure, Hermes bridge prototype decision, and the Cut 1 install/harness prompt.

Important boundary:

- Do not treat Keryke as part of the Arlo runtime migration.
- Before touching production, secrets, gateways, or runtime behavior, refresh the official Hermes docs and verify current migration command behavior.

Current next move:

- Run the Hermes Bridge Cut 1 install/harness against a fresh bare Hermes runtime before strategic runtime cutover.
- Treat A.5 Context Engine cluster and A.6 L12 SUB stack as remaining May 4 plan spine items after A.4.
