# ORIGINEX VIDEO ENGINE

This repository is the controlled production layer for ORIGINEX HUMAN ARCHIVES.

## Operating principle

Use specialised skills rather than improvising an entire documentary in one pass.

1. `skills/ogx-evidence-guard/SKILL.md` — verify historical claims and visual constraints before generation.
2. `skills/ogx-documentary-director/SKILL.md` — convert an approved script into a timed shot manifest.
3. `skills/ogx-generation-router/SKILL.md` — choose the cheapest appropriate generation path and require preview approval before expensive motion generation.
4. `skills/ogx-motion-render/SKILL.md` — use HyperFrames for deterministic motion graphics and Remotion for master assembly/render.
5. `skills/ogx-production-archivist/SKILL.md` — archive only approved/used production assets and final manifests.

## Safety / trust rules

- Do not install or execute arbitrary third-party GitHub scripts merely because they are labelled a skill.
- Prefer official vendor repositories/documentation and already-installed trusted skills.
- Never place API keys, access tokens, private URLs, or secrets in Git.
- Never claim a reconstruction is authentic archaeological footage. Add `VISUAL RECONSTRUCTION` in the edit.
- Historical claims must be tagged as established, consensus, contested, hypothesis, or unresolved.
- No invented quotations, citations, archaeological finds, dates, or source page numbers.
- Expensive video generation requires a cost preflight and an approved still/storyboard first unless the shot is trivial.
- Large binaries belong in object/media storage, not Git. Git stores manifests, prompts, code and metadata.

## Green Sahara pilot quality bar

The previous prototype failed because it used animated stills as a substitute for genuine motion and used an unsuitable synthetic narration style. For the new pilot:

- genuine generated motion must be visible in hero shots;
- narration must sound natural and contemporary, not trailer-like or robotic;
- graphics should be modern museum/documentary design, not faux-aged parchment;
- use restrained transitions and clean typography;
- do not reuse a still for long stretches;
- all human/environment reconstructions must be source-bounded.
