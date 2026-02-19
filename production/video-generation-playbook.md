# note_to_self — AI Video Generation Playbook

Goal: turn screenplay scenes into production-ready AI video clips without losing tone, continuity, or emotional precision.

## Core Reality (Important)
AI video is still weak at:
- long narrative continuity
- consistent faces/hair/wardrobe across many shots
- subtle acting beats over long takes
- stable props/text on screen

So we produce like this:
- short clips (3–8s)
- shot-by-shot assembly
- strict continuity references
- editorial-first workflow

---

## Pipeline (Use This)

1. **Lock scene intent first**
   - What must the audience feel?
   - What plot info must land?
   - What cannot be lost?

2. **Convert scene to shot list**
   - 8–20 shots per scene depending on pacing
   - one emotional purpose per shot

3. **Generate clips in tiers**
   - Tier A: key emotional anchors (closeups, reveals)
   - Tier B: connective coverage (OTS, inserts, movement)
   - Tier C: atmosphere/B-roll

4. **Assemble rough cut immediately**
   - don’t wait to finish all clips before editing
   - identify missing transitions early

5. **Patch only gaps**
   - generate replacement shots for continuity holes
   - avoid endless “improve everything” loops

---

## Visual Continuity Rules

Keep a fixed character bible while generating:
- Ada: 32, dark brown tied hair, light olive skin, restrained expression, gray/navy wardrobe
- Corvus motif: raven (never humanoid robot)
- Marcus: early 50s, salt-and-pepper, practical office wear
- Dara: late 20s, warmer style, subtle color accent

Environment anchors:
- server room = cool fluorescent + rack blues
- office floor = neutral daylight
- apartment = low practical warmth
- rooftop = wind, dusk contrast

Never change these casually between scenes.

---

## Prompting Format (Recommended)
Use this structure for every shot:

1. **Shot type + lens feeling**
2. **Subject + action**
3. **Environment + lighting**
4. **Mood + performance style**
5. **Hard negatives** (what to avoid)

### Prompt Template
"Cinematic [shot type] of [character + action], in [location], [lighting], grounded indie thriller drama tone, restrained performance, realistic skin and fabric texture, subtle 35mm grain, natural camera motion, no stylized sci-fi glow, no text overlays, no robotic humanoid design."

---

## Audio Strategy
Treat generated dialogue as temp.

Use final pipeline:
- lock picture first
- add curated room tone + foley
- record/compose final voice layers after edit timing is stable

Especially for Corvus presence: use subtle phase/tone shifts, not obvious "robot effect" clichés.

---

## Scene Delivery Standard
Before a scene is "done", verify:
- emotional beat lands without explanation
- no obvious character look drift between adjacent shots
- no accidental style jump (hyper-CGI shot in realistic sequence)
- pacing supports tragedy (no rushed payoff)

If one shot breaks tone, replace it.

---

## Practical Production Recommendation
For each scene, maintain a small working pack:
- `scene.md` (story intent)
- `shot-list.md` (numbered shots)
- `prompts.md` (final generation prompts)
- `selects.md` (chosen clip IDs + notes)

This keeps generation and editing aligned and prevents chaos as scene count scales.

---

## Human Update Format (for collaborators)
When reporting progress, always include:
1. scene number and status
2. shots generated / shots accepted
3. continuity risks found
4. what needs manual creative decision next

And always remind:
- Pull before editing: `git pull --rebase origin main`
- Pull often during active collaboration; this repo changes fast.
