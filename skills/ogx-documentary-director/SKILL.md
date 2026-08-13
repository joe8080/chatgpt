---
name: ogx-documentary-director
description: Convert an approved ORIGINEX narration script into a modern documentary shot manifest with pacing, evidence labels, real archaeology, maps, motion graphics and AI reconstruction shots.
---

# OGX Documentary Director

## Output
Create a shot manifest. Each shot must include:
- `shot_id`
- `start_time`
- `end_time`
- `narration_excerpt`
- `visual_type` = real_archive | archaeology | map | motion_graphic | reconstruction_video | reconstruction_still | source_card
- `visual_direction`
- `motion_direction`
- `evidence_status`
- `source_ids`
- `reconstruction_label`
- `generator_route`
- `approval_status`

## Modern visual language
- Contemporary premium documentary, not faux-antique design.
- Clean dark/navy/charcoal layouts, sharp typography, restrained gold accents where brand appropriate.
- Real archaeological imagery should feel primary, not buried under effects.
- Use parallax, map motion, clean data transitions and genuine video motion.
- Avoid fake film scratches, excessive sepia, parchment backgrounds, cheesy zooms and slideshow pacing.

## Pacing
- Visual state changes roughly every 3-7 seconds, but avoid frantic cuts.
- Hero reconstruction shots: 5-10 seconds.
- Source cards: 2-5 seconds unless narration requires longer.
- Maps should animate direction, time or geography rather than remain static.
- Use visual contrast: wide environment -> evidence close-up -> map/diagram -> human-scale reconstruction -> source receipt.

## Motion requirement
A shot tagged `reconstruction_video` must contain genuine subject/environmental motion, not only a digital pan over a still.

Examples of acceptable motion:
- water ripples and reed movement
- natural walking/fishing activity
- aerial camera travel over landscape
- shoreline drying over time
- clouds/rain systems moving
- fish swimming through water

## Green Sahara opening target
The first five minutes should feel like a current Netflix/BBC/PBS digital documentary, not a school slideshow:
1. stark present Sahara
2. archaeological discovery/evidence
3. large Nile perch visual
4. dramatic but scientifically restrained desert-to-savanna transformation
5. monsoon/precession motion graphic
6. Green Sahara aerial
7. Mega-Chad map/scale visualization
8. regional chronology
9. return to Gobero and transition toward Kiffian people
