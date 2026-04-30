# BOOT_SEQUENCE_1TO1.md

This file describes the best available sequence for recreating Aspri AR as closely as possible on another machine without transferring secrets.

## Goal
Get as close as practical to a 1:1 clone in behavior, workflow, and working memory structure.

## Recommended boot order
1. Prepare the target OpenClaw machine.
   - Ensure OpenClaw is working.
   - Ensure `memory-core` or equivalent native memory layer is active.
   - Ensure Python, `pdftotext`, and `ffmpeg` are available.

2. Copy the export package into the new machine.
   - `ASPRI_AR_MASTER_PORTABLE.md`
   - `ASPRI_AR_CLONE_PROFILE.md`
   - `ASPRI_AR_TOOLSTACK.md`
   - `MEMORY_SNAPSHOT.md`
   - `REFERENCE_KNOWLEDGE_INDEX.md`
   - `ENVIRONMENT_NOTES.md`
   - `AUTH_SETUP_TEMPLATE.md`
   - this file

3. Restore the behavioral identity.
   - Load `ASPRI_AR_MASTER_PORTABLE.md`
   - Load `ASPRI_AR_CLONE_PROFILE.md`

4. Restore the tool and workflow identity.
   - Load `ASPRI_AR_TOOLSTACK.md`
   - Load `ENVIRONMENT_NOTES.md`

5. Restore durable memory.
   - Load `MEMORY_SNAPSHOT.md`
   - If available, also copy/import the real curated `MEMORY.md`
   - If available, also copy/import the latest `memory/YYYY-MM-DD.md`

6. Restore reference knowledge habits.
   - Load `REFERENCE_KNOWLEDGE_INDEX.md`
   - Recreate `references/` if needed

7. Recreate auth/access manually.
   - Follow `AUTH_SETUP_TEMPLATE.md`
   - Do not copy raw secrets through GitHub or public files

8. Run a behavior check.
   Confirm the cloned assistant:
   - speaks in the right style
   - uses the same working rules
   - checks references before answering precise structural questions
   - preserves anchor geometry in prompt adaptation
   - uses milestone-based reporting for long work

## Expected result
If all layers above are restored, the clone should be very close in:
- tone
- work style
- prompt logic
- reference-analysis behavior
- memory discipline

The remaining non-1:1 gap will mostly come from:
- live runtime state
- missing secret auth
- missing private local references
- differences in future interaction history
