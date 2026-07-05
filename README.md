# video-script-skill

`video-script-skill` helps generate short-video scripts, shot lists, voiceover copy, captions, and publishing packages.

## What It Is

It is a reusable workflow for converting real material into publishable video planning documents.

## Use Cases

- Product demo scripts.
- AI workflow explanation videos.
- Project recap videos.
- Short educational clips.
- Voiceover and caption package generation.
- Documentary-style explainers that need reference breakdown, evidence tables, visual masters, and audiovisual QA.
- Voiceover-driven videos that require a sentence-level director table, dedicated asset package, sound plan, editor handoff package, and final polish gate.

## Install

```bash
mkdir -p ~/.codex/skills
cp -R video-script-skill ~/.codex/skills/video-script-skill
```

## Usage

```text
Use video-script-skill to make a 90-second script from this project demo note, with shot list and voiceover.
```

## Not Public

No copyrighted media, private footage, licensed music, raw recordings, customer data, API keys, or account exports are included.

## Quality Gates

For dense explainer videos, do not stop at a script. Produce the reference breakdown, evidence table, shot plan, source list, and QA notes before calling a draft ready for review.

For real voiceover videos, do not treat reused assets or a script-rendered preview as final. Build a dedicated asset package for the current voiceover, document each asset's beat-level purpose, and hand off stable media, captions, source tables, and QA notes for editor polish.

## Local Private Data

```bash
export VIDEO_ASSET_ROOT=/path/to/private-assets
```

Reference private assets by placeholder names in public docs.
