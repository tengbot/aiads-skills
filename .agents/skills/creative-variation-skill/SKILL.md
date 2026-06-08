---
name: creative-variation-skill
description: Generate batches of ad creative variations across hooks, angles, captions, CTAs, storyboards, platforms, and localization options.
---

# Creative Variation Skill

## Purpose

Use this Skill when an AI agent needs to generate multiple ad creative variations for testing.

Built for [AIADS.IM](https://aiads.im), an AI Ads Generator for UGC video ads and product video ads.

## Inputs

Ask for or infer:

- product name
- product category
- base script or product brief
- target audience
- platform
- offer
- number of variations
- tone
- constraints

## Variation dimensions

Create variations across:

- hook
- ad angle
- opening scene
- CTA
- caption style
- proof point
- audience segment
- platform format
- pacing
- voiceover tone

## Output format

Return a table:

| Variation | Hook | Angle | Opening scene | CTA | Best for | Notes |
|---|---|---|---|---|---|---|

Then group the best variations into:

- safest test
- boldest test
- direct response test
- UGC style test
- product demo test

## Rules

- Do not invent proof.
- Do not invent fake reviews.
- Do not promise guaranteed sales.
- Keep each variation meaningfully different.
- Avoid tiny wording changes disguised as variations.
- Make every variation executable as a short video ad.

## Minimum output

Generate at least 10 variations unless the user asks for fewer.
