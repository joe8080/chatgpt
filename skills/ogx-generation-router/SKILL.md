---
name: ogx-generation-router
description: Route ORIGINEX documentary shots to the most appropriate image/video model while controlling credits, retries, consistency and historical accuracy.
---

# OGX Generation Router

## Core rule
Do not jump directly from text prompt to expensive final video unless the shot is trivial.

Preferred flow:
1. Evidence Guard validates the shot.
2. Generate or source a still/storyboard.
3. Human/director approves composition.
4. Run credit/cost preflight.
5. Animate with the lowest-cost model that can meet the requirement.
6. Escalate model only after a defined failure.

## Higgsfield routing
Based on the official Higgsfield skill guidance and connected tool behavior:
- `seedance_2_0`: preferred for image-to-video/reference continuity.
- `kling3_0_turbo`: useful for economical text-to-video or simple single-frame animation.
- `kling3_0`: use when multi-shot/reference complexity justifies it.
- `cinematic_studio_3_0`: reserve for hero shots where cinematic quality visibly matters.

Always call cost estimation before expensive jobs.

## Reference-first rules
Use first/last frames where change over time is the point:
- desert -> humid Sahara
- wet lake -> shrinking lake -> dry basin
- Green Sahara -> present desert

Use a stable start image for human scenes to control clothing, tools, anatomy and landscape.

## Retry budget
- Draft/model test: maximum 2 attempts on the same model.
- If failure is structural, change model or reference strategy rather than repeating the same prompt.
- Never burn premium credits trying to repair a bad composition that should have been fixed at still-image stage.

## Model-arbitrage principle
Higgsfield is primary for cinematic historical motion. OpenArt/CreativeClaw may be used where the user's existing subscription/model access provides a better value or a model is demonstrably better at the shot.

## Audio
Do not rely on model-generated dialogue/audio for documentary B-roll. Narration, sound design and music are separate layers unless native sound is specifically useful.

## Quality rejection conditions
Reject/regenerate if:
- motion is only a pan/zoom over a static image when genuine motion was requested;
- bodies/faces deform noticeably;
- material culture becomes anachronistic;
- Sahara becomes tropical rainforest;
- pyramids/camels/horses/modern objects appear without support;
- the camera behaves like a game trailer rather than a documentary;
- lighting or colour grade breaks continuity with adjacent shots.
