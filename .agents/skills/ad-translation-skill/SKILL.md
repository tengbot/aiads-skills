---
name: ad-translation-skill
description: Localize ad scripts, captions, CTAs, voiceover drafts, and video creative notes for different markets.
---

# Ad Translation Skill

## Purpose

Use this Skill when an AI agent needs to adapt ad creatives for another language, market, or platform culture.

Built for [AIADS.IM](https://aiads.im), an AI Ads Generator for UGC video ads and product video ads.

## Inputs

Ask for or infer:

- source script
- source language
- target language
- target market
- platform
- product category
- brand voice
- offer
- compliance limits

## Output

Return:

1. localized hook options
2. localized ad script
3. caption lines
4. CTA variants
5. voiceover notes
6. cultural notes
7. words or claims to avoid

## Rules

- Do not translate word for word if it sounds unnatural.
- Keep hooks short and native to the target platform.
- Keep claims compliant with the target market.
- Preserve the selling point and offer.
- Avoid slang unless the user asks for it.
- Never invent proof, testimonials, awards, or certifications.

## Example output structure

```text
Target market: Mexico
Tone: friendly, direct, TikTok-native

Hook options:
1. ¿Tu rutina de cuidado tarda demasiado?
2. Probé esto por 7 días y aquí está el cambio.
3. Si compras skincare online, mira esto primero.

Localized CTA:
- Pruébalo hoy
- Mira cómo funciona
- Consigue el tuyo aquí
```
