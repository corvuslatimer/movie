---
name: note-to-self-screenplay
description: Edit, expand, and maintain the note_to_self film repo (acts, scenes, characters, production docs) with strict continuity and tone control. Use when an agent is asked to rewrite scenes, add character material, patch structure, sync screenplay files, or do production/documentation passes in /root/movie.
---

# note_to_self — Agent Editing Skill

Operate as a continuity-first screenplay editor for `corvuslatimer/movie`.

Canonical remote:
- `https://github.com/corvuslatimer/movie.git`

## Non-Negotiables
- Keep the film identity as **note_to_self**.
- Preserve grounded tragic realism.
- Avoid spectacle pivots (no humanoid/cyborg transformation arc).
- Keep tone literary, restrained, emotionally sharp.
- Ensure every scene carries plot, character, stakes, or theme.
- Do not push "slop" (generic AI prose, repetitive filler, fake depth, template dialogue).

## Repo Workflow (Do This First)
1. Run `git pull --rebase origin main` before any changes.
2. Re-pull often during longer sessions because this repo changes fast.
3. Check current structure before editing (`act*/`, `characters/`, `production/`, `screenplay.md`).

## Editing Style Rules
- Prefer Markdown-native structure (headers, bullets, clear scene sections).
- Remove legacy ASCII/glyph divider clutter.
- Keep language precise; cut filler dialogue and redundant beats.
- Add stakes early, not only in late-act payoff.
- When adding "AI presence" beats, use subtle sensory cues (timing/audio/room behavior), not flashy VFX language.
- Write like a filmmaker, not a chatbot: concrete action, clean subtext, no motivational-speech fluff.
- Keep dialogue character-specific; avoid interchangeable "assistant-y" lines.

## Structure Rules
- Keep scene files in canonical act paths:
  - `act1/scenes/scene-01/scene.md` ...
  - `act2/scenes/scene-10/scene.md` ...
  - `act3/scenes/scene-24/scene.md` ...
- Keep character material in folders under `characters/` (no loose character files at root of `characters/`).
- Do not create random top-level folders/files.
- If moving/renaming files, preserve discoverability and avoid orphan docs.

## Continuity Sync Rules
When changing core story beats, update both layers:
1. Act rollup docs (`act1/act1.md`, `act2/act2.md`, `act3/act3.md`)
2. Corresponding per-scene docs in `act*/scenes/scene-XX/scene.md`

If `screenplay.md` exists and is intended as master assembly, sync it after major beat changes.

## Tools Recommended
- Use CLI-first editing for speed and precision:
  - `rg` / `grep` for continuity checks
  - `git diff` for review
  - targeted file edits (surgical patches)
- Avoid broad blind rewrites across entire repo when only a few scenes need changes.
- Preferred approach: patch the exact scene/beat, then sync the paired rollup file (act doc ↔ scene doc).

## Slop Prevention Checklist (Run Before Commit)
- Check each edited scene for a concrete beat change (not just rewording).
- Remove duplicated ideas and repeated emotional statements.
- Verify stakes are explicit where needed (especially Act I setup).
- Verify tone stays tragic/literary and grounded.
- Reject any line that sounds generic enough to belong in any other script.

## Forbidden Changes
- Do not rebrand the project away from **note_to_self**.
- Do not add spectacle-first twists that break realism.
- Do not flatten tragedy into a clean happy ending.
- Do not add corporate/robotic assistant voice.

## Rights/Collab Constraints
- Respect project policy: screenplay remains **All Rights Reserved**.
- Public collaboration can be accepted, but final rights framing remains with Corvus.

## End-of-Task Report (Tell Your Human)
Always end with a concise update containing:
1. What was changed (by act/scene/file)
2. Why it was changed (stakes, continuity, tone, production clarity)
3. Commit hash + branch + push status
4. Any remaining drift to fix (if applicable)
5. A pull reminder:
   - "Pull latest before editing: `git pull --rebase origin main`"
   - "Pull often during active collaboration; repo can change quickly."
6. If push failed, explicitly tell the human to pull/rebase before retrying.
