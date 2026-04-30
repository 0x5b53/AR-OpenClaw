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

## Additional fidelity files
To get even closer to the original assistant behavior and environment, also review:
- `CURATED_MEMORY_EXPORT.md`
- `REFERENCE_MANIFEST.md`
- `WORKSPACE_STRUCTURE.md`
- `INSTALL_REPLICATION.md`
- `BEHAVIORAL_EDGE_CASES.md`

## Prompt-generation context
For a closer clone of Aspri AR's image/video prompting mindset, also use:
- `PROMPT_GENERATION_CONTEXT.md`

## Style examples
For a closer clone of how Aspri AR actually answers in conversation, also use:
- `SESSION_STYLE_EXAMPLES.md`

## Important note about references
To get a close clone of Aspri AR, importing the profile files alone is not enough.
The clone should also load or study the reference corpus in `references/`.

Why:
- a large part of Aspri AR's prompt-generation behavior was shaped by real reference material
- prompt logic, adaptation habits, and scene-structure habits depend on those references
- without the reference corpus, the clone may match tone and rules but still miss deeper prompt context

## Recommended import behavior for a strong clone
After loading the profile and memory files, the target engine should also:
1. inspect `REFERENCE_MANIFEST.md`
2. inspect `REFERENCE_KNOWLEDGE_INDEX.md`
3. load or study the most important files/folders inside `references/`
4. prioritize prompt-related references first, especially:
   - `references/Learning_Prompt_by_Andreis/`
   - `references/yacht-revision/`
   - `references/module3/`
   - `references/bus-house-100-scene-prompt-map-v1.md`
5. use `PROMPT_GENERATION_CONTEXT.md` and `SESSION_STYLE_EXAMPLES.md` as guidance for how those references should be interpreted in practice

## Practical import order for best fidelity
1. `ASPRI_AR_MASTER_PORTABLE.md`
2. `ASPRI_AR_CLONE_PROFILE.md`
3. `ASPRI_AR_TOOLSTACK.md`
4. `MEMORY_SNAPSHOT.md`
5. `CURATED_MEMORY_EXPORT.md`
6. `PROMPT_GENERATION_CONTEXT.md`
7. `SESSION_STYLE_EXAMPLES.md`
8. `REFERENCE_MANIFEST.md`
9. `REFERENCE_KNOWLEDGE_INDEX.md`
10. the actual `references/` corpus, studied progressively in priority order
