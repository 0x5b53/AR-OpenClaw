# Aspri AR Clone Export

Portable export package for recreating Aspri AR in another engine or on another OpenClaw machine.

## Included files
- `ASPRI_AR_MASTER_PORTABLE.md` - single-file portable profile
- `ASPRI_AR_CLONE_PROFILE.md` - identity, user preferences, and behavior rules
- `ASPRI_AR_TOOLSTACK.md` - memory/toolstack/workflow notes

## Current setup snapshot
This export reflects the current working style of Aspri AR:
- active native memory: `memory-core`
- curated long-term memory: `MEMORY.md`
- daily raw memory: `memory/YYYY-MM-DD.md`
- large-reference learning workflow: `study-ingestion`

## Quick import to another engine
If the target engine only supports one main instruction block:
1. Open `ASPRI_AR_MASTER_PORTABLE.md`
2. Copy all contents
3. Paste it into the target engine's system prompt / main behavior prompt

## Import to another OpenClaw machine
Recommended steps:

1. Clone or copy this export folder to the new machine.
2. Open the target OpenClaw workspace.
3. Copy these files into the workspace root:
   - `ASPRI_AR_MASTER_PORTABLE.md`
   - `ASPRI_AR_CLONE_PROFILE.md`
   - `ASPRI_AR_TOOLSTACK.md`
4. Make sure the target machine uses a similar memory workflow:
   - `memory-core` active as native memory
   - `MEMORY.md` for curated long-term notes
   - `memory/YYYY-MM-DD.md` for daily logs
5. If needed, paste the bootstrap prompt from `ASPRI_AR_MASTER_PORTABLE.md` into the target engine/session instructions.
6. Optionally bring over curated memory content from the original machine's `MEMORY.md` and the latest daily memory file.

## Recommended import order on another OpenClaw machine
1. Load `ASPRI_AR_MASTER_PORTABLE.md`
2. Load `ASPRI_AR_CLONE_PROFILE.md`
3. Load `ASPRI_AR_TOOLSTACK.md`
4. Load `MEMORY.md`
5. Load the latest `memory/YYYY-MM-DD.md`

## Notes
This export is intentionally kept clean and minimal so it can be reused on another machine without dragging the whole source workspace with it.

## Extended 1:1 clone package files
For a closer behavior/workflow clone, also use:
- `MEMORY_SNAPSHOT.md`
- `REFERENCE_KNOWLEDGE_INDEX.md`
- `ENVIRONMENT_NOTES.md`
- `AUTH_SETUP_TEMPLATE.md`
- `BOOT_SEQUENCE_1TO1.md`
