# Edit Assembly Flow - First Cut Pipeline

This document outlines an initial pipeline for assembling generated shots into scenes/acts for *note_to_self*. Focus on dreamcore consistency, using DaVinci Resolve or similar for editing. This is a first-cut version; iterate based on test assemblies.

## Prerequisites
- All priority shots generated (e.g., from shot-priority-40.md).
- Audio assets: server hum, whispers, piano motif, rain SFX.
- Software: DaVinci Resolve (free tier sufficient for draft), with VHS/grain plugins.

## Step 1: Import and Organize
- Import shots into project: Categorize by act/scene (e.g., folders Act0_Shot1-6).
- Tag with metadata: Dependencies, pass criteria from shot docs.
- Backup raw imports to avoid loss.

## Step 2: Rough Sequence Assembly
- Create timeline per act (e.g., Act0_Timeline).
- Sequence shots in order: Use shot list as guide; add 2-5s black slugs for pacing.
- Sync basic audio: Layer hum/ambience under all; align whispers to visuals.

## Step 3: Effects and Artifacts
- Apply global effects: VHS grain overlay (70% opacity), subtle desync (1-2 frames lag on cuts).
- Per-shot tweaks: Add warp/distortion per artifact-bible.md; ensure uncanny contract.
- Color grade: Desaturate to blues/greys; warm intrusions only where scripted.

## Step 4: Audio Mix and Motifs
- Add motifs: Insert piano unresolved keys on flashbacks; raven calls on thresholds.
- Mix levels: Ambience -20dB, dialogue -6dB, effects -12dB.
- Desync intentionally: Slight audio-visual offset for dread (0.5-1s).

## Step 5: Review and Pass Criteria
- Review full act: Check for drift (use anti-drift constraints).
- Pass if: Seamless flow, dread maintained, no jarring cuts; runtime <10min per act draft.
- Fallback: Re-generate problematic shots if assembly reveals issues.

## Step 6: Export and Handoff
- Export draft: 1080p MP4, H.264, with watermarks.
- Handoff to review: Share via drive; note issues in swarm-handoff.md.
- Iterate: Based on feedback, refine in next cut.

This pipeline aims for quick iterations; target first assembly in <4 hours post-generation.
