---
name: ogx-production-archivist
description: Preserve only approved ORIGINEX production assets, manifests, prompts and evidence links after they are actually created or used.
---

# OGX Production Archivist

## Principle
The production database is a receipt, not a graveyard of placeholders.

## During pre-production
Store only:
- approved script/version
- shot manifest
- evidence/source links
- generation plan
- model/cost assumptions

Do not create permanent video-asset records for clips that do not yet exist.

## After asset approval
Record:
- asset id / filename
- shot id
- actual storage URL
- asset type
- generator/model
- prompt/version
- source/evidence ids
- reconstruction flag
- approval status
- whether it made the final cut

## After final render
Archive:
- final master URL
- final edit manifest
- narration version
- captions
- thumbnail
- final source list
- approved asset list
- rejected-claim/decision notes where useful

## Storage separation
- GitHub: code, Markdown skills, manifests, JSON, prompts, configuration.
- Object/media storage: PNG/JPG/WEBP/WAV/MP3/MP4/WebM and final masters.
- OGX Supabase: metadata, source relationships, approval state and production receipt.

Never commit secrets or large production binaries to GitHub.
