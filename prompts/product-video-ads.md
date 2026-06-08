# Product Video Ads Prompts

Prompt patterns for turning product information into short ad video briefs.

Main site: https://aiads.im

## Product video angle prompt

```text
Product: {{product}}
Category: {{category}}
Audience: {{audience}}
Main benefit: {{benefit}}
Pain point: {{pain_point}}
Proof point: {{proof_point}}
Offer: {{offer}}
Platform: {{platform}}
Duration: {{duration}}

Create 6 product video ad angles.
For each angle, include:
- angle name
- first shot
- hook
- product reveal
- proof or demo moment
- CTA
- notes for video generation

Avoid fake reviews, fake proof, and guaranteed results.
```

## Product image to video prompt

```text
Product image description: {{image_description}}
Product name: {{product}}
Selling point: {{selling_point}}
Audience: {{audience}}
Platform: {{platform}}
Video style: {{style}}
Duration: 15 seconds
Aspect ratio: 9:16

Create a product image to video ad storyboard.
Return:
- scene number
- duration
- visual action
- on-screen text
- voiceover
- product focus
- transition
- CTA
```

## Product demo script prompt

```text
Write a short product demo video ad.

Product: {{product}}
Use case: {{use_case}}
Feature: {{feature}}
Benefit: {{benefit}}
Audience: {{audience}}
Objection: {{objection}}
Offer: {{offer}}

Structure:
Hook -> Demo -> Benefit -> Objection answer -> CTA

Return 15s and 30s versions.
```
