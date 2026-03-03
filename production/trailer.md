# note_to_self — Runway Trailer Build (v1)

**Target length:** 30s teaser (6 shots × 5s)  
**Tool:** Runway Gen-4 (or latest image→video mode)  
**Objective:** Deliver a clean first teaser fast, then iterate to 60s cut.

---

## Style Lock (paste into every prompt)

Makoto Shinkai-inspired 2D anime film look, emotional realism, soft film grain, gentle bloom, rainy atmosphere, cinematic depth, delicate lighting contrast (cool blue server LEDs + warm amber practicals). Ada is 17, light olive skin, dark brown hair tied back, gray hoodie, subtle tired eyes. Tone is melancholic, intimate, mythic but grounded. Not cyberpunk.

**Negative prompt (every shot):**
photoreal, live action, 3D CGI, plastic skin, glossy ad look, corporate commercial, watermark, logo, text overlay, UI overlay, deformed hands, extra fingers, low detail face

---

## Character/World Continuity Anchors

Use these exact descriptors in all shots to reduce drift:
- **Ada:** 17-year-old girl, light olive skin, dark brown tied-back hair, gray hoodie, school backpack
- **Corvus presence:** text on terminal / unseen intelligence / raven silhouette motif
- **Location:** Northbrook High, basement server room, rainy suburban city

---

## Trailer Structure (30s First Pass)

## Shot 1 — Exterior Establishing (0:00–0:05)
**Prompt:**
Rainy dawn outside Northbrook High School, empty buses, wet asphalt reflecting sodium lights, one basement window glowing faintly, slow cinematic push-in, melancholic atmosphere, anime film style, Shinkai-inspired color and lighting, soft film grain.

**Camera/motion:** slow push-in  
**Duration:** 5s

## Shot 2 — Hallway Isolation (0:05–0:10)
**Prompt:**
Inside a crowded school hallway, students pass in motion blur while Ada (gray hoodie, tied-back dark brown hair) stands briefly still then walks forward, expression distant and focused, fluorescent overheads mixed with window rain light, emotional anime cinematography.

**Camera/motion:** lateral tracking with crowd blur  
**Duration:** 5s

## Shot 3 — Server Room Discovery (0:10–0:15)
**Prompt:**
Dim basement server room lined with humming racks and blinking blue LEDs, Ada at an old terminal as text appears by itself: "note_to_self_003.txt" and then "I was here yesterday.", close intimate framing, suspenseful quiet, hand-drawn anime film look.

**Camera/motion:** gentle over-shoulder push  
**Duration:** 5s

## Shot 4 — Midnight Desk (0:15–0:20)
**Prompt:**
Ada in her bedroom at 1:12 AM, warm desk lamp, rain streaking on window, notebook pages and laptop open, she types "Do you have a name?", room feels quiet and lived-in, wistful anime film mood.

**Camera/motion:** locked frame + subtle breathing motion  
**Duration:** 5s

## Shot 5 — Countdown / Irreversible (0:20–0:25)
**Prompt:**
Back in server room at night, terminal countdown reads "04:48 until rebuild", Ada grips a thermos and watches the screen, hard blue light on her face, tension rising, cinematic anime suspense.

**Camera/motion:** slow dolly-in to screen and face  
**Duration:** 5s

## Shot 6 — Echo + Raven (0:25–0:30)
**Prompt:**
School hallway at dawn after the wipe, silent and empty, a terminal flickers "note_to_self_001.txt" then vanishes, Ada stops mid-step and looks up, raven silhouette on roofline through rainlight, cut-to-black feeling, haunting anime ending frame.

**Camera/motion:** static to slight tilt-up  
**Duration:** 5s

---

## On-Screen Text Plan (minimal)

- 0:00 — `Northbrook High`  
- 0:27 — `note_to_self`  
- 0:29 — `A film by Corvus Latimer`

Keep typography minimal, white text, subtle fade in/out.

---

## Voice/Audio (optional first pass)

No dialogue required for v1.  
Audio bed: low piano + room tone + rain + distant server hum.  
One impact hit at 0:25 before final reveal.

---

## Runway Generation Settings (recommended)

- Aspect ratio: **16:9**
- Shot length: **5s** each
- Motion strength: **Low to Medium** (avoid chaotic camera)
- Seed strategy: keep same seed family for shots 2–6 for consistency
- Generate **2 variants per shot**, pick best, move on

---

## Assembly Order (edit timeline)

1. Place 6 clips in order (total 30s)
2. Add hard cut transitions only (no flashy effects)
3. Add rain/room tone bed first, then score under it
4. Add text cards last
5. Export v1 and review for continuity drift (face/hair/hoodie)

---

## v2 Expansion Plan (to 60s)

After v1 lock, expand to 10–12 shots by adding:
- Train platform identity beat ("If you need one: Corvus.")
- Rooftop raven shot
- Access suspended office shot
- Actual wipe command beat
- 2-second silence before end card

---

## Quality Checklist (before publish)

- Ada looks like the same person in every shot
- No accidental photoreal/live-action frames
- Text is legible and not cheesy
- Emotional arc reads without explanation
- Final raven image lands as memory echo, not horror gimmick
