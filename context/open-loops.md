# Open Loops

## Tabula Integration

Tabula should eventually save or export raw material into:

`C:\Users\Adam\OneDrive\Documents\Obsidian Vault\00_inbox\Tabula`

Codex should then process those files into durable Obsidian notes.

## Arlo OpenClaw To Hermes Migration

A Hermes Agent migration dossier was filed on 2026-05-16.

Key open loop:

- Before any Arlo/OpenClaw migration edits, the acting coding agent should read `inbox/codex/2026-05-16-hermes-agent-dossier-for-arlo-openclaw-migration.md`.
- Refresh official Hermes docs before production work, especially migration command behavior, release state, secrets, gateways, MCP, cron, and runtime surfaces.
- Keep Arlo and Keryke scope separate. Keryke only receives the dossier as shared Hermes runtime knowledge.

## AI Contribution Lanes

Each assistant should have its own inbox/outbox lane rather than editing the same canonical files:

- ChatGPT outputs
- Claude outputs
- Codex outputs
- Tabula raw dumps

Codex can merge useful contributions into the source-of-truth Obsidian notes.

## GitHub Exchange

This repository should stay small, public-safe, current, and easy for other LLMs to read through GitHub connectors or browser tools.

## Obsidian Direct Access

Later, evaluate whether to add Obsidian MCP, Local REST API, Obsidian Publish, or another controlled browser-readable mirror. Direct unrestricted writing by multiple LLMs is not the default plan.

## Obsidian Cockpit UX

Mission Control v0 exists in the vault as a markdown dashboard, canvas, config note, daily log structure, Bases views, and an experimental local plugin.

Current judgment:

- It is good enough as an Obsidian-native memory surface.
- It is not yet good enough as a browser-like daily workspace.
- Do not spend more time trying to force Obsidian canvas/markdown to feel like a polished browser app unless Adam explicitly asks.
- If Adam wants a real cockpit, build a small local web dashboard that uses the vault as the backend.

## Backup And Sync Safety

The vault currently lives under OneDrive Documents. Avoid mixing multiple sync systems against the same vault without a backup plan.

## Processing Cadence

Useful Adam commands:

- "Process the drop zone."
- "Process Tabula."
- "Update the LLM context repo."
- "Check Claude/ChatGPT inbox and merge what matters."
- "Open the cockpit." This should mean the single Obsidian Cockpit launcher or a future browser dashboard, not the old separate Vault/Drop Zone shortcuts.
