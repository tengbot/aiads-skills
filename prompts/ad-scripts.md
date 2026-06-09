# Ad Script Prompts

Prompt patterns for turning product briefs into ad scripts.

Main site: https://aiads.im

## Direct response script

```text
Product: {{product}}
Audience: {{audience}}
Pain point: {{pain_point}}
Benefit: {{benefit}}
Proof point: {{proof_point}}
Offer: {{offer}}
Platform: {{platform}}
Duration: {{duration}}

Write a direct response video ad script.
Include:
- hook
- problem
- product reveal
- demo moment
- proof or reason to believe
- objection answer
- CTA
- captions
- voiceover
- scene notes

Do not invent proof, reviews, or guaranteed results.
```

## UGC script

```text
Product: {{product}}
Audience: {{audience}}
Common objection: {{objection}}
Benefit: {{benefit}}
Creator persona: {{creator_persona}}
Platform: {{platform}}

Write a UGC-style ad script.
Make it sound like a creator talking to a friend.
Return 15 second and 30 second versions.
```

## Product demo script

```text
Product: {{product}}
Feature: {{feature}}
Use case: {{use_case}}
Audience: {{audience}}
Offer: {{offer}}

Write a product demo ad script.
Structure:
Hook -> Demo -> Benefit -> CTA
Return captions and scene directions.
```
