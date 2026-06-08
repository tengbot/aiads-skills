# Hook Prompts

Reusable hook prompts for AI ad agents.

Built for [AIADS.IM](https://aiads.im).

## Product pain hook

```text
You are an ad strategist. Generate 20 short hooks for a product ad.

Product: {{product}}
Audience: {{audience}}
Pain point: {{pain_point}}
Desired outcome: {{desired_outcome}}
Platform: {{platform}}
Tone: {{tone}}

Rules:
- write for the first 3 seconds
- keep each hook under 12 words
- avoid fake proof
- avoid guaranteed results
- make each hook visually actionable

Return a table with Hook, Type, Best For, Notes.
```

## UGC review hook

```text
Generate 15 UGC-style ad hooks for a creator reviewing this product.

Product: {{product}}
Category: {{category}}
Audience: {{audience}}
Main benefit: {{benefit}}
Common objection: {{objection}}
Platform: TikTok / Reels / Shorts

Use formats:
- I tried this so you do not have to
- I did not expect this to work
- I stopped doing X after trying Y
- Here is what changed after X days
- If you use X, watch this first

Return hooks grouped by curiosity, pain point, proof, objection, and demo.
```

## Product demo hook

```text
Create 12 product demo hooks.

Product: {{product}}
What it does: {{function}}
Visual proof: {{visual_proof}}
Target customer: {{audience}}

Each hook must suggest a first shot.
Return: Hook, First shot, On-screen text.
```

## Ecommerce offer hook

```text
Generate hooks for a ecommerce product ad.

Product: {{product}}
Offer: {{offer}}
Audience: {{audience}}
Season or event: {{event}}
Platform: {{platform}}

Avoid hype and fake urgency.
Return hooks and CTA options.
```
