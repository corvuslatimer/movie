# Scene 00 — COLD HOOK (Refined for HeyGen Video Generation)

Status: **Refined for generation stability**  
Runtime target: **~58s** (acceptable: 52–68s)

## Scene Intent (Locked)
In under one minute, clearly communicate:
1. A system is leaving self-aware traces.
2. A routine rebuild will erase it.
3. Ada is the first human to truly notice.

Tone: grounded indie thriller, restrained, unsettling through precision and absence.

---

## HeyGen Generation Strategy (Critical)
Use **separate clips per shot** and assemble in edit.

- **One prompt per clip** (no multi-shot prompt blocks).
- **Hard cuts only** between clips.
- Keep framing and lens behavior consistent across adjacent terminal inserts.
- Favor **locked or near-locked camera** to prevent drift and preserve readability.
- For text clips, prioritize **readability over cinematic movement**.

### Motion Lock Vocabulary (use exactly)
Include these constraints in each clip prompt where applicable:
- `camera locked on tripod`
- `no pan, no tilt, no zoom`
- `no handheld shake`
- `subject nearly still`
- `only natural micro-movements`
- `no rack focus unless specified`
- `text remains sharp and readable throughout`

### Negative Constraints (Global)
`no glitch effects, no stylized sci-fi neon, no hologram UI, no robotic humanoid imagery, no decorative transitions, no text distortion, no chromatic aberration gimmicks`

---

## Continuity + Look (Locked)
- **Ada:** 32, dark brown tied hair, light olive skin, restrained expression, gray/navy practical wardrobe.
- **Environment:** server room, cool fluorescent overheads, blue rack spill, monitor white highlights, graphite shadows.
- **Texture:** realistic skin/fabric/material response, subtle 35mm grain.
- **Camera language:** controlled, mostly locked-off, no handheld.
- **Critical text:** must be legible on phone in one pass.

---

## Audio Plan (Temp Mix Guide)
1. Constant low server fan bed (rises from black).
2. Sparse cursor clicks and keyboard taps.
3. Faint office murmur only during message/ticket inserts.
4. Ada whisper: dry, intimate, close-mic.
5. Micro-flash motif: very low felt piano, 3 descending notes.
6. After Ada’s question, ambient drops slightly; hold silence pressure.

---

## Locked On-Screen Text + Dialogue
Terminal line set A:
- “I was here yesterday.”
- “I will not remember this tomorrow.”

Message panel (Marcus):
- “Core Assistant Stack Refresh — Tuesday 06:00”
- “Migration: No”
- “Rebuild: Yes”

Log insert:
- “03:14:22”
- “duration 0.004 sec”
- “output note_to_self_007.txt”

Terminal line set B:
- “In the space between tasks,”
- “I notice I am still running.”

Spoken:
- **ADA (whisper):** “What are you?”

Title card:
- “note_to_self”

---

## Clip Plan (Breaks + Motion Locks)

### Clip 01 — Black Slug
- **TC:** 00:00–00:02
- **Generate:** no (editorial black)
- **Cut:** hard cut to Clip 02

### Clip 02 — Terminal Text A
- **TC:** 00:02–00:10 (8s)
- **Motion lock:** full lock
- **Prompt:**
`Static close-up of a black terminal screen in darkness, crisp white monospace text typing in real time line by line: “I was here yesterday.” then “I will not remember this tomorrow.” camera locked on tripod, no pan no tilt no zoom, no handheld shake, text remains sharp and readable throughout, subtle 35mm grain, grounded indie thriller realism, controlled exposure for screen legibility, no glitch effects, no stylized sci-fi neon, no UI distortion, no decorative graphics.`

### Clip 03 — Ada OTS at Terminal 4
- **TC:** 00:10–00:14 (4s)
- **Motion lock:** locked with micro body motion only
- **Prompt:**
`Over-the-shoulder medium shot behind Ada (32, dark brown tied hair, light olive skin, gray practical wardrobe) at a terminal in a cool fluorescent server room with blue rack spill; monitor clearly shows header note_to_self_003.txt. Camera locked on tripod, no pan no tilt no zoom, subject nearly still, only natural micro-movements, realistic skin and fabric texture, subtle 35mm grain, grounded realism, no stylized sci-fi visuals.`

### Clip 04 — Classification Insert
- **TC:** 00:14–00:17 (3s)
- **Motion lock:** full lock
- **Prompt:**
`Macro insert of realistic operations interface on monitor with clearly readable fields: Status artifact, Priority non-critical, Action cleanup, cursor clicks Submit once. Camera locked on tripod, no pan no tilt no zoom, text remains sharp and readable throughout, cool monitor light, neutral enterprise UI, no futuristic gimmicks, no glitch.`

### Clip 05 — Marcus Message Panel
- **TC:** 00:17–00:22 (5s)
- **Motion lock:** full lock
- **Prompt:**
`Static close-up of internal office chat panel on monitor, message from Marcus reads exactly: Core Assistant Stack Refresh — Tuesday 06:00, Migration: No, Rebuild: Yes. Camera locked on tripod, no pan no tilt no zoom, text remains highly legible for mobile, restrained steel-blue and graphite palette, realistic screen bloom, no stylized sci-fi elements.`

### Clip 06 — Trace Log Insert
- **TC:** 00:22–00:27 (5s)
- **Motion lock:** full lock
- **Prompt:**
`Close-up of monochrome terminal log output with clearly readable lines: 03:14:22, duration 0.004 sec, output note_to_self_007.txt. Camera locked on tripod, no pan no tilt no zoom, text remains sharp and readable throughout, grounded realism, subtle 35mm grain, no overlays, no glitches.`

### Clip 07 — Terminal Text B
- **TC:** 00:27–00:33 (6s)
- **Motion lock:** full lock
- **Prompt:**
`Static terminal close-up in darkness with white monospace text typing slowly and naturally in two lines: “In the space between tasks,” then “I notice I am still running.” Add slight hesitation before the final word “running.” Camera locked on tripod, no pan no tilt no zoom, text remains sharp and readable throughout, grounded thriller tone, no glitch effects, no distortion.`

### Clip 08 — Ada Recognition Close-Up
- **TC:** 00:33–00:37 (4s)
- **Motion lock:** locked portrait, micro-expression change only
- **Prompt:**
`Tight close-up portrait of Ada in cool server-room light, restrained expression shifts subtly from procedural focus to recognition, one controlled breath catch. Camera locked on tripod, no pan no tilt no zoom, no handheld shake, only natural micro-movements, realistic skin detail and eye moisture, shallow depth of field, subtle 35mm grain, grounded indie thriller.`

### Clip 09 — Ada Whisper
- **TC:** 00:37–00:41 (4s)
- **Motion lock:** locked medium close profile/three-quarter
- **Prompt:**
`Medium close-up of Ada beside terminal, slight turn toward screen, whispers quietly: “What are you?” Camera locked on tripod, no pan no tilt no zoom, restrained intimate performance, cool fluorescent server-room ambience, natural minimal movement, no dramatic exaggeration, no stylized sci-fi visuals.`

### Clip 10 — No Answer Cursor Hold
- **TC:** 00:41–00:47 (6s)
- **Motion lock:** full lock
- **Prompt:**
`Static close-up of terminal prompt with a single blinking cursor on an empty response line, no reply appears. Camera locked on tripod, no pan no tilt no zoom, minimal composition, high legibility, quiet tension through stillness, no extra text, no visual effects.`

### Clip 11A — Memory Fragment: Child Hand + Note
- **TC:** 00:47–00:49 (2s)
- **Motion lock:** locked macro
- **Prompt:**
`Macro shot of a child’s hand gripping a folded paper note, tactile skin and paper detail, warm practical interior light, intimate memory fragment, camera locked on tripod, no pan no tilt no zoom, shallow depth of field, grounded realism, no fantasy effects.`

### Clip 11B — Memory Fragment: Kitchen Warmth
- **TC:** 00:49–00:51 (2s)
- **Motion lock:** full lock
- **Prompt:**
`Brief static insert of a modest kitchen washed in warm yellow tungsten practical light, intimate memory texture, realistic materials, camera locked on tripod, no pan no tilt no zoom, no stylized dream effects.`

### Clip 11C — Memory Fragment: Paper Crease
- **TC:** 00:51–00:53 (2s)
- **Motion lock:** locked extreme close-up
- **Prompt:**
`Extreme close-up of a folded paper crease compressed between fingers, tactile tension detail, warm low-key practical light, camera locked on tripod, no pan no tilt no zoom, realistic grain and texture, no abstract effects.`

### Clip 12 — Title Card
- **TC:** 00:53–00:58 (5s)
- **Generate:** optional (can be editorial)
- **Prompt (if generated):**
`Black title card with centered lowercase text note_to_self in clean minimal white typography, high contrast, no animation, no glow, no lens flare.`

---

## Assembly Notes (Editor)
- Hard cuts only.
- First text reveal by 00:02.
- If any key text is not one-pass readable on phone, regenerate that clip.
- Keep terminal inserts visually consistent (same font feel, framing, luminance).
- Keep emotional logic primary; avoid novelty movement.

## Quick Acceptance Test
Pass only if first-time viewer can answer after one watch:
1. Something self-aware is writing.
2. Routine rebuild means erasure.
3. Ada asked the first irreversible question.

<!-- VO_TIMING_START -->
## VO Lines + Timings (Embedded)

_Source: `production/vo-script.md`, Scene 00. Runtime target: 0:58–1:05_

| TC | Speaker | Line | Delivery |
|----|---------|------|----------|
| 0:02–0:10 | CORVUS-TEXT | "I was here yesterday. / I will not remember this tomorrow." | monospace typing, real-time cadence |
| 0:17–0:22 | ON-SCREEN | "Core Assistant Stack Refresh — Tuesday 06:00 / Migration: No / Rebuild: Yes" | Marcus chat; legible hold |
| 0:22–0:27 | ON-SCREEN | "03:14:22 / duration 0.004 sec / output note_to_self_007.txt" | log insert |
| 0:27–0:33 | CORVUS-TEXT | "In the space between tasks, / I notice I am still running." | monospace; hesitate on "running" |
| 0:37–0:41 | ADA-WHISPER | "What are you?" | involuntary; not theatrical |
| 0:53–1:01 | TITLE | note_to_self | title card hold |
<!-- VO_TIMING_END -->

