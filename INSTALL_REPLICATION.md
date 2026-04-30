# INSTALL_REPLICATION.md

This file describes the practical installation/capability baseline needed to recreate Aspri AR more faithfully on another machine.

## Recommended baseline
- OpenClaw installed and working
- native memory backend equivalent to `memory-core`
- Python 3 available
- `pdftotext` available
- `ffmpeg` available

## Recommended workflow skills/capabilities
- document/reference study workflow equivalent to `study-ingestion`
- video scene reverse-engineering workflow equivalent to `video-scene-reverse-engineering`
- ability to read/edit workspace files
- ability to inspect references before answering structural questions

## Recommended environment qualities
- access to a persistent workspace folder
- ability to keep curated memory files
- ability to keep daily raw memory files
- ability to maintain a `references/` corpus

## Recommended optional extras
- Python PDF fallback libraries when needed:
  - `pymupdf`
  - `pdfplumber`
  - `pypdf`
- local model/provider access if useful for experimentation

## Replication rule
The goal is not to copy every temporary file, but to reproduce:
- the same working habits
- the same verification habits
- the same prompt engineering structure
- the same memory discipline
- the same reference-analysis capability
