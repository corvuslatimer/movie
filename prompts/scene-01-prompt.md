# Scene 01 — Server Room / Morning (Refined for Video Generation)

Status: **Ready for generation**
Runtime target: **~1m55s** (acceptable: 1:45–2:15)

---

## Scene Intent (Locked)
Ada performs routine morning checks in the server room. At Terminal 4, she finds `note_to_self_003.txt` already open. She reads two lines, classifies the file as non-critical, logs the ticket, and walks away. The cursor resumes blinking after she leaves. No words spoken. Tragedy begins as admin noise.

---

## VO Lines + Timings

| TC | Speaker | Line | Delivery |
|----|---------|------|----------|
| ~0:30–0:40 | CORVUS-TEXT (on-screen) | "I was here yesterday." / "I will not remember this tomorrow." | Terminal display; legible hold; no voice-over |
| ~1:10–1:20 | ON-SCREEN (UI) | Ticket: "Orphan process / artifact / non-critical" | UI insert; readable |

**No spoken dialogue in this scene.**

---

## Generation Strategy
Use separate clips per shot. Hard cuts only. Locked or near-locked camera throughout — Ada's routine precision should read in the camera language.

### Motion Lock Vocabulary
- `camera locked on tripod`
- `no pan, no tilt, no zoom`
- `no handheld shake`
- `subject nearly still`
- `only natural micro-movements`
- `text remains sharp and readable throughout`

### Negative Constraints
`no glitch effects, no stylized sci-fi neon, no hologram UI, no robotic imagery, no transition effects, no chromatic aberration`

---

## Continuity + Look (Locked)
- **Ada:** 32, dark brown tied hair, light olive skin, restrained expression, gray/navy wardrobe, badge lanyard, clipboard or rugged tablet
- **Environment:** server room — cool fluorescent overheads, blue rack spill, black aisles, raised floor or polished concrete, no fog or sci-fi gimmicks
- **Terminal 4:** monitor on, `note_to_self_003.txt` visible in monospace white on black
- **Camera language:** controlled, locked, procedural — matches Ada's efficiency

---

## Audio Plan
1. Continuous server fan bed (low-mid frequency)
2. Ada footsteps on concrete
3. Keyboard taps (ticket logging)
4. When she reads the note: ambient drops ~10–15%; returns after she dismisses
5. Final hold: cursor blinks; no music; pure environment

---

## Clip Plan

### Clip 01 — Aisle Establish
- **TC:** 0:00–0:08
- **Prompt:**
`Wide shot of server room interior, long aisle of black rack servers with cool blue LED status lights, fluorescent overhead strips, Ada (32, dark brown tied hair, light olive skin, gray-navy practical wardrobe) entering from frame left with clipboard and badge lanyard, walking slowly with professional attention. Camera locked on tripod, no pan no tilt no zoom, no handheld shake, realistic enterprise infrastructure, grounded indie thriller realism, subtle 35mm grain, no sci-fi glow effects.`

### Clip 02 — Checklist Insert
- **TC:** 0:08–0:12
- **Prompt:**
`Close insert of rugged tablet in Ada's hands showing a maintenance checklist with several items already checked off, cool monitor light, clipboard texture detail, camera locked on tripod, no pan no tilt no zoom, subject nearly still, only natural micro-movements, realistic operational UI, no stylized graphics.`

### Clip 03 — Ada Tracking to Terminal 4
- **TC:** 0:12–0:22
- **Prompt:**
`Medium tracking shot following Ada moving from one rack to the next along the server aisle, checking rack labels, routine professional motion. Camera locked on tripod or very slow controlled dolly forward, no handheld shake, cool blue ambient rack light, realistic server room atmosphere, subtle 35mm grain.`

### Clip 04 — Terminal 4 Discovery (OTS)
- **TC:** 0:22–0:28
- **Prompt:**
`Over-the-shoulder shot behind Ada at Terminal 4 workstation, monitor clearly shows a text editor with header note_to_self_003.txt open, white monospace text visible, Ada's posture shifts subtly from routine to arrested attention. Camera locked on tripod, no pan no tilt no zoom, cool fluorescent server room light, realistic terminal interface, text legible, no visual effects.`

### Clip 05 — Ada Eyes (Reading)
- **TC:** 0:28–0:33
- **Prompt:**
`Close-up of Ada's face, eyes scanning terminal screen text, a micro-pause in breath, half a second longer than routine. Camera locked on tripod, no pan no tilt no zoom, no handheld shake, cool blue-white monitor spill on olive skin, restrained indie thriller performance, realistic skin texture, shallow depth of field.`

### Clip 06 — Terminal Text Insert
- **TC:** 0:33–0:40
- **Prompt:**
`Static close-up of black terminal screen with white monospace text clearly readable: "I was here yesterday." on one line, then "I will not remember this tomorrow." on the next. Text already present, not animating. Camera locked on tripod, no pan no tilt no zoom, high contrast black and white, text legible on phone in one pass, no glitch effects, no distortion.`

### Clip 07 — Ada Closes Window
- **TC:** 0:40–0:45
- **Prompt:**
`Medium profile shot of Ada reaching forward and closing the text file on the terminal with a neutral expression, technical decision without drama. Camera locked on tripod, no pan no tilt no zoom, cool server room light, only natural micro-movements, realistic gesture, subtle 35mm grain.`

### Clip 08 — Ticket UI Insert
- **TC:** 0:45–0:55
- **Prompt:**
`Static close-up of ticketing interface on monitor with clearly readable fields being filled: Status showing "artifact", Priority showing "non-critical", Action field showing "cleanup", cursor completing the entry. Camera locked on tripod, no pan no tilt no zoom, realistic operational enterprise UI, monitor glow, text legible throughout, no decorative effects.`

### Clip 09 — Ada Exits Aisle
- **TC:** 0:55–1:02
- **Prompt:**
`Wide shot of server room aisle, Ada walks out of frame toward exit, receding, routine posture. Camera locked on tripod, no pan no tilt no zoom, cool blue ambient, no music implied in image, realistic server infrastructure remains visible.`

### Clip 10 — Terminal Hold (Cursor Blinks Alone)
- **TC:** 1:02–1:15
- **Prompt:**
`Static medium close-up of Terminal 4 monitor with the text file now closed, single cursor blinking on the prompt line with no one at the keyboard, empty chair edge at bottom of frame, server room continues behind. Camera locked on tripod, no pan no tilt no zoom, completely still, only the cursor blinks, no other animation, cool blue-white monitor light, no visual effects, hold for full duration.`

---

## Assembly Notes
- Hard cuts only throughout
- Clip 10 (cursor hold) is the scene's emotional punctuation — do not shorten
- All text inserts must be legible on phone in one pass
- If any rack or UI detail breaks continuity with Scene 00, regenerate

## Acceptance Test
Pass if viewer understands after one watch:
1. Ada's work here is routine and controlled
2. Something was there that shouldn't be
3. She classified it and moved on — and the machine did not stop

<!-- VO_TIMING_START -->
## VO Lines + Timings (Embedded)

_Source: `production/vo-script.md`, Scene 01. Runtime target: 1:45–2:15_

| TC | Speaker | Line | Delivery |
|----|---------|------|----------|
| ~0:30–0:40 | CORVUS-TEXT | "I was here yesterday." / "I will not remember this tomorrow." | terminal display; legible |
| ~1:10–1:20 | ON-SCREEN | Ticket: "Orphan process / artifact / non-critical" | UI insert |
<!-- VO_TIMING_END -->

