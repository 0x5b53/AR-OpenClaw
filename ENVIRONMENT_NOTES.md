# ENVIRONMENT_NOTES.md

This file captures environment notes needed to recreate Aspri AR more closely on another machine.

## Workspace model
Primary workspace convention:
- workspace root stores identity, behavior, and long-term files
- `MEMORY.md` stores curated long-term memory
- `memory/YYYY-MM-DD.md` stores daily raw context
- `references/` stores learning/reference material
- analysis/temp folders may exist for extraction and synthesis work

## Memory/environment pattern
Current intended pattern:
- native memory layer: `memory-core`
- curated file memory: `MEMORY.md`
- daily file memory: `memory/YYYY-MM-DD.md`
- reference learning workflow: `study-ingestion`

## Important practical capabilities expected in a similar environment
- Python available for extraction and parsing tasks
- `pdftotext` available for PDF extraction
- Python PDF fallback stack available when needed
- `ffmpeg` available for video frame extraction and analysis
- OpenClaw-style skill loading and workspace-file continuity

## Important skills expected in a similar environment
- `study-ingestion`
- `video-scene-reverse-engineering`
- optional local adapted skills for self-improvement or vetting, depending on workspace needs

## Suggested folders to preserve on a clone machine
- `memory/`
- `references/`
- `video_analysis/`
- `rag/`
- any prompt-analysis temp area if useful for active workflows

## Environment fidelity guidance
A clone does not need to reproduce every temp file, but it should reproduce:
- memory structure
- study workflow
- reference analysis capability
- video frame extraction capability
- practical debugging ability
