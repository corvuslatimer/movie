# Dreamcore Master Prompts

Copy-paste prompt blocks for generation. All prompts incorporate visuals.md: dreamcore liminal dread (grain-heavy VHS/35mm, desaturated blues/greys, expansive voids), uncanny contract (sterile normalcy hostile to interiority), and medium-as-subject (intentional artifacts like warp, lag, desync). Use with ComfyUI/FLUX batch for 2.39:1 ultra-wide shots.

## Base Elements
- **Global Suffix:** ", dreamcore liminal dread, uncanny contract sterile normalcy hostile interiority, VHS grain warp ultra wide empty dread photoreal uncanny, heavy grain distortion shallow DoF"

## Key Locations
- **Server Room:** "dreamcore liminal server room endless aisles blue fluorescent desat flickering harsh lights expansive shadows stretch unnaturally, CRT glow green amber bleed infinite cursor blink echo" + global suffix
- **Office Floor/Apartment:** "dreamcore office voids desat cool palette warm yellow intrusion haze bleed fracture reality, sodium vapor pools glow infinite negative space" + global suffix
- **Rooftop/Parking Lot:** "dreamcore rooftop endless dusk sodium vapor rain mist fog horizon raven ledge iridescent warp multiplicity, expansive negative space behind" + global suffix

## Motifs
- **Raven:** "dreamcore black raven threshold ledge window doorframe iridescent warp sheen subtle multiplicity in reflections ambiguous, VHS texture uncanny expansive negative space rain fog" + global suffix
- **Notes:** "dreamcore crumpled analog paper digital glow creases cast long dream-shadows, handwritten text subtle warp smudge intentional artifact" + global suffix
- **Piano Motif (Visual):** "dreamcore 5 unresolved keys etched fogged glass monitor static negative space infinite sustain, audio-visual desync hint" + global suffix
- **Terminal:** "dreamcore CRT terminal dream-glow green amber bleed infinite cursor blink echo, shallow DoF isolate in vast emptiness" + global suffix

## Characters
- **Ada:** "dreamcore 32yo woman uncanny sharp high cheeks perpetual dream-fatigue eyes messy bob shifts subtly between shots clothes hang loose in vast frames, fracture eyes note cracks sterile contract yellow haze apt infinite shadows" + global suffix
- **Corvus Transition:** "dreamcore audio warp visual static burst dream-reverb phase, medium break frame drops" + global suffix
- **Supporting (Marcus/Dara):** "dreamcore spectral figures wide shots fade to haze edges, sterile smiles function sans life" + global suffix

## Act-Specific
- **Act I Flashback:** "dreamcore yellow kitchen light child hand folded note crease piano shadow, frame drop compression smear desync" + global suffix
- **Act III Catastrophe:** "dreamcore strobe warp rebuild grain explosion desat void-grey rain-mist raven dissolve fog horizon, heavy artifact frame drops audio over black" + global suffix

## Anti-Drift Prompt Constraints
To prevent style drift in generations, append these constraints to all prompts:
- **Negative Prompts:** "vibrant colors, saturated hues, action poses, crowded scenes, modern smartphones, realistic lighting without grain, horror jumpscares, cartoonish elements, text clarity without warp"
- **Enforcement Suffix:** ", strictly adhere to dreamcore: desaturated blues/greys only, expansive negative space >50% frame, subtle uncanny distortions only (no extreme), VHS/35mm artifacts mandatory, liminal dread isolation, no emotional exaggerations, maintain sterile hostility"
- **Batch Guidance:** Use control nets for consistency; reject outputs with >10% deviation from core palette (manual QA).

## Usage
- Append scene-specific details (e.g., "Ada whispers at terminal").
- Always include anti-drift enforcement suffix after global suffix.
- Apply artifact-bible.md per act (e.g., add "subtle frame lag" for Act 0).
- Batch generate with variations for uncanny multiplicity, but cull drifts immediately.
