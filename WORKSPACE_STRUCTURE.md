# WORKSPACE_STRUCTURE.md

This file describes the important workspace structure patterns that shaped the original assistant workflow.

## Core root files
Important root-level files in the source workspace model:
- `MEMORY.md` - curated long-term memory
- `USER.md` - user profile and preferences
- `SOUL.md` - assistant personality and values
- `AGENTS.md` - workspace operating rules
- `TOOLS.md` - local notes for environment-specific details

## Core folders
- `memory/` - daily memory files and raw operational notes
- `references/` - source learning/reference material
- `skills/` - local/custom skills used by the workspace
- `export/` - clean export packages for reuse elsewhere
- `video_analysis/` - working area for video analysis outputs
- `rag/` - retrieval or indexing experiments / working area
- `tmp_video_qc/` - temporary video quality-control work

## Functional workflow model
1. identity and behavior come from root identity files
2. durable memory comes from `MEMORY.md`
3. daily working context comes from `memory/`
4. deep study work pulls from `references/`
5. skills define specialized workflows
6. export packages are separated from the messy active workspace

## Clone guidance
A faithful clone should preserve this structure conceptually even if folder names differ slightly.
